# Prompts prontos · Potenza Motos Elétricas

Copie, troque o que está entre `[colchetes]` e cole na IA. Funcionam no Claude, no ChatGPT e no Gemini, desde que o **spec** e o **GUIA-PRODUCAO.md** estejam anexados ou conectados (veja o README).

Se a IA não tiver os arquivos, comece a conversa com o **Prompt 0**.

---

## Prompt 0 · Carregar a marca (quando a IA não tem os arquivos)

```
Você vai criar materiais para a Potenza Motos Elétricas, loja de motos elétricas (autopropelidos) em Serafina Corrêa (RS).
Leia e siga estas regras antes de qualquer coisa:
https://github.com/agenciagufo/potenzaDS
Arquivos principais: templates/av-design-system/av-design-system-spec.md e GUIA-PRODUCAO.md.
Resumo: verde #5AF205 sobre preto; verde #2E7D00 para texto em fundo claro; Saira nos títulos e Inter no texto; ícones em cor chapada, sem gradiente; tom próximo e regional; nunca prometer "sem CNH" para modelo não confirmado; nunca anúncio direcionado a menores; WhatsApp (54) 98438-7607.
Confirme que entendeu em 3 linhas antes de começar.
```

---

## Prompt 1 · Carrossel

```
Crie um carrossel de [6/7/8] slides para o Instagram da Potenza sobre: [tema].
Público: [pais / adultos que querem economizar / pessoas mais velhas].
Siga a estrutura de carrossel do GUIA-PRODUCAO.md (capa, contexto, conteúdo, prova, CTA).
Para cada slide, entregue:
- Título (até 6 palavras, indique a palavra que vai em verde)
- Texto de apoio (até 25 palavras)
- Sugestão de imagem (foto real da loja ou do produto, ou ícone)
- Posição dos elementos na grade 1080x1350
Depois, escreva a legenda com gancho, CTA e 3 a 5 hashtags locais.
```

## Prompt 2 · Post de produto

```
Crie um post de produto (1080x1350) para o modelo [nome do modelo].
Dados: autonomia [X km], velocidade máxima [X km/h], recarga [X horas], preço [R$ X ou "consulte"].
Classificação legal confirmada: [autopropelido / ciclomotor / não confirmada].
Siga o modelo "Post de produto" do GUIA-PRODUCAO.md.
Entregue: título, 3 destaques com ícone, preço, CTA, layout descrito e legenda.
Só use "sem CNH" se a classificação for autopropelido confirmado.
```

## Prompt 3 · Post de entrega ao cliente

```
Crie a arte e a legenda de entrega para: cliente [nome ou "cliente"], modelo [modelo], cidade [cidade].
A foto real será aplicada por mim. Siga o modelo "Post de entrega" do GUIA-PRODUCAO.md.
Tom caloroso e local, sem preço. Legenda curta agradecendo e convidando outros a fazer o test-ride.
```

## Prompt 4 · Oferta

```
Crie um post de oferta (1080x1350) e um story (1080x1920) para: [oferta, condição e validade].
Uma oferta só por peça. Preço ou condição em verde, Saira Black.
Respeite a área segura do story (250 px no topo e 340 px na base livres).
Entregue os textos, o layout de cada peça e a legenda.
```

## Prompt 5 · Sequência de stories

```
Crie uma sequência de [3 a 5] stories sobre [tema], com uma mensagem por story.
Inclua pelo menos uma enquete ou caixinha de perguntas e termine com link para o WhatsApp (54) 98438-7607.
Para cada story: texto, sticker interativo (se houver) e sugestão de fundo.
```

## Prompt 6 · Calendário do mês

```
Monte um calendário de conteúdo de [mês] para a Potenza, com [3] posts por semana.
Misture: produto, carrossel educativo, entrega ao cliente, institucional e oferta.
Para cada post: data, formato, tema, objetivo e título da capa.
Considere datas locais e sazonais relevantes para Serafina Corrêa (RS).
```

## Prompt 7 · Gerar a peça em HTML (para virar imagem)

```
Gere a peça [descrição] como um HTML de 1080x1350 px, usando exatamente:
- fundo #000000; destaque #5AF205; texto branco
- fontes do Google Fonts: Saira (títulos) e Inter (texto)
- logo: https://raw.githubusercontent.com/agenciagufo/potenzaDS/main/templates/av-design-system/images/pme-horizontal-white.png
- margem de 80 px
Sem gradiente em ícones. Entregue um HTML por slide.
```

## Prompt 8 · Revisar uma peça pronta

```
Revise esta peça [anexe a imagem] contra o spec da Potenza e o checklist do GUIA-PRODUCAO.md.
Liste o que está fora do padrão (cor, fonte, logo, promessa legal, público) e como corrigir.
```

---

## Dicas

- **Imagem gerada por IA erra texto e logo.** Use a IA para o texto e o layout, e monte no Canva com o logo real e uma foto real.
- **Sempre informe a classificação legal do modelo** ao pedir peças de produto.
- Se a resposta fugir do padrão, responda: *"Revise contra o spec da marca e corrija."*
