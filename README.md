Description longue (README ou GitHub)
Ce projet représente l’API Gateway du système distribué basé sur des microservices. Il assure le routage des requêtes HTTP 
vers les microservices MSCompte et MSBanque, tout en permettant une gestion centralisée de la configuration, de la sécurité (authentification, autorisation), 
ainsi que du load balancing si nécessaire.
Le projet s’intègre dans une architecture de type Spring Cloud Gateway, avec la possibilité d’ajouter des routes dynamiques via une base 
de données ou Redis.

✅ Fonctionnalités prévues :
Routage des requêtes HTTP vers MSCompte et MSBanque
Gestion centralisée des points d’entrée
Support des routes statiques et dynamiques
Intégration facile avec Eureka ou Discovery Service
Personnalisation des filtres (authentification, logs, CORS)
