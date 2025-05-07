# AIML_project
# 🎧 Spotify Million Playlist Dataset Challenge

Questo progetto è stato realizzato per il corso triennale di *Applicazioni Informatiche del Machine Learning* presso La Sapienza Università di Roma.

L'obiettivo era affrontare la task di **continuazione automatica delle playlist** utilizzando il **Million Playlist Dataset (MPD)** rilasciato da Spotify, **senza l'uso delle API ufficiali**.  
Il modello di raccomandazione è stato implementato tramite **Matrix Factorization** usando la tecnica di **Truncated SVD**.

---

## 📊 Dataset

- **Fonte**: [Spotify MPD Challenge (RecSys 2018)](https://www.aicrowd.com/challenges/spotify-million-playlist-dataset-challenge)
- **Contenuto**: 1 milione di playlist generate dagli utenti tra il 2010 e il 2017
- **Formato**: JSON

---

## ⚙️ Metodo

Il sistema di raccomandazione si basa su Collaborative Filtering e utilizza **Matrix Factorization** per predire tracce mancanti in una playlist a partire dai pattern osservati nel dataset.

---

## 📈 Metriche di Valutazione

Il modello è stato valutato tramite:
- Recall@K
- Precision@K
- Mean Reciprocal Rank (MRR)
