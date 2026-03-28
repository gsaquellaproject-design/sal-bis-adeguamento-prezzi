# SAL Bis Adeguamento Prezzi

## 🇮🇹 Descrizione

Questo progetto open source mira ad automatizzare il calcolo dei SAL bis
di adeguamento prezzi negli appalti pubblici italiani, ai sensi della
Legge di Bilancio 2026 (L. 199/2025) e del D.L. 50/2022. Oggi queste
operazioni vengono svolte quasi sempre con fogli Excel manuali, con
rischio di errori e grande dispendio di tempo per RUP, direttori lavori
e imprese appaltatrici.

L'obiettivo è modellare in modo trasparente le regole di adeguamento
prezzi (prezzari aggiornati, lavorazioni già eseguite, limiti normativi)
e fornire uno strumento riutilizzabile, verificabile e aperto per tutti
i soggetti coinvolti nei contratti di lavori pubblici.

## 🇮🇹 Obiettivi

- Ridurre il lavoro manuale nei calcoli di SAL bis.
- Applicare in modo chiaro i prezzari aggiornati alle lavorazioni già eseguite.
- Fornire output utilizzabili come base per la documentazione ufficiale di SAL/SAL bis.
- Offrire un riferimento aperto per PA, RUP, DL, imprese e consulenti tecnici.

## 🇮🇹 Stato del progetto

- Fase: prototipo iniziale / definizione requisiti.
- Stack previsto: Python (CLI iniziale, possibile interfaccia web in futuro).
- Focus attuale: struttura dei dati di input/output e modellazione delle regole di calcolo.
- La cartella `docs/` contiene i casi d'uso principali.
- La cartella `examples/` contiene esempi di input dati.

---

## 🇬🇧 English Overview

This open-source project aims to automate SAL-bis price adjustment
calculations for Italian public works contracts, in line with recent
regulations (e.g. Italian Budget Law 2026 and Decreto Aiuti). These
workflows are currently handled mostly with manual spreadsheets, which
are error-prone and time-consuming for public officials and contractors.

The goal is to codify the price-adjustment rules in transparent,
auditable code and provide a reusable tool for all parties involved in
public works contracts.

### 🇬🇧 Goals

- Reduce manual work in SAL-bis price adjustment calculations.
- Clearly apply updated regional/national price lists to already-executed work items.
- Provide outputs that can be used as a basis for official SAL / SAL-bis documentation.
- Offer an open reference for public bodies, RUPs, site supervisors, contractors and technical consultants.

### 🇬🇧 Project status

- Stage: early prototype / requirements definition.
- Planned stack: Python (CLI first, possible web UI later).
- Current focus: data model and business rules for SAL-bis workflows.
- The `docs/` folder collects main use cases.
- The `examples/` folder contains sample input data.

---

## Use of Claude AI

If accepted into the Claude for Open Source program, this project will
use Claude Max to:

- help translate complex legal/technical rules into Python code,
- generate and refine documentation and real-world examples,
- assist in designing and validating test cases for typical SAL-bis scenarios.

The aim is to make the logic as transparent and auditable as possible
for public administrations, RUPs, site supervisors and contractors.
