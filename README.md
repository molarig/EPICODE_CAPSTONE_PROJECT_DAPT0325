# EPICODE_CAPSTONE_PROJECT_DAPT0325
Repository che ospita il Capstone Project del corso Epicode Data Analyst.

## 🏨 Panoramica del progetto

Questo progetto presenta un report Power BI costruito su un dataset di recensioni alberghiere per il brand fittizio **Elysia Global Hotels & Resorts**. Ho progettato logo e mockup del sito web con l'aaiuto di Nano Banana 2 e li ho utilizzati come guida per definire palette colori, tipografia e stile delle visualizzazioni, in modo da ottenere una forte coerenza visiva tra identità digitale e cruscotto analitico. Il progetto è stato svolto in lingua inglese immaginando di doverlo presentare a stakeholder internazionali.  

## 🗂️ Modello dati

Il modello dati si basa su tre tabelle principali:  
- una tabella **hotel**, con l’elenco delle strutture, le città dove si trovano e i punteggi base per ogni struttura;  
- una tabella **recensioni**, con date, punteggi complessivi e di dettaglio (cleanliness, comfort, facilities, location, staff, value for money) e testo delle review;  
- una tabella **utenti**, con informazioni anagrafiche e di segmento (traveller type, fascia d’età, genere, paese).  

## 📊 Struttura del report

Il report è organizzato in cinque pagine principali:

- **Score Overview**: fornisce una vista sintetica della catena: numero di hotel, recensioni e reviewer, punteggi medi globali e mappa con average score per città, oltre al ranking dei top hotel per punteggio complessivo.  
- **Hotel Quality**: confronta i punteggi “base” delle strutture con le medie delle recensioni per ogni hotel e città, mettendo in evidenza dove le aspettative vengono superate o disattese e offrendo un focus per dimensione di qualità (pulizia, comfort, location, staff, ecc.).  
- **Customer Segments**: esplora le performance per tipologia di viaggiatore, fascia d’età, genere e paese, combinando matrici e grafici stacked per capire quali segmenti generano più volumi e quali risultano più soddisfatti. 
- **Temporal Analysis**: analizza l’evoluzione annuale e stagionale dei volumi di review e dei punteggi medi, con filtri per anno, città e traveller type, per evidenziare trend temporali.  
- **Hotel Detail** – pagina di drill‑down dedicata al singolo hotel, con andamento storico dei punteggi, breakdown per segmenti di clientela e word cloud del testo delle recensioni per cogliere a colpo d’occhio i temi più citati (i testi delle recensioni sono generati con una sequenza casuale di parole, per questo i temi visibili nella word cloud risultano non coerenti ad un contesto alberghiero).  

## ✨ Obiettivi e competenze

L’obiettivo del progetto è simulare un cruscotto per una catena alberghiera internazionale, mettendo in evidenza competenze di **data analysis**, **DAX** e **data storytelling** applicate a un contesto business realistico, con particolare attenzione al design e alla coerenza di brand.
