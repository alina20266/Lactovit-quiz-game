[README.md](https://github.com/user-attachments/files/33339140/README.md)
# Quiz Lactourea · Marathon International de Casablanca 2026

Borne tactile du stand Lactovit au village du Marathon International de Casablanca, du 21 au 25 octobre 2026. Les visiteurs répondent à un quiz de 6 questions sur la gamme Lactourea Réparateur et sa routine, gagnent un cadeau immédiat selon leur score, et peuvent entrer dans le classement du jour.

**Lien de la borne :** https://alina20266.github.io/Lactovit-quiz-game/

## Contenu du dépôt

| Fichier | Rôle |
| --- | --- |
| `index.html` | L'application complète, en un seul fichier : textes, questions, polices et visuels intégrés. |
| `README.md` | Ce mode d'emploi. |

Aucune installation n'est nécessaire. Une fois la page chargée, le jeu fonctionne même si la connexion internet coupe, tant que la page n'est pas rechargée.

## Installer la borne

1. Ouvrir le lien ci-dessus dans **Chrome** ou **Edge**, en navigation normale (pas en navigation privée, sinon les scores ne sont pas conservés).
2. Passer en plein écran avec **F11**.
3. L'écran est conçu pour une borne **portrait 1080 x 1920**. Sur un autre écran, l'affichage s'adapte avec des bandes sur les côtés.
4. Sans action pendant 60 secondes, la borne revient seule à l'écran de veille.

## Déroulé d'une partie

- **6 questions** par partie, une par thème : votre peau, le secret Lactourea, la Lotion Réparatrice, la Crème Mousse, la routine rouge, après la course. Les questions sont tirées au sort et l'ordre des réponses change à chaque partie.
- **Points :** 500 par bonne réponse, plus un bonus de rapidité jusqu'à 500 points. 25 secondes par question.
- **Cadeaux immédiats :**

| Bonnes réponses | Cadeau |
| --- | --- |
| 4 sur 6 | Fleur de douche |
| 5 sur 6 | Trousse |
| 6 sur 6 | Sac Lactourea rouge |

  Un seul cadeau immédiat par numéro de téléphone et par jour. L'écran de résultat affiche le cadeau gagné : le visiteur le montre à l'équipe.
- **Classement du jour :** les visiteurs qui s'inscrivent (prénom, téléphone et consentement) entrent dans le classement. Les **5 meilleurs scores de chaque journée** gagnent un coffret de la gamme complète Lactovit. Seule la première participation du jour de chaque numéro compte. On peut aussi jouer sans inscription : le cadeau immédiat reste possible, hors classement.
- **Découvrir :** espace pédagogique accessible sans jouer (trouvez votre soin, le secret Lactourea, la Crème Mousse, la routine rouge, les déodorants, la sueur décodée, les conseils du coureur, où trouver Lactovit).

## Espace équipe

- **Accès :** toucher 5 fois rapidement le coin supérieur droit de l'écran de veille, puis saisir le code équipe (communiqué en interne).
- **On y trouve :** les gagnants du jour avec leur téléphone, le classement complet, le nombre de parties et de cadeaux par palier, le taux de réussite de chaque question, l'export CSV et la suppression des données.
- **Chaque soir :** exporter le CSV et contacter les 5 gagnants du jour.
- **En fin d'opération :** exporter une dernière fois, puis « Effacer toutes les données ».

## Données personnelles

- Les prénoms, numéros et scores sont enregistrés **uniquement dans le navigateur de la borne**. Ils ne sont envoyés à aucun serveur et ne sont jamais stockés sur GitHub.
- Changer de navigateur, d'ordinateur ou d'adresse de page crée un classement séparé. Garder la même borne et le même lien pendant tout l'événement.
- Recharger la page ne supprime pas les scores. Vider les données du navigateur les supprime.

## Mettre à jour le quiz

1. Renommer la nouvelle version en `index.html`.
2. Dans ce dépôt : **Add file → Upload files**, déposer le fichier, puis **Commit changes**. L'ancien fichier est remplacé.
3. Attendre jusqu'à 10 minutes, puis recharger la page sur la borne. Les scores déjà enregistrés sont conservés.

Les réglages (paliers de cadeaux, nombre de gagnants, temps par question, délai d'inactivité, code équipe, textes du règlement) sont regroupés dans le bloc `CONFIG`, au début du script de `index.html`. Les modifier sur une copie locale, tester en ouvrant le fichier dans Chrome, puis le téléverser.

## Mentions

Projet réalisé par Alina Distribution pour Lactovit Maroc. Les marques Lactovit et Lactourea, les logos et les visuels produits appartiennent à leurs titulaires et ne sont pas sous licence libre. Usage réservé à l'animation du stand.
