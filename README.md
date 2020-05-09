# Debounce

Recentemente precisei realizar um trabalho de performance em projeto legado, e me deparei com um problema bastante comum e que vemos muito em algumas aplicações. Um campo de pesquisa/filtro onde cada vez que o usuário digitava uma letra no campo erá feita uma requisição na API.

Pesquisando sobre, cheguei até o debounce para não deixar uma ação ser executada toda hora, segurando a frequência de execução de certa ação.
Pensando nisso fiz o exemplo de pesquisa/filtro de usuários, consumindo uma API de usuários, vamos controlar os requests para essa API criando uma função de Debounce para esse controle.

No meu caso como se tratava de um legado, fiz em javascript puro, porém temos outras aplicações que fazem isso de uma forma mais robusta e com maiores tratamentos

- [Lodash](https://www.npmjs.com/package/lodash.debounce)



## Principais tecnologias utilizadas
- HTML
- CSS
- JavaScript

![](https://github.com/EusRique/debounce/blob/master/debounce.gif)