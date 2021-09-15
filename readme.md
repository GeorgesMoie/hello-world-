# hello-world-
Getting started with Github

Il s'agit de prendre en main le fonctionnement de Github.

Qu'est-ce que GitHub ?
GitHub est une plate-forme d'hébergement de code pour le contrôle de version et la collaboration. Il vous permet, à vous et à d'autres, de travailler ensemble sur des projets de n'importe où.

Ce didacticiel vous apprend les éléments essentiels de GitHub tels que les référentiels , les branches , les commits et les Pull Requests . Vous allez créer votre propre référentiel Hello World et apprendre le flux de travail Pull Request de GitHub, un moyen populaire de créer et de réviser du code.

Aucun codage nécessaire
Pour terminer ce didacticiel, vous avez besoin d'un compte GitHub.com et d'un accès Internet. Vous n'avez pas besoin de savoir coder, utiliser la ligne de commande ou installer Git (le logiciel de contrôle de version GitHub est basé sur



Étape 1. Créer un référentiel
Un référentiel est généralement utilisé pour organiser un seul projet. Les référentiels peuvent contenir des dossiers et des fichiers, des images, des vidéos, des feuilles de calcul et des ensembles de données – tout ce dont votre projet a besoin. Nous vous recommandons d'inclure un fichier README ou un fichier contenant des informations sur votre projet. GitHub permet d'en ajouter un en même temps que vous créez votre nouveau référentiel. Il offre également d'autres options courantes telles qu'un fichier de licence.

Votre hello-worldréférentiel peut être un endroit où vous stockez des idées, des ressources, ou même partagez et discutez des choses avec d'autres.

Pour créer un nouveau référentiel
Dans le coin supérieur droit, à côté de votre avatar ou de votre icône d'identité, cliquez sur puis sélhectionnez Nouveau référentiel
Nommez votre référentiel hello-world.
Écrivez une courte description.
Sélectionnez Initialiser ce référentiel avec un fichier README .



Étape 2. Créer une succursale
Le branchement est le moyen de travailler sur différentes versions d'un référentiel en même temps.

Par défaut, votre référentiel a une branche nommée mainqui est considérée comme la branche définitive. Nous utilisons des branches pour expérimenter et apporter des modifications avant de les valider main.

Lorsque vous créez une branche à partir de la mainbranche, vous faites une copie, ou un instantané, de maince qu'elle était à ce moment-là. Si quelqu'un d'autre a apporté des modifications à la mainbranche pendant que vous travailliez sur votre branche, vous pouvez récupérer ces mises à jour.

Ce schéma montre :

La mainbranche
Une nouvelle branche appelée feature(parce que nous effectuons un "travail de fonctionnalité" sur cette branche)
Le voyage qui featureprend avant qu'il ne se fonde dansmain
une branche

Avez-vous déjà enregistré différentes versions d'un fichier ? Quelque chose comme:

story.txt
story-joe-edit.txt
story-joe-edit-reviewed.txt
Les branches accomplissent des objectifs similaires dans les référentiels GitHub.

Chez GitHub, nos développeurs, rédacteurs et concepteurs utilisent des branches pour séparer les corrections de bogues et le travail des fonctionnalités de notre mainbranche (de production). Lorsqu'un changement est prêt, ils fusionnent leur branche dans main.

Pour créer une nouvelle branche
Accédez à votre nouveau référentiel hello-world.
Cliquez sur le menu déroulant en haut de la liste des fichiers qui dit branch: main .
Tapez un nom de branche, readme-edits, dans la zone de texte de la nouvelle branche.
Sélectionnez la case bleue Créer une branche ou appuyez sur "Entrée" sur votre clavier.
branche gif

Vous avez maintenant deux branches, mainet readme-edits. Ils se ressemblent exactement, mais pas pour longtemps ! Ensuite, nous ajouterons nos modifications à la nouvelle branche.


Étape 3. Apportez et validez les modifications
Bravo! Maintenant, vous êtes sur la vue du code de votre readme-editsbranche, qui est une copie de main. Faisons quelques modifications.

Sur GitHub, les modifications enregistrées sont appelées commits . Chaque commit est associé à un message de commit , qui est une description expliquant pourquoi une modification particulière a été apportée. Les messages de validation capturent l'historique de vos modifications, afin que les autres contributeurs puissent comprendre ce que vous avez fait et pourquoi.

Effectuer et valider des modifications
Cliquez sur le README.mdfichier.
Clique le  icône de crayon dans le coin supérieur droit de la vue du fichier à modifier.
Dans l'éditeur, écrivez un peu sur vous-même.
Écrivez un message de validation qui décrit vos modifications.
Cliquez sur le bouton Valider les modifications .
s'engager

Ces modifications seront apportées uniquement au fichier README sur votre readme-editsbranche, donc maintenant cette branche contient un contenu différent de main.



Étape 4. Ouvrir une demande de tirage
Belles retouches ! Maintenant que vous avez des changements dans une branche de main, vous pouvez ouvrir une pull request .

Les Pull Requests sont au cœur de la collaboration sur GitHub. Lorsque vous ouvrez une pull request , vous proposez vos modifications et demandez à quelqu'un de réviser et d'extraire votre contribution et de les fusionner dans sa branche. Les demandes d' extraction affichent les différences , ou les différences, du contenu des deux branches. Les modifications, ajouts et soustractions sont affichés en vert et en rouge.

Dès que vous effectuez un commit, vous pouvez ouvrir une pull request et démarrer une discussion, avant même que le code ne soit terminé.

En utilisant le système @mention de GitHub dans votre message de demande d'extraction, vous pouvez demander les commentaires de personnes ou d'équipes spécifiques, qu'elles soient au bout du couloir ou à 10 fuseaux horaires.

Vous pouvez même ouvrir des pull request dans votre propre référentiel et les fusionner vous-même. C'est un excellent moyen d'apprendre le flux GitHub avant de travailler sur des projets plus importants.

Ouvrir une demande d'extraction pour les modifications apportées au fichier README
