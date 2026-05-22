# Variables et types de base

## Variables

En Elixir, les variables sont immutables.

Exemple :

```elixir
name = "Alpha"
age = 22
````

---

## Affichage

```elixir
IO.puts(name)
```

---

## Interpolation

```elixir
IO.puts("Bonjour #{name}")
```

---

# Types de base

## Integer

```elixir
age = 22
```

## Float

```elixir
price = 19.99
```

## Boolean

```elixir
is_admin = true
```

## String

```elixir
name = "Alpha"
```

## List

```elixir
numbers = [1, 2, 3]
```

## Tuple

```elixir
user = {"Alpha", 22}
```

---

# Vérifier le type

```elixir
is_integer(age)
is_float(price)
is_boolean(is_admin)
```

---

# Important

Les variables en Elixir ne sont pas modifiées comme dans les langages impératifs.

```elixir
x = 10
x = 20
```

Ici on crée un nouveau binding.

---

# Résumé

Dans cette section nous avons appris :

* les variables,
* les types primitifs,
* l’interpolation,
* l’affichage.
