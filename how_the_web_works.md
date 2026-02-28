# 🌐 TryHackMe — How the Web Works

## 📌 Objectif du chapitre
Comprendre les bases du fonctionnement du Web : comment un navigateur communique avec un serveur, comment les sites sont accessibles via Internet, et quels sont les composants techniques fondamentaux utilisés.

---

## 🧠 Concepts abordés

### 🔗 Client / Serveur
- Le **client** (navigateur web) envoie des requêtes
- Le **serveur web** reçoit la requête et renvoie une réponse
- Les échanges se font via le protocole **HTTP/HTTPS**

---

### 🌍 DNS (Domain Name System)
- Le DNS permet de traduire un **nom de domaine** (ex: `tryhackme.com`)
- en **adresse IP** (ex: `104.xxx.xxx.xxx`)
- Étapes simplifiées :
  1. Requête DNS
  2. Résolution du nom
  3. Retour de l’adresse IP
  4. Connexion au serveur

---

### 📡 HTTP & HTTPS
- **HTTP** : protocole de communication entre client et serveur
- **HTTPS** : version sécurisée (chiffrement TLS)
- Notions clés :
  - Requête (GET, POST…)
  - Réponse (codes HTTP : 200, 404, 403, etc.)
  - Headers
  - Body

---

### 🧾 Méthodes HTTP principales
- **GET** : récupérer des données
- **POST** : envoyer des données
- **PUT** : modifier des données
- **DELETE** : supprimer des données

---

### 🗂️ Composants d’un site web
- **Frontend** : HTML, CSS, JavaScript (ce que voit l’utilisateur)
- **Backend** : logique serveur, bases de données
- **Serveur web** : Apache, Nginx, etc.

---

### 🔐 Sécurité (notions introductives)
- Importance du HTTPS
- Exposition possible via :
  - Mauvaise configuration serveur
  - Données sensibles dans les requêtes
- Le Web est une surface d’attaque majeure en cybersécurité

---

## 🛠️ Outils & commandes évoqués
- Navigateur web
- Inspection des requêtes
- Compréhension du rôle du DNS et des protocoles

---

## ✅ Ce que j’ai retenu
- Le Web repose sur des échanges simples mais structurés
- Chaque requête laisse des traces exploitables en cybersécurité
- Bien comprendre HTTP/DNS est essentiel avant d’aborder le pentest web

---