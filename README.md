# 🏎️ Porsche Sales Intelligence — Dashboard Interativa

Dashboard interativa de análise de vendas da Porsche, desenvolvida em HTML com auxílio de Inteligência Artificial, como parte do desafio **Criando uma Dashboard da Porsche com Agentes de IA**, da formação Santander Excel 2026, na [DIO](https://www.dio.me/).

O projeto transforma uma base de vendas em uma experiência visual interativa, permitindo analisar o desempenho comercial por modelo, ano do veículo, cidade e método de pagamento.

## 🌐 Acesse o projeto

- **Dashboard publicada:** [Acesse a Porsche Sales Intelligence](https://caduos.github.io/Dashboard_Porsche_Sales/)
- **Repositório:** [Porsche Sales Intelligence no GitHub](https://github.com/cadUoS/Dashboard_Porsche_Sales)

## 📊 Visão geral

A proposta é transformar dados de vendas em informações úteis para a tomada de decisão, utilizando uma interface inspirada na identidade visual da Porsche, com uma estética elegante, refinada e moderna.

A dashboard foi construída em HTML e reúne indicadores, gráficos e filtros interativos em uma única página, sem depender do Excel para visualizar os resultados.

## 🎯 Perguntas de negócio

O desenvolvimento foi orientado por três perguntas principais:

### 1. Quais são os modelos de Porsche mais vendidos por cidade?

Identificar os modelos com maior volume de vendas em cada cidade, permitindo observar diferenças na preferência dos consumidores e oportunidades comerciais por região.

### 2. Qual é o ano de modelo dos veículos com maior volume de vendas no período?

Analisar a distribuição das vendas por ano do veículo, identificando quais anos de modelo apresentam maior saída dentro do período selecionado.

### 3. Quais são os modelos mais populares em cada cidade?

Explorar o ranking de modelos e os indicadores por cidade para identificar os veículos com maior presença nas vendas, apoiando análises de demanda e possíveis estratégias comerciais locais.

## 📌 Indicadores e funcionalidades

A dashboard conta com os seguintes recursos:

- **Total de vendas:** quantidade de registros considerados após a aplicação dos filtros.
- **Faturamento:** soma dos valores das vendas no recorte selecionado.
- **Modelo líder:** modelo com maior volume de vendas.
- **Cidade líder:** cidade com maior quantidade de vendas.
- **Ranking de modelos:** comparação entre os veículos mais vendidos.
- **Análise por cidade:** identificação do modelo líder em cada localidade.
- **Distribuição por ano de modelo:** visualização dos anos com maior volume de vendas.
- **Métodos de pagamento:** análise da participação de cada forma de pagamento.
- **Insights automáticos:** destaques atualizados conforme os filtros aplicados.

### 🔎 Filtros interativos

É possível explorar os dados utilizando quatro filtros principais:

- Modelo da Porsche;
- Ano do modelo;
- Cidade;
- Método de pagamento.

Também é possível delimitar o período da análise, facilitando a comparação de resultados em diferentes recortes.

## 🎨 UI/UX e identidade visual

O design foi inspirado no site oficial da Porsche Brasil, priorizando uma experiência visual premium.

Principais características:

- Interface escura e sofisticada;
- Tipografia limpa e hierarquia visual bem definida;
- Destaques em vermelho, inspirados na identidade esportiva da marca;
- Indicadores e gráficos com cores de destaque;
- Cards com contraste e organização visual;
- Layout adaptável a diferentes tamanhos de tela.

**Referência visual:** [Porsche Brasil](https://www.porsche.com/brazil/pt/)

## 🛠️ Tecnologias utilizadas

- **HTML5:** estrutura da dashboard.
- **CSS3:** estilização, layout responsivo e identidade visual.
- **JavaScript:** filtros, cálculos dos indicadores, gráficos e geração de insights.
- **Microsoft Excel:** origem e organização da base de dados.
- **ChatGPT com Canvas:** apoio à criação, estruturação e refinamento da dashboard.
- **Git e GitHub:** versionamento e hospedagem do código.
- **GitHub Pages:** publicação da dashboard na web.

## 🧹 Tratamento dos dados

O projeto utiliza a base sanitizada de vendas da Porsche disponibilizada no desafio da DIO, composta por 100 registros.

Para a análise, foram utilizadas as colunas sanitizadas referentes a:

- Data da venda;
- Modelo da Porsche;
- Ano do modelo;
- Preço da venda;
- Método de pagamento;
- Cidade.

Os dados foram organizados para permitir a aplicação dos filtros, a contagem de vendas, a soma do faturamento e a geração dos rankings.

A dashboard utiliza os dados incorporados ao próprio arquivo HTML, permitindo a execução diretamente no navegador, sem a necessidade de uma conexão com banco de dados.

## 🤖 Uso da Inteligência Artificial

O ChatGPT foi utilizado com o recurso Canvas como apoio ao desenvolvimento da dashboard.

O processo envolveu:

1. Definição das perguntas de negócio que orientariam a análise;
2. Estruturação dos filtros e dos indicadores;
3. Desenvolvimento da interface HTML;
4. Refinamento da identidade visual, buscando uma apresentação elegante e alinhada à marca Porsche;
5. Implementação dos gráficos, dos cálculos e dos insights dinâmicos;
6. Preparação do arquivo para publicação no GitHub Pages.

A construção foi realizada de forma iterativa, utilizando instruções em linguagem natural para ajustar a interface e as funcionalidades conforme os objetivos do projeto.

### Prompt utilizado como referência

> Desenvolva uma dashboard interativa em HTML, utilizando a base sanitizada de vendas da Porsche. A interface deve apresentar um visual elegante e refinado, inspirado no site oficial da Porsche Brasil.
>
> Inclua filtros por modelo da Porsche, ano do modelo, cidade, método de pagamento e período. Apresente indicadores de total de vendas, faturamento, modelo líder e cidade líder.
>
> A dashboard deve responder às perguntas: quais modelos são mais vendidos por cidade, qual ano de modelo apresenta maior volume de vendas no período e quais modelos são mais populares em cada cidade.
>
> Implemente gráficos, rankings e insights que sejam atualizados de acordo com os filtros selecionados. Mantenha o projeto em um único arquivo HTML, com CSS e JavaScript incorporados, pronto para publicação no GitHub Pages.

O resultado foi refinado posteriormente para aprimorar a apresentação visual, os destaques de cor e a experiência de navegação.

## 🚀 Publicação

A dashboard foi preparada para ser hospedada no GitHub Pages, permitindo que o projeto seja acessado diretamente pelo navegador.

Para reproduzir a publicação:

1. Crie um repositório público no GitHub;
2. Adicione o arquivo `index.html` à raiz do repositório;
3. Acesse **Settings → Pages**;
4. Selecione **Deploy from a branch**;
5. Escolha a branch `main` e a pasta `/(root)`;
6. Salve e aguarde a publicação.

## 📚 Aprendizados

O desenvolvimento deste projeto permitiu praticar conceitos de:

- Análise exploratória de dados;
- Definição de perguntas de negócio;
- Criação de indicadores e rankings;
- Desenvolvimento de dashboards interativas;
- Manipulação de dados com JavaScript;
- Uso de Inteligência Artificial no desenvolvimento;
- Design de interfaces e visualização de informações;
- Versionamento com Git e publicação com GitHub Pages.

## 👨‍💻 Autor

**Eduardo Silva**

Projeto desenvolvido como parte da formação **Santander Excel 2026**, na [DIO](https://www.dio.me/).

[GitHub](https://github.com/cadUoS) · [LinkedIn](https://www.linkedin.com/in/carlos-eduardo-de-oliveira-da-silva-11b682268/?isSelfProfile=true)

---

⭐ Se este projeto foi interessante para você, fique à vontade para explorar o repositório e conhecer a dashboard!
