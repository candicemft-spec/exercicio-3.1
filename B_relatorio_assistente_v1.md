Diagnóstico Operacional e Service Blueprint do Requerimento e Concessão de Pensão por Morte (Espécie 21) no RGPS

Contextualização do Cenário Operacional (AS-IS) e Fundamentos do Blueprint

A Pensão por Morte Previdenciária, classificada internamente como Espécie 21, constitui um dos eixos fundamentais e mais sensíveis da rede de proteção social gerida pelo Regime Geral de Previdência Social (RGPS). Administrado pelo Instituto Nacional do Seguro Social (INSS) e operacionalizado tecnologicamente pela Empresa de Tecnologia e Informações da Previdência (Dataprev), o serviço de concessão deste benefício atravessa atualmente uma transição paradigmática, marcada por profundas turbulências operacionais e institucionais. A migração forçada de um modelo estritamente analógico, centralizado no atendimento físico e na dependência de servidores públicos para a análise documental, para um ecossistema digital centrado na concessão automática via algoritmos, gerou inegáveis ganhos de eficiência em casos padronizados, mas simultaneamente introduziu vulnerabilidades sistêmicas severas e pontos de falha que afetam diretamente os direitos fundamentais dos cidadãos.



O cenário operacional atual (AS-IS) reflete uma administração pública sob imensa pressão de demanda. Historicamente, a Pensão por Morte ocupa posições de destaque nas estatísticas de represamento da autarquia. Em levantamentos recentes, o benefício representava a terceira maior fila de requerimentos do INSS, com aproximadamente 136.837 pedidos acumulados aguardando análise, o que correspondia a cerca de 10,8% do total de solicitações não periciais. Diante deste estrangulamento e de uma fila total que chegou a registrar 2,191 milhões de requerimentos no sistema, a autarquia previdenciária acelerou a automação por meio de robôs baseados em regras rígidas de cruzamento de dados. A plataforma digital "Meu INSS", que centraliza essas interações, consolidou-se como a maior plataforma de serviços digitais do governo federal, suportando uma média impressionante de 105 milhões de acessos mensais.   



Posição	Tipo de Benefício Previdenciário / Assistencial	Volume de Pedidos Acumulados	Representatividade

1º	Benefício de Prestação Continuada (BPC-Loas)	434.773	Fila Majoritária

2º	Aposentadoria por Idade	254.629	Alta Demanda

3º	Pensão por Morte (Espécie 21)	136.837	Gargalo Crítico de Subsistência

4º	Aposentadoria por Tempo de Contribuição	131.977	Alta Demanda

5º	Salário Maternidade	126.619	Demanda Sazonal/Contínua

A tabela acima demonstra a criticidade da Pensão por Morte no ecossistema de serviços do Estado. Contudo, a automação que visava mitigar este passivo revelou-se falha sob a ótica do devido processo legal. Auditorias contundentes do Tribunal de Contas da União (TCU), culminando em determinações plenárias expedidas em 10 de junho de 2026, revelaram que o sistema desenvolvido pela Dataprev apresenta pontos críticos de falha técnica e ofensa aos direitos dos segurados, negando de forma automatizada e peremptória cerca de 1 em cada 10 pedidos sem viabilizar o direito à defesa, à complementação documental ou ao contraditório por parte do cidadão.   



O mapeamento exaustivo desta jornada, estruturado rigorosamente no formato de Service Blueprint, visa fornecer a uma auditoria de controle externo a transparência analítica necessária sobre as camadas visíveis ao usuário (Frontstage) e as engrenagens invisíveis da administração (Backstage). O foco da presente análise incide sobre as falhas de interoperabilidade entre sistemas governamentais, os gargalos normativos impostos por legislações supervenientes, a obsolescência de sistemas legados como o Plenus, e os espaços abertos para fraudes sofisticadas. Este documento delineia a realidade prática (AS-IS), expondo as gambiarras operacionais e os curtos-circuitos sistêmicos que afastam o fluxo real da modelagem processual idealizada nas cartilhas do governo.



Service Blueprint: Jornada de Concessão de Pensão por Morte (Espécie 21)

A jornada a seguir detalha, de forma estruturada e cronológica, o fluxo percorrido pelo dependente do segurado instituidor (o falecido), dissecando cada interação, sistema, normativo e ponto de quebra desde o evento motivador até a efetivação e manutenção do benefício.



ETAPA 1: Ocorrência do Fato Gerador e Registro Civil do Óbito

Ações do Cidadão (Ótica do Usuário):

A jornada de prestação do serviço público estatal inicia-se muito antes de qualquer login em plataformas digitais ou de senhas retiradas em agências; ela começa no momento de maior vulnerabilidade psicológica e desorientação do usuário: o luto agudo. O cidadão, atuando na condição de familiar sobrevivente ou dependente direto, depara-se com o falecimento do segurado instituidor, evento que pode ocorrer no domicílio, em vias públicas ou no interior de unidades hospitalares. A primeira e imediata necessidade do usuário é providenciar a Declaração de Óbito (DO), documento de atestação médica que atua como o embrião de todo o processo legal subsequente. De posse deste formulário médico, o dependente, muitas vezes sob estresse extremo, necessita deslocar-se fisicamente ao balcão de um Cartório de Registro Civil de Pessoas Naturais para promover a lavratura da Certidão de Óbito, o documento mater sem o qual a concessão da Pensão por Morte inexiste no mundo jurídico-administrativo. Neste estágio pré-requerimento, o cidadão absoluto desconhece que a eficácia, a celeridade e o sucesso do seu futuro requerimento previdenciário no INSS dependem de forma umbilical e crítica da precisão com que o escrevente do cartório digita os dados vitais e, sobretudo, da infraestrutura de comunicação em rede que transmitirá esse fato ao Estado brasileiro.



Evidências Físicas/Digitais:

As evidências materiais nesta etapa são predominantemente analógicas, embora em transição digital. O cidadão recebe e manuseia a Declaração de Óbito (DO) impressa em papel, tradicionalmente gerada em vias coloridas (amarela ou branca), preenchida de próprio punho pelo médico atestante ou legista. Posteriormente, no cartório, a evidência tangível transforma-se na Certidão de Óbito oficializada, emitida em papel moeda padronizado nacionalmente, contendo selos de autenticidade, QR Codes de validação e assinaturas do oficial registrador, além do formato digital via central do registro civil.



Linha de Interação (Frontstage):

O contato direto do cidadão com a máquina do Estado, de forma ampliada e delegada, ocorre através de profissionais de saúde em hospitais ou do Instituto Médico Legal (IML), que emitem a DO. O principal ponto de contato (touchpoint) desta fase inaugural é o atendimento presencial no balcão do Cartório de Registro Civil. O cidadão interage com o Oficial do Cartório ou seus escreventes, respondendo a perguntas sobre o estado civil do falecido, a existência de bens, herdeiros e, fundamentalmente, sobre os documentos de identificação (CPF, RG, Título de Eleitor) do segurado instituidor, informações vitais que ditarão o sucesso do cruzamento de dados na Dataprev.



Processos de Bastidor (Backstage):

