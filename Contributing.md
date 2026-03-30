# 🤝 Contributing – Projet Professionnel

Ce document rassemble les bonnes pratiques, conventions de code et règles de collaboration à suivre pour toutes les personnes contribuant au projet professionnel. L’objectif est de garantir un développement cohérent, lisible et maintenable pour tous.

---

## ✅ Cloning and Project Setup

1. Clonez le dépôt:

   ```bash
   git clone https://github.com/yassinbou12/PROJET_PRO.git
   ```

2. Accédez au dossier du projet frontend:

   ```bash
   cd projet-pro/frontend
   ```

3. Installez les dépendances nécessaires:

   ```bash
   npm install
   ```
4. Accédez au dossier du projet backend:

   ```bash
   cd projet-pro/backend
   ```

5. Installez les dépendances nécessaires:

   ```bash
   ./mvnw install
   ```

---

## 🚀 Create a pull request

1. Basculez sur la branche de développement:

   ```bash
   git checkout dev
   git pull origin dev
   ```

2. Créez une nouvelle branche à partir de dev:

   ```bash
   git checkout -b [prefix]/[action-name]
   ```

3. Effectuez vos modifications, et commettre les avec un message significatif:

   ```bash
   git add .
   git commit -m "[prefix]: courte description de la modification"
   ```

4. Push vos modifications:

   ```bash
   git push origin [prefix]/[action-name]
   ```

5. Naviguer vers GitHub et ouvrez un **_pull request_** vers dev, en ajoutant une description claire de vos changements

---

## 🏷️ Branch Naming & Commit Message Conventions

### 🧩 Préfixes de branches autorisés

| Préfixe | Usage prévu |
|---------|-------------|
| feature/[stack]/ | Nouvelle fonctionnalité |
| bugfix/[stack]/ | Correction de bug |
| docs/[stack]/ | Documentation |
| refactor/[stack]/ | Refactorisation (sans modification de logique) |
| test/[stack]/ | Ajout ou modification de tests |
| chore/[stack]/ | Maintenance / mise à jour de dépendances |

Où **[stack]** est l'un des suivants :
- `backend`
- `frontend`
- `mobile`
- `common` (pour les modifications qui touchent plusieurs stacks)

✅ Exemples :
- `feature/backend/gestion-cycles`
- `bugfix/frontend/websocket-deconnexion`
- `docs/mobile/update-readme`
- `chore/common/update-dependencies`

### 💬 Préfixes de commit (Conventional Commits)

Chaque commit doit commencer par un préfixe clair :

| Préfixe | Signification |
|---------|---------------|
| feat: | Ajout d'une fonctionnalité |
| fix: | Correction de bug |
| docs: | Modification de documentation |
| refactor: | Refactorisation de code |
| test: | Ajout ou modif de test |
| chore: | Changement de config / dépendances |
| ci: | Intégration continue |

✅ Exemples de commits :
- `feat(backend): ajout du tableau de monitoring`
- `fix(frontend): correction du bug Kafka lors du cycle thermal`
- `docs(mobile): mise à jour du README`
- `chore(common): mise à jour des dépendances`

### 📦 Processus de contribution

1. Créer une branche à partir de dev
2. Développer la fonctionnalité ou la correction
3. Faire des commits clairs et descriptifs
4. Pousser la branche sur GitHub
5. Ouvrir une Pull Request vers dev
6. Attendre une validation technique

---

## 🤝 Bonnes pratiques de contribution

- Soyez clair et concis dans vos messages de commit et vos descriptions de PR.
- Respectez les normes de codage définies dans le projet.
- N’ajoutez pas de fichiers non nécessaires (ex : fichiers de logs, fichiers temporaires).
- Si vous avez un doute, ouvrez une issue pour discuter avant de coder.
