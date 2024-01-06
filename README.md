# esphome-4chpro-venmar-hvr

Contrôleur d'échangeur d'air Venmar Constructo 1.5 HVR basé sur ESPHome et un interrupteur WiFi Sonoff 4CHPRO R3.

Le Constructo 1.5 HVR supporte les modes arrêt, vitesse lente et vitesse rapide.

Connexion à l'échangeur d'air basé sur https://cocoontech.com/threads/control-of-broan-venmar-hrv-or-erv-info.28397/

Boutons:
- R1: Vitesse lente
- R2: Vitesse rapide
- R3: Démarrage du mode intermittent: 20 minutes à vitesse lente et 40 minutes à vitesse rapide
- R4: Arrêt complet

Interrupteurs (dans Home Assistant):
- Vitesse lente (R1): Active/Désactive le relais R1. `COM` connecté à `B` avec résistance 47K OHM et `NO` connecté à `G`.
- Vitesse rapide (R2): Active/Désactive le relais R2. `COM` connecté à `B` avec résistance 4.7K OHM et `NO` connecté à `G`.
- Intermittent: Démarre/Arrête le mode intermittent: 20 minutes à vitesse lente et 40 minutes à vitesse rapide. 
