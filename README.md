# Exercice 20 - Formulaires HTML



## Directives

- Récupérez et clonez le dépôt git depuis l'adresse Github classroom que je vais vous donner via Teams.

## Formulaire

- Les informations du formulaire doivent être envoyé à l'adresse "https://mathieufrechette.ca/validation.php" avec la méthode **POST**
- Dans le titre **Coucours de beauté caprin de Montpellier 2022**. l'année (2022) doit être calculé et affiché en Javascript selon la date actuelle. 
- Ajoutez en css une bordure dans le bas de chaque input qui est **required**.

### Section Information propriétaire

| Label    | Type               | Notes                                                        |
| -------- | ------------------ | ------------------------------------------------------------ |
| Nom      | input type "text"  | Doit avoir la valeur "proprietaire_nom" à l'attribut name. C'est un champs requis |
| Prénom   | input type "text"  | Doit avoir la valeur "proprietaire_prenom" à l'attribut name. C'est un champs requis |
| Adresse  | input type "text"  | Le nombre maximal de caractère est de 50.                    |
| Ville    | input type "text"  | Le nombre maximal de caractère est de 30.                    |
| Courriel | input type "email" | C'est un champs requis                                       |

 **Validation à faire en Javascript**

- Les champs nom, prénom et courriel ne doivent pas être vide.
- Le courriel doit être validé avec une expression régulière. 
- La longueur des champs adresse et ville doit aussi être validé en JS.

Vous pouvez utiliser cette constante pour tester le courriel avec une expression régulière : 

`const regex_email = /^[\w-\.]+@([\w-]+\.)+[\w-]{2,4}$/;`

### Section Information participant

| Label | type             | Notes                                                        |
| ----- | ---------------- | ------------------------------------------------------------ |
| Nom   | input type text  | C'est un champs requis                                       |
| Race  | select           | Les valeurs sont Alpine, Saanen, Nubienne, Toggenbourg, La Mancha. |
| Sexe  | input type radio | La valeur male est sélectionnée par défaut.                  |

**Validation à faire en Javascript**

- Quand on modifie la valeur du sélect de la race, on modifie l'image de la chèvre selon la race sélectionnée.
- Le champ nom ne doit pas être vide.