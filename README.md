# Des composants accessibles et de qualité

Checklistes/idées tirées de l’atelier de @goetsu et @nico3333fr à Paris Web : https://www.paris-web.fr/2017/ateliers/des-composants-accessibles-et-de-qualite-le-double-effet-kiss-cool.php

Si vous souhaitez, complétez cette liste ou proposez, en issue ou PR.

## Accessibilité et Ergonomie 

- Design Patterns (à voir si adapté selon les cas)
- tests (aides techniques, etc.)
- référentiel-compliant
- responsive
- supporte la nav séquentielle
- s’insère dans une structure hx
- Compatibilité navigateurs

## Industrialisation 

- Github
- NPM/Yarn
- versions minifiées
- versions transpilées
- licencer le code
- builders
- "pluginification"
- avec ou sans jquery
- plusieurs composants (occurences) par page (dont occurences insérées via AJAX)
- customisation/configurabilité
- intégralement paramétrable
- publier des releases
- avoir des préférences pour l’indentation
- CDN
- tests (fonctionnels, unitaires, etc.) 
- exemples tout faits
- internationalisation (Right To Left, etc.)


## Design 

- exemples
- exemples prêts à être utilisés
- présentation jolie
- animations/transitions
- montrer des use cases différents


## BP code 
- CSP compliant 
- orthogonalité
- fonctionnement sans js
- performance du code js
- amélioration progressive
- composants scopés
- lintés
- penser à ce que ça fonctionne en AJAX
- vérifier que quand on clique sur un enfant, les actions censées se déclencher se déclenchent bien (ex, un enfant d'un bouton en Vanilla JS => https://github.com/nico3333fr/van11y-accessible-hide-show-aria/commit/1e402c73905ec29c744149130b5649c8329184ca )
- tests
- modules selon la stack (angular/etc.)


## Pour aller plus loin 

- tests edge cases 
- imbrication de composants, imbrication d´un composant dans le même (ex. accordéon dans accordéon)
- mix pour nouveaux composants
- configs par défauts selon les environnements

## Promotion/Vie du projet

- news
- documentation
- doc simple pour non-technique
- exemples
- exemples de sites qui l’utilisent/showcase
- suivi des issues (milestones)
- communauté (travail restant, etc.)
- logo, branding

Si vous voyez des bonnes idées à ajouter, GO GO GO !
