# Json

## Définition

JSON (JavaScript Object Notation – Notation Objet issue de JavaScript) est un format léger d'échange de données. Il est facile à lire ou à écrire pour des humains.

## Syntaxe

Le JSON permet de structurer les données sous forme d'un **tableau associatif**, c'est à dire un tableau qui associe une **valeur** à chaque **clé**.

```json
var myObj = {name: "John", age: 31, city: "New York"};
```

## Méthodes utiles

### Convertir en string : stringify 

Cette fonction transforme un JSON en String
```json
var myJSON = JSON.stringify(myObj);
```
### Convertir en JSON : parse

```json
var myJSON = '{"name":"John", "age":31, "city":"New York"}';
var myObj = JSON.parse(myJSON);
```
