# Os sentidos da doutrinacao e da ideologia de gênero na Comissão Especial Escola sem Partido

O reposítório apresenta uma proposta de classificação das notas taquigráficas da Comissão Escola sem Partido. Este modelo poderá ser replicado para outras comissões. Assim, o scrip é uma proposta de classificação, e tem como potencial, a análise de redes e flexibilidade para o acoplamento de dados, seja pelo ID do deputado ou por seus nomes. 
O modelo realiza diversas tarefas de ETL para a formação de um banco de dados.
A partir de uma lista de notas taquigráficas em PDF, o modelo extrai e separa o nome dos oradores do texto de suas falas.
Esse banco foi enrriquecido com dados referentes a religião dos parlamentares, se pertenciam a Comissão Escola sem Partido, bem como informações sobre o posicionamento, se favorável ou contrário ao projeto.

## Objetivo:

Mapear os sentidos atribuídos às noções de “doutrinação ideológica” e “ideologia de gênero” e as justificativas em defesa e contra contidas nas falas de deputados da Comissão. Nesse caso, notas taquigráficas.

## Aplicação

* Análise de redes de atores.
* Análise de discuso a partir de NLP.
* Visualização de gráfico Lexical Dispersion Plot.
* Centralização do debate parlamentar e cronologia dos fatos e das falas em um banco de dados.

## Problemas
As notas taquigráficas apresentam diversos formatos de publicação, exigindo a separação dos documentos em tipos. A partir desses tipos foi possível ralizar ETL de modo concentrado, o que facilitou a separação de fragmentos do texto com Regex. 

## Obs.
Os bancos de dados não foram inseridos em função de constituir parte de um trabalho ainda em desenvolvimento e não publicado. 






