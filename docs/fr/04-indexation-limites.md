# 4. Indexation et limites

Le monorepo fournit plusieurs consommateurs de l’état : DApp, indexeur Ponder, indexeur personnalisé, CLI et définitions de sous-graphe. Ils n’ont pas tous la même latence ni la même source de vérité.

Les frontends doivent distinguer un événement observé, une réponse contestable et un résultat final. Une donnée absente de l’indexeur n’est pas nécessairement absente de la chaîne.

Les limites principales sont l’hypothèse d’un arbitre, les bonds insuffisants, la qualité du template et la disponibilité des services d’indexation.

Dernier chapitre : les suites de cas du dépôt permettent d’approfondir les scénarios ; aucune installation, compilation ou exécution n’a été réalisée dans ce parcours.
