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

[Bundesamt für Sicherheit in der Informationstechnik (BSI)](../16%20Behörden,%20Regulierung%20&%20Standards/README.md#bundesamt-für-sicherheit-in-der-informationstechnik-bsi)
→ [MITRE ATT&CK](../16%20Behörden,%20Regulierung%20&%20Standards/README.md#frameworks)
→ [Cyber Agora](../15%20Awareness%20&%20Social%20Engineering/README.md#videos--lernmaterial)
→ [Chaos Computer Club (CCC) / Conti-Fallbeispiel](../06%20Malware%20&%20Angriffsvektoren/README.md#fallbeispiel-conti)

**Ziel:** Grundlagen der IT-Sicherheit, typische Angriffstechniken und reale Sicherheitsvorfälle kennenlernen.

### Stufe 2 – Windows Security

Windows
→ [Sysmon](../10%20SIEM,%20Logging%20&%20Detection/README.md#endpoint-logging)
→ [Wazuh](../10%20SIEM,%20Logging%20&%20Detection/README.md#siem--endpoint-security)
→ [Sigma](../10%20SIEM,%20Logging%20&%20Detection/README.md#detection-rules)

**Ziel:** Sicherheitsrelevante Ereignisse auf Windows-Systemen protokollieren und auswerten.

### Stufe 3 – Netzwerk & Open Source Intelligence

[DNSDumpster](../01%20OSINT%20&%20Reconnaissance/README.md#domain--dns-recherche)
→ [Netzwerk & Netzwerksicherheit](../02%20Netzwerk%20&%20Netzwerksicherheit/README.md)
→ Analyse

**Ziel:** Open Source Intelligence (OSINT), Netzwerkinformationen und öffentlich verfügbare Infrastrukturinformationen untersuchen.

### Stufe 4 – Schwachstellenanalyse

[PingCastle](../03%20Schwachstellenanalyse%20&%20Security%20Testing/README.md#active-directory-sicherheit)
→ [Vulnerability Scanner](../03%20Schwachstellenanalyse%20&%20Security%20Testing/README.md#vulnerability-scanner)
→ Security Assessment

**Ziel:** Schwachstellen und Fehlkonfigurationen erkennen und bewerten.

### Stufe 5 – Angriff verstehen

[Mimikatz](../06%20Malware%20&%20Angriffsvektoren/README.md#credential-dumping)
→ [MITRE ATT&CK](../16%20Behörden,%20Regulierung%20&%20Standards/README.md#frameworks)
→ [Backdoors & Breaches](../07%20Incident%20Response/README.md#incident-response-training)

**Ziel:** Angriffstechniken und mögliche Angriffsabläufe in autorisierten Laborumgebungen nachvollziehen.

### Stufe 6 – Security Information and Event Management & Detection

[Sysmon](../10%20SIEM,%20Logging%20&%20Detection/README.md#endpoint-logging)
→ [Wazuh](../10%20SIEM,%20Logging%20&%20Detection/README.md#siem--endpoint-security)
→ [Sigma](../10%20SIEM,%20Logging%20&%20Detection/README.md#detection-rules)
→ [OpenSearch](../10%20SIEM,%20Logging%20&%20Detection/README.md#log-management--security-analytics)

**Ziel:** Logs sammeln, zentral analysieren und Detection Rules zur Angriffserkennung einsetzen.

### Stufe 7 – Incident Response

Detection
→ [Indicator-of-Compromise-Analyse (IOC) & Threat Hunting](../07%20Incident%20Response/README.md#ioc-analyse--threat-hunting)
→ [ANY.RUN](../06%20Malware%20&%20Angriffsvektoren/README.md#malware-analyse--sandbox)
→ [Incident Response](../07%20Incident%20Response/README.md)

**Ziel:** Einen erkannten Sicherheitsvorfall untersuchen, einordnen und geeignete Reaktionsmaßnahmen ableiten.

### Stufe 8 – IT-Forensik

[FTK Imager](../09%20IT-Forensik/README.md#forensic-imaging)
→ [Autopsy](../09%20IT-Forensik/README.md#datenträger--artefaktanalyse)
→ [Volatility](../09%20IT-Forensik/README.md#speicherforensik)
→ [National Software Reference Library (NSRL) / Reference Data Set (RDS)](../09%20IT-Forensik/README.md#hashsets--referenzdaten)

**Ziel:** Digitale Beweismittel sichern und Datenträger- sowie Arbeitsspeicheranalysen kennenlernen.

### Stufe 9 – Development, Security and Operations

[SonarQube](../11%20DevSecOps/README.md#statische-codeanalyse)
→ Codeanalyse
→ Security Findings

**Ziel:** Sicherheitsprobleme während der Softwareentwicklung erkennen und bewerten.

### Stufe 10 – Industrial & Operational Technology Security

[PROFINET](../13%20Industrial%20&%20OT%20Security/README.md#profinet)
→ IEC 62443
→ [Operational Technology (OT) Security](../13%20Industrial%20&%20OT%20Security/README.md)

**Ziel:** Grundlagen industrieller Netzwerke und Besonderheiten der OT-Sicherheit kennenlernen.

### Stufe 11 – Cloud & Container Security

[Cloud & Container Security](../12%20Cloud%20&%20Container%20Security/README.md)

🚧 **Baustelle – wird mit zukünftigen Werkzeugen und Übungen erweitert.**

## Empfohlene Werkzeug-Reihenfolge

1. [MITRE ATT&CK](../16%20Behörden,%20Regulierung%20&%20Standards/README.md#frameworks)
2. [Sysmon](../10%20SIEM,%20Logging%20&%20Detection/README.md#endpoint-logging)
3. [Wazuh](../10%20SIEM,%20Logging%20&%20Detection/README.md#siem--endpoint-security)
4. [Sigma](../10%20SIEM,%20Logging%20&%20Detection/README.md#detection-rules)
5. [OpenSearch](../10%20SIEM,%20Logging%20&%20Detection/README.md#log-management--security-analytics)
6. [ANY.RUN](../06%20Malware%20&%20Angriffsvektoren/README.md#malware-analyse--sandbox)
7. [SonarQube](../11%20DevSecOps/README.md#statische-codeanalyse)
8. [PingCastle](../03%20Schwachstellenanalyse%20&%20Security%20Testing/README.md#active-directory-sicherheit)
9. Ansible
10. [Operational Technology (OT) / IEC 62443](../13%20Industrial%20&%20OT%20Security/README.md)

## Hinweis

Einige der genannten Werkzeuge können sicherheitskritische Funktionen besitzen. Übungen sollten ausschließlich auf eigenen Systemen, in dafür vorgesehenen Laborumgebungen oder mit ausdrücklicher Genehmigung des jeweiligen Systembetreibers durchgeführt werden.
