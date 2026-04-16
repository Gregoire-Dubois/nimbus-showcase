# nimbus-showcase
Application de monitoring d'applications d'entreprise - Stack Java 25 / Spring Boot / Angular 19

![Java](https://img.shields.io/badge/Java-25-orange)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.5-green)
![Angular](https://img.shields.io/badge/Angular-19-red)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-16-blue)
![Docker](https://img.shields.io/badge/Docker-Compose-2496ED)

## Contexte

L'application Nimbus a été pensée pour répondre à un besoin concret en entreprise.

Il arrive que les applications métiers tombent en panne et que les services de MCO (Maintien en Conditions Opérationnelles) doivent en être avertis au plus vite. De même, il est impératif de communiquer rapidement avec les équipes métiers impactées.

C'est dans cette optique que Nimbus a été conçue — mettre à disposition des administrateurs et des utilisateurs une interface épurée permettant de communiquer sur l'état des applications de l'entreprise.

> Projet personnel.

## Démonstration vidéo : 
https://youtu.be/rOWmt2hK0gc

## Aperçu

*Screenshots à venir*

## Fonctionnalités

**Côté utilisateur**
- Dashboard météo en temps réel (☀️ En ligne / 🌤️ Perturbé / 🌧️ Dégradé / ⛈️ En panne / 🔧 Maintenance)
- Signalement de pannes en un clic
- Retrait de signalement

**Côté administrateur**
- Gestion complète des applications (CRUD)
- Upload de logos applicatifs
- Forçage de statut (UP / DOWN / MAINTENANCE)
- Tableau de bord avec nombre de signalements en temps réel

## Stack technique

| Couche | Technologie |
|--------|------------|
| Backend | Java 25, Spring Boot 3.5 |
| Persistance | Spring Data JPA, PostgreSQL 16 |
| Frontend | Angular 19, Tailwind CSS v3 |
| Infra dev | Docker Compose |

## Architecture

- **Backend** : Architecture MVC — API REST
- **Frontend** : Architecture feature-based Angular
- **Authentification** : SSO Microsoft Entra ID *(roadmap)*

## Roadmap

- [ ] SSO (login/logout, gestion des rôles)
- [ ] WebSocket STOMP pour les mises à jour en temps réel
- [ ] Dockerisation complète (front + back + PostgreSQL)
- [ ] Calcul météo basé sur ratio signalements/utilisateurs connectés
- [ ] Système de licence par client
