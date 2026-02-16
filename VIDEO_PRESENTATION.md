# Nexarena - Script de Présentation Vidéo

## 📹 Durée suggérée : 5-7 minutes

---

## 🎬 INTRO (30 secondes)

### Visuels à montrer
- Logo Nexarena
- Animation d'ouverture dynamique
- URL du site web

### Script vocal
> "Bonjour et bienvenue ! Aujourd'hui, je vous présente **Nexarena**, une plateforme complète de classement et de gestion de serveurs de jeux vidéo. Développée avec Symfony 7.4 et PHP 8.3, Nexarena offre une solution moderne et performante pour les communautés gaming."

---

## 🏠 PARTIE 1 : PAGE D'ACCUEIL ET DÉCOUVERTE (1 minute)

### Visuels à montrer
- Page d'accueil avec animations
- Top 3 des serveurs du mois
- Grille des catégories de jeux
- Barre des partenaires
- Thèmes visuels variés

### Script vocal
> "La page d'accueil met en avant le Top 3 des serveurs les plus votés du mois, ainsi qu'une sélection de serveurs mis en vedette. Les utilisateurs peuvent naviguer facilement parmi les différentes catégories : Minecraft, FiveM, Rust, CS2, GMod, et bien d'autres."

### Points clés à mentionner
- Navigation intuitive
- Design moderne et attractif
- Catégorisation claire des serveurs

---

## 🎮 PARTIE 2 : FONCTIONNALITÉS PRINCIPALES (2 minutes)

### A. Système de Classement (30 secondes)

#### Visuels
- Page de classement par catégorie
- Détails d'un serveur
- Statistiques de votes

#### Script
> "Le cœur de Nexarena est son système de classement. Les serveurs sont classés par nombre de votes mensuels. Les joueurs peuvent voter pour leurs serveurs préférés via OAuth Discord ou Steam, avec un système anti-triche incluant la détection de VPN."

### B. Pages Serveur Personnalisables (40 secondes)

#### Visuels
- Onglet Information (bannière, description, liens sociaux)
- Onglet Serveur (joueurs en ligne, statut temps réel)
- Onglet Avis
- Démonstration de 3-4 thèmes différents (Minecraft, FiveM, Cyberpunk, Ocean)

#### Script
> "Chaque serveur dispose d'une page dédiée avec 3 onglets. L'onglet Information affiche la bannière personnalisée, la description enrichie et les liens sociaux. L'onglet Serveur interroge le serveur en temps réel pour afficher le nombre de joueurs connectés et leur liste. Et ce qui est vraiment unique : 25 thèmes visuels différents sont disponibles pour personnaliser l'apparence de chaque page serveur !"

### C. Requêtes en Temps Réel (30 secondes)

#### Visuels
- Serveur CFX (FiveM) en ligne avec liste de joueurs
- Serveur Minecraft avec statistiques
- Auto-rafraîchissement en action

#### Script
> "Nexarena interroge automatiquement les serveurs de jeux toutes les 60 secondes. Compatible avec les protocoles CFX pour FiveM et RedM, Source Engine pour CS2, Rust et GMod, ainsi que Minecraft SLP. Les joueurs voient en temps réel qui est connecté."

### D. Widgets Embarquables (20 secondes)

#### Visuels
- Configurateur de widget avec aperçu
- Code d'intégration
- Widget carte serveur embarqué

#### Script
> "Les propriétaires de serveurs peuvent générer des widgets personnalisables pour les intégrer sur leurs sites externes. Configuration visuelle complète : couleurs, mode sombre/clair, border-radius, et aperçu en direct."

---

## 👥 PARTIE 3 : SYSTÈME DE RECRUTEMENT (1 minute 30)

### A. Pour les Serveurs (45 secondes)

#### Visuels
- Liste des offres de recrutement
- Création d'une offre
- Constructeur de formulaire dynamique (drag & drop)
- Formulaire avec différents types de champs

#### Script
> "Le système de recrutement permet aux serveurs de publier des offres d'emploi ou de recrutement de staff. Les gestionnaires créent des formulaires dynamiques avec un constructeur visuel : texte, zones de texte, sélections, cases à cocher, emails, nombres... Jusqu'à 20 champs personnalisables."

### B. Pour les Candidats (45 secondes)

#### Visuels
- Liste publique des offres
- Formulaire de candidature
- Dashboard candidat avec statuts (En attente, Acceptée, Refusée)
- Chat en temps réel avec le gestionnaire

#### Script
> "Les candidats parcourent les offres publiques et soumettent leur candidature. Ils peuvent suivre l'état de leurs candidatures depuis leur espace personnel. Si le gestionnaire active le chat, une messagerie en temps réel permet d'échanger directement. Les notifications alertent chaque partie des nouveaux messages."

---

## 🛠️ PARTIE 4 : GESTION COLLABORATIVE (45 secondes)

### Visuels
- Mes serveurs
- Ajout d'un collaborateur
- Interface de gestion des permissions (9 permissions)
- Actions d'un collaborateur

