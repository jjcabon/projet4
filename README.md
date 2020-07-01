# projet4
Projet en plusieurs TP pour des terminales NSI concernant les paradigmes de programmation, en particulier la programmation objet, les données structurées et les requêtes SQL
Je vous transmets les idées que j'ai eu ce matin.
Il faut rédiger des questions et des démarches pour les élèves pour qu'ils construisent tout ça et repérer les compétences du programme acquises.
Comptons 2 heures par TP cela veut dire qu'il faudra leur simplifier la recherche. 
Notre objectif est de construire un projet pédagogique pour que les élèves apprennent un maximum de choses en construisant.
Projet 4:
Construire un outil de mémorisation active: la remémoration.
Principe: se poser des questions, se souvenir de la réponse et insister sur celles qui sont mal acquises. Principe mis en oeuvre dans l'application anki et également quizlet.

TP1: On pose une question. On attend que le participant se rappelle et on lui demande de s'évaluer: facile, moyen, difficile.
Un test est une liste de 10 questions + réponses.  On pose 20 questions soit dans l'ordre soit au hasard (random) et on récupère l'évaluation de chacune qui pourrait être notée 5pts, 3 pts ou 1pts selon le niveau. Un score du participant peut être calculé et affiché. Les questions évaluées difficiles seront posées à nouveau. On utilise la POO, on la met en oeuvre.

TP2 Données structurées: comment organiser toutes ces données?
Comment poser le problème aux élèves?
Table Question/Réponse: idTest, idMatière,cours
Table Matière: idMat, ?
Table participant: idPart, idMat, idTest, score 
Table résultats: idRes, idPart, idTest
Quelles relations entre elles?

TP3 recherches dans les tables
les requêtes, la logique, les jointures...
?
TP4 création d'un site web
quelles démarche pour les élèves?

TP 5 
confidentialité des données: CNIL
sécurité de l'accès aux données?
