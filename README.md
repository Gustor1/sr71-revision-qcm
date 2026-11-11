# SR71 - Révision CCNA 1, CCNA 2 et compléments

Application en français : 438 cartes. CCNA 1 : 113 numéros / 122 cartes. CCNA 2 : 87 numéros / 94 cartes. Les variantes distinctes sont conservées. Compléments SR71 : 153 questions originales (dont 4 sur RIP/OSPF ajoutées le 8 novembre 2026, absentes du PDF 04) sur les notions absentes ou insuffisamment évaluées dans la sélection des deux banques.

Questions de cours (écrit) : 69 questions ouvertes rédigées uniquement à partir des PDF du cours, réparties sur les 10 chapitres, avec un résumé « à savoir pour l’écrit » par chapitre, une réponse modèle, une explication et une auto-évaluation (tmp/cours_questions.py → questions-cours.json).

Cours express : une leçon par module du cours SR71 (10 leçons), pour partir de zéro : essentiel avec numéros de diapo, schémas, lexique, vidéos conseillées par Lutz (35 vidéos, marquées « (Lutz) », tmp/lutz_videos.py), recherches vidéo YouTube, liens vers les fiches réflexes, les compléments et les fiches de calcul (tmp/lessons.py → lessons.json).

Méthode rapide : « Fiches réflexes CCNA 1 / CCNA 2 » regroupe les 200 questions Cisco en 41 familles. Chaque fiche contient les bases (sans prérequis), les indices pour reconnaître la question, une méthode pas à pas, la règle, un moyen mnémotechnique, le piège et des exemples résolus tirés des vraies questions. Le parcours essentiel propose 46 questions types qui couvrent 145 questions Cisco. Familles définies dans tmp/reflexes.py et tmp/reflexes_guide.py → reflexes.json, intégrées par build.py.

Les trois parties sont accessibles par le filtre « Partie à réviser ». Les compléments comportent les bonnes réponses, une explication et les références au fichier et aux pages du cours. Ils ne sont pas des questions Cisco ni des annales.

Les PDF des notions non couvertes et des QCM complémentaires sont téléchargeables depuis le site. Le cahier de calculs (41 méthodes) est également disponible ; ses corrections et sa couverture des cours ont été vérifiées le 7 novembre 2026. Sa transformation en parcours interactif reste à faire. La progression des calculs n'est pas encore suivie.

- Questions à choix unique, multiple et exercices d’association.
- Schémas, corrigés et références aux pages du cours.
- Filtres par banque, chapitre, questions jamais faites, erreurs et favoris.
- Progression enregistrée dans le navigateur, export/import JSON.

Ouvrir `index.html` ou utiliser le site GitHub Pages. Aucun compte nécessaire.
La progression est propre au navigateur et à l’adresse du site. Pour transférer une progression depuis la version locale, exporter sa sauvegarde puis l’importer sur le site.

Les fichiers de sauvegarde personnels ne sont pas publiés dans ce dépôt.

Source des questions : PDF fournis des banques ITExamAnswers CCNA 1 et CCNA 2. Traduction de travail, non officielle. Les légendes des schémas sont traduites à côté des illustrations ; les commandes et les adresses sont conservées.
