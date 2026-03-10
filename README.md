Water 5 — Smart Irrigation App
Intelligence Artificielle pour l’irrigation agricole

Application Flutter permettant d’aider les agriculteurs à optimiser l’irrigation grâce à l’IA, aux capteurs et aux prévisions météo.

Développé dans le cadre du projet AgroIrri CI.

📱 Aperçu de l'application

Fonctionnalités principales :

📊 Dashboard intelligent

🌧 Prévisions météo agricoles

🌱 Analyse de l’humidité du sol

📈 Historique des décisions d’irrigation

🚨 Alertes et notifications SMS

⚙️ Paramétrage des capteurs et du modèle IA

🧠 Architecture du projet
water5/
├── lib/
│   ├── main.dart
│   │
│   ├── theme/
│   │   └── app_theme.dart
│   │
│   ├── models/
│   │   └── models.dart
│   │
│   ├── widgets/
│   │   └── common_widgets.dart
│   │
│   └── screens/
│       ├── splash_screen.dart
│       ├── loading_screen.dart
│       ├── main_screen.dart
│       ├── dashboard_screen.dart
│       ├── history_screen.dart
│       ├── alerts_screen.dart
│       └── settings_screen.dart
│
└── pubspec.yaml
🎨 Design System

Palette basée sur un vert agricole naturel.

Variable	Couleur	Usage
g300	#a8e063	Couleur principale
g700	#00a05a	Gradient
g800	#007542	Vert foncé
g900	#002a14	Texte
bg	#0a1a10	Fond
accent	#c8a96e	Or (notifications)
warn	#e05a3a	Alertes
sky	#6ec4d4	Informations météo
📦 Packages Flutter utilisés
Package	Utilisation
google_fonts	Typographie moderne
fl_chart	Graphiques
provider	Gestion d'état
shared_preferences	Stockage local
intl	Formatage dates
animate_do	Animations UI
📲 Écrans de l'application
Splash Screen

Logo animé et présentation de l'application.

Loading Screen

Chargement des services :

API météo

Connexion Arduino

Calcul ET₀

Modèle IA

Service SMS

Dashboard

Vue principale :

Décision d’irrigation

Métriques du sol

Prévisions météo

Graphiques agricoles

Historique

Historique des décisions :

Statistiques mensuelles

Liste chronologique

Visualisation graphique

Alertes

Gestion des alertes :

Notifications

SMS agriculteur

Alertes irrigation

Paramètres

Configuration :

Profil agriculteur

Parcelle

Capteurs Arduino

Modèle IA

⚙️ Installation
1️⃣ Installer Flutter

Installer le SDK Flutter :

https://flutter.dev/docs/get-started/install
2️⃣ Cloner le projet
git clone https://github.com/loicuriel663-maker/water_5.git
cd water5
3️⃣ Installer les dépendances
flutter pub get
4️⃣ Lancer l'application
flutter run
🏗 Build
Android
flutter build apk --release
iOS (macOS requis)
flutter build ios --release
Web
flutter build web --release
🔗 Intégration future
Backend IA

API Python avec FastAPI :

/decision
/history
/sensors
Capteurs

Connexion avec Arduino via USB :

flutter_libserialport
SMS

Africa's Talking

flutter_sms

Notifications
flutter_local_notifications
♿ Accessibilité

L'application respecte plusieurs principes d’accessibilité :

Semantics() sur les éléments interactifs

Contraste WCAG AA

Interface sombre optimisée

Support mode paysage

🌍 Contexte du projet

Projet développé pour améliorer l’agriculture intelligente en Côte d’Ivoire, en combinant :

intelligence artificielle

capteurs IoT

météo agricole

automatisation de l’irrigation

👨‍💻 Auteur

Uriel Loïc
Étudiant ingénieur informatique — INP-HB

📍 Yamoussoukro — Côte d’Ivoire

Projet : AgroIrri CI