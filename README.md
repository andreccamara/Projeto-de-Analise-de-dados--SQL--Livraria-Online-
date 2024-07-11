# Projeto final de Análise de dados - SQL - Livraria Online 

# Descrição do Projeto
O coronavírus pegou o mundo todo de surpresa mudando a rotina das pessoas. Os moradores das cidades já não passavam mais seu tempo livre fora de casa, indo a cafés e shoppings; a maioria ficou em casa lendo livros. Isso chamou a atenção de startups que se apressaram para desenvolver novos aplicativos para os amantes de livros.

Neste projeto temos um banco de dados(ficticio) de um dos serviços concorrentes nesse mercado. Ele contém dados sobre livros, editoras, autores, e classificação de clientes e avaliação de livros. Essa informação será usada para gerar uma proposição válida para o novo produto.

# Objetivos
- Encontrar o número de livros lançados depois de 1 de janeiro de 2000.
- Encontrar o número de avaliações e a classificação média para cada livro.
- identificar a editora que lançou o maior número de livros com mais de 50 páginas (isso vai ajudar a excluir brochuras e publicações parecidas da sua análise).
- identificar o autor com a média mais alta de classificação de livros: olhar apenas para livros com pelo menos 50 classificações.
- Encontrar o número médio de avaliações entre usuários que classificaram mais do que 50 livros.

# Ferramentas e Bibliotecas Utilizadas
- Python: Linguagem principal utilizada para a análise.
- sqlalchemy: Biblioteca python para trabalhar com consultas SQL

# Metodologia:
- importação dos dados
- Descrever os objetivos do estudo.
- Estudar as tabelas (imprima as primeiras linhas).
- Fazer uma consulta SQL para cada uma das tarefas.
- Enunciar os resultados de cada consulta no notebook.
- Descrever suas conclusões para cada uma das tarefas.

# lista das tabelas e suas colunas:

books — livros:

Contém dados sobre livros:

book_id — identificador do livro
author_id — identificador do autor
title — título
num_pages — número de páginas
publication_date — data de publicação
publisher_id — identificador da editora
authors — autores:

Contém dados sobre os autores:

author_id — identificador do autor
author — autor
publishers — editoras:

Contém dados sobre editoras:

publisher_id — identificador da editora
publisher — editora
ratings — classificações:

Contém dados sobre classificação dos usuários:

rating_id — identificador da classificação
book_id — identificador do livro
username — o nome do usuário que avaliou o livro
rating — classificação
reviews — avaliação:

Contém dados sobre revisão dos clientes:

review_id — identificador da revisão
book_id — identificador do livro
username — o nome do usuário que revisou o livro
text — o texto da revisão

# Resultados
São 1000 livros de 635 autores publicados por 340 editoras com 6456 avaliações e 2793 criticas 
São 821 publicações após o ano 2000
O numero de avaliações por livro: 2793 
A media das medias de classificações por livro é 3,9. 
Das 334 editoras que publicaram livros, a maior é Penguin Books  
são 14 autores que tem livros com mais de 50 avaliações, com uma avaliação media entre 4.2 e 3.6 
O mais bem avaliado é a JK rowlling em conjunto com a ilustradora Mary GrandPré depois markus Zusak e depois J.R.R.Tolkien.

# Aprendizados
Este projeto permitiu-me desenvolver as seguintes habilidades:

- consultas complexas de SQL em python
- utilização de funções e variaveis para deixar o codigo mais limpo e didatico


# Como Executar o Projeto

- Clone o repositório
- Navegue até o diretório do projeto
- Instale as dependências
- Execute o script principal


## Contato:
Andre Corso Camara
[linkedin](https://www.linkedin.com/in/andre-corso-c%C3%A2mara/)
[email](devandrecorso@hotmail.com)