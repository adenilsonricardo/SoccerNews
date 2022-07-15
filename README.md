# soccer-news-app


## Sobre
Criar um App Android Nativo usando a linguagem de programação Java, explorando os componentes nativos mais atuais oferecidos pelo Android Jetpack e utilizar um repositório simulando uma API REST para as imagem e link das reportagens.

## Objetivo
Parte 1:
- Criação do App Soccer News;
- Refatorando o Bottom Navigation Padrão;
- CardView para as notícias;
- Colocando as noticias no RecyclerView

Parte 2:
- Criação da pseudo-API: https://github.com/adenilsonricardo/soccer-news-api
- Classes de domínio e consumo da API via Retrofit;
- Gerenciar imagens pelo Picasso;
- Intent Nativa para Links externos;
- Revisão Estrutural

Parte 3:
- Consumir imagens otimizadas para o App;
- Intent nativa para compartilhar no Android;
- Evento de Click para Favoritar;
- Room para persistência de dados locais

Parte 4:
- Melhorias:
   - Centralização do android.content.Context;
   - Entendendo o Repository;
   - Refactoring visando o Repository;
   - SwipeRefreshLayout e tratamento de estados

## Projeto

### App com notícias sobre o futebol feminimo, com botões para acesso a matéria completa, favoritar e compartilhar, e com uma segunda tela para mostrar as noticias favoritadas.
- Tela inicial - News:
  - Imagem;
  - Titulo da Noticia;
  - Resumo;
  - Botão do link da noticia;
  - Botão favoritar;
  - Botão Share
  
- Tela secundária - Favorites:
  - Imagem;
  - Titulo da Noticia;
  - Resumo;
  - Botão do link da noticia;
  - Botão favoritar;
  - Botão Share
  
- Visto e aplicados os conceitos sobre o pacote Android Jetpack, Material Design, Layouts de app, Modelagem de API, Bibliotecas Retrofit e Glide e BottomNavigation vistas ao longo do curso.
