````md
# 📊 Application de Notation du Personnel

Une application web simple et responsive permettant de gérer et calculer la notation du personnel selon plusieurs critères d’évaluation.

---

# 🚀 Aperçu du Projet

Cette application permet :

- d’afficher une liste du personnel,
- de saisir des notes d’évaluation,
- de calculer automatiquement les scores,
- d’attribuer une décision selon le résultat,
- de générer des statistiques,
- de produire des données aléatoires pour les tests,
- et d’effacer toutes les données rapidement.

Le projet est développé uniquement avec :

- HTML5
- CSS3
- JavaScript Vanilla

Aucune dépendance externe n’est requise.

---

# 📁 Structure du Projet

```bash
📦 notation-personnel
 ┣ 📄 Notation_Personnel.html
 ┣ 📄 personnel.js
 ┣ 📄 style.css
 ┗ 📄 README.md
````

---

# 🖥️ Interface Utilisateur

L’application contient :

## ✅ Tableau du personnel

Chaque ligne contient :

* Matricule
* Nom
* Âge
* Poste
* Notes d’évaluation :

  * Assiduité
  * Discipline
  * Animation
  * Encadrement
  * Préparation
* Total
* Décision
* Action de calcul

---

## ✅ Statistiques

Les statistiques affichent :

| Catégorie | Description                        |
| --------- | ---------------------------------- |
| Rapide    | Personnel performant               |
| Moyen     | Personnel moyen                    |
| Long      | Personnel nécessitant amélioration |

---

# ⚙️ Fonctionnalités

## 1. Calcul individuel

Chaque employé peut être évalué individuellement via le bouton :

```js
Calculer
```

Le système :

* vérifie les notes,
* calcule le total,
* attribue une décision,
* colore automatiquement la ligne.

---

## 2. Calcul global

Le bouton :

```js
Calculer Tous
```

permet de calculer toutes les lignes automatiquement.

---

## 3. Génération automatique

Le bouton :

```js
Générer
```

génère des notes aléatoires entre 0 et 20 pour tous les employés.

Pratique pour :

* les démonstrations,
* les tests,
* les simulations.

---

## 4. Statistiques

Le bouton :

```js
Statistiques
```

calcule automatiquement :

* le nombre de décisions "Rapide",
* le nombre de décisions "Moyen",
* le nombre de décisions "Long".

---

## 5. Réinitialisation

Le bouton :

```js
Effacer
```

supprime :

* toutes les notes,
* les résultats,
* les statistiques.

---

# 🧠 Logique de Décision

| Total | Décision | Couleur |
| ----- | -------- | ------- |
| ≥ 70  | Rapide   | Vert    |
| ≥ 50  | Moyen    | Orange  |
| < 50  | Long     | Rouge   |

---

# 🔍 Validation des Données

Le système vérifie automatiquement :

* que les champs ne sont pas vides,
* que les notes sont numériques,
* que les notes sont comprises entre 0 et 20.

En cas d’erreur :

```bash
Les notes doivent être entre 0 et 20 !
```

---

# 🎨 Design & Responsive

L’interface est :

* moderne,
* responsive,
* simple d’utilisation,
* adaptée aux mobiles,
* adaptée aux tablettes,
* adaptée aux ordinateurs.

Technologies utilisées :

* Flexbox
* Media Queries
* Responsive Table
* Hover Effects

---

# 📦 Données du Personnel

Les données sont stockées dans :

```bash
personnel.js
```

Sous format JSON :

```js
{
  "Matricule": "12345",
  "name": "John Doe",
  "age": 30,
  "position": "Software Engineer"
}
```

---

# ▶️ Exécution du Projet

## Méthode 1 — Ouverture directe

Ouvrir simplement :

```bash
Notation_Personnel.html
```

dans votre navigateur.

---

## Méthode 2 — Live Server (Recommandé)

Avec Visual Studio Code :

1. Installer l’extension :

   * Live Server

2. Cliquer droit sur :

```bash
Notation_Personnel.html
```

3. Sélectionner :

```bash
Open with Live Server
```

---

# 🛠️ Technologies Utilisées

| Technologie | Rôle               |
| ----------- | ------------------ |
| HTML5       | Structure          |
| CSS3        | Style & Responsive |
| JavaScript  | Logique métier     |

---

# 📈 Améliorations Futures

Possibilités d’évolution :

* sauvegarde LocalStorage,
* export PDF,
* export Excel,
* système d’authentification,
* backend Node.js / PHP,
* base de données MySQL,
* recherche et filtrage,
* pagination,
* dashboard avancé,
* graphiques statistiques.

---

# 🔐 Bonnes Pratiques Implémentées

✅ Séparation des fichiers
✅ Validation des données
✅ Responsive Design
✅ Code modulaire
✅ Manipulation DOM dynamique
✅ Interface utilisateur claire

---

# 👨‍💻 Auteur

Projet développé dans le cadre d’un système de gestion et d’évaluation du personnel.

---

# 📄 Licence

Ce projet est open-source et peut être utilisé à des fins pédagogiques ou professionnelles.

---

# ⭐ Capture Fonctionnelle

## Exemple de workflow :

1. Générer des notes
2. Calculer tous les employés
3. Afficher les statistiques
4. Réinitialiser les données

---

# 📞 Support

Pour toute amélioration ou contribution :

* Fork du projet
* Pull Request
* Suggestions & optimisations

---

# ✅ Résultat

Une mini application RH moderne, simple et efficace permettant :

✔️ la notation du personnel
✔️ le calcul automatique des résultats
✔️ la génération de statistiques
✔️ une visualisation claire des performances

```
```
