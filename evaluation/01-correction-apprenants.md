# Corrigé : Évaluation Architectures et Hébergement

---

## 1. QCM (Réponses)

1. N-tiers
2. Base de données
3. Docker
4. Distribuer les requêtes vers plusieurs serveurs backend
5. Virtualisation avec VPS

---

## 2. Vrai/Faux (Réponses et justifications)

1. Vrai. Une API REST permet de structurer les échanges entre modules, même dans un monolithe.

2. Faux. Un hébergement mutualisé partage ses ressources entre plusieurs clients, ce qui peut limiter les performances.

3. Faux. Docker isole uniquement les processus applicatifs tandis qu'une VM inclut un OS complet.

4. Vrai. Chaque service étant indépendant, il peut être mis à jour ou scalé sans impacter les autres.

5. Faux. Les sauvegardes protègent contre la perte de données due à des erreurs humaines ou à une panne matérielle.

---

## 3. Questions courtes (Réponses attendues)

1. Une architecture n-tiers sépare les couches (frontend, backend, base de données), limitant ainsi les risques
   d’attaques.

2. Un VPS offre des ressources dédiées et plus de contrôle, tandis qu’un hébergement mutualisé partage les ressources
   et réduit les performances.

3. Un administrateur peut utiliser un pare-feu, limiter l’accès SSH et appliquer le principe du moindre privilège.

4. Les logs permettent de surveiller l’activité, détecter les erreurs ou tentatives d’intrusion et analyser la
   performance.

5. Pour une application simple, les microservices ajoutent une complexité inutile en multipliant les points de
   communication.

---

## 4. Étude de cas (Réponses détaillées)

1. Recommandation d’une architecture n-tiers.

2. Hébergement sur un VPS avec une possible évolution vers le cloud.

3. Mise en place d’un load balancing, optimisation SQL et caching.

4. Sécurisation des accès, protection contre les attaques et sauvegardes régulières.

---

## 5. Rédaction technique (Réponses détaillées)

1. Étapes d’installation d’un serveur VPS avec configuration et sécurisation.

2. Stratégies pour sécuriser une API REST (authentification, validation des entrées, chiffrement).

3. Optimisation des performances backend (cache, optimisation des requêtes, scalabilité).

---

Total de l’évaluation : 60 points.
