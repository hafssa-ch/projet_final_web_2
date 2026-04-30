# 💰 Gestion de Dépenses Personnelles
## Projet final du module:

Application **multi-plateforme** permettant de gérer efficacement ses dépenses, son budget et ses statistiques.

Elle est composée de :

- 🌐 Une API backend (Node.js + SQLite)
- 💻 Une application web (React)
- 📱 Une application mobile (Android Java)

---

## 🎯 Objectif du projet

Ce projet a pour objectif de proposer une solution simple et efficace pour :
- Suivre ses dépenses quotidiennes
- Gérer un budget mensuel
- Visualiser ses données financières via des graphiques

---

## 📦 Technologies utilisées

| Composant  | Technologies |
|------------|-------------|
| Backend    | Node.js, Express, SQLite, JWT, bcryptjs, cors |
| Web        | React, React Router, Axios, Recharts |
| Mobile     | Android (Java), Retrofit, RecyclerView, MPAndroidChart, SharedPreferences |
| Outils     | Git, Postman, curl, Android Studio, VS Code |

---

## 🚀 Fonctionnalités

### 🔐 Authentification

- Inscription et connexion sécurisées
- Gestion des sessions avec JWT
- Hachage des mots de passe

### 💸 Dépenses

- Ajouter une dépense (montant, date, catégorie, note)
- Modifier et supprimer une dépense
- Filtrer par date et catégorie

### 📂 Catégories

- Ajouter, modifier et supprimer
- Attribution de couleur

### 📊 Budget
- Définir un budget mensuel
- Voir le montant dépensé
- Voir le reste disponible
- Barre de progression
- Alerte en cas de dépassement

### 📈 Statistiques

- Camembert par catégorie
- Histogramme mensuel

### 🌐 Interface Web

- Dashboard interactif
- Visualisation des données
- Gestion complète

---

## 🗂️ Structure du projet

```
GestionDepenses/
│
├── backend/
│ ├── controllers/
│ ├── routes/
│ ├── middleware/
│ ├── database.js
│ ├── server.js
│ └── expenses.db
│
├── webapp/
│ ├── src/
│ │ ├── components/
│ │ ├── contexts/
│ │ ├── services/
│ │ └── App.js
│ └── package.json
│
└── mobile/
└── (Projet Android Studio)
```

---

## ⚙️ Installation et exécution

### 🔧 Backend

```
cd backend
npm install
npm start
```

Serveur disponible sur :
http://localhost:5000

### 🌐 Web
```
cd webapp
npm install
npm start
```

Application web :
http://localhost:3000

### 📱 Android

Ouvrir avec Android Studio
Modifier l’URL API :
Cas	URL
Émulateur	http://10.0.2.2:5000/api/

Téléphone	http://IP_PC:5000/api/
Lancer l’application

## 🔑 Compte de démonstration

Email	: demo@example.com

Mot de passe	: password123

## 🗄️ Base de données

4 tables principales :

- users
- expense_categories
- expenses
- monthly_budgets

✔ Base SQLite

✔ Création automatique

✔ Requêtes sécurisées

## 🎨 Interface utilisateur

Web
Dashboard avec graphiques
Gestion complète
Mobile
Navigation par onglets
Listes avec RecyclerView
Notifications
Graphiques

---

## 📸   Resultat

### site web

https://github.com/user-attachments/assets/999554cf-4e34-4ef8-a4e7-574354a09b2a


### application android

https://github.com/user-attachments/assets/dc66297a-adcf-4b20-aa1d-132f48674162


-----
## 👨‍🏫 Encadrement

Projet réalisé à l’ENS Marrakech#

Encadré par: Dr.Mohamed Lachgar


Réalisé par:
Hafssa CHKOUKED


## ⭐ Conclusion

Ce projet illustre une application complète Full Stack (Mobile + Web + Backend) en respectant les bonnes pratiques modernes de développement logiciel.