As atividades invisíveis ao cidadão nesta fase constituem o gatilho tecnológico para a automação previdenciária. Após a lavratura do assento de óbito, o cartório tem a obrigação legal de inserir os dados do falecido e os metadados da certidão no Sistema Nacional de Informações de Registro Civil (Sirc) e na Central de Informações de Registro Civil (CRC). O Sirc atua como um barramento centralizador e um grande data lake de informações vitais do Governo Federal. A comunicação tempestiva do óbito via Sirc é o gatilho sistêmico absoluto; é esta integração de bastidor que permitirá aos robôs do INSS e da Dataprev cessarem preventivamente e de forma automática eventuais benefícios de aposentadoria ou auxílio-doença que o falecido recebia em vida, mitigando fraudes e pagamentos indevidos pós-morte. Simultaneamente, este mesmo batimento de dados habilita a base do Cadastro Nacional de Informações Sociais (CNIS) para reconhecer o status de "falecido" do instituidor, preparando o terreno digital para a futura concessão automática da pensão aos dependentes elegíveis que protocolarão o pedido.   



Arcabouço Normativo e Sistemas:



Sistemas Envolvidos: SIRC (Sistema Nacional de Informações de Registro Civil), gerido pelo Governo Federal; CRC (Central de Informações de Registro Civil), gerida pelo Operador Nacional do Registro Civil; Sisobi (Sistema de Informação de Óbitos legado, cujos dados históricos estão armazenados no próprio Sirc).   



Normativos Aplicáveis: Lei de Registros Públicos (Lei nº 6.015/1973), que rege os prazos e formas de assento de óbito; Instrução Normativa PRES/INSS nº 141/2022 (especificamente o Art. 177-A, que estipula as regras de contorno para datas incompletas na certidão).   



Fail Points (Pontos de Falha Conhecidos):



Atraso Crônico na Alimentação do SIRC: O processo estatal trava rotineiramente logo em sua origem. Cartórios frequentemente atrasam o envio dos lotes de registros de óbito para a nuvem governamental. Em extensas auditorias conduzidas pelo Tribunal de Contas da União, como documentado no Acórdão associado ao processo TC 018.882/2024-2, constatou-se que o atraso dos declarantes em registrar o óbito formalmente, somado à lentidão sistêmica, causa volumes massivos de pagamentos indevidos de aposentadorias entre a data real do óbito e a data de averbação no sistema, forçando a autarquia a exaustivos processos de cobrança administrativa de difícil recuperação.   



Colapso de Interoperabilidade e Defasagem de Dados: O diagnóstico operacional revela uma falha massiva de integração de dados entre as próprias bases do país. Dados auditados pelo TCU indicaram que, em determinado período de amostragem, enquanto a base primária da CRC (alimentada diretamente pelos cartórios) possuía 11.819.946 registros de óbitos consolidados, as bases governamentais do Sirc e do legado Sisobi continham apenas 2.604.234 para o mesmo período. Isso expõe um déficit alarmante e inexplicável de aproximadamente 10,6 milhões de registros de óbitos que falharam em transitar da CRC para o Sirc. Para a jornada do cidadão, isso significa que o robô do INSS tentará cruzar dados com uma base federal desatualizada e cega, impossibilitando a concessão automática da pensão.   



Inconsistência Material e Datas Incompletas: Faltas de preenchimento de dias ou meses exatos na Certidão de Óbito geram pane nos algoritmos de benefício. Para mitigar o travamento do sistema, o INSS precisou criar normativos de contorno (gambiarras institucionais legalizadas). O Art. 177-A da IN 141/2022 estabelece que, se a certidão não tiver o dia exato, o sistema arbitrará o último dia do mês; se faltar o mês, arbitra-se o último dia do ano; na ausência total de datas, presume-se a data de lavratura no cartório. Tais ficções jurídicas afetam diretamente a Data de Início do Benefício (DIB) da Pensão e os valores de atrasados devidos à família.   



``: Apesar das auditorias apontarem o déficit milionário de registros, não há transparência pública granular sobre a arquitetura de sincronização de dados (APIs) entre a base nacional da CRC, gerida pelo Operador Nacional (ONRCPN), e os servidores da Dataprev. O SLA (Service Level Agreement) exato, a frequência de polling de atualização e o tempo de latência técnica da propagação de um óbito registrado no interior do país até o reconhecimento no sistema de mainframe Plenus do INSS não estão documentados acessivelmente, impedindo o desenho de uma matriz de risco temporal perfeita pela auditoria.



ETAPA 2: Acesso aos Canais, Autenticação e Triagem

Ações do Cidadão (Ótica do Usuário):

Superada a fase do registro civil e já de posse da certidão, o dependente inicia o esforço proativo de requerer seu direito junto ao INSS. O cidadão enfrenta, de imediato, a barreira da escolha do canal de atendimento e a necessidade de comprovar sua identidade no ambiente digital. Ele precisa decidir se fará o pedido através do aplicativo de smartphone ou site "Meu INSS", se ligará para a Central de Teleatendimento 135, ou se tentará um atendimento presencial em uma Agência da Previdência Social (APS). O cidadão que detém literacia digital tenta acessar a plataforma única do governo (Gov.br), frustrando-se frequentemente com as exigências de elevar seu nível de confiabilidade da conta para "Prata" ou "Ouro" via senhas bancárias ou biometria facial, requisitos exigidos para destravar serviços automatizados de concessão. Paralelamente, populações rurais, analfabetos digitais ou residentes em áreas remotas enfrentam a assimetria informacional; eles procuram despachantes, advogados previdenciaristas, lan houses ou enfrentam os menus intermináveis da Central 135. As dúvidas que permeiam a mente do usuário são críticas: "Eu realmente tenho direito a essa pensão?", "Como provo minha união não casada documentalmente no sistema?".   



Evidências Físicas/Digitais:

O cidadão se depara com a tela de Login Único do portal Gov.br, que exige CPF e senha. Ao ingressar, a evidência digital é a interface limpa e focada em autoatendimento do aplicativo Meu INSS, exibindo o catálogo vasto de serviços. Se a opção for telefônica, a evidência é o áudio robótico da URA (Unidade de Resposta Audível) da Central 135, seguido da voz de um atendente terceirizado. Nas agências físicas, restam os totens de autoatendimento, as senhas impressas em papel termossensível e o ambiente de espera.



Linha de Interação (Frontstage):

O Frontstage digital é asséptico e padronizado: o cidadão interage primariamente com a interface de usuário (UI) do App Meu INSS via smartphone ou navegador web, que atua como um balcão virtual ininterrupto. No canal telefônico, a interação humana direta se dá com os operadores de telemarketing da Central 135. Nas raras vezes em que consegue atendimento físico para serviços não-agendáveis, interage com servidores administrativos, estagiários ou terceirizados nas APS, que atualmente atuam muito mais como orientadores para o uso dos canais digitais do que como recepcionistas de processos em papel.



Processos de Bastidor (Backstage):

A engrenagem invisível da autenticação é altamente complexa. Ao inserir o CPF, os servidores do Serviço Federal de Processamento de Dados (Serpro) fazem a validação de identidade cruzando dados instantaneamente com a Receita Federal do Brasil (RFB) e com bases do Tribunal Superior Eleitoral (TSE) ou da Secretaria Nacional de Trânsito (Senatran) para garantir a conformidade da biometria facial. Uma vez autenticado e com a sessão aberta no Meu INSS, os sistemas de middleware da Dataprev são acionados, realizando chamadas (APIs) em tempo real ao Cadastro Nacional de Informações Sociais (CNIS), carregando instantaneamente para a tela os vínculos laborais, remunerações e o histórico previdenciário do usuário logado. Caso o canal escolhido seja a intermediação da Central 135, o operador telefônico acessa uma interface de front-end restrita (geralmente via Sibe ou Sabi), preenchendo as telas iniciais do requerimento com base nas informações verbalizadas pelo cidadão, gerando ao fim uma tarefa e uma carta de "Cumprimento de Exigência" automática, sinalizando que o cidadão deverá obrigatoriamente anexar os documentos de forma digital pelo Meu INSS ou depositá-los fisicamente nas "urnas" de coleta das agências da APS.



