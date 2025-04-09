# AI Tools Hub 🚀

![AI Tools Hub Screenshot](placeholder.png)
*<(Por favor, substitua `placeholder.png` por uma captura de tela real da sua aplicação!)*

Uma aplicação web dinâmica de página única (SPA) construída com HTML, Tailwind CSS e JavaScript puro para exibir um diretório selecionado de ferramentas de IA e tecnologia. Possui filtros, ordenação, múltiplas visualizações, um painel de administração para gerenciar ferramentas e carregamento por rolagem infinita.

## ✨ Funcionalidades

*   **Listagem Dinâmica de Ferramentas:** Exibe centenas de ferramentas a partir de um array JavaScript.
*   **Filtragem:** Filtra ferramentas por Categoria e Tipo (Grátis, Pago, Ambos).
*   **Ordenação:** Ordena ferramentas por Popularidade, Recência, Avaliação e Nome (A-Z, Z-A).
*   **Busca:** Procura ferramentas por nome, descrição ou categoria.
*   **Múltiplas Visualizações:** Alterna entre visualizações elegantes em Grade (Grid) e detalhadas em Lista (List).
*   **Rolagem Infinita (Infinite Scroll):** Carrega mais ferramentas automaticamente conforme você rola a página para baixo.
*   **Design Responsivo:** Adapta-se a diferentes tamanhos de tela (desktop, tablet, mobile).
*   **UI Futurista:** Tema escuro com estética moderna usando classes utilitárias do Tailwind CSS e variáveis CSS customizadas.
*   **Painel de Administração (Básico):**
    *   Requer login (credenciais padrão fornecidas).
    *   Adiciona novas ferramentas via formulário.
    *   Edita ferramentas existentes (carrega dados no formulário).
    *   Exclui ferramentas.
    *   Busca ferramentas dentro da lista de administração.
    *   Exporta dados das ferramentas como JSON.
    *   Importa dados das ferramentas de um JSON (substitui os dados existentes).
*   **Exibição de Estatísticas:** Mostra estatísticas chave como total de ferramentas, categorias, destaques e essenciais.
*   **Filtros Rápidos de Categoria:** Barra de rolagem horizontal com botões de categoria para filtragem rápida.

## 🔧 Tecnologias Utilizadas

*   **HTML:** Estrutura da página web.
*   **CSS:**
    *   **Tailwind CSS (via CDN):** Framework CSS *utility-first* para desenvolvimento rápido de UI. *(Nota: CDN é para desenvolvimento/demo. Use o CLI ou PostCSS para produção.)*
    *   **CSS Customizado:** No bloco `<style>` para variáveis de tema, animações e sobrescritas específicas.
*   **JavaScript (Puro):** Gerencia todo o comportamento dinâmico, filtros, renderização, lógica de administração, rolagem infinita, etc.
*   **Font Awesome:** Para ícones.
*   **Google Fonts:** Para tipografia customizada ('Inter' e 'Orbitron').
*   **Unsplash:** Usado via URLs para imagens de exemplo (requer conexão com a internet para carregar as imagens).

## 🚀 Como Começar

Como esta é uma aplicação de página única autocontida usando CDNs:

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/seu-usuario/ai-tools-hub.git
    cd ai-tools-hub
    ```
2.  **Abra o arquivo HTML:** Simplesmente abra o arquivo `index.html` (ou o nome que você salvou) diretamente no seu navegador web.

É isso! Nenhum passo de compilação ou servidor local é necessário para a funcionalidade básica (embora as imagens do Unsplash exijam conexão com a internet).

## ⚙️ Utilização

*   **Navegação:** Role para baixo para carregar mais ferramentas automaticamente (rolagem infinita).
*   **Filtrar/Ordenar:** Use os menus dropdown abaixo da seção principal para filtrar por categoria/tipo ou ordenar os resultados.
*   **Botões de Categoria:** Clique nos botões abaixo dos filtros dropdown para filtragem rápida por categoria.
*   **Busca:** Use a barra de busca principal na seção hero para encontrar ferramentas por palavra-chave.
*   **Alternar Visualização:** Use os ícones de lista/grade no cabeçalho (ou menu mobile) para alternar entre os layouts.
*   **Painel de Administração:**
    *   Clique no ícone de escudo (<i class="fas fa-user-shield"></i>) no canto inferior direito.
    *   Faça login usando as credenciais padrão:
        *   **Usuário:** `admin`
        *   **Senha:** `123456`
        *   **⚠️ IMPORTANTE: Essas credenciais estão fixas no código JavaScript. Para qualquer implantação real, implemente autenticação adequada no lado do servidor!**
    *   Dentro do painel, você pode adicionar, buscar, editar (clicando no ícone de edição, que preenche o formulário), excluir, importar e exportar dados de ferramentas.

## 🎨 Customização

*   **Dados das Ferramentas:** A lista principal de ferramentas é definida no array JavaScript `tools` dentro do bloco `<script>` no final do arquivo HTML. Você pode modificar diretamente este array ou substituir a lógica de geração para adicionar/alterar ferramentas.
*   **Categorias:** As categorias disponíveis são definidas no array JavaScript `CATEGORIES`. Modifique-o para alterar nomes de categorias, ícones ou palavras-chave usadas para geração de imagens.
*   **Estilo:**
    *   Cores do tema, fontes, etc., são definidas como variáveis CSS no bloco `<style>`. Modifique essas variáveis em `:root` para alterar a aparência geral.
    *   Classes utilitárias do Tailwind CSS são usadas extensivamente em todo o HTML para layout e estilo.

## 🤝 Contribuição

Contribuições são bem-vindas! Se você tiver sugestões ou encontrar bugs, por favor, abra uma *issue*. Se você gostaria de contribuir com código:

1.  Faça um *fork* do repositório.
2.  Crie uma nova *branch* (`git checkout -b feature/sua-feature`).
3.  Faça suas alterações.
4.  Faça o *commit* das suas alterações (`git commit -m 'Adiciona alguma feature'`).
5.  Faça o *push* para a *branch* (`git push origin feature/sua-feature`).
6.  Abra um *Pull Request*.

## 📄 Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE.md](LICENSE.md) (se você criar um) para detalhes.

## 🙏 Agradecimentos

*   [Tailwind CSS](https://tailwindcss.com/)
*   [Font Awesome](https://fontawesome.com/)
*   [Google Fonts](https://fonts.google.com/)
*   [Unsplash](https://unsplash.com/) pelas imagens de exemplo.
