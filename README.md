# Projeto de Análise Descritiva de um Conjunto de Dados

Esse projeto tem como finalidade utilizar os conhecimentos adquiridos no curso de estatística, realizados na plataforma Alura, para desenvolver uma análise descritiva básica de um conjunto de dados retirados da Pesquisa Nacional por Amostra de Domicílios - 2015 do IBGE.

O projeto realiza a construção de histogramas, calcular e avaliar medidas de tendência central, medidas separatrizes e de dispersão dos dados.

## Pesquisa Nacional por Amostra de Domicílios - 2015

A Pesquisa Nacional por Amostra de Domicílios - PNAD investiga anualmente, de forma permanente, características gerais da população, de educação, trabalho, rendimento e habitação e outras, com periodicidade variável, de acordo com as necessidades de informação para o país, como as características sobre migração, fecundidade, nupcialidade, saúde, segurança alimentar, entre outros temas. O levantamento dessas estatísticas constitui, ao longo dos 49 anos de realização da pesquisa, um importante instrumento para formulação, validação e avaliação de políticas orientadas para o desenvolvimento socioeconômico e a melhoria das condições de vida no Brasil.

O arquivo do dataset utilizado encontra-se no repositório como - 'dados.csv'

## Os seguintes tratamentos foram realizados nos dados originais:

Foram eliminados os registros onde a Renda era inválida (999 999 999 999);
Foram eliminados os registros onde a Renda era missing;
Foram considerados somente os registros das Pessoas de Referência de cada domicílio (responsável pelo domicílio).

Fonte dos Dados: https://www.ibge.gov.br/estatisticas/multidominio/ciencia-tecnologia-e-inovacao/9127-pesquisa-nacional-por-amostra-de-domicilios.html?=&t=microdados

## Bibliotecas utilizadas e ferramentas

(pandas, numpy, seaborn, matplotlib.pyplot)
