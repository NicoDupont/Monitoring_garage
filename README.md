# Monitorer mon Garage avec Esphome et HomeAssitant

Monitoring du garage + gestion des relais contact sec pour automatisme portail et lumiere portail.  

### Electronique :

Liste des composants :

- 1x esp32
- 1x résistance 10k ohm
- 1x résistance 4.7k ohm
- 1x capteur magnétique fermeture/ouverture de porte/fenetre
- 1x capteur DHT22
- 1x PIR Sensor AM312
- 1x sensor de luminosité GY-2561 TSL2561
- 1x boite de dérivation
- 1x alimentation 5v usb-c
- 1x regulateur 5v=>3.3v am317
- du cable, des borniers à visser
- 1 pcb pour l'assemblage
- 2 relais 5v

##### Schéma electronique :

![ShémaFritzing]()

##### Réalisation :

![ShémaFritzing]()

### Home Assistant :

#### Yaml pour esphome : 

    .yaml

#### Sensor sur HA : 

![sensorha]()