Arcabouço Normativo e Sistemas:



Sistemas Envolvidos: Gov.br (gerido pelo Serpro e Ministério da Gestão), Meu INSS (desenvolvido e mantido pela Dataprev), CNIS (Cadastro Nacional de Informações Sociais), e interfaces internas de protocolo como Sibe.



Normativos Aplicáveis: Portaria PRES/INSS nº 1.382/2021, que regulamenta de forma exaustiva o uso dos canais de atendimento remoto e as diretrizes de prestação de serviços digitais da autarquia.



Fail Points (Pontos de Falha Conhecidos):



A Exclusão Digital como Barreira Institucional: Especialistas e acadêmicos apontam a profunda desigualdade no acesso. Conforme discutido por pesquisadores e suportado por auditorias, a transição abrupta para o Meu INSS criou barreiras intransponíveis para segurados com parcos recursos tecnológicos ou baixa escolaridade. Nem todos possuem a expertise ou o equipamento necessário para interagir com sistemas automatizados, resultando em uma "desistência induzida" ou na dependência financeira de intermediários.   



Colapsos de Infraestrutura e Intermitência: O portal Meu INSS não é imune a quedas de servidor. Processando uma volumetria esmagadora de, em média, 105 milhões de acessos mensais no ano de 2026 , o sistema sofre com lentidão em dias de pagamento de maciça e intermitências que impedem a emissão tempestiva de protocolos, aumentando a ansiedade do dependente.   



Vulnerabilidade da Autenticação a Fraudes Estruturadas: A arquitetura do Gov.br tornou-se alvo preferencial de estelionatários. Criminosos, munidos de dados oriundos de vazamentos em larga escala  e valendo-se do uso incipiente de ferramentas avançadas de Inteligência Artificial para burlar reconhecimentos faciais ou invadir e-mails, acessam o perfil de segurados recém-falecidos ou de idosos para alterar senhas bancárias, comandar mudanças de local de pagamento ou protocolar benefícios e empréstimos fraudulentos antes mesmo que a família legítima consiga bloquear o acesso.   



ETAPA 3: Preenchimento de Dados e Protocolo do Requerimento

Ações do Cidadão (Ótica do Usuário):

Logado no sistema, o cidadão navega até a categoria "Pensão" e seleciona "Pensão por Morte Urbana" ou "Pensão por Morte Rural". Ele é então submetido a um fluxo de questionários dinâmicos que exigem autodeclarações precisas sobre sua relação com o falecido (Cônjuge, Companheiro, Filho Menor, Filho Inválido, Pais). Nesta etapa crítica, o usuário deve digitalizar e anexar fotografias ou arquivos em formato PDF dos documentos exigidos pelo regulamento: Certidão de Casamento ou Óbito, RG, CPF, comprovantes de endereço e as complexas e vitais provas materiais de União Estável. O usuário opera o sistema na esperança de que as fotos tiradas pelo celular estejam perfeitamente enquadradas e nítidas para não serem rejeitadas. Concluído o envio, ele anseia pela tela de sucesso, efetuando o download do comprovante de requerimento para sua segurança psicológica.



Evidências Físicas/Digitais:

O cidadão visualiza os formulários digitais estruturados do Meu INSS contendo perguntas autodeclaratórias restritivas (ex: "O segurado especial trabalhava na agricultura familiar de forma contínua?"). A principal evidência final é a emissão do PDF do Comprovante de Requerimento, ostentando o Número do Benefício (NB), o Número do Protocolo (Tarefa), a Data da Entrada do Requerimento (DER) e o resumo das respostas fornecidas.



Linha de Interação (Frontstage):

A interação se restringe à comunicação visual da interface da plataforma Meu INSS, que utiliza microcópias (textos explicativos de interface) para orientar o upload de arquivos, indicando os limites de tamanho (geralmente até 5MB por arquivo) e as extensões permitidas, sinalizando de forma sistêmica o sucesso ou o erro no envio do pacote de dados para o servidor do INSS.



Processos de Bastidor (Backstage):

No momento em que o cidadão clica em "Avançar" ou "Concluir", uma intrincada coreografia sistêmica ocorre no backend. O sistema de front-end envia um payload de dados criptografados para o Gerenciador de Tarefas (GET), que criará uma fila de trabalho, e simultaneamente para os sistemas corporativos de benefício da autarquia, como o Sibe (Sistema Integrado de Benefícios).

Neste milissegundo, a máquina executa uma verificação prévia crítica de elegibilidade, conhecida como análise da "Qualidade de Segurado". Os robôs consultam as amarras profundas do CNIS para responder a uma pergunta condicional rígida: O CPF do falecido detinha vínculo com a Previdência no momento do óbito? O sistema verifica se ele estava empregado, se era aposentado em manutenção, ou se mantinha a qualidade de segurado pelo "período de graça" legal (intervalo de 12 a 36 meses sem contribuir após demissão, dependendo do histórico). Se essa pré-validação encontrar consistência, o requerimento ganha tração para seguir na esteira automática; caso contrário, é carimbado com alertas de divergência cadastral.   



Arcabouço Normativo e Sistemas:



Sistemas Envolvidos: Sibe (Sistema Integrado de Benefícios, que atua como repositório de análise), GET (Gerenciador de Tarefas, o distribuidor do fluxo de trabalho), e o CNIS.



Normativos Aplicáveis: Lei nº 8.213/1991 (especificamente o Artigo 16, que define taxativamente as classes hierárquicas de dependentes) ; Portaria PRES/INSS nº 1.286/2021, que determina os códigos de fluxos operacionais, classificando, por exemplo, a Pensão por Morte Urbana sob o código de sub-tarefa 1659 e a Rural sob 1658.   



Fail Points (Pontos de Falha Conhecidos):



Fadiga e Erros de Captura Documental: A qualidade dos documentos digitalizados pelo próprio usuário em smartphones de baixa resolução frequentemente resulta em arquivos ilegíveis, desfocados ou cortados. Essa deficiência material na entrada dos dados induz algoritmos de Reconhecimento Óptico de Caracteres (OCR), quando existentes, ao erro crasso, ou força o servidor humano a emitir exigências frustrantes para que o cidadão reenvie tudo, alongando o tempo de processamento em meses.



A Armadilha Legislativa dos Casamentos Recentes: A arquitetura do sistema não amortece a complexidade da legislação. A Lei nº 13.135/2015 alterou drasticamente a Lei 8.213/91, determinando que casamentos ou uniões estáveis iniciados com menos de dois anos de antecedência ao óbito do segurado não garantem pensão vitalícia ou de longo prazo, conferindo o benefício por apenas limitadíssimos 4 (quatro) meses. O sistema automático aplica esta regra de forma cega com base apenas na data da certidão de casamento inserida.   



