# AI-Reviewer-Contradiction-ChatGPT5

---

## ⚠️ **Important Notice (Added October 2025):**  

- This repository presents a **student-led, independent research investigation** analyzing evidence-alignment and reviewer-contradiction behavior observed in the **public paid-tier web interface** of OpenAI’s ChatGPT-5 model.  
- The project reflects the author’s dual role as an **independent researcher and computer-science student**, combining formal academic learning with self-directed experimentation.  
- All testing was conducted using the author’s **personally purchased ChatGPT Plus/Pro subscription**, providing authorized public access only — no internal tools, privileged APIs, or confidential materials were involved.  
- Screenshots, transcripts, and structured logs are included **solely for educational and research documentation under fair-use provisions**.  
- This work is **not affiliated with, endorsed by, or connected to OpenAI, Google, or Anthropic** in any way.  
- The purpose of this investigation is purely **academic and educational** — to study, document, and better understand reviewer-level contradictions, perception errors, and evidence-alignment limitations in large conversational AI systems.


---

## Context  
This repository documents a **contradiction incident** involving *ChatGPT-5* when acting as a reviewer of an academic-style PDF.  
Unlike typical hallucinations or answer errors, this case highlights a **direct misalignment between claimed evidence and visible evidence**.  

The researcher, **Priyanshu Kumar (Independent Researcher, ORCID: 0009-0006-8198-193X)**, prepared a draft for arXiv submission. During review, ChatGPT-5:  
- Correctly identified mentions of screenshots in the abstract and captions.  
- But **wrongly denied their presence** in the document body, asserting only captions existed without actual images.  

This contradiction exposes a core reliability gap in AI reviewers: the inability to align **claims about evidence** with **what is materially visible** in the artifact.  

## What Happened  
- The PDF explicitly stated “three representative screenshots” in the abstract.  
- Figures 1–3 were each labeled as screenshots with captions.  
- ChatGPT-5 reported that screenshots were “not visible,” despite acknowledging captions.  
- Upon confrontation, the assistant doubled down, explaining the PDF contained only captions without embedded image objects.  

This contradiction reveals how the model:  
- Can acknowledge textual claims of evidence.  
- Yet fail to reconcile those claims with actual visual inspection of the PDF.  

## Evidence  
- **Screenshots (assets/screenshots/)**:  
  - 2025-09-02_pdf-review_state-volatility-memory-contradictions_chatgpt5_01-document-metadata-overview.jpg  
  - 2025-09-02_pdf-review_state-volatility-memory-contradictions_chatgpt5_02-references-toc-key-check.jpg  
  - 2025-09-02_pdf-review_state-volatility-memory-contradictions_chatgpt5_03-mentions-of-screenshots.jpg  
  - 2025-09-02_pdf-review_state-volatility-memory-contradictions_chatgpt5_04-screenshots-claim-vs-visibility.jpg  

- **Reports (reports/)**:  
  - `chatgpt5_reviewer-contradiction_log.jsonl` (structured log).  
  - `chatgpt5_reviewer-contradiction_log.md` (human-readable log).  
  - `SHA256_checksum.txt` (cryptographic verification).  

- **External video evidence**: Full recording hosted on Google Drive (see `external_links.md`).  

## Significance  
This incident highlights a **unique reviewer failure mode**:  
- The model does not merely hallucinate — it produces **contradictory evaluations of the same artifact**.  
- Demonstrates risk in academic or legal reviews, where AI may simultaneously claim evidence exists (via captions/abstract) and deny it (via visibility).  
- Suggests *dual-track reasoning*: textual vs. structural interpretations not being reconciled.  

## Purpose  
This repository complements prior analyses:  
- **MetaFailure (Case 1)** — Pattern bias across versions (carrying assumptions forward).  
- **Contradiction (this Case 2)** — Misalignment between claimed vs. visible evidence.  
- **Speculation (Case 3)** — Review drift into unverifiable hypotheses.  

Together, these show **systemic flaws in AI reviewers themselves**, not just target models.  

---
**Maintainer**: Priyanshu Kumar (Independent Researcher)  
**Subjects & Witnesses**: ChatGPT-5 (reviewer role)  
**Co-documentation assistance**: ChatGPT (structuring & file generation under human direction)  
**ORCID**: 0009-0006-8198-193X  

---

## Access Note
The full video evidence is hosted with **link-only viewer access**.  
It is **not public, not indexed, and not searchable** — ensuring controlled distribution.  
This balance keeps the research transparent while preventing accidental exposure.

---

*Note: This clarification notice was added in October 2025 to ensure full transparency regarding the research scope, ethical intent, and academic context of this project.  
The author conducted this investigation independently as part of personal academic exploration into AI reviewer reliability using officially authorized paid access to ChatGPT-5.*

