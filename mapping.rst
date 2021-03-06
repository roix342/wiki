.. meta::
   :description: Apprenez à dessiner de plus belles cartes sur RPG Maker. Maîtrisez l'art du mapping et du level-design grâce à nos guides et tutoriels.

Introduction au mapping
=======================

On appelle *mapping* l'action de dessiner une carte (ou *map*) qui sera généralement explorée par le joueur. C'est une activité intuitive, et souvent le premier contact des débutants avec le logiciel.

Principes de base
-----------------

Chaque carte possède ses propres propriétés, notamment la taille et le tileset utilisé. On appelle tileset l'ensemble des cases (ou *tiles*) à disposition pour dessiner une carte, à l'image de la palette d'un peintre.

Le format et la taille des tilesets varient selon la version de RPG Maker utilisée, mais ils sont toujours composés de deux éléments principaux : les tiles normaux, et les autotiles. Ces derniers génèrent automatiquement des bords en fonction des tiles qui les entourent, ce qui permet de tracer des chemins facilement. Les autotiles peuvent être animés, pour représenter une étendue d'eau, ou une cascade.

Afin de superposer les éléments, le mapping est réalisé sur deux couches ou plus, selon le logiciel. La première couche est utilisée pour dessiner le sol et les murs, tandis que les couches supérieures permettent de placer des éléments contenant de la transparence, comme les arbres.

Autres techniques de mapping
----------------------------

Parallax mapping
~~~~~~~~~~~~~~~~

Le parallax mapping est une technique utilisée depuis RPG Maker 2000, qui fut plus largement popularisée avec l'arrivée de RPG Maker VX, en raison de ses possibilités de mapping trop restrictives. Cela consiste à réaliser sa carte dans un éditeur d'image externe, au lieu de l'éditeur de RPG Maker, puis à ancrer l'image produite à la carte du jeu, souvent à l'aide d'un script. Ce procédé permet une liberté totale mais produit des fichiers beaucoup plus lourds, car on perd l'optimisation liée aux cases réutilisables d'un tileset.

Une carte dessinée en parallax mapping est composée d'une image pour la couche inférieure aux personnages, d'une deuxième image pour la couche supérieure, et d'éventuelles images supplémentaires pour les effets de lumière et de brouillard.

Programmes dédiés
~~~~~~~~~~~~~~~~~

Toujours dans l'optique d'élargir ses possibilités, il est possible d'utiliser des programmes spécialisés dans le mapping, comme Tiled (`mapeditor.org <http://www.mapeditor.org/>`_). Cela demande cependant de programmer un interpréteur des données produites, pour les rendre compatibles avec son jeu RPG Maker.