A "Aporia" das Provas Mistas (União Estável pré-Casamento): Como agravante ao ponto anterior, é extremamente comum no Brasil que o casal viva em união estável informal por décadas e decida oficializar o casamento civil meses antes do falecimento de um dos cônjuges. Pela norma, o dependente tem o direito de somar o tempo da união informal ao casamento recente para escapar da penalidade dos "4 meses". Contudo, a interface do Meu INSS peca gravemente em User Experience (UX) governamental, não orientando ativamente o viúvo(a) a anexar de imediato as provas documentais antigas para comprovar a união prévia. Como resultado, a automação baseia-se apenas na certidão recente e defere o benefício penalizado de 4 meses.   



``: A lógica exata de microsserviços das APIs da Dataprev e o peso de roteamento sistêmico que define se um protocolo do Sibe fluirá diretamente para a máquina analítica do Prisma (sistema focado em acertos judiciais e administrativos mais complexos) ou se ficará travado no GET não são detalhados abertamente em manuais de operação de nível usuário, ocultando como o INSS prioriza determinadas filas ocultas em detrimento de outras no escopo de banco de dados.   



ETAPA 4: Análise de Reconhecimento de Direito (Automação vs. Manual)

Esta quarta etapa representa o núcleo nevrálgico da prestação do serviço, onde o ecossistema tecnológico do INSS atua sob um modelo operacional de bifurcação estrita: a via expressa e opaca dos robôs decisórios e a via demorada e burocrática dos servidores humanos alocados em centrais remotas de análise.



Ações do Cidadão (Ótica do Usuário):

O papel do dependente nesta fase é de espera vigilante e passiva. O cidadão acompanha obsessivamente o status do seu pedido no aplicativo, aguardando que o marcador "Em Análise" mude de cor. Dependendo da sorte sistêmica de seus dados cruzados, ele pode receber uma notificação de aprovação em ínfimas 12 horas ou, pelo contrário, sofrer meses a fio na obscuridade de filas inatingíveis. Eventualmente, ele é surpreendido com "Cartas de Cumprimento de Exigência" demandando a juntada de novos documentos em prazos fatais de 30 dias. Com o transcorrer do tempo sem renda, a angústia pela subsistência aumenta exponencialmente, precipitando, não raro, o endividamento familiar ou a busca por escritórios de advocacia para a impetração de Mandados de Segurança na Justiça Federal.



Evidências Físicas/Digitais:

O sistema fornece indicativos de status via tela ("Concluído", "Em Exigência", "Indeferido", "Deferido"). Em caso de finalização da etapa, o cidadão efetua o download da Carta de Concessão ou da Carta de Indeferimento, documentos estruturados em formato PDF que trazem a fundamentação legal da decisão (por vezes em linguajar técnico ininteligível ao leigo) e a memória de cálculo inicial do benefício, caso aprovado.



Linha de Interação (Frontstage):

O INSS comunica ativamente as mudanças de fase processual através do envio de notificações em massa via SMS (mensagens curtas textuais), Push notifications no próprio celular via aplicativo gov.br/Meu INSS, ou disparo automatizado de E-mails, alertando o cidadão para que acesse o portal e tome ciência dos atos administrativos.



Processos de Bastidor (Backstage):



A Esteira Automática (A Lógica dos Robôs): A "concessão automática" ocorre num cenário de alinhamento perfeito de dados em bases governamentais. Se a mulher é casada oficialmente, e tanto a certidão de casamento quanto o assento de óbito do instituidor encontram-se perfeitamente registrados, averbados e sincronizados na base do SIRC , e, cumulativamente, o instituidor já percebia aposentadoria ou ostentava recolhimentos irretocáveis no seu extrato do CNIS sem pendências cadastrais, o algoritmo desenvolvido pela Dataprev entra em ação. Operando por meio de um batimento de regras condicionais estritas (IF/THEN logic), a máquina identifica compatibilidade plena, calcula as cotas e defere o benefício sem que qualquer servidor humano precise abrir o processo, finalizando o trâmite em prazos recordes, por vezes inferiores a 12 horas após o upload.   



O Transbordo Inevitável para a Análise Manual Humana: Contudo, o algoritmo quebra rapidamente diante de "eventos de vida não-padronizados". Nestes casos, o robô ou emite um indeferimento sumário (falha abordada a seguir) ou "transborda" a tarefa, empurrando-a para as prateleiras digitais do Gerenciador de Tarefas (GET). O GET, atuando como um distribuidor logístico de trabalho, endereça o protocolo para a fila de um servidor humano lotado preferencialmente em uma CEAP - Central Especializada de Alta Performance (neste caso, a Central Especializada para Análise de Requerimentos de Pensão por Morte e Auxílio Reclusão - CEAP - DEPENDENTES). O modelo de CEAPs baseia-se em metas intensivas de produtividade que exortam servidores em teletrabalho a ultrapassar a meta ordinária em troca de bônus financeiros (GDASS/Programa Especial).   



Gatilhos Frequentes que Forçam o Direcionamento Manual:



União Estável Não Registrada em Cartório: A Inteligência Artificial governamental ainda não possui discernimento ou autorização normativa para interpretar provas materiais heterogêneas e avaliar o contexto probatório. A análise conjugada de apólices de seguro de vida, contas de luz com o mesmo endereço, dependência em imposto de renda, planos de saúde conjuntos ou acervos de conversas e fotos em redes sociais exige inexoravelmente a valoração subjetiva de um analista do INSS. A Instrução Normativa 128/2022 estipula regras estritas de meios probatórios para a União Estável , afastando de plano a concessão automática para casais não formalizados civilmente. Comprovadamente, quem tenta submeter união estável pedindo deferimento expresso comete fraude ou terá o processo remetido para a longa fila humana.   



Complexidade de Filhos Maiores Inválidos: O robô não pode atestar perícia médica de incapacidade. Filhos maiores de 21 anos que reivindicam cota de pensão sob a alegação de invalidez demandam a criação sistêmica de uma sub-tarefa obrigatória denominada "Parecer Médico Pericial Pós Óbito no Gerenciador de Tarefas - GET". Peritos médicos reais precisam ser acionados para avaliar prontuários e atestar se a alegada invalidez incapacitante precedia a data exata do falecimento do pai/mãe segurado.   



Acumulação de Benefícios Pós-Reforma: O servidor humano ou o robô aprimorado devem aplicar as duras regras de barreira do Art. 24 da Emenda Constitucional 103/2019 (Reforma da Previdência). Desde sua promulgação, é vedada a percepção cumulativa integral de pensão por morte deixada por cônjuge com aposentadoria própria do RGPS ou de Regimes Próprios (RPPS). O sistema deve calcular redutores matemáticos drásticos no benefício de menor valor para impedir o enriquecimento além do teto delineado na Constituição.   



Arcabouço Normativo e Sistemas:



Sistemas Envolvidos: Prisma e Sibe, os motores de análise onde os servidores navegam para emitir despachos e construir a fundamentação jurídica de concessão ou de emissão de Cartas de Exigência. Sistema legado PLENUS, acessado via emulador de host (Host DTPRJCV3) no Subsistema de Benefícios (SISBEN), utilizado obrigatoriamente para investigar participações anteriores, acúmulos, ou desdobramentos de benefícios rurais em cotas-partes de pensões geradas antes de 1994.   



