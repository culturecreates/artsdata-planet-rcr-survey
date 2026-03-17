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