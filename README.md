# RMBC Skills para Antigravity

A consagrada metodologia **RMBC** (Research, Mechanism, Brief, Copy) de Stefan Georgi estruturada como skills nativas de workspace para o **Antigravity**.

---

## Sobre o Método RMBC

Criado por Stefan Georgi — copywriter com mais de \$700M em faturamento atribuído —, o método RMBC transforma a escrita de copy de alta conversão em um processo de engenharia estruturado em 4 fases:

1. **Research (R):** Pesquisa profunda de ICP, dores, desejos, níveis de consciência, concorrentes e comprovações clínicas/ingredientes.
2. **Mechanism (M):** Criação de um mecanismo único e específico explicando *por que* a solução funciona (passando no teste "apenas nós").
3. **Brief (B):** Direcionamento estratégico conectando a pesquisa à copy (ângulos, tom de voz, prova, apelo de urgência).
4. **Copy (C):** Redação da copy direta orientada à conversão (lead, revelação do mecanismo, empilhamento de provas e fechamento).

Todas as skills de geração aplicam automaticamente **5 Quality Gates**:
- **Especificidade:** Toda afirmação deve incluir número, dado ou prazo.
- **Quantificação de mecanismo:** Referências a mecanismos incluem métricas/estudos.
- **Jornada do leitor:** Conexão direta com as tentativas anteriores e dores reais.
- **Diversidade de provas:** Uso combinado de pelo menos 2 tipos de prova (estudos, testemunhos, autoridades, dados).
- **Tratamento de objeções:** Respostas concretas para as principais resistências.

---

## Estrutura do Projeto no Antigravity

As skills estão prontas para execução local e automática dentro deste workspace:

```text
.
├── .agents/
│   └── skills/                  # Skills nativas descobertas pelo Antigravity
│       ├── hook-battery/
│       ├── fb-ad-copy/
│       ├── rmbc-context/        # Hub metodológico central
│       │   └── resources/
│       │       └── rmbc-methodology.md
│       └── ...
├── skills -> .agents/skills     # Symlink de conveniência
├── docs/
│   └── benchmark-results.md
├── lib/
│   └── attribution-variants.md
├── README.md
└── LICENSE
```

---

## Skills Disponíveis (43)

### 1. Testadas em Benchmark (3 skills)
Skills centrais com validação em testes A/B cegos (+17pp de conversão média sobre prompts genéricos):

| Skill | Descrição |
|-------|-----------|
| `hook-battery` | Gera 10 ganchos (2 por gatilho psicológico) para parar o feed. |
| `email-promo` | E-mail promocional com testes A/B de assunto e quebra de objeções. |
| `copy-rewrite` | Diagnostica fraquezas e reescreve copy existente seção a seção. |

### 2. Geração de Copy (23 skills)
Aplicam todos os 5 Quality Gates na produção de peças orientadas à conversão:

