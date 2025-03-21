# ATVDS01
Atividade Java
O código implementa um sistema de gerenciamento de produtos utilizando Java. Ele possui duas classes principais: Produto, que define os objetos que representam produtos, e Main, que contém a lógica do programa e permite ao usuário criar, alterar, excluir e listar produtos.

A classe Produto define os atributos essenciais de um produto, como nome, descrição, categoria, quantidade e preço. Para facilitar a criação de objetos, ela oferece três construtores: um que recebe todos os atributos, outro que assume uma descrição padrão quando não informada e um terceiro que apenas exige nome e preço. Além disso, essa classe possui métodos getters e setters que permitem acessar e modificar os valores dos atributos.

A classe Main é responsável por executar o programa e interagir com o usuário. Ela utiliza uma lista para armazenar os produtos cadastrados e um Scanner para capturar as entradas do usuário. O programa exibe um menu com opções numeradas, permitindo criar novos produtos, editar um produto já cadastrado, remover um produto da lista e listar todos os produtos disponíveis.

Quando o usuário escolhe criar um produto, ele insere nome, preço, quantidade, categoria e descrição, e um novo objeto Produto é adicionado à lista. Na opção de alteração, o programa exibe todos os produtos disponíveis, permitindo que o usuário selecione um item para modificar seus atributos. Para excluir um produto, a lista de produtos é apresentada e o usuário escolhe qual deseja remover. Caso opte por listar os produtos, o programa exibe todos os itens cadastrados com suas respectivas informações.

O programa funciona dentro de um loop que se repete até que o usuário escolha a opção de sair. Ele também verifica se a lista de produtos está vazia antes de permitir ações como alteração ou exclusão. A implementação poderia ser aprimorada com validações mais robustas, formatação melhorada na exibição dos produtos e a possibilidade de persistência dos dados, armazenando os produtos em um arquivo para que não sejam perdidos ao encerrar o programa.

Fiquei com um pouco de dificuldade enquato fazia a funcionalidade de alterar um produto, mas pedi ajuda para o pessoal da sala e consegui resolver :)
