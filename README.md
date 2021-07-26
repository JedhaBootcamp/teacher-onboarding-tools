
- [Onboarding pour professeur Essentials](#onboarding-pour-professeur-essentials)
- [ZOOM](#zoom)
     - [Explications et téléchargement](#explications-et-telechargement)
     - [Lancement du ZOOM](#lancement-du-zoom)
     - [Record](#record)
     - [Création de breakout rooms](#création-de-breakout-rooms)
- [Icebreaking](#icebreaking)
- [Explications des outils principaux du bootcamp](#explications-des-outils-du-bootcamp)
     - [Feuille de présence](#feuille-de-présence)
     - [Github](#github)
         -[Repo en fonction de la formation enseignée](#repo-en-fonction-de-la-formation-enseignée)
     - [JULIE](#julie)
         - [Connexion & cours](#connexion-et-cours)
         - [Workspace](#workspace)
     - [Google Drive](#google-drive)
     - [Slack](#slack)
- [Journée type](#journée-type)
- [Plus d'outils](#plus-d-outils)
     - [Tableau](#tableau)
     - [Google Cloud Platform](#google-cloud-platform) 
- [Pour la première journée](#pour-la-première-journée)
- [Les notes de cours professeurs par journée d'enseignement](#les-notes-de-cours-professeurs-par-journée-d-enseignement)
     - [M01.D01-Data Visualisation](#data-visualisation)
     - [M02.D01-Introduction to SQL and cloud computing](#introduction-to-sql-and-cloud-computing)
     - [M02.D02-Advanced SQL](#advanced-sql)
     - [M03.D01-Introduction to python and statistics](#introduction-to-python-and-statistics)
     - [M03.D02-AB Testing and web analytics](#ab-testing-and-web-analytics)
     - [M04.D01-Machine Learning Regressions](#machine-learning-regressions)
     - [M04.D02-Machine Learning Classifications](#machine-learning-classifications)
     - [M05.D01-Project](#project)

# Onboarding pour professeur Essentials

Ce repository contient toutes les informations concernant la session que tu vas encadrer.

# ZOOM

## Explications et téléchargement

Étant donné le fait que les élèves sont en présentiel et distanciel, les cours se déroulent sur <a href="https://zoom.us/">ZOOM</a>. Si tu ne l'as pas téléchargé je t'invite à le faire <a href="https://zoom.us/download">ICI</a>.

## Lancement du ZOOM

Une fois téléchargé il faudra le lancer sur Slack. Pour ce faire il faudra aller sur le channel de la session que tu enseignes et faire la commande suivante : 

`/zoom meeting NomDeSession_M0x_D0x_NomDeLaJournée`

Pour exemple je prendrai la première journée que l'on enseigne sur la ds-paris-00 : `/zoom meeting ds-paris-00_M01_D01_Data-Visualisation`

**ATTENTION**
La première fois que tu feras la commande `/zoom meeting` tu devras <ins>autoriser ZOOM à accéder à Slack</ins>.

## Record

Une fois que le ZOOM est lancé, il faut lancer le record, voir le GIF ci-dessous :


![record zoom to the cloud](https://essentials-teacher-onboarding.s3.eu-west-3.amazonaws.com/record_zoom_cloud.gif)


## Création de breakout rooms

Pour la partie exercice, il est important de créer des salles de travail. C'est pourquoi dans l'outil ZOOM il y a la possibilité de diviser la réunion en plusieurs groupes. Je t'invite à suivre le GIF ci-dessous afin de les créer. Ton rôle principal est de passé dans les toutes les breakouts afin de donner des tips à tout le monde. Cela permet également de faire les choses suivantes :

1. Créer de l'intéraction entre élèves.
2. Mettre du dynamisme d'un point de vue professeur sur la partie **pratique**.
3. Permet d'avancer plus vite sur les exercices pour les élèves.

![Zoom Breakout Rooms](https://essentials-teacher-onboarding.s3.eu-west-3.amazonaws.com/zoom_breakout.gif)

# Icebreaking

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
1. :rocket: A réussit son permis du premier coup.
2. :feu: Habite à Paris.
3. :brain: A fait l'armée.
```

Tu l'auras compris, les élèves doivent donc trouver <ins>la réponse fausse</ins>, dans ce cas la 1.

Le but est de délier les langues et faire preuve de créativité. Cela permet d'avoir une session soudée dès le début.

# Explication des outils principaux et du bootcamp

À la suite de l'icebreaking, l'encadrant pédagogique de Jedha va dérouler quelques slides afin d'expliquer les outils ainsi que le déroulement général du bootcamp. Cela te permettra de ne pas être dérangé durant ton cours si un élève n'a pas accès la ressource.

## Feuille de présence
Tu as dû recevoir tes credentials via <ins>un mail d'Edusign</ins>. Cela permet d'envoyer les feuilles de présence. Voici un exemple de comment faire pour les envoyer.

Dans un premier temps rendez-vous sur <a href="https://edusign.app/">EduSign</a> puis tu pourras suivre ce GIF :

<img src="https://essentials-teacher-onboarding.s3.eu-west-3.amazonaws.com/edusign_send_attendance.gif"/>

## Github

Tu pourras retrouver toutes les ressources de cours sur Github. Slides, note de cours, note de professeurs, solutions des exercices, cours, etc...

L'architecture est la suivante :

<img src="https://essentials-teacher-onboarding.s3.eu-west-3.amazonaws.com/architecture_repo_github.png"/>

Comme indiqué dans l'architecture ci-dessus, le dossier le plus important est celui nommé **03-Instructors** car il contient beaucoup d'éléments qui te seront très importants pour un bon enseignement.

1. Les slides : Qui te seront utiles afin de présenter les concepts que tu vas enseigner.
2. Les notes de cours : Elles te permettront de pouvoir mettre un timing sur les cours données.
3. Slack Message : Ce message est à envoyé à chaque fin de journée d'enseignement.

### Repo en fonction de la formation enseignée

1. <a href="https://github.com/JedhaBootcamp/ESSENTIALS_PROGRAM">Essentials</a>
2. <a href="https://github.com/JedhaBootcamp/FULL_STACK_12_WEEK_PROGRAM">Fullstack Full Time</a>
3. <a href="https://github.com/JedhaBootcamp/FULL_STACK_24_WEEK_PROGRAM">Fullstack Part Time</a>
4. <a href="https://github.com/JedhaBootcamp/LEAD_PROGRAM">Lead</a>
4. <a href="https://github.com/JedhaBootcamp/cybersecurity_essentials_program">Cybersecurity</a>


## <a href="https://app.julie.academy/">JULIE</a>

### Connexion & Cours

C'est la plateforme d'apprentissage que les élèves utiliseront durant toute leur formation.

Voici la procédure pour avoir ton mot de passe si tu ne t'es jamais connecté à la plateforme :

1. Aller sur le site <a href="http://app.julie.academy/">JULIE</a>
2. Clique sur _Forget your password?_
3. Suivre la procédure de réinitialisation reçue par mail
4. Se connecter avec le mot de passe créé

Une fois connecté sur JULIE, tu peux retrouver les cours via ce chemin _Courses > Data Dregrees > Essentials_. Tu remarqueras que l'architecture qu'il y a présente dans la section <ins>Github</ins> est la même dans JULIE sans le dossier _03-Instructors_

### Workspace

Oui JULIE possède un workspace intégré. C'est sur ce Jupyter Lab que tu feras pratiquer les élèves sur la partie Python et Machine Learning (module 3 et 4).

Pour lancer une machine voici des GIFs explicatifs :

Lancement de la machine :

<img src="https://essentials-teacher-onboarding.s3.eu-west-3.amazonaws.com/workspace_1.gif"/>

Utilisation de la machine créée :

<img src="https://essentials-teacher-onboarding.s3.eu-west-3.amazonaws.com/workspace_2.gif"/>

**Important** les workspaces sont tout le temps sauvegardés. C'est important de le préciser aux élèves pour ne pas qu'ils craignent de perdre quoi que ce soit. **Si jamais** nous venions à cleaner des machines ou des données, les personnes concernées seraient prévenues 1 semaine à l'avance afin de tout télécharger en local.

## Google Drive

Cela permettra aux élèves de récupérer les solutions. Comme tu as pu le voir, les élèves n'ont en aucuns cas accès au dossier _03-Instructors_, c'est pourquoi c'est à toi de partager les solutions dans leur Drive. Tu as reçu le lien dans le mail.

Comment est structuré le drive? Restons sur l'exemple de la ds-paris-00 :

<img src="https://essentials-teacher-onboarding.s3.eu-west-3.amazonaws.com/architecture_google_drive.png"/>

Les solutions devront être déposées dans le Drive dans le dossier **### Solutions ###** en fin de cours afin de permettre aux élèves d'y accéder.

## Slack

Notre messagerie instantanée sur laquelle tu partageras tout avec les élèves (lien zoom, synthèse des cours, jokes...).

Tu devrais avoir accès au channel de la session sur laquelle tu enseigne `#ds-{campus}-{session_number}`.

# Journée type

1. 9:55 : Dire bonjour sur Slack.
2. 10:00 : Lancer le ZOOM avec la commande `/zoom meeting NomDeSession_M0x_D0x_NomDeLaJournée` dans le channel Slack.
3. 10:00 : Lancer le record sur le Cloud ZOOM.
4. 10:05 : Envoyer les feuilles de présence.
5. 10:05 Pendant une 15aine de minutes, demander aux élèves comment s'est passé le cours dernier, voir si ils n'ont pas de questions sur l'exercice de la veille. 
6. 10:20 : Débuter le cours du jour.
7. 12:30 : Pause du midi.
8. 13:30 : Reprise des cours / début des exercices (création des breakout rooms).
9. 18:00 : Envoie de la synthèse du jour.
10. 18:30 : Dépôt des solutions dans le Google Drive.