Vou auditar isso com rigor. Antes de validar ou refutar as afirmações normativas e factuais, preciso verificar as mais críticas — especialmente as que dependem de eventos recentes (a suposta determinação do TCU de jun/2026, a fraude dos descontos associativos, o Tema 1.124 do STJ) e os números de fila. Deixe-me checar.Bom grounding sobre a fraude. Agora preciso verificar a afirmação mais crítica e recente do documento: a suposta determinação plenária do TCU de 10/06/2026 sobre o "robô negador" e o prazo de 180 dias.Agora vou verificar as regras normativas substantivas da pensão por morte (duração, carência, cotas pós-EC 103) para checar se o documento as representa corretamente.Verificação final dos pontos jurídicos específicos — o Tema do STJ e a natureza do dado da fila.Auditei a peça contra fontes primárias e secundárias verificáveis. O documento é bem estruturado e acerta o panorama geral (automação + CNIS sujo + judicialização + fraude associativa), mas contém \*\*erros factuais relevantes, imprecisões normativas que comprometem a base jurídica do blueprint, e omissões de backstage e de fail points que uma auditoria de controle externo não pode deixar passar\*\*. Abaixo, achado a achado, com trecho, correção e fonte. Marquei a gravidade para priorização.



\---



\## A. ERROS FACTUAIS E NORMATIVOS



\*\*A1 — \[ALTA] "Tema de Repercussão 1.124" do STJ está classificado errado e datado errado.\*\*

Trecho: \*"um contencioso massivo, que atingiu o Superior Tribunal de Justiça (STJ) sob o Tema de Repercussão 1.124 em 2026, discute os efeitos financeiros…"\*

Três erros: (i) "Tema de Repercussão" é nomenclatura do \*\*STF\*\* (repercussão geral); no STJ é \*\*Tema Repetitivo\*\* (recursos especiais repetitivos, art. 1.036 CPC). (ii) Não está "em discussão" — o STJ publicou o acórdão do Tema Repetitivo 1124 em 6/11/2025, com tese vinculante já fixada. (iii) Não é de 2026.

Pior, \*\*a direção da tese está invertida\*\*. O documento sugere que o segurado "não pode ser penalizado". A tese efetivamente fixada é, no cenário central, \*\*desfavorável\*\* ao segurado: quando a concessão se dá por prova nova não submetida ao INSS, os efeitos financeiros contam a partir da citação, e não da DER — com a ressalva (item 2.2) de que, se o INSS tinha o dever de oportunizar complementação e não o fez, a DIB pode ser fixada na DER. Para um blueprint financeiro, isso é material: define onde nascem os atrasados.

Observação de oportunidade: há precedente do \*\*TRF4 afastando o Tema 1124 justamente nos casos de indeferimento automático/carta robotizada\*\*, por entender que o INSS deu causa — nesses casos os efeitos ficam na DER e o processo não é sobrestado. Isso conecta o Tema 1124 ao "robô negador" e deveria estar no blueprint.



\*\*A2 — \[ALTA] A regra dos "4 meses" está incompleta e a tabela de duração por idade foi totalmente omitida.\*\*

Trecho: \*"casamentos ou uniões estáveis iniciados com menos de dois anos… conferindo o benefício por apenas limitadíssimos 4 (quatro) meses."\*

O documento apresenta \*\*um só\*\* gatilho (união < 2 anos). São \*\*dois gatilhos alternativos\*\* (art. 77, §2º, V, "b", Lei 8.213/91): a pensão dura 4 meses se o óbito ocorrer sem que o segurado tenha vertido 18 contribuições mensais OU se o casamento/união tiver menos de 2 anos. Falta a carência de 18 contribuições — exatamente o tipo de regra que o algoritmo aplica e que gera indeferimento/penalização.

Além disso, omite-se por completo a \*\*tabela de duração por idade do cônjuge\*\* (alínea "c"): 3 anos (<22), 6 (22-27)… até vitalícia a partir de 44 anos. Sem essa tabela, o blueprint não consegue mapear o cálculo de DCB nem o passivo/encerramento — central para auditoria financeira do FRGPS.



\*\*A3 — \[ALTA] A exceção do acidente (dispensa de requisitos + 100%) não é mencionada.\*\*

O documento diz que "o sistema automático aplica esta regra de forma cega". Mas há regra de contorno legal que o sistema \*\*precisa\*\* checar: se o óbito decorrer de acidente de qualquer natureza ou doença profissional/do trabalho, são dispensados os requisitos de 18 contribuições e 2 anos de união (art. 77, §2º-A), e o cálculo passa a ser integral (100%). Um fail point real é o sistema aplicar "4 meses" em óbito acidentário por não capturar a causa mortis.



