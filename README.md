# analise_de_Abel_Ferreira_no_Campeonato_Brasileiro
Estudo sobre os jogos do Palmeiras sobre o comando de Abel Ferreira no Brasileirão de 20, 21, 22 e 23.

Os dados iniciais foram obtidos pelo transfermarket e contam, a princípio com dados até 30/07/2023. Para acessar o datalake com os dados basta acessar: https://basedosdados.org/dataset/c861330e-bca2-474d-9073-bc70744a1b23?table=18835b0d-233e-4857-b454-1fa34a81b4fa
Esses dados estão no arquivo ados_entre_09_08_2020_e_29_07_2023.csv

O arquivo criando_df_2020_2021_2022_e_2023_ate_29_07_2023.ipynb foi utilizado para criar os dataframes individuais de cada Campeonato Brasileiro, gerando os arquivos palmeiras_2020.csv, palmeiras_2021.csv, palmeiras_2022.csv e palmeiras_2023.csv
Esses arquivos possuem os seguintes dados:

ano_campeonato - Ano da competição;
data - Data da partida;
rodada - número da rodada da partida;
estadio - Estádio onde foi realizado o jogo;
time_mandante - Time mandante da partida;
time_visitante - Time visitante da partida;
tecnico_mandante - Técnico da equipe mandante;
tecnico_visitante - Técnico da equipe visitante;
gols_mandante - Gols da equipe mandante;
gols_visitante - Gols da equipe visitante;

O arquivo analises.ipynb possui as análises realizadas nesses dados como: Aproveitamento nos jogos como mandante e visitante, aproveitamento durante o capeonato, análise dos jogos e aproveitamento de Abel contra cada adversário e contra cada técnico.

O arquivo será atualizado conforme o banco de dados do Transfermarket fornecer mais dados das partidas.
