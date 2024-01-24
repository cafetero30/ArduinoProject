## Compte rendu séance 5
### Mercredi 24 janvier

**Objectif :** Permettre le contrôle à distance de la voiture grace à un joystick


Lors de cette cinquième séance de TP, j'ai enfin réussi à utiliser le Bluetooth avec l'Arduino. Pour résoudre les problèmes de communication entre l'Arduino et le PC, ainsi qu'entre les deux modules Bluetooth, une solution a été trouvée. Il a simplement fallu changer les modules Bluetooth. Dans un premier temps, j'ai emprunté un module Bluetooth à un autre groupe dont le leur fonctionnait correctement, afin de mieux cibler le problème. Mon code a parfaitement fonctionné avec leur module, donc j'ai décidé de remplacer les miens, et finalement, tout s'est réparé.


J'ai donc pu effectuer quelques derniers réglages sur mon code pour adapter la vitesse de rotation des roues ainsi que les valeurs transmises par Bluetooth. Au cours de cette séance, j'ai également pu utiliser la carte Arduino NANO, qui ne fonctionnait pas jusqu'à présent car il fallait utiliser un processeur différent (Old Bootloader).


Le pilotage de la voiture sera donc orchestré par un joystick connecté à une carte Arduino UNO, laquelle transmettra la vitesse et le sens de la direction à une carte Arduino NANO installée sur le véhicule. Sur chacune des cartes, un module Bluetooth (maître et esclave) sera utilisé pour assurer leur communication mutuelle.


**Conclusion :**
L’objectif est donc enfin réussi au bout de cette cinqième séance. Bien que du retard ait été pris sur le diagramme de Gantt, j'ai l'intention de le compenser en intensifiant mes efforts chez moi. La prochaine étape consiste à donner vie à la voiture.
