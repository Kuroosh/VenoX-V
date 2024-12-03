---

### Vollständige `bug_report.md` mit Systeminformationen

```markdown
---
name: 🐛 Bug Report
about: Melde einen Fehler, der im Projekt aufgetreten ist
title: "[BUG]:"
labels: bug
assignees: ''
---

# 🐛 Bug Report

**Beschreibung des Problems**
<!-- Beschreibe das Problem so detailliert wie möglich. Was ist passiert, und was hast du erwartet, das passieren sollte? -->

**Schritte zur Reproduktion**
<!-- Beschreibe die Schritte, um das Problem zu reproduzieren. Gib möglichst genaue Details an. -->
1. Schritt 1
2. Schritt 2
3. Schritt 3

**Erwartetes Verhalten**
<!-- Beschreibe, was deiner Meinung nach hätte passieren sollen. -->

**Screenshots / Logs**
<!-- Wenn möglich, füge Screenshots oder Log-Dateien bei, die das Problem verdeutlichen. -->
- Screenshot oder Bild:
- Log-Auszug (falls relevant):
  ```log
  [Füge hier relevante Logdaten ein]
  ```

---

### **Systeminformationen**
<!-- Fülle bitte alle verfügbaren Felder aus. Je mehr Details, desto besser! -->

- **Betriebssystem:** 
  <!-- Beispiel: Windows 10 Pro 64-bit, Linux Ubuntu 22.04, macOS Ventura -->
- **Spiel-Version:** 
  <!-- Beispiel: VenoX RP v1.2.3 -->
- **Server-Version (falls bekannt):** 
  <!-- Beispiel: FiveM 5848 -->
- **Prozessor (CPU):** 
  <!-- Beispiel: Intel Core i7-9700K, AMD Ryzen 5 5600X -->
- **Grafikkarte (GPU):** 
  <!-- Beispiel: NVIDIA GeForce GTX 1080 Ti, AMD Radeon RX 6800 -->
- **Arbeitsspeicher (RAM):** 
  <!-- Beispiel: 16 GB DDR4 3200 MHz -->
- **Speicher (Festplatte):** 
  <!-- Beispiel: SSD 500 GB, HDD 1 TB -->
- **Internetverbindung:** 
  <!-- Beispiel: 50 Mbit/s Download, 10 Mbit/s Upload -->
- **Andere relevante Hardware:** 
  <!-- Beispiel: USB-Controller, Joystick, spezielles Headset -->

---

**Zusätzliche Informationen**
<!-- Alles andere, das hilfreich sein könnte, wie z. B. Ideen für mögliche Ursachen, Zusammenhänge mit anderen Fehlern oder eine mögliche Lösung. -->
```

---

### **Einfügen in die `bug_report.md`**
1. Kopiere den kompletten Code oben.
2. Erstelle eine neue Datei im `.github/ISSUE_TEMPLATE/`-Ordner deines Repositories mit dem Namen `bug_report.md` (falls nicht schon vorhanden).
3. Füge den kopierten Inhalt in die Datei ein.
4. Speichere die Änderungen und commite sie direkt in die Haupt-Branch oder öffne einen Pull Request, wenn du in einem Team arbeitest.

Jetzt ist der **Systeminformationen**-Abschnitt vollständig in der Bug-Report-Vorlage enthalten. Wenn ein Nutzer ein neues Issue erstellt, wird dieser Abschnitt automatisch angezeigt, und die Nutzer können ihre Hardware-Spezifikationen angeben.
