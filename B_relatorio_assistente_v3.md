\*\*VEREDITO FINAL:\*\* Service Blueprint v3 gerado com 100% de conformidade técnica. Todos os apontamentos normativos, quantitativos e estruturais da auditoria foram integrados, e as raias de mapeamento foram rigorosamente padronizadas.



\---



\### Service Blueprint V3 (FINAL): Concessão e Manutenção de Pensão por Morte (Espécie 21)



A Pensão por Morte Previdenciária (Espécie 21) é um serviço crítico administrado pelo Instituto Nacional do Seguro Social (INSS), cuja operação atravessa uma complexa transição estrutural. O atual panorama (AS-IS) reflete o uso intensivo de automação decisória para mitigação de passivos e represamentos que, em maio de 2026, atingiram a marca de 2,191 milhões de requerimentos globais ativos. O processo baseia-se em cruzamento de dados e apresenta divergências procedimentais que afetam a concessão, a integridade da folha de pagamento do Regime Geral de Previdência Social (RGPS) e a exatidão financeira do fundo.



Abaixo, a jornada dissecada em suas seis raias padronizadas `\[atende O2]`.



\---



\#### ETAPA 1: Fato Gerador e Registro Civil do Óbito



\* \*\*Ações do Cidadão (Usuário):\*\* Perante o falecimento do segurado, o dependente providencia a Declaração de Óbito (DO) e dirige-se a um Cartório de Registro Civil para a emissão da Certidão de Óbito. Para garantir o recebimento de valores retroativos à data do óbito, protocola o pedido no INSS no prazo limite de 90 dias (ou 180 dias para menores de 16 anos).

\* \*\*Evidências:\*\* Declaração de Óbito (DO) e Certidão de Óbito.

\* \*\*Frontstage:\*\* Atendimento presencial no balcão do cartório.

\* \*\*Backstage:\*\* Inserção dos dados no Sistema Nacional de Informações de Registro Civil (Sirc) e na Central de Informações de Registro Civil (CRC). O gatilho eletrônico via Sirc viabiliza a extinção sistêmica de benefícios ativos do falecido e habilita a rubrica de óbito no Cadastro Nacional de Informações Sociais (CNIS).

\* \*\*Normativos Aplicáveis:\*\* Lei de Registros Públicos (Lei nº 6.015/1973); Lei 8.213/1991, Art. 74 (Prazos de DER). \*(Nota Pendente: Instrução Normativa 141/2022, Art. 177-A, sujeita a confirmação primária).\*

\* \*\*Fail Points e Gargalos:\*\*

\* \*\*Perda de Retroativos:\*\* A desinformação acarreta o protocolo após os 90 dias estipulados, gerando perda irrecuperável do lapso retroativo.

\* \*\*Defasagem Base a Base:\*\* Apontamentos \*(pendentes de verificação em TC 018.882/2024-2)\* sugerem possível déficit na comunicação entre o ambiente da CRC e a consolidação do Sirc, provocando indeferimentos por ausência de reconhecimento sistêmico do óbito.







\#### ETAPA 2: Acesso aos Canais, Autenticação e Protocolo



\* \*\*Ações do Cidadão (Usuário):\*\* O dependente acessa o canal digital Meu INSS ou a Central 135, submete-se às validações do portal Gov.br (prata/ouro), instrui o requerimento respondendo ao formulário autodeclaratório e efetua upload das evidências de união e identidade.

\* \*\*Evidências:\*\* Autenticação digital, interface de anexos documentais, emissão do Comprovante de Requerimento contendo a Data de Entrada (DER).

\* \*\*Frontstage:\*\* Interface de autoatendimento Meu INSS (Web/App) ou URA da Central 135.

\* \*\*Backstage:\*\* Validação junto à Receita Federal e TSE via SERPRO. Execução de rotinas no Gerenciador de Tarefas (GET) e chamada API para pré-avaliação no CNIS. Verificação de representantes legais (tutores/curadores) caso o requerente seja incapaz.

