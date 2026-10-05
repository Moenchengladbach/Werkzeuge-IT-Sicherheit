# SIEM, Logging & Detection

**Security Information and Event Management (SIEM)** umfasst die zentrale Sammlung, Korrelation und Analyse sicherheitsrelevanter Ereignisse. Logging und Detection bilden die Grundlage zur Erkennung verdächtiger Aktivitäten.

## Lernziele

- Logging-Architekturen verstehen
- Sicherheitsereignisse zentral analysieren
- Detection Rules kennenlernen
- Angriffe anhand von Logs erkennen

## Relevanz

SIEM, Logging und Detection bilden die technische Grundlage vieler Security Operations Center (SOC).

## Inhalt

### SIEM & Endpoint Security

- [Wazuh](https://wazuh.com/)
  - **Wofür:** Open-Source-SIEM sowie Extended Detection and Response (XDR)
  - **Relevanz:** Security Monitoring, Threat Detection und Laborumgebungen

### Log Management & Security Analytics

- [OpenSearch](https://opensearch.org/)
  - **Wofür:** Open-Source-Suche, Log-Analyse, Observability und Security Analytics
  - **Relevanz:** Log Management und SIEM-Infrastrukturen

### Endpoint Logging

- [Microsoft Sysmon](https://learn.microsoft.com/de-de/sysinternals/downloads/sysmon)
  - **Wofür:** Detaillierte Protokollierung von Prozessen, Netzwerkverbindungen und Systemaktivitäten
  - **Relevanz:** Windows Logging, Threat Hunting und Incident Detection

### Detection Rules

- [SigmaHQ – Sigma](https://github.com/SigmaHQ/sigma)
  - **Wofür:** Herstellerunabhängiges Format zur Beschreibung von Detection-Regeln für Logereignisse
  - **Relevanz:** Detection Engineering, Threat Hunting und SIEM

### Historische Werkzeuge

- [CISA – Logging Made Easy (LME), archiviert](https://github.com/cisagov/lme-docs)
  - **Wofür:** Vereinfachte Logging- und SIEM-Umgebung
  - **Status:** Historisch – Unterstützung durch CISA seit 22. Mai 2026 eingestellt
  - **Relevanz:** Dokumentation und Nachvollziehen eines früheren Logging-/SIEM-Ansatzes