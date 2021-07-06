# Aufgabe 1 in BDK6.5.3 (wB/öB) P3 Data Librarianship und Programmierung
## 1. Text-Editor der Wahl
Es wurde PyCharm gewählt.

## 2. Eine Python-Bibliothek
simple-categories 0.1.2 - Hiermit werden die Zeilen einer Textdatei gelesen. Die Ausgabe der Ergebnisse erfolgt in Kategorien.
Im persönlichen Gebrauch kann diese README.md davon gelesen werden.
https://pypi.org/project/simple-categories/
 
## 3. Eine Fehlermeldung und Ihre Lösung
print(id_data["result"][uids]["title"])

NameError                                 Traceback (most recent call last)
<ipython-input-35-bb0e30b4cd1e> in <module>
----> 1 print(id_data["result"][uids]["title"])

##### NameError: name 'uids' is not defined
---------
Anstatt uids muss die ID 27708327 eingefügt werden.
 
print(id_data["result"]["27708327"]["title"])

## 4. Was ist JupyterLab?
JupyterLab ist eine neues Interface von Project Jupyter. Es besitzt eine
flexible Benutzeroberfläche und kann diverse Tools zeitgleich ausführen,
um diese nutzen zu können. Weiterhin werden verschiedene Dateiformate unterstüzt,
um diese zu bearbeiten.

## 5. Was ist der große Unterschied zwischen den Webframeworks flask und Django?
Django ist komplexer als flask. Flask ist minimalistischer und ermöglicht
mehr Flexibilität und Entscheidungsfreiheit, da bei Django die Anwendungsmöglichkeiten
bereits vorgegeben sind.
