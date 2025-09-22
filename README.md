# 🚀 TEMPLATE-BAP - Guide de Gestion de Projet GitHub

Salut les devs ! 👋 Bienvenue dans ce template spécialement conçu pour vos BAP. Ce repo va vous accompagner dans la découverte de la gestion de projet avec GitHub. (Apres avoir lu les readME [README](README.md) et [EXEMPLES_ISSUES](EXEMPLES_ISSUES.md), n'hésitez pas à supprimer ces fichiers une fois que vous avez compris leur contenu !)

## 📚 Qu'est-ce que c'est ?

Ce template est votre point de départ pour comprendre et maîtriser :
- 🔗 Le lien entre un repository GitHub et les outils de gestion de projet
- 📊 Les GitHub Projects et leur utilisation
- 🎯 Les bonnes pratiques de gestion de projet en équipe
- 🛠️ L'organisation du workflow de développement

> 💡 **Note importante :** Le template de projet GitHub "BAP-Template-projet" est déjà configuré par l'organisation IIM-CDI. Vous n'avez qu'à l'utiliser, pas besoin de tout recréer !
---

## 🛠️ Comment utiliser ce template ?

### 🚀 Étape 1 : Créer votre projet
1. Utilisez ce repository comme template (bouton "Use this template")
2. Créez un nouveau repository pour votre BAP
3. Allez dans l'onglet "Projects" de votre nouveau repo

### 📋 Étape 2 : Utiliser le template de projet de l'organisation
1. Cliquez sur "New project"
2. Sélectionnez le template **"BAP-Template-projet"** dans la liste
3. Le projet se crée automatiquement avec toute la structure ! 🎉

**✨ Tout est déjà configuré :**
- ✅ Les 7 colonnes du workflow BAP
- ✅ Les custom fields (Story Points, Durée, Difficulté, Dates)
- ✅ Les vues et filtres adaptés

### 🔗 Lier automatiquement votre repository au GitHub Project

Pour que toutes les issues et pull requests de votre repo soient ajoutées automatiquement à votre projet :

1. Ouvrez votre GitHub Project.
2. Cliquez sur **Workflows** (en haut à droite).
3. Dans le menu à gauche, sélectionnez **Auto-add to project**.
4. Cliquez sur les trois petits points (⋯) à droite de la règle.
5. Dans les **Filters**, choisissez le repository correspondant à votre projet.
6. Dans les critères, mettez : `is:issue,pr is:open`
7. Cliquez sur **Save and turn on**.

Ainsi, toutes les issues et PR ouvertes de votre repo seront ajoutées automatiquement à votre tableau de projet !

### 📝 Étape 3 : Créer vos premières issues
1. Cliquez sur "New issue" dans votre repository
2. Choisissez le template approprié (gestion, front-end, back-end, etc.)
3. Remplissez tous les champs (durée, difficulté, story points)
4. L'issue apparaîtra automatiquement dans votre projet !

### 🎯 Étape 4 : Organiser votre journée
- **Début de matiné** : Planifiez vos tâches dans "Pour jeudi prochain" et pour aujourd'hui
- **Pendant la matiné** : Déplacez vos tickets au fur et à mesure de l'avancement
- **Avant de finir** : Demandez une review puis marquez "Fini aujourd'hui"

---

## 🎯 GitHub Projects : Votre nouveau meilleur ami

### Qu'est-ce que GitHub Projects ?

GitHub Projects est l'outil intégré à GitHub qui vous permet de gérer vos projets directement depuis votre repository. Imaginez-le comme un tableau Kanban intelligent qui comprend votre code ! 🧠

### 🔗 Comment lier ce repo à un GitHub Project

1. **Utiliser le template existant** 
   - Allez sur l'onglet "Projects" de votre repository
   - Cliquez sur "New project"
   - Choisissez le template : **BAP-Template-projet** (déjà configuré par l'organisation)

2. **Lier automatiquement les issues et PR**
   - Vos issues et pull requests apparaîtront automatiquement
   - Vous pouvez les glisser-déposer entre les colonnes
   - Les statuts se mettent à jour en temps réel ! ⚡

✨ **Le template est déjà configuré avec :**
- Toutes les colonnes BAP
- Les custom fields (Story Points, Durée, Difficulté)  
- Les labels spécifiques aux projets étudiants

### 📋 Avantages du template BAP-Template-projet

🎯 **Tout est prêt à l'emploi :**
```
📂 Colonnes du projet :
├── 📋 Toutes les tâches (Vue d'ensemble complète)
├── 📅 Pour jeudi prochain (Objectifs à court terme)
├── 🎯 TO DO aujourd'hui (Focus du jour)
├── 🔄 En cours (Work in progress)
├── 👀 Review (En révision)
├── ✅ Fini aujourd'hui (Accomplissements du jour)
└── 🏆 Tâches finies du projet (Historique complet)
```

🎨 **Custom Fields pré-configurés :**
- **📊 Story Points** : Estimation de la complexité globale
- **⏱️ Durée** : Rapide (< 30 min) | Normal (30 min - 2h) | Long (> 2h)
- **🔧 Difficulté technique** : Simple | Moyen | Dur
- **📅 Dates** : Date de début et de fin pour le suivi

🏷️ **Labels spécifiques BAP :**
- 📋 `gestion de projet` | 🎨 `front-end` | ⚙️ `back-end` | 📚 `documentation` | 🔌 `iot`

## 🛠️ Les bases de la gestion de projet sur GitHub

### 1. Les Issues : Vos tâches structurées 📝

Les issues sont le cœur de votre organisation :

```markdown
**Exemple d'issue bien rédigée :**
Titre : [FEATURE] Ajouter un système de connexion utilisateur

## Description
Implémenter un système d'authentification pour permettre aux utilisateurs de se connecter.

## Acceptance Criteria
- [ ] Page de connexion avec formulaire
- [ ] Validation des données
- [ ] Redirection après connexion
- [ ] Gestion des erreurs

## Labels
- `feature`
- `priority-high`
- `frontend`
```

### 2. Les Labels : Votre système de catégorisation 🏷️

Utilisez les labels spécifiques aux BAP :
- � `gestion de projet` : Organisation, planification, suivi
- 🎨 `front-end` : Interface utilisateur, UX/UI  
- ⚙️ `back-end` : Serveur, API, base de données
- 📚 `documentation` : README, guides, commentaires
- 🔌 `iot` : Internet des objets, capteurs, hardware

### 💡 Exemples concrets d'utilisation

**📊 Story Points - Comment estimer ?**

Les story points fonctionnent sur la base de la suite de Fibonacci et permettent d'estimer la complexité relative des tâches :

```
1-2 points  : Petite correction, ajout simple
3-5 points  : Fonctionnalité moyenne, quelques heures de travail
8-13 points : Grosse fonctionnalité, plusieurs jours de travail
```

**⏱️ Exemple d'estimation de durée :**
```
"Rapide" : Corriger une typo, ajouter un bouton simple
"Normal" : Créer une page web basique, connecter un capteur  
"Long"   : Développer un système complet, intégration complexe
```

**🔧 Difficulté technique expliquée :**
```
"Simple" : Utiliser des connaissances déjà acquises
"Moyen"  : Apprendre 1-2 nouveaux concepts 
"Dur"    : Beaucoup de recherche, concepts avancés
```

**🎯 Exemple de workflow hebdomadaire :**
```
Jeudi matin : Planification pour la journée
Jeudi pendant la BAP : Focus jour → "TO DO aujourd'hui"
Jeudi fin de BAP : Finalisation → "Review" puis "Fini aujourd'hui"
```

### 3. Les Milestones : Vos objectifs à court terme 🎯

Organisez vos releases :
```
🏁 Sprint 1 (Semaine 1-2)
├── Setup du projet
├── Architecture de base
└── Première fonctionnalité

🏁 Sprint 2 (Semaine 3-4)
├── Interface utilisateur
├── Tests unitaires
└── Documentation
```

### 4. Les Assignees : Qui fait quoi ? 👥

- Assignez chaque tâche à un membre de l'équipe
- Une personne = une responsabilité claire
- Rotation des rôles pour l'apprentissage

---

## 🔄 Workflow de développement recommandé

### Le cycle de vie d'une feature

1. **📝 Création de l'issue**
   ```
   Quelqu'un identifie un besoin → Création d'une issue détaillée
   ```

2. **🎯 Planification**
   ```
   Issue ajoutée au projet → Assignation → Estimation
   ```

3. **🏗️ Développement**
   ```
   Création de branche → Développement → Commits réguliers
   ```

4. **🔍 Review**
   ```
   Pull Request → Review par les pairs → Corrections si nécessaire
   ```

5. **✅ Déploiement**
   ```
   Merge → Tests → Fermeture de l'issue → Célébration ! 🎉
   ```

### Conventions de nommage

**Branches :**
```
feature/nom-de-la-fonctionnalité
bugfix/description-du-bug
hotfix/correction-urgente
```

**Commits :**
```
feat: ajouter système de connexion
fix: corriger bug de validation
docs: mettre à jour le README
```

---

## 🎨 Personnaliser votre espace de travail

### Templates d'issues

Créez des templates dans `.github/ISSUE_TEMPLATE/` :

```yaml
# bug_report.yml
name: 🐛 Bug Report
description: Signaler un problème
body:
  - type: textarea
    attributes:
      label: Description du problème
      placeholder: Décrivez le bug rencontré...
```

### Automatisation avec GitHub Actions

```yaml
# .github/workflows/project-automation.yml
name: Project Automation
on:
  issues:
    types: [opened]
jobs:
  add-to-project:
    runs-on: ubuntu-latest
    steps:
      - name: Add issue to project
        # Automatically adds new issues to your project board
```

---

## 📈 Métriques et suivi

### Indicateurs à surveiller :

- 📊 **Vélocité** : Nombre de tâches terminées par sprint
- ⏱️ **Lead time** : Temps entre création et résolution d'une issue
- 🔄 **Cycle time** : Temps de développement effectif
- 🎯 **Burndown** : Progression vers les objectifs

### Rapports utiles :

📋 Daily standup questions :
1. Qu'est-ce que j'ai fait la semaine dernière ?
2. Qu'est-ce que je vais faire cette semaine ?
3. Y a-t-il des blocages ?

---

## 🚀 Tips pour les étudiants

### ✅ Bonnes pratiques

- **Soyez descriptifs** : Une issue claire = moins de malentendus
- **Communiquez** : Utilisez les commentaires pour tenir l'équipe informée
- **Itérez** : Petites tâches = feedback rapide = meilleur apprentissage
- **Documentez** : Votre futur vous dira merci ! 🙏

### ❌ Pièges à éviter

- Issues trop vagues ("Faire le site web" ❌)
- Branches qui vivent trop longtemps
- Oublier de lier les PR aux issues
- Ne pas mettre à jour le statut des tâches

### 🎓 Pour aller plus loin

- 📖 [GitHub Docs](https://docs.github.com/en/issues/planning-and-tracking-with-projects)
- 🎥 Tutoriels YouTube sur "GitHub Project Management"
- 💬 Discord de la promo pour partager vos découvertes !

---

## 🤝 Contribuer à ce template

Ce template évolue avec vos retours ! N'hésitez pas à :

1. 🍴 Fork ce repo
2. ✨ Proposer des améliorations
3. 📝 Partager vos expériences
4. 🐛 Signaler des problèmes

---

## 📞 Support

Besoin d'aide ? 
- 💬 Posez vos questions en issue
- 🤝 Demandez à vos camarades
- 📧 Contactez vos respos d'axes

---

**Happy coding ! 🎉**

> *"La gestion de projet, c'est comme cuisiner : avec les bons ingrédients et une bonne organisation, on obtient toujours un excellent résultat !"* 👨‍🍳

---

*Ce template a été créé avec ❤️ pour les étudiants de 2ème année de code 🦐*
