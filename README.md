# Cahier des charges - Pakin-Entelijan

## Participants/Rôle
* Roberton C. Philistin (Chef de projet, Développeur arduino)
* Angelo Dimitrov Charlemagne (Développeur service Web)
*	Kesner Silien (Montage arduino)
*	Jean Paul Genisma (Développeur service Web)

## Scénario
* Un parking entièrement automatisé, calcule le temps de garage de différents véhicules et émet une facture qui après règlement ouvre la barrière de sortie. La gestion du paiement ne sera pas pris en compte dans ce projet. A l'entrée du parking, le conducteur reçoit une carte avec une puce RFID d'un distributeur. Quand il se garre, un capteur de proximité placé à chaque place de parking déclenche un compteur et un capteur RFID identifie le véhicule. Le système associe le véhicule au compteur déclenché par le capteur de proximité. A la récupération du véhicule. L'éloignement du véhicule du capteur de proximité arrête le compteur. A la sortie, le conducteur dépose la carte avec la puce RFID dans une machine qui affiche les détails pour le véhicule en question (temps de garrage, prix, ...) et ouvre la barrière.

## Matériels
* Puces RFID,
* Capteurs : capteur RFID, capteur de proximité
* Actionneurs : LEDs rouge et verte, moteur pour ouvrir la barrière de sortie

## Service Web
* Calcule du temps de garrage
* 

## Interface Web
* Affichage du temps de garrage

## Architecture logicielle
* Client/Serveur 2 tiers
