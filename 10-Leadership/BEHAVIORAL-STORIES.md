# Behavioral Stories

Build concise STAR-style stories around:

- difficult technical decision
- production incident
- conflict
- mentoring
- influencing stakeholders
- architecture migration
- delivery under pressure
- failure / lesson learned
- cross-team leadership

---

## Stories in development

### SOAP-to-REST middleware modernization (BofA, current)

**Category:** Architecture migration / AI-assisted engineering

**Situation:** Credit-card backend middleware (SOAP) being modernized to REST. Initiative covers eight applications. Assigned to one of the largest and most complex applications (three endpoints). Middleware connects customer-facing apps to a credit-card decisioning platform.

**Actions taken so far:**
- Completed a proof of concept using WSDL as the canonical contract; finalized the JAXB object generation approach
- Used GitHub Copilot to generate a reference project structure
- Restructured the application's directory organization to align with Spring Boot conventions and SOLID principles
- Using Copilot to generate the implementation skeleton, enabling developers to work on independent components in parallel
- Reviewing generated code for business-logic preservation and engineering standards compliance

**Key distinction:** Another engineer owns the automated-testing framework. Do not claim that work.

**Result:** Developing. Capture evidence as the project progresses — see `TECHNICAL-LEADERSHIP.md` for the evidence checklist.

**Interview framing:** Focus on individual contributions, technical decisions, how AI tools were used effectively, and what required human judgment. Use concrete evidence, not unsupported productivity claims.

---

## Status

In progress (developing stories).
