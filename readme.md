 
cota-real

Programa em javascript que faz acesso á cotação de moedas através da API API http://fixer.io/ 

* Feito e testado no Linux mint 17.3 kernel linux e navegador Mozilla Firefox 50.1.0

* Utiliza jquery 3.1.1

O programa obtem cotações da moeda Real entre os períodos de 7 de Agosto de 2009 a 17 de Novembro de 2011, tendo como base o dólar, do Fixer.io, trazendo os seguintes dados:

1. O dia que foi observado o menor valor.	1.5347 na data: 26/07/2011

2. O dia que foi observado a maior valor.	1.9111 na data: 23/09/2011
	
3. A média da cotação para esse período, excetuando os dias de início e fim. 	media: 1.7228095180722909


Pelo programa ser em Javascript, não é necessário um servidor local para rodar o código, basta abrir o arquivo cota-real.html com um navegador para executá-lo.

Para rodar o código do programa, ao abrir o arquivo, clique no botão "calcular" para dar início ao algoritmo. As requisições em tempo real em javascript pode levar um pouco de tempo para calcular o resultado.


Autor Marcelo