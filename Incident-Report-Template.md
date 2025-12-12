# 🚨 Incident Report Template

This document serves as the formal record for the Security Incident Response Team (IRT) for all security incidents handled.

## 1. Basisinformationen (Basic Information)

| Feld | Eingabe (Input) |
| :--- | :--- |
| **Incident ID** | [Unique ID: IR-YYYYMMDD-XXX] |
| **Datum / Uhrzeit der Entdeckung** | [TT.MM.JJJJ, HH:MM UTC] |
| **Datum / Uhrzeit des Beginns (geschätzt)** | [TT.MM.JJJJ, HH:MM UTC] |
| **Meldender / Entdecker** | [Name / System] |
| **Status** | [Offen / In Bearbeitung / Geschlossen / Falsch Positiv] |

---

## 2. Beschreibung (Description)

### Beschreibung des Vorfalls:
[Detaillierte Beschreibung des beobachteten Ereignisses, der Auswirkungen und der Indikatoren. Was ist passiert? Wer war beteiligt?]

### Betroffene Systeme (Affected Systems):
| Systemtyp (z.B. Server, Endpoint) | Hostname / IP | Funktion | Asset Owner |
| :--- | :--- | :--- | :--- |
| | | | |
| | | | |

---

## 3. Maßnahmen (Response Actions)

### 3.1. Eindämmung (Containment)
[Welche sofortigen Schritte wurden zur Isolierung des Vorfalls unternommen? Z.B.: Trennung vom Netzwerk, Sperrung von Konten.]

### 3.2. Beseitigung (Eradication)
[Welche Schritte wurden zur vollständigen Entfernung der Bedrohung durchgeführt? Z.B.: Löschen von Malware, Entfernen von Backdoors.]

### 3.3. Wiederherstellung (Recovery)
[Welche Schritte wurden unternommen, um die betroffenen Systeme wieder in den Normalbetrieb zu versetzen? Z.B.: Patches aufspielen, Systeme neu starten.]

---

## 4. RCA (Root Cause Analysis)

### Ursache des Vorfalls:
[Die primäre technische oder prozessuale Schwachstelle, die zur Kompromittierung geführt hat. Z.B.: Ungepatchte Software, Phishing, Fehlkonfiguration.]

### Präventionsmöglichkeiten:
[Wie hätte dieser Vorfall verhindert werden können?]

---

## 5. Lessons Learned (Gelernte Lektionen)

### Technische Verbesserungen:
[Z.B.: Einführung von MFA, Verbesserung des Network Segmentation.]

### Prozessuale Verbesserungen:
[Z.B.: Anpassung des IR-Plans, Verbesserung der Schulung.]

### Datum und Genehmigung:
**IR-Team-Leitung:** [Name]
**Datum der Schließung:** [TT.MM.JJJJ]
