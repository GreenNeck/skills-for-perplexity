# Master Skill Guide: UI/UX

Este guia consolida as melhores práticas e princípios para UI Design Systems, UX Research e otimização de Landing Pages, otimizado para a compreensão de modelos de linguagem.

## 1. UI Design System Skill

**Descrição**: Criação e manutenção de sistemas de design para interfaces de usuário. Use para padronizar componentes, definir tokens de design (cores, tipografia, espaçamento) e garantir consistência na UI.

### Componentes Essenciais de um Design System

1.  **Tokens de Design (Design Tokens)**
    *   Variáveis que armazenam valores visuais fundamentais.
    *   **Cores**: Primárias, secundárias, neutras, semânticas (sucesso, aviso, erro).
    *   **Tipografia**: Famílias de fontes, tamanhos (escalas), pesos, alturas de linha.
    *   **Espaçamento**: Escalas baseadas em um valor base (ex: 4px ou 8px).
    *   **Bordas**: Raios (border-radius), larguras e estilos.
    *   **Sombras**: Elevações para criar profundidade.

2.  **Biblioteca de Componentes (Component Library)**
    *   Elementos de interface reutilizáveis construídos a partir dos tokens.
    *   **Átomos**: Botões, inputs, ícones, tipografia base.
    *   **Moléculas**: Grupos de átomos (ex: um campo de busca com input e botão).
    *   **Organismos**: Grupos de moléculas (ex: um cabeçalho de navegação completo).
    *   **Templates/Páginas**: Estruturas de layout completas.

3.  **Diretrizes de Uso (Guidelines)**
    *   Documentação sobre *como* e *quando* usar cada componente.
    *   Estados de componentes (default, hover, active, disabled, focus).
    *   Regras de acessibilidade (contraste, navegação por teclado, ARIA labels).
    *   Padrões de redação (UX Writing) para mensagens de erro, tooltips, etc.

### Princípios de Construção

*   **Atomic Design**: Metodologia (criada por Brad Frost) que divide a interface em componentes menores e reutilizáveis (Átomos, Moléculas, Organismos, Templates, Páginas).
*   **Acessibilidade First**: Componentes devem ser acessíveis desde a concepção (WCAG).
*   **Flexibilidade e Extensibilidade**: O sistema deve permitir adaptações sem quebrar a consistência global.
*   **Nomenclatura Semântica**: Nomeie tokens pelo seu *propósito*, não pelo seu *valor* (ex: use `color-primary` em vez de `color-blue`).

### Instruções de Uso

1.  **Auditoria Visual**: Antes de criar, analise as interfaces existentes para identificar padrões inconsistentes.
2.  **Definição de Tokens Base**: Comece definindo a paleta de cores, escala tipográfica e sistema de espaçamento.
3.  **Criação de Átomos**: Desenvolva os componentes mais básicos (botões, inputs de texto).
4.  **Documentação Simultânea**: Documente cada componente assim que for criado, incluindo estados e exemplos de uso.
5.  **Composição (Moléculas e Organismos)**: Combine os átomos para formar componentes mais complexos.
6.  **Revisão e Teste**: Teste os componentes em diferentes contextos e dispositivos para garantir responsividade e acessibilidade.
7.  **Evolução Contínua**: Um Design System é um produto vivo; atualize-o conforme as necessidades do projeto evoluem.

## 2. UX Research Skill

**Descrição**: Planejamento e execução de pesquisas de experiência do usuário (UX Research). Use para criar personas, mapas de jornada do usuário, roteiros de entrevista, análise de usabilidade e síntese de insights.

### Tipos de Pesquisa UX

| Método                  | Tipo          | Quando Usar                                          | Output                              |
|-------------------------|---------------|------------------------------------------------------|-------------------------------------|
| Entrevistas em Profundidade | Qualitativo | Entender motivações, comportamentos e dores          | Insights, citações, padrões         |
| Testes de Usabilidade   | Qualitativo   | Identificar problemas de usabilidade em protótipos   | Lista de problemas priorizados      |
| Pesquisa de Campo (Observação) | Qualitativo | Entender o contexto real de uso                 | Notas de campo, fotos, vídeos       |
| Questionários/Surveys   | Quantitativo  | Validar hipóteses em escala                          | Dados estatísticos, tendências      |
| Análise de Dados (Analytics) | Quantitativo | Entender o comportamento atual dos usuários     | Funis, mapas de calor, taxas        |
| Card Sorting            | Misto         | Definir arquitetura de informação                    | Estrutura de navegação              |
| Tree Testing            | Misto         | Validar a arquitetura de informação                  | Taxa de sucesso por tarefa          |

