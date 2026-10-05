<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0070F2,50:1B2A4A,100:714B67&height=260&section=header&text=Yassine%20Zouguari&fontSize=68&fontColor=ffffff&fontAlignY=40&desc=Technical%20ERP%20Engineer%20%E2%80%A2%20SAP%20%C2%B7%20Odoo%20%C2%B7%20AI%20%C2%B7%20Full-Stack&descAlignY=62&descSize=22" width="100%"/>

<a href="https://github.com/Zouguari">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1200&color=0070F2&center=true&vCenter=true&width=720&lines=Building+SAP+BTP+%2F+CAP+extensions+on+S%2F4HANA+Cloud;Writing+ABAP+Cloud+%26+Classic+ABAP+interfaces+(IDoc+%C2%B7+BAPI);Customizing+and+automating+Odoo+17+modules;Plugging+AI+into+ERP+data+%E2%80%94+safely;Full-stack+Python+%26+Java+%C2%B7+DevOps+%C2%B7+Cloud" alt="Typing SVG"/>
</a>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-yassine--zouguari-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/yassine-zouguari)
[![Email](https://img.shields.io/badge/Email-Contact_me-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:Yassine.zouguari.123@gmail.com)
[![Credly](https://img.shields.io/badge/Credly-Verified_badges-FF6B00?style=for-the-badge&logo=credly&logoColor=white)](https://www.credly.com/earner/earned/badge/31cdc2c5-0920-401b-b627-504b15beedc8)

</div>

```text
┃ SAP Easy Access ─ User: ZOUGUARI_Y ─ Client: 400
┃
┃ ▶ Command field : /nZYASSINE
┃ ✔ Transaction ZYASSINE started — navigate below, the SAP way.
```

> 🧭 **Navigation tip:** every section of this profile is a real SAP transaction code. If you know them, you already know where to look.

<br/>

## 👤 `/nSU01` — User Profile

```abap
CLASS zcl_yassine_zouguari DEFINITION PUBLIC FINAL CREATE PUBLIC.
  PUBLIC SECTION.
    INTERFACES if_oo_adt_classrun.
ENDCLASS.

CLASS zcl_yassine_zouguari IMPLEMENTATION.
  METHOD if_oo_adt_classrun~main.
    out->write( |Role    : Engineering student — IS Management & Governance (5th year)| ).
    out->write( |School  : ENSIASD Taroudant · Ibn Zohr University| ).
    out->write( |Mission : Technical ERP consultant — SAP & Odoo, powered by AI| ).
    out->write( |Builds  : BTP/CAP extensions · ABAP interfaces · Odoo modules| ).
    out->write( |Also    : Full-stack Python & Java · DevOps · Cloud| ).
    out->write( |Speaks  : Arabic (native) · French (B2) · English (B2)| ).
    out->write( |Looking : End-of-studies internship (PFE) — 2027| ).
  ENDMETHOD.
ENDCLASS.
```

<br/>

## 🗺️ The Bridge — where ERP meets AI

I don't treat SAP, Odoo, AI and web development as separate worlds. My work sits **in between** them:

```mermaid
flowchart LR
    subgraph SAP["🔷 SAP"]
        S4["S/4HANA Cloud"]
        ABAP["ABAP Cloud · Classic ABAP"]
        CAP["SAP BTP · CAP Node.js"]
        ABAP -->|"IDoc · BAPI"| S4
        S4 <-->|"OData"| CAP
    end

    subgraph AI["🧠 AI Layer"]
        LLM["LLM agents · Anomaly detection · KPI insights"]
    end

    subgraph ODOO["🟣 Odoo 17"]
        O["Custom modules · HR automation · ORM"]
    end

    subgraph APPS["⚡ Full-Stack"]
        WEB["Next.js · FastAPI · Django"]
        MOB["React Native · Expo"]
    end

    CAP --> LLM
    O -->|"XML-RPC"| LLM
    LLM --> WEB
    O --> MOB

    classDef sap fill:#0070F2,stroke:#0050B0,color:#fff
    classDef ai fill:#1B2A4A,stroke:#48C9B0,color:#fff
    classDef odoo fill:#714B67,stroke:#5A3A52,color:#fff
    classDef app fill:#48C9B0,stroke:#2E9C86,color:#0B1B2B
    class S4,ABAP,CAP sap
    class LLM ai
    class O odoo
    class WEB,MOB app
```

**Principle I build by:** AI suggests, the ERP decides. Real business data is never altered cosmetically, and every AI-recommended action stays pending until a human confirms it in the ERP.

<br/>

## 🔐 `/nPFCG` — Roles & Authorizations *(Certifications)*

<div align="center">

| | Certification | Code | Verify |
|:-:|:--|:-:|:-:|
| <img src="https://img.shields.io/badge/-SAP-0FAAFF?style=flat-square&logo=sap&logoColor=white"/> | **SAP Certified — Back-End Developer — ABAP Cloud** | `C_ABAPD_2601` | [![Credly](https://img.shields.io/badge/Credly-View-FF6B00?style=flat-square&logo=credly&logoColor=white)](https://www.credly.com/earner/earned/badge/31cdc2c5-0920-401b-b627-504b15beedc8) |
| <img src="https://img.shields.io/badge/-SAP-0FAAFF?style=flat-square&logo=sap&logoColor=white"/> | **SAP Certified — Backend Developer — SAP Cloud Application Programming Model** | `C_CPE` | [![Credly](https://img.shields.io/badge/Credly-View-FF6B00?style=flat-square&logo=credly&logoColor=white)](https://www.credly.com/earner/earned/badge/4bab003b-e9b4-4c64-8c0c-d9b78fbc531c) |
| <img src="https://img.shields.io/badge/-Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white"/> | **Oracle Certified Professional: Java SE 17 Developer** | `1Z0-829` | [![Oracle](https://img.shields.io/badge/Oracle-View-F80000?style=flat-square&logo=oracle&logoColor=white)](https://catalog-education.oracle.com/ords/certview/sharebadge?id=B83791B2AC31E947924EA51F0BB8AF1C8385662DD7CC0E2768E5AE9ABD579BE9) |
| <img src="https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white"/> | **Programming with Python 3.X** — Simplilearn | `2026` | — |

</div>

<!-- TODO: add the 2 other Java certifications here (same row format) -->

<br/>

## 📦 `/nSE80` — Object Navigator *(Featured Projects)*

### 🔷 SAP Track

| Project | What it does | Stack |
|:--|:--|:--|
| **[Vendor Spend Intelligence](https://github.com/Zouguari/vendor-spend-intelligence)** | Side-by-side SAP BTP extension connected to **S/4HANA Cloud** that uses AI to detect blocked and duplicate vendors. | `SAP BTP` `CAP Node.js` `CDS` `OData` `AI` |
| **[SAP ABAP IDoc — Sales Orders](https://github.com/Zouguari/sap-abap-idoc-sales-orders)** | End-to-end inbound interface in **Classic ABAP**: custom IDoc type & segments, inbound function module, BAPI order creation, log table, and an ALV monitor with one-click reprocessing of failed IDocs. Exported with abapGit. | `ABAP` `IDoc / ALE` `BAPI` `ALV` `abapGit` |
| **[CAP Purchase Request](https://github.com/Zouguari/cap-purchase-request)** | Purchase request application built with the SAP Cloud Application Programming Model, with an AI analysis layer. | `CAP Node.js` `CDS` `AI` |
| **[SAP Purchase Request](https://github.com/Zouguari/Sap_purchase_request)** | Purchase request scenario on SAP. | `SAP` |

### 🟣 Odoo Track

| Project | What it does | Stack |
|:--|:--|:--|
| **[SmartERP AI](https://github.com/Zouguari/smarterp-ai)** | SaaS decision-analytics platform and AI agent for **Odoo 17**: KPI analysis, anomaly detection and recommendations for SME managers, with audit trails and human-confirmed ERP actions. | `Odoo 17` `XML-RPC` `FastAPI` `Next.js` `LLM` |
| **[Smart HR Mobile](https://github.com/Zouguari/smart-hr-mobile)** | Mobile HR app connected to an Odoo backend. | `React Native` `Expo` `TypeScript` `Odoo` |
| **[HR Automation — Odoo](https://github.com/Zouguari/Rh_automatise-odoo)** | Automated HR modules in Odoo, configured to user needs. | `Odoo` `Python` |
| **[ENSIASD ERP](https://github.com/Zouguari/ENSIASD-ERP---Syst-me-de-Gestion-Int-gr-)** | Full academic ERP for ENSIASD: students, grades, attendance, internships and dashboards. | `Odoo 17` `Python` `PostgreSQL` `Docker` |
| **[WEBEDU — Student Portal](https://github.com/Zouguari/WEBEDUapplicationERP)** | Web application exposing student grades and information through the Odoo ERP API. | `Django` `REST API` `Odoo` |

<br/>

## 📋 `/nSM37` — Job Overview *(Experience)*

| Job name | Status | Highlights |
|:--|:-:|:--|
| `Z_URIKACLOUD_AI_ERP` · **AI & ERP Intern**, UrikaCloud · May–Aug 2026 | ✅ Finished | Built SmartERP AI, Smart HR Mobile and an AI recruitment module on top of Odoo 17. |
| `Z_LAFARGEHOLCIM_CV` · **AI Engineer Intern**, LafargeHolcim | ✅ Finished | Real-time face-recognition attendance system with a web dashboard. |
| `Z_CAR_RENTAL_WEB` · **Full-Stack Intern** | ✅ Finished | Car rental platform: reservations, vehicle catalogue, users and authentication. |
| `Z_MAROCARTISAN_LEAD` · **Global Project Lead** | ✅ Finished | Coordinated **10 teams (55 students)** on a Moroccan artisan marketplace; owned the Oracle DB architecture, code reviews and CI workflows. |

<br/>

## ⚙️ `/nSPRO` — Implementation Guide *(Tech Stack)*

**🔷 SAP**

![ABAP Cloud](https://img.shields.io/badge/ABAP_Cloud-0FAAFF?style=for-the-badge&logo=sap&logoColor=white)
![Classic ABAP](https://img.shields.io/badge/Classic_ABAP-0070F2?style=for-the-badge&logo=sap&logoColor=white)
![RAP](https://img.shields.io/badge/RAP-0070F2?style=for-the-badge&logo=sap&logoColor=white)
![CDS](https://img.shields.io/badge/CDS-0070F2?style=for-the-badge&logo=sap&logoColor=white)
![SAP CAP](https://img.shields.io/badge/SAP_CAP-0FAAFF?style=for-the-badge&logo=sap&logoColor=white)
![SAP BTP](https://img.shields.io/badge/SAP_BTP-0070F2?style=for-the-badge&logo=sap&logoColor=white)
![S/4HANA](https://img.shields.io/badge/S%2F4HANA_Cloud-1B2A4A?style=for-the-badge&logo=sap&logoColor=white)
![IDoc](https://img.shields.io/badge/IDoc_%C2%B7_BAPI_%C2%B7_ALV-1B2A4A?style=for-the-badge&logo=sap&logoColor=white)
![OData](https://img.shields.io/badge/OData-0FAAFF?style=for-the-badge&logo=odata&logoColor=white)

**🟣 Odoo**

![Odoo 17](https://img.shields.io/badge/Odoo_17-714B67?style=for-the-badge&logo=odoo&logoColor=white)
![Odoo ORM](https://img.shields.io/badge/ORM_%C2%B7_Custom_Modules-714B67?style=for-the-badge&logo=odoo&logoColor=white)
![XML-RPC](https://img.shields.io/badge/XML--RPC_API-5A3A52?style=for-the-badge&logo=odoo&logoColor=white)
![HR](https://img.shields.io/badge/HR_Automation-5A3A52?style=for-the-badge&logo=odoo&logoColor=white)

**🧠 AI & Data**

<a href="#"><img src="https://skillicons.dev/icons?i=tensorflow,sklearn,opencv&theme=dark" /></a>
![LLM](https://img.shields.io/badge/LLM_Agents-1B2A4A?style=for-the-badge&logo=openai&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)

**⚡ Full-Stack — Languages & Frameworks**

<a href="#"><img src="https://skillicons.dev/icons?i=python,java,js,ts,php,bash&theme=dark" /></a>
<br/>
<a href="#"><img src="https://skillicons.dev/icons?i=django,fastapi,flask,nodejs,nextjs,react,laravel,html,css&theme=dark" /></a>
<br/>
![React Native](https://img.shields.io/badge/React_Native_%C2%B7_Expo-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![PL/SQL](https://img.shields.io/badge/PL%2FSQL-F80000?style=for-the-badge&logo=oracle&logoColor=white)

**🗄️ Databases**

<a href="#"><img src="https://skillicons.dev/icons?i=postgres,mysql&theme=dark" /></a>
![Oracle](https://img.shields.io/badge/Oracle_DB-F80000?style=for-the-badge&logo=oracle&logoColor=white)

<br/>

## 🚚 `/nSTMS` — Transport Management *(DevOps & Cloud)*

```text
 DEV ──▶ Git / abapGit ──▶ GitHub Actions ──▶ Docker / Compose ──▶ AWS · SAP BTP
```

<a href="#"><img src="https://skillicons.dev/icons?i=git,github,githubactions,docker,linux,aws&theme=dark" /></a>
![SAP BTP](https://img.shields.io/badge/SAP_BTP-0070F2?style=for-the-badge&logo=sap&logoColor=white)
![abapGit](https://img.shields.io/badge/abapGit-1B2A4A?style=for-the-badge&logo=git&logoColor=white)

**Methods & governance:** Agile Scrum · Kanban · CI/CD · ITIL v4 · COBIT · CMMI · Microservices · REST APIs · Modular ERP design

<br/>

## 🟢 `/nSM50` — Work Processes *(Currently running)*

| WP | Status | Task |
|:-:|:-:|:--|
| `DIA 0` | 🟢 Running | Sharpening **Classic ABAP** on S/4HANA (interfaces, ALV, IDoc monitoring) |
| `DIA 1` | 🟢 Running | Evolving **Vendor Spend Intelligence** on SAP BTP |
| `BGD 0` | 🟡 Waiting | Looking for an **end-of-studies internship (PFE) 2027** — SAP · Odoo · AI |

<br/>

## 📈 `/nST03N` — Workload Analysis

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=Zouguari&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" />
&nbsp;
<img height="170" src="https://streak-stats.demolab.com?user=Zouguari&theme=tokyonight&hide_border=true" />

</div>

<br/>

## 📬 `/nSBWP` — Business Workplace *(Contact)*

<div align="center">

**Working on SAP, Odoo or AI-for-ERP? Let's talk.**

[![Email](https://img.shields.io/badge/Yassine.zouguari.123%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:Yassine.zouguari.123@gmail.com)
[![LinkedIn](https://img.shields.io/badge/yassine--zouguari-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/yassine-zouguari)

</div>

```text
✔ Profile ZYASSINE saved successfully   │   Status: Open to PFE 2027   │   SAP · Odoo · AI · Full-Stack
```

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:714B67,50:1B2A4A,100:0070F2&height=130&section=footer" width="100%"/>
</div>