\*\*A4 — \[ALTA] A fórmula de cálculo pós-EC 103 (art. 23) está ausente; só se cita o art. 24.\*\*

O documento cita o art. 24 (acumulação) mas \*\*não\*\* o art. 23, que é a mudança mais impactante para o valor: cota familiar de 50% + 10% por dependente, até 100% (art. 23, EC 103/2019), e — crítico para um modelo financeiro — sob a EC 103 a cota não é reversível: quando um dependente cessa, o total da pensão diminui (art. 23, §1º), ao contrário da reversão integral do antigo art. 77, §1º. A não-reversibilidade é uma fonte recorrente de erro de pagamento e de litígio que o blueprint precisa modelar.



\*\*A5 — \[MÉDIA] O número "2,191 milhões" está com o sentido invertido.\*\*

Trecho: \*"uma fila total que chegou a registrar 2,191 milhões de requerimentos no sistema."\*

O documento apresenta 2,191 mi como ápice de congestionamento. É o oposto: 2,191 milhões em maio/2026 é o menor patamar em 17 meses, queda de 30% frente aos 3,128 milhões de fevereiro. Usar esse número como evidência de "estrangulamento" enfraquece o argumento e é factualmente incorreto.



\*\*A6 — \[MÉDIA] O "1 em cada 10" precisa de contexto e está parcialmente mal-lido.\*\*

O documento usa "≈10% negados automaticamente por divergência de CNIS, sem contraditório". Dois ajustes: (i) o índice de 10,94% de negativa automática baseia-se em dados de auditoria de 2024, não em achado novo de jun/2026 — datar isso evita imprecisão. (ii) O achado central do TCU não é só a \*taxa\* de negativa, mas a \*taxa de erro\*: mais de 10% dos indeferimentos em análise automática estão equivocados, e na análise manual os erros passam de 13%. Esse dado é inconveniente para a narrativa do documento (ver C/E abaixo): a análise humana erra \*\*mais\*\*, não menos.

Acrescente que o acórdão tem número: \*\*Acórdão TCU 1498/2026\*\* (citado pela nota da OAB SP, que confirma o foco em contraditório administrativo e dever de concessão do melhor benefício), e que a auditoria abrange todos os benefícios (aposentadorias, pensões, auxílio-reclusão, salário-maternidade, incapacidade e BPC), não só a Espécie 21. O documento por vezes sugere que os 10% são específicos da pensão.



\*\*A7 — \[MÉDIA] Cronologia e atribuição causal da fraude associativa estão imprecisas.\*\*

Trecho: \*"no segundo semestre de 2025, os órgãos correcionais… flagraram… 'fraude da fraude'… embasadas na posse indevida de dados vazados dos gigantes repositórios da Dataprev."\*

A "fraude da fraude" (contestações com áudios/assinaturas forjadas) é de fato de meados de 2025, mas o documento \*\*omite o fato gerador\*\*: a \*\*Operação Sem Desconto\*\*, deflagrada por CGU e PF em 23/04/2025, sobre descontos associativos via ACTs sem autorização (97% dos entrevistados não autorizaram), com impacto estimado em R$ 6,3 bilhões e \~6 milhões de beneficiários. E a causa raiz não foi "vazamento de dados da Dataprev" — foi \*\*fragilidade do controle de autorização das filiações/ACTs\*\*: o próprio INSS declarou não ter competência técnica pericial para validar a veracidade das assinaturas digitais, baseando a averbação na boa-fé das entidades. Atribuir a vazamento da Dataprev é uma inferência fraca (ver E2).



\*\*A8 — \[BAIXA] Nome da entidade incorreto.\*\*

Trecho: \*"Confederação Nacional de Agricultores."\* O nome correto é \*\*CONAFER — Confederação Nacional dos Agricultores Familiares Rurais e Empreendedores Familiares do Brasil\*\*. As seis entidades da "fraude da fraude" são, conforme apuração, Amar Brasil, AASAP, ANDDAP, CENAP.ASA, CONAFER e Ambec — o documento só nomeia três e erra uma.



\---



\## B. BACKSTAGE (BASTIDOR) OMITIDO



\*\*B1 — \[ALTA] Habilitação tardia e rateio de cotas como processo, não como evento.\*\* O documento trata o rateio só na fase de pagamento. Falta mapear a \*\*habilitação de codependente posterior\*\* (art. 76 da Lei 8.213): quando companheira/filho de outra relação habilita depois, há recálculo de cotas e a parcela do novo dependente corre \*\*a partir da sua habilitação\*\*, sem prejudicar quem já recebia. É backstage relevante e fonte de litígio entre dependentes.



