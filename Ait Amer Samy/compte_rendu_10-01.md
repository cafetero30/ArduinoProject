## Compte rendu séance 3
### Mercredi 10 Janvier

**Objectif :** Connecter la voiture au joystick en bluetooth


Lors de cette troisième séance de TP, mon objectif de pouvoir connecter la voiture au joystick en bluetooth pour pouvoir commander la voiture à distance. Je suis allé chercher des informations sur internet et auprès de mes camarades qui avaient déjà reussi a faire quelque chose de similaire.
Dans une premier temps j'ai essayé de scinder le programme principal en 2. Le programme principal sert a pour voir commander la voiture grace a un joystick sans bluetooth. J'ai donc mis la partie maitre (partie du joystick) dans un programme master et l'autre partie (partie des roues de la voiture) dans un programme slave. 

Cependant j'ai rencontré quelques problèmes notamment lors de l'envoie des données entre les deux modules bluetooth. En effet, les données transmises sont des "floats" et utilisent beaucoup d'octets ce qui rend la transmission moins précise. Lors de la prochaine séance, il faudrait que je trouve une solution pour que les informations a transmetttres prennent moins d'espace (octets).

J'ai donc deux programmes, un pour le module emmeteur (maitre, master hc05) et un pour le module récepteur (esclave, slave hc06) que je dois retravailler afin que les deux modules arduino (la voiture et le joystick) puissent communiquer entre eux en bluetooth. Voici par exemple le programme du hc05:

<img width="609" alt="Capture d’écran 2024-01-11 à 18 03 43" src="https://github.com/cafetero30/ArduinoProject/assets/132355825/aaf4a8e8-b3fe-44d0-bc33-e6aff214d2e5">

**Conclusion :**
Pour cette séance l'objectif n'est pas totalement réussi car l'assossiation en bluetooth des 2 modules prends plus de temps que prévu mais je comprends de plus en plus de choses, et apprend au fur et à mesure en faisant des erreurs.
