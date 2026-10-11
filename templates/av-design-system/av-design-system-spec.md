# Potenza Motos Elétricas · Design System

Fonte única da verdade do sistema visual da Potenza Motos Elétricas. Versão v1.0 · 2026.

Use estes tokens ao gerar qualquer interface, peça ou componente da marca.

## 1. Cores

| Token | Hex | Uso |
|---|---|---|
| `--primary` | `#5AF205` | Verde neon do logo e da fachada. Destaques, ícones e CTA sobre fundo escuro. Nunca como texto sobre fundo claro (contraste 1,6:1) |
| `--accent` | `#A6FF4D` | Realces, chips e destaques pontuais |
| `--deep` | `#2E7D00` | Verde para texto e botões sobre fundo claro (5,2:1 no branco); início do gradiente |
| `--deep-hover` | `#3C9C00` | Hover de CTA |
| `--bg` (dark) | `#000000` | Fundo do tema escuro |
| `--bg` (light) | `#F4F4F1` | Fundo do tema claro |

**Gradiente de marca (CTA):** `linear-gradient(90deg, #2E7D00, #5AF205)`. Versão 135° para ícones e bordas.

**Escala de texto (opacidades sobre o fundo):** t1 100% (títulos) · t2 72% (corpo forte) · t3 50–58% (corpo) · t4 35–46% (labels) · t5 22–42% (meta) · t6 (divisores).
Contraste mínimo: **4.5:1** para texto normal, 3:1 para texto grande. Nunca use cinza claro em texto de corpo.

**Superfícies:** fills de 1.5% a 5% sobre o fundo; linhas de 4% a 10%. O tema claro espelha os mesmos papéis com preto translúcido.

## 2. Tipografia

**Saira** (títulos, 700–900, itálico permitido em chamadas) + **Inter** (corpo e textos longos, 400–600). Ambas gratuitas no Google Fonts. No Canva, se Saira não estiver disponível, use uma sans larga e geométrica parecida e mantenha Inter no corpo.

| Papel | Tamanho | Line-height | Peso | Tracking |
|---|---|---|---|---|
| Display | clamp(2.5rem, 6vw, 4.5rem) | 1.0 | 900 | −0.03em |
| H1 | clamp(2rem, 4.5vw, 3.5rem) | 1.05 | 900 | −0.025em |
| H2 | clamp(1.5rem, 3vw, 2.5rem) | 1.1 | 700 | −0.02em |
| H3 | 1.4rem | 1.2 | 700 | normal |
| H4 | 1.125rem | 1.3 | 700 | normal |
| Body L | 1rem | 1.8 | 400 | normal |
| Body M | 0.875rem | 1.75 | 400 | normal |
| Overline / label | 0.6rem | — | 600–700 | 0.18–0.25em, uppercase |

Corpo com no máximo 65–75 caracteres por linha.

## 3. Layout e espaçamento

- Container máximo: **74rem**; padding lateral `clamp(1.25rem, 4vw, 2.75rem)`.
- Seções: padding vertical `clamp(4.5rem, 9vw, 8rem)`, separadas por linha de 1px.
- Raio padrão: **4px** (cards e botões); 9999px para chips e toggles.
- Grids fluidos: `repeat(auto-fit, minmax(Xrem, 1fr))` (X de 10 a 18 conforme a densidade).
- Breakpoints: **960px** (hero passa a 2 colunas) · **900px** (menu vira dropdown) · **640px** (compacta labels).
- Alvos de toque no mobile: mínimo **44×44px**.

## 4. Componentes

- **Botões:** uppercase, 0.72rem, peso 800, tracking 0.1em, padding 0.9rem 1.8rem. Variantes: `primary` (gradiente de marca), `outline`, `ghost`, `solid`. Hover: leve `translateY(-1px)` + sweep de cor subindo.
- **Cards:** fundo translúcido + borda de 1px + blur. Nunca aninhe cards.
- **Chips/badges:** pílula com borda em gradiente sutil; ponto pulsante para status "live".
- **Inputs:** fundo de fill 3%, borda 1px, foco na cor da marca. Todo input tem label associado.
- **Icon box:** 2.75rem, fundo e borda em verde translúcido chapado, sem gradiente.
- **Ícones:** conjunto line, traço 1.6px, grade 24×24, **cor chapada** (#5AF205 no fundo escuro, #2E7D00 no fundo claro). Nunca usar gradiente em ícones.

## 5. Movimento

| Token | Duração | Uso | Curva |
|---|---|---|---|
| micro | 100–150ms | hover, foco | linear |
| ui | 250–350ms | botão, tooltip | ease-back |
| enter | 500–700ms | card, reveal | ease-apple `cubic-bezier(0.16,1,0.3,1)` |
| cinematic | 900–1400ms | hero, texto escalonado | ease-expo `cubic-bezier(0.19,1,0.22,1)` |
| ambient | 3–8s | pulse, float, shimmer | ease-in-out (loop) |

Sempre respeitar `prefers-reduced-motion: reduce`.

## 6. Marca

Dois temas convivem no mesmo arquivo: a logo **clara** aparece no tema escuro e a **escura** no tema claro. Nunca recolorir, distorcer, girar ou aplicar efeitos fora do documentado.

Assets disponíveis (provisórios, extraídos do logo raster gerado por IA):
| Arquivo | Papel | Uso |
|---|---|---|
| `pme-horizontal-white.png` | Logo principal | Fundos escuros: posts, stories, capas |
| `pme-horizontal-black.png` | Logo principal | Fundos claros |
| `pme-selo-white.png` | Selo circular | Avatar de perfil, adesivo, marca d'água em fundo escuro |
| `pme-selo-black.png` | Selo circular | Fundos claros |
| `pme-raio-white.svg` / `.png` | Símbolo (raio), vetor chapado #5AF205 | Favicon, ícone, avatar, detalhe gráfico em fundo escuro |
| `pme-raio-black.svg` / `.png` | Símbolo (raio), vetor chapado #2E7D00 | Fundos claros, impressão a uma cor |

Limitações: os logos horizontal e selo são PNG com efeitos de brilho e metal; não servem para bordado, recorte, impressão a uma cor ou tamanho abaixo de 48px. Substituir por versão vetorial chapada quando existir. O raio já é vetor chapado.

## 7. Tom de voz e conteúdo

- Primeira loja de motos elétricas de Serafina Corrêa (RS). Argumentos: test-ride na loja, orientação na entrega, atendimento local, economia.
- Tom próximo, regional e claro. Evitar exagero "esportivo"; o público inclui pessoas mais velhas (triciclo) e pais que compram para os filhos.
- Quando o assunto for jovens, falar com os pais: segurança, responsabilidade, uso de capacete. Nunca anúncio direcionado a menores.
- Só afirmar "sem CNH e sem emplacamento" para modelos confirmados como autopropelidos (até 1.000 W, 32 km/h, 70 cm de largura). Nunca prometer isso para o triciclo sem confirmação.
- Fotos reais da loja, dos modelos e de entregas a clientes têm prioridade sobre imagens geradas por IA.
- Contato: WhatsApp (54) 98438-7607 · Rua José Veríssimo, esquina com Av. Miguel Soccol, ao lado do Clube dos Motoristas, Serafina Corrêa.
