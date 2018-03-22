# sugarlabs-porting-list

### The list of activities that requires porting to GTK3 and GST 1.0.

GTK2 and GST0.10 are end of life. We need to upgrade the remaining activities with these dependencies.
Status is as of 17/03/18

|                                                   |                     |                          |                                                          | 
|---------------------------------------------------|---------------------|--------------------------|----------------------------------------------------------| 
| Activities name                                   | Shortlist           | Works on Fedora          | Type                                                     | 
| sugarlabs/activity-erikos                         |                     | yes                      | produce sound of animal on clicking, useless             | 
| sugarlabs/activity-turtle-confusion               | shortlist           | yes                      | complex maths activity                                   | 
| sugarlabs/activity-turtle-flags                   | y                   | yes                      | similar to previous but flags                            | 
| sugarlabs/adivinanzas-activity                    |                     | yes                      | Quiz type activity, needs i18n                           | 
| sugarlabs/agubrowser-activity                     | already ported      | NO                       | Cannot IMport name webkit                                | 
| sugarlabs/ahorcadito-activity                     | Delete              | no                       | AttributeError: 'NoneType Object has no attrubyte View'  | 
| sugarlabs/ajedrez-activity                        | yes                 | yes                      | Chess Type activity                                      | 
| sugarlabs/amazonas-activity                       | already working     |                          |                                                          | 
| sugarlabs/analyze                                 | delete              |                          |                                                          | 
| sugarlabs/arithmetic                              |                     |                          |                                                          | 
| sugarlabs/ayni-activity                           |                     | yes                      | A nice game, problem solving.                            | 
| sugarlabs/baltigames-activity                     |                     | no                       | Import Error: No module named hulahop                    | 
| sugarlabs/bichos-activity                         |                     |                          |                                                          | 
| sugarlabs/blender-activity                        |                     | no                       | ValueError: Namespace Vte not available for version 2.91 | 
| sugarlabs/block-party-activity                    |                     | yes                      | tetris game with some errors                             | 
| sugarlabs/blocku                                  |                     |                          |                                                          | 
| sugarlabs/Bounce                                  |                     |                          |                                                          | 
| sugarlabs/calendario                              |                     | yes                      | Claender activity                                        | 
| sugarlabs/cavestory                               |                     | no                       | Very little py files                                     | 
| sugarlabs/club-othello-activity                   |                     | yes                      | Resize error                                             | 
| sugarlabs/colgadito-activity                      | delete              |                          |                                                          | 
| sugarlabs/colgadito-spyral                        |                     |                          | popular on activities.sugarlab.github.io                 | 
| sugarlabs/colors                                  |                     |                          | old, not maintained                                      | 
| sugarlabs/compress-activity                       | y                   |                          | no                                                       | 
| sugarlabs/convert                                 |                     |                          | pango not import                                         | 
| sugarlabs/cuidarme-activity                       |                     | yes                      | High graphics pacman game                                | 
| sugarlabs/dasher-activity                         | y                   | yes                      | typper                                                   | 
| sugarlabs/derecho-a-transitar-activity            |                     |                          |                                                          | 
| sugarlabs/diccionario-guarani-castellano-activity |                     |                          |                                                          | 
| sugarlabs/falabracman-activity                    | yes REPOrt          |                          |                                                          | 
| sugarlabs/feliz-navidad-activity                  | y                   |                          |                                                          | 
| sugarlabs/flipsticks                              | y                   | yes                      | stickgame, can make learn body parts                     | 
| sugarlabs/followmeButia                           |                     |                          |                                                          | 
| sugarlabs/foodforce2-activity                     |                     |                          |                                                          | 
| sugarlabs/fortune-maker-activity                  |                     |                          | no                                                       | 
| sugarlabs/fossrit                                 |                     |                          | libvte.so.9                                              | 
| sugarlabs/FreeFromMalaria                         | y                   |                          |                                                          | 
| sugarlabs/Frotz                                   |                     |                          | what is this                                             | 
| sugarlabs/gcd-activity                            |                     |                          |                                                          | 
| sugarlabs/geotonky-activity                       | REPORT CHECK        |                          | I don't understand                                       | 
| sugarlabs/gogo                                    |                     |                          |                                                          | 
| sugarlabs/i-can-read-activity                     | y                   |                          |                                                          | 
| sugarlabs/iknowEditor                             |                     |                          | don't understand                                         | 
| sugarlabs/iknowmyabcs                             | yes                 |                          |                                                          | 
| sugarlabs/jam-clock-activity                      |                     |                          | useless                                                  | 
| sugarlabs/jam-media-explorer-activity             |                     |                          |                                                          | 
| sugarlabs/jam-tank-activity                       |                     |                          |                                                          | 
| sugarlabs/jamedia-imagenes-activity               |                     |                          |                                                          | 
| sugarlabs/jamedia-tube-activity                   |                     |                          |                                                          | 
| sugarlabs/JClic                                   |                     |                          |                                                          | 
| sugarlabs/jigsaw-puzzle-branch                    | yes                 |                          |                                                          | 
| sugarlabs/Kiwix                                   |                     |                          | NOt preffered but okay                                   | 
| sugarlabs/laybrinth-activity                      | pre installed       |                          |                                                          | 
| sugarlabs/Lemonade                                |                     |                          | I don't understand                                       | 
| sugarlabs/moon-activity                           | yes(github mention) |                          |                                                          | 
| sugarlabs/myosa-examples                          |                     |                          |                                                          | 
| sugarlabs/panorama                                |                     |                          | Event queue full error                                   | 
| sugarlabs/pilas-activity                          |                     |                          | python dev env                                           | 
| sugarlabs/playgo                                  | y                   |                          |                                                          | 
| sugarlabs/pydebug-activity                        |                     |                          |                                                          | 
| sugarlabs/pyeyes-activity                         |                     |                          | useless                                                  | 
| sugarlabs/read-sd-comics                          |                     |                          |                                                          | 
| sugarlabs/record-activity                         | yes                 | a lot of work to be done |                                                          | 
| sugarlabs/SocialCalc                              |                     |                          | Excel                                                    | 
| sugarlabs/spanish-guarani                         |                     |                          | maybe, spanish dictionary                                | 
| sugarlabs/starchart                               |                     |                          |                                                          | 
| sugarlabs/sugar-toolkit                           |                     |                          |                                                          | 
| sugarlabs/Sugarizehelp (javascript)               |                     |                          |                                                          | 
| sugarlabs/supertux-activity                       | y                   |                          | no module named vte                                      | 
| sugarlabs/supervampireninjazero-activity          |                     |                          | no module named vte                                      | 
| sugarlabs/tamtam                                  | yes(report)         |                          |                                                          | 
| sugarlabs/Time-Line                               |                     |                          | NOt working                                              | 
| sugarlabs/VncLauncher                             |                     |                          |                                                          | 
