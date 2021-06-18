# semana6
Introdução a APIs

1) Qual a relação entre os métodos HTTP e o CRUD?

CRUD = CREATE, READ, UPDATE E DELETE
O HTTP tem métodos bem similares a esses, como por exemplo o POST que pode ser relacionado ao CREATE, o GET ao READ, o PUT ao UPDATE e o DELETE que tem, inclusive, o mesmo nome no CRUD.

2) Comente, com exemplos, a diferença entre o PUT e o PATCH.

O PUT serve para criar ou atualizar dados, geralmente mais gerais. O PATCH atualiza termos específicos.

3) Assim como na aula, apresente os dados dos JSONs no console 
    - No colors-rgb.js apresente o nome da cor e o codigo RGB como no exemplo: "gainsboro - rgb(220, 220, 220, 1)"
    - No estados-cidade.js apresente o nome do Estado, a sigla e todas as cidadades, sem arrays aparentes no console
    - No filmes.js apresente titulo, plot, generos e lingua. Genero e lingua devem ser apresentados em arrays no console.

4) Defina o conceito de idempotência e como uma API pode ser idempotente

Idempotência é uma propriedade onde operações aplicadas repetidas vezes não serão capazes de alterar o resultado após a aplicação inicial. "Por exemplo, na aritmética, adicionar zero a um número é uma operação idempotente." O GET, por exemplo, é uma operação idempotente pois pode retornar a mesma resposta da primeira chamada inúmeras vezes.

5) Cite alguns diferentes padrões de projetos de software:

Abstract Factory, Factory Method, Singleton.
