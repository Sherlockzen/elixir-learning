# Int

-> Representa os números inteiros

```elixir
1 + 1 = 2
```

# Float

-> Representa os números decimais

```elixir
1 / 2 = 0.5
```
# String

-> Strings em Elixir são encodadas com UTF-8 e são envoltas por **aspas duplas**

```elixir
"Some Text"
```

# Boolean

-> Representa o booleanos true ou false

# Atoms

-> Um atom é uma constante cujo valor é o seu próprio nome. Se assemelha ao signals do Ruby

```elixir
:foo
:foo == :bar
false
```


# Aridade da função

-> No elixir as funções são representadas com a sua aridade que nada mais é que os seus respectivos parâmetros. Isso acontece porque uma mesma função pode ter aridades diferentes, ou seja quantidade de parâmetros diferentes.

```elixir
do_something(x) != do_something(x, y)

#Representação de função e sua aridade
do_something/1
do_something/2
```