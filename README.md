# Diagramme de classe

![Classes](uml/classes.png)

## Vrai ou faux

Etant donné le diagramme de domaine ci-dessus, les assertions suivantes sont-elles vraies ou fausses ? 
- Etudiant est une classe d’association
Faux (Cours serait une classe d'association par exemple)
- Un étudiant peut participer à autant de cours qu’il veut
Vrai la cardinalité (côté Cours) * représente de 0 à infini
- Plusieurs professeurs peuvent enseigner la même discipline
Faux car pour chaque discipline il y a qu'un professeur
- Un professeur peut enseigner plusieurs disciplines
Vrai il peut en enseigner autant qu'il veut (cardinalité *)
- Un cours peut être enseigner à 2 étudiants
Faux il faut au minimum 5 étudiants
- Un cours peut être enseigner à 20 étudiants 
Vrai, de 5 à 30 c'est valide

## Question ouverte

Représentez la même association avec la notation UML « petit losange » 

- Quelles informations perd-on par rapport au diagramme ci-dessus ?

On perd le lien direct entre Professeur et Discipline.