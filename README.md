# Segmentação de Clientes e Análise de Campanhas de Marketing
Projeto de Data Science aplicado a negócios, com foco em segmentação de clientes, análise comportamental e tomada de decisão de marketing, utilizando dados simulados de um e-commerce.

Este projeto foi desenvolvido com o objetivo de demonstrar habilidades em Python, NumPy, análise estatística e raciocínio de negócio, indo além de simples métricas descritivas.

-------------
## Objetivo do Projeto
Identificar qual segmento de clientes é mais vantajoso para campanhas de marketing, considerando:

-Gasto mensal

-Frequência de compras

-Tempo de permanência no site

-Perfil demográfico (idade e renda)

Ao final, o projeto responde:

"Para qual público uma campanha de marketing deve ser direcionada para maximizar retorno financeiro?"

-------------
## Contexto de Negócio
Empresas de e-commerce precisam decidir onde investir seu orçamento de marketing. Campanhas mal direcionadas aumentam custos e reduzem o ROI.

-Neste cenário, utilizamos dados simulados de clientes para:

-Segmentar consumidores

-Avaliar comportamento de compra

-Simular decisões estratégicas

---------------
## Tecnologias Utilizadas
-Python 3

-NumPy

-Pandas

-Matplotlib

-Jupyter Notebook

--------------
# Etapas do Projeto
## Geração dos Dados

Foram simuladas variáveis realistas de clientes:

Idade

Renda mensal

Quantidade de compras

Valor médio por compra

Tempo de navegação no site

Isso permite testar análises sem depender de dados sensíveis reais.

## Limpeza e Preparação

Remoção de valores negativos de renda

Criação da variável gasto mensal

Padronização dos dados para análise

## Análise Exploratória

Foram calculadas métricas como:

Média, mediana e desvio padrão da renda

Gasto médio mensal

Distribuição de gastos

Essas métricas ajudam a entender o comportamento geral dos clientes.

## Segmentação de Clientes

Os clientes foram segmentados em três grupos com base no gasto mensal:

Segmento Baixo → até o 33º percentil

Segmento Médio → entre 33º e 66º percentil

Segmento Alto → acima do 66º percentil

Cada segmento foi analisado individualmente.

## Análise Comparativa entre Segmentos

Foram comparadas métricas como:

Idade média

Tempo médio no site

Volume de clientes

Resultado importante:

Apesar de perfis demográficos semelhantes, o segmento alto concentra maior potencial de retorno financeiro.

----------------
## Insight de Negócio

Decisão Estratégica:

Campanhas de marketing premium devem ser direcionadas prioritariamente ao segmento alto, pois:

Representa a maior fatia de receita

Possui comportamento de compra consistente

Apresenta maior potencial de ROI

Segmento médio pode ser utilizado para testes A/B ou campanhas de conversão gradual.

-------------------
## Possíveis Extensões Futuras

Implementação de modelo RFM

Simulação de A/B Test

Cálculo de ROI por segmento

Clusterização com K-Means

Transformação do projeto em pipeline modular

----------
# Autor

João Pedro Borba Calil
Estudante de Ciência de Dados / Machine Learning
Interessado em análise de dados aplicada a negócios, tecnologia e estratégia.

-----------
# Observação Final

Este projeto tem fins educacionais e demonstrativos, focando em boas práticas de análise e comunicação de resultados.

Se este repositório foi útil, sinta-se à vontade para ⭐ o projeto.
