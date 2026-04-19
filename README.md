# Network Security Monitoring & Intrusion Detection System

## Description
Ce projet consiste à concevoir un système de surveillance de la sécurité réseau basé sur l’analyse du trafic et la détection d’intrusions en temps réel.

## Objectifs
- Surveiller le réseau local
- Détecter les activités suspectes
- Identifier les machines actives
- Renforcer la sécurité de l’infrastructure

## Technologies utilisées
- Kali Linux
- Nmap
- Wireshark (optionnel)
- Bash / Python

## Fonctionnalités
- Scan du réseau avec Nmap
- Identification des hôtes actifs
- Analyse des adresses IP et MAC
- Test de connectivité avec Ping
- Détection basique d’anomalies réseau

## Exemple d’utilisation

### Scan réseau
```bash
nmap -sn 192.168.128.0/24
