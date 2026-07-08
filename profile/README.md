<div align="center">

# Form Commons

### **Shared document infrastructure for public-interest services.**

[![Status: Early Development](https://img.shields.io/badge/status-early%20development-f59e0b)](#-project-status)
[![Accessibility Target: WCAG 2.2 AA](https://img.shields.io/badge/accessibility%20target-WCAG%202.2%20AA-22c55e)](#-our-principles)
[![Focus: Public Interest](https://img.shields.io/badge/focus-public%20interest-2563eb)](#-what-we-build)
[![Licensing: Open](https://img.shields.io/badge/licensing-open-7c3aed)](#-licensing)

</div>

---

Form Commons is an open-source initiative building **accessible, local-first document infrastructure** for regulated services, civic participation, community work, and other public-interest settings.

Many agencies, service providers, nonprofits, contractors, public programs, and community organizations depend on documents whose content is shaped by laws, regulations, funding rules, contracts, accessibility standards, professional guidance, or public decision-making processes. Too often, those documents are recreated independently, maintained inconsistently, and made difficult for the people using them to understand.

**Form Commons develops shared foundations for doing this work better.**

> 🏗️ We treat important public-interest documents as shared infrastructure—not isolated files.

Form Commons documents are designed as structured, self-contained `.fc.html` files that open in an ordinary browser, work offline, require no account, and remain under the user’s control. The same structured source can also produce accessible DOCX and PDF outputs.

## 🛠️ What we build

Form Commons develops:

- 📄 openly licensed document definitions and templates;
- 🌐 self-contained `.fc.html` documents that work offline in ordinary browsers;
- ⚙️ a local-first PWA for filling, reviewing, protecting, and exporting documents;
- 🧬 structured YAML and JSON schemas for regulated and public-interest content;
- 🧱 reusable accessible components and document fragments;
- 📑 accessible DOCX and tagged PDF export paths;
- 🔎 requirements crosswalks, source provenance, and review records;
- ✅ validation, migration, testing, and reproducible-release infrastructure;
- 📘 adoption and implementation guidance for public-interest organizations;
- 🗺️ future jurisdiction or organization modules where research shows they are appropriate.

The goal is not to replace legal, regulatory, clinical, professional, or community review. It is to turn public requirements and recurring workflows into **clearer, more usable, and more maintainable document infrastructure**.

## 🌱 Our principles

### 👤 Person-centered and usable

Documents should serve the people whose lives, rights, needs, or communities they describe—not only auditors, administrators, or software systems.

### ♿ Accessible by default

Form Commons targets **WCAG 2.2 AA**. Accessibility, plain language, cognitive usability, screen-reader compatibility, mobile use, and print quality are designed in from the beginning and tested through automated checks, manual review, assistive-technology testing, and user research.

### 💾 User-owned and offline

A completed document is a file the user controls—not a record trapped in an account or proprietary service. Official `.fc.html` documents work offline and make no network requests.

### 🔎 Requirements are traceable

Regulated or jurisdiction-specific content should be connected to current primary sources, with clear verification dates, implementation notes, review status, and confidence levels.

### 🔓 Open and adaptable

Organizations should be able to inspect, reuse, localize, and improve the work without being locked into a proprietary platform.

### 🧩 Structured, not duplicated

Shared components, declarative source files, reusable fragments, and carefully governed overlays should reduce copy-and-paste drift across document editions.

### 🔐 Local, private, and intentionally shared

Form Commons does not upload document contents, answers, filenames, analytics, telemetry, or usage events. Sensitive information should be minimized, protected when appropriate, and included in sharing or derived copies only through deliberate user action.

Form Commons does not claim to replace organizational access controls, audit systems, retention rules, or records-management policies.

### 🕰️ Built for long-term stewardship

Official documents should remain openable by future engines. Schema changes require migrations, releases should be reproducible, and the project is designed for durable institutional stewardship rather than dependence on a commercial platform.

### 🌍 Free without a commercial tier

Form Commons has no subscriptions, advertising, paid feature gates, license fees, or commercially privileged edition. Grants, donations, and institutional stewardship may fund the work, but all software capabilities and templates remain free and open.

### 🧭 Honest about scope

No single document can satisfy every jurisdiction or replace every mandatory government form, portal, or system of record. Each project should state where it can be used, where it serves as a companion, and where further review is required.

## 🚀 Initial focus

Our first document type is a universal **Individualized Support Plan (ISP)** for person-centered planning in intellectual and developmental disability services.

The first release is being designed around:

- a universal person-centered common core;
- applicable U.S. Medicaid HCBS content and process requirements;
- planning, provider-implementation, rights, risk, review, and lifecycle modules;
- plain-language, symbol-supported, and authored Easy Read content;
- accessible completion through self-contained `.fc.html`;
- accessible DOCX and tagged PDF exports;
- transparent source crosswalks and review history;
- local file ownership, optional password protection, and no document telemetry.

The first release does not claim to replace a jurisdiction’s mandatory form, portal, or electronic record system. Jurisdiction-specific overlays are deferred until the universal document and overlay model have been validated.

## 🧪 Project status

Form Commons is in early development.

Initial work is focused on:

1. establishing the document architecture and component contracts;
2. building the local-first engine, PWA, and reproducible release pipeline;
3. publishing the first Individualized Support Plan candidate;
4. validating accessibility and usability with real stakeholders;
5. documenting where future jurisdiction-specific or companion editions are appropriate.

Repositories and releases should clearly identify their status:

| Status | Meaning |
|---|---|
| ⚪ **Draft** | Under active development and not ready for operational reliance |
| 🟡 **Candidate** | Ready for focused review, testing, or a carefully governed pilot |
| 🟢 **Reviewed** | Reviewed by identified qualified contributors against stated sources through a published date |
| 🧷 **Companion** | Intended to supplement—not replace—a prescribed form, portal, or system |
| 🗄️ **Deprecated** | Superseded and no longer recommended for new use |

A **reviewed** label records the review performed. It is not legal advice, certification, or a guarantee of compliance.

## 🤝 Who this is for

Form Commons may be useful to:

- people receiving services, self-advocates, families, and supporters;
- public agencies and community organizations;
- nonprofit and human-services providers;
- support coordinators and case-management entities;
- accessibility, policy, legal, and compliance reviewers;
- researchers, document engineers, and open-source contributors.

## 💬 Contributing

We welcome contributions from people with lived experience, practitioners, designers, developers, policy specialists, accessibility reviewers, and legal or compliance professionals.

Contributions may include:

- identifying missing or outdated requirements;
- reviewing language for clarity, dignity, and accuracy;
- testing documents with assistive technology;
- improving templates, components, and fragments;
- validating source crosswalks;
- reporting compatibility or accessibility issues;
- contributing fictional examples and implementation guidance;
- improving generation, validation, migration, and release tooling.

Each repository provides its own contribution instructions, review standards, and licensing terms.

## 🏛️ Governance and review

Form Commons uses transparent, documented processes for:

- source verification;
- editorial and subject-matter review;
- accessibility review;
- release approval;
- migration and change tracking;
- deprecation;
- community feedback;
- conflict-of-interest disclosure.

Major document projects should seek review from affected communities and qualified subject-matter experts before being represented as stable or reviewed.

Official `.fc.html` files and data blobs are governed by a long-term compatibility covenant: documents created by an official release should continue to open in future engines.

## 📜 Licensing

Unless a repository states otherwise:

- original document templates and written guidance are licensed under **Creative Commons Attribution 4.0 International (CC BY 4.0)**;
- software, schemas, and developer tooling use the open-source license identified in that repository;
- third-party assets retain their own licenses and attribution requirements.

Always consult the license and attribution files included with the specific repository or release.

## 🔐 Privacy and trust

Published blank forms and saved `.fc.html` documents are self-contained and make no network requests.

The hosted Form Commons PWA may retrieve same-origin application updates, but it does not transmit document contents, answers, filenames, telemetry, analytics, or usage events.

Documents may support optional password protection. Form Commons cannot recover lost passwords and does not provide cloud backup or remote access to user files.

## ⚠️ Important notice

Form Commons provides open document infrastructure and research-informed implementation resources. It is **not** a government agency, law firm, certification body, healthcare provider, or substitute for legal, clinical, regulatory, or professional advice.

Organizations remain responsible for confirming that a document meets the current laws, regulations, contracts, payer requirements, agency policies, accessibility obligations, and recordkeeping rules that apply to their work.

## 📣 Get involved

Follow the organization, watch project repositories, open an issue, or join a discussion as projects become available.

---

<div align="center">

## Form Commons

**Shared document infrastructure for public-interest services.**

</div>