\*\*B2 — \[ALTA] Cálculo da RMI / aposentadoria ficta.\*\* O fluxo salta de "defere" para "calcula as cotas" sem o passo de derivação do valor-base (aposentadoria por incapacidade ficta → média do art. 26 EC 103 → 50%+10%). Para auditoria financeira, esse é o nó do valor e deveria ser um bloco de backstage explícito.



\*\*B3 — \[ALTA] Recurso administrativo ao CRPS.\*\* Entre o indeferimento (Etapa 4) e a judicialização há uma etapa inteira ausente: \*\*recurso às Juntas de Recursos e Câmaras de Julgamento do Conselho de Recursos da Previdência Social (CRPS)\*\*. O documento só menciona "Conselhos Recursais" de passagem, sem mapeá-lo como estágio com seus próprios prazos, filas e fail points.



\*\*B4 — \[MÉDIA] Ciclo formal de exigência.\*\* A "carta de exigência" aparece como evento, não como \*\*sub-processo\*\* (emissão → prazo de 30 dias → reanálise → novo indeferimento/deferimento). É justamente o ciclo que o Acórdão 1498/2026 manda restaurar antes da negativa automática.



\*\*B5 — \[MÉDIA] Representação de incapazes.\*\* Para dependente menor ou inválido falta o backstage de \*\*representante legal / tutela-curatela / conta para crédito\*\*, e eventual necessidade de alvará — recorrente em pensão.



\*\*B6 — \[BAIXA] Prova de vida hoje é majoritariamente passiva.\*\* O documento descreve a prova de vida como ação ativa anual do cidadão. Desde 2022-2023 o modelo migrou para \*\*fé de vida por batimento de bases\*\* (biometria/cruzamentos governamentais), com exceção residual. Mantê-la como modelo ativo descreve um AS-IS desatualizado.



\---



\## C. NORMATIVOS E EVIDÊNCIAS AUSENTES



\*\*C1 — \[ALTA] Art. 74 da Lei 8.213/91 (DER e prazo de 90 dias).\*\* Regra-chave para o cidadão e para o passivo de atrasados, totalmente ausente: requerido em até 90 dias do óbito, a pensão retroage à data do óbito; após, conta-se da data do pedido (180 dias para menores de 16). É também fail point financeiro (ver D1).



\*\*C2 — \[ALTA] EC 103/2019, art. 23 (cota e §1º não-reversibilidade)\*\* — ver A4. Citar só o art. 24 deixa o cálculo capenga.



\*\*C3 — \[MÉDIA] Lei 8.212/91 (Custeio).\*\* Você pediu explicitamente. O documento não a cita. Embora o período de graça esteja no art. 15 da 8.213, a \*\*qualidade de segurado e a base contributiva que sustenta o FRGPS\*\* estão ancoradas na 8.212. Para um blueprint que serve a auditoria financeira do fundo, a perna do custeio (receita) precisa ao menos ser nominada.



\*\*C4 — \[MÉDIA] LGPD (Lei 13.709/2018).\*\* As Etapas 2 e 6 falam de vazamento e fraude com dados pessoais mas nunca invocam a LGPD nem o papel da ANPD — moldura normativa óbvia para o risco de dados.



\*\*C5 — \[MÉDIA] IN PRES/INSS 128/2022 está citada corretamente; a "IN 141/2022, art. 177-A" precisa de conferência.\*\* A instrução normativa consolidadora vigente de procedimentos é a \*\*128/2022\*\*. A referência a uma "IN 141/2022, art. 177-A" para arbitramento de datas incompletas \*\*não está confirmada\*\* e deve ser checada na fonte primária antes de validar — pode ser confusão de numeração. Não a valide por gentileza.



\*\*C6 — \[BAIXA] Portarias 1.382/2021 e 1.286/2021 e os códigos de sub-tarefa 1658/1659.\*\* Plausíveis, mas \*\*não verificáveis\*\* em fonte aberta no nível de detalhe afirmado. Tratar como "a confirmar em norma primária", não como fato assentado.



\---



\## D. FAIL POINTS NÃO IDENTIFICADOS



\*\*D1 — \[ALTA] Perda de retroativos por DER tardia (>90 dias).\*\* Cidadão em luto que demora a requerer perde o período entre óbito e pedido. Fail point financeiro clássico, ausente.



\*\*D2 — \[ALTA] Engargalamento no CRPS.\*\* Recurso administrativo que pode levar anos — estágio inteiro de "desistência induzida" e judicialização, não mapeado (ver B3).



\*\*D3 — \[ALTA] Disputa de habilitação entre dependentes.\*\* Viúva × companheira, filhos de relações distintas, concubinato (STF Tema 526). Trava o pagamento e migra para o judiciário. Não consta como fail point.



