# Réseau d'entreprise avec VLANs et routage inter-VLAN

Projet Cisco Packet Tracer – Sécurité et networking.

## Objectif
Segmenter un réseau en 3 VLANs (ADMIN, TECH, SERVER), sécuriser
l'accès console et configurer le routage inter-VLAN (Router-on-a-Stick).

## Contenu
- `topologie.pkt` : fichier Packet Tracer
- `configs/` : configurations de S1 et R1
- `captures/` : captures d'écran
- Compte rendu Word

## Plan d'adressage
| VLAN | Nom    | Réseau          | Gateway      |
|------|--------|-----------------|--------------|
| 10   | ADMIN  | 192.168.10.0/24 | 192.168.10.1 |
| 20   | TECH   | 192.168.20.0/24 | 192.168.20.1 |
| 30   | SERVER | 192.168.30.0/24 | 192.168.30.1 |

## Outils
Cisco Packet Tracer