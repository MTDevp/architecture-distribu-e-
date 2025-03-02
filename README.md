# Configuration dans IntelliJ
1. **Ouvrir le projet**  
   Lancez IntelliJ IDEA et ouvrez le projet concerné.

2. **Accéder à la gestion de Git**  
   Dans la barre d'outils, allez dans **VCS** ou cliquez sur l'onglet **Git** en bas de l'IDE.

3. **Gérer les remotes**  
   Sélectionnez **Manage Remotes**.

4. **Ajouter un nouveau remote**  
   Cliquez sur le bouton **+** pour ajouter une nouvelle source distante.

5. **copier l'url suivant ** 
https://github.com/MTDevp/architecture-distribu-e-.git

## 🛠️ Méthode de travail  

Dans notre projet, nous suivons une approche **Git Flow**, où chaque microservice est développé sur une branche spécifique.  

### 1️⃣ **Création d'une branche pour chaque microservice**  

Pour assurer une bonne organisation et un développement modulaire, chaque microservice sera développé sur une **branche dédiée**.  

Exemples de branches pour les microservices :  
- `music-service` : Service d'authentification  
- `user-service` : Gestion des utilisateurs  
 

**Commande pour créer et basculer sur une branche dédiée :**  
```bash
git checkout -b nom-du-microservice
