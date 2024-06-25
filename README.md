Formation Data Scientist d'Open Classrooms<br>
Projet 7 : Implémentez un modèle de scoring<br>
<br>
Objectif : automatiser la prédiction de défaut de remboursement sur des prêts à la consommation.<br>
<br>
Ce dépôt git sert au déploiement dans le cloud de l'API de prédiction et de son interface Streamlit.<br>
<br>
Le dossier <b>interface</b> contient le code de l'interface Streamlit avec des données de test.<br>
Le dossier <b>app</b> contient le code de l'API, les données de test préprocessées et le modèle entraîné.<br>
Le dossier <b>tests</b> contient des tests unitaires pour le code de l'API qui sont lancés à chaque push.<br>
Un docker-compose et des DockerFiles ont été ajoutées pour faciliter le déploiement dans le cloud.