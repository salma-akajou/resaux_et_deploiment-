---
marp: true
theme: default
_class: lead
_paginate: false
paginate: true
backgroundColor: #ffffff
style: |
  section {
    font-size: 22px;
    color: #1a1a1a;
    line-height: 1.6;
    padding: 60px 80px;
  }

  footer { 
    width: 100%; 
    text-align: right; 
    font-size: 14px; 
    color: #0B3C5D; 
  }

  .logo-header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    position: absolute;
    top: 40px;   
    left: 60px;
    right: 60px;
  }

  .logo-header img { 
    height: 140px; 
    margin-left:10px; 
    margin-right:10px; 
  }

  h1 { 
    color: #0B3C5D; 
    font-size: 2.8em; 
    margin-top: 100px; 
    text-align: left; 
  }

  h2 { 
    color: #0B3C5D; 
    font-size: 2em; 
    border-bottom: 3px solid #0B3C5D; 
    margin-bottom: 40px;
  }

  h3 { 
    text-align: left; 
    color: #123; 
    margin-top: 0; 
  }

  .sommaire-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 20px;
    margin-top: 20px;
  }

  .sommaire-item {
    display: flex;
    align-items: center;
    background: #eaf2f8;
    border-radius: 12px;
    padding: 15px 20px;
    border-left: 6px solid #0B3C5D;
  }

  .sommaire-num {
    background: #0B3C5D; 
    color: white; 
    width: 35px; 
    height: 35px;
    display: flex; 
    justify-content: center; 
    align-items: center;
    border-radius: 50%; 
    font-weight: bold; 
    margin-right: 15px; 
    flex-shrink: 0;
  }

  .dt-card {
    background: #f4f9fc;
    padding: 30px;
    border-radius: 12px;
    border-top: 6px solid #0B3C5D;
    text-align: left;
    margin-top: 20px;
    width: 100%;
    box-shadow: 0 5px 15px rgba(0,0,0,0.05);
  }

  .badge-simple {
    padding: 8px 18px;
    border-radius: 6px;
    font-weight: 600;
    background-color: #0B3C5D;
    color: #ffffff !important;
    font-size: 0.85em;
    border: none;
  }
---

<div class="logo-header">
  <img src="images/ofppt-logo.png" alt="Logo Left">
  <img src="images/logo-solicode.png" alt="Logo Right">
</div>

### **Infrastructure LAN & Équipements Réseau**

**Réalisée par :** Salma Akajou  
**Encadré par :** M. ESSARRAJ Fouad  
**Filière :** Développement Mobile

---

## Sommaire

<div class="sommaire-grid">
  <div class="sommaire-item"><div class="sommaire-num">1</div>Notion de LAN</div>
  <div class="sommaire-item"><div class="sommaire-num">2</div>Pourquoi utiliser un LAN ?</div>
  <div class="sommaire-item"><div class="sommaire-num">3</div>Les topologies réseau</div>
  <div class="sommaire-item"><div class="sommaire-num">4</div>Les éléments d'un LAN</div>
  <div class="sommaire-item"><div class="sommaire-num">5</div>Fonctionnement du LAN</div>
  <div class="sommaire-item"><div class="sommaire-num">6</div>Bonnes pratiques</div>
  <div class="sommaire-item"><div class="sommaire-num">7</div>Conclusion</div>
</div>

---

## 1. Notion de LAN

<div class="dt-card">

Le **LAN (Local Area Network)** signifie **Réseau Local**.

Il s'agit d'un réseau qui connecte plusieurs appareils dans un espace limité comme :

* maison,
* bureau,
* salle informatique,
* entreprise.

### Un LAN permet à toutes les machines du même endroit de communiquer entre elles.

Il facilite donc l'échange rapide des données et le partage des ressources.

</div>

---

## 2. Pourquoi utiliser un LAN ?

<div class="dt-card">

L'utilisation d'un LAN est importante pour plusieurs raisons :

* partager les fichiers entre utilisateurs,
* utiliser une imprimante commune,
* connecter tous les postes à Internet,
* centraliser le travail sur un même réseau.

### Grâce au LAN, les utilisateurs travaillent ensemble plus facilement sans être isolés.

C'est un système pratique, rapide et économique dans les entreprises.

</div>

---

## 3. Les topologies réseau

<div class="dt-card">

La topologie représente la manière dont les ordinateurs et les équipements sont reliés entre eux dans un réseau.

Il existe plusieurs formes de connexion :

### ⭐ Topologie Étoile
Dans cette forme, tous les ordinateurs sont reliés à un appareil central appelé **Switch**.

Si un poste envoie une information, elle passe d'abord par le Switch puis elle est envoyée vers la bonne machine.

Cette topologie est pratique car si un câble tombe en panne, le reste du réseau continue de fonctionner.

---

## 3. Les topologies réseau

### ➖ Topologie Bus
Dans cette forme, tous les appareils sont branchés sur une seule ligne principale.

Les données circulent dans cette ligne jusqu'à atteindre l'appareil concerné.

Cette méthode est simple mais si la ligne principale a un problème, tout le réseau peut être perturbé.

---

## 3. Les topologies réseau

### 🔄 Topologie Anneau
Dans cette forme, chaque appareil est connecté au suivant, ce qui crée un cercle fermé.

L'information passe d'un appareil à un autre jusqu'à arriver à destination.

Si un poste ou une connexion tombe en panne, la circulation des données devient difficile.

---

> Aujourd'hui, la topologie étoile est la plus utilisée car elle offre plus de stabilité, de facilité de gestion et de sécurité.

</div>

---

## 4. Les éléments d'un réseau LAN

<div class="dt-card">

<span class="badge-simple">Switch</span> : appareil central qui relie tous les ordinateurs entre eux.

<span class="badge-simple">Routeur</span> : appareil qui connecte le réseau local à Internet.

<span class="badge-simple">Carte Réseau</span> : composant présent dans chaque PC pour accéder au réseau.

<span class="badge-simple">Câble RJ45</span> : câble physique qui transporte les données.

<span class="badge-simple">Wi-Fi</span> : permet la connexion sans fil.

<span class="badge-simple">Serveur</span> : machine qui stocke et partage les fichiers ou services.

### Tous ces éléments travaillent ensemble pour faire fonctionner le LAN.

</div>

---

## 5. Fonctionnement du LAN

<div class="dt-card">

Dans un réseau LAN, lorsqu'un ordinateur veut envoyer des données :

```txt
PC → Switch → autre PC / Serveur
```
Le Switch reçoit l'information et l'envoie vers la bonne destination.

Si l'utilisateur veut accéder à Internet :

```txt
PC → Switch → Routeur → Internet
```
Le Routeur joue donc le rôle de passerelle vers l'extérieur.

Le LAN permet ainsi une communication interne rapide et un accès externe organisé.
</div>

---
## 6. Bonnes pratiques

<div class="dt-card">

Pour maintenir un réseau LAN efficace, il faut :

* bien organiser les câbles,
* sécuriser le routeur avec mot de passe,
* surveiller les équipements,
* limiter les accès non autorisés,
* vérifier régulièrement la connexion.

### Une bonne organisation garantit stabilité, sécurité et rapidité.

</div>

---

## 7. Conclusion

<div class="dt-card">

Le LAN est une infrastructure essentielle dans les maisons, écoles et entreprises.

Il permet de connecter plusieurs appareils afin de :

* communiquer,
* partager des ressources,
* accéder à Internet,
* travailler de manière centralisée.

### En résumé, le LAN simplifie énormément le fonctionnement informatique d'un même espace.

</div>

---

## Merci pour votre attention !

