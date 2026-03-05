# Introduction au langage SQL avec le SGBD Firebird

➡️ Cours associé : **[Introduction au langage SQL avec le SGBD Firebird](https://stahe.github.io/sql-firebird-janv-2006/)**

## Présentation

Ce document est une introduction au langage **SQL (Structured Query Language)** appliquée au **SGBD Firebird**.
Il reprend et adapte un document pédagogique plus ancien rédigé en **1991 pour Oracle**, lui-même largement inspiré de la documentation officielle d’Oracle et de l’ouvrage :

* *SQL – Initiation, Programmation et Maîtrise*
  par **Christian Marée** et **Guy Ledant**, publié chez Eyrolles. 

SQL est un **langage standard permettant de créer, maintenir et interroger des bases de données relationnelles**.
Il est largement indépendant du système de gestion de bases de données (SGBD) utilisé, même si certains SGBD introduisent des extensions propriétaires. 

## Pourquoi Firebird ?

Les exemples de ce document utilisent le **SGBD Firebird**.
Ce choix est motivé par une caractéristique particulièrement pratique dans un contexte pédagogique : une base de données Firebird peut être **contenue dans un unique fichier**.

Cela permet par exemple :

* de copier facilement une base sur une **clé USB**
* de l’utiliser sur **différents ordinateurs** (personnel, université, laboratoire)
* de travailler sans infrastructure complexe

## Compatibilité SQL

Bien que les exemples soient écrits pour Firebird, la plupart peuvent être reproduits avec d’autres SGBD relationnels, par exemple :

* MySQL
* PostgreSQL
* Firebird
* SQL Server Express
* Microsoft Access
* Oracle

Ces systèmes utilisent tous SQL, avec parfois des **variantes ou extensions propres au produit**. 

## Public visé

Ce document s’adresse :

* aux **débutants souhaitant découvrir SQL**
* aux personnes désirant **réviser les bases du langage**

Il se concentre sur l’apprentissage du **SQL fondamental**.

## Hors périmètre

Certains aspects ne sont volontairement pas abordés :

* procédures stockées
* programmation SQL avancée
* API SQL
* administration d’un SGBD

L’objectif est de fournir une **initiation claire et progressive au langage SQL**. 
