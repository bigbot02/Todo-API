# ToDo API

## Prérequis
- Java 17
- MySQL (via XAMPP)
- Maven

## Démarrage
1. Clonez le dépôt.
2. Configurez MySQL et créez la base de données `todo_db`.
3. Mettez à jour `application.properties` avec vos informations MySQL.
4. Exécutez l'application via IntelliJ/Eclipse ou `mvn spring-boot:run`.
5. Accédez à Swagger UI à `http://localhost:8080/swagger-ui.html`.

## Endpoints
- `GET /api/tasks` : Liste toutes les tâches.
- `GET /api/tasks/{id}` : Récupère une tâche spécifique.
- `POST /api/tasks` : Crée une nouvelle tâche.
- `PUT /api/tasks/{id}` : Met à jour une tâche.
- `DELETE /api/tasks/{id}` : Supprime une tâche.
- `GET /api/tasks/search` : Recherche des tâches par titre.
- `GET /api/tasks/completed` : Filtre les tâches terminées.
