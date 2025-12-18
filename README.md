
# Application de Gestion de Factures (Invoice)

❤️ SOUTIENS-MOI POUR DES TUTOS DE QUALITÉ (Seulement 2 €/mois) :  https://fr.tipeee.com/faizdev/

Pour un guide pas à pas, consultez la vidéo complète du tutoriel sur YouTube :
[Regarder le tuto complet](https://youtu.be/VoKDkMjE9LU)

![Commencrére un saas de création de facture](https://github.com/user-attachments/assets/506f04a5-c38a-4a73-a1ec-21fd0055c7cc)

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