Normativos Aplicáveis: Emenda Constitucional nº 103/2019 (em especial o Artigo 24 e as novas cotas da pensão por morte) ; Lei nº 8.213/1991; Regulamento da Previdência Social consolidado no Decreto nº 3.048/1999 ; Instrução Normativa PRES/INSS nº 128/2022.   



Fail Points (Pontos de Falha Conhecidos e Diagnóstico de Auditoria):



A Devassa do TCU e a Tragédia do "Robô Negador" (Junho/2026): O ponto de quebra sistêmica mais grave da atual década no INSS foi dissecado por uma auditoria fulminante do Tribunal de Contas da União. Em julgamento plenário realizado na quarta-feira, dia 10 de junho de 2026, o TCU expôs as entranhas falhas do sistema desenvolvido pela Dataprev, concluindo que o aumento da demanda e o foco na velocidade subverteram garantias fundamentais. O achado central da corte foi alarmante: o sistema automatizado estruturou-se para negar benefícios em massa. Constatou-se que cerca de 1 em cada 10 pedidos (aproximadamente 10% da volumetria submetida à automação) é negado sumária e automaticamente pelo robô devido a divergências de CNIS, sem que fosse oportunizada qualquer notificação prévia de pendência ao cidadão. A automação, visando limpar a fila freneticamente, atropelava o direito constitucional ao contraditório (a emissão da Carta de Exigência). Como consequência, o TCU exarou determinação impositiva ordenando que o INSS, a Dataprev e o Ministério da Previdência Social procedam, no prazo impostergável de 180 dias, à reformulação da matriz de algoritmos da concessão automática. A medida exige a garantia do melhor benefício e impõe o dever sistêmico de notificar o beneficiário para sanar pendências antes da negativa automática. Entidades da sociedade civil, como a OAB-SP, manifestaram-se ratificando que a tecnologia deve atuar como vetor de ampliação de acesso, e não como guilhotina de supressão de garantias legais. O INSS e Dataprev informaram não terem sido notificados formalmente até o momento daquela publicação, mas atestaram contínua evolução na ferramenta.   



A Judicialização e o Lapso do Tempo (O Gargalo dos Atrasados): Quando a engrenagem administrativa falha brutalmente e o segurado, desassistido pelos sistemas falhos de orientação, busca amparo na Justiça Federal para garantir sua Pensão por Morte, ocorrem intensos atritos contábeis. Um contencioso massivo, que atingiu o Superior Tribunal de Justiça (STJ) sob o Tema de Repercussão 1.124 em 2026, discute os efeitos financeiros (o pagamento de valores atrasados retroativos) nos processos judiciais em que o segurado, por total ausência de orientação da autarquia ou do aplicativo, só conseguiu apresentar documentos hábeis essenciais (como as exatas provas da União Estável) dentro do processo judicial, anos após o requerimento inicial. Especialistas defendem que o segurado não pode ser duplamente penalizado perdendo o montante financeiro retroativo devido às falhas da administração pública em orientá-lo na fase administrativa.   



ETAPA 5: Concessão, Implantação e Geração do Primeiro Pagamento

Ações do Cidadão (Ótica do Usuário):

Com o mérito do direito finalmente reconhecido pelo servidor humano ou pelo robô corrigido, a preocupação central do viúvo ou dependente transmuta-se de procedimental para financeira: o recebimento do numerário vital para sua subsistência familiar. A ação do usuário passa a ser o acesso ao "Extrato de Pagamento" ou a emissão do Histórico de Créditos (HisCre) através do portal. O cidadão vasculha este documento visando descobrir a exata "Data de Disponibilidade", o valor nominal bruto, eventuais descontos que possam ter sido lançados sobre a competência e, primordialmente, qual é a agência pagadora (instituição financeira) e o endereço designados administrativamente pelo INSS para que ele compareça para o saque inaugural da verba.



Evidências Físicas/Digitais:

A evidência digital por excelência é o Histórico de Créditos (HisCre) e o Extrato de Pagamento de Benefício. A evidência tangível materializa-se posteriormente na ponta final: o crédito efetivado em conta corrente bancária pessoal do beneficiário (via TED, PIX ou depósito em conta vinculada) ou a autorização sistêmica para emissão de um cartão magnético para saque físico nos caixas eletrônicos das redes bancárias conveniadas. O cidadão também interage com o Calendário Oficial de Pagamentos anualmente distribuído.   



Linha de Interação (Frontstage):

O INSS desloca a linha de contato direta e o Frontstage passa a ser protagonizado pelas Instituições Financeiras conveniadas com o Estado, que atuam como os tentáculos pagadores do governo. A plataforma Meu INSS serve apenas como o vitrinista que exibe o calendário de liberação atrelado ao dígito numérico final do Número de Benefício (NB) gerado.   



Processos de Bastidor (Backstage):

O complexo ecossistema financeiro do INSS é o núcleo desta etapa de liquidação.



Comando de Implantação de Vantagem: O servidor do INSS, ao deferir o pedido, emite o comando de despacho concessório eletrônico por dentro dos módulos operacionais do Prisma ou do Sibe. O algoritmo capta essa aprovação e injeta o fluxo no Sistema Único de Benefícios (SUB) e no mainframe veterano PLENUS.   



O Rito Contábil da "Maciça": A folha de pagamentos mensal da autarquia previdenciária, classicamente denominada "Maciça" nos corredores administrativos e na literatura bancária, é uma colossal operação de processamento digital em lote (batch processing) executada nos centros de dados de mainframes da Dataprev. Essa rotina roda obedecendo a cronogramas sistêmicos estritos (comumente girando entre a última semana e a primeira semana do mês, dependendo do dígito verificador e atrelando pagamentos a datas como dias 02, 03 ou 06 do mês subsequente). Durante a madrugada e os finais de semana estipulados no calendário interno de TI, a "Maciça" consolida e agrupa todos os pagamentos da espécie Pensão por Morte (21) e demais espécies ativas, calculando redutores e efetuando os abatimentos financeiros compulsórios (Imposto de Renda Retido na Fonte, Pensões Alimentícias judiciais). É neste motor contábil que a Dataprev divide a pensão global em cotas financeiras perfeitamente fracionadas e iguais (rateios) quando o sistema identifica, por exemplo, a multiplicidade de dependentes habilitados, rateando o valor entre a viúva principal e filhos reconhecidos de outros relacionamentos conjugais do segurado falecido.   



O Instrumento de Exceção: O PAB: Considerando a morosidade e as janelas de corte inegociáveis da Maciça, o modelo operacional adotou válvulas de escape financeiras. Caso a pensão sofra um atraso considerável e acabe sendo aprovada num dia em que o faturamento da "Maciça" já encontra-se selado, ou caso seja necessário liberar montantes retroativos vultosos (atrasados consolidados desde a data do óbito), o servidor precisa emitir administrativamente um "Pagamento Alternativo de Benefício", universalmente conhecido pela sigla PAB. O PAB destina-se a acelerar o socorro financeiro ou corrigir quantias equivocadas sem forçar o cidadão a suportar o aguardo penoso até o próximo giro de 30 dias do calendário folha. A evolução tecnológica do PAB resultou no SPAB (Novo Sistema de Pagamento Alternativo de Benefício), implantado pela Dataprev com o fito de modernizar a arquitetura e automatizar devoluções de crédito não sacados por erros cadastrais.   