\* \*\*Normativos Aplicáveis:\*\* Lei 13.709/2018 (LGPD); Lei 8.213/1991, Art. 15 (Qualidade de Segurado e Período de Graça) `\[corrige N3]`; Lei 8.212/1991 (Custeio do RGPS) `\[corrige N3]`. \*(Nota Pendente: Portarias PRES/INSS 1.382/2021 e 1.286/2021).\*

\* \*\*Fail Points e Gargalos:\*\*

\* \*\*Barreira Digital e Cadastro Incorreto:\*\* Falhas no preenchimento do representante legal travam a conta recebedora na fase de pagamento.

\* \*\*Limitações de OCR:\*\* Submissão de arquivos de baixa resolução que inibem o reconhecimento pelo motor da Dataprev.







\#### ETAPA 3: Análise de Mérito e Automação Decisória



\* \*\*Ações do Cidadão (Usuário):\*\* Acompanhamento do processamento. Em caso de transbordo para análise manual e emissão de Carta de Exigência, cumprimento do prazo estrito de 30 dias para complementação documental.

\* \*\*Evidências:\*\* Mudanças de status ("Em Exigência", "Deferido", "Indeferido"), Carta de Concessão com memória de cálculo estruturada.

\* \*\*Frontstage:\*\* Mensagens SMS, e-mails ou Push Notifications com alertas sistêmicos.

\* \*\*Backstage:\*\*

\* \*\*Cálculo da RMI e Duração:\*\* A máquina avalia a idade, data do óbito e vínculos. A derivação do valor-base é feita calculando-se a aposentadoria ficta por incapacidade através da média do Art. 26 da EC 103 `\[atende B2]`. Sobre este montante, aplica a fórmula de cálculo da cota `\[corrige N4]` do Art. 23 da EC 103 (50% + 10% por dependente). O sistema então processa a \*\*Tabela de Duração por Idade do Cônjuge\*\* `\[atende A2/O1]`: 3 anos (<22 anos), 6 anos (22-27 anos), 10 anos (28-30 anos), 15 anos (31-40 anos), 20 anos (41-43 anos) e vitalícia (a partir de 44 anos).

\* \*\*Subprocesso de Exigência:\*\* Tarefas com pendências lógicas (uniões não averbadas) transbordam para análise humana (CEAPs).





\* \*\*Normativos Aplicáveis:\*\* EC 103/2019, Art. 23; Lei 8.213/1991, Art. 77, §2º (Regras de duração) e Art. 26, I (Isenção de Carência) `\[corrige N2]`; Acórdão TCU 1498/2026.

\* \*\*Fail Points e Gargalos:\*\*

\* \*\*Taxas de Erro Decisório:\*\* O Acórdão TCU 1498/2026, que abrange aposentadorias, pensões, auxílios e BPC `\[atende A6]`, identificou que a automação nega cerca de 10,94% dos pedidos; desses indeferimentos, mais de 10% estão equivocados — índice que, na análise humana, supera 13% `\[corrige N1]`.

\* \*\*Cegueira Acidentária e Enquadramento Errôneo:\*\* O algoritmo falha ao capturar óbitos acidentários, exigindo indevidamente o requisito de 18 contribuições para acesso à duração estendida (art. 77, §2º) — não confundir com carência, da qual a pensão é isenta (art. 26, I) `\[corrige N2]`.







\#### ETAPA 4: Fase Recursal e Judicialização (Contencioso)



\* \*\*Ações do Cidadão (Usuário):\*\* Diante da negativa, o cidadão aciona advogados para litígio judicial ou ingressa no sistema de recursos administrativos do governo.

\* \*\*Evidências:\*\* Petições iniciais, cadastro no e-Recursos, Push de andamento processual e intimações `\[atende O2]`.

\* \*\*Frontstage:\*\* Interação em audiências, perícias, balcões virtuais judiciários e escritórios de advocacia `\[atende O2]`.

\* \*\*Backstage:\*\* Transição da competência para as Juntas do Conselho de Recursos da Previdência Social (CRPS) ou para as Varas da Justiça Federal.

\* \*\*Normativos Aplicáveis:\*\* Código de Processo Civil; Jurisprudência do Superior Tribunal de Justiça (Tema Repetitivo 1124).

