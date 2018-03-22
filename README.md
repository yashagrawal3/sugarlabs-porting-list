# sugarlabs-porting-list

### The list of activities that requires porting to GTK3 and GST 1.0.

GTK2 and GST0.10 are end of life. We need to upgrade the remaining activities with these dependencies.
Status is as of 17/03/18

|                                                   |                 |                 |                                                          | 
|---------------------------------------------------|-----------------|-----------------|----------------------------------------------------------| 
| Activities name                                   | Shortlist       | Works on Fedora | Type/error                                                     | 
| sugarlabs/activity-erikos                         |                 | yes             | produce sound of animal on clicking,                     | 
| sugarlabs/activity-turtle-confusion               | yes             | yes             | complex maths activity                                   | 
| sugarlabs/activity-turtle-flags                   | yes             | yes             | similar to previous but flags                            | 
| sugarlabs/adivinanzas-activity                    | yes             | yes             | Quiz type activity, needs i18n                           | 
| sugarlabs/agubrowser-activity                     | already ported  | no              | Cannot import name webkit                                | 
| sugarlabs/ahorcadito-activity                     | Delete          | no              | AttributeError: 'NoneType Object has no attrubyte View'  | 
| sugarlabs/ajedrez-activity                        | yes             | yes             | Chess Type activity                                      | 
| sugarlabs/amazonas-activity                       | already working |                 |                                                          | 
| sugarlabs/analyze                                 | delete          |                 |                                                          | 
| sugarlabs/arithmetic                              |                 |                 |                                                          | 
| sugarlabs/ayni-activity                           | yes             | yes             | A nice game, problem solving.                            | 
| sugarlabs/baltigames-activity                     |                 | no              | Import Error: No module named hulahop                    | 
| sugarlabs/bichos-activity                         |                 |                 |                                                          | 
| sugarlabs/blender-activity                        |                 | no              | ValueError: Namespace Vte not available for version 2.91 | 
| sugarlabs/block-party-activity                    | yes             | yes             | tetris game with some errors                             | 
| sugarlabs/blocku                                  |                 |                 |                                                          | 
| sugarlabs/Bounce                                  |                 |                 |                                                          | 
| sugarlabs/calendario                              |                 | yes             | Claender activity                                        | 
| sugarlabs/cavestory                               |                 | no              | Very little py files                                     | 
| sugarlabs/club-othello-activity                   |                 | yes             | Resize error                                             | 
| sugarlabs/colgadito-activity                      | delete          |                 |                                                          | 
| sugarlabs/colgadito-spyral                        | yes             |                 | popular on activities.sugarlab.github.io                 | 
| sugarlabs/colors                                  |                 |                 | old, not maintained                                      | 
| sugarlabs/compress-activity                       |                 |                 | no                                                       | 
| sugarlabs/convert                                 |                 |                 | pango not import                                         | 
| sugarlabs/cuidarme-activity                       |                 | yes             | High graphics pacman game                                | 
| sugarlabs/dasher-activity                         |                 | yes             |                                                          | 
| sugarlabs/derecho-a-transitar-activity            |                 |                 |                                                          | 
| sugarlabs/diccionario-guarani-castellano-activity |                 |                 |                                                          | 
| sugarlabs/falabracman-activity                    | yes             |                 |                                                          | 
| sugarlabs/feliz-navidad-activity                  |                 |                 |                                                          | 
| sugarlabs/flipsticks                              | yes             | yes             | stickgame, can make learn body parts                     | 
| sugarlabs/followmeButia                           |                 |                 |                                                          | 
| sugarlabs/foodforce2-activity                     | yes             |                 |                                                          | 
| sugarlabs/fortune-maker-activity                  |                 |                 |                                                          | 
| sugarlabs/fossrit                                 |                 |                 | libvte.so.9                                              | 
| sugarlabs/FreeFromMalaria                         |                 |                 |                                                          | 
| sugarlabs/Frotz                                   |                 |                 | I don't understand                                       | 
| sugarlabs/gcd-activity                            |                 |                 |                                                          | 
| sugarlabs/geotonky-activity                       |                 |                 | I don't understand                                       | 
| sugarlabs/gogo                                    |                 |                 |                                                          | 
| sugarlabs/i-can-read-activity                     | yes             |                 |                                                          | 
| sugarlabs/iknowEditor                             |                 |                 | I don't understand                                       | 
| sugarlabs/iknowmyabcs                             | yes             |                 |                                                          | 
| sugarlabs/jam-clock-activity                      |                 |                 |                                                   | 
| sugarlabs/jam-media-explorer-activity             |                 |                 |                                                          | 
| sugarlabs/jam-tank-activity                       |                 |                 |                                                          | 
| sugarlabs/jamedia-imagenes-activity               |                 |                 |                                                          | 
| sugarlabs/jamedia-tube-activity                   |                 |                 |                                                          | 
| sugarlabs/JClic                                   |                 |                 |                                                          | 
| sugarlabs/jigsaw-puzzle-branch                    | yes             |                 |                                                          | 
| sugarlabs/Kiwix                                   | yes             |                 |                                   | 
| sugarlabs/laybrinth-activity                      | yes             |                 |                                                          | 
| sugarlabs/Lemonade                                |                 |                 | I don't understand                                       | 
| sugarlabs/moon-activity                           | yes             |                 |                                                          | 
| sugarlabs/myosa-examples                          |                 |                 |                                                          | 
| sugarlabs/panorama                                |                 |                 | event queue full error                                   | 
| sugarlabs/pilas-activity                          | yes             |                 | python dev env                                           | 
| sugarlabs/playgo                                  |                 |                 |                                                          | 
| sugarlabs/pydebug-activity                        |                 |                 |                                                          | 
| sugarlabs/pyeyes-activity                         |                 |                 |                                                          | 
| sugarlabs/read-sd-comics                          |                 |                 |                                                          | 
| sugarlabs/record-activity                         | yes             |                 |                                                          | 
| sugarlabs/SocialCalc                              | yes             |                 | excel type activity                                      | 
| sugarlabs/spanish-guarani                         | yes             |                 | spanish dictionary                                       | 
| sugarlabs/starchart                               | yes             |                 |                                                          | 
| sugarlabs/sugar-toolkit                           | N/A             |                 |                                                          | 
| sugarlabs/Sugarizehelp (javascript)               | N/A             |                 |                                                          | 
| sugarlabs/supertux-activity                       |                 |                 | no module named vte                                      | 
| sugarlabs/supervampireninjazero-activity          |                 |                 | no module named vte                                      | 
| sugarlabs/tamtam                                  | yes             |                 |                                                          | 
| sugarlabs/Time-Line                               |                 |                 | not working                                              | 
| sugarlabs/VncLauncher                             |                 |                 |                                                          | 
