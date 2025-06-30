# CaseEudesMalheiros

Olá, Seguem as intruções para que os notebooks executem sem erros
Criei as análises e notebooks no Databricks Free, então vou listar o passo a passo utilizando o databricks como referência

1 - Criar um schema chamado Ifood 
2 - Dentro do Schema criar um volume chamado base_case_ifood
3 - Baixar os bases do case (restaurant.csv, consumers.csv e colocar dentro do volume criado no passo anterior
4 - dar um wget na base order.json  e após baixar o arquivo colocá-lo no volume citado no item 2
5 - o arquivo ab_test_ref estava no formato .tar, extrair o arquivo utilizando ferramentas como winrar, .zip e após isso subir o arquivo csv no volume
6 - Feito os passos anteriores, os notebooks estão preparados para rodar normalmente.

Abraços! 
