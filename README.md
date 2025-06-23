# IoT Energy Monitoring System – Arduino & Python

Ce projet est une simulation de système de surveillance énergétique domestique, développé dans un cadre académique à l’INSEA. Il vise à mesurer, analyser et visualiser la consommation électrique dans différentes pièces d’un logement intelligent.

---

## Description

Le système repose sur une carte Arduino Uno et des capteurs de courant ACS712 pour collecter les données de consommation électrique (tension et courant). Ces données sont transmises via liaison série et traitées en Python à l’aide de la bibliothèque Pandas. Un tableau de bord Power BI est ensuite utilisé pour visualiser les tendances de consommation et identifier les zones à forte consommation.

---

## Objectifs

- Suivre en temps réel la consommation électrique dans 3 pièces différentes  
- Identifier les équipements ou pièces les plus énergivores  
- Analyser les schémas d’utilisation sur des périodes journalières et hebdomadaires  
- Présenter les résultats de manière visuelle et exploitable  

---

## Architecture du système

1. **Capteurs de courant (ACS712)** connectés à une carte **Arduino Uno**  
2. Transmission des données via **communication série**  
3. Traitement des données brutes en **Python (Pandas)**  
4. Création de tableaux de bord dans **Power BI**  

---

## Technologies utilisées

- Arduino (langage C++)  
- Python (traitement des données avec Pandas)  
- Communication série (USB – Arduino ↔ Python)  
- Microsoft Power BI (visualisation)

---

## Résultats

- Affichage LCD en temps réel de la puissance consommée  
- Export des données nettoyées au format CSV  
- Tableaux de bord Power BI : évolution de la consommation par jour, heure, pièce  

---

## Exécution

1. Charger le code Arduino sur une carte Uno via l’IDE Arduino  
2. Lancer le script Python pour capturer et traiter les données (connexion série requise)  
3. Ouvrir le fichier Power BI fourni pour consulter les graphiques (données simulées si besoin)

---

## Contexte académique

- Réalisé par : Zakaria Douih  
- Institution : INSEA – Département Génie Logiciel et Data  
- Date : Mars 2025  

---

## Contact

Pour toute information complémentaire, vous pouvez me contacter à : **douihzakaria@gmail.com**

---

## Licence

Projet réalisé dans un cadre académique. Usage éducatif uniquement.
