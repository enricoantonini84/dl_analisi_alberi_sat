# Analisi Deep Learning per Rilevamento Alberi da Immagini Satellitari

Tesi di laurea in Informatica - Università degli Studi di Verona
Anno Accademico 2024/2025

**Autore:** Enrico Antonini (matr. vr500151)
**Relatore:** Prof. Davide Quaglia

## Descrizione

Questa tesi esplora l'utilizzo di tecniche di deep learning per la rilevazione automatica della copertura arborea in contesti urbani a partire da immagini satellitari.

Vengono analizzati e confrontati diversi approcci:

- **YOLO11** - Object detection con reti neurali convoluzionali
- **DetecTree** - Machine learning con classificatore AdaBoost
- **DetecTree2** - Segmentazione delle corone con Mask R-CNN
- **SegFormer** - Segmentazione semantica con Vision Transformers
- **Watershed** - Post-processing per isolamento singoli alberi

## Contenuti

La tesi è scritta in LaTeX ed è organizzata nei seguenti capitoli:

1. Introduzione
2. Dettagli tecnici (reti neurali, dataset, training)
3. YOLO
4. DetecTree
5. DetecTree2
6. SegFormer
7. Applicazione della regola 3-30-300 e mappa degli alberi
8. Analisi dei risultati
9. Confronto servizi di mappe satellitari
10. Ringraziamenti

## Compilazione

Per compilare la tesi:

```bash
pdflatex main.tex
biber main
pdflatex main.tex
pdflatex main.tex
```

## Licenza

Questo lavoro è rilasciato sotto licenza [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/).

Sei libero di:
- **Condividere** — copiare e redistribuire il materiale in qualsiasi formato
- **Adattare** — remixare, trasformare e costruire sul materiale

Alle seguenti condizioni:
- **Attribuzione** — Devi dare credito appropriato all'autore
- **NonCommerciale** — Non puoi usare il materiale per scopi commerciali
- **StessaLicenza** — Se modifichi o sviluppi altri documenti a partire da questo materiale, devi distribuire i tuoi contributi sotto la stessa licenza
