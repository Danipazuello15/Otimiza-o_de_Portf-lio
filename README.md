# Otimização de Portfólio com Simulação de Monte Carlo

Este projeto explora a otimização de portfólio utilizando a técnica de Simulação de Monte Carlo. Aplicando métodos quantitativos, ele identifica a alocação de ativos ideal para maximizar o Sharpe Ratio, que mede o retorno ajustado ao risco. Este modelo é especialmente útil para investidores que buscam maximizar o retorno de seus investimentos com um nível controlado de risco.

## Descrição do Projeto

A otimização de portfólios é uma das estratégias mais importantes no campo de finanças e investimentos. Este projeto foi desenvolvido para simular e identificar uma combinação ótima de ativos em um portfólio de ações, utilizando dados históricos para calcular retornos esperados, riscos (volatilidade) e o Sharpe Ratio para diferentes combinações de pesos. 

O objetivo principal é **maximizar o retorno por unidade de risco**, criando um portfólio que oferece o maior Sharpe Ratio possível, e, assim, apoiando decisões de investimento mais informadas e eficientes.

## Objetivos

1. **Calcular Retornos e Riscos**: Utilizando dados históricos para calcular os retornos esperados e a volatilidade de cada ativo no portfólio.
2. **Simular Portfólios**: Aplicar a Simulação de Monte Carlo para gerar diversas combinações de alocação de ativos e calcular o Sharpe Ratio de cada combinação.
3. **Identificar o Portfólio Ótimo**: Encontrar a combinação de pesos que maximiza o Sharpe Ratio, criando o portfólio com a melhor relação entre risco e retorno.
4. **Visualizar a Fronteira Eficiente**: Gerar um gráfico que ilustra a relação entre risco e retorno dos portfólios simulados, destacando o portfólio ótimo.

## Justificativa e Aplicabilidade

Este projeto foi bem-sucedido em:
- **Identificar o Portfólio com Melhor Retorno Ajustado ao Risco**: Através da análise de Monte Carlo, foi possível encontrar uma alocação de ativos que oferece o maior Sharpe Ratio. Esse portfólio representa a melhor escolha para investidores que desejam maximizar seus retornos sem assumir riscos excessivos.
- **Auxiliar na Tomada de Decisões de Investimento**: O projeto fornece uma base quantitativa para a tomada de decisões, ajudando investidores a alocar recursos de maneira mais eficiente. O Sharpe Ratio, como métrica de risco-retorno, é amplamente reconhecido em finanças para avaliar a qualidade de um portfólio.
- **Visualizar Riscos e Retornos**: A visualização da fronteira eficiente permite que os investidores compreendam a relação entre risco e retorno e escolham portfólios alinhados com sua tolerância ao risco.

## Metodologia

1. **Coleta de Dados**: Utilizamos dados históricos das ações de várias empresas para calcular os retornos diários e a volatilidade de cada ativo.
2. **Simulação de Monte Carlo**:
   - Geramos 10.000 portfólios simulados com alocações de ativos aleatórias.
   - Calculamos o retorno esperado, o risco (volatilidade) e o Sharpe Ratio de cada portfólio.
3. **Identificação do Portfólio Ótimo**:
   - Selecionamos o portfólio com o maior Sharpe Ratio entre os simulados, maximizando o retorno ajustado ao risco.
4. **Visualização da Fronteira Eficiente**:
   - Plotamos a relação entre risco e retorno para todos os portfólios simulados e destacamos o portfólio ótimo, permitindo uma análise visual da fronteira eficiente.

## Resultados

- **Portfólio Ótimo**: O portfólio que maximiza o Sharpe Ratio foi encontrado e consiste em uma combinação específica de ações, com pesos otimizados para maximizar o retorno ajustado ao risco.
- **Visualização**: O gráfico da fronteira eficiente mostra a distribuição dos portfólios em um gráfico de risco-retorno, com o portfólio de maior Sharpe Ratio destacado. Essa visualização oferece uma compreensão clara das escolhas de alocação de ativos e seus impactos no risco e retorno esperados.

## Tecnologias e Ferramentas Utilizadas

- **Python**: Linguagem de programação principal para cálculos, simulações e visualizações.
- **Pandas e NumPy**: Utilizadas para manipulação de dados e cálculos de estatísticas.
- **Matplotlib**: Para visualização gráfica da fronteira eficiente e do portfólio ótimo.

## Como Executar o Projeto

1. Clone este repositório para o seu ambiente local.
2. Certifique-se de ter as bibliotecas necessárias instaladas:
   ```bash
   pip install pandas numpy matplotlib

