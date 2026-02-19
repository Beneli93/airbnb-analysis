# Airbnb Data Analysis – Europa

## Projektbeschreibung
Dieses Projekt analysiert einen öffentlichen Airbnb-Datensatz aus 9 europäischen Städten in Europa. Ziel ist es, herauszufinden, welche Faktoren die Gästezufriedenheit, den Preis und die Attraktivität der Wohnungen beeinflussen.  

Der Datensatz enthält u.a.:  
- Stadt, Preis pro Nacht, Wochentag/Wochenende  
- Zimmertyp, private Räume, Kapazität, Superhost-Status  
- Entfernung zum Stadtzentrum und zu Metro-Stationen  
- Attraction Index, Restaurant Index und Normalisierungen  
- Bewertungen zur Sauberkeit und Gästezufriedenheit  

Mit Python (Pandas, Matplotlib, Seaborn, Plotly, Cartopy) wurden folgende Analysen und Visualisierungen erstellt:  
- Median- und Durchschnittspreise pro Stadt/Wochentag/Wochenende (Bar Charts)  
- Boxplots zur Erkennung von Ausreißern bei den Preisen  
- Scatterplots: Preis vs. Gästezufriedenheit, Bubble-Plots mit Combined Score  
- Heatmaps: Korrelationen zwischen numerischen Variablen, Durchschnittswerte nach Preisgruppe  
- Radarplots: Entfernung zum Stadtzentrum pro Stadt  
- Europakarte mit Städten, Preisen, Kapazität und Attraction/Restaurant Index  

Die Ergebnisse werden abschließend in einer [PowerPoint-Präsentation](presentation/Airbnb-Datenanalyse.pptx) zusammengefasst.

---

## Ordnerstruktur & Dateilinks
- **[data/Datensatz_Airbnb.csv](data/Datensatz_Airbnb.csv)** – Rohdaten für die Analyse  
- **[scripts/](scripts/)** – Python-Skripte für Analyse und Visualisierung  
  - Beispiel: [airbnb_analysis.py](scripts/airbnb_analysis.py)  
- **[presentation/Airbnb-Datenanalyse.pptx](presentation/Airbnb-Datenanalyse.pptx)** – Zusammenfassung der Ergebnisse  
- **[docs/](docs/)** – Projektbeschreibung, Aufgabenstellung  
- **[visuals/](visuals/)** – fertige Plots aus der Analyse  
  - z. B. Boxplots, Bubble-Plots, Heatmaps, Radarplots, Europakarte  

---

## Analyse-Schritte
1. Daten einlesen, prüfen und bereinigen  
2. Median- und Durchschnittspreise nach Stadt und Tag berechnen  
3. Ausreißer bei Preisen identifizieren (Boxplots)  
4. Scatterplots und Bubble-Plots zur Analyse von Preis und Gästezufriedenheit  
5. Korrelationen zwischen numerischen Variablen (Heatmap)  
6. Radarplots zur Entfernung zum Stadtzentrum pro Stadt  
7. Ergebnisse in der PowerPoint-Präsentation zusammenfassen  

---

## Benötigte Python-Pakete
- pandas  
- numpy  
- matplotlib  
- seaborn  
- plotly  
- cartopy  

---

## Hinweise & Vorschau
- Alle Dateien sind im entsprechenden Ordner abgelegt, um die Struktur übersichtlich zu halten.  
- Screenshots oder fertige Plots aus `visuals/` können optional direkt in die README eingebunden werden:  

```markdown
![Boxplot Preise](visuals/boxplot_preise.png)
![Europakarte](visuals/europakarte.png)
