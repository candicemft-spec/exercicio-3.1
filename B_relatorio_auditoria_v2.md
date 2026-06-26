Auditei a v2 contra a matriz de resolução e contra o corpo do blueprint, achado por achado, e verifiquei erros novos. Veredito resumido: \*\*a grande maioria dos 28 achados foi efetivamente incorporada ao corpo\*\* (não só declarada na matriz), os "pendentes" foram corretamente sinalizados no texto, mas há \*\*3 achados tratados na matriz e ausentes/incompletos no corpo\*\* e \*\*4 erros novos introduzidos na v2\*\* — sendo um deles quantitativo e de gravidade alta. Detalho abaixo.



\---



\## (a) Cobertura dos achados do audit\_v1



Status de cada ID (✓ incorporado ao corpo; ⚠️ só na matriz ou incompleto; ⏸ pendente sinalizado corretamente):



| ID | Status | ID | Status | ID | Status |

|---|---|---|---|---|---|

| A1 | ✓ | B3 | ✓ | C6 | ⏸ |

| A2 | ⚠️ incompleto | B4 | ✓ (parcial) | D1 | ✓ |

| A3 | ✓ | B5 | ✓ | D2 | ✓ |

| A4 | ✓ | B6 | ✓ | D3 | ✓ |

| A5 | ✓ | C1 | ✓ | D4 | ✓ |

| A6 | ⚠️ + erro novo | C2 | ✓ | D5 | ✓ |

| A7 | ✓ | C3 | ✓ + erro novo | D6 | ✓ |

| A8 | ✓ | C4 | ✓ | E1 | ⏸ |

| B1 | ✓ | C5 | ⏸ | E2 | ✓ |

| B2 | ✓ (parcial) | | | E3 | ✓ |

| | | | | E4/E5 | ⏸ |



\*\*Os "pendentes" (C5, C6, E1, E4, E5)\*\* foram bem resolvidos: C5 e C6 estão com a ressalva expressa no corpo das Etapas 1 e 2; E1 virou a \*"Defasagem Base a Base"\* com hedge correto (\*"Apontamentos (pendentes de verificação em TC 018.882/2024-2) sugerem possível déficit"\*) — e, acertadamente, a v2 \*\*abandonou os números não confirmados\*\* (11,8 mi × 2,6 mi) em vez de repeti-los. E4 (tabela de filas) e E5 (telas legadas) foram \*\*removidos\*\* do corpo, o que é melhor do que "manter com ressalva". Boa decisão editorial.



\*\*Achados tratados na matriz mas ausentes/incompletos no corpo — exija correção na v3:\*\*



\*\*A2 (parcial) — \[ALTA] A tabela de duração por idade não entrou no corpo.\*\* A matriz afirma: \*"inseridos os gatilhos alternativos… e a tabela de duração conforme idade do dependente."\* Os gatilhos (18 contribuições / 2 anos) aparecem na Etapa 3, mas \*\*a tabela de duração (3/6/10/15/20 anos / vitalícia a partir de 44) não está em lugar nenhum do blueprint\*\*. Era a omissão normativa mais relevante do v1 e segue sem endereçamento real. Sintoma disso: a Etapa 3 lista \*"idade"\* como input do cálculo, mas a idade não governa a RMI — governa a DCB, que o texto nunca calcula. Sem a tabela, não há como mapear a cessação nem o passivo, que é o cerne financeiro.



\*\*A6 (parcial) — \[MÉDIA] "Abrange outros benefícios" ficou só na matriz.\*\* A matriz diz \*"esclarecido que abrange outros benefícios"\*, mas o corpo (Etapa 3) não afirma que o índice e o Acórdão 1498/2026 cobrem aposentadorias, auxílios e BPC, não só a Espécie 21. O leitor da v2 continua podendo ler os 10,94% como específicos da pensão.



\*\*B2 (parcial) — \[BAIXA] Art. 26 da EC 103 não citado.\*\* A matriz prometeu mapear \*"a derivação da média do Art. 26 da EC 103"\*. O corpo descreve a aposentadoria ficta e cita só o Art. 23 (cota); a base de cálculo (média do Art. 26) não é referenciada. Lacuna menor, mas é a norma da média.



\---



\## (b) Erros NOVOS introduzidos na v2



\*\*N1 — \[ALTA] Conflação de duas métricas distintas do TCU.\*\*

Trecho (Etapa 3): \*"O Acórdão TCU 1498/2026 identificou que 10,94% dos indeferimentos processados por esteiras automáticas contêm erros… o erro na esteira de servidores humanos é de 13%."\*

Aqui a v2 fundiu dois números que o v1 separou de propósito:

\- \*\*10,94% = taxa de indeferimento\*\* (1 em cada 10 \*pedidos\* é negado pela automação). É percentual sobre \*pedidos\*, não sobre \*indeferimentos\*.

\- \*\*">10%" = taxa de erro dentro dos indeferimentos\*\* automáticos; e \*\*">13%"\*\* dentro dos manuais (achado do portal do TCU).

A frase \*"10,94% dos indeferimentos contêm erros"\* atribui ao numerador errado: pega a taxa de negativa (sobre pedidos) e a reapresenta como taxa de erro (sobre negativas). O denominador está trocado. A comparação automação×humano está na direção certa, mas o número correto para o lado da automação é ">10%", não 10,94%. Além disso, o 10,94% \*\*não foi "identificado pelo Acórdão 1498/2026"\*\* — é dado de auditoria de 2024 que o acórdão \*levou em consideração\*. Corrigir para: \*"a automação nega cerca de 10,94% dos pedidos; desses indeferimentos, mais de 10% estão equivocados — índice que, na análise humana, supera 13%."\*



