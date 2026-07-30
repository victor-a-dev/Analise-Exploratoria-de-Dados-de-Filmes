# Análise Exploratória de Dados de Filmes

Este projeto consiste em uma análise exploratória de dados sobre filmes, utilizando dois conjuntos de dados: avaliações de usuários (MovieLens) e informações detalhadas de filmes (TMDB). O objetivo é extrair insights sobre padrões de notas, distribuição de receitas, orçamentos, idiomas originais e comparar a performance de diferentes filmes.

## 📊 Conjuntos de Dados Utilizados

- **MovieLens (ratings.csv)**: Contém avaliações de usuários para filmes, incluindo nota (0.5 a 5.0), ID do usuário, ID do filme e timestamp.
- **TMDB (tmdb_5000_movies.csv)**: Contém informações como orçamento, receita, idioma original, popularidade, gêneros, data de lançamento, entre outros.

## 🔍 Análises Realizadas

### 1. Análise das Notas (MovieLens)
- Distribuição das notas – histograma e boxplot.
- Cálculo de média, mediana e outras estatísticas descritivas.
- Comparação entre as notas de filmes específicos (ex: Toy Story vs. Jumanji).
- Exploração da quantidade de avaliações por filme.

### 2. Análise dos Filmes (TMDB)
- Distribuição de receitas e orçamentos.
- Distribuição de idiomas originais – identificação da predominância do inglês.
- Visualização da proporção de filmes em inglês versus outros idiomas.
- Gráficos de barras e pizza para idiomas.

### 3. Comparações e Visualizações
- Boxplots para comparar distribuições de notas entre filmes.
- Histogramas e gráficos de densidade para médias por filme.
- Uso de paletas de cores para melhor visualização (ex: `mako`).

### 4. Tratamento de Dados
- Renomeação de colunas para português.
- Filtragem de dados (ex: filmes com receita > 0, filmes em outros idiomas).
- Normalização de contagens para exibir percentuais.

## 🛠️ Bibliotecas Utilizadas

- **pandas** – manipulação e análise de dados.
- **matplotlib** – criação de gráficos estáticos.
- **seaborn** – visualizações estatísticas avançadas.
- **numpy** – operações matemáticas e estatísticas.