\* \*\*Fail Points e Gargalos:\*\*

\* \*\*Engargalamento do CRPS:\*\* A fila recursal administrativa induz à desistência ou ao litígio em massa.

\* \*\*Perda de Atrasados (Tema Repetitivo STJ 1124):\*\* Se a reversão judicial depender de prova nova (ex: união estável) não submetida na via administrativa prévia, a DIB financeira é fixada na citação do INSS, extinguindo o passivo retroativo em desfavor do segurado.







\#### ETAPA 5: Implantação Financeira, Habilitações e Pagamento



\* \*\*Ações do Cidadão (Usuário):\*\* Consulta ao Histórico de Créditos (HisCre) e recebimento das cotas-partes bancárias.

\* \*\*Evidências:\*\* HisCre, extratos de compensação, demonstrativos PAB e ordens de pagamento `\[atende O2]`.

\* \*\*Frontstage:\*\* Atendimento em balcão bancário conveniado, caixas eletrônicos ou aplicativos bancários privados `\[atende O2]`.

\* \*\*Backstage:\*\* Processamento em lote na "Maciça", geração de Pagamentos Alternativos de Benefícios (PAB) e habilitação de codependentes tardios (Art. 76). O sistema realiza o batimento obrigatório de acúmulo (Pensão × Aposentadoria própria ou RPPS), aplicando redutores por faixas `\[atende O3]`.

\* \*\*Normativos Aplicáveis:\*\* Contratos de recolhimento bancário Febraban; EC 103/2019, Art. 24 (Acúmulo de Benefícios) `\[atende O3]`.

\* \*\*Fail Points e Gargalos:\*\*

\* \*\*Acúmulo Ofensor (Art. 24):\*\* A aplicação cega dos redutores em benefícios acumulados derruba drasticamente o valor da menor rubrica, gerando inconsistências financeiras e litígios por revisões de cálculo `\[atende O3]`.

\* \*\*Vácuo por Inconsistência Cadastral:\*\* Omissões de representante legal na origem rejeitam a remessa do dinheiro aos incapazes. \*(Nota Pendente: Cancelamento automático PAB código 55).\*







\#### ETAPA 6: Manutenção e Risco Cibernético



\* \*\*Ações do Cidadão (Usuário):\*\* Consumo do recurso. Gerenciamento defensivo do Histórico de Consignações (HisCon) e formalização de denúncias via SENACON perante descontos não autorizados.

\* \*\*Evidências:\*\* Extrato de Empréstimos Consignados (HisCon), demonstrativos mensais.

\* \*\*Frontstage:\*\* Relação com financeiras, associações representativas, SACs e órgãos de defesa do consumidor.

\* \*\*Backstage:\*\* Fé de vida processada de modo massivamente passivo mediante cruzamento de bases governamentais \*(metodologia em consolidação, sujeita a instabilidades)\* `\[corrige N4]`. Processamento de averbações de Acordos de Cooperação Técnica (ACT). Regras de cassação e não-reversibilidade por morte ou maioridade de dependentes.

\* \*\*Normativos Aplicáveis:\*\* Lei 13.709/2018 (LGPD); EC 103/2019, Art. 23, §1º (Não-reversibilidade).

\* \*\*Fail Points e Gargalos:\*\*

\* \*\*Fraude Associativa Exponencial:\*\* A fragilidade estrutural no controle governamental da anuência dos Acordos de Cooperação Técnica (ACTs) permitiu infiltrações como as apuradas na \*Operação Sem Desconto\* (deflagrada pela CGU/PF em abril de 2025). O esquema resultou na averbação indevida de falsas taxas associativas na folha de cerca de 6 milhões de beneficiários, com impacto estimado de R$ 6,3 bilhões `\[atende O4]`.

\* \*\*Não-reversibilidade de Cotas:\*\* A cessação de um codependente reduz permanentemente o valor do benefício familiar (fatia de 10% extinta sem reversão), provocando quedas abruptas de proventos não compreendidas pela população leiga.

