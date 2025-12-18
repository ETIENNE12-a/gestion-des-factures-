
# Application de Gestion de Factures (Invoice)
---

## Installation

1. Copier `.env.example` en `.env` et remplir les valeurs :
   ```bash
   cp .env.example .env
   ```
2. Installer les dépendances :
   ```bash
   npm install
   ```

## Lancement

Démarrer l'application en développement :
```bash
npm run dev
```

L'application sera disponible sur `http://localhost:3000` par défaut.

## Variables d'environnement importantes
- `NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY` — clé publique Clerk (frontend)
- `CLERK_SECRET_KEY` — clé secrète Clerk (backend)
- `DATABASE_URL` — URL de la base de données (ex : `file:./dev.db` pour SQLite)

> ⚠️ Ne commitez jamais votre fichier `.env` avec des clés réelles.

## Contribuer
Les contributions sont bienvenues : ouvrez une issue ou une pull request.

---

