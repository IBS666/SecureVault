# 🔐 SecureVault

SecureVault est une **plateforme web sécurisée** qui permet aux utilisateurs de gérer, organiser et partager leurs mots de passe et données sensibles de manière simple et fiable.  
Elle intègre également un **chatbot intelligent alimenté par l’IA (OpenAI)**, capable d’accompagner les utilisateurs et d’améliorer leur expérience en temps réel.

---

##  Fonctionnalités principales

###  Gestion des coffres et identifiants
- Créer, organiser et rechercher des coffres (Vaults) et des identifiants.
- Partager de manière sécurisée les données avec d’autres utilisateurs.

###  Sécurité
- Authentification sécurisée avec **JWT**.
- Chiffrement des mots de passe avec **bcrypt**.
- Gestion des rôles et permissions (Users / Admins).

###  Gestion des organisations
- Créer une organisation.
- Ajouter et gérer des membres.
- Gérer les accès par rôle.




##  Architecture du projet
```plaintext
SecureVault/
├── backend/
│   ├── src/main/java/com/securevault/
│   │   ├── controllers/
│   │   ├── models/
│   │   ├── repositories/
│   │   ├── services/
│   │   └── SecureVaultApplication.java
│   └── src/main/resources/
│       └── application.properties
│
├── frontend/
│   ├── src/app/
│   │   ├── login/
│   │   ├── dashboard/
│   │   ├── signUp/
│   │   ├── services/
│   │   └── welcome/
│   └── angular.json
│
└── README.md

