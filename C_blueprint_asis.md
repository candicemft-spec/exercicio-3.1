## Service Blueprint AS-IS — Pensão por Morte (Espécie 21) · RGPS/INSS

Jornada do dependente do segurado falecido, do óbito ao pagamento/manutenção, nos canais Meu INSS (app/web), Central 135 e atendimento presencial nas APS. Diagnóstico AS-IS (estado atual), não redesenho. As decisões de fronteira — onde passa a Linha de Visibilidade, o que é fail point e em que camada cada ator opera — foram tomadas na sessão `/grill-me` registrada em `C_grill_transcript.md`.

| Camada \ Etapa | 1. Óbito / Registro civil | 2. Acesso e protocolo | 3. Análise e automação | 4. Recurso / Judicialização | 5. Implantação e pagamento | 6. Manutenção |
|---|---|---|---|---|---|---|
| **Evidências Físicas** | Declaração de Óbito; Certidão de Óbito | tela Meu INSS / URA 135; Comprovante de Requerimento (DER) | status (SMS/push); Carta de Exigência; Carta de Concessão | petições; e-Recursos; intimações | HisCre; demonstrativo PAB; crédito bancário | extrato HisCon; demonstrativo mensal |
| **Ações do Cidadão** | obtém certidão; protocola em ≤ 90 dias | autentica Gov.br (prata/ouro); autodeclara; faz upload de provas | acompanha status; cumpre exigência em 30 dias | recorre ao CRPS ou aciona advogado/Justiça | consulta HisCre; recebe cotas-parte | gere consignações (HisCon); denuncia descontos (defesa do consumidor) |
| *— Linha de Interação —* | | | | | | |
| **Frontstage** (visível) | balcão do cartório | interface Meu INSS / URA 135 | mensagens de status **+ Carta de Exigência** | balcão virtual / audiência / escritório | banco conveniado / app bancário | SAC; financeiras; associações; defesa do consumidor |
| *— Linha de Visibilidade —* | | | | | | |
| **Backstage** (invisível) | gatilho Sirc → CNIS; extinção do benefício do falecido | validação SERPRO/Receita/TSE; GET; pré-avaliação CNIS | algoritmo decisório; batimento CNIS; cálculo da RMI (média art. 26 → cota art. 23); duração por idade | tramitação nas Juntas/Câmaras do CRPS; varas federais | "Maciça" (Dataprev); geração de PAB; habilitação tardia (art. 76); batimento de acúmulo (art. 24) | fé de vida passiva (cruzamento de bases); averbação de ACT; cassação / não-reversibilidade |
| *— Linha de Interação Interna —* | | | | | | |
| **Processos de Suporte** | Sirc / CRC / cartórios | Gov.br / SERPRO / CNIS | CNIS (Dataprev); motor de regras; análise humana (CEAPs) | CRPS; Justiça Federal | Dataprev (folha); rede bancária Febraban | Dataprev (consignação); LGPD; entidades ACT |
| **⚠ Fail points** | ⚠ **Perda de retroativos (DER > 90 dias)** | barreira digital Gov.br / cadastro de representante | ⚠ **Cegueira acidentária** (4 meses indevidos); erro decisório ~10,94% | ⚠ **Engargalamento do CRPS** (anos de espera → desistência/judicialização) | vácuo por inconsistência cadastral (crédito de incapazes) | ⚠ **Fraude associativa** — Operação Sem Desconto (ACTs sem anuência) |

### Legenda das fronteiras
- **Linha de Interação** — separa o que o cidadão faz do que o serviço apresenta no palco.
- **Linha de Visibilidade** — fronteira central do AS-IS. Decisão tomada no grill: na Etapa 3, o cidadão **vê** a mudança de status e a Carta de Exigência (Frontstage); o algoritmo decisório, o batimento CNIS e o cálculo da RMI ficam **abaixo** (Backstage).
- **Linha de Interação Interna** — separa o pessoal/processos de contato (Backstage) dos sistemas de retaguarda que os sustentam (Processos de Suporte).

### Fail points priorizados
1. **Perda de retroativos (DER > 90 dias)** — o luto retarda o protocolo; o lapso óbito→pedido é perdido (art. 74, Lei 8.213/91).
2. **Cegueira acidentária** — o script não captura a causa mortis acidentária e aplica indevidamente os 4 meses / requisitos (art. 77, §2º-A).
3. **Engargalamento do CRPS** — recurso administrativo que se arrasta por anos, induzindo desistência ou judicialização em massa.
4. **Fraude associativa** — fragilidade no controle de anuência dos ACTs (Operação Sem Desconto, CGU/PF, abr/2025; ≈ R$ 6,3 bi).

