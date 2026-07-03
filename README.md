Projet de l'Association Réunionaise des Radio Amateurs

Objectif Global : permettre la supervision de l'autonomie des stations automatiques basées sur RaspberryPi

La carte permet :
de remonter au RaspberryPi diverses informations :
- Présence du 5V (GPIO 16)
- Tension d'alimentation 12V (via ADC)
- Tension d'alimentation 3,3V issu du RaspberryPi
- Température par CTN externes (2 canaux)
les tensions sont remontées par un ADS1115 sur le bus I2C (Ad 0x48 par défaut)

de commander le RaspberryPi :
- 3 boutons (GPIO 20, 21, 12)

D'afficher des états :
- une LED (GPIO06)

Le PCB a été lancé en fabrication (JLCPCB) le 2 juillet

Date : 3 juillet 2026
