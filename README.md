###Projeto - Sistema de vendas - Livraria
Projeto proposto na disciplina de Projeto Integrador - Desenvolvimento Estruturado de Sistemas, durante o 2° semestre da faculdade de Análise e Desenvolvimento de Sistemas.


###Objetivo do projeto
Desenvolver um sistema de vendas para um comércio de escolha do grupo (foi escolhido uma livraria).
O sistema deve ser composto por dois cadastros principais (cliente e produto), uma tela de venda de produtos e uma tela de “relatório”, que exibirá os resultados da venda dos produtos na própria interface. Os dois cadastros propostos são pré-requisitos para composição da funcionalidade de venda de produto, elemento central do sistema. 

##Descrição do sistema
	O primeiro cadastro será composto, basicamente, pelas funcionalidades de manutenção de clientes (CRUD). Deverá ser possível inserir, excluir, alterar e consultar clientes meio de uma pesquisa simples buscando pelo nome ou CPF.
	Todos os dados principais que normalmente compõem um cadastro de clientes, como nome, cpf, endereço, telefone, e-mail, sexo, estado civil e data de nascimento deverão estar disponíveis na aplicação. Os campos deverão ter validação de tipo, tamanho e obrigatoriedade (pelo menos nome, sexo, CPF, e-mail e endereço devem ser inseridos) antes da inserção ou manipulação no banco de dados. Não deverá ser permitido cadastrar dois clientes com o mesmo CPF.
	O segundo cadastro será a manutenção do produto (CRUD) a ser vendido. Deverá ser possível inserir, excluir, alterar e consultar produtos por meio de uma pesquisa simples. Assim como o cliente, o produto também será utilizado para compor a venda. No entanto, terá uma funcionalidade mais complexa em relação ao cadastro de clientes, pois deverá possuir um controle de estoque simples. Ou seja, deverá ser possível atualizar o produto com indicadores de estoque, onde vendas decrementarão este estoque e, da mesma forma, não será possível realizar novas vendas para produtos sem estoque. Os campos necessários para composição da aplicação dependerão do tema escolhido, mas também deverão ter validação de tipo, tamanho e obrigatoriedade antes da inserção ou manipulação no banco de dados.
	Como atividade principal do sistema, está localizado o processo de venda. Uma venda será o registro de saída de estoque de determinados produtos, com quantidades especificadas, para determinado cliente num determinado momento no tempo. Durante o processo de venda, o usuário deverá ser capaz de escolher um ou mais produtos a serem vendidos, as quantidades dos produtos e qual cliente irá comprá-los e o sistema mostrará o valor final da venda e permitirá concretizá-la. Validações de obrigatoriedade (seleção de cliente, produtos e quantidade), tipo, validade e tamanho também deverão ser efetuadas.
	Por fim, o relatório de vendas permitirá que o usuário visualize na própria interface do sistema, o resumo das vendas (relatório sintético) em um determinado período de tempo (máximo mensal), indicando o valor total das vendas, a data de compra e o cliente. Também deverá ser exibido o valor total das vendas do período selecionado no relatório sintético. Além disso, deverá ser possível visualizar os detalhes da venda (relatório analítico), com os produtos vendidos em cada venda, bem como suas respectivas quantidades.

##Imagens
Cadastro e consulta de clientes:
![cadastro clientes](https://i.imgur.com/xxN7epe.jpeg "cadastro clientes")
![consulta de clientes](https://i.imgur.com/vRFEG7x.jpg "consulta de clientes")

Cadastro e consulta de produtos:
![produtos](https://i.imgur.com/8CMvCvr.jpeg "produtos")

Tela de vendas:
![vendas](https://i.imgur.com/DVZeFTV.jpg "vendas")

Tela de relatórios:
![relatorios](https://i.imgur.com/vLkAjlz.jpg "relatorios")

# Observações importantes
	TELA DE CONSULTA DE CLIENTES E PRODUTOS: para atualizar os dados cadastrados bastas alterar diretamente na tabela de consulta e depois clicar no botão atualizar;
	TELA DE VENDAS: para adicionar quantidade de um mesmo produto no carrinho de compras, basta clicar sobre o mesmo na tabela de produtos a quantidade desejada; Para remover algum item do carrinho, basta clicar sobre o mesmo também.

###Bibliotecas e tecnologias utilizadas:
- Java
- MySQL
- JDBC

###Participantes / colaboradores:
 - Danilo da Silva Ranéa
 - João Vitor Maldonado Roschel
 - Paulo H. Honorato de Souza
 - Sillas Cavalcante
 
###Orientador:
 - Prof° Fernando Timoteo Fernandes
