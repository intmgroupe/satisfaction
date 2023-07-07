Introduction
============

This plugin extends the satisfaction survey of GLPI.

Satisfaction is a plugin which allows you to add questions to the satisfaction survey.

Version 1.5.3 and before version 1.6.0 are a fork to work on top of GLPI 9.5 and its fork ISTM-NG in version 1.5.

Features
--------

- Different surveys (one for each entity)

- Multiple questions with three types:
  - Yes / No dropdown list.
  - Text box.
  - Note: It will be possible to configure the total number of stars.
  - Numeric scale (0-10, NC): Features a radio button series from 0 to 10 with an extra NC.

- This plugin will allow you to add all the questions configured in the plugin with the two questions of the GLPI core in the satisfaction survey.

- This plugin will add two new tags to the notifications for "Satisfaction survey" and "Satisfaction survey answer" events.
  - The tag "##satisfaction.question##" will allow you to add the list of questions of the plugin.
  - The tag "##satisfaction.answer##" will allow you to add the list of questions and answers of the plugin.

Translations
------------

  Join us on [Transifex](https://www.transifex.com/InfotelGLPI/GLPI_satisfaction)

------------------------------------------------------------------------------------------------------------------------

Introduction
============

Ce plugin étend l'enquête de satisfaction de GLPI.

Satisfaction est un plugin qui vous permet d'ajouter des questions à l'enquête de satisfaction.

La version 1.5.3 et avant la version 1.6.0 sont un fork pour travailler au dessus de GLPI 9.5 et son fork ISTM-NG en version 1.5.

Fonctionnalités
--------

- Différents questionnaires (un pour chaque entité)

- Questions multiples avec trois types de questions :
  - Liste déroulante Oui / Non.
  - Zone de texte.
  - Note : Il sera possible de configurer la nombre total d’étoiles.
  - Échelle numérique (0-10, NC) : Dispose d'une série de boutons radio de 0 à 10 avec un NC supplémentaire.

- Ce plugin va permettre d’ajouter l’ensemble des questions configurés dans le plugin avec les deux questions du cœur de GLPI.

- Ce plugin va ajouter deux nouvelles balises dans les notifications concernant les événements « Enquête de satisfaction » et « Réponse à l’enquête de satisfaction ».
  - La balise « ##satisfaction.question## » va permettre d’ajouter la liste des questions du plugin.
  - La balise « ##satisfaction.answer## » va permettre d’ajouter la liste des questions et réponses du plugin.

Traductions
-----------

Rejoignez-nous sur [Transifex](https://www.transifex.com/InfotelGLPI/GLPI_satisfaction)
