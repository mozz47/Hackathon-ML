# Hackathon: Immobilienpreisanalyse mit Machine Learning

## 📌 Projektbeschreibung
Dieses Projekt wurde im Rahmen Hackathons der Vorlesung "Machine Learning" durchgeführt und befasst sich mit der Vorhersage von Immobilienpreisen anhand verschiedener Merkmale. Dabei wurde ein **RandomForestRegressor** verwendet, um basierend auf strukturierten Daten ein Vorhersagemodell zu trainieren.

## 📂 Datenverarbeitung
Vor dem Modelltraining wurde eine umfassende Datenvorbereitung durchgeführt:
- **Datenbereinigung**: Fehlende Werte wurden je nach Attribut sinnvoll ersetzt oder entfernt.
- **Feature Engineering**: Kategorische Variablen wurden mit `pd.get_dummies()` encodiert.
- **Datenaufteilung**: Die Daten wurden in **Trainings- (80%)** und **Testdaten (20%)** gesplittet.

## 🤖 Modelltraining
Das Modell wurde mit folgenden Schritten trainiert:
1. Zusammenführen und One-Hot-Encoding der Daten.
2. Training eines **RandomForestRegressors** mit `Scikit-learn`.
3. Evaluierung mit Metriken wie **MSE, RMSE, MAE, R²-Score und MAPE**.
4. Erstellung von Vorhersagen auf einem separaten Test-Datensatz.

## 📊 Ergebnisse
Die Evaluierung des Modells zeigte eine **gute Vorhersagegenauigkeit** auf den Testdaten, sodass das Modell sinnvoll zur Schätzung von Immobilienpreisen verwendet werden kann.

## 📁 Dateien
- `model.ipynb` – Jupyter Notebook mit dem gesamten Workflow.
- `train_bearbeitet.csv` – Bearbeiteter Trainingsdatensatz.
- `test.csv` – Testdatensatz für das Modell.
- `prediction.csv` – Vorhersagen des Modells.
- `data_description_bearbeitet.json` – Beschreibungen der Datenfelder.
- `description.txt` – Details zur Datenverarbeitung und Modellbeschreibung.

## 🚀 Verwendung
Das Modell kann ausgeführt werden, indem das **Jupyter Notebook** (`model.ipynb`) geöffnet und die Zellen schrittweise ausgeführt werden.

---

📌 **Hinweis**: Dieses Projekt wurde zu **Lernzwecken** erstellt.
