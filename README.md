# EG_petClinicCI
CI pipeline with the Java/Spring project PetClinic

# Résumé

Mise en place d'une solution d'automatisation d'une ligne d'automatisation d'intégration continue pour une équipe de développement Java/Spring.
La base de données est "in memory" (h2) mais est portable sur SGBD MySQL/MariaDB ou postGresql
La solution proposera permettra de
- Automatisation des processus qualités avec 
  - métriques source du code (sonarqube)
  - tests unitaire, tests fonctionnels & tests de non-régressio (selenium)
- Nous voulons que ce soit on premise (1er temps) ou en cloud (second temps)
- et que nos données soient sécurisées (sauvegardes)
- le client et utilisateur final testeur doivent pouvoir sur connecter à l'application en dev ou recette
- La solution est monitorée
