# ⚖️ THEMIS — Legal AI Plugin for Claude Code

> **Having rights is good. Enforcing them is better.**

[![Claude Code Plugin](https://img.shields.io/badge/Claude%20Code-Plugin-blueviolet?style=for-the-badge&logo=anthropic)](https://claude.ai/code)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](LICENSE)
[![Jurisdictions](https://img.shields.io/badge/Jurisdictions-AT%20%7C%20DE%20%7C%20EU%20%7C%20US-orange?style=for-the-badge)](#coverage)
[![Skills](https://img.shields.io/badge/Skills-4-blue?style=for-the-badge)](#skills)

**THEMIS** is a full-stack legal AI assistant for Claude Code, covering Austrian, German, EU, and US law with exact statutes, landmark case references, ready-to-use legal templates, and enforcement strategies — across every major area of law.

No more "consult a lawyer for everything." Know your rights, enforce them, generate finished legal documents — all inside your AI assistant.

---

## Why THEMIS?

Most legal AI tools either:
- Cover only one country
- Give vague summaries without citing actual laws
- Can't generate usable documents
- Don't cover the areas that matter most (IP theft, influencer law, employment, criminal defense)

THEMIS covers **all of it** — with real paragraph numbers, real case law, and real output.

---

## Skills

### `/themis` — Full Legal Assistant
The complete legal knowledge base. Ask any legal question across AT/DE/EU/US law. Every answer includes:
- Exact statute (e.g. `§ 97 UrhG DE`, `17 U.S.C. § 512`, `Art. 17 DSGVO`)
- Landmark cases where relevant (BGH, OGH, SCOTUS, Circuit Courts)
- Practical implications
- Next steps and deadlines

### `/brief` — Legal Letter Generator
Describe your situation in plain language → get a finished, professionally formatted letter. No legal knowledge required.

Examples:
- "Someone stole my video on TikTok" → DMCA Takedown + Abmahnung
- "My employer fired me without reason" → Kündigungsschutzklage
- "My tenant won't pay rent" → Zahlungsaufforderung + Kündigung
- "I got an unjust cease & desist" → Professional pushback letter

### `/vertrag` — Contract Generator & Reviewer
Create or audit any contract:
- Influencer & brand collaboration agreements
- NDAs (one-way and mutual)
- Employment contracts (AT/DE compliant)
- Software license agreements
- Freelancer/work-for-hire contracts
- Rental agreements

Red flags highlighted. Missing clauses identified. Unfair terms flagged.

### `/strafanzeige` — Criminal Complaint Generator
Structured police reports and criminal complaints for AT/DE/US:
- Correct statutes for each crime
- Right authority (police, DA, FBI, FTC, IC3)
- Required evidence checklist
- Filing deadlines
- Finished complaint ready to submit

---

## Coverage

### 🇦🇹 Austria (ABGB, StGB, UrhG, MRG, EheG, IO...)
Criminal law · Civil/contract law · Family & divorce · Inheritance · Employment · Copyright · Trademark · Rental law · Data protection · Competition law · Administrative law · Insolvency

### 🇩🇪 Germany (BGB, StGB, UrhG, KSchG, MarkenG, InsO...)
Criminal law · Civil law · Family law (BGB + Düsseldorfer Tabelle) · Employment (KSchG, AGG, BetrVG) · Copyright · Trademark · Rental law · GDPR implementation · Competition law (UWG) · Insolvency

### 🇪🇺 EU
GDPR (all 99 articles) · DSA · EUTM trademark law · Consumer rights directives · E-Commerce law · Platform liability (Section 230 equivalent)

### 🇺🇸 United States (Federal + Key State Law)
Constitutional rights (1st, 4th, 5th, 6th Amendment) · Federal criminal law (18 U.S.C.) · Copyright Act + DMCA · Lanham Act (trademark) · Employment law (Title VII, FLSA, FMLA, ADA) · Privacy (CCPA, COPPA, HIPAA) · FTC influencer rules · Contract law (UCC) · Bankruptcy (Chapter 7/13) · Immigration basics · State-specific family law

---

## Installation

```bash
claude plugin install themis
```

Or install directly from this repo:

```bash
claude plugin install github:schenkei-code/themis
```

---

## Quick Start

```
/themis Someone is using my YouTube video in their TikTok without permission. What are my rights?
```

```
/brief My landlord hasn't fixed the heating for 3 weeks. Write a formal letter demanding repair and reducing rent.
```

```
/vertrag Create an influencer collaboration contract. I'm a creator with 80K followers, brand wants 3 Reels, paying €2,500, wants to use content in ads for 6 months.
```

```
/strafanzeige Someone hacked my Instagram account and is posting as me. I'm in Germany. How do I file a criminal complaint?
```

---

## Areas of Law

| Area | AT | DE | EU | US |
|---|:---:|:---:|:---:|:---:|
| Criminal Law | ✅ | ✅ | — | ✅ |
| Civil / Contract Law | ✅ | ✅ | ✅ | ✅ |
| Family Law | ✅ | ✅ | — | ✅ |
| Employment Law | ✅ | ✅ | ✅ | ✅ |
| Copyright / IP | ✅ | ✅ | ✅ | ✅ |
| Trademark | ✅ | ✅ | ✅ | ✅ |
| Data Protection / Privacy | ✅ | ✅ | ✅ | ✅ |
| Rental / Property | ✅ | ✅ | — | — |
| Traffic Law | ✅ | ✅ | — | ✅ |
| Corporate / Business | ✅ | ✅ | ✅ | ✅ |
| Insolvency / Bankruptcy | ✅ | ✅ | — | ✅ |
| Competition Law | ✅ | ✅ | ✅ | ✅ |
| Influencer / FTC Rules | ✅ | ✅ | ✅ | ✅ |
| Immigration | — | — | — | ✅ |
| Administrative Law | ✅ | — | — | — |

---

## Who This Is For

- **Content Creators & Influencers** — DMCA takedowns, brand deal contracts, FTC compliance, stolen content
- **Freelancers** — Client contracts, non-payment disputes, intellectual property protection
- **Startup Founders** — NDAs, employment agreements, IP assignments, corporate structure
- **Tenants & Landlords** — Lease disputes, rent reductions, eviction procedures
- **Employees** — Wrongful termination, wage theft, discrimination, whistleblower protection
- **Anyone who has been wronged** — and wants to know their rights before paying for a lawyer

---

## Example Outputs

### `/brief` — Content Theft Abmahnung (DE)
```
RECHTSGRUNDLAGE: § 97 UrhG DE, § 19a UrhG DE
FRIST: 7 Tage ab Zustellung

---

[Dein Name]
[Adresse]

An: [Name des Verletzers]

[Ort], [Datum]

Abmahnung wegen Urheberrechtsverletzung

Sehr geehrte(r) [Name],

ich bin der alleinige Urheber des am [Datum] auf YouTube unter
[URL] veröffentlichten Videos "[Titel]".

Ich habe festgestellt, dass Sie dieses Werk ohne meine Einwilligung
am [Datum] auf TikTok unter [URL] veröffentlicht haben. Dies stellt
eine Verletzung meines ausschließlichen Rechts der öffentlichen
Zugänglichmachung gemäß § 19a UrhG dar...

[vollständiger professioneller Abmahntext]
```

### `/themis` — FTC Influencer Rules (US)
```
Under 16 C.F.R. Part 255 (FTC Endorsement Guides, updated 2023):

You MUST disclose any material connection — including free products,
discounts, affiliate relationships, or family/employee ties.

Key requirements:
• Disclosure must be "clear and conspicuous"
• Must appear at the BEGINNING of the post (not buried in hashtags)
• "#ad" or "Paid Partnership" both work on Instagram
• YouTube: check the "paid promotion" box AND verbal disclosure in first 30s
• Penalty: up to $51,744 per violation (FTC Act § 5, 15 U.S.C. § 45)

New 2023: AI-generated content that is deceptive = FTC violation.
```

---

## Disclaimer

THEMIS is an AI legal assistant, not a licensed attorney. All information is for educational purposes. For high-stakes matters — criminal defense, custody battles, major litigation — retain a licensed attorney in your jurisdiction. Laws change; verify current statutes for critical decisions.

---

## Contributing

Contributions welcome. Especially:
- Additional jurisdictions (CH, UK, FR, IT, NL...)
- More case law references
- Additional document templates
- Corrections to existing content

Open a PR or issue.

---

## License

MIT License — see [LICENSE](LICENSE)

---

*THEMIS — Having rights is good. Enforcing them is better.*
