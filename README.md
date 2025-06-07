# AI_Engineering_Projects_Advanced_MachineLearning
My AI Engineering Master's Projects - Machine Learning: Models and Algorithms Module

# Classificazione Frutti Esotici
Progetto di Machine Learning per migliorare la classificazione dei frutti esotici di TropicTaste Inc., passando da un processo manuale ad uno automatico e preciso

## 🎯 Obiettivo

L'obiettivo è creare un modello che classifichi i frutti basandosi sulle loro caratteristiche numeriche, riducendo errori e ottimizzando la gestione dell'inventario e la qualità

## 💾 Dataset

Il dataset è disponibile [qui](https://proai-datasets.s3.eu-west-3.amazonaws.com/fruits.csv) e include le seguenti variabili:

* `Frutto` (target): Tipo di frutto
* `Peso (g)`: Peso in grammi
* `Diametro medio (mm)`: Diametro medio in millimetri
* `Lunghezza media (mm)`: Lunghezza media in millimetri
* `Durezza buccia (1-10)`: Durezza su scala 1-10
* `Dolcezza (1-10)`: Dolcezza su scala 1-10
* `Acidità (1-10)`: Acidità su scala 1-10

## 🧠 Metodologia

Algoritmo **K-Nearest Neighbors (KNN)**

Il progetto si articola in:

1.  **Preparazione Dati**: Caricamento, pulizia (gestione valori mancanti) e normalizzazione
2.  **Modello KNN**: Sviluppo, addestramento e ottimizzazione
3.  **Valutazione**: Test del modello con validazione incrociata e calcolo delle metriche di performance (es. accuratezza)
4.  **Visualizzazione**: Grafici e analisi dei risultati per capirne l'efficacia

## 📊 Analisi

Ogni fase del progetto sarà accompagnata da analisi e commenti per interpretare al meglio i dati e i risultati del modello
