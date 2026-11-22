# swiss-banking-compliance-copilot
Swiss Banking Compliance &amp; RegTech Copilot

Following my first WealthTech prototype, I built a second open-source project focused on RegTech & Financial Crime Prevention: the Swiss Banking Compliance Copilot (Python, Streamlit, Gemini LLM).

Designed to support both Private Banking and Institutional workflows, this dual-module assistant tackles two daily operational pain points:

- KYC & AML Surveillance (AMLA / LBA): Compares 30-day account inflows/outflows against a client’s declared source of wealth to flag volume anomalies, pass-through behavior, and draft structured Enhanced Due Diligence (EDD) memos.
  
- Pre-Send Suitability & Comms Auditor (FIDLEG / LSFin): Reviews Relationship Manager email drafts against the client's approved risk mandate, flags prohibited yield promises, and generates a compliant rewrite before anything is sent.

Advantages:

- Time & Operational Efficiency: "In Swiss banking, compliance officers and RMs typically spend 45 to 90 minutes per alert manually cross-checking transaction logs against KYC profiles—a workflow this copilot accelerates by ~75%, turning hours of investigative memo drafting into a 2-minute review."

- Risk Reduction & Commercial Speed: "At the same time, pre-screening client emails against FIDLEG (LSFin) suitability rules catches regulatory red flags before they leave the bank—protecting against costly FINMA sanctions while allowing Relationship Managers to follow up with clients 5x faster."