O Desafio de Correção de Repasses (Código 55): O nível de detalhismo exigido dos servidores é minucioso. Quando um PAB processado no banco apresenta erro de digitação de nome e é rejeitado, o servidor da Agência (APS) precisa entrar no ambiente legado de caracteres verdes, a Tela CONPAB do PLENUS (ou usar emulações do Prisma). Ele bloqueia o crédito avariado e precisa comandar um novo PAB imediatamente, tendo a rigorosa cautela de assinalar flag afirmativo "S" (SIM) na rubrica paramétrica de "Erro Administrativo". Se esta microtarefa for ignorada, o banco de dados mestre da Dataprev rechaça e cancela instantaneamente o pagamento lançando o temido código de falha "55" (não há registro de crédito anterior), jogando o benefício num limbo contábil.   



Arcabouço Normativo e Sistemas:



Sistemas Envolvidos: PLENUS, SISBEN (Tela operacional CONPAB), PRISMA, SUB (Sistema Único de Benefícios), SISPAGBEN (Sistema de Pagamento de Benefícios), o ambiente massivo Mainframe de Maciça gerido pela Dataprev, e a nova arquitetura parcial do SPAB (Novo PAB).   



Normativos Aplicáveis: Contratos de prestação de serviços, Acordos e Convênios de recolhimento e pagamento bancário vigentes estabelecidos entre a Dataprev/INSS e a rede compensadora capitaneada pela Federação Brasileira de Bancos (Febraban).   



Fail Points (Pontos de Falha Conhecidos):



O Vácuo Financeiro do Calendário (O Gap de Implantação): Dada a arquitetura estática da geração das folhas, o beneficiário que tiver a sorte de sua pensão concedida por um juiz ou servidor no dia seguinte ao "corte de maciça" frequentemente amarga lacunas dramáticas de 30 a 45 dias para embolsar efetivamente o primeiro pagamento, caso os gerentes recusem ou esqueçam de liberar um PAB.   



Miopia Institucional sobre a Acurácia do SPAB: Relatórios de auditagem sistêmica interna oriundos da Auditoria-Geral do próprio INSS (Nota Técnica 01/2022) asseveraram que o alardeado "Novo PAB" não logrou atingir a plena efetividade prometida. Constatou-se que a migração de arquitetura fora lançada em fatias e, nos exames de conformidade, concluiu-se que o sistema SPAB limitava-se essencialmente à função de "reemissão automática" de crédito devolvido, fato que "reflete na impossibilidade de se avaliar a efetividade e eficácia de referido sistema até que todas as demais funcionalidades previstas se encontrem implementadas", operando num vazio parcial.   



``: Foge ao mapeamento e aos normativos de rotina gerencial ordinária das agências a compreensão do rastreio do lastro financeiro no back-end fazendário. O rastro cronológico minucioso de como e quando ocorre o empenho e a ordem bancária de liquidação financeira no SIAFI do Governo Federal – a ordem de depósito no banco em comparação com o arquivo gerado na maciça da Dataprev – carece de detalhamento técnico público compreensível aos auditores não detentores de senhas fazendárias.



ETAPA 6: Pós-Concessão, Manutenção Contínua e Vulnerabilidade Crítica a Fraudes

Ações do Cidadão (Ótica do Usuário):

Findo o turbilhão do requerimento e com o direito averbado, o processo estabiliza-se num longo planalto de manutenção e consumo contínuo. Ao longo dos meses e anos, o pensionista consome o recurso para o custeio de vida, sendo massivamente assediado pelo setor financeiro para contrair operações de empréstimos consignados que oneram irreversivelmente a sua margem atrelada ao benefício. A interação do usuário com a máquina estatal é predominantemente passiva; ele só adota uma postura ativa em duas ocasiões específicas: na exigência anual burocrática de apresentar a "Prova de Vida", ou nos momentos dramáticos em que abre o portal, verifica perdas substanciais no seu vencimento líquido e constata a injeção misteriosa e ilegítima de descontos associativos ou bancários os quais nunca consentiu no balcão virtual do "Meu INSS". Nessas ocorrências funestas, é forçado a engajar-se num périplo de reclamações contra as obscurecidas sedes destas entidades nos canais SACs ou no Portal do Consumidor da Secretaria Nacional do Consumidor (Senacon) para lograr exclusões e estornos da pirataria financeira perpetrada com seu contracheque.



Evidências Físicas/Digitais:

O monitoramento deste status vitalício dá-se primariamente pelo acesso regular ao Extrato de Pagamento de Benefício. Complementarmente, o cidadão valesse do Extrato de Empréstimos Consignados (vulgarmente conhecido como HisCon), um demonstrativo técnico no portal Meu INSS onde são expostas as margens disponíveis, as taxas aplicadas, as operadoras financeiras averbadoras e as faturas das referidas mensalidades associativas furtivamente descontadas no rodapé da folha.   



Linha de Interação (Frontstage):

A relação é terceirizada: o segurado relaciona-se diretamente com representantes da miríade de Instituições Financeiras conveniadas que exploram o crédito popular, com as denominadas "Associações de Aposentados" sedentas por base de filiação , e, reativamente, com os postos de ouvidoria oficial do Governo Federal em caso de queixas sistêmicas.   



Processos de Bastidor (Backstage):



O Monopólio das Averbações Financeiras: Entidades civis associativas e federações laborais, escudadas sob a legitimidade conferida pela celebração formal de "Acordos de Cooperação Técnica" (ACT) celebrados junto às cúpulas do INSS , detêm permissão arquitetônica para enviar densos lotes de arquivos eletrônicos magnéticos contendo "chaves de descontos" em folha diretamente aos servidores mainframe da Dataprev. A norma processual pressupõe romanticamente que tais rubricas financeiras oriundas destas instituições carreguem inexoravelmente o aval irrestrito, a assinatura biométrica ou a anuência eletrônica certificada do pensionista antes da averbação.   



A "Guilhotina Sistêmica" (Batimentos de Óbito de Pensionistas): O ecossistema não apenas concede; ele também extingue direitos rigorosamente. A Dataprev projeta que os barramentos de metadados operem de forma vorazmente contínua. Caso o pensionista venha a falecer anos depois, a engrenagem (os algoritmos de manutenção e varredura robótica) confronta sistematicamente os dados em circulação no SIRC contra a folha de pagamento do Plenus. Quando uma equivalência mortuária for detectada, o benefício de número 21 é extinto, decepado sem compaixão e os créditos emitidos pós-óbito na conta bancária são resgatados preventivamente da rede bancária pelo governo para evitar fraudes ou o que o jargão denomina "saques fantasma" por parte dos parentes do agora ex-pensionista.   



Arcabouço Normativo e Sistemas:



Sistemas Envolvidos: Sistema de Controle e Averbações de Consignações mantido na infraestrutura da Dataprev, PLENUS (como base matriz de pagamento e interrupção).



Normativos Aplicáveis: O robusto cipoal de Instruções Normativas pertinentes ao limite (margem) de crédito consignado, os Termos de Adesão bancária para empréstimos em folha e a validade jurídica rigorosa dos Acordos de Cooperação Técnica (ACTs) que abrem as portas dos vencimentos dos pensionistas a descontos associativos.   



Fail Points (Pontos de Falha Conhecidos e Vulnerabilidades Mapeadas à Auditoria):



