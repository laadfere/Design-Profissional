📝 Descrição Geral do Módulo
Esta pasta contém todos os ativos essenciais (HTML, CSS e JavaScript) para a construção da interface do usuário (Front-end) do projeto. A estrutura é baseada no Material Design do Google e utiliza o framework Materialize CSS para garantir um design moderno, responsivo e com componentes interativos prontos para uso.

🏗️ Estrutura e Funções dos Arquivos
Os arquivos estão divididos em três categorias principais: Estrutura, Estilização e Interação.

1. Estrutura e Conteúdo (HTML)
Arquivo	Tecnologia	Finalidade
index.html	HTML5	É a página inicial e o esqueleto de toda a interface. Ele contém a estrutura semântica do conteúdo, define a ordem dos elementos (navegação, corpo, rodapé) e realiza a importação de todos os arquivos CSS e JavaScript necessários para o funcionamento e estilo.

Exportar para as Planilhas

2. Estilização (CSS)
Arquivo	Tecnologia	Finalidade
materialize.css	CSS (Framework)	Versão completa e legível do framework Materialize. Contém todas as regras de estilo para os componentes, layouts de grid, tipografia, cores e utilitários.
materialize.min.css	CSS (Minificado)	Versão otimizada e minificada do Materialize, ideal para o ambiente de produção. Arquivos minificados são menores, removendo espaços e comentários, o que acelera o tempo de carregamento da página.
estilos.css	CSS (Customizado)	Contém as regras de estilo personalizadas e específicas do projeto. Este arquivo é crucial para sobrescrever estilos padrões do Materialize, definir cores de tema, ajustar margens e estilizar elementos que são únicos à sua aplicação.

Exportar para as Planilhas

3. Interação e Comportamento (JavaScript)
Arquivo	Tecnologia	Finalidade
materialize.js	JavaScript (Framework)	Versão completa e legível do código JavaScript do Materialize. Contém a lógica de comportamento de componentes interativos, como Dropdowns, Modals, SideNav (menu lateral) e o efeito Parallax.
materialize.min.js	JavaScript (Minificado)	Versão otimizada e minificada do JavaScript do Materialize, usada em produção para garantir o carregamento rápido da lógica interativa.
configuracoes.js	JavaScript (Customizado)	Contém o código JavaScript específico do projeto responsável por inicializar os componentes do Materialize e adicionar qualquer lógica personalizada. O uso da sintaxe jQuery ($(function() { ... });) garante que o código seja executado apenas quando a página estiver totalmente carregada. No seu exemplo, ele inicializa o menu lateral (.sidenav) e o efeito parallax.

Exportar para as Planilhas

🚀 Integração e Fluxo de Carregamento
Todos os arquivos trabalham em conjunto, seguindo uma ordem de carregamento otimizada (como visto no index.html):

CSS no <head>: O browser carrega os estilos (Materialize e Customizados) primeiro, para evitar que a página apareça "desformatada" antes de ter o visual completo.

HTML no <body>: O conteúdo estrutural é carregado.

JavaScript no Fim do <body>: Os scripts (jQuery, Materialize e configuracoes.js) são carregados por último para não bloquear a renderização visual da página, garantindo que os componentes estejam disponíveis para interação logo após o carregamento da estrutura.
