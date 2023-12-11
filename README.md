# Tasks Organizer with Django

Une application de gestion de tâches avec Python et le framework Django

## Modèles

- Collection
  - name
  - slug
- Task
  - description
  - collection (ForeignKey)

## Fonctionalités

[x] Ajouter une collection  
[ ] Supprimer une collection  
[x] Empêcher l'ajout d'une collection en doublon  
[ ] Ajouter une tâche (reliée à une collection)  
[ ] Supprimer une tâche  
[ ] Afficher les tâches d'une collection

---

**Faire tourner le serveur en local** sur le port 8000: `python manage.py runserver`
