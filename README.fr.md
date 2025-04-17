# MonLivre
**Un espace personnel pour organiser, suivre et annoter vos livres préférés.**

## À propos du projet
MonLivre est une application conçue pour les amoureux des livres qui souhaitent :
- Organiser leurs collections de livres et leurs éditions spécifiques.
- Suivre leurs progrès de lecture et ajouter des livres à leur liste de souhaits.
- Annoter et documenter leurs réflexions ou citations préférées.
- Découvrir et célébrer leur voyage littéraire à travers des statistiques et des journaux personnalisés.

## Fonctionnalités principales
- **Gestion des livres** : Ajoutez des livres avec leurs éditions spécifiques (éditeur, année, type d'édition).
- **Statut personnalisé** : Suivez les livres que vous possédez, que vous avez lus, ou que vous souhaitez acquérir.
- **Annotations** : Notez vos pensées, vos analyses ou des citations marquantes.
- **Statistiques** : Observez vos habitudes de lecture et suivez vos progrès.
- **Design moderne** : Interface utilisateur réactive construite avec Vue + Quasar.

## Technologies utilisées
- **Frontend** : Vue + Quasar
- **Backend** : Node.js (NestJS) avec Prisma pour la gestion de la base de données.
- **Base de données** : PostgreSQL.
- **Déploiement** : Hébergé avec AWS (Dockerisé).

## Installation et utilisation
### Prérequis
- Node.js installé (version 16 ou supérieure).
- PostgreSQL configuré pour le backend.

### Installation
1. Clonez ce dépôt :
   ```bash
   git clone https://github.com/andrelcunha/MonLivre.git
   ```

2. Installez les dépendances :
   ```bash
   cd monlivre-backend
   npm install
   ```

3.Configurez votre fichier .env pour la connexion à la base de données :
   ```env
   DATABASE_URL=postgresql://<utilisateur>:<mot_de_passe>@<host>:<port>/<nom_de_la_base>
   ```

4. Lancez le serveur:
   ```bash
    npm run start
    ```

5. Accédez à l'application via : http://localhost:3000

## Licence
Ce projet est sous licence MIT. Consultez le fichier LICENSE pour plus de détails.

