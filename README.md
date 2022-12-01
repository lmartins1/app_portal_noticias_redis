# app_portal_noticias_redis

Simples portal de notícia para praticar a utilização do Redis (armazenamento de resultado de consultas em memória para não haver consumo excessivo do banco de dados) no laravel e o pacote Debugbar para receber as consultas que o sistema faz e seu tempo de execução.

1 - A consulta é realizada no banco de dados;
2 - A consulta já não é mais realizada em banco de dados, sendo retornado seu valor a partir do armazenamento realizado em cache.

![1](https://user-images.githubusercontent.com/114930799/205116489-524efa08-a768-4bbe-8aa8-f67e7972a97a.PNG)

![2](https://user-images.githubusercontent.com/114930799/205116495-f7bd1c90-6ac8-4974-a884-db29ea6125db.PNG)
