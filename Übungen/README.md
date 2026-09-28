# Übungen & Lernpfad

Dieser Bereich verbindet die im Repository gesammelten Werkzeuge zu praktischen Lern- und Übungsszenarien.

## Lernziele

- Werkzeuge nicht nur einzeln, sondern im Zusammenhang einsetzen
- Angriffe und Sicherheitsereignisse nachvollziehen
- Logs sammeln und analysieren
- Detection Rules entwickeln
- Sicherheitsvorfälle untersuchen
- Sicherheitsmaßnahmen praktisch nachvollziehen

## Relevanz

Praktische Übungen unterstützen den Transfer von theoretischem Wissen in reale Security-Szenarien. Der Lernpfad bietet eine mögliche Reihenfolge, um verschiedene Bereiche und Werkzeuge der IT-Sicherheit kennenzulernen.

## Lernpfad

**Angriff verstehen → Ereignisse erzeugen → Logs sammeln → Angriff erkennen → Detection Rule erstellen → Sicherheitsvorfall analysieren → Maßnahmen einleiten**

### Stufe 1 – Grundlagen

Bundesamt für Sicherheit in der Informationstechnik (BSI) → MITRE ATT&CK → Cyber Agora → Chaos Computer Club (CCC)

**Ziel:** Grundlagen der IT-Sicherheit, typische Angriffstechniken und reale Sicherheitsvorfälle kennenlernen.

### Stufe 2 – Windows Security

Windows → Sysmon → Wazuh → Sigma

**Ziel:** Sicherheitsrelevante Ereignisse auf Windows-Systemen protokollieren und auswerten.

### Stufe 3 – Netzwerk & Open Source Intelligence

DNSDumpster → Netzwerkmonitoring → Analyse

**Ziel:** Open Source Intelligence (OSINT), Netzwerkinformationen und öffentlich verfügbare Infrastrukturinformationen untersuchen.

### Stufe 4 – Schwachstellenanalyse

PingCastle → Vulnerability Scanner → Security Assessment

**Ziel:** Schwachstellen und Fehlkonfigurationen erkennen und bewerten.

### Stufe 5 – Angriff verstehen

Mimikatz → MITRE ATT&CK → Backdoors & Breaches

**Ziel:** Angriffstechniken und mögliche Angriffsabläufe in autorisierten Laborumgebungen nachvollziehen.

### Stufe 6 – Security Information and Event Management & Detection

Sysmon → Wazuh → Sigma → OpenSearch

**Ziel:** Logs sammeln, zentral analysieren und Detection Rules zur Angriffserkennung einsetzen.

### Stufe 7 – Incident Response

Detection → Indicator-of-Compromise-Analyse (IOC) → ANY.RUN → Threat Hunting → Reaktion

**Ziel:** Einen erkannten Sicherheitsvorfall untersuchen, einordnen und geeignete Reaktionsmaßnahmen ableiten.

### Stufe 8 – IT-Forensik

FTK Imager → Autopsy → Volatility → National Software Reference Library (NSRL) / Reference Data Set (RDS)

**Ziel:** Digitale Beweismittel sichern und Datenträger- sowie Arbeitsspeicheranalysen kennenlernen.

### Stufe 9 – Development, Security and Operations

SonarQube → Codeanalyse → Security Findings

**Ziel:** Sicherheitsprobleme während der Softwareentwicklung erkennen und bewerten.

### Stufe 10 – Industrial & Operational Technology Security

PROFINET → IEC 62443 → Operational Technology (OT) Security

**Ziel:** Grundlagen industrieller Netzwerke und Besonderheiten der OT-Sicherheit kennenlernen.

### Stufe 11 – Cloud & Container Security

🚧 **Baustelle – wird mit zukünftigen Werkzeugen und Übungen erweitert.**

## Empfohlene Werkzeug-Reihenfolge

1. MITRE ATT&CK
2. Sysmon
3. Wazuh
4. Sigma
5. OpenSearch
6. ANY.RUN
7. SonarQube
8. PingCastle
9. Ansible
10. Operational Technology (OT) / IEC 62443

## Hinweis

Einige der genannten Werkzeuge können sicherheitskritische Funktionen besitzen. Übungen sollten ausschließlich auf eigenen Systemen, in dafür vorgesehenen Laborumgebungen oder mit ausdrücklicher Genehmigung des jeweiligen Systembetreibers durchgeführt werden.
