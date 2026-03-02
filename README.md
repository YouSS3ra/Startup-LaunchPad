Startup LaunchPad

<p align="center">
<img src="assets/images/logo.jpeg" width="150" alt="Startup LaunchPad Logo" style="border-radius: 20px;">
</p>

<p align="center">
<strong>L'outil ultime pour transformer vos idées en Roadmaps concrètes.</strong>


<i>Built with Flutter & SQLite — Designed for Entrepreneurs.</i>
</p>
✨ Vision du Projet

Startup LaunchPad est une application mobile conçue pour lever les barrières entre l'idéation et l'exécution. Elle permet aux innovateurs de centraliser leurs réflexions, de structurer leurs priorités et de visualiser l'avancement de leur projet à travers un environnement fluide et utilisable 100% hors-ligne.
🛠️ Stack Technique & Architecture

L'application repose sur une séparation stricte des préoccupations pour garantir performance et maintenabilité :

<table>
<tr>
<td width="50%">
<h3>Core Tech</h3>
<ul>
<li><b>Framework:</b> Flutter</li>
<li><b>Langage:</b> Dart</li>
<li><b>Local DB:</b> SQLite (startup.db)</li>
<li><b>Charts:</b> fl_chart</li>
</ul>
</td>
<td width="50%">
<h3>Architecture</h3>
<ul>
<li><b>Pattern:</b> Modèle-Vue-Service (MVS)</li>
<li><b>State Management:</b> Provider / Riverpod</li>
<li><b>Logic:</b> Repository Pattern</li>
</ul>
</td>
</tr>
</table>
📋 Fonctionnalités Clés
🧠 Gestion d'Idées Intelligente

    Centralisation par catégories : Tech, Marketing, Business, Produit.

    Système de tri par priorité (Haute, Moyenne, Basse).

    Recherche textuelle ultra-rapide.

📊 Tableau Kanban Dynamique

    Visualisation du flux de travail en 3 étapes : Backlog, In Progress, Done.

    Mise à jour intuitive des statuts.

    Compteurs d'avancement en temps réel.

📈 Roadmap & Analytics

    Progression globale du projet via des barres et cercles interactifs.

    Graphiques détaillés de la répartition des efforts.

    Historique des activités récentes.

📂 Organisation du Code
Plaintext

lib/
├── database/     # Configuration & Requêtes SQLite
├── models/       # Entités Ideas, Categories, Stats
├── pages/        # UI Screens (Kanban, Dashboard, Roadmap)
├── repositories/ # Abstraction de la manipulation de données
├── services/     # Logique métier & Services internes
├── widgets/      # Composants UI réutilisables (Cards, Badges)
└── main.dart     # Point d'entrée & State Management

📱 Aperçu Visuel

<p align="center">
<img src="assets/images/startup_splash.jpg" width="200" alt="Splash Screen">
<img src="assets/images/splash_page1.jpg" width="200" alt="Intro 1">
<img src="assets/images/splash_page2.jpg" width="200" alt="Intro 2">
</p>
⚙️ Installation
Bash

# Cloner le projet
git clone https://github.com/votre-pseudo/startup-launchpad.git

# Installer les dépendances
flutter pub get
# Lancer l'application
flutter run
