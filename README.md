# Sport Recife na Série B — Análise por Contexto de Jogo (2019–2024)

Este projeto analisa o desempenho do **Sport Club do Recife** na **Série B do Campeonato Brasileiro**
nas temporadas **2019, 2022, 2023 e 2024**, considerando diferentes contextos de jogo.

## 🎯 Objetivo
Comparar o desempenho do Sport de acordo com o contexto da partida:
- Mandante na **Ilha do Retiro**
- Mandante na **Arena de Pernambuco**
- Visitante contra equipes do **Nordeste**
- Visitante contra equipes **fora do Nordeste**

## 📊 Dados utilizados
- Base histórica de partidas do futebol brasileiro (Séries A e B)
- Dados manuais dos jogos do Sport na Série B 2024
- Classificação manual de mandantes por região (Nordeste / Fora do Nordeste)
- Identificação dos jogos disputados na Arena de Pernambuco

Todos os dados foram tratados e integrados em um único dataset final.

## 🧠 Metodologia
1. Filtragem das partidas da Série B
2. Seleção apenas dos jogos do Sport Recife
3. Criação das variáveis:
   - Mandante / Visitante
   - Resultado (Vitória, Empate, Derrota)
   - Pontos por jogo
   - Contexto final da partida
4. Geração de tabelas de desempenho e comparações por contexto

## 📈 Principais Resultados
Os resultados consolidados estão disponíveis em formato CSV na pasta `data/`, incluindo:
- Aproveitamento por contexto de jogo
- Comparação Ilha do Retiro vs Arena de Pernambuco
- Comparação Visitante no Nordeste vs Fora do Nordeste

## ▶️ Como executar o projeto
1. Clone este repositório
2. Instale as dependências: pip install -r requirements.txt
3. Abra o notebook: notebooks/02_analise_sport_final.ipynb

## 🧩 Interpretação dos Resultados

A análise evidencia diferenças claras de desempenho do Sport Recife de acordo com o contexto da partida.

- **Mandante na Ilha do Retiro:**  
  O Sport apresenta um aproveitamento extremamente elevado, indicando um forte efeito de mando de campo. Os números sugerem que a Ilha do Retiro exerce um impacto significativo no desempenho da equipe, tornando o Sport praticamente imbatível neste contexto ao longo do período analisado.

- **Mandante na Arena de Pernambuco:**  
  Apesar de ainda apresentar vantagem competitiva em relação aos adversários, o desempenho na Arena de Pernambuco é inferior ao observado na Ilha do Retiro. Os dados indicam que o efeito do mando de campo existe, e é forte, porém em menor intensidade que na Ilha do Retiro.

- **Visitante contra equipes do Nordeste:**  
  O retrospecto do Sport fora de casa contra equipes do Nordeste é particularmente muito negativo, com baixo aproveitamento. Esse cenário contrasta com a expectativa de equilíbrio regional e sugere dificuldades específicas nesse contexto competitivo.

- **Visitante fora do Nordeste:**  
  Fora de casa, contra equipes de outras regiões, o Sport apresenta um desempenho mais próximo da média geral, sem grandes extremos positivos ou negativos, indicando um comportamento competitivo mais estável.

Esses resultados reforçam a importância do contexto da partida na performance da equipe e oferecem subsídios objetivos para análises técnicas, estratégicas e históricas.

## 🔜 Próximos passos
- Visualizações gráficas do desempenho por contexto
- Expansão do estudo para outras equipes

---
Projeto desenvolvido para fins de estudo em **Ciência de Dados aplicada ao esporte**.