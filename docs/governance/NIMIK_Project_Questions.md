MMIW Project Planning – Foundational Questions

This document outlines critical questions to guide early decisions and clarify the scope, design, and impact of the project. Questions are grouped by domain: technical, methodological, ethical, and social.

---

TECHNICAL DOMAIN

Architecture & Infrastructure
- What tech stack best balances performance, maintainability, and low-cost hosting?
- Will the system be modular (e.g., separate scrapers, API, frontend)?
- Will we self-host or use cloud services like Supabase, Render, or Vercel?
- How will data persistence and versioning be handled?

Data Handling
- What fields will we support in our initial data schema?
- How will we store multimedia (e.g., photos)? Will we proxy or hotlink?
- Will we use relational DBs (PostgreSQL) or flexible formats (JSON, NoSQL)?
- How will we handle duplicate or conflicting data entries?

Scaling & Updates
- How often will scrapers run? On schedule or trigger-based?
- How will we detect changes in source data over time (diffs)?
- Will we support real-time search, or batch-generated static content?

Security
- What level of access control do we need (admin roles, read-only, API keys)?
- How will we handle rate limiting for scraping and public access?
- What steps are in place to protect sensitive data from exploitation or misuse?

---

METHODOLOGICAL DOMAIN

Data Collection
- What qualifies as a valid source? (e.g., tribal agency vs. advocacy blog)
- How will we normalize and structure unstructured data (free text, PDFs)?
- How will we handle partially complete data (missing dates, names, tribal info)?

Provenance
- How will we track where each piece of data came from?
- Will we archive snapshots of source pages as evidence?
- How will we ensure data is not manipulated or falsified post-scrape?

Version Control
- Will records be immutable or editable with logs?
- How do we manage updates to cases (e.g., found, deceased, reclassified)?
- Can users submit corrections or flags?

---

ETHICAL DOMAIN

Data Ethics
- Are we legally and ethically allowed to scrape and republish each source?
- How do we honor tribal data sovereignty while still indexing public cases?
- What are our red lines for showing sensitive info (e.g., graphic case notes, juvenile names)?

Consent & Removal
- Will families or tribes be able to request takedowns or edits?
- Will we build a consent mechanism for family-submitted info in the future?

Representation
- Are we reinforcing bias or misrepresenting cases in how they’re displayed?
- Are we amplifying the cases equitably across tribes and regions?

Transparency
- How will we disclose the limitations of our data (incompleteness, accuracy)?
- Will we publish a changelog or system health dashboard?

---

SOCIAL DOMAIN

Community Trust
- How do we earn and maintain trust from Native communities and MMIW orgs?
- Who will we consult before launching the project publicly?
- Are we open to tribal audits or co-governance of the system?

Collaboration
- Which orgs, agencies, or independent researchers should we partner with early?
- How will we avoid duplicating or undermining existing efforts?

Impact
- What outcomes do we want to measure (e.g., search visibility, solved cases, pressure on agencies)?
- How do we avoid retraumatizing families or exploiting stories for clout?

Longevity
- Who maintains the system long-term?
- How do we prepare for handoff, archiving, or scaling if it grows rapidly?
- Should this become a nonprofit or integrate into existing civic tech ecosystems?

---

NEXT STEPS

1. Review and answer all “Phase 1” critical questions.
2. Organize answers into a living project brief.
3. Begin structuring development phases based on clarified answers.
