# Introduction à la programmation fonctionnelle avec Elixir

## Qu’est-ce que la programmation fonctionnelle ?

La programmation fonctionnelle est un paradigme de programmation basé sur l’utilisation des fonctions.

Contrairement à la programmation impérative où l’on modifie souvent l’état du programme, la programmation fonctionnelle privilégie :

- les fonctions pures,
- l’immutabilité,
- la composition de fonctions,
- la transformation des données.

Elixir est un langage fortement inspiré de ce paradigme.

---

# Pourquoi apprendre la programmation fonctionnelle ?

La programmation fonctionnelle aide à :

- écrire du code plus prévisible,
- réduire les bugs liés aux mutations,
- mieux gérer la concurrence,
- créer des applications plus maintenables,
- penser en termes de transformations de données.

C’est aussi une excellente manière d’améliorer sa logique de programmation.

---

# Pourquoi Elixir ?

Elixir est un langage moderne construit sur la VM Erlang (BEAM).

Il est particulièrement connu pour :

- sa tolérance aux pannes,
- sa concurrence,
- ses performances pour les systèmes distribués,
- sa syntaxe agréable,
- son approche fonctionnelle.

Elixir est souvent utilisé pour :
- APIs backend,
- systèmes temps réel,
- chats,
- applications distribuées,
- plateformes scalables.

---

# Les concepts clés de la programmation fonctionnelle

## 1. Immutabilité

Les données ne sont pas modifiées après leur création.

Exemple :

```elixir
x = 10
x = 20
````

Ici, on crée un nouveau binding.

---

## 2. Fonctions pures

Une fonction pure :

* retourne toujours le même résultat pour les mêmes arguments,
* ne modifie pas l’extérieur.

Exemple :

```elixir
def add(a, b) do
  a + b
end
```

---

## 3. Functions as First-Class Citizens

Les fonctions peuvent être :

* stockées dans des variables,
* passées comme arguments,
* retournées par d’autres fonctions.

---

## 4. Pattern Matching

Le pattern matching est au cœur de Elixir.

Exemple :

```elixir
{name, age} = {"Alpha", 22}
```

---

## 5. Recursion

La récursion remplace souvent les boucles classiques.

Exemple :

```elixir
def countdown(0), do: "Terminé"

def countdown(n) do
  IO.puts(n)
  countdown(n - 1)
end
```

---

# Différence avec JavaScript

En JavaScript :

```js
let count = 0
count++
```

On modifie la valeur.

En Elixir :

```elixir
count = 0
count = count + 1
```

On crée un nouveau binding.

---

# Philosophie fonctionnelle

Au lieu de penser :

> “Comment modifier cette donnée ?”

On pense :

> “Comment transformer cette donnée en une nouvelle donnée ?”

---

# Structure du parcours

Dans ce dépôt nous allons apprendre :

1. Variables et types
2. Immutabilité
3. Fonctions
4. Pattern Matching
5. Recursion
6. Enum
7. Pipe Operator
8. Higher Order Functions
9. Processes
10. OTP

---

# Objectif du dépôt

Ce dépôt sert à :

* documenter mon apprentissage,
* pratiquer régulièrement,
* construire des mini projets,
* comprendre profondément la programmation fonctionnelle avec Elixir.
