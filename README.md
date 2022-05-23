Desafio - Gerando Relatórios com Paralelismo - Ignite Elixir

Projeto:

* Segundo desafio proposto pelo Ignite na trilha de Elixir da Rocketseat, para praticar e fixar o aprendizado criando o projeto Gerando Relatórios com Paralelismo no Elixir.

Tecnologias Usadas:

* Elixir
* Erlang

Como Executar:

* Após clonar o repositório, em um Terminal execute os seguintes comandos:

* iex -S mix

* :timer.tc(fn -> GenReport.build_from_many(["part_1.csv", "part_2.csv", "part_3.csv"]) end)

Importante:

* Você deve possuir um ambiente apto a executar o Elixir.
