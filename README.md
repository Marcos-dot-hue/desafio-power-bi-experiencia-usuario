# Desafio Power BI — Experiência do Usuário (UX)

## Dashboard Interativo de Vendas

Projeto desenvolvido como parte do Bootcamp de Power BI da **DIO**, com o objetivo de aprimorar a experiência do usuário na navegação e interação com relatórios gerenciais.

O desafio foi desenvolvido utilizando o **Microsoft Power BI Desktop** e a base de dados **Financial Sample**, explorando recursos de visualização, indicadores, filtros interativos e navegação entre páginas.

## Objetivo

Construir uma experiência de análise de dados mais intuitiva, permitindo que o usuário explore diferentes perspectivas do desempenho comercial por meio de páginas organizadas, indicadores e elementos interativos.

## Páginas do Relatório

### 1. Sales Report

Página principal do relatório, apresentando:

- Indicadores de vendas totais, lucro total e unidades vendidas.
- Gráfico de evolução mensal do lucro.
- Análise de vendas por segmento.
- Análise de vendas por produto.
- Botões de navegação entre as visões Geral e Temporal, utilizando indicadores (bookmarks).

### 2. Análise Temporal de Vendas

Página dedicada à análise temporal do desempenho comercial, com:

- Indicadores gerenciais.
- Visualização da evolução mensal do lucro.
- Gráficos complementares de vendas por segmento e produto.
- Navegação para as demais páginas do relatório.

### 3. Análise de Produtos e Segmentos

Página voltada à exploração dos resultados comerciais, contendo:

- Indicadores de vendas, lucro e unidades vendidas.
- Gráficos comparativos por segmento e produto.
- Filtro interativo por país (Country).
- Filtro interativo por produto (Product).
- Atualização dinâmica dos indicadores e gráficos conforme as seleções.

## Indicadores Gerais

| Indicador | Resultado |
|---|---:|
| Vendas Totais | 118,73 milhões |
| Lucro Total | 16,89 milhões |
| Unidades Vendidas | 1,13 milhão |

## Validação da Interatividade

Foram realizados testes combinando os filtros **France** e **Paseo**.

| Indicador | Resultado filtrado |
|---|---:|
| Vendas Totais | 5,60 milhões |
| Lucro Total | 838,75 mil |
| Unidades Vendidas | 71,61 mil |

Os testes confirmaram a atualização simultânea dos indicadores e dos gráficos, além do retorno aos resultados gerais após a limpeza dos filtros.

## Recursos Utilizados

- Microsoft Power BI Desktop
- Power Query e base Financial Sample
- Indicadores (KPIs)
- Gráficos de barras, colunas, linhas e cascata
- Árvore de decomposição
- Segmentações de dados (Slicers)
- Navegador de páginas
- Indicadores (Bookmarks) para alternância de visuais
- Formatação e organização da interface

## Arquivo do Projeto

O arquivo principal do projeto é:

`desafio-power-bi-experiencia-usuario.pbix`

## Aprendizados

O desenvolvimento permitiu aprofundar conhecimentos sobre experiência do usuário aplicada ao Business Intelligence, organização visual de dashboards, navegação entre páginas e utilização de filtros para análises gerenciais.

Além da construção dos gráficos, o projeto reforçou a importância da usabilidade, da clareza das informações e da validação funcional dos elementos interativos.

## Autor

**Marcos-dot-hue**

Projeto desenvolvido para fins educacionais e de portfólio profissional, como parte dos desafios práticos da DIO.
