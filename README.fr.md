# README.md
- [Deutsch](README.de.md)
- [English](README.md)
- [Spanish](README.es.md)
- [French](README.fr.md)
- [Italian](README.it.md)
- [언어](README.ko.md)
- [日本語](README.ja.md)
- [简体中文](README.zh_cn.md)
- [繁体中文](README.zh_tw.md)

# 🎠 Motrix - Client macOS natif pour chatGPT

Téléchargez [la dernière version depuis l'appstore macOS](https://apps.apple.com/us/app/id6447776319)

## Fonctionnalités principales
- Prise en charge du proxy LLM local litellm
- Vous devez avoir une clé d'API GPT pour exécuter l'application Motrix
- Connexion au service chatGPT API ou au service proxy GPT (Hôte personnalisé)
- Prise en charge du chat de groupe
- Retentative automatique
- Sélecteur rapide de modèle de prompt
- Les nœuds de chat peuvent être organisés comme un arbre (Glisser-déposer)
- Commutateur rapide d'ouverture globale vers le chat
- Les nœuds de chat personnalisés s'affichent dans la barre de menu
- Affichage des conversations en Markdown
- Enregistrer les chats favoris et les consulter ultérieurement
- Icône visible de l'IA indiquant le nombre de messages contextuels que l'IA peut lire
- Rechercher des conversations par mots-clés
- Intégration de 6 thèmes avec prise en charge de la lumière/sombre

V1.9.2
---
- Ajout d'une fonctionnalité de sauvegarde et de restauration de toutes les données dans les préférences.
- Ajout d'une fonctionnalité de duplication de messages vers un autre nœud de chat.
- Ajout du mode de chat de mémo pour simplement enregistrer quelque chose et ne pas envoyer au serveur de l'IA.
- Ajout d'un message temporaire envoyé en tant que message de chat de groupe en démarrant une nouvelle discussion avec le format "@node1;node2;node5 newline texte de traduction".
- Ajout d'un chat de groupe temporaire rapide depuis le menu contextuel de l'arbre de gauche.
- Ajout de la fonctionnalité de verrouillage du contexte à une ligne, permettant à la conversation d'être toujours envoyée à partir de la ligne de contexte verrouillée.
- Ajout d'un double clic pour éditer la fenêtre contextuelle de minuterie de discussion pour passer en mode éditeur.
- Ajout d'options de thread de chat de groupe parallèle dans la barre de défilement, cela permet de réduire les demandes parallèles à l'API en raison de problèmes de réponse du serveur.
- Ajout d'options d'édition de minuterie directement dans la fenêtre de discussion contextuelle.
- Ajout d'un raccourci pour ouvrir n'importe quel nœud de chat avec une fenêtre flottante.
- Correction du style du thème de la fenêtre rapide ne correspondant pas.
- Correction du mode flux ne pouvant pas lire les données provenant du projet open source litellm en mode proxy.
- [V1.9.2-Uni](https://download.marksdo.com/apps/Motrix/V1.9.2/Motrix.dmg)

V1.9.1
---
- Ajout de la possibilité de double-cliquer pour modifier la fenêtre contextuelle de la minuterie en mode éditeur.
- Ajout d'options d'édition de minuterie directement dans la fenêtre de discussion contextuelle.
- Ajout d'un raccourci pour ouvrir n'importe quel nœud de chat avec une fenêtre flottante.
- Correction du style du thème de la fenêtre rapide ne correspondant pas.
- Correction du mode flux ne pouvant pas lire les données provenant du projet open source litellm en mode proxy.
- [V1.9.1-Uni](https://download.marksdo.com/apps/Motrix/V1.9.1/Motrix.zip)

V1.9.0
---
- Ajout de la prise en charge du proxy llm/gpt local (litellm) http://127.0.0.1:8000 en tant qu'hôte pour prendre en charge la plupart des serveurs de chat llm/gpt open source.
- Ajout de la fonctionnalité de clonage de nœud d'arbre de discussion dans le menu contextuel droit.
- Ajout de la fonctionnalité de configuration par lots des paramètres de modèle des nœuds (sélectionnez plusieurs nœuds dans l'arbre, puis utilisez le menu contextuel -> configuration par lots).
- Correction du problème de non-fermeture de la description des instructions système.
- [73.6 MB](https://download.marksdo.com/apps/Motrix/V1.9.0/Motrix.zip)  
![image](/images/V190.webp)

V1.8.9
---
- Ajout d'un raccourci pour passer au nœud de chat suivant dans l'arbre (à utiliser avec d'autres applications de raccourcis en lot du système).
- Ajout d'une capture d'écran dans le menu contextuel droit du contenu du chat.
- La fenêtre contextuelle du résultat de la requête AI programmée peut être enregistrée en tant qu'image complète dans le presse-papiers.
- La barre d'outils de la ligne de contenu du chat a été supprimée. Utilisez le menu contextuel droit comme remplacement.
- Correction du problème de disposition lors du partage en lot du contenu du chat vers une image.
- Correction du plantage au démarrage de macOS 11.
- Télécharger l'édition universelle [73.5 MB](https://download.marksdo.com/apps/Motrix/V1.8.9/Motrix.zip)

V1.8.7
---
- Ajout de la configuration de la clé du modèle. Vous pouvez configurer la clé du modèle lorsque de nouveaux modèles sont publiés.
- Ajout de la fonctionnalité de suppression en lot des lignes de chat sélectionnées.
- Ajout d'une option pour désactiver le défilement automatique vers le bas de la liste de chat.
- Ajout de la configuration d'apparence pour changer la taille de la police de l'interface utilisateur.
- Ajout des touches ⌘+(+-) pour changer rapidement la taille du contenu du chat.
- Ajout d'une option de hauteur fixe de la boîte de saisie dans le curseur des options.
- La taille de la barre de navigation de gauche peut être de plus petite taille.
- Le nouveau nœud de chat utilisera les derniers paramètres de l'IA du nœud de chat sélectionné précédemment.
- Correction de la fenêtre contextuelle de question IA personnalisée qui peut toujours apparaître lorsque le système est en veille.
- Correction de l'impossibilité de basculer l'option de rendu Markdown dans les paramètres.
- Correction du problème d'intention des raccourcis de l'application Motrix.

V1.8.5
---
- Ajout de la prise en charge des modèles GPT3.5 & GPT4 16K.
- Ajout de la prise en charge de la largeur par défaut de la fenêtre contextuelle de minuterie (utilisée pour les conseils quotidiens d'IA avec des réponses longues).
- Correction du problème d'affichage en mode flux dans certains cas.
- Correction des bugs d'affichage de la fenêtre de minuterie contextuelle réduite.

V1.8.4
---
- Ajout d'une nouvelle page de guide de chat. Vous pouvez sélectionner un rôle IA prédéfini pour commencer la discussion.
- Correction de bugs et améliorations des performances.

V1.8.3
---
- Ajout d'une vue en grille dans le sélecteur de nœuds de service rapide de Motrix.
- Ajout d'une option pour activer/désactiver les messages non lus dans le nœud de l'arborescence de gauche.
- Ajout d'une option pour désactiver le défilement automatique en cours de saisie.
- Correction de l'incapacité à revenir à l'avant en cliquant sur l'icône de l'application dans la barre de dock.
- Correction de certains problèmes de traduction en plusieurs langues.
- Correction du problème de crash du mode de synthèse vocale.

V1.8.2
---
- Ajout de la prise en charge de l'application Raccourcis (macOS 13.0+). Interrogez la réponse de l'IA puis intégrez-la à votre propre flux de travail automatique. Vous pouvez voir comment l'utiliser dans les préférences de l'application.
- Le service rapide de Motrix peut désormais sélectionner une fenêtre miniature pour afficher le contenu de la réponse de l'IA.
- Correction du problème d'affichage du service Motrix dans le navigateur ou dans une autre application de texte.

V1.8.1
---
- Correction du problème occasionnel où la recherche globale ne pouvait pas lister les données.
- Correction de la limitation de certaines fonctionnalités pour les plans Pro.
- Correction du problème de hauteur du corps du message qui ne convient pas.

V1.8
---
- Ajout d'une minuterie quotidienne pour interroger automatiquement le nœud de chat de l'IA et afficher des conseils inspirants ou motivants. Vous pouvez également l'utiliser pour afficher quotidiennement des astuces de codage, des exercices de langue. (Double-cliquez sur la ligne de question de l'utilisateur)
- Ajout d'une minuterie quotidienne qui peut être directement invoquée depuis le menu contextuel de la barre de menus de Motrix.
- Ajout du raccourci global CMD+SHIFT+F pour basculer rapidement vers les favoris de recherche globale.
- Correction de problèmes de défilement.
- Correction du problème occasionnel où le sélecteur rapide de modèle ne peut pas insérer de texte.
- Amélioration des performances en mode flux.

Fonctionnalités de V1.7
---
- Ajout du mode de fenêtre flottante, vous pouvez faire d'une fenêtre de chat un petit panneau flottant.
- Possibilité de faire glisser du texte vers n'importe quelle zone de la fenêtre de chat pour envoyer un message.
- Ajout d'un interrupteur d'affichage de la disposition dans la barre d'outils principale et prise en charge de l'icône de restauration personnalisée.
- Ajout du service rapide de Motrix, lorsque vous sélectionnez un texte dans une autre application d'édition, sélectionnez "Motrix quick" pour afficher un sélecteur de nœuds de chat et envoyer le texte sélectionné au système de chat.
- Ajout d'un menu contextuel avec le clic droit sur le message pour copier rapidement, ajouter aux favoris et modifier.
- Correction du problème de stabilité de la vue déroulante.
- Correction du bogue de saut de ligne en Markdown.

Fonctionnalités de V1.5 à 1.6
---
- Ajout du mode de flux pour obtenir les jetons de réponse un par un.
- Possibilité de modifier le message intégré en double-cliquant sur la ligne du message.
- Ajout de la configuration d'apparence dans les paramètres pour une personnalisation de l'interface utilisateur.
- Ajout de 3 nouveaux thèmes avec prise en charge de la lumière et du sombre.
- Ajout de la fonctionnalité de sauvegarde et de restauration de la disposition (y compris le thème actuel, le mode clair sombre, la taille de la police, les options automatiques, etc.).
- Ajout de l'animation de saisie.
- Ajout du service de texte du système d'exploitation, appel de l'API de Motrix dans tous les autres éditeurs de texte du système.
- Correction & Test de la compatibilité de Mortix avec les appareils macOS 11.0, 12.0.
- Correction de bugs et améliorations des performances.

Fonctionnalités de V1.4
---
- Prise en charge de la recherche dans toutes les conversations.
- Prise en charge du mode de sélection en lot. Sélectionnez les messages de chat à partager ou à exporter.
- Prise en charge de l'affichage des favoris dans toutes les conversations (dans le menu de recherche).
- Personnalisation du nombre maximal de tokens pour chaque nœud (vous devez comprendre comment ils fonctionnent, comme le message contextuel, cela peut affecter la compréhension de l'IA de la quantité de contexte).
- Mode d'entrée par défaut du nœud personnalisé
- Correction de bugs et améliorations des performances.

Fonctionnalités de V1.1 à V1.3
---
- Mode de dictée : vous pouvez utiliser le microphone pour enregistrer du texte. L'application le traduira en texte et conservera la piste audio.
- Lecture de contenu vocal : un simple clic sur l'avatar de l'utilisateur ou du bot.
- Mode de discussion de groupe : vous pouvez définir un nœud parent et ajouter certains nœuds enfants (vous devez utiliser les instructions système pour initialiser le rôle de l'IA et son rôle), puis envoyer un message dans le nœud parent. Tous les enfants donneront une réponse dans la conversation actuelle.
- Presse-papiers automatique : copie automatiquement le contenu dans le presse-papiers lorsqu'il y a une réponse.
- Mode de parole automatique : énonciation automatique de la réponse.
- Masquage automatique : masque automatiquement la réponse de l'IA. Cela concerne principalement les utilisateurs qui souhaitent pratiquer la dictée dans différentes langues.

Fonctionnalités de V1.0
---
- Intégration d'un éditeur de Markdown.
- Groupez librement les nœuds de discussion avec un style d'arborescence (prise en charge du glisser-déposer).
- 3 thèmes avec prise en charge des couleurs claires/sombres.
- Rendu des blocs de code coloré.
- Enregistrez toute conversation pour une révision ou une requête ultérieure.
- Les conversations sont enregistrées localement, elles peuvent donc être consultées hors ligne ultérieurement.
- Modèle de prompt personnalisé et sélecteur rapide avec "/".

Captures d'écran

![capture d'écran](images/screenshot.webp)

![capture d'écran1](images/screenshot1.webp)

![capture d'écran2](images/screenshot2.webp)

![capture d'écran3](images/screenshot3.webp)

![capture d'écran4](images/screenshot4.webp)

![capture d'écran5](images/screenshot5.webp)

![capture d'écran6](images/screenshot6.webp)

![capture d'écran7](images/screenshot7.webp)

![capture d'écran8](images/screenshot8.webp)

![capture d'écran9](images/screenshot9.webp)

![capture d'écran10](images/screenshot10.webp)

![capture d'écran11](images/screenshot11.webp)