| Skill | Descrição |
|-------|-----------|
| `advertorial-writer` | Advertoriais de formato longo estilo editorial. |
| `bonus-stack` | Empilhamento de bônus aumentando valor percebido da oferta. |
| `broadcast-email` | E-mails de broadcast para engajamento e relacionamento. |
| `cart-abandonment-flow` | Sequência de recuperação de carrinho abandonado. |
| `checkout-abandonment` | Diagnóstico e copy de recuperação para abandono de checkout. |
| `email-retention-sequences` | Sequências de e-mails para retenção pós-compra e LTV. |
| `fb-ad-copy` | Anúncios Meta/Facebook (imagem única, carrossel e vídeo). |
| `guarantee-writer` | Garantias de reversão de risco agressivas e persuasivas. |
| `lander-copy` | Copy completa para landing pages e páginas de vendas. |
| `lead-writer` | Abertura magnética (primeiras 200–500 palavras) de copy longa. |
| `offer-stack` | Estruturação de oferta irresistível com ancoragem de preço. |
| `order-form-cro` | Otimização de copy e elementos de confiança no formulário de pedido. |
| `pdp-ecomm-template` | Copy de alta conversão para páginas de produto (PDP) de e-commerce. |
| `post-purchase-sequence` | Sequência pós-compra para combater remorso e incentivar uso. |
| `reengagement-sequence` | Reativação de inscritos e clientes inativos. |
| `scarcity-urgency` | Elementos éticos de escassez e urgência no fechamento. |
| `soap-opera-sequence` | Sequência de e-mails estilo novela com ganchos narrativos. |
| `thank-you-page` | Copy da página de confirmação/obrigado com upsell imediato. |
| `ugc-brief` | Briefing autêntico para criadores de UGC (User Generated Content). |
| `upsell-script` | Scripts para ofertas OTO (One-Time Offer) e upsell imediato. |
| `upsell-sequence-writer` | Sequências de e-mail para ascensão a ofertas de maior ticket. |
| `vsl-script` | Roteiro estruturado para Video Sales Letter (VSL). |
| `webinar-registration-copy` | Copy otimizada para páginas de inscrição em webinars. |
| `welcome-sequence` | Sequência de boas-vindas e onboarding para novos leads. |

### 3. Estratégia & Planejamento (12 skills)
Focadas em posicionamento estratégico, arquitetura de funil e mídia paga:

| Skill | Descrição |
|-------|-----------|
| `ab-test-plan` | Plano estruturado de testes A/B (hipótese, variantes e métricas). |
| `ad-angle-generator` | Geração de 5–7 ângulos criativos únicos para campanhas. |
| `ad-creative-audit` | Auditoria de criativos de anúncios com pontuação e correções. |
| `competitor-offer-analysis` | Análise de gaps nas ofertas e mecanismos dos concorrentes. |
| `creative-brief` | Briefing criativo estratégico entre copywriting e design. |
| `free-offer-brief` | Estruturação de iscas digitais e produtos tripwire. |
| `funnel-architecture` | Mapeamento da jornada do cliente no funil DTC completo. |
| `funnel-audit` | Auditoria de funis existentes com identificação de vazamentos. |
| `mechanism-ideation` | Ideação do mecanismo único do produto (o "M" do RMBC). |
| `media-buying-brief` | Briefings para gestores de tráfego (públicos, metas e testes). |
| `pricing-strategy` | Estratégia de precificação, ancoragem e formatos de apresentação. |
| `write-copy` | Roteador mestre: identifica o objetivo e aciona a skill recomendada. |

### 4. Pesquisa & Metodologia (5 skills)
Alimentam e auditam a qualidade das cópias produzidas:

| Skill | Descrição |
|-------|-----------|
| `rmbc-context` | Hub metodológico com as diretrizes e padrões de Stefan Georgi. |
| `rmbc-copy-audit` | Avaliação de copy frente às 4 dimensões de qualidade RMBC. |
| `ingredient-research` | Pesquisa de ingredientes, estudos clínicos e alegações seguras. |
| `unified-research-synthesizer` | Síntese de pesquisas multifonte em um briefing executável. |

---

## Como Utilizar no Antigravity

Como o projeto está configurado em `.agents/skills/`, as skills já estão disponíveis para o agente nesta sessão de trabalho.

Basta descrever em linguagem natural o que você precisa produzir:
- *"Gere ganchos para meu produto de clareamento dental"* → aciona `hook-battery`
- *"Faça uma auditoria nesta página de vendas"* → aciona `rmbc-copy-audit` ou `funnel-audit`
- *"Escreva um anúncio para o Meta focado em dor nas costas"* → aciona `fb-ad-copy`
- *"Desenvolva uma sequência de carrinho abandonado com 4 e-mails"* → aciona `cart-abandonment-flow`
- *"Não sei por onde começar para criar minha oferta"* → aciona `write-copy`

---

## Licença

[MIT](LICENSE)