### Processo de Pesquisa

1.  **Definição do Problema**: Qual pergunta de pesquisa precisa ser respondida? Qual decisão de design será informada por essa pesquisa?
2.  **Planejamento**: Escolha o método adequado, defina o perfil dos participantes e crie o roteiro/questionário.
3.  **Recrutamento**: Encontre participantes que representem os usuários reais do produto.
4.  **Coleta de Dados**: Execute as sessões de pesquisa com rigor e empatia.
5.  **Análise e Síntese**: Identifique padrões, agrupe insights e priorize descobertas.
6.  **Comunicação**: Apresente os insights de forma clara e acionável para a equipe de produto e design.

### Criação de Personas

Uma persona é uma representação fictícia e baseada em dados de um segmento de usuários. Inclua:
*   **Nome e Foto**: Humaniza o personagem.
*   **Dados Demográficos**: Idade, profissão, localização.
*   **Objetivos**: O que ela quer alcançar com o produto?
*   **Frustrações (Pain Points)**: Quais são suas maiores dificuldades?
*   **Comportamentos**: Como ela usa tecnologia? Quais são seus hábitos?
*   **Citação Representativa**: Uma frase que capture sua essência.

### Mapa de Jornada do Usuário (User Journey Map)

Visualiza a experiência completa do usuário ao interagir com um produto ou serviço. Inclua:
*   **Fases**: As etapas da jornada (ex: Descoberta, Consideração, Compra, Uso, Suporte).
*   **Ações**: O que o usuário faz em cada fase.
*   **Pensamentos**: O que o usuário pensa em cada fase.
*   **Emoções**: Como o usuário se sente (use uma curva emocional).
*   **Pontos de Dor**: Onde a experiência é frustrante ou confusa.
*   **Oportunidades**: Onde o design pode melhorar a experiência.

### Roteiro de Entrevista (Estrutura Base)

1.  **Abertura (5 min)**: Apresentação, objetivo da entrevista, pedido de permissão para gravar.
2.  **Aquecimento (5 min)**: Perguntas sobre o contexto do participante (profissão, rotina).
3.  **Exploração (30-40 min)**: Perguntas abertas sobre o tema central. Evite perguntas de "sim/não".
4.  **Aprofundamento**: Siga os temas que surgirem com "Por quê?", "Me conta mais sobre isso" e "Como você se sentiu?".
5.  **Encerramento (5 min)**: Pergunte se há algo que o participante gostaria de adicionar. Agradeça.

### Template de Persona

```markdown
# Persona: [Nome da Persona]

> "[Citação representativa que captura a essência desta persona]"

---

## Perfil

| Atributo        | Detalhe                          |
|-----------------|----------------------------------|
| **Idade**       | [XX anos]                        |
| **Profissão**   | [Cargo/Profissão]                |
| **Localização** | [Cidade, Estado]                 |
| **Educação**    | [Nível de escolaridade]          |
| **Renda**       | [Faixa de renda]                 |
| **Família**     | [Estado civil, filhos, etc.]     |

---

## Objetivos

O que esta persona quer alcançar com o produto/serviço?

1. [Objetivo principal]
2. [Objetivo secundário]
3. [Objetivo terciário]

---

## Frustrações (Pain Points)

Quais são as maiores dores e dificuldades desta persona?

1. [Frustração principal]
2. [Frustração secundária]
3. [Frustração terciária]

---

## Comportamentos e Hábitos

- **Uso de Tecnologia**: [Descreva como usa dispositivos e apps]
- **Fontes de Informação**: [Onde busca informações: redes sociais, blogs, etc.]
- **Processo de Decisão de Compra**: [Como toma decisões de compra]
- **Rotina Relevante**: [Aspectos da rotina que impactam o uso do produto]

---

## Motivações

O que move esta persona? Quais são seus valores e aspirações?

[Descreva em 2-3 frases as motivações profundas desta persona.]

---

## Cenário de Uso

[Descreva uma situação típica em que esta persona usaria o produto/serviço. Seja específico e narrativo.]

---

## Citações Reais (de Entrevistas)

> "[Citação 1 de uma entrevista real com usuários que representam esta persona]"

> "[Citação 2 de uma entrevista real]"

---

## Insights para o Design

- [Implicação de design 1 baseada nos objetivos/frustrações desta persona]
- [Implicação de design 2]
- [Implicação de design 3]
```

## 3. Landing Page UX Skill

**Descrição**: Design e otimização de landing pages de alta conversão. Use para estruturar seções, definir hierarquia de conteúdo, otimizar CTAs, reduzir fricção e aumentar a taxa de conversão de páginas de destino.

