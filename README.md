# Bitcoin-Richtungsprognose mit Machine Learning

Autor: Mostafa Adlan
Universität: HTW Berlin
Projekttyp: Bachelorarbeit
Programmiersprache: Python 3

---

## Projektübersicht

Dieses Projekt implementiert eine Machine-Learning-Pipeline zur Vorhersage der Bitcoin-Kursrichtung (Up oder Down) anhand historischer OHLCV-Zeitreihendaten.

Die folgenden Modelle wurden implementiert:

* Logistische Regression
* Random Forest
* LSTM-Neuronales Netzwerk

Die Vorhersagen wurden für folgende Zeitauflösungen durchgeführt:

* Tagesdaten (Daily)
* 15-Minuten-Daten (15m)

Das Projekt folgt wissenschaftlichen Standards, einschließlich zeitbasierter Train/Test-Aufteilung, Reproduzierbarkeit und Vermeidung von Data Leakage.

---

## Datensatz

Der Datensatz befindet sich unter:

data/btc_15m_data_2018_to_2025.csv

Er enthält Bitcoin-OHLCV-Daten mit einer Auflösung von 15 Minuten.

Die Tagesdaten wurden aus den 15-Minuten-Daten durch Resampling erzeugt.

---

## Projektstruktur

Bitcoin-ML-Project/

data/
btc_15m_data_2018_to_2025.csv

notebooks/
Bitcoin_ML_Project.ipynb

thesis_figures/
(generierte Abbildungen)

requirements.txt

README.md

---

## Installation

Schritt 1 — Virtuelle Umgebung erstellen:

python -m venv .venv

Schritt 2 — Umgebung aktivieren (Mac):

source .venv/bin/activate

Schritt 3 — Abhängigkeiten installieren:

pip install -r requirements.txt

---

## Ausführung

Notebook öffnen und ausführen:

notebooks/Bitcoin_ML_Project.ipynb

Dann auswählen:

Restart Kernel → Run All

---

## Implementierte Modelle

Logistische Regression
Random Forest
LSTM-Neuronales Netzwerk

---

## Evaluationsmetriken

Accuracy
Precision
Recall
F1-Score
Confusion Matrix
ROC-Kurve

---

## Reproduzierbarkeit

Zur Sicherstellung reproduzierbarer Ergebnisse wurden feste Zufalls-Seeds verwendet.

---

## Akademischer Kontext

Dieses Projekt wurde im Rahmen einer Bachelorarbeit an der HTW Berlin entwickelt.

Die Implementierung folgt wissenschaftlichen Standards und guter wissenschaftlicher Praxis.

---

## Erklärung zur Nutzung von KI-Tools

Im Rahmen dieses Projekts wurden KI-Tools (z. B. ChatGPT) unterstützend verwendet, insbesondere zur Fehlersuche (Debugging), Code-Bereinigung und Dokumentationshilfe.

Alle Machine-Learning-Modelle, Experimente, Auswertungen und Interpretationen wurden eigenständig vom Autor durchgeführt, überprüft und verstanden.

Der Autor übernimmt die volle wissenschaftliche und akademische Verantwortung für den Inhalt dieser Arbeit gemäß den Richtlinien der HTW Berlin.