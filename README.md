# Calculateur CVSS v4.0
Le calculateur CVSS v4.0 est basé sur le document de spécification de la version 4.0 du Common Vulnerability Scoring System (CVSS). Ce document constitue la référence officielle pour comprendre comment évaluer la gravité des vulnérabilités.

Ce projet est une application web qui permet de calculer le score CVSS pour une vulnérabilité donnée. La logique principale est implémentée à l’aide de classes JavaScript qui encapsulent les métriques CVSS, les calculs de score et la manipulation de chaînes vectorielles :

    La classe Vector gère la chaîne vectorielle CVSS et les métriques associées. Elle constitue l’épine dorsale de la logique de l’application, en fournissant des méthodes pour mettre à jour et valider la chaîne vectorielle, calculer les classes équivalentes et dériver les valeurs des métriques.

    La classe CVSS40 est chargée du calcul du score CVSS v4.0. Elle interagit avec une instance de la classe Vector pour calculer le score et déterminer le niveau de gravité.

L’application est en ligne et accessible à l’adresse suivante : Calculateur CVSS v4.0.(https://deeprecon89.github.io/calcultateur-cvss-v4/).

## License
This project is licensed under the BSD-2-Clause License. See the [LICENSE](./LICENSE) file for more information.
