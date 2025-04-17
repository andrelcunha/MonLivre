# MonLivre
[![fr](https://img.shields.io/badge/lang-fr-blue.svg)](README.fr.md)
[![en](https://img.shields.io/badge/lang-ptbr-green.svg)](README.pt-br.md)

*A personal space to organize, track, and annotate your favorite books.*

## About the Project
MonLivre is an app designed for book lovers who want to:
- Organize their book collections and specific editions.
- Track their reading progress and create wishlists for future reads.
- Annotate and document their thoughts or favorite quotes.
- Explore and celebrate their literary journey with personalized stats and journaling.

## Key Features
- **Book Management**: Add books with their specific editions (publisher, year, edition type).
- **Personal Status**: Track books you own, have read, or wish to acquire.
- **Annotations**: Write down your thoughts, analyses, or memorable quotes.
- **Statistics**: View your reading habits and monitor progress.
- **Modern Design**: Responsive user interface built with Vue + Quasar.

## Technologies Used
- **Frontend**: Vue + Quasar
- **Backend**: Node.js (NestJS) with Prisma for database management.
- **Database**: PostgreSQL
- **Deployment**: Hosted with AWS (Dockerized).

## Installation and Usage
### Prerequisites
- Node.js installed (version 16 or higher).
- PostgreSQL configured for the backend.

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/andrelcunha/MonLivre.git
   ```
2. Install dependencies:
   ```bash
   cd monlivre-backend
   npm install
   ```
3. Configure your .env file for database connection:
   ```env
   DATABASE_URL=postgresql://<username>:<password>@<host>:<port>/<database_name>
   ```
4. Start the server:
   ```bash
   npm run start
   ```
5. Access the app in your browser at http://localhost:3000.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
