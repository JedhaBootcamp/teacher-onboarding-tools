# Essentials teacher's onboarding

Ce repository contient toutes les informations concernant la session que tu vas encadrer.

# French

# Pour la première journée

## 1. First thing first

La première des choses à faire est d'envoyer un message de présentation sur le channel Slack de ta session. Si tu n'y a pas accès tu peux envoyer un mail au PM du campus (le contact qui t'a envoyé le mail dans lequel se trouvait le lien de ce Github Page). 

Voici un modèle de message :

```
Hello @canal,
Je suis `X`, travaillant en tant que `X` chez `X` et je suis très heureux de vous avoir en tant que professeur pour votre formation Data Essentials !
Afin de bien démarrer votre premier jour, vous pouvez d'ores et déjà :
* Installer Tableau sur votre poste via ce lien - https://public.tableau.com
* Vérifiez que vous ayiez bien accès à JULIE (https://app.julie.academy/) aussi, qui est notre plateforme sur laquelle vous aurez tout vos contenus de cours.
Aussi pour ceux qui viennent en présentiel, l'adresse de la formation est le : 13 Rue du Pont aux Choux 75003, Paris.
Code d'accès : 32A16 puis fond de cour à gauche.

Des membres de l'équipe Jedha seront là pour vous accueillir :)
```

# 2. ZOOM

## Explications et téléchargement

Étant donné le fait que les élèves sont en présentiel et distanciel, les cours se déroulent sur <a href="https://zoom.us/">ZOOM</a>. Si tu ne l'as pas téléchargé je t'invite à le faire <a href="https://zoom.us/download">ICI</a>.

## Lancement du ZOOM

Une fois téléchargé il faudra le lancer sur Slack. Pour ce faire il faudra aller sur le channel de la session que tu enseignes et faire la commande suivante : 

`/zoom meeting NomDeSession_M0x_D0x_NomDeLaJournée`

Pour exemple je prendrai la première journée que l'on enseigne sur la ds-paris-00 : `/zoom meeting ds-paris-00_M01_D01_Data-Visualisation`

**ATTENTION**
La première fois que tu feras la commande `/zoom meeting` tu devras autoriser ZOOM à accéder à Slack.

## Record

Une fois que le ZOOM est lancé, il faut lancer le record, voir le GIF ci-dessous :


![record zoom cloud](https://essentials-teacher-onboarding.s3.eu-west-3.amazonaws.com/record_zoom_cloud.gif)
<img src="https://essentials-teacher-onboarding.s3.eu-west-3.amazonaws.com/record_zoom_cloud.gif"/>

## Icebreaking

Le principe est simple, nous allons faire un jeu en introduction afin de "briser la glace" (pas de panique tu seras encadré par quelqu'un de l'équipe afin que cela se déroulé au mieux). Le jeu est 2 vérités, et 1 mensonge. Pour ce faire voici un template de message, à copier-coller sur Slack, qui permettra aux étudiants de voter sur Slack :

```
### {FIRSTNAME} ###
1. :rocket: 
2. :feu:
3. :brain:
```

Un exemple :

```
### Richard ###
1. :rocket: A réussit son permis du premier coup
2. :feu: Habite à Paris
3. :brain: A fait l'armée
```

Tu l'auras compris, les élèves doivent donc trouver la réponse fausse, dans ce cas la 1.

Le but est de délier les langues et faire preuve de créativité. Cela permet d'avoir une session soudée dès le début.

# 3. Explication des outils et du bootcamp

À la suite de l'icebreaking, l'encadrant pédagogique de Jedha va dérouler quelques slides afin d'expliquer les outils ainsi que le déroulement général du bootcamp. Cela te permettra de ne pas être dérangé durant ton cours si un élève n'a pas accès la ressource

## Feuille de présence
Tu as dû recevoir tes credentials via un mail d'Edusign. Cela permet d'envoyer les feuilles de présence. Voici un exemple de comment faire pour les envoyer.

Dans un premier temps rendez-vous sur <a href="https://edusign.app/">EduSign</a> puis tu pourras suivre ce GIF :

<img src="https://essentials-teacher-onboarding.s3.eu-west-3.amazonaws.com/edusign_send_attendance.gif"/>

## <a href="https://github.com/JedhaBootcamp/ESSENTIALS_PROGRAM">Github</a>

Tu pourras retrouver toutes les ressources de cours sur Github. Slides, note de cours, note de professeurs, solutions des exercices, cours, etc...

La structuration est la suivante :

<img src="https://essentials-teacher-onboarding.s3.eu-west-3.amazonaws.com/architecture_repo_github.png"/>


Comme indiqué dans l'architecture ci-dessus, le dossier le plus important est celui nommé **03-Instructors** car il contient beaucoup d'éléments qui te seront très importants pour un bon enseignement.

1. Les slides : Qui te seront utiles afin de présenter les concepts que tu vas enseigner.
2. Les notes de cours : Elles te permettront de pouvoir mettre un timing sur les cours données.
3. Slack Message : Ce message est à envoyé à chaque fin de journée d'enseignement.

## <a href="https://app.julie.academy/">JULIE</a>

### Connexion & Cours

C'est la plateforme d'apprentissage que les élèves utiliseront durant toute leur formation.

Voici la procédure pour avoir ton mot de passe si tu ne t'es jamais connecté à la plateforme :

1. Aller sur le site <a href="http://app.julie.academy/">JULIE</a>
2. Clique sur _Forget your password?_
3. Suivre la procédure de réinitialisation reçue par mail
4. Se connecter avec le mot de passe crée

Une fois connecté sur JULIE, tu peux retrouver les cours via ce chemin _Courses > Data Dregrees > Essentials_. Tu remarqueras que l'architecture qu'il y a présente dans la section <ins>Github</ins> est la même dans JULIE sans le dossier _03-Instructors_

### Workspace

Oui JULIE possède un workspace intégré. C'est sur ce jupyter lab que tu feras pratiquer les élèves sur la partie Python et Machine Learning (module 3 et 4).

Pour lancer une machine voici des GIFs explicatifs :

Lancement de la machine :

<img src="https://essentials-teacher-onboarding.s3.eu-west-3.amazonaws.com/workspace_1.gif"/>

Utilisation de la machine créée :

<img src="https://essentials-teacher-onboarding.s3.eu-west-3.amazonaws.com/workspace_2.gif"/>

**Important** les workspaces sont tout le temps sauvegardé. C'est important de le préciser aux élèves pour ne pas qu'ils craignent de perdre quoi que ce soit. **Si jamais** on venait à cleaner des machines ou des données, les personnes concernées seraient prévenues 1 semaine à l'avance afin de tout télécharger en local.

## Google Drive

Cela permettra aux élèves de récupérer les solutions. Comme tu as pu le voir, les élèves n'ont en aucuns cas accès au dossier _03-Instructors_, c'est pourquoi c'est à toi de partager les solutions dans leur Drive. Tu as reçu le lien dans le mail.

Comment est structuré le drive? Restons sur l'exemple de la ds-paris-00 :

<img src="https://essentials-teacher-onboarding.s3.eu-west-3.amazonaws.com/architecture_google_drive.png"/>


Les solutions devront être déposées dans le Drive en fin de journée afin que les élèves puissent y avoir accès.

## Slack

Notre messagerie instantanée sur laquelle tu partageras tout avec les élèves (lien zoom, synthèse des cours, jokes...)

Tu devrais avoir accès au channel de la session sur laquelle tu enseigne `#ds-{campus}-{session_number}`

## Google Cloud Platform

SQL

# Déroulement d'une journée type

1. 9:55 : Dire bonjour sur Slack
2. 10:00 : Lancer le ZOOM avec la commande `/zoom meeting NomDeSession_M0x_D0x_NomDeLaJournée` dans le channel Slack
3. 10:00 : Lancer le record sur le Cloud ZOOM
4. 10:05 : Envoyer les feuilles de présence
5. 10:05 Pendant une 15aine de minutes, demander aux élèves comment s'est passé le cours dernier, voir si ils n'ont pas de questions sur l'exercice de la veille. 
6. 10:20 : Débuter le cours du jour.
7. 12:30 : Pause du midi
8. 13:30 : Reprise des cours / début des exercices
9. 18:00 : Envoie de la synthèse du jour
10. 18:30 : Dépôt des solutions dans le Google Drive