### Anatomia de uma Landing Page de Alta Conversão

Uma landing page eficaz segue uma estrutura narrativa que guia o visitante do problema à solução e da solução à ação.

#### Seções Essenciais (em ordem)

1.  **Hero Section (Dobra)**
    *   Proposta de Valor Principal (headline): O que é, para quem é e qual o benefício principal.
    *   Subheadline: Complementa a headline com mais contexto.
    *   CTA Primário: Botão de ação principal, visível sem scroll.
    *   Imagem/Vídeo Hero: Mostra o produto em uso ou o resultado desejado.

2.  **Social Proof (Prova Social Imediata)**
    *   Logos de clientes ou parceiros conhecidos.
    *   Número de clientes, usuários ou avaliações.
    *   Estrelas de avaliação (ex: "4.9/5 de mais de 2.000 avaliações").

3.  **Problema/Contexto**
    *   Identifique a dor do usuário de forma empática.
    *   Mostre que você entende a situação dele.

4.  **Solução/Benefícios**
    *   Apresente o produto como a solução para o problema identificado.
    *   Foques em benefícios (transformações), não em características técnicas.
    *   Use ícones e textos curtos para facilitar a leitura.

5.  **Como Funciona**
    *   Explique o processo em 3-5 passos simples.
    *   Reduza a percepção de complexidade.

6.  **Prova Social Detalhada**
    *   Depoimentos com foto, nome e cargo/empresa.
    *   Cases de sucesso com resultados mensuráveis.
    *   Avaliações de plataformas externas (Google, Trustpilot, etc.).

7.  **Oferta e Preço**
    *   Apresente os planos/preços de forma clara.
    *   Destaque o plano recomendado.
    *   Liste o que está incluído em cada plano.

8.  **FAQ (Perguntas Frequentes)**
    *   Responda as objeções mais comuns.
    *   Reduza a incerteza e o risco percebido.

9.  **CTA Final**
    *   Repita o CTA principal com uma mensagem de urgência ou garantia.
    *   Inclua a garantia de devolução do dinheiro (se aplicável).

### Princípios de UX para Conversão

*   **Clareza acima de criatividade**: O visitante deve entender o que você oferece em menos de 5 segundos.
*   **Uma página, uma ação**: Remova links de navegação, menus e distrações. O único destino deve ser o CTA.
*   **Velocidade de carregamento**: Cada segundo a mais de carregamento reduz a conversão em até 7%. Otimize imagens e use CDN.
*   **Mobile First**: A maioria do tráfego vem de dispositivos móveis. Projete para mobile primeiro.
*   **Contraste do CTA**: O botão de CTA deve se destacar visualmente do restante da página.
*   **Redução de Fricção**: Minimize o número de campos em formulários. Peça apenas o essencial.

### Hierarquia Visual na Landing Page

| Elemento           | Tamanho Relativo | Peso Visual |
|--------------------|------------------|-------------|
| Headline Principal | Maior            | Máximo      |
| Subheadline        | Grande           | Alto        |
| Botão CTA          | Médio-Grande     | Máximo (cor)|
| Benefícios         | Médio            | Médio       |
| Corpo de Texto     | Normal           | Baixo       |
| Rodapé/Legal       | Pequeno          | Mínimo      |

### Checklist de Otimização

*   [ ] A proposta de valor está clara na headline?
*   [ ] O CTA está visível sem scroll (above the fold)?
*   [ ] Há pelo menos uma forma de prova social na dobra?
*   [ ] A página tem um único objetivo/ação?
*   [ ] O formulário pede apenas campos essenciais?
*   [ ] A página carrega em menos de 3 segundos?
*   [ ] A experiência mobile está otimizada?
*   [ ] As objeções principais são respondidas no FAQ?
*   [ ] Há uma garantia clara para reduzir o risco percebido?
*   [ ] O contraste do botão CTA é suficiente?

### Wireframe de Landing Page

