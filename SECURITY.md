# Security Policy

<p align="center"><a href="#english">🇬🇧 English</a> · <a href="#italiano">🇮🇹 Italiano</a></p>

## English
### Supported versions
Security fixes target the latest maintained revision of this repository. For upstream code, also consult the upstream project's supported versions and advisories.

### Scope
Fork-specific RFNM changes, build configuration, modules, hardware interfaces and integration points maintained in this fork. Vulnerabilities in unchanged upstream SDR++ code should also be coordinated with upstream.

### Reporting
Do not open a public issue for an unpatched vulnerability. Use GitHub private vulnerability reporting / Security Advisories when available. Include affected commit/version, impact, reproducible steps or minimal proof of concept, platform/hardware assumptions and possible mitigations. Remove unrelated sensitive data.

### Responsible and legal use
Use the project only with devices, systems and signals you own or are explicitly authorized to receive, analyze or modify. Applicable radio, privacy and communications law takes precedence over project documentation.

### Security requirements
Never commit secrets or private captures. Treat device input, paths, downloaded archives, package sources and configuration as untrusted. Verify upstream sources where practical, use least privilege, and carefully review commands that install system components or access hardware. Preserve upstream security fixes when rebasing/merging. Do not weaken device bounds or load untrusted modules/configuration without clear user control.

## Italiano
### Versioni supportate
Le correzioni riguardano la revisione mantenuta più recente di questo repository. Per il codice upstream consulta anche versioni supportate e advisory del progetto originario.

### Ambito
Fork-specific RFNM changes, build configuration, modules, hardware interfaces and integration points maintained in this fork. Vulnerabilities in unchanged upstream SDR++ code should also be coordinated with upstream.

### Segnalazione
Non aprire issue pubbliche per vulnerabilità non corrette. Usa la segnalazione privata / Security Advisories quando disponibile. Indica commit/versione, impatto, passaggi riproducibili o PoC minimo, assunzioni su piattaforma/hardware e mitigazioni, eliminando dati sensibili non necessari.

### Uso responsabile e legale
Usa il progetto solo con dispositivi, sistemi e segnali che possiedi o che sei esplicitamente autorizzato a ricevere, analizzare o modificare. Le norme applicabili in materia radio, privacy e comunicazioni prevalgono sulla documentazione.

### Requisiti di sicurezza
Non committare segreti o acquisizioni private. Considera non fidati input dei dispositivi, percorsi, archivi scaricati, sorgenti pacchetti e configurazione. Verifica le fonti upstream quando possibile, usa privilegi minimi e controlla attentamente i comandi che installano componenti di sistema o accedono all'hardware. Preserve upstream security fixes when rebasing/merging. Do not weaken device bounds or load untrusted modules/configuration without clear user control.
