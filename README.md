# Verificação de Idade para entrada no cassino Boa Sorte

## 📋 Descrição do Projeto
Gerente de segurança do cassino Boa Sorte, implementou um rigoroso sistema de verificação de idade para impedir a entrada de menores. O sistema utiliza inteligência artificial para analisar documentos e características físicas dos visitantes, garantindo que apenas maiores de 18 anos possam acessar as áreas de jogos. Os funcionários do estabelecimento foram treinados para seguir protocolos rígidos de identificação e verificando a idade dos clientes automaticamente.

## Objetivo
Desenvolver um modelo de machine learning capaz de estimar a idade de uma pessoa a partir de uma foto, auxiliando no processo de acesso ao estabelecimento.

## 🛠️ Ferramentas e Bibliotecas Utilizadas
- Python
- Pandas
- TensorFlow
- Keras
- sklearn
- ResNet-50
- Plotly

## 🔍 Metodologia
- Análise exploratória de dados
- Treinamento de modelo de aprendizado profundo
- Avaliação de desempenho usando Mean Absolute Error (MAE)

## Resultados
- Modelo: ResNet-50
- MAE de Teste: 7,9925
- Status: Aprovado (MAE abaixo de 8)

## Conclusão
  EAM (Mean Absolute Error): O EAM, ou Erro Médio Absoluto, é uma métrica que mede a diferença média absoluta entre as previsões do modelo e os valores reais. Um EAM de 7.9925 indica que, em média, as previsões do modelo apresentam um erro 
  absoluto de aproximadamente 7,99 unidades em relação aos valores observados. O objetivo é minimizar essa métrica o máximo possível, garantindo previsões mais precisas.

  Test EAM: O valor de 7.9925 foi calculado no conjunto de teste, indicando a capacidade do modelo de generalizar para dados que não foram utilizados durante o treinamento. Isso significa que, em média, o modelo erra por cerca de 7,99 
  unidades ao prever os valores no conjunto de teste.
  Progresso do Modelo: O modelo ResNet-50 está mostrando progresso durante o treinamento, com uma redução consistente na perda ao longo das épocas. Isso sugere que ele está aprendendo de forma eficaz a capturar os padrões presentes nos 
  dados.


## Próximos Passos
- Refinamento do modelo
- Redução do erro de predição
- Integração com sistemas de checkout

## Requisitos
- Plataforma GPU para treinamento
- Conjunto de dados de imagens com idades

## 🚀 Como Usar

1. Clone o repositório
```bash
 https://github.com/paulo-santos-ds/analise_de_sentimentos_em_criticas_de_filmes
```

2. Extrair o arquivo (imdb_reviews.zip)

3. Instale as dependências
```bash
pip install -r requirements.txt
```

4. Execute o notebook principal
```bash
analise_de_sentimentos_em_criticas_de_filmes.ipynb
```

