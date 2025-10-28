# EM-DATA Project

## Descrizione generale
Questo progetto nasce con l’obiettivo di esplorare e analizzare il dataset **Emergency Events Database (EM-DAT)**, che raccoglie informazioni sui disastri naturali e tecnologici a livello mondiale.  
L’analisi si concentra in particolare sulla **gestione dei dati mancanti** e sulla **complessità dell’oggetto di studio**, ovvero gli eventi di disastro, fenomeni rari e altamente eterogenei per cause, effetti e distribuzione geografica.

---

## Struttura del progetto

### 1. Data Understanding
- **Descrizione del dataset:** analisi delle principali variabili, delle loro distribuzioni e delle relazioni tra le diverse categorie di disastri.  
- **Flusso del lavoro:** rappresentazione delle fasi analitiche adottate.  
- **Statistiche descrittive e visualizzazioni spaziali:** esplorazione quantitativa e geografica dei fenomeni.

### 2. Data Preparation
- **Gestione dei dati mancanti:** approfondimento delle ipotesi MAR e MNAR e applicazione di tecniche di imputazione mirate.  
- **Analisi della correlazione di Spearman:** valutazione delle relazioni tra variabili numeriche e costruzione di nuove feature significative.  
- **Standardizzazione e discretizzazione:** preparazione del dataset per le fasi di mining.

### 3. Clustering
Applicazione e confronto di diversi algoritmi di clustering (K-Means, Gaussian Mixture Models, Agglomerative e DBSCAN) per individuare gruppi omogenei di disastri e interpretare i profili emergenti.

### 4. Regole di Associazione
Utilizzo degli algoritmi **Apriori** e **FP-Growth** per individuare pattern ricorrenti tra le caratteristiche dei disastri, con attenzione particolare ai legami tra **gravità**, **tipo di disastro** e **impatto economico e umano**.

---

## Contributo principale
L’aspetto distintivo del progetto consiste nella **gestione metodologica dei dati mancanti**, spesso trascurata ma cruciale nel contesto dei disastri, e nella **modellazione di un fenomeno raro e complesso**, in cui le relazioni tra variabili sono deboli, non lineari e influenzate da molteplici fattori.

---

## Tecnologie e librerie
- Python (pandas, numpy, matplotlib, seaborn, scikit-learn, mlxtend)
- Jupyter Notebook / VS Code
- Git e GitHub per il versionamento

---

## Ambiente di lavoro
- Arch Linux + Hyprland

---
