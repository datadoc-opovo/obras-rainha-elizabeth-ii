# Filmes com referência à Rainha Elizabeth II

Em 8 de setembro, a monarca com o reinado mais longo da história britânica faleceu aos 96 anos. De forma mais direta, como uma personagem central da obra, ou como uma referência do contexto, Rainha Elizabeth II esteve presente em diversas criações artísticas ao longo dessas décadas. Com isso, a Central de Jornalismo de Dados do O POVO (DATADOC) raspou páginas do IMDB com buscas por títulos de séries, filmes e documentários que fazem referência a ela.

A matéria ["Confira séries, vídeos e documentários com referência à Rainha Elizabeth II"](https://mais.opovo.com.br/reportagens-especiais/2022/09/13/confira-series-videos-e-documentarios-com-referencia-a-rainha-elizabeth-ii.html), feita a partir dos dados presentes nesse repositório, pode ser lida no **O POVO+**, plataforma multistreaming de Jornalismo do **O POVO**.

---


## Fonte e coleta de dados

* [Pesquisa no IMDB: Títulos cujo enredo contenham o termo 'Elizabet II'](https://www.imdb.com/search/title/?plot=%22Elizabeth%20II%22&count=250&view=advanced)
* [Pesquisa no IMDB: Títulos com a hashtag 'reference-to-queen-elizabeth-ii'](https://www.imdb.com/search/keyword/?keywords=reference-to-queen-elizabeth-ii&ref_=kw_nxt&mode=detail&page=1&sort=moviemeter,asc)

## Metodologia

As páginas de busca listadas acima foram raspadas com o [Web Scraper](https://www.webscraper.io/) e, a partir dos dados extraídos, foi feita uma análise exploratória dos dados. Os sitemaps construídos para a raspagem estão disponíveis nos arquivos `sitemap_01_rainha_elizabeth_ii` e `sitemap_02_rainha_elizabeth_ii`, na pasta `web_scraper`.

---

## Arquivos gerados
***Dataframes***

* `df_filmes_por_genero.csv`: Classificação das obras por gênero;
* `df_avaliacoes_titulos.csv`: Dataframe com lista de títulos e respectivas avaliações;
* `df_avaliacoes_titulos_top10.csv`: Listagem dos  10 filmes com as avaliações mais altas;
* `top10_generos_referencia.csv`: 10 gêneros mais presentes entre as obras que fazem referência à monarca;
* `referencias_rainha_nota.csv`: 10 obras com maiores notas e que fazem referência à monarca;
* `df_titulos_groupby_ano.csv`: Quantidade de títulso por ano;
* `df_top10_generos_obras.csv`: Top 10 dos gêneros mais presentes entre as obras - total das duas bases utilizadas.

***Visualizações***

* [Os 10 títulos mais bem avaliados do IMDB em que a Rainha Elizabeth II aparece no enredo](https://public.flourish.studio/visualisation/11141675/)
* [Número de obras sobre a rainha Elizabeth II no IMDB por década](https://public.flourish.studio/visualisation/11143455/)
* [Os 10 gêneros mais presentes entre os títulos relacionados à rainha Elizabeth II](https://public.flourish.studio/visualisation/11142300/)
* [Os 10 títulos mais bem avaliados do IMDB com referência à rainha Elizabeth II](https://public.flourish.studio/visualisation/11142501/) 


---

## Como utilizar

Para executar o notebook com a coleta e processamento dos dados, é necessário um ambiente com Python3 e dependências que podem ser instaladas via Pip:

```
!pip install 
!pip install 
!pip install 
```

## A Central DATADOC

A Central de Jornalismo de Dados do O POVO (DATADOC) alia tecnologia e técnicas diversas de análises de dados para produzir um jornalismo de precisão para que você forme sua opinião com segurança. Nosso objetivo é fazer com que todos tenham acesso aos dados utilizados nas notícias que produzimos.

A DATADOC é composta por uma equipe de três jornalistas (sendo uma infografista), uma desenvolvedora front-end e um cientista da computação que coletam, enriquecem e disponibilizam as bases e códigos de cada reportagem para um jornalismo transparente e baseado em evidências.

---

**🔥📰👩🏻‍💻 Se você gostou do nosso material, apoie assinando o OP+ e acompanhando o nosso trabalho.**

**📝📨 Para feedback, dúvidas ou sugestões: datadoc@opovodigital.com**

---

🗓️🕵🏻 Confira também outras produções recentes da central DATADOC: A matéria ***Indígenas representaram menos de 1,2% do total de candidaturas no CE*** apresenta dados sobre candidaturas por raça/cor no Ceará e no Brasil e está [disponível no **O POVO+**](https://mais.opovo.com.br/reportagens-especiais/2022/09/10291900-indigenas-representaram-menos-de-12-do-total-de-candidaturas-no-ce.html).
