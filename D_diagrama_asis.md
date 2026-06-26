## Diagrama AS-IS — Pensão por Morte (Espécie 21) · RGPS/INSS

Fluxo da jornada do dependente, do óbito ao pagamento/manutenção, com os fail points em destaque. Reflete as etapas e atores do `C_blueprint_asis.md`. A Linha de Visibilidade separa o que o cidadão vê (frontstage) do backstage; os fail points (⚠) marcam onde a jornada trava.

```mermaid
flowchart TD
  Obito([Óbito do segurado]) -->|certidão| Cartorio[Cartório de Registro Civil]
  Cartorio -->|gatilho eletrônico| Sirc[(Sirc / CRC)]
  Sirc -->|rubrica de óbito| CNIS[(CNIS)]
  Sirc -.->|⚠ defasagem base a base| F0[/Fail: óbito não reconhecido/]

  Obito -->|requer em ate 90 dias| Canais{Canal de protocolo}
  Canais -->|digital| MeuINSS[Meu INSS app/web]
  Canais -->|telefone| C135[Central 135]
  Canais -->|presencial| APS[Agência APS]
  Canais -.->|⚠ DER > 90 dias| F1[/Fail: perda de retroativos/]

  MeuINSS --> Auth[Autenticação Gov.br]
  C135 --> Auth
  APS --> Auth
  Auth -->|valida identidade| SERPRO[(SERPRO / Receita / TSE)]
  Auth -->|gera DER|

@'
## Diagrama AS-IS — Pensão por Morte (Espécie 21) · RGPS/INSS

Fluxo da jornada do dependente, do óbito ao pagamento/manutenção, com os fail points em destaque. Reflete as etapas e atores do `C_blueprint_asis.md`. A Linha de Visibilidade separa o que o cidadão vê (frontstage) do backstage; os fail points (⚠) marcam onde a jornada trava.

```mermaid
flowchart TD
  Obito([Óbito do segurado]) -->|certidão| Cartorio[Cartório de Registro Civil]
  Cartorio -->|gatilho eletrônico| Sirc[(Sirc / CRC)]
  Sirc -->|rubrica de óbito| CNIS[(CNIS)]
  Sirc -.->|⚠ defasagem base a base| F0[/Fail: óbito não reconhecido/]

  Obito -->|requer em ate 90 dias| Canais{Canal de protocolo}
  Canais -->|digital| MeuINSS[Meu INSS app/web]
  Canais -->|telefone| C135[Central 135]
  Canais -->|presencial| APS[Agência APS]
  Canais -.->|⚠ DER > 90 dias| F1[/Fail: perda de retroativos/]

  MeuINSS --> Auth[Autenticação Gov.br]
  C135 --> Auth
  APS --> Auth
  Auth -->|valida identidade| SERPRO[(SERPRO / Receita / TSE)]
  Auth -->|gera DER| Analise[[Análise e automação decisória]]

  Analise -->|consulta| CNIS
  Analise -->|cálculo RMI: art. 26 -> cota art. 23| RMI[Cálculo da RMI e duração]
  Analise -->|pendência| Exig[Carta de Exigência - 30 dias]
  Exig -->|transbordo| CEAP[Análise humana CEAP]
  Analise -.->|⚠ cegueira acidentária| F2[/Fail: 4 meses indevidos/]

  Analise -->|defere| Pgto[Implantação e pagamento]
  Analise -->|indefere| Recurso{Contencioso}
  Recurso -->|administrativo| CRPS[Juntas e Câmaras do CRPS]
  Recurso -->|judicial| JF[Justiça Federal]
  CRPS -.->|⚠ espera de anos| F3[/Fail: engargalamento -> desistência/]

  Pgto -->|Maciça| Dataprev[(Dataprev - folha)]
  Dataprev -->|crédito| Banco[Banco conveniado Febraban]
  Banco --> Beneficiario([Dependente recebe cota])
  Pgto -.->|habilitação tardia art. 76| Rateio[Re-rateio de cotas]

  Beneficiario --> Manut[[Manutenção]]
  Manut -->|fé de vida passiva| Cruz[(Cruzamento de bases)]
  Manut -->|averbação ACT| ACT[Entidades associativas]
  ACT -.->|⚠ anuência fraudada| F4[/Fail: fraude associativa - Op. Sem Desconto/]
  Manut -.->|cessação de cota| NaoRev[/Não-reversibilidade EC 103/]
```