```markdown
# Wireframe de Landing Page — [Nome do Produto/Serviço]

## Seção 1: Hero (Dobra)

```
+----------------------------------------------------------+
|  LOGO                              [CTA Secundário]      |
+----------------------------------------------------------+
|                                                          |
|  [HEADLINE PRINCIPAL — Proposta de Valor em 1 frase]     |
|                                                          |
|  [Subheadline — Complemento com mais contexto e          |
|   benefício secundário. Máximo 2 linhas.]                |
|                                                          |
|  [★★★★★ 4.9/5 — +2.000 clientes satisfeitos]            |
|                                                          |
|  [ BOTÃO CTA PRINCIPAL — Verbo de Ação + Benefício ]     |
|                                                          |
|  [Imagem/Vídeo do produto em uso ou resultado]           |
+----------------------------------------------------------+
```

**Copy Sugerido:**
- Headline: "[Resultado Desejado] sem [Obstáculo Principal]"
- Subheadline: "A solução que [Público-Alvo] usa para [Benefício] em [Prazo]."
- CTA: "Começar Gratuitamente" / "Garantir Minha Vaga" / "Ver Demonstração"

---

## Seção 2: Logos de Clientes / Prova Social Rápida

```
+----------------------------------------------------------+
|  "Usado por mais de [X] empresas como:"                  |
|  [Logo 1]  [Logo 2]  [Logo 3]  [Logo 4]  [Logo 5]       |
+----------------------------------------------------------+
```

---

## Seção 3: O Problema

```
+----------------------------------------------------------+
|  [Título: Você já se sentiu assim?]                      |
|                                                          |
|  [Ícone/Ilustração]  [Dor 1 — Descrição curta]          |
|  [Ícone/Ilustração]  [Dor 2 — Descrição curta]          |
|  [Ícone/Ilustração]  [Dor 3 — Descrição curta]          |
|                                                          |
|  [Parágrafo empático: "Você não está sozinho(a)..."]     |
+----------------------------------------------------------+
```

---

## Seção 4: A Solução / Benefícios

```
+----------------------------------------------------------+
|  [Título: Apresentando [Nome do Produto]]                |
|  [Subtítulo: A forma mais simples de [Resultado]]        |
|                                                          |
|  [Ícone] [Benefício 1]    [Ícone] [Benefício 2]         |
|  [Texto curto]            [Texto curto]                  |
|                                                          |
|  [Ícone] [Benefício 3]    [Ícone] [Benefício 4]         |
|  [Texto curto]            [Texto curto]                  |
+----------------------------------------------------------+
```

---

## Seção 5: Como Funciona

```
+----------------------------------------------------------+
|  [Título: Como funciona?]                                |
|                                                          |
|  [Passo 1]  →  [Passo 2]  →  [Passo 3]                  |
|  [Ícone]       [Ícone]       [Ícone]                     |
|  [Descrição]   [Descrição]   [Descrição]                 |
+----------------------------------------------------------+
```

---

## Seção 6: Depoimentos

```
+----------------------------------------------------------+
|  [Título: O que nossos clientes dizem]                   |
|                                                          |
|  ┌────────────────┐  ┌────────────────┐                  |
|  │ [Foto] [Nome]  │  │ [Foto] [Nome]  │                  |
|  │ [Cargo]        │  │ [Cargo]        │                  |
|  │ ★★★★★          │  │ ★★★★★          │                  |
|  │ "[Depoimento]" │  │ "[Depoimento]" │                  |
|  └────────────────┘  └────────────────┘                  |
+----------------------------------------------------------+
```

---

## Seção 7: Preços

```
+----------------------------------------------------------+
|  [Título: Escolha o plano ideal para você]               |
|                                                          |
|  ┌──────────┐  ┌──────────────────┐  ┌──────────┐       |
|  │  BÁSICO  │  │   PROFISSIONAL   │  │ EMPRESA  │       |
|  │  R$XX/mês│  │ ★ RECOMENDADO ★  │  │  R$XX/mês│       |
|  │          │  │   R$XX/mês       │  │          │       |
|  │ [Feature]│  │ [Feature]        │  │ [Feature]│       |
|  │ [Feature]│  │ [Feature]        │  │ [Feature]│       |
|  │ [CTA]    │  │ [CTA Destaque]   │  │ [CTA]    │       |
|  └──────────┘  └──────────────────┘  └──────────┘       |
+----------------------------------------------------------+
```

---

## Seção 8: FAQ

```
+----------------------------------------------------------+
|  [Título: Perguntas Frequentes]                          |
|                                                          |
|  ▼ [Pergunta 1 — Objeção mais comum]                     |
|    [Resposta clara e tranquilizadora]                    |
|                                                          |
|  ▼ [Pergunta 2 — Sobre preço/cancelamento]               |
|    [Resposta]                                            |
|                                                          |
|  ▼ [Pergunta 3 — Sobre resultados/prazo]                 |
|    [Resposta]                                            |
+----------------------------------------------------------+
```

---

## Seção 9: CTA Final

```
+----------------------------------------------------------+
|  [Título: Pronto para [Resultado Desejado]?]             |
|                                                          |
|  [Subheadline com urgência ou garantia]                  |
|                                                          |
|  [ BOTÃO CTA PRINCIPAL ]                                 |
|                                                          |
|  🔒 Garantia de [X] dias. Sem risco para você.           |
+----------------------------------------------------------+
```