\*\*D4 — \[MÉDIA] Queda de valor por cessação de cota (EC 103, não-reversível).\*\* Na manutenção, o beneficiário vê o valor cair quando um codependente sai, sem entender por quê — fonte de reclamação e de erro de pagamento. Ausente.



\*\*D5 — \[MÉDIA] Óbito acidentário tratado como comum.\*\* Sistema aplica 4 meses/cálculo reduzido por não capturar causa mortis acidentária (ver A3).



\*\*D6 — \[MÉDIA] Dependente sem meio de recebimento.\*\* Menor/idoso sem conta, sem representante, com nome divergente — o documento toca no "código 55" no PAB, mas não no fail point de cadastro do dependente na ponta.



\---



\## E. INFERÊNCIAS MAL-SUPORTADAS / FONTES FRACAS / NÚMEROS A VERIFICAR



\*\*E1 — \[ALTA] A discrepância SIRC × CRC (11.819.946 vs 2.604.234 ≈ 10,6 mi) e o TC 018.882/2024-2 não foram confirmados.\*\* São números muito específicos, apresentados como achado assentado do TCU, que \*\*não consegui validar em fonte aberta\*\*. Como você tem acesso interno, recomendo puxar o \*\*TC 018.882/2024-2\*\* e conferir os valores, a data-base e o universo antes de usá-los — hoje são a evidência mais forte do documento e, se imprecisos, derrubam a tese da Etapa 1.



\*\*E2 — \[ALTA] "Robô negador" como mecanismo deliberado.\*\* O texto editorializa ("estruturou-se para negar em massa", "mecanismo maquiavélico"). O achado do TCU é sobre \*\*ausência de contraditório e má qualidade de dados (CNIS)\*\*, não intenção dolosa. E contraria o próprio texto o dado de que a análise manual erra mais (>13%) que a automática (>10%) — ou seja, a peça romantiza o servidor humano como crivo de qualidade, quando o TCU mostra o contrário. Recomendo neutralizar o tom e ancorar no Acórdão 1498/2026.



\*\*E3 — \[MÉDIA] Fraude associativa atribuída a vazamento da Dataprev.\*\* Inferência fraca; o vetor apurado foi autorização/filiação forjada e falha de controle dos ACTs (ver A7). Há vazamentos de dados do INSS noticiados, mas misturá-los à causa da fraude associativa é salto não suportado.



\*\*E4 — \[MÉDIA] Tabela de ranking de filas (BPC 434.773; Idade 254.629; Pensão 136.837; 10,8%).\*\* Internamente consistente, mas \*\*sem data-base nem fonte\*\*. Precisa de âncora (mês/ano e relatório de origem) para sobreviver a uma revisão de auditoria.



\*\*E5 — \[BAIXA] Detalhes operacionais finos (tela CONPAB, flag "S" de erro administrativo, código 55, SPAB, deferimento "em 12 horas").\*\* Plausíveis como conhecimento institucional, mas \*\*não verificáveis\*\* externamente. Marcar como "a confirmar em manual operacional/POP" — não citar como fato público.



\---



\## Síntese de prioridade para a revisão (v2)



Os \*\*erros que comprometem a base jurídica\*\* e precisam de correção antes de qualquer outra coisa: A1 (Tema 1124 — classe, data e direção da tese), A2 (4 meses + tabela de idade), A4 (art. 23 e não-reversibilidade), A3 (acidente). Os \*\*achados que sustentam o blueprint como evidência de auditoria\*\* e precisam de validação documental: E1 (SIRC×CRC / TC 018.882/2024-2) e A6 (Acórdão 1498/2026 com a leitura correta dos índices). As \*\*lacunas estruturais do blueprint\*\* a preencher: B1-B3 (habilitação/rateio, RMI, CRPS) e D1-D3 (DER 90 dias, CRPS, disputa de dependentes).



Duas observações finais de método: o texto às vezes trata índices e fatos relativos a \*\*todos os benefícios\*\* como se fossem específicos da Espécie 21 — vale segregar; e o tom editorial ("guilhotina", "masmorras cibernéticas", "maquiavélico") fragiliza um documento de controle externo, que ganha força com asserção factual sóbria e ancoragem normativa.



Se quiser, eu \*\*consolido isto num quadro de achados em .docx\*\* (colunas: nº, trecho, tipo, gravidade, dispositivo/fonte correta, recomendação), no padrão de matriz de achados, pronto para anexar ao papel de trabalho. Posso também montar a versão corrigida das Etapas 2-4 com os dispositivos certos embutidos.



Tópico sensível na peça (luto, fraude contra idosos): mantive o foco técnico, mas registro que parte das fontes secundárias são escritórios de advocacia — boas para a regra geral, fracas como fonte primária; para o que for à matriz, prefira lei seca, o acórdão do TCU e o do STJ.

