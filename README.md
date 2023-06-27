# Exemplo de código em Python lendo JSONL do SNSCRAPE

Utilizamos o SNSCRAPE para capturar JSONS, esse comando aqui serve para colocar esses mesmo arquivos num banco de dados para melhor manipulação.

A ordem que vocês devem olhar os arquivos comentados para melhor compreensão:


1) alchemy.py >> arquivo que monta a estrutura do banco de dados, determinando suas colunas;
2) config.json\[.default\] >> arquivo onde devem ser colocadas as credenciais de acesso ao banco;
3) run_configuration.py >> executa a construção da estrutura do banco de dados;
4) database.py >> conjunto de comandos que permitirá inserção de dados no banco de dados;
5) read_json.py >> arquivo que faz a leitura dos json capturados pelo SNSCRAPE;
