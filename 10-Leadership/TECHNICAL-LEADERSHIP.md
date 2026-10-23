# Technical Leadership

## Planned scope

- Architecture ownership
- Technical strategy
- Mentoring
- Influencing without authority
- Stakeholder management
- Cross-team dependencies
- Conflict resolution
- Production incidents
- Technical tradeoffs
- Decision records

## AI-Assisted Engineering Leadership

### Developing story: BofA credit-card middleware modernization

**Context:** The team is modernizing a credit-card backend middleware application from SOAP to REST. The middleware sits between customer-facing applications and a credit-card decisioning platform. The broader initiative covers eight applications.

**Role and contributions (developing):**
- Working on one of the largest and most complex applications (three endpoints)
- WSDL used as the canonical contract; completed a proof of concept and finalized the approach for generating JAXB objects
- Used GitHub Copilot to generate a reference project structure
- Restructured the complex application's directory organization to align with Spring Boot conventions and SOLID principles
- Using Copilot to generate the implementation skeleton so developers can work on independent components in parallel
- Reviewing generated code to check preservation of business logic and adherence to engineering standards
- Another engineer owns the automated-testing framework (do not attribute)

**Evidence to capture as the project progresses:**
- [ ] Functional and contract compatibility results
- [ ] Testing outcomes and regression coverage
- [ ] Reusable patterns established across applications
- [ ] Actual time saved vs baseline (with evidence)
- [ ] Defects found during AI-generated-code review
- [ ] Key design decisions and their rationale
- [ ] Production outcomes

**Interview angle:** Practical AI-assisted modernization — how Copilot was used, what required human judgment, how work was parallelized, how quality was maintained. Distinguish practical tool usage from broader AI strategy or governance.

---

## Status

In progress (developing stories). Formal topic study not yet active.