### Script
> "Un serveur peut avoir jusqu'à 10 collaborateurs avec des permissions granulaires : modifier les informations, gérer les images, les liens sociaux, le thème, l'API, les webhooks, le statut, modérer les commentaires, ou même supprimer le serveur. Chaque collaborateur voit uniquement ce qu'il est autorisé à gérer."

---

## 🔧 PARTIE 5 : ADMINISTRATION (1 minute)

### A. Dashboard Admin (20 secondes)

#### Visuels
- Dashboard avec statistiques
- Graphiques (serveurs par catégorie, inscriptions, votes)
- Tableaux des utilisateurs et articles récents

#### Script
> "Le back-office offre un dashboard complet avec statistiques en temps réel, graphiques interactifs Chart.js, et vues d'ensemble des utilisateurs et contenus récents."

### B. Gestion de Contenu (20 secondes)

#### Visuels
- Gestion des serveurs (approbation, activation)
- Gestion des articles de blog
- Modération des commentaires signalés

#### Script
> "Les administrateurs approuvent les nouveaux serveurs, modèrent les commentaires signalés, gèrent les offres de recrutement, et publient des articles de blog. Système complet de modération avec workflow d'approbation."

### C. Configuration Avancée (20 secondes)

#### Visuels
- Paramètres du site (118 paramètres, 14 catégories)
- Gestion des rôles et permissions (21 permissions)
- Upload d'images pour les 25 thèmes

#### Script
> "118 paramètres configurables répartis en 14 catégories permettent de personnaliser entièrement le site : SEO, réseaux sociaux, API, sécurité, contenu légal. Un système de rôles hiérarchiques avec 21 permissions granulaires contrôle l'accès aux fonctionnalités."

---

## 🔐 PARTIE 6 : SÉCURITÉ ET AUTHENTIFICATION (30 secondes)

### Visuels
- Page de connexion avec OAuth
- Configuration 2FA (QR code)
- Badges OAuth (Google, Discord, Twitch, Steam)

### Script
> "L'authentification supporte 4 providers OAuth : Google, Discord, Twitch et Steam, avec liaison automatique des comptes. L'authentification à deux facteurs TOTP renforce la sécurité. Throttling de connexion, détection VPN, et validation stricte des uploads protègent la plateforme."

---

## 💻 PARTIE 7 : STACK TECHNIQUE (30 secondes)

### Visuels
- Logo Symfony, PHP, MariaDB
- Structure du projet (arborescence)
- Code source (aperçu propre)

### Script
> "Techniquement, Nexarena repose sur Symfony 7.4, PHP 8.3, et MariaDB 11.8. L'architecture inclut 19 entités Doctrine, 15 services métier, 9 extensions Twig, et une API REST complète. Le code suit les meilleures pratiques Symfony avec une séparation claire des responsabilités."

### Points clés à afficher
```
Stack:
• Symfony 7.4
• PHP 8.3+
• MariaDB 11.8+
• OAuth2 (Google, Discord, Twitch, Steam)
• 2FA TOTP
• Chart.js pour graphiques
• Quill.js pour éditeur riche
```

---

## 🚀 PARTIE 8 : API ET INTÉGRATIONS (30 secondes)

### Visuels
- Documentation API
- Exemple de requête API (cURL ou Postman)
- Webhook de vote (payload JSON)
- Scan VirusTotal d'un plugin

### Script
> "L'API REST permet aux serveurs de vérifier les votes, récupérer des statistiques et la liste des meilleurs votants. Les webhooks notifient automatiquement le serveur à chaque vote avec signature HMAC-SHA256. Les plugins uploadés sont automatiquement scannés via VirusTotal."

---

## 📊 PARTIE 9 : FONCTIONNALITÉS BONUS (30 secondes)

### Visuels rapides
- Catalogue de plugins (Minecraft, FiveM, GMod, Discord, TeamSpeak)
- Blog/Actualités avec éditeur Quill
- Partenaires et services
- Système de notifications (cloche avec badge)

### Script
> "D'autres fonctionnalités enrichissent la plateforme : un catalogue de plugins téléchargeables pour différentes plateformes, un blog intégré pour les actualités, une barre de partenaires personnalisable, et un système complet de notifications in-app avec polling en temps réel."

---

## 🎯 CONCLUSION (30 secondes)

### Visuels
- Montage rapide des meilleurs écrans
- Statistiques impressionnantes (nombre de fonctionnalités, lignes de code, etc.)
- Call-to-action

### Script vocal
> "Nexarena, c'est plus de 25 fonctionnalités majeures, 25 thèmes personnalisables, 9 permissions granulaires, et une architecture robuste pensée pour la scalabilité. Que vous soyez propriétaire de serveur, joueur, ou administrateur de plateforme, Nexarena offre une expérience complète et moderne. Merci de votre attention !"

### Texte à afficher
```
✨ Nexarena en chiffres :
• 25 thèmes visuels
• 4 providers OAuth
• 19 entités Doctrine
• 15 services métier
• 118 paramètres configurables
• 21 permissions
• Support multi-protocoles (CFX, Source, Minecraft)
```

---

## 🎨 CONSEILS DE RÉALISATION

