# Security Checklist – OLRT

Tento soubor slouží k evidenci nastavení bezpečnostních funkcí repozitáře.

## 1. Dokumentace
- [x] SECURITY.md vytvořen (root repozitáře)
- [x] README odkazuje na SECURITY.md (doporučeno zkontrolovat)

## 2. GitHub Security Settings (stav k 2025-08-27)
- [x] Private vulnerability reporting → Enabled
- [x] Dependency graph → Enabled (součást konfigurace)
- [x] Dependabot alerts → Enabled
- [x] Dependabot security updates → Enabled (součást GitHub recommended)
- [x] Code scanning (CodeQL) → Enabled
- [x] Secret Protection (Secret scanning) → Enabled
- [ ] Push protection → volitelné, zatím neaktivní

## 3. Proces
- [x] Otestováno vytvoření draft security advisory
- [x] Otestováno „Report a vulnerability“ (privátní hlášení)

## 4. Správa
- [x] Přístup k alertům mají admini a security managers
- [ ] Periodická kontrola (1× za čtvrtletí)
