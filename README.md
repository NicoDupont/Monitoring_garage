# Monitorer mon Garage avec Esphome et HomeAssitant

Monitoring du garage + gestion des relais contact sec pour automatisme portail et lumiere portail.  

### Electronique :

Liste des composants :

- 1x esp32
- 1x résistance 10k ohm
- 1x résistance 4.7k ohm
- 1x capteur magnétique fermeture/ouverture de porte/fenetre
- 1x fusible 0.5a + porte fusible
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

Les gpio du diagramme ne sont pas les bons.  
Voir le yaml  

![ShémaFritzing](https://github.com/NicoDupont/Monitoring_garage/blob/main/img/esp_garage_frtitzing_v2.png?raw=true)

##### Réalisation :

![electronique](https://github.com/NicoDupont/Monitoring_garage/blob/main/img/IMG_1292.jpg?raw=true)

#### Sensor sur HA : 

![sensorha](https://github.com/NicoDupont/Monitoring_garage/blob/main/img/entite.png?raw=true)





