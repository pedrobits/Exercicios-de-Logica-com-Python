QUESTÃO 4 de 4 - Conteúdo até aula 06

Enunciado: Você e sua equipe de programadores foram
contratados por pequena empresa para desenvolver o software de gerenciamento de
pessoas. Este software deve ter o seguinte menu e opções:

Cadastrar Livro

Consultar Livro

Consultar Todos

Consultar por Id

Consultar por Autor

Retornar ao menu

Remover Livro

Encerrar Programa

Elabore um programa em Python que:

A.
Deve-se implementar o print com uma mensagem de
boas-vindas que apareça o seu nome [EXIGÊNCIA DE CÓDIGO 1 de 8];

B.
Deve-se implementar uma lista vazia com o nome de **lista_livro
**e a variável **id_global** com valor inicial igual a 0 [EXIGÊNCIA DE CÓDIGO 1 de 7];

C.
Deve-se implementar uma função chamada **cadastrar_livro(id)
**em que **: ** [EXIGÊNCIA
DE CÓDIGO 2 de 7];

a.Pergunta
 **nome** ,  **autor** , **editora **do livro;

b.Armazena
o **id** (este é fornecido via parâmetro da função),  **nome** ,  **autor** ,
**editora **dentro de um dicionário;

c.  Copiar
o dicionário para dentro da  **lista_livro** ;

D.  Deve-se
implementar uma função chamada **consultar_livro() **em que **: ** [EXIGÊNCIA DE CÓDIGO 3 de 7];

a.Deve-se
pergunta qual opção deseja (1. Consultar Todos / 2. Consultar por Id / 3.
Consultar por Autor / 4. Retornar ao menu) e
printar a “Opção inválida" se entrar com valor diferente de 1, 2, 3
ou 4 :

i.    Se
Consultar Todos, apresentar todos os livros com todos os seus dados cadastrados;

ii.    Se
Consultar por Id, apresentar o livro específico com todos os seus dados
cadastrados;

iii.    Se
Consultar por Autor, apresentar o(s) livro(s) do autor com todos os seus dados
cadastrados;

iv.    Se
Retornar ao menu, deve-se retornar ao menu principal;

E.
Deve-se implementar uma função chamada **remover_livro()
**em que **: ** [EXIGÊNCIA
DE CÓDIGO 4 de 7];

a.Deve-se
pergunta pelo **id **do colaborador a ser removido;

b.Remover
o livro da  **lista_livro** ;

F.
Deve-se implementar uma estrutura de menu no main em
que: [EXIGÊNCIA DE CÓDIGO 5 de
7];

a.Deve-se
pergunta qual opção deseja (1. Cadastrar Livro / 2. Consultar Livro / 3.
Remover Livro / 4. Encerrar Programa)e executar o printar de “Opção inválida"
se entrar com valor diferente de 1, 2, 3 ou 4 :

i.    Se
Cadastrar Livro, acrescentar em um **id_ global** e chamar a função  **cadastrar_livro(id_
global)** ;

ii.    Se
Consultar Livro, chamar função  **consultar_livro()** ;

iii.    Se
Remover Livro, chamar função  **remover_livro()** ;

iv.    Se
Encerrar Programa, sair do menu (e com isso acabar a execução do código);

 G.
Deve-se implementar uma  **lista de dicionários ** (uma
lista contento dicionários dentro)  [EXIGÊNCIA DE CÓDIGO 6 de 7];

H.
Deve-se inserir comentários **relevantes** no
código [EXIGÊNCIA DE CÓDIGO 7
de 7];

I.
Deve-se apresentar na saída de console uma mensagem de
boas-vindas com o seu nome [EXIGÊNCIA
DE SAÍDA DE CONSOLE 1 de 6];

J.
Deve-se apresentar na  saída de console um cadastro de 3 livros
(sendo **2 **deles no mesmo autor) [EXIGÊNCIA DE SAÍDA DE CONSOLE 1 de 6];

K.
Deve-se apresentar na saída de console uma consulta de
todos os livros [EXIGÊNCIA DE
SAÍDA DE CONSOLE 2 de 6];

L.
Deve-se apresentar na saída de console uma consulta por
código de um dos livros [EXIGÊNCIA
DE SAÍDA DE CONSOLE 3 de 6];

M.
Deve-se apresentar na saída de console uma consulta por
setor em que **2 **livros sejam do mesmo autor [EXIGÊNCIA DE SAÍDA DE CONSOLE 4 de 6];

N.
Deve-se apresentar  na  saída de console uma remoção de um dos livros seguida
de uma consulta de todos os livros [EXIGÊNCIA DE SAÍDA DE CONSOLE 5 de 6];
