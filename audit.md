| Date             | Url                                                                                                                        | Nombre requêtes | Taille(kb) | Taille du dom | GES (gCO2e) | Eau (cl) | ecoIndex | Note |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------- | --------------- | ---------- | ------------- | ----------- | -------- | -------- | ---- |
| 10/06/2026 11:48 | [https://clear-walter-governance-solution.trycloudflare.com/](https://clear-walter-governance-solution.trycloudflare.com/) | 1466            | 3525       | 89            | 2.02        | 3.03     | 48.90    | D    |

On peut observer sur le tableau ci-dessus, que le nombre de requêtes est de 1466, la taille de la page et du dom sont très élevée. 
Donc, il faut les dimunuer afin d'élever l'éco index.



## Audit après la correction du code

| Date             | Url                                              | Nombre requêtes | Taille(kb) | Taille du dom | GES (gCO2e) | Eau (cl) | ecoIndex | Note |
| ---------------- | ------------------------------------------------ | --------------- | ---------- | ------------- | ----------- | -------- | -------- | ---- |
| 10/06/2026 16:45 | [http://localhost:3000/](http://localhost:3000/) | 22              | 11135      | 140           | 1.55        | 2.32     | 72.72    | B    |

Depuis le tableau suivant, on remarque qu'en enlevant l'import lucide et les requêtes en trop, le nombre de requêtes a diminué de 1466 à 22. Ce qui engendre l'écoIndex à augmenter de 48.90 à 72.72.