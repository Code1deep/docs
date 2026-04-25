# docs – Documentation technique et schémas d'architecture

[![Licence](https://img.shields.io/badge/Licence-CC_BY--SA_4.0-blue.svg)](LICENSE)

## Objectif

Ce dépôt centralise toute la documentation technique de ma recherche doctorale : architecture de la Base de Données Intelligente (BDI), protocoles de collecte, schémas du Living Lab et manuels utilisateur.

## Contenu

| Fichier | Description | Statut |
|---------|-------------|--------|
| `architecture_bdi.pdf` | Schéma complet de la Base de Données Intelligente | 🟡 En cours |
| `protocole_mqtt.pdf` | Documentation du protocole de collecte (MQTT) | 🟡 En cours |
| `manuel_utilisateur.pdf` | Guide d'utilisation de la BDI pour les apprenants | ⬜ À créer |
| `schema_living_lab.png` | Plan du Living Lab (capteurs, équipements) | 🟡 En cours |
| `api_reference.md` | Documentation de l'API REST de la BDI | ⬜ À créer |
| `calibration_procedure.md` | Procédure de calibration des capteurs | ✅ À jour |

## Architecture BDI (vue d'ensemble)
[Capteurs IoT] → [MQTT Broker] → [BDI-prototype] → [InfluxDB] → [Grafana Dashboard]
↓
[obstacle-detection]
↓
[Alertes / Étayage]
## Versions

| Version | Date | Modifications |
|---------|------|---------------|
| v0.1 | 2026-03 | Première version : schémas d'architecture |
| v0.2 | 2026-04 | Ajout protocole MQTT, schéma Living Lab |
| v0.3 | (à venir) | Documentation API, manuel utilisateur final |

## Téléchargement direct

- [Architecture BDI (PDF)](./architecture_bdi.pdf) *(à venir)*
- [Protocole MQTT (PDF)](./protocole_mqtt.pdf) *(à venir)*
- [Schéma Living Lab (PNG)](./schema_living_lab.png) *(à venir)*

## Contribution

Les documents sont sous licence CC BY-SA 4.0. Toute contribution doit respecter cette licence.

## Licence

**Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)**

Copyright (c) 2026 A. Elbah

Cette licence permet :
- ✅ Partager (copier, redistribuer)
- ✅ Adapter (remixer, transformer)
- ✅ Usage commercial

**Conditions** :
- ✅ Attribution (citer l'auteur original)
- ✅ Partage dans les mêmes conditions

Voir le fichier [LICENSE](LICENSE) pour le texte complet.
