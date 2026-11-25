# Mein Arbeitsrepo — JavaScript V2

Deine persönliche Sammelstelle für den Kurs: **Labs, Übungen, Screenshots, Projekte und dein Abschlussprojekt** entstehen alle in diesem Repository — jede Aufgabe nach demselben Muster.

---

## Erst mal ganz einfach: Was ist das hier?

- **GitHub** ist ein Speicherort im Internet für Code. Wie ein Ordner, nur online.
- Ein **Repository** (kurz „Repo") ist so ein Ordner mit deinen Dateien und deren Änderungshistorie.
- Ein **Template** (Vorlage) ist ein Repo, aus dem man sich Kopien macht. **Dieses Repo ist die Vorlage.**
- Deine Kopie davon ist **dein Arbeitsrepo**. Nur du arbeitest darin — die Vorlage bleibt unberührt.

---

## Schritt für Schritt: Dein Arbeitsrepo anlegen (einmalig)

1. **Bei GitHub einloggen.** (Account noch nicht vorhanden? Auf github.com kostenlos registrieren — Benutzername, E-Mail, Passwort.)
2. **Die Vorlage öffnen** — du bist ja schon hier. 😊
3. **Oben rechts auf den grünen Knopf „Use this template"** klicken, dann **„Create a new repository"**.
4. **Repository-Name eintragen**, z. B. `js-v2-arbeit-anna` oder `js-v2-meine-arbeit`.
5. **„Public"** (öffentlich) wählen — so kann die Lehrkraft deine Arbeit sehen, ohne Zugang beantragen zu müssen.
6. Auf **„Create repository"** klicken. **Fertig — das ist jetzt dein Arbeitsrepo.**

&gt; **Merke:** Der „Use this template"-Knopf macht eine **eigenständige Kopie**. Du kannst alles ändern, ohne die Vorlage anzufassen. Und einmal angelegt, sammelt dein Repo den ganzen Kurs über alles.

---

## So arbeitest du damit

### 1. Repo auf deinen Rechner holen
In deinem Repo auf **„Code" → „Download ZIP"** klicken und entpacken. Den Ordner in VS Code öffnen.

### 2. Für jede neue Aufgabe: einen Ordner nach demselben Muster
Pro Lab, Übung oder Projekt legst du einen eigenen Ordner an:

​```
js-v2-arbeit-anna/
├── index.html                  ← deine Übersichtsseite (Hub)
├── css/ style.css              ← deine Stile
├── js/ app.js                  ← dein JavaScript
├── labs/
│   ├── lab-01-variablen/
│   │   ├── index.html          ← jede Aufgabe bekommt ihre eigene index.html
│   │   └── ...
│   └── lab-02-bedingungen/
├── uebungen/
│   └── uebung-01/
├── screenshots/                ← Belege & Zwischenstände als Bilder
├── projekte/
│   └── projekt-1/
└── abschlussprojekt/
​```

- Jede Aufgabe bekommt **ihre eigene `index.html`** — aufgebaut wie die Übersichtsseite: HTML-Grundgerüst, CSS verlinkt, JavaScript mit `defer` im Head.
- Auf der **Übersichtsseite** (`index.html` im Hauptordner) trägst du jedes Mal einen Link zu deiner neuen Aufgabe ein (Beispiel steht als Kommentar im Code).
- **Screenshots** kommen in den `screenshots/`-Ordner — z. B. als Beleg, dass dein Code läuft.

### 3. Zwischenstände sichern
Immer wenn etwas funktioniert: Änderungen **committen** („Commit changes" — kurzer Satz, was du gemacht hast). So kann nichts verloren gehen und die Lehrkraft sieht deine Fortschritte.

### 4. Im Browser prüfen
`index.html` in VS Code mit der **Live-Server-Erweiterung** öffnen — jede Änderung siehst du sofort.

### 5. Veröffentlichen (für das Abschlussprojekt)
Repo → **Settings → Pages → Source: „Deploy from a branch"** → Branch `main`, Folder `/ (root)` → Save. Nach 1–2 Minuten läuft dein Projekt unter `https://&lt;dein-benutzername&gt;.github.io/&lt;dein-repo&gt;/`.

---

## Die Projekte (ab Kapitel 11)

Du wählst aus dem **Katalog** oder reichst ein **Eigenprojekt** ein:

1. **Highscore-Spiel** — Browser-Spiel mit Punktezählung und Highscore-Liste
2. **Formular-Meister** — mehrstufiges Formular mit Live-Validierung
3. **Sicherheits-Audit** — Demoseite mit typischen Web-Schwachstellen
4. **Eigenantrag** — deine Idee (kurz beschreiben und absegnen lassen)

### Anforderungen (Mindeststandard)

- Mindestens **2 JavaScript-Features** (z. B. Validierung, Local Storage, dynamisches Rendern)
- Saubere Trennung: HTML (Inhalt), CSS (Gestaltung), JS (Verhalten)
- **Responsive**: funktioniert am Handy (ab 360 px) und am Desktop
- Veröffentlicht mit **GitHub Pages**

---

## Gute Gewohnheiten

- Keine fremden Bilder ohne Quellenangabe, keine personenbezogenen Daten.
- Ordner- und Dateinamen klein, mit Bindestrichen: `lab-01-variablen`, nicht `Lab 01 Variablen!`.
- Teste am Handy (Browser-Entwicklerwerkzeuge → Geräte-Emulation 360 px).
- Fragen? Das Tutorial: https://www.pantam.at/tutorials/js-classic-v2/

## Lizenz

MIT — siehe [LICENSE](LICENSE).
