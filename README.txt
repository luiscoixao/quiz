Déploiement GitHub Pages

1. Créer un dépôt GitHub.
2. Envoyer index.html, manifest.webmanifest et icon_quiz_histoire.png à la racine.
3. Dans GitHub > Settings > Pages > Deploy from branch > branch main > /(root).
4. Ouvrir l’URL fournie par GitHub Pages.

Personnalisation des questions
- L’application contient une base d’exemple.
- Vous pouvez cliquer sur “Exporter la base”, modifier le fichier JSON, puis le réimporter.
- Ou bien coller directement le JSON dans la zone prévue.

Structure minimale JSON
{
  "appTitle": "Quiz Histoire S1",
  "subjects": [
    {
      "id": "ancienne",
      "name": "Histoire ancienne",
      "questions": [
        {
          "question": "...",
          "answers": ["A","B","C","D"],
          "correctIndex": 1,
          "explanation": "...",
          "chapter": "...",
          "difficulty": "facile"
        }
      ]
    }
  ]
}
