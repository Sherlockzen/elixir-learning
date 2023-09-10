# Imutabilidade

-> Um valor uma vez atribuido em memória não pode ser modificado. Dessa forma as operações realizadas com os tipos de dados do elixir não altera o dado em si.

Ex:

```elixir

iex> x = 2
2
iex> x + 4
6
iex> x
2

```

No exemplo anterior estou criando uma variável com valor de 2 e em seguida estou somando esse valor com 4, perceba que ao chamar novamente x após esta operação ele continua apontando para o valor de 2. Se eu quiser alterar o x eu poderia realizar algo assim:

```elixir

iex> x = x + 4
6
iex> x
6

```

Dessa forma meu x agora aponta para o valor 6 em vez do valor 2 anteriormente associado a ele. Perceba no entanto que esse x agora não é o anterior, ele é uma nova instância na memória.