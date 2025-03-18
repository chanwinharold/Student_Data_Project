

**Contexte** :
Les données ont été recueillies lors d'une enquête menée auprès d'élèves de l'enseignement secondaire en mathématiques et en portugais. Elles contiennent de nombreuses informations intéressantes sur la situation sociale, le genre et les études des élèves. Elles peuvent être utilisées pour évaluer l'AED ou pour prédire la note finale des élèves.

**Contenu** :
Attributs pour les ensembles de données student—mat.csv (cours de mathématiques) et student—por.csv (cours de portugais) :


1. école — école de l'élève (binaire : 'GP' — Gabriel Pereira ou 'MS' — Mousinho da Silveira)
2. sexe — sexe de l'étudiant (binaire : « F » — féminin ou « M » — masculin)
3. âge — âge de l'étudiant (numérique : de 15 à 22)
4. adresse — type d'adresse du domicile de l'étudiant (binaire : « U » — urbain ou « R » — rural)
5. famsize — taille de la famille (binaire : « LE3 » — inférieur ou égal à 3 ou « GT3 » — supérieur à 3)
6. Pstatus — statut de cohabitation des parents (binaire : « T » — vivant ensemble ou « A » — séparés)
7. Medu — niveau d'éducation de la mère (numérique : 0 — aucun, 1 — éducation primaire (4e année), 2 — 5e à 9e année, 3 — éducation secondaire ou 4 — éducation supérieure)
8. Fedu — niveau d'éducation du père (numérique : 0 — aucun, 1 — éducation primaire (4e année), 2 — 5e à 9e année, 3 — éducation secondaire ou 4 — éducation supérieure)
9. Mjob — emploi de la mère (nominal : « enseignant », « lié aux soins de santé », « services » civils (par exemple administratifs ou policiers), « à domicile » ou « autre »)
10. Fjob — emploi du père (nominal : « enseignant », « soins de santé », « services » civils (par exemple administratifs ou policiers), « à domicile » ou « autre »)
11. raison — raison de choisir cette école (nominale : proche de « chez soi », « réputation » de l'école, préférence de « cours » ou « autre »)
12. tuteur — tuteur de l'étudiant (nominal : « mère », « père » ou « autre »)
13. temps de trajet — temps de trajet domicile—école (numérique : 1 — <15 min., 2 — 15 à 30 min., 3 — 30 min. à 1 heure, ou 4 — >1 heure)
14. studytime — temps d'étude hebdomadaire (numérique : 1 — < 2 heures, 2 — 2 à 5 heures, 3 — 5 à 10 heures ou 4 — > 10 heures)
15. échecs — nombre d'échecs de classe passés (numérique : n si 1<=n<3, sinon 4)
16. schoolsup — soutien éducatif supplémentaire (binaire : oui ou non)
17. famsup — soutien éducatif familial (binaire : oui ou non)
18. payant — cours supplémentaires payants dans le cadre du cours (mathématiques ou portugais) (binaire : oui ou non)
19. activités — activités extrascolaires (binaire : oui ou non)
20. crèche — fréquenté l'école maternelle (binaire : oui ou non)
21. supérieur — souhaite poursuivre des études supérieures (binaire : oui ou non)
22. Internet — Accès Internet à domicile (binaire : oui ou non)
23. romantique — avec une relation amoureuse (binaire : oui ou non)
24. famrel — qualité des relations familiales (numérique : de 1 — très mauvaise à 5 — excellente)
25. temps libre — temps libre après l'école (numérique : de 1 — très faible à 5 — très élevé)
26. goout — sortir avec des amis (numérique : de 1 — très faible à 5 — très élevé)
27. Dalc — consommation d'alcool au cours d'une journée de travail (numérique : de 1 — très faible à 5 — très élevée)
28. Walc — consommation d'alcool le week—end (numérique : de 1 — très faible à 5 — très élevée)
29. santé — état de santé actuel (numérique : de 1 — très mauvais à 5 — très bon)
30. absences — nombre d'absences scolaires (numérique : de 0 à 93)


Ces notes sont liées à la matière du cours, Mathématiques ou Portugais :

G1 — note de la première période (numérique : de 0 à 20)
G2 — note de la deuxième période (numérique : de 0 à 20)
G3 — note finale (numérique : de 0 à 20, objectif de sortie)