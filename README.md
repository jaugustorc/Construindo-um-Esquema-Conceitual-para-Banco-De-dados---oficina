# Construindo-um-Esquema-Conceitual-para-Banco-De-dados---oficina
Construindo um Esquema Conceitual para Banco De dados

## Descrição do Desafio
Agora você irá criar um esquema conceitual do zero. A partir da narrativa fornecida você será capaz de criar todas as entidades, relacionamentos e atributos. Caso encontre algo que não foi definido na narrativa, utilize a sua compreensão do contexto e deixe uma descrição no README do seu github. para verificação.

O esquema deverá ser adicionado a um repositório do Github para futura avaliação do desafio de projeto. Adicione ao Readme a descrição do projeto conceitual para fornecer o contexto sobre seu esquema.

### Objetivo:
Cria o esquema conceitual para o contexto de oficina com base na narrativa fornecida

### Narrativa:
	- Sistema de controle e gerenciamento de execução de ordens de serviço em uma oficina mecânica
	- Clientes levam veículos à oficina mecânica para serem consertados ou para passarem por revisões  periódicas
	- Cada veículo é designado a uma equipe de mecânicos que identifica os serviços a serem executados e preenche uma OS com data de entrega.
	- A partir da OS, calcula-se o valor de cada serviço, consultando-se uma tabela de referência de mão-de-obra
	- O valor de cada peça também irá compor a OSO cliente autoriza a execução dos serviços
	- A mesma equipe avalia e executa os serviços
	- Os mecânicos possuem código, nome, endereço e especialidade
	- Cada OS possui: n°, data de emissão, um valor, status e uma data para conclusão dos trabalhos.

# Modelando Oficina:
## Entidades: 
	- Ordem de Serviço;
	- Cliente;
	- Veiculos; 
	- Equipes;
	- Funcionarios;
	- Tabela de Serviços;
	- Serviços, e
	- Estoque de Peças
## Ordem de serviço:
	- Deve ser vinculada a um tipo de trabalho a ser executado (conserto ou revisão).
	- Valor do serviço.
	- Cada peça tambem irá compor a OS
	- Numero, data de emissão, valor, status e data para conclusão dos trabalhos.
	- Pode ser composta por vários serviços e um mesmo serviço pode estar contido em mais de uma OS.
	- Uma OS pode ter vários tipos de peças e uma peça pode estar presente em mais de uma OS.

## Cliente:
	- O cliente pode ter mais de um veiculo 
	- Autoriza a execução dos serviços

## Veiculo:
	- O veiculo pode ser consertado ou ter revisão periodica
	
## Equipe:
	- Possui um numero de funcionarios
	- Cada um executa uma tarefa
	- Preencher OS com data de entrega
	- Avalia e Executa

## Mecânicos:
	- Código, nome, endereço e especialidade
	
## Tabela de Serviços
	- Tipo de serviço a ser executado, valor do serviço, peças utilizadas, tempo de entrega do serviço, 


