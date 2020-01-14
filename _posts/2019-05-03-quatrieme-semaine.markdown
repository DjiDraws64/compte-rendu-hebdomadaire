---
layout: post
title:  "Quatrième semaine"
date:   2019-05-03 5:00:00 +0200
categories: 1ereannee
author: Djinani
---


#### du 29 avril au 03 mai 2019

On a fait tout le tour de l'entreprise CHM pour changer quelques écrans.

Après avoir importer la base de données dans **phpmyadmin**, je dois l'importer dans **GLPI**:

* -- Il faut tout d'abord changer la capacité maximale de la taille dans **php.ini**
* -- Puis exporter la base de données en fichier **SQL** depuis **phpmyadmin**
* -- Compresser le fichier sql, en le remnommant par **.sql.zip**
* -- **Créer une nouvelle base de données**
* -- **Importer** l'achive dans notre nouvelle base de données
* -- Configurer GLPI pour prendre en compte notre notre base de données, en la mettant par défaut, dans **config_db.php**
* -- Relancher **Apache**
* -- Puis relancer **GLPI**, une page de mise à jour est affichée

