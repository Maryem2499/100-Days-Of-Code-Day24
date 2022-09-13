# Files, Directories and Paths
## Goals : 
Nous allons apprendre à travailler avec le syetème de fichiers local et comprendre le fonctionnement des annuaires.
A la fin de la journée, nous aurons améliorer notre précédent jeu de serpent.
Si le match est terminé, le score le plus élevé sera mis à jour pour que nous puissons continuer à assayer de s'améliorer au serpent.
## Ajouter le score le plus elevé au jeu du serpent :
Commençant avec l'ajout de la fonctionnalitée permettant de suivre les scores.
## Comment ouvrir, lire et écrire dans un fichier en utilisant le mot clé "with" :
Parlons du système de fichiers et de la façon dont vous pourriez utiliser Python pour ouvrir des fichiers, lire des fichiers, d'écrire dans des fichiers et aussi de les fermer à nouveau, tout cela sans toucher la souris.
### Ouvrir un fichier :
méthode intégré. Vous pouvez pas donc besoin d'importer quoi que ce soit, vous pouvez l'utiliser directement. Et ça necessite quelque intrants, le fichier que vous voulez ouvrir, le mode dans lequel vous vouliez ouvrir ce fichier ainsi d'autres choses facultatives que vous pouvez les spécifier.
### Lire à partir d'un fichier \ un fichier : 
cette méthode renvoi le contenu de fichier sous forme de chine de caractéres, et l'enregistrer dans une variable.
### Ecrire  dans un fichier : 
permet d'ajouter des ligne dans votre fichier soit en supprimant les lignes précédentes soit sans les supprimer.
## Challenge : Lire et écrire le score le plus elevé dans un fichier dans le jeu du serpent : 
Malheureusement, comme vous l'avez vu précédement, au moment ou nous menons ce jeu et ou nous réalisons une nouvelle jeu, le score le plus elevé la prochaine fois que nouq recommencerons le jeu qui est complétement perdu.
## Copréhension des chemins d'accés absolues : 
les fichier n'ont pas seulement un nom. Ils ont aussi un chemin ou une façon de les atteindre.
Rappeler que sur l'ordinateur, il y'a des fichiers et des dossiers. Dont les fichiers peuvent vivre dans des dossiers et vous pouvez naviguer dans plusieurs dossiers pour arriver à un dossier particulier.
 Ces dérnier commencent toujours par rapport à la racine.
## Introduction "the Mail Merge challenge"
Il est le temps de mettre à l'épreuve ce que vous avez appris. Dans ce projet nous allons, faire un peu de fusion de courrier qui est l'endroit ou vous prenez quelque chose comme une liste des noms, et nous voulons insérer chacun de ces noms dans une lettre.
Suivre les inddices1, 2 et 3.
## Solution :
### Méthode readlines() : 
Renvoyer toutes les lignes du fichiers sous forme de liste ou chaque ligne est un élément de l'objet liste.
### Méthode String replace() :
Permet de remplacer des chaines de caractére en Python. ==> Consiste à remplacer une phrase spécifiée une autre phrase spécifiée.
Exemple : txt = "23 years old old"
            x = txt.replace("23","24")
            print(x) 
Résultat : 24 years old
### Méthode String strip() :
Supprime les espaces au début et à la fin de la chine.
Exemple : txt = "     Banana"
            x = txt.strip()
            print("Of all fruits ", x," is my favorite")
Résultat : Of all fruits banana is my favorite.
