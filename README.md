# 👋 Hi, ich bin 66Beastmaster

**BeastWareTeam** – lokale, private und selbstbestimmte Software.

Zentrale Anlaufstelle: [bestware.4lima.de](https://bestware.4lima.de)  
Organisation: [BeastWareTeam](https://github.com/beastwareteam)

---

## 🧞 Zentrales Projekt: Genie AI Platform

**[genie-platform](https://github.com/beastwareteam/genie-platform)** ist die Arbeitsumgebung, die sich beim Benutzen selbst zusammenbaut.

Du sagst in einem Satz, was du brauchst —  
*„eine Tabelle meiner offenen Rechnungen“*,  
*„ein Balkendiagramm der Ausgaben je Monat“*,  
*„ein Browserfenster mit zwei Reitern nebeneinander“* —  

… und daraus entsteht eine **sofort bedienbare Fläche**.  
Kein leeres Formular. Keine Auswahl aus einem Baukasten. Kein Vorschlag, den man noch umsetzen muss.

### Kernprinzipien

- **Lokal zuerst**  
  Sprachmodelle, Sprachausgabe, Texterkennung und Datenbank laufen auf deinem eigenen Rechner.  
  Netz-Dienste sind optional und brauchen explizit deinen Schlüssel.

- **Bausteine statt Tool-Auswahl**  
  160+ Bausteine in 23 Familien – von der einfachen Eingabezeile bis zum Systemmonitor.  
  Die Plattform wählt und kombiniert sie selbst.

- **Rechte & Transparenz**  
  Jede Aktion wird vor der Ausführung einer von drei Rechtestufen zugeordnet.  
  Du behältst die Kontrolle.

- **Deutsch & Englisch** (weitere Sprachen folgen)

📖 **Dokumentation & Landkarte der Bausteine**  
→ [Genie AI Platform (DE)](https://beastwareteam.github.io/genie-platform/de/)  
→ [Genie AI Platform (EN)](https://beastwareteam.github.io/genie-platform/en/)

```bash
git clone https://github.com/beastwareteam/genie-platform.git
cd genie-platform
pip install -e .
python -m genie.main