Epidemia Sistêmica de Fraudes e a "Fraude da Fraude" Associativa: A fase de manutenção foi convertida pelos atores criminosos em um vasto celeiro rentável de delitos contra a economia popular, transformando a segurança de dados da autarquia em letra morta. Redes criminosas sofisticadas estruturam táticas de engenharia social embasadas na posse indevida de dados vazados dos gigantes repositórios da Dataprev e outras fontes oficiais, alvos contumazes de ataques de segurança relatados na mídia e nos relatórios investigativos. Mais complexa e perniciosa que as fraudes financeiras comuns, no segundo semestre de 2025, os órgãos correcionais do governo (a Controladoria-Geral da União - CGU, em coordenação com o próprio setor de Inteligência do INSS) flagraram entidades de classe que desvirtuaram suas atribuições originais para orquestrar esquemas classificados nos veículos de imprensa como "fraude da fraude". Foi descoberto um escandaloso escoadouro de fundos mediante o qual, no mínimo, seis dessas associações sindicais (citando expressamente as organizações conhecidas como Amar Brasil, AASAP e Confederação Nacional de Agricultores) praticavam a burla ativa, forjando a assinatura biométrica e eletrônica nos mandatos para legalizar a implementação em série de descontos mensais nos repasses dos pensionistas pela Pensão por Morte, extraindo fortunas em forma de falsas taxas filiatórias. No desfecho punitivo, ficou administrativamente firmado e solidificado como tese de defesa governamental que meras "gravações em áudio de consentimento" feitas via telefone não constituem estofo jurídico suficiente para lastrear autorização de averbação junto à folha do INSS, transferindo o ônus de controle severo ao Estado.   



A Solidificação da Responsabilidade Objetiva Estatal nos Consignados: Um avanço marcante nas amarras institucionais da fiscalização externa manifesta-se nos pronunciamentos judiciais que rechaçam a inação conivente da autarquia federal. Precedentes firmes oriundos dos tribunais (exemplificando o recente arcabouço jurisdicional proferido no âmbito do Tribunal Regional Federal da 3ª Região, que abrange Mato Grosso do Sul) pacificaram um entendimento rigoroso sobre o ônus da vigilância ativa. A jurisprudência assentou que o INSS detém uma responsabilidade civil objetiva, premente e indeclinável de auditar, vigiar e assegurar o rigor técnico nas engrenagens das concessões financeiras lançadas nas folhas por seus parceiros averbadores (os bancos). No evento drástico e comum em que um pensionista indefeso padece frente a fraudes no seu contracheque geradas por bancos irresponsáveis, o ente público é impedido de eximir-se repassando o fardo culposo exclusivamente aos agentes privados. O Estado tornou-se corresponsável condenado pelas indenizações devidas à lacuna e à inabilidade estrutural para controlar o seu próprio território virtual sistêmico e as fronteiras do Plenus.   



Biometria Violada pela Inteligência Artificial e Dados Pessoais Vazados: O cenário que já contava com brechas operacionais passou a conviver com crimes operados em altíssima tecnologia cibernética. Gangues tecnológicas organizadas recorrem e se adestram no uso predatório e insidioso da Inteligência Artificial Genenativa combinada a bibliotecas vastas de informações vitais comercializadas no mercado obscuro (bancos de dados do INSS extraviados ). Eles empregam tecnologias contornativas que emulam vozes de aposentados recém-mortos, fraudam o motor do Serpro nos atos de feitura virtual de senhas ou "Provas de Vida Remotas", habilitam empréstimos imensos e promovem aberturas e encerramentos de contas corrente com notório objetivo da lavagem rápida de capitais provenientes dos espólios de pensionistas.   



Tabelas e Resumos Operacionais Analíticos de Sistemas (Material Exclusivo para Fins de Auditoria)

O arcabouço tecnológico desenhado acima aponta para a falha crônica na arquitetura de interoperabilidade e latência no processamento, com ênfase na fase probatória do luto. A seção abaixo condensa os mapas vitais de fluxo e quantitativos descobertos por cortes de contas.



Análise de Volumetria e a Discrepância Alarmante (Registros de Óbito)

A tabela a seguir espelha e dimensiona, em sua crueza, o grau severo do fosso cibernético apurado e criticado nos processos que instruem a fiscalização superior federal (Processo TCU TC 018.882/2024-2). Revela a fratura informacional gravíssima entre a entidade privada legalizada que coleta dados vitais nas bases nos municípios e as gigantes nuvens governamentais que precisam destes bytes pontuais para interromper a liberação indevida da dinastia previdenciária.   



Base de Dados / Origem Institucional	Gestão e Arquitetura Operacional	Volume Registrado Encontrado	Latência e Implicações Críticas (Auditoria)

CRC (Central de Informações de Registro Civil)	Administrada com celeridade pelo ente privado e descentralizado (Cartórios/Notários). A fonte vital limpa e originária.	11.819.946 Óbitos	A base serviu como a malha de teste primária utilizada pelo controle de contas.

SIRC / Sisobi (Governo Federal / Ministério da Previdência / INSS)	Sistema Barramento Estatal centralizado. Usado cegamente pelas esteiras decisórias automáticas (os robôs da Dataprev).	2.604.234 Óbitos	

Déficit monumental auditado de 10,6 milhões de registros apagados da visão do INSS comparado à CRC.



&#x20; 

Implicações Diretas na Concessão:

Este déficit massivo documentado de 10,6 milhões de registros demonstra inequivocamente que a arquitetura dos sistemas do INSS encontra-se lastreada sobre bases podres e atrasadas. Em se mantendo o atraso na API e a ausência do registro pontual e transparente no Sirc, qualquer pleito de requerimento automatizado submetido pelo cônjuge por via do aplicativo do segurado dependente nas esferas de Pensão por Morte deparará fatalmente com um bloqueio incontornável dos scripts Dataprev, visto que para o cérebro eletrônico, o de cujus constará legalmente vivo nas engrenagens.   



Ecossistema Modular da Dataprev para Pensão por Morte (Diagnóstico Estrutural Pós EC 103)

O Estado reagiu ao endurecimento imposto pela Reforma Constitucional Previdenciária de 2019 empreendendo a massiva alteração estrutural no ecossistema subjacente de cálculos. Este quadro abaixo explicita, contudo, a balcanização insidiosa de seis frontes separadas que exigem um esforço intelectual extremo do analista para efetuar a simples navegação de aprovação entre bases analíticas legadas (verdes e estáticas) e modernos frameworks em aplicativos (dinâmicos):   



Sistema Operado (Backstage)	Natureza e Função Específica no Processamento da Pensão por Morte	Diagnóstico do Ponto de Atrito Friccional (Fail Point)

Sistema Único de Benefícios (SUB)	

Barramento integrativo que orquestra e transaciona os dados deferidos entre a retaguarda do requerimento e as ordens remetidas aos núcleos de emissão bancária na rede.



Sujeito a constantes curtos-circuitos por intermitências pontuais. Complexo e opaco nos trâmites simultâneos de atrasados judiciais e PABs fora da escala massiva.

Sibe (Sistema Integrado de Benefícios)	

Tela principal da era digital (Web-based). Focado prioritariamente na análise moderna, deferimento ou despachos de fluxos correntes no Brasil pós-1991.



Luta contra a desorganização de interfaces confusas nas abas de transbordo (entre o que foi indeferido na matriz do robô e despachado na análise manual CEAP).

Prisma (Sistema de Reconhecimento)	

Framework corporativo maciço concebido para dominar passivos antigos e acertos judiciais espinhosos ou recálculos extensos que exigem diligência estrita do atendente humano.



