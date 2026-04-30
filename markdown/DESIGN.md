---
name: PAC (Pequenos Aprendizados Culturais)
colors:
  primary: "#228B22" # Verde Floresta (Identificado no logo)
  secondary: "#FFD700" # Amarelo Ouro
  accent: "#CC4E33" # Terracota/Laranja Queimado
  surface: "#F9F9F9" # Off-white (Fundo limpo para mobile)
  on-surface: "#3E2723" # Marrom Escuro (Para textos e ícones)
typography:
  body-md:
    fontFamily: Sans-serif (Limpa)
    fontSize: 16px
    fontWeight: 400
rounded:
  lg: 12px # Cantos arredondados consistentes
---

# Design System - PAC

## Overview
Uma interface orgânica, acolhedora e educativa focada em democratizar o acesso à cultura para pessoas de baixa renda. O design deve evocar um sentimento de "scrapbook" ou colagem comunitária, equilibrando o institucional com o artístico.

## Colors
- **Primary** (Verde): Usado em títulos de seções, marcadores laterais e no logo.
- **Secondary** (Amarelo): Destaque para categorias de matérias e botões de chamada secundária.
- **Accent** (Terracota): Blocos geométricos decorativos que sobrepõem imagens e links de interação.
- **On-surface** (Marrom): Navegação inferior, divisores verticais e ícones.

## Typography
- **Headlines**: Sans-serif em negrito, com uso ocasional de Capitulares (Drop Caps) no início de textos do Museu.
- **Body**: Sans-serif regular, priorizando espaçamento entre linhas para leitura em telas pequenas.
- **Metadata**: Fontes menores em cinza ou marrom para datas e instruções de comparecimento.

## Components
- **Cards de Expedição**: Bordas sólidas coloridas, cantos arredondados e imagens com aspecto de fotografia física.
- **Botões de Ação**: Largura total (Full width) para facilitar o clique no mobile, com cores vibrantes (Verde ou Amarelo).
- **Imagens Estilo Colagem**: Uso de `transform: rotate()` leve e sobreposição de blocos coloridos para simular recortes.

## Do's and Don'ts
- **Do**: Manter a hierarquia "Próxima Saída" sempre no topo do primeiro scroll.
- **Don't**: Usar tons de cinza industrial; prefira o marrom ou cores terrosas para divisores.
- **Do**: Garantir contraste de 4.5:1 para garantir que o conteúdo cultural seja legível para todos os públicos.
- **Don't**: Sobrecarregar a tela Home com muito texto; use botões de navegação direta (Saídas/Galeria).