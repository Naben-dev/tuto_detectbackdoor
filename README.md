# tuto_detectbackdoor

Ce script est un tutoriel pour les débutants pour pouvoir détecter les scripts infectés d'une backdoor.
Il a été entièrement fait par moi le 18/04 et je le poste ici car certains serveurs me l'ont volés :
https://cdn.discordapp.com/attachments/713154244839997440/996458079673663618/Capture_decran_2022-07-12_184814.jpg

*Une backdoor est un code malveillant qui est parfoit cachés dans certains de vos scripts dans le but de vous infecter.*

---------------

__**Première étape : Cibler la proie**__
Tout simplement si vous voyez une personne qui commence à forcer pour partager son script genre une personne qui envoi un "debug d'un script" gratuitement dans un salon sans que personne ne lui ai rien demandé, ou bien une personne qui force pour partager son script dans avec tout le monde.

**Deuxième étape : Analyser le script**
Maintenant que vous avez repéré le script qui pose problème téléchargez le sur votre pc et allez analyser les fichiers serveur du script (les backdoors sont preque tout le temps dans les fichiers serveurs car elles ne peuvent presque rien faire côté client), n'oubliez pas d'aller vérifier dans le fxmanifest qu'il n'est pas fait un fichier serveur qu'il a fait passer pour un fichier client.+

**Troisième étape : Analyser le côté serveur**
Maintenant que vous avez trouvé les fichiers serveurs c'est parti pour vérifier si ils contiennent une backdoor.
Tout simplement analysez la totalité du code en essayant de comprendre à quoi il sert, une backdoor peut se retrouver par une partie du code qui est crypté (voir exemple de code crypté en photo ci-joint) et une backdoor contient souvent un "PerformHttpRequest" ou bien un "load" si vous voyez cela dans un script il est évident ou presque que c'est une backdoor.
(sans comptez les gens ou il y a ouvertement écrit cipher ou je ne sais quoi dans leur code).

*PS : n'oubliez pas de faire glisser le barre de slide il arrive que les gens cachent les backdoors à l'autre bout du script ou bien tout en bas de la page.*

**Image de backdoor : https://cdn.discordapp.com/attachments/713154244839997440/965741271404662794/unknown.png**
