# chatgpt5_incident_v17/

## Context
This folder documents **Incident v17** in the ongoing investigation of ChatGPT-5’s handling of evidence within uploaded research PDFs. In this case, the system was asked to evaluate **PDF v17** and determine whether screenshots were present.  

The evaluation revealed a discrepancy: the **Abstract and figure captions** mention “three representative screenshots,” but the **PDF itself contained no visible images**.  

---

## What Happened
- **Abstract**: Explicitly stated evidence included “24 standardized logs and three representative screenshots.”  
- **Evidence Section**: Contained **Figure 1–3 captions**, each referring to screenshots.  
- **Observation by ChatGPT-5**: While the textual references were acknowledged, the assistant noted that **no actual figures or images appeared in the PDF body**.  
- **Result**: This was labeled an **evidence misalignment** — textual claims of screenshots without corresponding visible artifacts.  

---

## Significance
This incident highlights a key risk in AI-assisted document review:  
- AI may **differentiate between “textual claims” and “visible evidence.”**  
- If misalignment occurs, the system may flag inconsistencies, but users could misinterpret this as either false negatives or missed content.  
- Such situations create **flawed assessments**, especially in research contexts that depend on verifying whether visual evidence (screenshots, figures, charts) is actually present.  

---

## Purpose
- Extends earlier **v15–v16 cases** (pattern bias and speed-over-accuracy failures).  
- Documents a **new failure mode**: *misalignment between claimed evidence and visible evidence*.  
- Serves as a structured reference point for future reliability testing of LLMs in **document analysis, auditing, and fact verification tasks**.  
