# 3. États, restauration et interopérabilité

Le second mécanisme suivi ici est états, restauration et interopérabilité.
Il relie l’état principal aux acteurs, messages ou preuves nécessaires pour poursuivre l’exécution.
Les limites sont vérifiées avant que le résultat ne devienne observable par les autres modules.
Les chemins d’échec conservent l’état précédent lorsque les conditions attendues ne sont pas réunies.
Les paramètres de configuration modifient le comportement sans changer les invariants fondamentaux du code.
Les appels croisés exigent de vérifier l’identité de l’émetteur et la provenance des données.
Les consommateurs doivent distinguer une valeur proposée, une valeur validée et une valeur finalisée.
La documentation du dépôt précise les conventions nécessaires aux clients et opérateurs.

Fin du parcours. Retour au [sommaire](README.md).
