# Design

## Theme

Light SaaS, desktop-first, registo Linear/Attio. Justificação do tema claro: centro de comando usado em horário comercial, monitor de desktop em ambiente iluminado.

## Colors

- Background: `#F7F7F8`
- Surface: `#FFFFFF`
- Text: `#171717`; secundário `#6E6E76`; terciário `#9B9BA3`
- Border: `#E7E7E7`; divisores subtis `#EFEFF1`; hover `#F5F5F6`
- Accent (apenas CTAs e indicadores de estado): `#F45B35`; suave `#FEEFEA`
- Green (vitória / delta positivo): `#22A06B`; suave `#E7F5EF`
- Amber (warm / aviso): `#D99A00`; texto `#8A6200`; suave `#FBF3DE`
- Red (apenas vencido): `#D64545`; suave `#FBEAEA`
- Escala de score: hot ≥ 90 (`#C2410C` sobre `#FDEDE4`), warm 70–89 (amber), medium 50–69 (neutro `#6E6E76` sobre `#F4F4F5`), cold < 50 (neutro claro)

Sem gradientes. Sem sombras pesadas: apenas `0 1px 2px rgba(23,23,23,.04)` em cards.

## Typography

Inter (400, 500, 600, 700) com fallback de sistema.

- Base: 13px/1.45
- Etiquetas de secção: 11px, maiúsculas, tracking +0.05em
- Título da página: 16.5px/600; subtitulo 13px secundário
- Número de KPI: 21px/600, `font-variant-numeric: tabular-nums`
- Tabela: 13px; colunas numéricas com `tabular-nums`

## Layout

- Sidebar fixa de 236px com border-right; conteúdo em coluna única com grelhas internas.
- Header com saudação à esquerda e ações à direita.
- Grelha principal: KPIs em 4 colunas; depois 2 colunas (1.55fr / 1fr) para "o que fazer hoje" e "Pipeline"; tabela de leads em recuperação em largura total.
- Ritmo: gaps de 12px dentro de secções, 20px entre secções.

## Components

- Sidebar: card de workspace, pesquisa com kbd ⌘K, nav agrupada (Principal / Espaço) com chips de contagem, perfil no fundo.
- Header: saudação + botões de ícone (pesquisa, notificações com ponto), avatar, CTA primário "+ Novo Lead".
- Card KPI: surface branca, border 1px, radius 10px, etiqueta em maiúsculas, número, sub-linha (chip ou texto).
- Listas: linhas com divisores de 1px, hover `#FAFAFA`.
- Badges: score pill (dot + número), badge de estado com texto, botão ghost sm, botão primário.
- Secções com link de rodapé "Ver … →".
