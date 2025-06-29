# Dezentrales Medizinisches Datenverwaltungssystem

## Überblick

Sicheres Blockchain-System für die Patientendatenverwaltung in einer privaten ästhetischen Klinik in Genf. Vollständige Lösung mit Off-Chain-Verschlüsselung, granularer rollenbasierter Zugriffskontrolle und strenger DSGVO-Konformität mit vollständigem Audit-Trail aller medizinischen Datenzugriffe.

## Gelöstes Problem

- **Medizinische Datensicherheit** : Riskante Zentralisierung von Patientenakten  
- **DSGVO-Konformität** : Schwierigkeit beim Nachweis der Einwilligung und Nachverfolgung von Zugriffen  
- **Interoperabilität** : Isolierte Systeme ohne sichere Kommunikation  
- **Medizinische Prüfung** : Begrenzte Nachverfolgbarkeit von Konsultationen und Änderungen

## Technische Lösung

- **Solidity Standards** : ERC-721 + ERC721Enumerable für Datensatz-Tokenisierung  
- **OpenZeppelin Sicherheit** : AccessControl, ReentrancyGuard, Pausable  
- **Hybride Architektur** : Sensible Daten off-chain verschlüsselt, IPFS-Hash on-chain  
- **Zugriffskontrolle** : Rollenbasiertes System (DOCTOR, NURSE, SECRETARY, AUDITOR)

## Wichtige technische Highlights

- **Erweiterte Verschlüsselung** : Patientendaten vor IPFS-Speicherung verschlüsselt  
- **Vollständiger Audit-Trail** : Nachverfolgbarkeit aller Zugriffe mit Blockchain-Zeitstempel  
- **Notfallzugriff** : Temporäres System für kritische Situationen  
- **Custom Errors** : Gas-effiziente und benutzerfreundliche Fehlerbehandlung  
- **Indizierte Events** : Erweiterte Überwachung und Analytik  
- **Komplexe Modifiers** : Multi-Kriterien-Validierung mit Geschäftslogik

## Meine Rolle

- **Vollständige Architektur** : Design des Rollen- und Berechtigungssystems  
- **Haupt-Smart-Contract** : Vollständige Entwicklung (14 Seiten Solidity-Code)  
- **Blockchain-Sicherheit** : Implementierung fortgeschrittener Sicherheitsmuster  
- **Unit-Tests** : Vollständige Test-Suite für alle Anwendungsfälle

## Status

**Proof of Concept** in Entwicklung – Geschätzte Lieferung Q4 2025  
**Aktuelle Phase**: Sicherheitstests und Gas-Optimierung

## Link

Detailliertes PDF beigefügt – Vollständiges GitHub-Repo auf Anfrage verfügbar

## Architektur

