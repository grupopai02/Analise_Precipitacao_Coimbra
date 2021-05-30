# Bem-vindos 👋
# :school_satchel: Contexto
**Este trabalho foi realizado no âmbito da Unidade Curricular de Programação e Algoritmos II lecionada pelo docente João Gilberto de Matos Orvalho na Licenciatura de Comunicação e Design Multimédia da Escola Superior de Educação de Coimbra.**

O nosso projeto consiste na limpeza e tratamento de um conjunto de dados de um ficheiro .csv. Os dados referem-se à precipitação no concelho de Coimbra, entre os dias 30 de Janeiro a 28 de Abril de 2021. Este conjunto de dados obtiveram-se diretamente da base de dados do Instituto Português do Mar e da Atmosfera (IPMA).

**O grupo responsável por este projeto é constituído pelos seguintes elementos: Beatriz Pereira, Joana Lopes, Gonçalo Almeida e João Caetano.**


# :bricks: Estrutura

O repositório está organizado da seguinte forma:

- `Precipitação_coimbra.csv` - Ficheiro extraído da base de dados Instituto Português do Mar e da Atmosfera (IPMA), que contém os dados que vamos tratar no projeto.
- `Precipitção_coimbra.ipynb` - Ficheiro em formato Jupyter Notebook que contem o código na linguagem python.
- `fundamentação de dados.pdf` - Ficheiro que contém a fundamentação do nosso projeto, com um pequeno relatório e especificações técnicas.


# :satellite: API's Usados

Os dados usados neste projeto e muito outros semelhantes, encontram-se no seguinte API: http://api.ipma.pt/#

O ficheiro .csv utilizado obtém-se através do seguinte link: https://api.ipma.pt/open-data/observation/climate/precipitation-total/coimbra/


# :notebook_with_decorative_cover: Dicionário dos dados 

Explicação do conteudo no ficheiro `Precipitação_coimbra.csv` :

|Nome da coluna | Conteúdo                                                  |Possíveis Valores   |
|---------------|-----------------------------------------------------------|--------------------|
| Date          | Data dos valores de referência                            |AAAA-MM-DD          |
| Minimum       | Valor diário mínimo de Precipitação total em mm           |Valores decimais    |
| Maximum       | Valor diário máximo de Precipitação total em mm           |Valores decimais    |
| Range         | Valor diário da amplitude de Precititação total em mm     |Valores decimais    |
| Mean          | Valor diário da mediana de Precipitação total em mm       |Valores decimais    |
| Std           | Valor diário do desvio padrão de Precipitação total em mm |Valores decimais    |
