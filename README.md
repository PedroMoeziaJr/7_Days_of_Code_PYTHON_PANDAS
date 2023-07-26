# 7 Days of code PYTHON e PANDAS

Projeto para o desafio da Alura 7 days of code voltado para linguem Python utilizado a biblioteca Pandas

| :placard: Vitrine.Dev |     |
| -------------  | --- |
| :sparkles: Nome        | **Análise de Dados Bibliotecário**
| :label: Tecnologias | Python, Pandas e Jupyter 
| :rocket: URL         | https://url-deploy.com.br
| :fire: Desafio     | [https://url-do-desafio.com.br](https://7daysofcode.io/matricula/pandas)

<!-- Inserir imagem com a #vitrinedev ao final do link -->
![](https://via.placeholder.com/1200x500.png?text=imagem+lindona+do+meu+projeto#vitrinedev)

## Detalhes do projeto

Passos do projeto.
Iremos explorar os dados de empréstimos dos acervos do sistema de bibliotecas da UFRN.

Um dos objetivos de uma biblioteca é garantir que os materiais informacionais estejam sendo utilizados. Os empréstimos realizados podem ser um indicador, mesmo que de forma básica (pois você não consegue garantir que haja uma leitura ou utilização real).

Por este motivo, entender a quantidade de empréstimos se torna importante.

Questões de diferentes perspectivas podem surgir como:

A quantidade de empréstimos está aumentando ou diminuindo ao decorrer dos últimos anos?
Em quais bibliotecas do sistema estão a maior quantidade de empréstimos?
Quais são os temas mais emprestados? E os menos?

Com estas e outras informações será possível entender o cenário e apresentá-lo à diretoria das bibliotecas, para que possam tomar melhores decisões na melhoria da infraestrutura, dos recursos e processos da unidade de informação.

Os dados trabalhados são dos últimos 10 anos.

Projeto foi feito desenvolvido através do Jupyter

Vamos entender:

A quantidade de empréstimos está aumentando ou diminuindo ao decorrer dos últimos anos?

Em quais bibliotecas do sistema estão a maior quantidade de empréstimos?

Quais são os temas mais emprestados? E os menos?

Com estas e outras informações será possível entender o cenário e apresentá-lo à diretoria das bibliotecas, para que possam tomar melhores decisões na melhoria da infraestrutura, dos recursos e processos da unidade de informação.

Primeiro vamos carregar os dados dos acervso das bibliotecas da UFRN:



https://caelum57945.lt.acemlnb.com/Prod/link-tracker?redirectUrl=aHR0cHMlM0ElMkYlMkZnaXRodWIuY29tJTJGRnJhbmNpc2NvRm96JTJGN19EYXlzX29mX0NvZGVfQWx1cmEtUHl0aG9uLVBhbmRhcyUyRnRyZWUlMkZtYWluJTJGRGlhXzEtSW1wb3J0YW5kb19kYWRvcyUyRkRhdGFzZXRzJTJGZGFkb3NfZW1wcmVzdGltb3MlM0Z1dG1fc291cmNlJTNEQWN0aXZlQ2FtcGFpZ24lMjZ1dG1fbWVkaXVtJTNEZW1haWwlMjZ1dG1fY29udGVudCUzRCUyNTIzN0RheXNPZkNvZGUlMkItJTJCUHl0aG9uJTJCUGFuZGFzJTJCMSUyNTJGNyUyNTNBJTJCSW1wb3J0YSUyNUMzJTI1QTclMjVDMyUyNUEzbyUyQmRlJTJCZGFkb3MlMjZ1dG1fY2FtcGFpZ24lM0QlMjU1QkFsdXJhJTJCJTI1MjM3RGF5cyUyQk9mJTJCQ29kZSUyNTVEJTI1MjhQeXRob24lMkJQYW5kYXMlMkItJTJCMSUyNUMyJTI1QUElMkJFZCUyQiUyNTI5JTJCMSUyNTJGNw==&sig=23wrxpVMcPpaMfgu9UvDG8jmjUdUW18dsjcVqWuHoJZh&iat=1690283038&a=%7C%7C476258007%7C%7C&account=caelum57945%2Eactivehosted%2Ecom&email=p%2FLaa4%2BwnIxJNUkyWuhk%2Ffq%2FTOZTvVn8xPnbeo8wKKOxsMA%3D%3AmqMv8yvCKMS10gpt10HKMZXFX3dsaWAB&s=8632c23926ed43f8dd1480ea1ceee11e&i=2315A14372A12A16383



Depois, vamos carrega os dados dos Exemplares do acervo

https://github.com/FranciscoFoz/7_Days_of_Code_Alura-Python-Pandas/blob/main/Dia_1-Importando_dados/Datasets/dados_exemplares.parquet?utm_source=ActiveCampaign&utm_medium=email&utm_content=%237DaysOfCode+-+Python+Pandas+1%2F7%3A+Importa%C3%A7%C3%A3o+de+dados&utm_campaign=%5BAlura+%237Days+Of+Code%5D%28Python+Pandas+-+1%C2%AA+Ed+%29+1%2F7

<h1>Dia_1 : Unificar em um único dataframe todos os dados pertinentes para a análise.</h1>
<h2>Etapas:</h2>
## 1- Carregar os dados de empréstimos e concatena-los usando a função pd.concat()
## 2- Verificar dados duplicados e nulos e retira-los
## 3- Carregar os dados do acervo e mesclar com os dados de empréstimo usando a função pd.merge()


