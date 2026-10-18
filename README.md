# OSINT-Tools-Slovakia
<img src="https://flagcdn.com/w320/sk.png" alt="Slovakia_FLAG"/>
A list of OSINT resources and tools that may be useful to you when conducting investigations related to Slovakia. Most of the resources and tools has versions in Slovak, English. A new Commercial Register Act (No. 29/2026 Z. z.) has applied since 17 August 2026. Under it, stored company documents (zbierka dokumentov) are open to anyone free of charge, while beneficial-owner data is not published in the Commercial Register itself (§ 100(2)). The Office for Personal Data Protection opened proceedings against the Ministry of Justice on 19 August 2026 over birth numbers and signatures visible in those documents, so access rules may change. Beneficial owners of entities receiving public money are still published in the Register of Public Sector Partners (RPVS): as of 2026-10-12, UBO verification documents open without login. Many official Slovak portals (ORSR, ŽRSR, ÚGKK cadastre apps, ÚVO, courts) block automated access, so the links were validated through independent sources and should be checked by hand.

![Last updated](https://img.shields.io/github/last-commit/Provereno-Media/OSINT-Tools-Slovakia?label=Last%20updated)

## Contributions
Feel free to join this project — [OSINT For Countries V2.0](https://github.com/Provereno-Media/OSINT-for-countries-V2.0)

## Table of contents:
 - [Open Data portals](#open-data-portals)
 - [Legal Entities](#legal-entities)
 - [Cadastral and other Maps](#maps)
 - [Vehicles](#vehicles)
 - [People, phones, social etc.](#people)
 - [Public procurements](#public-procurement)
 - [WHOIS](#whois)

## Open Data portals
(Country Open Data, Stock Exchange, Courts)
- [Národný katalóg otvorených dát (National Open Data Catalogue)](https://data.slovensko.sk/) — national catalogue of open datasets published by Slovak public administration bodies (JavaScript web app). *Lang: SK.* 🏛️
- [Štatistický úrad SR – Databázy (Statistical Office – Databases)](https://slovak.statistics.sk/wps/portal/ext/Databases/!ut/p/z0/04_Sj9CPykssy0xPLMnMz0vMAfIjo8ziHQMDA4N9wsIM3MOM3Aw8jQ3dDfxCQw0M3Mz1g1Pz9AuyHRUBxP-3Qg!!) — entry point to DATAcube and its successor STATdata (economic and socio-economic time series), an open-data API (JSON-stat, CSV, XML, XLSX) and the register of territorial units. *Lang: SK, EN.* 🏛️
- [Slov-Lex (Legislative and Information Portal)](https://www.slov-lex.sk/) — Ministry of Justice legal information system: Collection of Laws (Zbierka zákonov), Register of measures and court decisions of general courts (judikáty section); a static version is at static.slov-lex.sk. *Lang: SK.* 🏛️
- [Obchodný vestník (Commercial Bulletin)](https://obchodnyvestnik.justice.gov.sk/ObchodnyVestnik/Formular/FormulareZverejnene.aspx) — Ministry of Justice official gazette for legally required company and insolvency notices; search by IČO, business name, seat, issue number or publication date. *Lang: SK.* 🏛️
- [Najvyšší súd SR – Rozhodnutia (Supreme Court – Decisions)](https://www.nsud.sk/rozhodnutia/) — database of over 100,000 Supreme Court decisions; filter by keyword, ECLI, case number, decision date and college (civil, commercial, criminal, administrative). *Lang: SK.* 🏛️
- [Infosúd – Súdne rozhodnutia (Infosúd – Court Decisions)](https://obcan.justice.sk/infosud/-/infosud/zoznam/rozhodnutie) — Ministry of Justice list of published decisions of Slovak general courts. *Lang: SK.* 🏛️
- [Otvorené súdy (Open Courts)](https://www.otvorenesudy.sk/) — Transparency International Slovensko project that restructures court data: about 4.7 million decisions, 3.6 million hearings and 3,700 judges, with analyses based on judges' asset declarations and statistics; open API. *Lang: SK.*
- [Burza cenných papierov v Bratislave (Bratislava Stock Exchange)](https://www.bsse.sk/) — list of listed securities, exchange announcements, price lists, trade data (15-minute delay), SAX index and statistics. *Lang: SK, EN.*

## Legal Entities
- [Obchodný register SR (Commercial Register)](https://www.orsr.sk/) — Ministry of Justice register of companies: name, IČO, seat, legal form, statutory bodies, shareholders and history; search by name, IČO, seat, file number or person's name. Under the new law in force since 17 Aug 2026, stored documents are public, but beneficial-owner data is not published here. *Lang: SK, EN.* 🏛️
- [Register právnických osôb (Register of Legal Entities, Entrepreneurs and Public Authorities – RPO)](https://rpo.statistics.sk/rpo) — Statistical Office reference register combining data from the source registers (commercial, trade and others); search without login by IČO, name or legal form, including historical and dissolved entities. Extended criteria and official extracts require login. *Lang: SK.* 🏛️
- [Živnostenský register SR (Trade Licence Register)](https://www.zrsr.sk/index) — register of trade licences of sole proprietors and companies, including regulated activities; beware of the look-alike private site rzsr.sk. *Lang: SK.* 🏛️
- [Register účtovných závierok (Register of Financial Statements)](https://www.registeruz.sk/cruz-public/domain/accountingentity/simplesearch) — Ministry of Finance register of annual financial statements and reports; search by entity name, IČO or tax ID (DIČ); public API available. *Lang: SK, EN.* 🏛️
- [Register partnerov verejného sektora (Register of Public Sector Partners – RPVS)](https://rpvs.gov.sk/rpvs/) — register of entities receiving public money or property above the legal thresholds, with their beneficial owners and verification documents filed by the authorised person (lawyer, notary, bank, auditor, tax adviser). As of 2026-10-12, documents naming beneficial owners open without login. *Lang: SK.* 🏛️
- [REPLIK – Register úpadcov (Insolvency Register)](https://replik.justice.sk/ru-verejnost-web/pages/home.xhtml) — Ministry of Justice register of pre-insolvency, bankruptcy, restructuring and liquidation proceedings, which replaced the earlier Register úpadcov on 1 Oct 2025; search by person or company name, IČO or case number. Also covers public notices, estate assets for sale and trustees. *Lang: SK, EN.* 🏛️
- [Finančná správa – Informačné zoznamy (Financial Administration – Public Lists)](https://www.financnasprava.sk/sk/elektronicke-sluzby/verejne-sluzby/zoznamy) — tax debtors (arrears above €170, updated monthly), VAT register, VAT payers with grounds for deregistration, corporate income tax paid, tax reliability index, excise and fuel registers; CSV/XML exports. *Lang: SK.* 🏛️
- [Register mimovládnych neziskových organizácií (Register of Non-Governmental Non-Profit Organisations – RMNO)](https://ives.minv.sk/rmno/) — Ministry of Interior register of civic associations, foundations, non-profit organisations and non-investment funds; search by name, IČO, registration number, region, municipality or person (statutory). *Lang: SK, EN.* 🏛️
- [foaf.sk](https://www.foaf.sk/) — company and person search built on ORSR and other public data, with ownership and business-link mapping, financials, Obchodný vestník and procurement records. *Lang: SK.* 💲 Freemium: free plan covers company/person search, basic company info and basic financial indicators; connection graphs, full financial statements, debts and courts are paid (from €35/month).

## Maps
(Cadastral Maps if available, GIS etc.)
- [ZBGIS – Mapový klient (ZBGIS Map Client)](https://zbgis.skgeodesy.sk/) — official map client of the Geodesy, Cartography and Cadastre Authority (ÚGKK SR) for the ZBGIS base geographic database, including cadastral map data. *Lang: SK.* 🏛️
- [Portál ESKN (Electronic Cadastre Services)](https://kataster.skgeodesy.sk/eskn-portal/) — ÚGKK portal for electronic services and data of the real-estate cadastre; ÚGKK warns that only ESKN, CICA and ZBGIS are its official cadastre portals. *Lang: SK.* 🏛️
- [Portál CICA (Cadastre Descriptive Data Search)](https://kataster.vugk.sk/) — ÚGKK application for simple searches of descriptive cadastre data and ownership-sheet (list vlastníctva) information. *Lang: SK.* 🏛️
- [Môj kataster (My Cadastre)](https://katasterportal.skgeodesy.sk) — ÚGKK property cadastre portal for property and ownership information. *Lang: SK.* 🏛️
- [Kto vlastní Slovensko? (Who Owns Slovakia?)](https://ktovlastni.transparency.sk/) — Transparency International Slovensko map of hotels, spas, ski and golf resorts, aquaparks and attractions, with operator, final owner, financial statements, debts and a transparency score; data updated 15 May 2024. *Lang: SK.*
- [Mapy.com](https://mapy.com/) — map portal with base, tourist (hiking/cycling), transport and winter maps, plus aerial and 3D views. *Lang: SK, EN.*

## Vehicles
### Land
- [Kontrola platnosti diaľničnej známky (e-Vignette Validity Check)](https://eznamka.sk/selfcare/modification/select/select-vignettes/?operation=Check) — official check of whether a vehicle has a valid Slovak motorway e-vignette; input is the registration plate (EČV) and country of registration. *Lang: SK, EN, DE, RU, PL, HU.* 🏛️
- [Notársky centrálny register záložných práv (Notarial Central Register of Pledges)](https://www.notar.sk/zalozne-prava) — Notarial Chamber register of pledges over movable assets and receivables; search by pledgor, debtor or creditor name, IČO or date of birth, pledge description or **vehicle VIN**. Results are informative only. *Lang: SK.*
- [SKP – Overenie platnosti PZP (Slovak Insurers' Bureau – MTPL Check)](https://www.skp.sk/vyhladat-poistovatela-vozidla-a-overit-platnost-pzp/) — check compulsory motor third-party liability insurance by registration plate (EČV) or VIN for a chosen date; returns vehicle type, make, model, colour, insurer, policy number and coverage period. *Lang: SK.*

### Maritime
- [Equasis](https://www.equasis.org/) — free international database of ship and shipping-company safety information, run by France with EMSA and other maritime administrations; ship and company search for registered users. *Lang: EN.* ⚠️

### Aviation
- [ADS-B Exchange](https://globe.adsbexchange.com/) — live and historical aircraft tracking: registration, type, altitude, speed, signal source, day-by-day trace playback; filters and jump to airport or coordinates to monitor Slovak airspace. *Lang: EN.*

## People
(Names, Addresses, Yellow Pages, White Pages etc.)
- [Voľby a referendá – Štatistický úrad SR (Elections and Referendums – Statistical Office)](https://volby.statistics.sk/) — official archives of national (1990–2023), presidential, European Parliament, regional and municipal elections and referendums (to 2026), with data downloads. *Lang: SK, EN.* 🏛️
- [Sociálna poisťovňa – Zoznam dlžníkov (Social Insurance Agency – Debtors List)](https://www.socpoist.sk/nastroje-sluzby/zoznam-dlznikov) — natural and legal persons with social insurance debts of €5 or more, employers that have not filed contribution statements, and foreign self-employed persons with missing filings; search by name or surname; updated several times a month; full download available. *Lang: SK.* 🏛️
- [Slovenská advokátska komora – Zoznam advokátov (Slovak Bar Association – Lawyers Directory)](https://www.sak.sk/zoznam-advokatov/) — official directory of lawyers, law firms and trainee lawyers; search by name, firm, employer, city, practice area and language. *Lang: SK.*
- [Otvorená prokuratúra (Open Prosecution)](https://prokuratura.otvorenesudy.sk/) — Transparency International Slovensko portal on prosecutors and their asset declarations, prosecutors' offices and their decisions, and crime statistics. *Lang: SK.*
- [Rodiny na súdoch (Families in the Courts)](http://sudy.transparency.sk/) — Transparency International Slovensko map of family ties between judges and court staff across Slovak courts (data years 2012–2019), built on Otvorené súdy data. *Lang: SK.*
- [Zlaté stránky (Golden Pages)](https://www.zlatestranky.sk/) — Slovak business directory (yellow pages); search by company name, category or location, with contacts and opening hours. *Lang: SK.*
- Try [OSINT Industries](https://app.osint.industries) and don't forget about the [Digital Profiler's Toolkit](https://github.com/paulpogoda/Digital-Profiler-s-Toolkit)

## Public procurement
- [Centrálny register zmlúv (Central Register of Contracts – CRZ)](https://www.crz.gov.sk/) — mandatory register of contracts concluded by public bodies; each record gives the contract title and number, price, supplier, contracting authority and publication date. *Lang: SK.* 🏛️
- [Úrad pre verejné obstarávanie (Public Procurement Office – ÚVO)](https://www.uvo.gov.sk/) — central procurement authority; keeps the register of economic operators that suppliers must join to trade on the state e-marketplace and in public contracts. *Lang: SK.* 🏛️
- [Elektronický kontraktačný systém (Electronic Contracting System – EKS)](https://www.eks.sk/) — state e-procurement platform and electronic marketplace: overview of orders, marketplace contract register, buyer and supplier registers, offer catalogue and historical open data (CSV). *Lang: SK.* 🏛️
- [Otvorené zmluvy (Open Contracts)](https://otvorenezmluvy.sk/) — crowdsourced layer over published public contracts (title, authority, supplier, price), with user comments and "controversial" flags; the entries visible on the site date from 2011–2016. *Lang: SK.*
- [Faktúra za eurofondy (Invoice for EU Funds)](http://eurofondy.transparency.sk/) — Transparency International Slovensko portal on EU funds spending in Slovakia, 2021–2027 programming period. *Lang: SK.*
- [Verejné firmy (Public Companies)](http://firmy.transparency.sk/) — Transparency International Slovensko rating of 100 state, municipal, regional and university companies (2024 edition): open tenders, disclosure of finances, executive pay, grants and sponsorship; company profiles by year. *Lang: SK, EN.*

## WHOIS
- [SK-NIC](https://www.sk-nic.sk/) — .sk ccTLD registry operator (also org.sk and the domain auction system): domain rules, lifecycle, registrar information. *Lang: SK.*
- [SK-NIC – domains.txt (List of Registered .sk Domains)](https://sk-nic.sk/subory/domains.txt) — daily file of all live .sk domains with registrar ID, holder ID, name servers and expiry date; useful for finding domains that share a holder ID or name servers. *Lang: SK, EN.*
- [SK-NIC – Zoznam všetkých registrátorov (List of All Registrars)](https://sk-nic.sk/zoznam-vsetkych-registratorov/) — registrar directory with contact details; use it to resolve registrar IDs from domains.txt or WHOIS. *Lang: SK.*
- [Virtualno.sk – Údaje o .sk doménach (.sk Domain Statistics)](https://virtualno.sk/statistiky/udaje-o-sk-domenach/) — SK-NIC statistics: number of .sk domains since 2008, new and deleted domains, DNSSEC adoption, registrars and holders (including foreign holders). *Lang: SK.*
- [IANA – .sk Delegation Record](https://www.iana.org/domains/root/db/sk.html) — official delegation data for .sk: registry operator, technical contacts and WHOIS server `whois.sk-nic.sk` (for command-line WHOIS queries). *Lang: EN.*

---

## Contributing

To contribute to this repository:
1. Verify all links are working and accessible
2. Provide accurate descriptions of database contents
3. Follow the 7-category structure
4. Include official government sources when available
5. Submit pull requests with detailed change descriptions

## Legal Disclaimer

This repository is for educational and legitimate investigative purposes only. Users are responsible for:
- Complying with all applicable laws and regulations
- Respecting terms of service for all databases and tools
- Using information ethically and responsibly
- Obtaining proper authorization when required

The information provided is for informational purposes only and should not be considered legal advice.

---

**Repository maintained by the [OSINT-for-Countries-V2.0 community](https://github.com/Provereno-Media/OSINT-for-countries-V2.0)**
