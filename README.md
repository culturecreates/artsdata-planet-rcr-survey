# artsdata-planet-rcr-survey

Files, SPARQLs and demos related to the RCR Survey integration with Artsdata.

The contents of the `docs` directory is published using Github Pages.

Demos
=====
1. [Search Places](https://culturecreates.github.io/artsdata-planet-rcr-survey/standalone-place-demo) demo using the Artsdata Reconciliation API.
2. [Search Organizations](https://culturecreates.github.io/artsdata-planet-rcr-survey/standalone-place-to-organization.html)** A demo using the Artsdata SPARQL API.  This search allows the user to enter the name of a place or venue where they attend events to make it easier to find the organization that is reponsible for the events.
   **Logic:** A place is linked to organizations via the following relationships:
    * `ado:managedBy`
    * `ado:ownedBy`
    * `ado:usedBy`
    * `ado:hasResident`

 Note for Developers

The HTML for the demos contains two primary scripts:
* UI language handling: Handles language localization and interface updates.
* Core: Handles the API requests and search logic.

### Background

See: [2526-W-030 RCR Survey](https://docs.google.com/document/d/1x3kN6y7yLtifuOMHGbXZS6nyBAhnbrrSdL0zhk-swgU/edit?usp=sharing)

### Outcomes

The integration between the RCR survey software and Artsdata was a success. Survey respondents were able to retrieve an Artsdata entity in 55.3% of cases.

> Avant le nettoyage et le recodage des données, sur les 5 669 réponses à la question 3 du sondage (« Aux spectacles de quels autres organismes avez-vous assisté au cours des 12 derniers mois? » / “Which other organization(s) did you attend within the past 12 months?”), 3 133 sont des organismes clairement identifiés avec un identifant Artsdata et 2 536 réponses sont des réponses texte plutôt que des entités clairement identifiées. Cela veut dire que, grâce à l’intégration avec Artsdata, les répondants ont réussi à récupérer un organisme clairement identifié dans 55,3 % des cas.
