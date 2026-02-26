# Network Fundamentals – Module 2 (TryHackMe)

## 1. What is Networking?
Le **networking** désigne l’ensemble des technologies permettant à des machines (ordinateurs, serveurs, smartphones, etc.) de **communiquer entre elles** afin d’échanger des données.

Objectifs principaux :
- Partage de ressources (fichiers, imprimantes, services)
- Communication (web, email, messagerie)
- Accès à des services distants (cloud, bases de données, API)

---

## 2. Intro to LAN
Un **LAN (Local Area Network)** est un réseau local couvrant une zone géographique restreinte (maison, bureau, entreprise).

Caractéristiques :
- Faible latence
- Haut débit
- Contrôlé par une organisation ou un individu

Équipements courants :
- Ordinateurs
- Serveurs
- Switch
- Routeur
- Point d’accès Wi-Fi

---

## 3. Packets & Frames
Les données transmises sur un réseau sont **découpées** pour être envoyées efficacement.

### Packet (Paquet)
- Niveau réseau (**Layer 3 – OSI**)
- Contient :
  - Adresse IP source
  - Adresse IP destination
  - Données

### Frame (Trame)
- Niveau liaison de données (**Layer 2 – OSI**)
- Contient :
  - Adresse MAC source
  - Adresse MAC destination
  - Paquet encapsulé

> **Résumé :**  
> Les **paquets** voyagent entre réseaux,  
> les **trames** voyagent à l’intérieur d’un réseau local.

---

## 4. OSI Model
Le **modèle OSI** est un modèle conceptuel décrivant la circulation des données à travers un réseau en **7 couches**.

| Layer | Nom | Rôle |
|------|----|-----|
| 7 | Application | Interaction utilisateur (HTTP, FTP, SMTP) |
| 6 | Presentation | Encodage, chiffrement, compression |
| 5 | Session | Gestion des sessions |
| 4 | Transport | Fiabilité et ports (TCP / UDP) |
| 3 | Network | Routage et adresses IP |
| 2 | Data Link | Trames et adresses MAC |
| 1 | Physical | Câbles et signaux |

Utilité du modèle OSI :
- Compréhension du fonctionnement réseau
- Diagnostic de pannes
- Classification des protocoles et attaques

---

## 5. Extending Your Network
Pour communiquer avec d’autres réseaux (ex : Internet), on utilise des équipements supplémentaires.

### Routeur
- Relie plusieurs réseaux
- Permet la communication LAN ↔ WAN
- Basé sur les adresses IP

### Firewall
- Filtre le trafic réseau
- Autorise ou bloque les connexions
- Élément clé de la sécurité réseau

---

## 6. Commande essentielle : ping
La commande `ping` permet de **tester la connectivité réseau** via ICMP.

### Ping continu (sans limite)
```bash
ping 8.8.8.8