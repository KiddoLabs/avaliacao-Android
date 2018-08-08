# Teste para avaliação Android - Kiddo Labs :smirk:

--- 
Este projeto visa testar o conhecimento dos programadores **Android** que estão na fase de seleção da [Kiddo Labs](www.kiddolabs.com).

<p align="center">
	<img src="img/android.png">
</p>


### Instruções para a entrega do desafio

1. Primeiro, faça um fork deste projeto para sua conta no GitHub (crie uma se você não possuir).
1. Crie uma nova branch, com seu nome e sobrenome.
1. Faça um pull-request com o seu projeto.

### Instruções para o desenvolvimento

* O layout foi desenvolvido em [Sketch](https://www.sketchapp.com/), faça o download trial caso você não possua, ou caso tenha expirado seu período de teste, se baseie nos prints das telas.
* O APP deverá ter 3 telas, e as APIs do [themoviedb](https://www.themoviedb.org/documentation/api)
* Crie uma conta no TheMovieDB e pegue sua API Key
* A primeira tela consumirá a API de listar os filmes popualares [API de exemplo](https://developers.themoviedb.org/3/movies/get-popular-movies)
* A segunda tela, se baseando no retorno da rota anterior, deverá ter os detalhes do filme
* A terceira tela mostrará as opções de compra do filme, não é necessária a implementação da compra
* A quarta tela deverá mostrar os filmes favoritados
* Salve uma APK do app na pasta APK

**Veja a documentação completa da API em [API TheMovieDB](https://www.themoviedb.org/documentation/api)** 


### Layouts
Siga o layout abaixo para desenvolver o projeto.

Use o [Teste_Android.sketch](Teste_Android.sketch)


|               Home               |            Detalhe do filme           |       Compra do filme
|----------------------------------|---------------------------------------|---------------------------------------|
|<img src="img/home.png" width="180">  |  <img src="img/detalhe.png" width="180">  |   <img src="img/comprar_selecionado.png" width="180">  |
                                  


### Tela de principal/tela de favoritos
1. A tela deverá consumir a API de lista de filmes do themoviedb, deverá retornar todos os filmes, paginados de 20 em 20 itens.
1. Filtar para mostrar somente os filmes favoritados.
1. Scroll inifinito.

### Tela de detalhe do filme
1. Pegar as informações do filme clicado.
1. Usar banco de dados para favoritar o filme.
1. Checar se filme já está salvo, se estiver, trocar botão para remover do favorito.

### Tela de compra do filme
1. Mostrar todas as opções de compra retornados da API.
1. Caso não tenha nenhuma opção, mostrar que não está disponível para compra ou alugar.



### Deve conter
1. Checar se tem conexão com internet
1. Caso haja falha na request, avisar a falha
1. Cache de imagens
1. Scroll infinito
1. Suportar versão mínima api 19
1. Usar um arquivo .gitignore no seu repositório
1. Usar um Framework para Comunicação com API
1. Fazer mapeamento json
1. Indicativo de carregamento a cada página


### Ganha + pontos se conter :scream:
1. Testes unitários
1. Não conter memory leak
1. Documentação do código
1. Transições personalizadas entre as telas
1. Pull to refresh
1. Utilizar alguma arquitetura de desenvolvimento
1. Layout de empty data caso não tenha favoritos
1. Programação reativa
1. Databinding ou ButterKnife
1. Kotlin :heart:
1. Efeitos, muitos efeitos, amamos efeitos. Be creative! :rocket:


As sugestões de bibliotecas fornecidas são só um guideline, sinta-se à vontade para usar soluções diferentes e nos surpreender. O importante de fato é que os objetivos macro sejam atingidos.

### Avaliação :mag_right:

Seu projeto será avaliado de acordo com os seguintes critérios:

* Sua aplicação preenche os requerimentos básicos?
* Você documentou a maneira de configurar o ambiente e rodar sua aplicação?
* Você seguiu as instruções de envio do desafio?
* Adicionalmente, tentaremos verificar a sua familiarização com as bibliotecas padrões, bem como sua experiência com programação orientada a objetos a partir da estrutura de seu projeto.



# Boa sorte! :smile:
