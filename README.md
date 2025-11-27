📝 Descrição Geral
Este repositório serve como um portfólio técnico, reunindo projetos que demonstram competência em três áreas críticas do desenvolvimento: Modelagem de Dados Relacional, Desenvolvimento Front-end (com múltiplos frameworks) e Programação Estruturada em C (com foco em lógica e análise de algoritmos).

📂 Estrutura e Projetos
Domínio Principal	Projeto / Foco	Tecnologias Chave
Modelagem de Dados	Sistema de Controle de Qualidade do Ar (SCQA)	DER, Modelo Lógico/Físico, SQL, Dicionário de Dados.
Front-end (Projeto 1)	Landing Page Institucional	Materialize CSS, HTML5, JavaScript (Parallax).
Front-end (Projeto 2)	E-commerce / Bebidas de Luxo	Bootstrap 5, Leaflet (Mapas), CSS Customizado.
Linguagem C	Calculadora Científica & Benchmarks de Ordenação	C, structs, Manipulação de Arquivos, Análise de Algoritmos (O(N 
2
 ) vs O(NlogN)).

Exportar para as Planilhas

1. 📊 Módulo: Modelagem de Dados Relacional (SCQA)
Projeto de Banco de Dados para um Sistema de Controle de Qualidade do Ar (SCQA), cobrindo o ciclo completo de modelagem.

Habilidades Demonstradas
Modelagem Conceitual (DER) e Lógica.

Tradução para o Modelo Físico (SQL DDL).

Documentação técnica com Dicionário de Dados.

📁 Arquivos Chave
Modelo Conceitual SCQA.pdf

Modelo Logico SCQA.brM3

Modelo Fisico SCQA.sql

Dicionario de Dados SCQA.docx

2. 🌐 Módulo: Desenvolvimento Front-end (Múltiplos Frameworks)
Dois projetos distintos para demonstrar versatilidade na criação de interfaces de usuário responsivas, usando diferentes bibliotecas de design.

2.1. Projeto 1: Landing Page (Materialize CSS)
Uma página institucional ou de produto construída com o framework Materialize CSS.

Arquivo(s)	Função Principal
index.html (Materialize)	Estrutura da página principal com navegação lateral (sidenav) e efeito parallax.
materialize.min.css	Biblioteca CSS base do Material Design.
configuracoes.js (Materialize)	Script para inicializar os componentes interativos (sidenav e parallax).

Exportar para as Planilhas

2.2. Projeto 2: E-commerce de Luxo (Bootstrap & Leaflet)
Um conjunto de páginas (simulação de um E-commerce de itens de luxo) utilizando o framework Bootstrap 5 e a biblioteca Leaflet para geolocalização.

Arquivo(s)	Função Principal
index.html (Bootstrap)	Página inicial, incluindo a visualização de um mapa interativo (Leaflet) para localizar a loja ou a origem dos produtos.
BlueAgave.html, ChateauLafitte1787.html, KopiLuwak.html	Páginas de detalhes de produtos individuais, mantendo a consistência do design Bootstrap.
bootstrap.min.css	O framework CSS mais popular do mundo, garantindo um design responsivo e acessível.
styles.css (Custom)	Estilização personalizada, como a formatação da navbar e os ícones de redes sociais.
configuracoes.js (Leaflet)	Inicializa e configura o mapa interativo Leaflet no index.html, adicionando tiles e um marcador.

Exportar para as Planilhas

3. 🖥️ Módulo: Linguagem C e Algoritmos
Dois projetos de console que demonstram lógica, manipulação de dados em memória e análise de desempenho de código.

3.1. Projeto: Calculadora Científica (main.c)
Uma calculadora completa com funções matemáticas avançadas, demonstrando o uso de módulos e persistência de dados.

Funcionalidades: Operações básicas, trigonométricas, estatísticas (Média, Mediana), e manipulação de matrizes.

Destaque: Uso de structs para armazenar o Histórico de operações e salvamento/carregamento desse histórico em arquivo (.csv).

Documentação: O README.md original fornece detalhes sobre as operações e o processo de compilação.

3.2. Projeto: Análise de Algoritmos de Ordenação (main (1).c)
Um programa de benchmark que mede a eficiência de algoritmos de ordenação, utilizando alocação dinâmica e medição de tempo.

Algoritmos (Implícito): Selection Sort, Insertion Sort e Quick Sort (baseado no README.md do anexo).

Destaque: Implementa a estrutura Metrics para contabilizar Comparações e Trocas, fornecendo uma análise quantitativa da complexidade assintótica (Ex: Comparando O(N 
2
 ) com O(NlogN)).

Funções Principais: run_sort() (para medir o tempo de execução) e reset_metrics() (para garantir a precisão da contagem).

🚀 Tecnologias e Habilidades
Domínio	Conceitos e Ferramentas
Modelagem de Dados	DER, SQL (DDL/DML), Dicionário de Dados, BrModelo (Inferido).
Programação C	Ponteiros, structs, Alocação Dinâmica (malloc), I/O de Arquivos, Análise Algorítmica (Complexidade de Tempo e Espaço).
Web Front-end	HTML5, CSS3, JavaScript, jQuery, Bootstrap 5, Materialize CSS.
Geolocalização	Leaflet.js (Integração de mapas interativos).