\*\*N2 — \[MÉDIA] Mislabeling de "carência".\*\*

Trechos: Etapa 3 normativos \*"Lei 8.213/1991, Art. 77 (Regras de carência e duração)"\* e fail point \*"exigindo indevidamente a carência de 18 contribuições"\*. A pensão por morte \*\*independe de carência\*\* (Lei 8.213/91, art. 26, I); as 18 contribuições não são carência, são \*\*requisito de duração\*\* do art. 77, §2º. E o art. 77 trata de cota, duração e cessação — não de carência (que está nos arts. 25-26). Chamar isso de "carência" e localizá-la no art. 77 é erro técnico duplo, sensível numa peça de controle externo. Recomendo: \*"requisito de 18 contribuições para acesso à duração estendida (art. 77, §2º) — não confundir com carência, da qual a pensão é isenta (art. 26, I)."\*



\*\*N3 — \[MÉDIA] Misatribuição da qualidade de segurado à Lei 8.212/91.\*\*

Trecho (Etapa 2 normativos): \*"Lei 8.212/1991 (Qualidade de Segurado e Custeio)."\* A \*\*qualidade de segurado e o período de graça estão na Lei 8.213/91, art. 15\*\* — não na 8.212, que é o Plano de Custeio (contribuições/receita). A inclusão da 8.212 atende ao C3 do v1, mas a etiqueta entre parênteses precisa ser \*"(Custeio do RGPS)"\*; a qualidade de segurado deve ser remetida ao art. 15 da 8.213.



\*\*N4 — \[BAIXA] "Teto do Art. 23".\*\*

Trecho (Etapa 3): \*"aplica o teto do Art. 23 da EC 103 (cota familiar de 50% + 10%…)."\* O 50%+10% é a \*\*fórmula da cota\*\*, não um teto. Teto é o do RGPS (R$ 8.475,55/2026). Trocar "teto" por "fórmula de cálculo da cota".



\*Menores, opcionais:\* "registros do SUS" para prova de vida (Etapa 6) é específico e não verificado — deixar como "cruzamento de bases governamentais"; e a Etapa 6 cita "registros do SUS" e SERPRO/TSE como se a sistemática estivesse consolidada — convém um hedge.



\---



\## (c) Pontos em aberto para um Service Blueprint AS-IS de controle externo



\*\*O1 — \[ALTA] Tabela de duração (ver A2).\*\* É o item normativo que mais falta. Sem ele o blueprint não fecha a malha concessão→cessação→passivo.



\*\*O2 — \[MÉDIA] Faltam raias do blueprint em etapas inteiras.\*\* As Etapas 4 e 5 não têm a linha \*\*Frontstage (linha de interação)\*\*, e a Etapa 4 também não tem \*\*Evidências\*\* do lado do cidadão de forma completa. Não é cosmético: num Service Blueprint, a linha de interação é raia estruturante — sua ausência impede mapear onde o cidadão "toca" o serviço no contencioso (peticionamento, push de andamento processual, intimações). Padronizar as seis raias em todas as etapas.



\*\*O3 — \[MÉDIA] Regressão no Art. 24 (acumulação).\*\* O documento original (v1) descrevia o batimento de acúmulo pensão×aposentadoria própria/RPPS e os redutores. A v2 \*\*reduziu o Art. 24 a uma citação seca\*\* na Etapa 3, sem mapear o processo nem o fail point (o redutor por faixas que derruba o benefício de menor valor). Para auditoria financeira do FRGPS, o acúmulo é ofensor material — recuperar como subprocesso de backstage e/ou fail point na Etapa 5.



\*\*O4 — \[BAIXA] Magnitude da fraude e marco temporal.\*\* A Etapa 6 nomeia a Operação Sem Desconto e o vetor correto (ACTs), mas omite a dimensão (≈R$ 6,3 bi, \~6 mi de beneficiários, deflagração em abr/2025) — ancoragem útil de materialidade para controle externo.



\---



\### Veredito



A v2 é uma evolução sólida: corrigiu os erros jurídicos estruturais do v1 (Tema 1124, exceção acidentária, art. 23/não-reversibilidade, vetor da fraude, número da fila) e sinalizou os pendentes com honestidade metodológica. \*\*Não regrediu na maioria\*\*, mas introduziu \*\*um erro quantitativo de gravidade alta (N1)\*\* que um relator do TCU notaria de imediato, e \*\*dois erros normativos de classificação (N2, N3)\*\* que enfraquecem a precisão da fundamentação. O bloqueador remanescente continua sendo a \*\*tabela de duração por idade (A2/O1)\*\*, prometida na matriz e não entregue no corpo.



Prioridade para a v3, em ordem: (1) N1 — separar as duas métricas do TCU; (2) A2/O1 — inserir a tabela de duração; (3) N2/N3 — acertar carência e qualidade de segurado; (4) O3 — recuperar o acúmulo do art. 24; (5) O2 — padronizar as raias.



Se quiser, atualizo a \*\*matriz de achados em .docx\*\* acrescentando estas colunas de 2ª rodada (status de incorporação ao corpo, erros novos N1-N4, pontos em aberto O1-O4), no formato pronto para anexar ao papel de trabalho — e posso já entregar o parágrafo corrigido da Etapa 3 (métricas do TCU + tabela de duração + carência) para colar na v3.