Navegação exigente e labiríntica com alta densidade de manuais (parametrizações de rubrica severas). Enorme atrito no desmembramento das Pensões Rurais.



Mainframe PLENUS / SISBEN	

A âncora legada inamovível da nação. Um motor computacional vetusto rodando via ambiente Host/Telnet nos computadores centrais que arbitra toda a mecânica de rateio bancário real.



Interatividade baseada exclusivamente em "letras verdes" de terminal UNIX e atalhos rudimentares. Uma aversão frontal para as novas turmas concursadas. A temível tela CONPAB.



Gerenciador de Tarefas (GET)	

Logística burocrática digitalizada. O grande trilho algorítmico que avalia as naturezas e entrega os processos caóticos para a "fila infinita" e home-office do analista na CEAP.



Permanece passivo perante estoques em gargalos. Incapacitado para distinguir e separar a emergência dramática alimentar da pensão frente aos pedidos de averbação ordinários de idade.

&#x20; 

Síntese Investigativa Final e Diretrizes para Auditoria de Controle Externo

A modelagem de Service Blueprint construída nesta análise descortina não apenas um fluxograma processual, mas radiografa a real assimetria de poder e a debilidade organizacional vivenciadas durante o trajeto de formalização de um dos direitos mais sacrossantos de proteção familiar. O retrato operacional contumaz (o Estado AS-IS) do trâmite inerente à concessão da Pensão por Morte Previdenciária expõe abertamente um fortíssimo antagonismo prático: por um viés, celebra-se o avanço estético dos aplicativos front-end e os números mirabolantes de acessos virtuais que disfarçam a precarização das interações primárias; no plano invertido, atesta-se empiricamente a atroz estagnação das engrenagens lógicas, as bases defeituosas do back-end de processamento e a severa agressão metodológica das avaliações humanas em linha de produção no modelo CEAP. A consolidação dos achados descortina diretrizes taxativas e macrossistêmicas de intervenção fiscalizatória:



A "Caixa-Preta" Opressora do Algoritmo e a Quebra do Contraditório: A auditoria expõe cruamente que a mera transposição quantitativa veloz gerada pela automação descuidou flagrantemente da decência qualitativa. De acordo com os relatórios irrefutáveis exarados na determinação da cúpula de ministros do TCU na sessão do mês de junho de 2026, o algoritmo construído na Dataprev violou abertamente ditames seculares e principiológicos da lisura processual. O encerramento frio e perentório do andamento recursal (O fenômeno catalogado do "Robô Negador") atingindo expressivos 10% da volumetria, alicerçado invariavelmente em desvios do obsoleto CNIS sem oportunizar a simples via salutar da convocação corretiva para a "Carta de Exigência" empurrou, e segue a empurrar, parcelas fragilizadas do extrato social diretamente ao desespero alimentar, às instâncias protelatórias impenetráveis dos Conselhos Recursais Previdenciários da Esplanada dos Ministérios e à sobrecarga absurda dos mandados impetrados no poder Judiciário, agravando inclusive disputas acerca dos proventos atrasados. Este mecanismo maquiavélico deve ser neutralizado mediante o cumprimento do prazo impositivo de 180 dias outorgado aos entes, restabelecendo a programação sistêmica obrigatória de notificações prévias antes de qualquer negativa fria da placa digital.   



O Duelo e a Cegueira Axiológica no Exame Sociológico da Relação Sócio-Afetiva: A rigidez sistêmica choca-se frontalmente contra a organicidade antropológica e as normas civis do país. Instrumentos como a IN 128/2022 estatuíram obrigações severas acerca da valoração probatória no rito de prova perante as instâncias sobre a consubstanciação de União Estável (exigindo rastros em Impostos, registros de leitos e seguros). Contudo, como robôs operam numa gramática essencialmente binária e cartesiana, a tecnologia não detém a qualificação intelectiva da valoração material de provas. Segurados incautos e sem instrução forense têm seus protocolos indeferidos de pronto ou estrangulados pelas normativas de corte curto (quatro meses da nova lei conjugal) pela total omissão governamental em aplicar um bom desenho de Serviço Público (Design Thinking) com tutoriais explícitos de carregamento prévio que atenuem a falha tecnológica e eduquem o cidadão quanto à comprovação temporal.   



Vazamentos Crônicos e Insegurança Perdurante (Etapa de Manutenção Assaltada): A engrenagem previdenciária transmudou-se perigosamente de ente provedor e distribuidor de renda numa monumental "colônia de exploração financeira" para fraudadores ciber-crimináis. O manancial de dados acumulados nas masmorras cibernéticas Dataprev são recorrentemente extraviados em episódios obscuros ou expostos inadvertidamente por falhas imponderáveis. Isto fomenta e instrumentaliza engenhos audaciosos como a perniciosa "Fraude da Fraude" (CGU e INSS no embate contra quadrilhas sindicais estelionatárias flagradas mascarando descontos como as supracitadas Amar Brasil). A letargia inaceitável no desenvolvimento proativo de um "firewall gerencial" blindado para triagem dos famigerados Acordos de Cooperação Técnica converte a submissão dos contracheques gerados na maciça num autêntico saqueamento de idosos, gerando condenações severas na esfera da responsabilidade pública pelos tribunais superiores na salvaguarda material do consignado contra os agentes financeiros incúria.   



A Agonia Estrutural na Dinâmica da Retaguarda Digitalizada (Distopias no GET/CEAP): O INSS optou atabalhoadamente por terceirizar os impasses lógicos da automação diretamente à sobrecarga laboral psíquica das Centrais Especializadas de Alta Performance (CEAPs), fiando sua eficácia num regime exaustivo de recompensas pecuniárias sob pressão metas inalcançáveis em modo de teletrabalho ininterrupto. Todavia, ao constatar o acervo estancado com minúcias oriundas da inteligência analítica complexa das novas exigências, como as regras herméticas de transição em cálculos de limitação imposta na cumulação do Art. 24, EC 103/2019 das aposentadorias em concomitância as pensões , avulta-se a inépcia das esteiras do Gerenciador de Tarefas em rotear apropriadamente a prioridade perante as sub-tarefas desarticuladas nos fluxos 1658 ou de avaliações pós-óbito vitais. A fila segue o seu avanço de forma atabalhoada, corrompendo garantias sociais.   



A Tragédia Abissal do Insumo Primário em Ruínas (SIRC versus CRC): Nenhuma utopia em arquitetura de processamento ágil superará as lacunas colossais quando os cimentos estão esfarelando. Foge à razoabilidade jurídica o Estado empenhar a higidez decisória automática previdenciária de uma nação tendo a malha do balcão de dados do barramento SIRC deficitária em 10,6 milhões de registros frente aos estoques reais já pacificados pela entidade privada CRC (Conforme o assustador quadro no escopo auditorial do TCU - TC 018.882/2024-2). Enquanto o INSS não estabelecer um ecossistema com APIs perfeitas e espelhamentos real-time, lastreadas numa arquitetura unificada da nação para a detecção de assentos imaculados na DO ou falecimentos pregressos nos hospitais, os cofres da União permanecerão vazando milhões em benefícios pós-morte  e viúvas legítimas continuarão tendo direitos rechaçados em madrugadas cibernéticas frias pela absoluta ausência de empatia governamental enredada pela negligência da digitação no interior do país.   





