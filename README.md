# 🛸 Startup LaunchPad

<p align="center">
  <img src="assets/images/logo.jpeg" width="120" alt="Logo" style="border-radius: 50%;">
</p>

<p align="center">
  <b>L'architecte de votre innovation.</b><br>
  [cite_start]Une expérience fluide pour transformer l'intuition en exécution réelle[cite: 4, 11].
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter">
  <img src="https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite">
  <img src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white" alt="Dart">
</p>

---

### 🖋️ Le Concept
[cite_start]**Startup LaunchPad** est une application mobile conçue pour lever les barrières entre l'idéation et l'exécution[cite: 4]. [cite_start]Elle permet aux innovateurs de centraliser leurs réflexions, de structurer leurs priorités et de visualiser l'avancement de leur projet à travers un environnement fluide et utilisable **100% hors-ligne**[cite: 6, 26].

---

### 🏗️ Ingénierie & Architecture
[cite_start]L'application repose sur une séparation stricte des préoccupations pour garantir performance et maintenabilité[cite: 104]:

| 💻 Stack Core | 📐 Patterns |
| :--- | :--- |
| [cite_start]**Framework:** Flutter [cite: 99] | [cite_start]**Architecture:** MVS (Modèle-Vue-Service) [cite: 104] |
| **Langage:** Dart | [cite_start]**State Management:** Provider / Riverpod / Bloc [cite: 102] |
| [cite_start]**Base de données:** SQLite [cite: 16, 70] | [cite_start]**Logic:** Repository Pattern [cite: 104] |
| [cite_start]**Analytics:** fl_chart [cite: 65] | [cite_start]**UI:** Kanban Design [cite: 14, 39] |

---

### 🕹️ Expérience Produit

#### 🧠 Gestion d'Idées Intelligente
* [cite_start]**Centralisation multidimensionnelle** : Organisation par catégories (Tech, Marketing, Business, Produit)[cite: 33].
* [cite_start]**Priorisation stratégique** : Système de tri par niveaux d'importance (Haute, Moyenne, Basse)[cite: 32, 84].
* [cite_start]**Moteur de recherche** : Indexation textuelle pour retrouver vos idées instantanément[cite: 38].

#### 📊 Écosystème Kanban
* [cite_start]**Flux dynamique** : Visualisation en 3 étapes : *Backlog*, *In Progress*, et *Done*[cite: 40, 41, 42, 43].
* [cite_start]**Gestion intuitive** : Mise à jour fluide des statuts via drag-and-drop ou boutons dédiés[cite: 45, 86].
* [cite_start]**Monitoring** : Compteurs d'activité intégrés pour chaque colonne de flux[cite: 47].

#### 📈 Roadmap & Analytics
* [cite_start]**Progression visuelle** : Monitoring global via des indicateurs circulaires et barres de progression[cite: 57, 63].
* [cite_start]**Insights** : Graphiques détaillés de la répartition des efforts par catégorie et priorité[cite: 61, 62].

---

### 📂 Anatomie du Code
```bash
lib/
├── database/     # Schémas et gestion SQLite (startup.db) [cite: 71]
├── models/       # Entités Ideas & Data Structures [cite: 104]
├── pages/        # Écrans Dashboard, Kanban & Roadmap [cite: 104]
├── repositories/ # Couche d'accès aux données persistantes [cite: 104]
├── services/     # Logique métier et calculs statistiques [cite: 104]
├── widgets/      # Composants UI atomiques et animations [cite: 104]
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
