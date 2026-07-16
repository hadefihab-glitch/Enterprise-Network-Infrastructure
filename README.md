# 🏢 Infrastructure Informatique d'Entreprise

## 📖 Présentation du projet

Ce projet consiste à concevoir, déployer et administrer une infrastructure informatique complète simulant l'environnement d'une entreprise.

L'objectif principal est de mettre en œuvre les principales technologies utilisées dans les entreprises pour assurer la gestion des utilisateurs, des services réseau, de la sécurité et de la supervision de l'infrastructure.

L'environnement a été entièrement réalisé dans un laboratoire virtualisé à l'aide de VirtualBox, en intégrant plusieurs serveurs et postes clients afin de reproduire une architecture informatique professionnelle.

---

## 🎯 Objectifs du projet

- Concevoir une architecture réseau d'entreprise.
- Déployer un contrôleur de domaine Windows Server.
- Mettre en place Active Directory.
- Configurer les services DNS et DHCP.
- Sécuriser le réseau à l'aide du pare-feu pfSense.
- Déployer un serveur de supervision Zabbix.
- Superviser les serveurs, les postes clients et les équipements réseau.
- Intégrer les postes clients au domaine Active Directory.
- Configurer la supervision SNMP de pfSense.
- Simuler une infrastructure informatique complète et fonctionnelle.

---

## 🛠 Technologies utilisées

- Windows Server 2022
- Active Directory Domain Services (AD DS)
- Serveur DNS
- Serveur DHCP
- Ubuntu Server
- Zabbix 7
- pfSense Firewall
- VirtualBox
- SNMP
- ICMP
- Bash
- PowerShell

---

## 🏗 Architecture de l'infrastructure

Cette infrastructure comprend notamment :

- Un serveur Windows Server faisant office de contrôleur de domaine.
- Un serveur DNS.
- Un serveur DHCP.
- Un pare-feu pfSense assurant la sécurité et le routage.
- Un serveur Ubuntu hébergeant Zabbix.
- Des postes clients Windows et Linux.
- Une supervision centralisée de l'ensemble de l'infrastructure.
# 📸 Captures d'écran

## 🏗️ Architecture de l'infrastructure

Le schéma ci-dessous présente l'architecture globale de la plateforme de supervision mise en place avec Zabbix.

![](screenshots/Gemini_Generated_Image_kgg9tvkgg9tvkgg9.png)

---

## 🌐 Configuration de l'infrastructure réseau

### Serveur principal

![](screenshots/serveur.png)

### Configuration du protocole DHCP

![](screenshots/protocole.dhcp.png)

### Configuration de l'étendue DHCP (Scope)

![](screenshots/Configuration de l'étendue DHCP (Scope).png)

### Validation de l'attribution des adresses IP

![](screenshots/Validation de l'attribution d'une adresse IP par le serveur DHCP ....png)

---

## 🖥️ Configuration d'Active Directory

### Installation des services Active Directory (AD DS)

![](screenshots/Installation réussie d'Active Directory Domain Services (AD DS).png)

### Gestion des utilisateurs de l'OU IT

![](screenshots/Gestion des utilisateurs de l'OU IT.png)

### Intégration du poste client au domaine

![](screenshots/Client-USER-IHAB Joined to IHAB.local Domain.png)

---

## 🔥 Configuration de pfSense

### Accès à l'interface Web de pfSense

![](screenshots/Accès à l'interface Web de pfSense (WebConfigurator).png)

### Vérification de la connectivité entre pfSense et les clients

![](screenshots/vérification connxion pfsense avec client.png)

### Clients LAN connectés

![](screenshots/pfSense - Connected LAN Clients (User-IHAB, Finance & RH).png)

### Installation du service SNMP

![](screenshots/pfsense-net-snmp-installation.png.png)

### Intégration de pfSense dans Zabbix via SNMP

![](screenshots/pfsense-added-to-zabbix-via-snmp.png)

---

## 📊 Déploiement du serveur Zabbix

### Vérification du service Apache

![](screenshots/vérification apach.png)

### Vérification du service MariaDB

![](screenshots/vérification mariadb.png)

### Vérification du serveur Zabbix

![](screenshots/Vérification zabbix .png)

### Vérification de l'agent Zabbix

![](screenshots/vérification zabbix.agent.png)

---

## 🖥️ Ajout des hôtes supervisés

### Connexion des clients RH et FINANCE

![](screenshots/Connexion des clients RH et Finance au serveur Zabbix.png)

---

## 📈 Supervision des ressources

### Supervision du client FINANCE

![](screenshots/Surveillance des ressources système du client FINANCE dans Zabbix.png)

### Supervision du client RH

![](screenshots/Surveillance des ressources système du client RH dans Zabbix.png)

---

## 🚨 Mise en place des alertes

### Création du déclencheur CPU

![](screenshots/Création d'un déclencheur pour la surveillance du CPU.png)

### Création du script de remédiation automatique

![](screenshots/Création d'un script de correction automatique du CPU dans Zabbix.png)

### Création de l'action automatique

![](screenshots/Création d'une action pour exécuter automatiquement le script de correction CPU.png)

### Détection d'une surcharge CPU

![](screenshots/Déclenchement d'une alerte CPU lorsque l'utilisation dépasse 90....png)

### Résolution automatique du problème

![](screenshots/Exécution réussie de la remédiation automatique et résolution du problème CPU dans Zabbix....png)

---

## 📊 Tableau de bord

### Dashboard Zabbix

![](screenshots/Dashboard.png)
---

## 🚀 Fonctionnalités mises en œuvre

- Gestion centralisée des utilisateurs avec Active Directory.
- Création d'Unités d'Organisation (OU).
- Attribution automatique des adresses IP via DHCP.
- Résolution de noms grâce au serveur DNS.
- Sécurisation du réseau avec pfSense.
- Supervision des serveurs et des équipements avec Zabbix.
- Surveillance des performances CPU, mémoire et disponibilité des hôtes.
- Supervision SNMP du pare-feu pfSense.
- Génération d'alertes automatiques en cas d'incident.

---

## 💼 Compétences développées

- Administration Windows Server
- Active Directory
- Administration Linux
- Administration Réseau
- DNS
- DHCP
- Firewall pfSense
- Supervision avec Zabbix
- SNMP
- Virtualisation
- Déploiement d'infrastructure informatique
- Résolution de problèmes réseau

---

## ✅ Résultat

Ce projet démontre ma capacité à concevoir, déployer, sécuriser et superviser une infrastructure informatique complète, similaire à celle utilisée dans une entreprise.
Il met en pratique des compétences en administration systèmes, réseaux, sécurité et supervision, tout en respectant les bonnes pratiques professionnelles.
