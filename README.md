# 🇩🇪 DE-Compliance-Kompass — BSI TR-02102 (PQC 2031), NIS-2 (§ 30 / § 38 BSIG), CRA, TR-03185 & E-Rechnung 2027

[![Live Portal & Rechner](https://img.shields.io/badge/%E2%9A%A1_Interaktiver_PQC_%26_NIS--2_Rechner-Live_im_Browser-2563eb?style=for-the-badge)](https://kenanerorr404.github.io/de-compliance-kompass/pqc-nis2-rechner.html)
[![Claim €0+ Starter Pack](https://img.shields.io/badge/%F0%9F%93%A5_Gratis_CSV--Leseprobe_%28%E2%82%AC0%2B%29-Sofort--Checkout-16a34a?style=for-the-badge)](https://kenanghalioun.gumroad.com/l/flcsb?wanted=true)
[![Unlock 9-File PQC .xlsx Suite (-20%)](https://img.shields.io/badge/%F0%9F%94%90_9--Dateien_PQC_%26_CBOM_.xlsx_Suite-%E2%82%AC39%2C20_%2820%25_OFF%29-1d4ed8?style=for-the-badge)](https://kenanghalioun.gumroad.com/l/wcqysh/BSI2026PRO?wanted=true)
[![Unlock 5-File TR-03185 .xlsx Suite (-20%)](https://img.shields.io/badge/%F0%9F%9B%A1%EF%B8%8F_5--Dateien_TR--03185_%26_DiGA_.xlsx_Suite-%E2%82%AC39%2C20_%2820%25_OFF%29-0f172a?style=for-the-badge)](https://kenanghalioun.gumroad.com/l/juznqz/BSI2026PRO?wanted=true)

Technisches Open-Source-Prüfwerkzeug (`bsi_pqc_check.py`), interaktiver Risiko-Kalkulator und B2B-Fachleitfäden für **CISOs, DevSecOps-Teams, Software-/DiGA-Hersteller, KRITIS-Zulieferer und IT-Prüfer** in Deutschland.

---

## ⚡ 1. Sofort-Scan im geklonten Repository (`bsi_pqc_check.py` direkt enthalten!)

Dieses Repository enthält den **Zero-Dependency Linux CLI-Scanner (`bsi_pqc_check.py`)** direkt im Hauptverzeichnis (100 % Python Standard Library — keine Drittanbieter-Pakete erforderlich). Er prüft lokale `sshd_config`-, `openssl.cnf`- und X.509-Zertifikate automatisiert gegen das **BSI-Auslaufszenario 2031 (`BSI TR-02102-1/-2/-4`)** und **§ 30 Abs. 2 Nr. 8 BSIG (NIS-2)**:

```bash
# 1. Direkt nach dem Klonen lokal ausführen (erzeugt Terminal-Audit + HTML-Report + CBOM-CSV-Vorschau):
python3 bsi_pqc_check.py --generate-cbom-csv

# 2. Oder für CI/CD-Pipelines mit strukturiertem JSON-Export (CRA Anhang VII / C5:2026 CRY-Nachweis):
python3 bsi_pqc_check.py --json-out cbom_findings.json

# 3. Zero-Install One-Liner für beliebige Linux-Server:
curl -sSL https://raw.githubusercontent.com/KenanErorr404/de-compliance-kompass/main/bsi_pqc_check.py | python3 -
```

* 🧮 **60-Sekunden Browser-Schnelltest (0 Cookies, 100 % clientseitig):** **[BSI PQC & NIS-2 Risiko- und Bußgeld-Rechner öffnen](https://kenanerorr404.github.io/de-compliance-kompass/pqc-nis2-rechner.html)**
* 📄 **Kostenlose CSV-Leseprobe im Repo:** [`samples/BSI-Audit-Matrix-Leseprobe.csv`](samples/BSI-Audit-Matrix-Leseprobe.csv) oder **[📥 €0+ Starter Pack direkt herunterladen](https://kenanghalioun.gumroad.com/l/flcsb?wanted=true)**

---

## 📦 2. Schlüsselfertige `.xlsx` Enterprise-Compliance-Suites (`-20 %` Code `BSI2026PRO` automatisch aktiv)

Für Unternehmen, die über den Host-Scan hinaus sofort **prüfungsfertige Excel-Workbooks (`.xlsx` mit Live-KPI-Formeln), Drop-in Server-Configs, CycloneDX-SBOM-Pipelines und § 38 BSIG Geschäftsführungs-Beschlussvorlagen** benötigen:

### 🔐 Paket A: `BSI TR-02102-1 PQC & CBOM Enterprise-Migrations-Toolkit` — **39,20 € statt 49 €**
[![1-Click Checkout PQC Suite](https://img.shields.io/badge/%E2%9A%A1_Jetzt_9--Dateien_PQC_.xlsx_Toolkit_freischalten_%28%E2%82%AC39%2C20%29-Direkt--Checkout-1d4ed8?style=for-the-badge)](https://kenanghalioun.gumroad.com/l/wcqysh/BSI2026PRO?wanted=true)

| # | Datei im Enterprise-ZIP | Typ | Prüfzweck & enthaltener Inhalt | Free Repo | Enterprise (`€39,20`) |
| :-: | :--- | :--- | :--- | :-: | :-: |
| **1** | `BSI-TR-02102-CBOM-und-Risiko-Matrix-2031.xlsx` | **Excel Workbook (3 Tabs)** | **Tab 1:** Executive KPI-Dashboard (Live-Formeln) · **Tab 2:** **45 vorbefüllte CBOM-Assets** (TLS 1.3, SSHv2, IPsec/IKEv2, PKI/CA, KMS/HSM, DB/Backup, AS4/ERP) inkl. HNDL-Scoring & Frist 2031/2035 · **Tab 3:** § 38 BSIG Sign-Off-Log | 3 Zeilen (`.csv`) | ✅ **Vollständig (45 Zeilen + Formeln)** |
| **2** | `Krypto-Inventar-PQC-2031.csv` | **CSV Import** | Maschinenlesbarer 45-Zeilen CBOM-Datensatz für Jira, ServiceNow, Confluence & BSI C5:2026 (`CRY-01`) | Auszug | ✅ **Vollständig** |
| **3** | `PQC-Migrationsplan-2026-2031.md` | **Roadmap SOP** | Mehrstufiger Architekturfahrplan gemäß BSI TR-02102-1 & Nationaler PQC-Leitlinie (BMI/BMDS/BSI) | ❌ | ✅ **Enthalten** |
| **4** | `Management-Vorlage-Haftungsfreistellung-BSIG38.html` | **A4 GF-Vorlage** | Druckfertiger Geschäftsleitungs-Beschluss zur persönlichen Haftungsentlastung nach **§ 38 BSIG** | ❌ | ✅ **Enthalten** |
| **5** | `configs/sshd_config_bsi_tr02102_4_pqc.conf` | **OpenSSH 9.9+** | Drop-in Hardening-Config (`mlkem768x25519-sha256`, Abschaltung `ssh-rsa` / SHA-1 nach BSI TR-02102-4) | ❌ | ✅ **Enthalten** |
| **6** | `configs/openssl_3_5_pqc_hybrid.cnf` | **OpenSSL 3.5+** | Drop-in Hybrid-KEM Config (`X25519MLKEM768` / `SecP256r1MLKEM768` + TLS 1.3 Cipher-Policy) | ❌ | ✅ **Enthalten** |
| **7** | `configs/nginx_tls13_bsi_tr02102_2.conf` | **Nginx Ingress** | Produktionsfertige TLS 1.3 Reverse-Proxy-Härtung nach **BSI TR-02102-2** | ❌ | ✅ **Enthalten** |
| **8** | `ci-cd/github-action-cbom-audit.yml` | **GitHub Action** | Automatisiertes CI/CD-Audit-Gate mit JSON/CSV CBOM-Artefakt-Archivierung | ❌ | ✅ **Enthalten** |
| **9** | `ci-cd/gitlab-ci-cbom-audit.yml` | **GitLab CI** | Schlüsselfertige GitLab-Pipeline für kontinuierliche Krypto-Compliance-Prüfungen | ❌ | ✅ **Enthalten** |

---

### 🛡️ Paket B: `BSI TR-03185, CRA-SBOM & DiGA (TR-03161) Audit-Readiness-Pack` — **39,20 € statt 49 €**
[![1-Click Checkout TR-03185 Suite](https://img.shields.io/badge/%F0%9F%9B%A1%EF%B8%8F_Jetzt_5--Dateien_TR--03185_%26_SBOM_.xlsx_Toolkit_freischalten_%28%E2%82%AC39%2C20%29-Direkt--Checkout-0f172a?style=for-the-badge)](https://kenanghalioun.gumroad.com/l/juznqz/BSI2026PRO?wanted=true)

| # | Datei im Enterprise-ZIP | Typ | Prüfzweck & enthaltener Inhalt | Enterprise (`€39,20`) |
| :-: | :--- | :--- | :--- | :-: |
| **1** | `BSI-TR-03185-und-DiGA-TR03161-Audit-Workbook.xlsx` | **Excel Workbook (3 Tabs)** | Executive Readiness-Score + **3-Klassen-Patch-Matrix (Klasse A/B/C)** für 24h/72h-Sicherheitsupdates ohne Rezertifizierung + BfArM DiGA TR-03161 Mapping | ✅ **Vollständig** |
| **2** | `TR-03185-Prozess-Audit-Matrix.csv` | **CSV Import** | Kompletter Prüfkatalog für Jira / GitLab / Azure DevOps Compliance-Tracking | ✅ **Vollständig** |
| **3** | `SOP-Sicherer-Release-Prozess-TR03185.md` | **Release SOP** | Auditfeste Verfahrensanweisung für CRA-Durchführungsgesetz, NIS-2 Lieferkette (§ 30 BSIG) & GoBD-Updates | ✅ **Enthalten** |
| **4** | `Checkliste-Update-Ohne-Rezertifizierung.html` | **A4 Protokoll** | Druckbares Patch-Klassifizierungs- und Freigabeformular für Prüfer & Benannte Stellen | ✅ **Enthalten** |
| **5** | `ci-cd/tr03185-release-gate.yml` | **SBOM CI/CD Gate** | Automatisierte **CycloneDX SBOM-Generierung nach BSI TR-03183-2**, SAST/CVE-Check & Release-Signierung | ✅ **Enthalten** |

> 🏢 **B2B-Rechnungskauf (EU-USt.-Beleg & SEPA-Firmenrechnung):** Über Gumroad (Merchant of Record) erhalten Sie sofort eine **EU-USt.-konforme Rechnung (inkl. USt-IdNr.-Eintrag)**. Alternativ können deutsche Unternehmen und Behörden direkt auf dem **[Live-Portal](https://kenanerorr404.github.io/de-compliance-kompass/)** per **„🏢 B2B-Bestellung auf Rechnung (SEPA, 14 Tage Zahlungsziel)"** bestellen.

---

## 📚 3. Alle 10 deutschen B2B-Compliance-Leitfäden & Interaktives Portal

| # | Fachleitfaden / Online-Tool | Schwerpunkt & Regulatorik | Live-Link (GitHub Pages) |
| :-: | :--- | :--- | :--- |
| **⚡** | **Interaktiver PQC- & NIS-2-Risiko-Rechner** | 60-Sekunden Gap-Score, HNDL-Analyse & § 60 / § 38 BSIG Bußgeld-Kalkulator | **[Rechner starten &rarr;](https://kenanerorr404.github.io/de-compliance-kompass/pqc-nis2-rechner.html)** |
| **10** | **E-Rechnungspflicht 2027 (EN 16931, XRechnung & ZUGFeRD)** | § 14 UStG (800k-Grenze), 10-Jahres-GoBD-Archivierung vs. PQC 2031, XXE-Schutz & AS4/SFTP-Härtung | **[Leitfaden lesen &rarr;](https://kenanerorr404.github.io/de-compliance-kompass/e-rechnungspflicht-2027-en16931-xrechnung-zugferd-gobd-bsi-sicherheit.html)** |
| **9** | **CRA-Durchführungsgesetz & NIS-2 Lieferkette (§ 30 BSIG)** | BSI-Marktüberwachung, 24h/72h ENISA-Meldung, CycloneDX SBOM (`TR-03183-2`) & 5-Jahres-Supportfrist | **[Leitfaden lesen &rarr;](https://kenanerorr404.github.io/de-compliance-kompass/cra-durchfuehrungsgesetz-nis2-lieferkette-sbom-kryptographie-2026.html)** |
| **8** | **BSI C5:2026 Cloud-Compliance & Nationale PQC-Leitlinie** | Cloud-Testat (`CRY`), CBOM-Pflicht, IT-Grundschutz & DevSecOps-Audit 2026 | **[Leitfaden lesen &rarr;](https://kenanerorr404.github.io/de-compliance-kompass/bsi-c5-2026-cloud-testat-pqc-leitlinie-kritis-nis2.html)** |
| **7** | **BSI Smart Meter Gateway (TR-03109), KRITIS-OT & IoT** | Vernetzte Steuerungsanlagen, PQC-Migration (`TR-02102`) & sichere Firmware-Updates (`TR-03185`) | **[Leitfaden lesen &rarr;](https://kenanerorr404.github.io/de-compliance-kompass/bsi-smart-meter-gateway-kritis-iot-kryptographie-2026.html)** |
| **6** | **NIS-2 Meldepflicht (§ 32 BSIG) & BSI-Sensorik 2026** | 24h/72h Incident-Response-Ablaufplan & Krypto-Vorfalls-Management | **[Leitfaden lesen &rarr;](https://kenanerorr404.github.io/de-compliance-kompass/nis2-bsig-32-meldepflicht-sensorik-incident-response-2026.html)** |
| **5** | **Digitale Souveränität & Cloud-Compliance 2026** | BSI-Vorgaben für Bundes-, Landes- und KRITIS-Zulieferer in der Lieferkette | **[Leitfaden lesen &rarr;](https://kenanerorr404.github.io/de-compliance-kompass/digitale-souveraenitaet-cloud-bsi-nis2-lieferkette-2026.html)** |
| **4** | **NIS-2 & Cyber Resilience Act (CRA) in CI/CD-Pipelines** | Automatisierte Compliance-Gates & kontinuierliche Krypto-Inventarisierung | **[Leitfaden lesen &rarr;](https://kenanerorr404.github.io/de-compliance-kompass/nis2-cra-automatisierte-cyber-abwehr-bsi-2026.html)** |
| **3** | **BSI-Prüfbericht Gesundheitswesen & DiGA (TR-03161)** | Sichere Standardkonfigurationen & BfArM-konforme Patch-Prozesse (`TR-03185`) | **[Leitfaden lesen &rarr;](https://kenanerorr404.github.io/de-compliance-kompass/bsi-it-sicherheit-gesundheitswesen-diga-tr03161-tr03185.html)** |
| **2** | **BSI TR-03185: Software-Updates ohne Rezertifizierung** | Klasse-A/B/C-Änderungsbewertung für schnelle CVE-Patches ohne Zertifikatsverlust | **[Leitfaden lesen &rarr;](https://kenanerorr404.github.io/de-compliance-kompass/bsi-tr-03185-software-updates-ohne-rezertifizierung.html)** |
| **1** | **BSI TR-02102-1: Ablaufdatum 2031 für RSA & ECDSA** | Post-Quanten-Migrationsleitfaden (`ML-KEM-768`, `ML-DSA`, OpenSSH 9.9+, OpenSSL 3.5+) | **[Leitfaden lesen &rarr;](https://kenanerorr404.github.io/de-compliance-kompass/bsi-tr-02102-ende-klassische-verschluesselung-pqc-2031.html)** |

---

## 📄 Lizenz & Hinweis
Der CLI-Scanner (`bsi_pqc_check.py`) und der Online-Risikorechner stehen unter der **MIT-Lizenz** frei zur Verfügung. Alle Fachinhalte dienen der technischen Information und stellen keine Rechts- oder Steuerberatung dar.
