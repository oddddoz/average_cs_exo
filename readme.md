# Average C

Le but de ce TP est de faire un petit programme pour calculer une moyenne.

## Consignes 

Vous coderez dans le ficher `Program.cs` du repository.
Il sera nécessaire de maitriser la déclaration de variable, la gestion de tableau,
les conditions et les boucles. 

### Logique

Faire une boucle permettant d'entrer autant de note que l'utilisateur le souhaite.
On ajoute ces notes à une `List` csharp. 

Si l'utilisateur envoie "end".
Alors toutes les notes ont étés entrées et la moyenne peut être calculé et affiché.

Pour calculer la moyenne il suffit de boucler sur toutes les notes, faire la somme puis diviser cette somme sur le nombre de notes totales.

### Rappel 

Pour récuper l'input d'un utilisateur dans la console. On peut faire `Console.ReadLine()`, cette fonction
attend l'input puis le retourne sous forme de `string`.
Il sera donc necessaire d'essayer de le convertir en `int` ou `float` pour pouvoir faire le calcul de la moyenne.

### Bonus

Pour ceux qui ont fini. On peut essayer d'ajouter un système permettant d'entrer le coéfficient après chaque note.
Puis calculer la moyenne en prenant en compte les coéfficients.

### La note

Cette exercice est ramassé et pourra faire l'objet d'une note sur 10 ou d'une note bonus. 
