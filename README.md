#README

##Projektbeschreibung: 

Entwicklung von Python-Skripten zur automatisierten Aufbereitung und Metadatenanreicherung der Forschungsdaten aus qualitativen Textdaten sowie Umfragedaten

Ziel: Zwei Python-Skripte wurden erstellt, die automatisiert Forschungsdaten aufbereiten zur Erleichterung im Forschungsprozess und Unterstützung bei der Einhaltung der FAIR-Prinzipien (Findable, Accessible, Interoperable, Reusable). 
Anhand zweier Beispielsdatensätze wird die Anwendung demonstriert.

Datentypen, für die ein Skript erstellt wird:
- Qualitative Textdaten: Interview-Transkripte
- Quantitative Daten: Umfragedaten

##Anleitung: 

Mindestens Python-Version 3.xx notwendig.

Zur Nutzung der Skripte müssen die nachfolgenden Bibliotheken (s. requierements.txt) installiert sein.

*Benötigte Bibliotheken:*
- Pandas
- Numpy
- Nltk
- Matplotlib 
- os (Metadaten)
- Python-docx
- Spacy (für Anonymisierung)
- re 
- Wordcloud 
- Textblob( Sentimentanalyse)


*Installation der Bibliotheken:*
Die Bibliotheken können mit dem Befehl „pip install -r requirements.txt“ in einem Schritt installiert werden.

##Beispieldatensätze:

Die im Repositorium verwendeten Datensätzen dienen der Demonstration der Skripte. 
Für das Skript zur Datenbereinigung und -anreicherung quantitativer Daten wurde ein Datensatz des Open-Access-Publikationsservers der Humboldt-Universität zu Berlin verwendet. Er ist Teil folgender Publikation: Schmitt, R. (2025). Open-Access-Publikationen der TU9 bei kommerziellen Verlagen von 2019 bis 2023. https://doi.org/10.18452/34059. 
Der Datensatz, der im Skript zur Datenbereinigung und -anreicherung qualitativer Daten verwendet wird, ist ein Transkript eines Interviews, das im Rahmen einer Masterarbeit der Skript-Erstellerin erstellt wurde. Es ist Bestandteil folgender veröffentlichten Masterarbeit: Tuttobene, R. (2024). „Learning by making“. Berliner Handreichungen zur Bibliotheks- und Informationswissenschaft. , 533, https://doi.org/10.18452/29409 
Für die Nutzung der Skripte auf eigene Datensätze muss der Pfad zur Quelldatei ausgetauscht werden.

##Lizenz:

Software: MIT-Lizenz 

Weitere Informationen s. License-Datei (erstellt mit https://choosealicense.com/) 

Lizenzen der Beispieldatensätze:

CC-BY 4.0: 20240825_OpenAPC_raw.csv 
CC-BY-NC-ND: HyLeC.docx  (Einverständniserklärung für Nutzung und Veröffentlichung des Interview-Transkripts im Rahmen der Masterarbeit vorhanden)

##Kontakt: 
tuttobenerosina@gmail.com 
