Fazer um programa para ler um número inteiro N e depois os 
dados (id, nome e salario) de N funcionários. Não deve haver 
repetição de id. 
 
Em seguida, efetuar o aumento de X por cento no salário de 
um determinado funcionário. Para isso, o programa deve ler 
um id e o valor X. Se o id informado não existir, mostrar 
uma mensagem e abortar a operação. Ao final, mostrar a 
listagem atualizada dos funcionários, conforme exemplos.
 
Lembre-se de aplicar a técnica de encapsulamento para não 
permitir que o salário possa ser mudado livremente. Um 
salário só pode ser aumentado com base em uma operação 
de aumento por porcentagem dada.

Exemplo 1: caminho feliz

Quantos funcionários você quer registrar? 1

Funcionário *1*
Id: 123
Nome: rayane
Salário: 1500

Insira o id do funcionário que irá ter um aumento salarial : 123
Insira a porcentagem que deseja incrementar: 15

Lista de funcionários:
123, rayane, 3225.00

Exemplo 2: ID existente 

Quantos funcionários você quer registrar? 2

Funcionário *1*
Id: 123
Nome: ray
Salário: 1500

Funcionário *2*
Id: 123
Esse ID já existe! Tente novamente com outro Id! 

Exemplo 3: ID não existente

Quantos funcionários você quer registrar? 1

Funcionário *1*
Id: 123
Nome: ray
Salário: 1500

Insira o id do funcionário que irá ter um aumento salarial : 456

Esse id não existe!

Lista de funcionários:
123, ray, 1500.00
