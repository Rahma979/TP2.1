# TP2.1

# Réponses aux questions demandés:

Question 1:

Quelles modifications sont apportées lorsque vous ajoutez une deuxième activité à votre application en choisissant File > New > Activity et un modèle d'activité? Choisissez-en un:
La deuxième activité est ajoutée en tant que classe Java. Vous devez toujours ajouter le fichier de mise en page (layout) XML.
Le deuxième fichier de mise en page XML d'activité est créé et une classe Java ajoutée. Vous devez toujours définir la signature de la classe.
La deuxième activité est ajoutée en tant que classe Java, le fichier de présentation (layout) XML est créé et le fichier AndroidManifest.xml est modifié pour déclarer une deuxième activité.
Le deuxième fichier de présentation (layout) XML d'activité est créé et le fichier AndroidManifest.xml est modifié pour déclarer une deuxième activité.

Rép:     La deuxième activité est ajoutée en tant que classe Java, le fichier de présentation (layout) XML est créé
     et le fichier AndroidManifest.xml est modifié pour déclarer une deuxième activité.
    
Question 2:

Que se passe-t-il si vous supprimez les éléments android:parentActivityName et <méta-data> de la deuxième déclaration d'activité du fichier AndroidManifest.xml? Choisissez-en un:
La deuxième activité n'apparaît plus lorsque vous essayez de la démarrer avec une intention (Intent) explicite.
Le deuxième fichier de mise en page (layout) XML d'activité est supprimé.
Le bouton Back (Précédent) ne fonctionne plus dans la deuxième activité pour renvoyer l'utilisateur à l'activité principale.
Le bouton Up (Haut) de la barre d'applications n'apparaît plus dans la deuxième activité pour renvoyer l'utilisateur à l'activité parent.

Rép:  La deuxième activité n'apparaît plus lorsque vous essayez de
      La démarrer avec une intention (Intent) explicite.

Question 3:

Quelle méthode de constructeur utilisez-vous pour créer une nouvelle intention (Intent) explicite? Choisissez-en un:
new Intent()
new Intent(Context context, Class<?> class)
new Intent(String action, Uri uri)
new Intent(String action)

Rép:    new Intent(Context context, Class<?> class)
           
Question 4:

Dans l'application HelloToast (du Travail à faire), comment ajoutez-vous la valeur actuelle du comptage à l'intention (Intent)? Choisissez-en un:
Comme les données d'intention (Intent)
Comme TEXT_REQUEST de l'intention (Intent)
En tant qu'action d'intention (Intent)
Comme extra d'intention (Intent)

Rép: extra d'intention (Intent)

Question 5:

Dans l'application HelloToast (du Travail à faire), comment afficher le nombre actuel dans la deuxième activité "Hello"? Choisissez-en un:
*Obtenez l'intention (Intent) avec laquelle l'activité a été lancée.
*Obtenez la valeur actuelle du comptage de l'intention.
*Mettez à jour le TextView pour le comptage.
*Tout ce qui précède.

 Rép:       Tout ce qui précède.
