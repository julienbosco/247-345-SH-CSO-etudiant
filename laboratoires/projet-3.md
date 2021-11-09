# Utilisation des E/S en C et Makefile

## Utilisation de WiringPi

Développez une application en C sur rPi permettant de contrôler les GPIO du rPi. L'application doit s'appeler `rpi-gpio` et doit prendre les paramètres suivants:

    rpi-gpio bcm_pin on|off

Pour cette application, utiliser la librairie WiringPi pour interfacer les E/S. Pour la compilation, utiliser le compilateur gcc. Vous devez donc installer WiringPi ainsi que GCC pour pouvoir faire fonctionner votre programme.

## Utilisation de la librairie standard

Refaire le même programme, mais en utilisant uniquement les fonctions de la librairie standard. Ceci veut dire que vous pouvez accéder aux E/S avec les fonctions `open(), read(), write() et close()`. Le format reste le même.

