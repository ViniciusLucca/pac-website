# Project Specifications - PAC (Pequenos Aprendizados Culturais)

## Project Overview
*   **Project Name:** Website Institucional PAC.
*   **Core Objective:** Democratizar o acesso à cultura brasileira para pessoas de baixa renda através da divulgação de saídas culturais e conteúdos educativos.
*   **Target Device:** Mobile-first (Otimizado para smartphones).
*   **Technical Stack:** HTML5, CSS3, JavaScript (Vanilla), Firebase (Firestore e Storage).

## Screen Inventory

### 1. Screen: Home
*   **Objective:** Atuar como o ponto central de navegação e introdução à marca.
*   **Components:**
    *   **Header:** Menu hambúrguer lateral e logotipo central.
    *   **Hero Section:** Banner de alto impacto visual ocupando o topo da tela.
    *   **Introduction:** Texto breve descrevendo a missão da ONG (aprox. 3-4 linhas).
    *   **Action Buttons:** Dois botões de largura total com os rótulos "SAÍDAS" e "GALERIA".
    *   **Footer:** Assinatura com o nome da ONG e o ano vigente.

### 2. Screen: Sobre a PAC
*   **Objective:** Apresentar a história e os valores da organização para gerar confiança.
*   **Components:**
    *   **Content Area:** Título em destaque seguido por texto institucional longo.
    *   **Imagery:** Espaço para uma imagem central representando o trabalho da equipe.
    *   **Navigation:** Botões para retornar à "Página Principal" ou avançar para "Próximas Saídas".

### 3. Screen: Expedições
*   **Objective:** Listar a próxima atividade disponível e servir de arquivo para o histórico da ONG.
*   **Section: Próxima Saída (Conversion):**
    *   **Layout:** Informações de logística à esquerda (Data, Endereço, Ponto de encontro) e imagem representativa à direita.
    *   **Call to Action:** Botão de destaque com o texto "Venha conosco!".
*   **Section: Saídas Anteriores (Archive):**
    *   **Cards:** Lista vertical de cartões contendo imagem do local, título, resumo do post e sistema de avaliação por estrelas.
    *   **Action:** Botão "Saiba mais" em cada card que direciona para a tela específica do Museu.

### 4. Screen: Saída Anterior (Museu da PAC)
*   **Objective:** Publicar conteúdo educativo e detalhado sobre as experiências culturais.
*   **Components:**
    *   **Header Detail:** Título da saída seguido da data do evento.
    *   **Main Image:** Foto de destaque do local visitado.
    *   **Blog Content:** Blocos de texto intercalados com imagens menores em estilo colagem (ligeiramente rotacionadas).
    *   **Social:** Link ou botão para comentários/interação (se aplicável ao cronograma).

### 5. Screen: Galeria
*   **Objective:** Exibir o impacto social através de registros fotográficos das saídas.
*   **Components:**
    *   **Image List:** Scroll vertical de fotografias com bordas arredondadas.
    *   **Captions:** Legendas curtas logo abaixo de cada foto.
    *   **Navigation:** Botão fixo ao final para retornar à "Página Principal".

## Functional Requirements
*   **Data Fetching:** O conteúdo das "Expedições" e "Galeria" deve ser carregado dinamicamente via Firebase Firestore.
*   **Performance:** Imagens devem utilizar carregamento preguiçoso (*lazy loading*) para economizar dados móveis dos usuários.
*   **Responsive Design:** O layout deve se ajustar perfeitamente entre dispositivos mobile e desktop, mantendo a prioridade na experiência móvel.
*   **Navigation:** O menu hambúrguer deve fornecer acesso rápido a todas as 5 telas de qualquer ponto do site.