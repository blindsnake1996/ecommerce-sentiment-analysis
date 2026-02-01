# 🛍️ E-Commerce Sentiment Analysis & Recommendation Prediction

## 📌 Übersicht
Dieses Projekt analysiert über 20.000 Kundenbewertungen eines Bekleidungseinzelhändlers. Das Ziel ist es, den "Business-Blindspot" zu schließen: Wir nutzen **Natural Language Processing (NLP)**, um aus Texten quantitative Insights zu gewinnen und vorherzusagen, ob ein Produkt weiterempfohlen wird.

## 🚀 Key Features
* **Sentiment Analysis Pipeline:** Umwandlung von unstrukturierten Review-Texten in numerische Sentiment-Scores mit NLTK/VADER.
* **Predictive Modeling:** Einsatz eines Random Forest Classifiers zur Vorhersage der Weiterempfehlungsrate.
* **Error Analysis:** Tiefenanalyse von Fehlklassifikationen (z.B. Sarkasmus oder kontrastives Feedback), um Modellgrenzen zu verstehen.

## 📊 Ergebnisse & Insights
* **Modell-Performance:** Erreichte einen F1-Score von ca. **88%**.
* **Wichtigster Faktor:** Der `Sentiment_Score` ist der stärkste Prädiktor für eine Empfehlung – weit vor dem Alter der Kundin oder der Textlänge.
* **Insight:** Das Modell erkennt "stille Kritiker" (hohe Bewertung, aber negatives Sentiment im Text), was für das Qualitätsmanagement entscheidend ist.

## 🛠 Tech-Stack
* **Sprache:** Python 3.x
* **Libraries:** Pandas, Scikit-Learn, NLTK (VADER), Seaborn, Matplotlib
* **Tools:** Jupyter Notebook

## 📁 Projektstruktur
- `notebooks/`: Enthält die explorative Datenanalyse (EDA) und das Modelltraining.
- `data/`: Datensatz (Womens Clothing E-Commerce Reviews).
- `requirements.txt`: Benötigte Python-Pakete.

## 📈 Future Work
* Einsatz von **BERT-Embeddings**, um den Kontext in komplexen Sätzen (z.B. "Tolle Farbe, aber schlechter Schnitt") besser zu erfassen.
* Entwicklung eines Dashboards (Streamlit), um Marketing-Teams Echtzeit-Sentiment-Tracking zu ermöglichen.

---
*Erstellt als Teil meines Data Science Portfolios.*
