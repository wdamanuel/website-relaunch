### Test Webprogrammierung 29.05.2024

**Name:**

**Anweisungen:** Beantworten Sie alle Fragen sorgfältig und vollständig. Die maximale Punktzahl für diesen Test beträgt 130 Punkte.

---

#### Teil 1: Planung eines Webprojektes (Relaunch)

**1.1.** Welchen wesentlichen Unterschied gibt es zwischen dem Relaunch einer bestehenden Webseite und der Planung einer neuen Webseite? (5 Punkte)

**1.2** Beschreiben Sie die wesentlichen Schritte bei der Planung eines Website-Relaunchs. (10 Punkte)

**1.3** Warum ist es wichtig, eine Bestandsaufnahme der aktuellen Website durchzuführen? Nennen Sie zwei Gründe. (5 Punkte)

**1.4** Welche Rolle spielt die Zielgruppenanalyse bei einem Website-Relaunch? (5 Punkte)

---

#### Teil 2: Git und Github

**2.1** Erklären Sie, was Git ist und wofür es verwendet wird. (5 Punkte)

**2.2** Was ist Github und wie unterscheidet es sich von Git? (5 Punkte)

**2.3** Erklären Sie jeden der folgenden Begriffe: (10 Punkte)

* Repository
* Branch
* Commit
* Merge
* Pull
* Push
* Clone
* Remote Repository / Origin
* Fetch
* Konflikt

---

#### Teil 3: CSS-Variablen nutzen

**3.1** Was sind CSS-Variablen und warum sind sie nützlich? (5 Punkte)

**3.2** Überarbeite den folgenden CSS-Code, indem du redundante Werte identifizierst und entscheidest, welche in CSS-Variablen ausgelagert werden sollten. Achte auf sinnvolle Variablennamen. (10 Punkte)

```css

/* Farben */
body {
  background-color: #f0f0f0;
}

.header {
  background-color: #333;
  color: #fff;
}

.button {
  background-color: #007bff;
  color: #fff;
  border: none;
  border-radius: 5px;
  padding: 10px 20px;
  cursor: pointer;
}

.card {
  background-color: #fff;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  border-radius: 10px;
  padding: 20px;
}

/* Schriftarten */
h1 {
  font-family: Arial, sans-serif;
}

p {
  font-family: Arial, sans-serif;
}

/* Abstände */
.container {
  margin: 20px;
}

.header {
  padding: 20px;
}

.card {
  margin-bottom: 20px;
}

/* Größen */
.button {
  font-size: 16px;
}

.card {
  width: 300px;
}

```

---

#### Teil 4: Komponentenbasierte Elemente für Websites entwickeln

**4.1** Was versteht man unter komponentenbasiertem Webdesign? (5 Punkte)

**4.2** Nennen Sie zwei Vorteile der Nutzung von komponentenbasierten Elementen. (5 Punkte)

**4.3** Erstellen Sie ein einfaches Beispiel für eine komponentenbasierte HTML-Struktur (Kartenkomponente mit Bild, Titel, Text). (10 Punkte)

```html
<!-- Beispiel HTML-Struktur für eine Kartenkomponente -->

```

---

#### Teil 5: Container Queries

**5.1** Was sind Container Queries und wie unterscheiden sie sich von Media Queries? (5 Punkte)

**5.2** Beschreiben Sie eine Situation, in der Container Queries besonders nützlich sein können. (5 Punkte)

**5.3** Erweitern Sie den folgenden **CSS-Code** um eine Container Query, sodass der Innenabstand eines Elements bis zu einer Containerbreite von 400px (width) 20px beträgt. (10 Punkte)

```css

.container {

}

.box {
  padding: 40px;
}

/* Container Query */

```

```html
<div class="container">
  <div class="box">
    Dies ist eine Beispiel-Box mit variabler Schriftgröße.
  </div>
</div>
```

---

#### Teil 6: Praktische Aufgabe

Sie erhalten ein bestehendes Webprojekt auf Github und sollen einen Relaunch planen und teilweise umsetzen. Gehen Sie wie folgt vor: (30 Punkte)

0. Erstellen Sie ein Repository "Aufgabe6-Webprog" auf Ihren lokalen Rechner und kopieren Sie den Inhalt aus dem Ordner "Daten" hinein.
1. Erstellen Sie den "initial commit"
2. Erstellen Sie einen neuen Branch mit dem Namen "relaunch".
3. **Durchführen der folgenden Änderungen:**
   - **CSS-Variablen:** Definieren Sie sinnvolle CSS-Variablen und verwenden Sie diese in Ihrer CSS-Datei.
   - **Komponentenbasierte Elemente:** Entwickeln Sie eine einfache, komponentenbasierte HTML-Struktur für eine Kartenkomponente, die einen Titel, ein Bild und einen Text enthält.
   - **Container Queries:** Implementieren Sie eine Container Query, um die Schriftgröße der Kartenkomponente basierend auf der Containergröße anzupassen. Verwenden Sie eine Schriftgröße von 1rem bis zu einer Containerbreite von 540px.
4. **Committen Sie Ihre Änderungen:** Geben Sie nach jedem bedeutenden Schritt einen aussagekräftigen Commit-Namen an und committen Sie Ihre Änderungen.
5. **Merge:** Führen Sie einen Merge des "relaunch"-Branches zurück in den Haupt-Branch ("main") durch.
6. Erstellen Sie auf ihrem Github-Account ein neues öffentliches Repository mit dem Namen "Abgabe-Webprog".
7. Notieren Sie hier die URL zu Ihrem Repo auf Github:
8. Pushen Sie Ihr lokales Repository in das neu erstellte Remote-Repository.
9. Speichern Sie zusätzlich alle lokalen Dateien als ZIP-Datei "vorname-nachname.zip" und mailen diese an manuel@startmedia.at