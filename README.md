# Desafio Análise de dados com Python e Pandas

Resolução do desafio para o Bootcamp de Data Engineering.

Durante o desafio foi realizada a extração da base de dados fornecida (Adventure Works), verificando a existência de valores nulos, os tipos de dados encontrados em cada coluna e também foi realizada uma validação dos dados através da biblioteca pandera.

A validação garante que todos os dados presentes na tabela estão formatados de acordo com o esperado. Coluna de Datas recebendo valores do tipo DateTime, Colunas de custo e preços com valores do tipo float e etc.

Foram adicionadas novas colunas para a geração de novas informações como: 
    - Custo por venda;
    - Faturamento por venda;
    - Diferença de dias entre a venda e o envio do produto;
    - Qual o trimestre do ano a venda foi realizada;

De posse das novas colunas, as lojas foram analisadas podendo gerar informações como:
    - Qual o custo por venda?
    - Qual o custo por venda?
    - Quantas lojas estão presentes no dataset?
    - Quais produtos estão presentes no dataset?
    - Qual das lojas tem a maior média entre a data da venda e data de envio?
    - Qual o trimestre em que cada venda foi realizada?

Alguns gráficos também foram criados, mostrando:
    - Média de dias entre a venda e o envio por loja;
    - Total de faturamento de todas as lojas por Trimestre;
    - Evolução do número de clientes atendidos por loja a cada trimestre;


