# Guide de Contribution

## Conventions de Commits 📝

Ce projet utilise la [convention Conventional Commits](https://www.conventionalcommits.org/) pour maintenir un historique de commits propre et génerer automatiquement les changelogs.

**⚠️ Important : La vérification se fait uniquement via GitHub Actions. Aucune installation locale n'est requise.**

### Format
```
<type>[optional scope]: <description>

[optional body]

[optional footer(s)]
```

### Types autorisés

| Type | Description | Exemple |
|------|-------------|---------|
| `feat` | Nouvelle fonctionnalité | `feat(auth): add login system` |
| `fix` | Correction de bug | `fix(api): handle null responses` |
| `docs` | Documentation | `docs: update installation guide` |
| `style` | Style de code (formatage) | `style: fix indentation` |
| `refactor` | Refactorisation | `refactor(db): optimize queries` |
| `test` | Tests | `test: add user service tests` |
| `chore` | Maintenance | `chore: update dependencies` |
| `perf` | Performance | `perf: improve loading time` |
| `ci` | CI/CD | `ci: add GitHub Actions workflow` |
| `build` | Build system | `build: configure webpack` |
| `revert` | Annulation | `revert: remove broken feature` |

### Règles importantes

✅ **À faire :**
- Utiliser l'impératif présent ("add" pas "added")
- Commencer par une minuscule après le type
- Garder la première ligne sous 72 caractères
- Être spécifique et descriptif

❌ **À éviter :**
- Messages vagues ("fix stuff", "update code")
- Point final dans le sujet
- Majuscule après le type
- Mélanger plusieurs types de changements

### Exemples complets

**Simple :**
```
feat(user): add profile picture upload
```

**Avec corps :**
```
feat(auth): implement two-factor authentication

Add TOTP-based 2FA using Google Authenticator.
Users can enable 2FA in their profile settings.

Closes #123
```

**Breaking change :**
```
feat(api)!: change user endpoint response format

BREAKING CHANGE: The /api/users endpoint now returns
user data in a different format. Update your client
applications accordingly.
```

### Workflow de développement

1. **Créer une branche** pour votre fonctionnalité
   ```bash
   git checkout -b feat/my-feature
   ```

2. **Faire vos commits** en respectant la convention
   ```bash
   git commit -m "feat(auth): add login functionality"
   ```

3. **Pousser votre branche**
   ```bash
   git push origin feat/my-feature
   ```

4. **Créer une Pull Request** sur GitHub

### Vérification automatique

- ✅ **GitHub Actions uniquement** vérifie automatiquement tous les commits
- ❌ **Les PRs avec des commits non conformes seront bloquées**
- � **Aucune installation locale requise**
- ⚡ **Feedback immédiat** dans les Pull Requests

### En cas d'erreur

Si vos commits ne respectent pas la convention, GitHub Actions vous le signalera dans la PR :

1. **Modifier le dernier commit :**
   ```bash
   git commit --amend -m "feat(auth): add login functionality"
   ```

2. **Modifier plusieurs commits :**
   ```bash
   git rebase -i HEAD~3  # Pour les 3 derniers commits
   ```

3. **Forcer la mise à jour :**
   ```bash
   git push --force-with-lease
   ```

### Aide et support

- 📖 [Documentation Conventional Commits](https://www.conventionalcommits.org/)
- 🔍 [Vérifiez vos commits dans l'onglet Actions de GitHub](https://github.com/IIM-CDI/TEMPLATE-BAP/actions)
- 💬 Contactez l'équipe en cas de question

### Protection de la branche main 🔒

La branche `main` est protégée pour garantir la qualité du code :

#### Règles en place :
- 🛡️ **Pull Request obligatoire** : Impossible de push directement sur `main`
- ✅ **Validation des commits** : Tous les commits doivent respecter la convention
- 👥 **Review obligatoire** : Au moins 1 approbation requise
- 🔄 **Branche à jour** : La branche doit être synchronisée avant le merge
- 💬 **Résolution des commentaires** : Tous les commentaires doivent être résolus

#### Workflow imposé :
1. Créer une branche de feature
2. Développer et committer (avec convention)
3. Ouvrir une Pull Request
4. ✅ GitHub Actions valide automatiquement les commits
5. ✅ Review et approbation d'un pair
6. ✅ Merge possible uniquement si tout est vert

> 📋 **Note pour les administrateurs** : Voir `.github/BRANCH_PROTECTION.md` pour la configuration détaillée

### Avantages de cette approche

✅ **Simplicité** : Aucune configuration locale nécessaire  
✅ **Sécurité** : Impossible de contourner la vérification  
✅ **Universalité** : Fonctionne pour tous les contributeurs  
✅ **Centralisation** : Toute l'équipe voit les mêmes résultats  
✅ **Qualité** : Historique Git propre et cohérent