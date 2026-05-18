# BGP At Doors of Autonomous Systems is Simple (BADASS)

## Introduction

Le projet **BGP At Doors of Autonomous Systems is Simple (BADASS)** de l’école 42 est une introduction au fonctionnement réel d’Internet et du routage réseau.

L’objectif est de construire une mini-architecture réseau composée de plusieurs systèmes autonomes (Autonomous Systems / AS) qui communiquent entre eux grâce au protocole BGP.

Ce projet permet de comprendre comment les données circulent entre différents réseaux à grande échelle.

---

# Objectifs du projet

Le projet consiste à :

- créer plusieurs réseaux indépendants ;
- connecter ces réseaux entre eux ;
- configurer des routeurs ;
- échanger des routes via BGP ;
- observer comment le trafic circule ;
- gérer différents chemins réseau ;
- simuler des coupures ou des changements de topologie.

---

# Qu’est-ce qu’un Autonomous System (AS) ?

Un **Autonomous System** est un ensemble de réseaux administrés par une même entité.

Exemples réels :
- fournisseurs d’accès Internet ;
- grandes entreprises ;
- infrastructures cloud ;
- opérateurs réseau.

Chaque AS possède :
- ses propres routes ;
- ses règles de routage ;
- ses connexions avec d’autres AS.

---

# Le rôle de BGP

Le protocole **Border Gateway Protocol (BGP)** permet aux Autonomous Systems d’échanger des informations de routage.

BGP sert notamment à :
- annoncer des routes ;
- choisir un chemin réseau ;
- rediriger le trafic ;
- maintenir la connectivité entre réseaux.

C’est le protocole principal utilisé sur Internet pour le routage inter-AS.

---

# Concepts abordés

## Réseau

- adressage IP ;
- sous-réseaux ;
- passerelles ;
- routage ;
- tables de routage.

---

## Protocoles réseau

- TCP/IP ;
- BGP ;
- échanges de routes ;
- sélection de chemins.

---

## Infrastructure système

- routeurs ;
- interfaces réseau ;
- virtualisation ;
- namespaces Linux ;
- Docker ou machines virtuelles.

---

## Administration Linux

- configuration réseau ;
- services système ;
- outils réseau ;
- monitoring ;
- logs.

---

# Fonctionnement général

Le projet reproduit une version simplifiée d’Internet :

1. plusieurs AS sont créés ;
2. chaque AS possède son propre réseau ;
3. les AS établissent des relations BGP ;
4. les routes sont échangées ;
5. le trafic peut circuler entre les différents réseaux.

---

# Ce que le projet permet de comprendre

- comment Internet route les données ;
- comment les fournisseurs d’accès communiquent ;
- comment les routes sont propagées ;
- comment un réseau choisit un chemin ;
- comment le trafic est redirigé lorsqu’une liaison change.

---

# Technologies et outils souvent utilisés

Selon les implémentations :

- Linux ;
- Docker ;
- namespaces réseau ;
- FRRouting (FRR) ;
- Bird ;
- outils réseau Linux (`ip`, `ping`, `traceroute`, etc.).

---

# Domaines liés

Ce projet touche à plusieurs domaines :

- ingénierie réseau ;
- infrastructure ;
- DevOps ;
- cloud ;
- cybersécurité ;
- systèmes distribués.

---

# Résumé

BADASS est un projet centré sur :

- le routage réseau ;
- les Autonomous Systems ;
- le protocole BGP ;
- l’architecture d’Internet.

Il permet de construire et manipuler une infrastructure réseau réaliste afin de comprendre le fonctionnement du routage entre grands réseaux.