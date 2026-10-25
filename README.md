# Quiz STI

> Réviser la matière **Sciences et Technologies de l’Informatique** avec un quiz simple, léger et utilisable directement dans le navigateur.

Quiz STI s’adresse aux élèves de **3ᵉ et 4ᵉ années Sciences Informatiques en Tunisie**. Il propose des questions, calcule le score et affiche un récapitulatif à la fin.

## ✨ Ce que propose le quiz

- Fonctionne côté navigateur, sans backend
- Charge les questions depuis le dossier `data/`
- Affiche le score et un récapitulatif de fin
- Offre une interface légère et adaptée aux petits écrans

## 🚀 Démarrer

Clonez le dépôt et ouvrez `index.html` dans un navigateur :

```bash
git clone https://github.com/anwarous/quiz-sti1.0.git
cd quiz-sti1.0
```

Pour servir le projet en local avec Python :

```bash
python -m http.server 8000
```

Puis ouvrez [http://localhost:8000](http://localhost:8000).

## 🗂️ Organisation

```text
index.html    Page du quiz
app.js        Navigation, chargement des questions et score
data/         Jeux de questions
logo.png      Logo facultatif
LICENSE       Licence GPL-3.0
```

## ➕ Ajouter des questions

Ajoutez les fichiers de questions dans `data/`, puis vérifiez que leur format correspond à celui attendu par le chargement dans `app.js`. Vous pouvez organiser les jeux par thème, niveau ou chapitre.

## 🛠️ Pistes d’évolution

- Mode examen et chronomètre
- Filtrage par niveau ou chapitre
- Explications après les réponses
- Export des résultats
- Traductions en arabe et en anglais

## 🤝 Contribuer

Les contributions sont les bienvenues. Forkez le dépôt, créez une branche pour votre changement, puis ouvrez une pull request avec une courte description.

## 📄 Licence

Distribué sous licence [GPL-3.0](LICENSE).
