# ✈️ Projet 01 : Analyse d'une base de données de réservations de vols

##  Description

Ce projet a été réalisé dans le cadre du **Cahier de Vacances Machine Learnia**. Son objectif est d'explorer une base de données de réservations de vols afin de répondre à des problématiques métier grâce à SQL, SQLite et Python.

À travers ce projet, j'ai appris à manipuler une base de données relationnelle, à écrire des requêtes SQL complexes et à analyser les données pour produire des recommandations basées sur les résultats obtenus.



##  Structure de la base de données

La base de données est composée de trois tables reliées entre elles :

* **passengers** (`id`, `first_name`, `last_name`, `email`, `nationality`) : informations sur les passagers.
* **flights** (`id`, `flight_number`, `origin`, `destination`, `departure_time`, `arrival_time`, `aircraft`, `capacity`, `price_eur`) : informations sur les vols.
* **bookings** (`id`, `passenger_id`, `flight_id`, `booking_date`, `seat_class`, `seat_number`, `status`) : informations sur les réservations.

Les relations entre ces tables m'ont permis d'utiliser les jointures SQL pour relier les données et réaliser des analyses plus complètes.



##  Objectifs du projet

* Explorer une base de données relationnelle.
* Répondre à des questions métier à l'aide de SQL.
* Analyser les performances des destinations.
* Identifier les destinations les plus rentables.
* Extraire des informations utiles à la prise de décision.



## 🛠️ Technologies utilisées

* Python
* Jupyter Notebook
* SQLite3
* SQL
* Pandas


##  Compétences acquises

Au cours de ce projet, j'ai appris à :

* me connecter à une base de données SQLite depuis Python ;
* exécuter des requêtes SQL dans un notebook Jupyter ;
* utiliser les principales clauses SQL (`SELECT`, `WHERE`, `ORDER BY`, `GROUP BY`) ;
* réaliser des agrégations avec `COUNT`, `SUM` et `AVG` ;
* utiliser les **jointures (`INNER JOIN`)** pour relier plusieurs tables ;
* comprendre et analyser une base de données relationnelle ;
* manipuler les résultats SQL avec **Pandas** ;
* transformer une problématique métier en requêtes SQL ;
* analyser les données afin d'aider à la prise de décision.



##  Ce que ce projet m'a apporté

Ce projet m'a permis de consolider mes connaissances en SQL tout en découvrant une démarche proche de celle d'un **Data Analyst**. J'ai appris à décomposer un problème métier en plusieurs questions, à construire les requêtes SQL adaptées et à interpréter les résultats obtenus pour formuler des recommandations basées sur les données.

