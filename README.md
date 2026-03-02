# 🛸 Startup LaunchPad

<p align="center">
  <img src="assets/images/logo.jpeg" width="120" alt="Logo" style="border-radius: 50%;">
</p>

<p align="center">
  <b>L'architecte de votre innovation.</b><br>
  Une expérience fluide pour transformer l'intuition en exécution réelle.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter">
  <img src="https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite">
  <img src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white" alt="Dart">
</p>

---

### 🖋️ Le Concept
**Startup LaunchPad** est une application mobile conçue pour lever les barrières entre l'idéation et l'exécution. Elle permet aux innovateurs de centraliser leurs réflexions, de structurer leurs priorités et de visualiser l'avancement de leur projet à travers un environnement fluide et utilisable **100% hors-ligne**.

---

### 🏗️ Ingénierie & Architecture
L'application repose sur une séparation stricte des préoccupations pour garantir performance et maintenabilité:

| 💻 Stack Core | 📐 Patterns |
| :--- | :--- |
| **Framework:** Flutter |**Architecture:** MVS (Modèle-Vue-Service) |
| **Langage:** Dart | **State Management:** Provider / Riverpod / Bloc  |
| **Base de données:** SQLite | **Logic:** Repository Pattern  |
| **Analytics:** fl_chart | **UI:** Kanban Design |

---

### 🕹️ Expérience Produit

#### 🧠 Gestion d'Idées Intelligente
* **Centralisation multidimensionnelle** : Organisation par catégories (Tech, Marketing, Business, Produit).
* **Priorisation stratégique** : Système de tri par niveaux d'importance (Haute, Moyenne, Basse).
* **Moteur de recherche** : Indexation textuelle pour retrouver vos idées instantanément.

#### 📊 Écosystème Kanban
* **Flux dynamique** : Visualisation en 3 étapes : *Backlog*, *In Progress*, et *Done*.
* **Gestion intuitive** : Mise à jour fluide des statuts via drag-and-drop ou boutons dédiés.
* **Monitoring** : Compteurs d'activité intégrés pour chaque colonne de flux.

#### 📈 Roadmap & Analytics
* **Progression visuelle** : Monitoring global via des indicateurs circulaires et barres de progression.
* **Insights** : Graphiques détaillés de la répartition des efforts par catégorie et priorité.

---

### 📂 Anatomie du Code
```bash
lib/
├── database/     # Schémas et gestion SQLite (startup.db) 
├── models/       # Entités Ideas & Data Structures 
├── pages/        # Écrans Dashboard, Kanban & Roadmap 
├── repositories/ # Couche d'accès aux données persistantes 
├── services/     # Logique métier et calculs statistiques 
├── widgets/      # Composants UI atomiques et animations 
└── main.dart     # Point d'entrée & State Management
```
### 📱 Aperçu de l'Expérience

#### 🏗️ Démonstration Interactive
<p align="center">
  <img src="assets/images/kanban_gif.gif" width="250" alt="Démo Kanban">
</p>

#### 🎨 Onboarding & Authentification
<p align="center">
  <img src="assets/images/splash_screen.jpeg" width="200" style="margin: 5px">
  <img src="assets/images/signin.jpeg" width="200" style="margin: 5px">
  <img src="assets/images/signup.jpeg" width="200" style="margin: 5px">
</p>

#### 📊 Dashboard & Pilotage
<p align="center">
  <img src="assets/images/home_page.jpeg" width="200" style="margin: 5px">
  <img src="assets/images/statistics.jpeg" width="200" style="margin: 5px">
  <img src="assets/images/roadmap.jpeg" width="200" style="margin: 5px">
</p>

<details>
  <summary>📸 Voir la galerie complète (Interface détaillée)</summary>
  <br>
  <p align="center">
    <img src="assets/images/kanban_backlog.jpeg" width="180" title="Backlog">
    <img src="assets/images/kanban_en cours.jpeg" width="180" title="En cours">
    <img src="assets/images/kanban_terminé.jpeg" width="180" title="Terminé">
    <img src="assets/images/list_idea_page.jpeg" width="180" title="Liste">
    <img src="assets/images/new_idea_page.jpeg" width="180" title="Ajout">
    <img src="assets/images/history.jpeg" width="180" title="Historique">
    <img src="assets/images/profil.jpeg" width="180" title="Profil">
    <img src="assets/images/parametres.jpeg" width="180" title="Paramètres">
  </p>
</details>

<p align="center">Développé avec ❤️ par l'équipe Startup LaunchPad</p>
