# Potenza Motos Elétricas · Design System

Identidade visual e regras de produção da **Potenza Motos Elétricas**, de Serafina Corrêa (RS). Este repositório serve a duas pessoas: quem cria peças à mão (Canva) e qualquer IA (Claude, ChatGPT, Gemini) que vá gerar posts, carrosséis, stories e outros materiais da marca.

## O que tem aqui

| Arquivo | Para quem | O que é |
|---|---|---|
| [`templates/av-design-system/av-design-system-spec.md`](templates/av-design-system/av-design-system-spec.md) | IA | **Regras da marca**: cores, fontes, logos, tom de voz e o que não pode ser dito. É o arquivo mais importante. |
| [`GUIA-PRODUCAO.md`](GUIA-PRODUCAO.md) | IA e pessoas | **Como montar as peças**: formatos, grade, estrutura de carrossel, post de produto, oferta, entrega, story. |
| [`PROMPTS.md`](PROMPTS.md) | Pessoas | Prompts prontos para copiar e colar em qualquer IA. |
| [`templates/av-design-system/images/`](templates/av-design-system/images/) | Todos | Logos em PNG transparente e o símbolo (raio) em SVG. |
| [`templates/av-design-system/av-design-system.html`](templates/av-design-system/av-design-system.html) | Pessoas | Página visual do design system (abrir no navegador). |
| [`templates/av-design-system/av-design-system-standalone.html`](templates/av-design-system/av-design-system-standalone.html) | Pessoas | Mesma página em arquivo único, para mandar por WhatsApp ou e-mail. |
| [`AGENTS.md`](AGENTS.md) | IA | Instrução curta para agentes que leem o repositório direto. |

## Resumo rápido da marca

- **Verde neon `#5AF205`** sobre **preto `#000000`**. No fundo claro, o verde de texto é **`#2E7D00`**.
- **Saira** nos títulos, **Inter** no texto.
- Ícones sempre em **cor chapada**, sem gradiente.
- Tom próximo e regional. Fala com adultos, pessoas mais velhas e **pais** (nunca anúncio direcionado a menores).
- "Sem CNH e sem emplacamento" **só** para modelos confirmados como autopropelidos.
- WhatsApp **(54) 98438-7607** · Rua José Veríssimo, esquina com Av. Miguel Soccol, ao lado do Clube dos Motoristas, Serafina Corrêa.

## Como usar com IA

### Claude (Projeto)
1. Crie um Projeto "Potenza".
2. Conecte este repositório pelo GitHub (ou envie os arquivos): `av-design-system-spec.md`, `GUIA-PRODUCAO.md` e os logos de `images/`.
3. Cole nas instruções do Projeto: *"Antes de criar qualquer material, siga o spec da marca e o guia de produção deste projeto. Use só as cores, fontes e logos documentados."*
4. Peça usando os prompts de [`PROMPTS.md`](PROMPTS.md).

### ChatGPT (GPT personalizado ou Projeto)
1. Crie um GPT ou Projeto e envie como conhecimento: o spec, o guia de produção e os logos.
2. Use a mesma instrução do item 3 acima.
3. Para gerar imagem, peça primeiro o **texto e o layout** de cada slide; depois a imagem. A IA de imagem erra texto, preço e logo com frequência: aplique o logo real e os textos no Canva.

### Gemini (Gem)
Mesmo processo: crie um Gem, anexe o spec e o guia, e cole a instrução.

### Canva
- Cadastre no **Brand Kit**: as cores do spec, as fontes Saira e Inter e os logos de `images/`.
- Use a IA para gerar **copy e estrutura**; monte a peça no Canva com fotos reais.

### Links diretos para os logos (para IAs que leem URL)
- Logo horizontal claro: `https://raw.githubusercontent.com/agenciagufo/potenzaDS/main/templates/av-design-system/images/pme-horizontal-white.png`
- Selo claro: `https://raw.githubusercontent.com/agenciagufo/potenzaDS/main/templates/av-design-system/images/pme-selo-white.png`
- Raio (SVG): `https://raw.githubusercontent.com/agenciagufo/potenzaDS/main/templates/av-design-system/images/pme-raio-white.svg`

## Limitações conhecidas

- O logo horizontal e o selo foram gerados por IA e estão em PNG com brilho e efeito metálico. Não servem para bordado, adesivo de recorte, impressão a uma cor ou tamanhos abaixo de 48 px. Falta a versão vetorial chapada.
- O raio já é vetor chapado (SVG) e pode ser usado em qualquer aplicação.
- O nome "Potenza" ainda precisa de verificação no INPI antes de grandes investimentos em material.

## Versão

v1.0 · outubro de 2026. Atualize o spec primeiro; os outros arquivos seguem o spec.
