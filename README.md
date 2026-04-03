# 🏛️ Association & Stadium Management System

Une plateforme web intégrée conçue pour la gestion administrative d'une association et la gestion automatisée des réservations d'un stade ou complexe sportif. Ce projet digitalise le suivi des membres, la participation aux activités et la planification des matchs.

---

## 🌟 Fonctionnalités Principales

### 👤 Gestion des Membres & Administration
- **Système d'Authentification :** Accès sécurisé multi-rôles (Admin, Bureau, Membre, Client).
- **Dashboard Statistique :** Visualisation en temps réel des indicateurs de performance (KPIs).
- **Suivi de Participation :** Interface dynamique pour marquer la présence/absence aux réunions et activités associatives.
- **Calcul Automatique :** Génération des taux de participation mensuels et annuels.

### ⚽ Module de Réservation de Stade (Stadium Booking)
- **Planning Interactif :** Calendrier en temps réel pour visualiser les créneaux disponibles et réservés.
- **Gestion des Matchs :** Système de réservation pour les utilisateurs (particuliers ou clubs).
- **Tarification Dynamique :** Gestion des prix selon les créneaux (Heures pleines/creuses, éclairage nocturne).
- **Suivi des Revenus :** Reporting sur les recettes générées par les locations du terrain.

---

## 📊 Aperçu des Indicateurs (KPIs)
L'application centralise les données pour une prise de décision rapide :
- **Engagement des membres :** Taux de participation cible de 80%.
- **Taux d'occupation :** Analyse de l'utilisation du stade par semaine/mois.
- **Suivi budgétaire :** Équilibre entre les coûts des activités et les revenus des réservations.
- **Impact social :** Nombre de bénéficiaires et de sportifs enregistrés.

---

## 🛠️ Stack Technique

- **Frontend :** React.js / Tailwind CSS (Interface moderne et Responsive).
- **Backend :** Spring Boot (Java 17) / Hibernate (Architecture REST).
- **Base de données :** MySQL / PostgreSQL.
- **Sécurité :** Spring Security & JWT (Authentification sécurisée).
- **Planning :** FullCalendar ou librairie personnalisée pour la grille horaire.
- **Charts :** Chart.js ou Recharts pour les statistiques.

---

## ⚙️ Installation

### 1. Prérequis
- Java 17+
- Node.js & NPM
- MySQL

### 2. Backend (Spring Boot)
```bash
# Configurer la DB dans src/main/resources/application.properties
./mvnw clean install
./mvnw spring-boot:run
