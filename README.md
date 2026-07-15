Projet de l'Association Réunionaise des Radio Amateurs

Objectif Global : permettre la supervision de l'autonomie des stations automatiques basées sur RaspberryPi

La carte permet :
de remonter au RaspberryPi diverses informations :
- Présence du 5V (GPIO 16) avec isolation galvanique par optocoupleur
- Tension d'alimentation 12V (via ADC) par pont diviseur (à ajuster)
- Tension d'alimentation 3,3V issu du RaspberryPi (via ADC)
- Température par CTN externes (2 canaux) (ajuster les résistances) (via ADC)

les tensions (et températures) sont remontées par un ADS1115 sur le bus I2C (Ad 0x48 par défaut, modifiable par JP1)

de commander le RaspberryPi :
- 3 boutons (GPIO 20, 21, 12)

D'afficher des états :
- une LED (GPIO06)

Le PCB a été lancé en fabrication (JLCPCB) le 2 juillet, fourni à l'ARRA le 15/7/26 -> release 1.0

Date : 15 juillet 2026
