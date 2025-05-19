# 👋 Hey !

Bienvenue sur ce mini projet **Next.js** lancé avec [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app) !

## 📩 À propos du projet

Il s'agit d'une **simulation de système de newsletter** où vous pouvez enregistrer les emails de vos abonnés.

Ce projet utilise **[Mailchimp](https://mailchimp.com/)**, une plateforme d’emailing, pour :

- Enregistrer les emails dans une liste d’audience
- Envoyer des newsletters personnalisées à vos abonnés
- Utiliser des **templates** pour rendre vos mails plus attrayants

> 🔐 Pour cela, vous devrez créer un compte Mailchimp et récupérer les informations d’identification nécessaires (clé API & ID d’audience).

---

## 🚀 Getting Started

### Étapes à suivre :

1. **Créer un compte Mailchimp**  
   👉 [https://mailchimp.com/](https://mailchimp.com/)

2. **Choisir une offre gratuite** pour commencer

3. **Créer une clé d'API** :  
   Allez dans *Account → Extras → API Keys*

4. **Récupérer l'ID de votre audience** :  
   Allez dans *Audience → Settings → Audience name and defaults*

5. **Créer un fichier `.env` à la racine du projet** et y ajouter les variables :

   ```env
   MAILCHIMP_API_KEY=your_api_key
   MAILCHIMP_API_SERVER= Mettez ici les 4 derniers caractères de votre clé d'api .
   MAILCHIMP_AUDIENCE_ID=your_audience_id

6. Installation :
npm install

7. Lancer le serveur de développement:

npm run dev
# ou
yarn dev
# ou
pnpm dev
# ou
bun dev

8. Développement:
   Vous pouvez commencer à éditer la page principale dans :app/page.tsx

9. Pour aller plus loin

    📖 Documentation Next.js

    🧠 Apprendre Next.js

    💻 Dépôt GitHub de Next.js
