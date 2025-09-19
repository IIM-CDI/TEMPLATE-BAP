# 📚 Exemples d'Issues BAP

Ce fichier contient des exemples d'issues bien rédigées pour chaque type de tâche BAP.

## 📋 Exemple : Gestion de Projet

**Titre :** [GESTION] Organiser le planning Sprint 1

**Description :**
Planifier le premier sprint du projet BAP en définissant les objectifs, répartissant les tâches et fixant les deadlines pour l'équipe.

**Durée :** Normal (30 min - 2h)
**Difficulté :** Simple
**Story Points :** 3
**Date limite :** jeudi 26/09/2025

**Critères d'acceptance :**
- [ ] Planning défini avec dates claires
- [ ] Tâches réparties équitablement dans l'équipe
- [ ] Objectifs SMART définis pour le sprint
- [ ] Réunion de lancement organisée

---

## 🎨 Exemple : Front-End

**Titre :** [FRONT] Créer la page d'accueil responsive

**Description :**
Développer la page d'accueil de l'application avec un design responsive qui s'adapte aux mobiles et tablettes.

**Durée :** Long (> 2h)
**Difficulté :** Moyen
**Story Points :** 8
**Date limite :** vendredi 27/09/2025

**Technologies :** HTML5, CSS3, JavaScript, Bootstrap
**Maquette :** [Lien Figma](https://figma.com/exemple)

**Critères d'acceptance :**
- [ ] Design responsive (mobile, tablette, desktop)
- [ ] Navigation fonctionnelle
- [ ] Images optimisées
- [ ] Validation W3C passée
- [ ] Tests sur différents navigateurs

---

## ⚙️ Exemple : Back-End

**Titre :** [BACK] Implémenter l'API d'authentification

**Description :**
Créer les endpoints d'authentification pour permettre aux utilisateurs de s'inscrire, se connecter et gérer leur session.

**Durée :** Long (> 2h)
**Difficulté :** Dur
**Story Points :** 13
**Type :** API/Endpoints

**Technologies :** Node.js, Express, JWT, bcrypt, MongoDB

**Endpoints à créer :**
- POST /api/auth/register
- POST /api/auth/login
- GET /api/auth/profile
- POST /api/auth/logout

**Critères d'acceptance :**
- [ ] Inscription utilisateur fonctionnelle
- [ ] Connexion avec JWT
- [ ] Mots de passe hashés (bcrypt)
- [ ] Validation des données d'entrée
- [ ] Tests unitaires écrits
- [ ] Documentation API mise à jour

---

## 📚 Exemple : Documentation

**Titre :** [DOC] Rédiger le guide d'installation

**Description :**
Créer un guide complet d'installation du projet pour permettre à de nouveaux développeurs de configurer rapidement l'environnement.

**Durée :** Normal (30 min - 2h)
**Difficulté :** Simple
**Story Points :** 3
**Type :** Guide d'installation

**Public cible :** Nouveaux développeurs de l'équipe

**Contenu à couvrir :**
- Prérequis système
- Installation des dépendances
- Configuration de la base de données
- Variables d'environnement
- Commandes de lancement
- FAQ troubleshooting

**Critères d'acceptance :**
- [ ] Instructions claires et testées
- [ ] Captures d'écran incluses
- [ ] Section troubleshooting
- [ ] Validation par un membre de l'équipe
- [ ] Liens vers ressources externes

---

## 🔌 Exemple : IoT

**Titre :** [IOT] Connecter capteur de température DHT22

**Description :**
Implémenter la lecture d'un capteur de température DHT22 avec un Arduino et transmettre les données via WiFi.

**Durée :** Normal (30 min - 2h)
**Difficulté :** Moyen
**Story Points :** 5
**Type :** Capteurs/Sensors

**Matériel nécessaire :**
- Arduino Uno
- Capteur DHT22
- Module WiFi ESP8266
- Résistance 10kΩ
- Breadboard et câbles

**Technologies :** C++, Arduino IDE, WiFi library

**Schéma :** [Lien Fritzing](https://fritzing.org/exemple)

**Critères d'acceptance :**
- [ ] Capteur connecté et fonctionnel
- [ ] Lecture température/humidité précise
- [ ] Transmission WiFi opérationnelle
- [ ] Code commenté et documenté
- [ ] Tests physiques validés
- [ ] Gestion des erreurs de connexion

---

## 🎯 Conseils pour bien rédiger vos issues

### ✅ Bonnes pratiques

1. **Titre explicite** : Utilisez le préfixe [TYPE] et soyez précis
2. **Description détaillée** : Expliquez le pourquoi et le comment
3. **Estimation réaliste** : N'hésitez pas à surestimer plutôt que sous-estimer
4. **Critères mesurables** : Utilisez des checkboxes pour les critères d'acceptance
5. **Contexte technique** : Précisez les technologies et contraintes

### ❌ Erreurs à éviter

1. **Titre vague** : ❌ "Faire le front" → ✅ "[FRONT] Créer la page de connexion"
2. **Pas d'estimation** : Toujours remplir durée, difficulté et story points
3. **Critères flous** : ❌ "Ça marche" → ✅ "Tests utilisateur validés"
4. **Trop ambitieux** : Divisez les grosses tâches en sous-tâches
5. **Oublier les dépendances** : Mentionnez les prérequis

### 📊 Guide d'estimation

**Story Points (complexité globale) :**
- 1-2 : Très simple, < 30 min
- 3-5 : Simple à moyen, 30 min - 2h
- 8 : Complexe, > 2h mais reste dans la journée
- 13 : Très complexe, plusieurs sessions de travail

**Durée vs Difficulté :**
- Rapide + Simple = petite correction, ajout mineur
- Normal + Moyen = développement standard d'une fonctionnalité
- Long + Dur = fonctionnalité majeure nécessitant recherche

**Conseils par domaine :**
- **Gestion** : Focus sur les livrables et deadlines
- **Front-end** : Pensez responsive et accessibilité
- **Back-end** : Sécurité et performance sont critiques
- **Documentation** : Clarity is king, testez vos instructions
- **IoT** : Prévoyez du temps pour les tests physiques

---

*Ces exemples sont là pour vous guider. Adaptez-les à votre contexte de projet ! 🚀*