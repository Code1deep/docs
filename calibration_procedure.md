# Procédure de calibration des capteurs Atlas Scientific

## pH

1. Plonger la sonde dans la solution pH 7.00
2. Attendre stabilisation (60 secondes)
3. Exécuter `calibrate_ph.py --point 7.0`
4. Rincer à l'eau distillée
5. Répéter avec solution pH 4.00 ou pH 10.00

## EC (Conductivité)

1. Plonger la sonde dans la solution 12.88 mS/cm
2. Attendre stabilisation
3. Exécuter `calibrate_ec.py`

## Bonnes pratiques

- Calibration hebdomadaire
- Stockage des sondes dans solution de conservation
- Vérifier les dates d'expiration des solutions
