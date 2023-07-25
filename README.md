# Nome do meu projeto

Rápida descrição do objetivo de fazer esse projeto

| :placard: Vitrine.Dev |     |
| -------------  | --- |
| :sparkles: Nome        | **Titulo do meu projeto**
| :label: Tecnologias | java, html, ruby, c# (tecnologias utilizadas)
| :rocket: URL         | https://url-deploy.com.br
| :fire: Desafio     | https://url-do-desafio.com.br

<!-- Inserir imagem com a #vitrinedev ao final do link -->
![](https://via.placeholder.com/1200x500.png?text=imagem+lindona+do+meu+projeto#vitrinedev)

## Detalhes do projeto

Textos e imagens que descrevam seu projeto, suas conquistas, seus desafios, próximos passos, etc...

Passos do projeto.
Iremos explorar os dados de empréstimos dos acervos do sistema de bibliotecas da UFRN.

Um dos objetivos de uma biblioteca é garantir que os materiais informacionais estejam sendo utilizados. Os empréstimos realizados podem ser um indicador, mesmo que de forma básica (pois você não consegue garantir que haja uma leitura ou utilização real).

Por este motivo, entender a quantidade de empréstimos se torna importante.

Questões de diferentes perspectivas podem surgir como:

A quantidade de empréstimos está aumentando ou diminuindo ao decorrer dos últimos anos?
Em quais bibliotecas do sistema estão a maior quantidade de empréstimos?
Quais são os temas mais emprestados? E os menos?

Com estas e outras informações será possível entender o cenário e apresentá-lo à diretoria das bibliotecas, para que possam tomar melhores decisões na melhoria da infraestrutura, dos recursos e processos da unidade de informação.

Mas para que tudo isso seja realizado, você precisará começar com a coleta e organização dos dados para que possa trabalhar com eles nas próximas análises.

Borá lá?!

Você trabalhará com dados apenas dos últimos 10 anos disponíveis. Por isso, importe para seu Jupyter Notebook os dados de:

Chegou a hora, Pedro Ivo Moézia de Lima Junior! Você vai começar a sua jornada no #7DaysOfCode.

Estou muito animado para começar esse desafio! Iremos explorar os dados de empréstimos dos acervos do sistema de bibliotecas da UFRN.

Um dos objetivos de uma biblioteca é garantir que os materiais informacionais estejam sendo utilizados. Os empréstimos realizados podem ser um indicador, mesmo que de forma básica (pois você não consegue garantir que haja uma leitura ou utilização real).

Por este motivo, entender a quantidade de empréstimos se torna importante.

Questões de diferentes perspectivas podem surgir como:

A quantidade de empréstimos está aumentando ou diminuindo ao decorrer dos últimos anos?
Em quais bibliotecas do sistema estão a maior quantidade de empréstimos?
Quais são os temas mais emprestados? E os menos?

Com estas e outras informações será possível entender o cenário e apresentá-lo à diretoria das bibliotecas, para que possam tomar melhores decisões na melhoria da infraestrutura, dos recursos e processos da unidade de informação.

Mas para que tudo isso seja realizado, você precisará começar com a coleta e organização dos dados para que possa trabalhar com eles nas próximas análises.

Borá lá?!

Você trabalhará com dados apenas dos últimos 10 anos disponíveis. Por isso, importe para seu Jupyter Notebook os dados de:

Empréstimos dos acervos das bibliotecas de UFRN 

https://caelum57945.lt.acemlnb.com/Prod/link-tracker?redirectUrl=aHR0cHMlM0ElMkYlMkZnaXRodWIuY29tJTJGRnJhbmNpc2NvRm96JTJGN19EYXlzX29mX0NvZGVfQWx1cmEtUHl0aG9uLVBhbmRhcyUyRnRyZWUlMkZtYWluJTJGRGlhXzEtSW1wb3J0YW5kb19kYWRvcyUyRkRhdGFzZXRzJTJGZGFkb3NfZW1wcmVzdGltb3MlM0Z1dG1fc291cmNlJTNEQWN0aXZlQ2FtcGFpZ24lMjZ1dG1fbWVkaXVtJTNEZW1haWwlMjZ1dG1fY29udGVudCUzRCUyNTIzN0RheXNPZkNvZGUlMkItJTJCUHl0aG9uJTJCUGFuZGFzJTJCMSUyNTJGNyUyNTNBJTJCSW1wb3J0YSUyNUMzJTI1QTclMjVDMyUyNUEzbyUyQmRlJTJCZGFkb3MlMjZ1dG1fY2FtcGFpZ24lM0QlMjU1QkFsdXJhJTJCJTI1MjM3RGF5cyUyQk9mJTJCQ29kZSUyNTVEJTI1MjhQeXRob24lMkJQYW5kYXMlMkItJTJCMSUyNUMyJTI1QUElMkJFZCUyQiUyNTI5JTJCMSUyNTJGNw==&sig=23wrxpVMcPpaMfgu9UvDG8jmjUdUW18dsjcVqWuHoJZh&iat=1690283038&a=%7C%7C476258007%7C%7C&account=caelum57945%2Eactivehosted%2Ecom&email=p%2FLaa4%2BwnIxJNUkyWuhk%2Ffq%2FTOZTvVn8xPnbeo8wKKOxsMA%3D%3AmqMv8yvCKMS10gpt10HKMZXFX3dsaWAB&s=8632c23926ed43f8dd1480ea1ceee11e&i=2315A14372A12A16383



Exemplares do acervo

https://github.com/FranciscoFoz/7_Days_of_Code_Alura-Python-Pandas/blob/main/Dia_1-Importando_dados/Datasets/dados_exemplares.parquet?utm_source=ActiveCampaign&utm_medium=email&utm_content=%237DaysOfCode+-+Python+Pandas+1%2F7%3A+Importa%C3%A7%C3%A3o+de+dados&utm_campaign=%5BAlura+%237Days+Of+Code%5D%28Python+Pandas+-+1%C2%AA+Ed+%29+1%2F7



Dados baixados? Ok, mas são diversas tabelas diferentes e isso dificulta o trabalho. Portanto, o seu primeiro passo é unificar em um único Dataframe todos os dados pertinentes para a análise.

Comece pelos empréstimos e você terá os dados das transações. Depois, mescle com os dados do acervo, para que você possa entender, por exemplo, de qual biblioteca era o material emprestado ou a qual tema ele se referia. Elas se relacionam pela coluna de código de barras de cada material.

Lembre-se que é muito comum receber dados nulos ou duplicados, por isso não deixe de fazer a limpeza.

DICA
Você pode importar os dados diretamente do Github para seu notebook apenas passando o endereço do link “Raw” como origem.

Confira a documentação do Pandas das diferentes formas de entrada de dados.

EXTRA
Deixei este artigo da Alura explicando um pouco mais sobre o formato de arquivo Apache Parquet e também esse meu texto que explica como você pode jogar fora os dados usando o Pandas.

https://www.alura.com.br/artigos/arquivos-parquet?utm_source=ActiveCampaign&utm_medium=email&utm_content=%237DaysOfCode+-+Python+Pandas+1%2F7%3A+Importa%C3%A7%C3%A3o+de+dados&utm_campaign=%5BAlura+%237Days+Of+Code%5D%28Python+Pandas+-+1%C2%AA+Ed+%29+1%2F7&vgo_ee=p%2FLaa4%2BwnIxJNUkyWuhk%2Ffq%2FTOZTvVn8xPnbeo8wKKOxsMA%3D%3AmqMv8yvCKMS10gpt10HKMZXFX3dsaWAB

Esse foi só o primeiro dia e amanhã a gente se encontra aqui, para mais um #7DaysOfCode de Python Pandas.

Após finalizado, não deixe de postar seus resultados nas redes sociais e me marcar.
Ficarei muito feliz de ver o seu trabalho!

Boa jornada!

Francisco Foz
Bibliotecário e Analista de Dados

1-Análise exploratória dos Dados.
Dados de empréstimo dos acervos.

Estrutura dos DataFrames: Os DataFrames combinados pelo `concat` devem ter a mesma estrutura (mesmo número de colunas) na dimensão que está sendo concatenada.
•
Ajuste do índice: Por padrão, o `concat` mantém os índices dos DataFrames originais e os repete quando há duplicações na concatenação. Você pode usar o parâmetro `ignore_index=True` para redefinir o índice do DataFrame resultante.
•
Exemplo: `pd.concat([df1, df2, df3], axis=0)` concatenará verticalmente os DataFrames `df1`, `df2` e `df3`.
2.
`merge`:
•
Operação: O método `merge` é usado para juntar DataFrames com base em colunas em comum, semelhante a um JOIN em bancos de dados relacionais.
•
Estrutura dos DataFrames: Os DataFrames envolvidos no `merge` devem ter colunas em comum que serão usadas como chaves para a junção.
•
Ajuste do índice: O `merge` não se preocupa com o índice dos DataFrames; ele se concentra em combinar os DataFrames com base nas colunas especificadas.
•
Exemplo: `pd.merge(df1, df2, on='coluna_comum')` juntará `df1` e `df2` com base na coluna em comum especificada.
Resumindo, `concat` é usado para combinar DataFrames vertical ou horizontalmente sem considerar valores específicos nas colunas, enquanto `merge` é usado para combinar DataFrames com base em valores específicos em colunas em comum.
Na prática, a escolha entre `concat` e `merge` depende da estrutura dos seus dados e do tipo de operação que você deseja realizar. Se você precisa apenas juntar DataFrames com base em colunas em comum, o `merge` é a escolha apropriada. Se você deseja simplesmente combinar DataFrames ao longo das linhas ou colunas, o `concat` é mais adequado.![image](https://github.com/PedroMoeziaJr/7_Days_of_Code_PYTHON_PANDAS/assets/112977342/00f81010-3d5e-4bad-a4ec-f26151b8c8e7)



