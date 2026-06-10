# Bachelorarbeit – Strukturierte Schmerzlokalisierung mittels 3D-Körpermodell

**Berner Fachhochschule (BFH) – Institut für Medizinische Informatik (I4MI)**  
Modul BTI3051/BTX8221 | 2025/2026

## Projektbeschreibung

Diese Bachelorarbeit beschreibt die Konzeption und prototypische Umsetzung einer strukturierten Schmerzlokalisierung mittels eines interaktiven, SNOMED-CT-segmentierten 3D-Körpermodells mit openEHR-basierter Datenpersistenz im Zusammenhang mit der mobilen Gesundheitsanwendung **Health Capture**.

Patientinnen und Patienten können Schmerzregionen direkt auf einem 3D-Körpermodell einzeichnen. Die gezeichneten Bereiche werden automatisch auf SNOMED-CT-Konzepte gemappt und strukturiert in einem Clinical Data Repository (CDR) gespeichert.

## Autorinnen und Autoren

| Rolle | Person |
|---|---|
| Autorin (Medizininformatik) | Chiara Stampfli |
| Autor (Medizininformatik) | Ovian Ramanathas |
| Betreuung | Michaël Laurac (BFH) |
| Experte | Mauro Welte (H+) |
| Interaktionsdesign | Ursula Stampfli |
| Flutter-Implementierung | Paul Mattheus |

## Technologien

- **3D-Körpermodell** – SNOMED-CT-segmentiert (CHOIR-Regionen, Dermatome, periphere Nerventerritorien)
- **Terminologie** – SNOMED CT 
- **Datenpersistenz** – openEHR Archetyp `CLUSTER.anatomical_location.v1`, Template PainLocV6, Better CDR

## Lizenz

Alle Rechte vorbehalten. Dieses Repository ist nicht zur Weiterverwendung freigegeben.
© 2026 Chiara Stampfli, Ovian Ramanathas
