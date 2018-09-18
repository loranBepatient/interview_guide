# Guide d’entretien front-end

## Général

- Quel est ton langage préféré et pourquoi ?
- Quelle est la différence entre langage compilé et langage interprété ?
- Qu'est-ce qu'un design pattern ? <i>exemple</i>
- Peux-tu citer un gestionnaire de versions ?

- Comment fais-tu ta veille techno ?

- Décrire le parcours quand on tape `http:://www.wikipedia.fr` dans un navigateur
- Quelle est la différence entre une requête `POST` / `PUT` / `PATCH`
- Quelle est la difference entre cookies / sessionsStorage / localStorage

- Peux-tu decrire ou montrer un code dont tu es particulierement fier et expliquer pourquoi ?

- Est-ce que tu joues au ping-pong ?

## CSS
- Quelle est la différence entre ID et class
- Comment centrer une `DIV` horizontalement et verticalement
- Quel preprocesseur CSS connais-tu ? A quoi sert-il ?

## Javascript

- Quelle librairie externe as-tu utilisée ? (yarn / npm)

- Quelle est la différence entre
    `=` -  `==` - `===`

- Quelle est la différence entre
    `var` `let` et `const`

- Quelle est la valeur de x :
    `const x = 1 + ‘3’`

- Qu'est-ce qu'une `Promise` et à quoi ça sert ?

- Qu'est-ce qu'un `Observable` et à quoi ça sert ?

- Quelle est la différence entre:

    `array.forEach()`

    et

    `array.map()`

- Peux tu ecrire un objet user qui contient Nom, Prenom, et une methode speak() ?

- Que retourne la fonction suivante :
    ```
    (function(x) {
        return !!x;
	})(‘a’);

- Que retourne la fonction suivante
    ```
    (function() {
        var foo = 'a';
        (function(foo) {
            foo = 'b';
        })(foo);
        return foo;
    })();

### Exercice

Voici une liste de résultats pour des étudiants.
Nous voulons pouvoir afficher la moyenne des 5 meilleurs notes pour un étudiant

```
const scores = [
  { id: 1, score: 76 },
  { id: 2, score: 99 },
  { id: 1, score: 100 },
  { id: 2, score: 56 },
  { id: 2, score: 12 },
  { id: 2, score: 87 },
  { id: 2, score: 100 },
  { id: 2, score: 18 },
  { id: 1, score: 86 },
  { id: 1, score: 81 },
  { id: 1, score: 83 },
  { id: 2, score: 37 },
  { id: 1, score: 65 },
  { id: 3, score: 40 },
  { id: 3, score: 40 },
  { id: 3, score: 40 },
  { id: 3, score: 40 },
  { id: 3, score: 40 },
  { id: 3, score: 10 }
];
```

Créer une fonction
```
function calculateAverage(id) {
    some magic
}
```
qui retournera la moyenne des 5 meilleures notes pour l'id de l'eleve.

