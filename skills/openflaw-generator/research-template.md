# OpenFlaw Research Template

Use this template when researching a subject for OpenFlaw analysis.

## Research Checklist

### For People
- [ ] Public interviews about failures/mistakes
- [ ] Statements about personal weaknesses/quirks
- [ ] Autobiographies or memoirs
- [ ] Social media posts about struggles
- [ ] Employee/colleague accounts
- [ ] Documentation of risk-taking behavior

### For Software
- [ ] Known issues / KNOWN_ISSUES.md
- [ ] Security advisories
- [ ] Changelog entries about bugs
- [ ] README limitations section
- [ ] GitHub issues (public bugs)
- [ ] Release notes mentioning tradeoffs

### For Organizations
- [ ] Transparency reports
- [ ] Recalls or public apologies
- [ ] Blog posts about failures
- [ ] CEO/founder statements
- [ ] Culture documentation
- [ ] Press coverage of mistakes

## Example: Elon Musk (Person)

### Flaw: Impulsivity on Twitter
- **The Flaw:** Posts without filter, makes promises publicly
- **The Feature:** Creates urgency, builds hype, keeps stakeholders engaged
- **Evidence:** "Funding secured" tweet, Mars timeline claims
- **Mitigation:** Some tweets get deleted, occasionally apologizes

### Flaw: Aggressive timelines
- **The Flaw:** Constantly misses deadlines
- **Feature:** Drives teams harder, achieves "impossible" eventually
- **Evidence:** Cybertruck delays, FSD timelines
- **Mitigation:** Keeps shipping anyway

### Flaw: Difficult management style
- **The Flaw:** High turnover, demanding boss
- **Feature:** Filters for high performers, creates intense culture
- **Evidence:** Multiple exec departures
- **Mitigation:** Compensates well, equity stakes

**Verdict:** Strong #OpenFlaw practitioner — openly discusses flaws, ships anyway

## Example: Docker (Software)

### Flaw: Root access in containers
- **The Flaw:** Security architecture allows privilege escalation
- **Feature:** Enables powerful DevOps workflows
- **Documentation:** Official docs warn about this
- **Mitigation:** Security best practices, rootless containers in development

### Flaw: Large image sizes
- **The Flaw:** Base images can be bloated
- **Feature:** Flexibility, pre-installed tools
- **Mitigation:** Multi-stage builds, Alpine images recommended

**Verdict:** #OpenFlaw software — documents tradeoffs openly
