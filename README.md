# Algoritmo Genético para Formação de Carteira de Ações

Este projeto utiliza um **algoritmo genético** e o **método de Markowitz** para otimizar a formação de um portfólio de ações, maximizando o retorno e minimizando o risco, com base em dados históricos da Bolsa de Valores.

## Descrição do Projeto

O objetivo deste projeto é implementar e comparar dois métodos de otimização de portfólio:

- **Algoritmo Genético**: Um método evolutivo inspirado na seleção natural, onde uma população de portfólios é gerada e evolui ao longo de várias gerações. O objetivo é maximizar o **Sharpe Ratio**, uma métrica que ajusta o retorno pelo risco.
  
- **Método de Markowitz**: Um método tradicional de otimização de portfólio, também conhecido como **teoria da carteira moderna**, que encontra a melhor combinação de ativos que equilibra retorno e risco.

Ambos os métodos utilizam a **restrição de 20%** como alocação máxima permitida para qualquer ativo no portfólio.

## Estrutura do Projeto

O código principal do projeto está no Jupyter Notebook: [Algoritmo Genético em Formação de Carteira de Ações](https://github.com/patrickdevv/FIAP_Fase02_Desafio/blob/main/Algoritimo_Gene%CC%81tico_em_formac%CC%A7a%CC%83o_de_carteira_de_ac%CC%A7o%CC%83es.ipynb).

### Principais componentes do notebook:

- **Carregamento de dados**: Importação de dados históricos de preços de ações.
- **Funções do Algoritmo Genético**:
  - Inicialização da população.
  - Avaliação de aptidão com o Sharpe Ratio.
  - Crossover e mutação de indivíduos (portfólios).
  - Ajuste de pesos para respeitar as restrições.
- **Método de Markowitz**:
  - Otimização quadrática para maximização do Sharpe Ratio.
- **Comparação de resultados**: Comparação entre o portfólio gerado pelo algoritmo genético e o método de Markowitz.

## Como Executar

1. Clone o repositório para a sua máquina:

git clone https://github.com/patrickdevv/FIAP_Fase02_Desafio.git

2. Navegue até o diretório do projeto:
cd FIAP_Fase02_Desafio

3. Abra o notebook Algoritimo_Genético_em_formação_de_carteira_de_ações.ipynb em um ambiente Jupyter, como o Jupyter Notebook ou Jupyter Lab.

4. Execute todas as células do notebook para rodar o algoritmo genético e o método de Markowitz.

### Licença
Este projeto está licenciado sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.

## Autores: 
Eduardo José Marcelino Vicente dos Santos
Patrick Iarrocheski