### Outils recommandés
- **Enregistrement écran** : OBS Studio, Camtasia, ScreenFlow
- **Montage vidéo** : DaVinci Resolve, Adobe Premiere Pro, Final Cut Pro
- **Voix off** : Audacity pour l'enregistrement, micro de qualité
- **Musique de fond** : Epidemic Sound, Artlist (musique libre de droits, volume bas)

### Techniques visuelles
1. **Zoom et highlights** : Zoomer sur les éléments importants
2. **Annotations** : Ajouter des flèches et textes pour guider l'attention
3. **Transitions fluides** : Éviter les coupures brusques
4. **Curseur visible** : Montrer où vous cliquez
5. **Vitesse** : Accélérer légèrement les parties répétitives (x1.2-1.5)

### Conseils audio
- Parler clairement et à rythme modéré
- Faire des pauses entre les parties
- Musique de fond à 15-20% du volume de la voix
- Éviter les bruits parasites

### Structure vidéo finale
```
00:00 - Intro + Logo
00:30 - Page d'accueil
01:30 - Fonctionnalités principales
03:30 - Système de recrutement
05:00 - Gestion collaborative
05:45 - Administration
06:45 - Sécurité
07:15 - Stack technique
07:45 - API
08:15 - Fonctionnalités bonus
08:45 - Conclusion
```

---

## 📝 CHECKLIST DE TOURNAGE

### Préparation
- [ ] Installer Nexarena en local ou sur un serveur de démo
- [ ] Créer des données de test variées :
  - [ ] 10-15 serveurs avec différentes catégories
  - [ ] Plusieurs thèmes appliqués
  - [ ] Offres de recrutement avec candidatures
  - [ ] Commentaires et avis
  - [ ] Votes de test
- [ ] Configurer tous les OAuth providers (ou utiliser des captures existantes)
- [ ] Préparer des comptes utilisateur avec différents rôles
- [ ] Nettoyer l'interface (pas d'erreurs, pas de texte de debug)

### Enregistrement
- [ ] Fermer les applications inutiles
- [ ] Désactiver les notifications
- [ ] Utiliser un navigateur propre (mode incognito ou profil dédié)
- [ ] Régler la résolution à 1920x1080 minimum
- [ ] Tester l'audio avant d'enregistrer
- [ ] Faire plusieurs prises si nécessaire

### Post-production
- [ ] Couper les moments d'hésitation
- [ ] Ajouter des transitions entre les parties
- [ ] Insérer les textes et annotations
- [ ] Ajuster les niveaux audio
- [ ] Ajouter une intro et outro
- [ ] Exporter en 1080p ou 4K

---

## 🌐 DIFFUSION

### Plateformes recommandées
- **YouTube** : Plateforme principale, SEO optimisé
- **Vimeo** : Version professionnelle
- **GitHub** : Lien dans le README
- **Site web** : Embed sur la page d'accueil

### Optimisation SEO
**Titre** : "Nexarena - Plateforme complète de classement de serveurs de jeux | Démo & Présentation"

**Description** :
```
Découvrez Nexarena, la plateforme ultime pour le classement et la gestion de serveurs de jeux vidéo.

⭐ Fonctionnalités principales :
• Classement de serveurs avec système de votes sécurisé
• 25 thèmes visuels personnalisables
• Requêtes en temps réel (CFX, Source Engine, Minecraft)
• Système de recrutement avec formulaires dynamiques
• Gestion collaborative avec 9 permissions
• Widgets embarquables configurables
• API REST complète
• Authentification OAuth (Google, Discord, Twitch, Steam)
• 2FA TOTP

🛠️ Stack technique :
Symfony 7.4 | PHP 8.3 | MariaDB | OAuth2 | Chart.js | Quill.js

🔗 Repository GitHub : https://github.com/Jack62300/nexarea_website

#Symfony #PHP #Gaming #ServerRanking #GameServers #WebDevelopment #OpenSource
```

**Tags** : Symfony, PHP, Gaming, Server Ranking, FiveM, Minecraft, Game Servers, Web Development, OAuth, API

---

## 📄 VARIANTES POSSIBLES

### Version courte (2-3 minutes)
Focus uniquement sur :
1. Intro (15s)
2. Page d'accueil + classement (30s)
3. Pages serveur avec thèmes (45s)
4. Système de recrutement (30s)
5. Dashboard admin (30s)
6. Conclusion (15s)

### Version longue (10-15 minutes)
Ajouter :
- Démonstration complète de création de serveur
- Workflow complet d'une candidature
- Configuration détaillée des permissions
- Démonstration de l'API avec exemples
- Installation et déploiement

### Version technique (pour développeurs)
Focus sur :
- Architecture Symfony
- Structure du code
- Services et repositories
- API endpoints détaillés
- Commandes console
- Extensions Twig
- Sécurité et performances

---

## 📞 CONTACT ET SUPPORT

Pour toute question sur la réalisation de cette vidéo ou sur le projet Nexarena, consultez :
- **Repository** : https://github.com/Jack62300/nexarea_website
- **Documentation** : README.md et FONCTIONNALITES.md
- **Issues** : GitHub Issues

Bonne réalisation ! 🎬
