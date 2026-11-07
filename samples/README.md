# 📦 BSI TR-02102-1, NIS-2 (§ 30 / § 38 BSIG), CRA & TR-03185 — Audit Samples & `.xlsx` Enterprise Suites

Willkommen im `samples/`-Verzeichnis des **[DE-Compliance-Kompass](https://kenanerorr404.github.io/de-compliance-kompass/)**. Hier finden Sie die kostenlose CSV-Prüfungs-Leseprobe (`BSI-Audit-Matrix-Leseprobe.csv`) sowie die direkte Übersicht über alle **9 Dateien** bzw. **5 Dateien** unserer schlüsselfertigen `.xlsx` Enterprise-Compliance-Toolkits.

[![Claim €0+ Starter Pack](https://img.shields.io/badge/%F0%9F%93%A5_Claim_%E2%82%AC0%2B_Starter_Pack-Free_Download-16a34a?style=for-the-badge)](https://kenanghalioun.gumroad.com/l/flcsb)
[![Unlock 45-Row PQC .xlsx Suite (-20%)](https://img.shields.io/badge/%F0%9F%94%90_Unlock_TR--02102_PQC_.xlsx_Suite_%289_Files%29-%E2%82%AC39.20_%2820%25_OFF%29-1d4ed8?style=for-the-badge)](https://kenanghalioun.gumroad.com/l/wcqysh/BSI2026PRO)
[![Unlock TR-03185 / DiGA .xlsx Suite (-20%)](https://img.shields.io/badge/%F0%9F%9B%A1%EF%B8%8F_Unlock_TR--03185_%26_DiGA_.xlsx_Suite_%285_Files%29-%E2%82%AC39.20_%2820%25_OFF%29-0f172a?style=for-the-badge)](https://kenanghalioun.gumroad.com/l/juznqz/BSI2026PRO)

---

## ⚡ Sofort-Zugriff (1-Klick Direktlinks inkl. `-20 %` Community-Rabatt `BSI2026PRO`)

1. 📥 **[€0+ Starter Pack kostenlos auf Gumroad herunterladen (`flcsb`)](https://kenanghalioun.gumroad.com/l/flcsb)** — CSV-Audit-Leseprobe + Upgrade-Leitfaden.
2. 🔐 **[Vollständiges 45-Zeilen `.xlsx` CBOM-Workbook + OpenSSH/OpenSSL/Nginx Configs freischalten — €39,20 statt €49 (-20 % angewendet)](https://kenanghalioun.gumroad.com/l/wcqysh/BSI2026PRO)**
3. 🛡️ **[Vollständiges TR-03185, CRA-SBOM & DiGA `.xlsx` Audit-Workbook freischalten — €39,20 statt €49 (-20 % angewendet)](https://kenanghalioun.gumroad.com/l/juznqz/BSI2026PRO)**
4. 🧮 **[Kostenloser interaktiver BSI PQC & NIS-2 Bußgeld-/Risiko-Rechner im Browser](https://kenanerorr404.github.io/de-compliance-kompass/pqc-nis2-rechner.html)**

---

## 📂 Vorschau aller 9 Dateien in der `BSI TR-02102-1 PQC & CBOM Enterprise-Suite` ([`wcqysh/BSI2026PRO`](https://kenanghalioun.gumroad.com/l/wcqysh/BSI2026PRO))

| # | Datei im Enterprise-ZIP | Typ | Prüfzweck & enthaltener Inhalt | In `samples/` (Free) | Im Enterprise-Pack (€39,20) |
| :-: | :--- | :--- | :--- | :-: | :-: |
| **1** | `BSI-TR-02102-CBOM-und-Risiko-Matrix-2031.xlsx` | **Excel Workbook (3 Tabs)** | **Tab 1:** Executive KPI-Dashboard (Live-Formeln) · **Tab 2:** **45 vorbefüllte CBOM-Assets** (TLS 1.3, SSHv2, IPsec/IKEv2, PKI/CA, KMS/HSM, DB/Backup) inkl. HNDL-Scoring & BSI-Ablaufdatum 2031/2035 · **Tab 3:** § 38 BSIG Audit Sign-Off Log | Nur 3 Zeilen (`.csv`) | ✅ **Vollständig (45 Zeilen + Formeln)** |
| **2** | `Krypto-Inventar-PQC-2031.csv` | **CSV Import** | Maschinenlesbarer 45-Zeilen CBOM-Datensatz für GRC-Import (Jira, ServiceNow, Confluence, C5:2026 CRY-01) | Auszug | ✅ **Vollständig** |
| **3** | `PQC-Migrationsplan-2026-2031.md` | **Roadmap SOP** | 3-Phasen-Architekturfahrplan gemäß BSI TR-02102-1 & Nationaler PQC-Leitlinie (BMI/BMDS/BSI Okt. 2026) | ❌ | ✅ **Enthalten** |
| **4** | `Management-Vorlage-Haftungsfreistellung-BSIG38.html` | **A4 GF-Vorlage** | Druckfertiger Geschäftsführungs-Beschluss & Budgetfreigabe zur persönlichen Haftungsentlastung nach **§ 38 BSIG** | ❌ | ✅ **Enthalten** |
| **5** | `configs/sshd_config_bsi_tr02102_4_pqc.conf` | **OpenSSH 9.9+** | Drop-in Hardening-Config (`mlkem768x25519-sha256`, Abschaltung `ssh-rsa` / SHA-1 nach BSI TR-02102-4) | ❌ | ✅ **Enthalten** |
| **6** | `configs/openssl_3_5_pqc_hybrid.cnf` | **OpenSSL 3.5+** | Drop-in Hybrid-KEM Config (`X25519MLKEM768` / `SecP256r1MLKEM768` + TLS 1.3 Cipher-Policy) | ❌ | ✅ **Enthalten** |
| **7** | `configs/nginx_tls13_bsi_tr02102_2.conf` | **Nginx Ingress** | Produktionsfertige TLS 1.3 Reverse-Proxy-Härtung nach **BSI TR-02102-2** & C5:2026 CRY-02 | ❌ | ✅ **Enthalten** |
| **8** | `ci-cd/github-action-cbom-audit.yml` | **GitHub Action** | Automatisiertes CI/CD-Audit-Gate mit JSON/CSV CBOM-Artefakt-Archivierung für CRA Anhang VII & C5 | ❌ | ✅ **Enthalten** |
| **9** | `ci-cd/gitlab-ci-cbom-audit.yml` | **GitLab CI** | Schlüsselfertige GitLab-Pipeline für kontinuierliche Krypto-Compliance-Prüfungen | ❌ | ✅ **Enthalten** |

👉 **[🔐 Alle 9 Dateien jetzt für €39,20 statt €49 herunterladen (20 % Rabattcode `BSI2026PRO` automatisch aktiv)](https://kenanghalioun.gumroad.com/l/wcqysh/BSI2026PRO)**

---

## 🛡️ Vorschau aller 5 Dateien im `BSI TR-03185, CRA-SBOM & DiGA Audit-Pack` ([`juznqz/BSI2026PRO`](https://kenanghalioun.gumroad.com/l/juznqz/BSI2026PRO))

| # | Datei im Enterprise-ZIP | Typ | Prüfzweck & enthaltener Inhalt | Im Enterprise-Pack (€39,20) |
| :-: | :--- | :--- | :--- | :-: |
| **1** | `BSI-TR-03185-und-DiGA-TR03161-Audit-Workbook.xlsx` | **Excel Workbook (3 Tabs)** | Readiness-Dashboard + **3-Klassen-Patch-Matrix (Klasse A/B/C)** für 24h/72h-Updates ohne Rezertifizierung + BfArM DiGA TR-03161 Mapping | ✅ **Vollständig** |
| **2** | `TR-03185-Prozess-Audit-Matrix.csv` | **CSV Import** | Vollständiger Prüfkatalog für Jira / GitLab / Azure DevOps Compliance-Tracking | ✅ **Vollständig** |
| **3** | `SOP-Sicherer-Release-Prozess-TR03185.md` | **Release SOP** | Auditfeste Verfahrensanweisung für CRA-Durchführungsgesetz, NIS-2 Lieferkette (§ 30 BSIG) & C5 DEV | ✅ **Enthalten** |
| **4** | `Checkliste-Update-Ohne-Rezertifizierung.html` | **A4 Protokoll** | Druckbares Patch-Klassifizierungs- und Freigabeformular für Prüfer & Benannte Stellen | ✅ **Enthalten** |
| **5** | `ci-cd/tr03185-release-gate.yml` | **SBOM CI/CD Gate** | Automatisierte **CycloneDX SBOM-Generierung nach BSI TR-03183-2**, SAST/CVE-Check & Release-Signierung | ✅ **Enthalten** |

👉 **[🛡️ Alle 5 Dateien jetzt für €39,20 statt €49 herunterladen (20 % Rabattcode `BSI2026PRO` automatisch aktiv)](https://kenanghalioun.gumroad.com/l/juznqz/BSI2026PRO)**

---

## 📊 Auszug aus dem 45-Zeilen CBOM-Workbook (`BSI-Audit-Matrix-Leseprobe.csv`)

| Asset-ID | System / Dienst | BSI-Referenz | Aktueller Algorithmus | BSI-Frist | HNDL-Risiko | Hybride PQC-Zielarchitektur |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| `CBOM-001` | Public Ingress Load Balancer | BSI TR-02102-2 | `ECDHE-RSA-AES256-GCM` (`RSA-2048`) | `2031-12-31` | **KRITISCH** | TLS 1.3 Hybrid Groups: `X25519MLKEM768` / `SecP256r1MLKEM768` |
| `CBOM-002` | Customer Identity & SSH Bastion | BSI TR-02102-4 | `curve25519-sha256` / `ssh-rsa` | `2031-12-31` | **KRITISCH** | OpenSSH >= 9.9 `KexAlgorithms mlkem768x25519-sha256` |
| `CBOM-003` | B2B Partner IPsec / IKEv2 VPN | BSI TR-02102-3 | `ECDH BrainpoolP384r1` | `2031-12-31` | **KRITISCH** | RFC 9370 Multiple Key Exchanges + `ML-KEM-1024` |
| **`CBOM-004` … `CBOM-045`** | *PKI, mTLS Mesh, KMS/HSM, PostgreSQL TDE, S3 Backups, Code-Signing …* | *BSI TR-02102-1..4* | *42 weitere Enterprise-Zeilen im `.xlsx` Workbook* | *2031 / 2035* | *Auto-KPI* | **[🔓 Vollversion freischalten (-20 %)](https://kenanghalioun.gumroad.com/l/wcqysh/BSI2026PRO)** |

---

### 🏢 B2B-Rechnungskauf (SEPA-Überweisung, 14 Tage Zahlungsziel)
Unternehmen, Behörden und KRITIS-Betreiber erhalten über Gumroad automatisch eine EU-USt.-konforme Rechnung (inkl. USt-IdNr.-Feld) oder können direkt auf unserem Portal **[DE-Compliance-Kompass](https://kenanerorr404.github.io/de-compliance-kompass/)** per **„🏢 B2B-Bestellung auf Rechnung (SEPA)"** bestellen.
