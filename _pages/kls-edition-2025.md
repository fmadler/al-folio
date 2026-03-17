---
layout: page-kls
permalink: /kls-generation/
title: KLS 2025
description: Generation of sql call to fill the app.
nav: true
nav_order: 10

kls_edition:
    annee: 2025
    name: La revanche des quatre terres
    web-path: 'la-revanche-des-quatre-terres'
    aventuriers:
        - nom: 'Maxime'
          web-path: 'maxime-2025'
          age: 36
          origine: 'Vosges'
          profession: 'Guide pêche'
    jours:
        - jour: 28
          nu: 44
          meteo: vent
          epreuves: 
                - epreuve: 'parcours-du-combattant'
                  description : 'Le mythique parcours du combattant homme-femme avec 2 vainqueurs'
                  participation-type: 'collectif'
                  type: 'confort'
                  web-path: 'parcours-du-combattant-2025'
                  nu: 15
                  tribu-web-path: 'blanc-2025'
                  recompense: 'diner'
                  skills: 'force,rapidite,endurance'
                  participants:
                    - participant: jerome-2
                      game-position: 1
                      recompense: 'diner'
                    - participant: louise
                      game-position: 1
                      recompense: 'diner'
                    - participant: jerome
                      game-position: 2
                    - participant: gaelle
                      game-position: 2
                    - participant: pierre-marie
                - epreuve: 'tir-a-l-arc'
                  description : "Tir à l'arc et élimination du dernier"
                  participation-type: 'collectif'
                  type: 'immunite'
                  web-path: 'tir-a-l-arc-2025'
                  nu: 22
                  tribu-web-path: 'blanc-2025'
                  recompense: 'totem,elimination-du-dernier'
                  skills: 'precision,dexterite'
                  participants:
                    - participant: jerome
                      game-position: 1
                      recompense: 'totem'
                    - participant: louise
                      game-position: 4
                    - participant: jerome
                      game-position: 2
                    - participant: gaelle
                      game-position: 2
                    - participant: pierre-marie
                      game-position: 3
                    - participant: jessica
                      game-position: 12
                      recompense: 'elimination-du-dernier'

---
<h1>
KLS generation sample
</h1>
<br/>
