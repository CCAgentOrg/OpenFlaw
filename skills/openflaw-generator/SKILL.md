# OpenFlaw Generator Skill

**Skill:** openflaw-generator  
**Description:** Generate an OpenFlaw document for a person, software project, or organization by conducting deep research and applying #OpenFlaw principles.  
**Location:** `skills/openflaw-generator/`

---

## Overview

This skill generates comprehensive OpenFlaw documents that apply the principles of radical transparency to any subject—identifying flaws, reframing them as features, and documenting known issues transparently.

## When to Use

Use this skill when:
- Analyzing a person (public figure, founder, developer) for OpenFlaw traits
- Evaluating a software project for OpenFlaw practices
- Assessing an organization's transparency culture
- Creating case studies for the #OpenFlaw showcase

## Input

The skill accepts:
- **Target:** A person, software project, or organization name
- **Research depth:** Brief (1-2 sources) or Deep (5+ sources)

## Process

### Step 1: Research the Subject

For **people:**
- Search for public statements about failures, flaws, or mistakes
- Look for interviews where they discuss weaknesses or unconventional traits
- Find examples of transparency in their career
- Identify traits that could be "flaws-as-features"

For **software:**
- Find the project's known-issues, security advisories, or changelog
- Look for transparency in bug reporting and vulnerability disclosure
- Check if they document tradeoffs and limitations
- Find examples of shipping with known issues

For **organizations:**
- Research their approach to recalls, errors, or public failures
- Look for transparency reports, open letters, or public admissions
- Find culture statements about failure and learning
- Identify documented tradeoffs in products/services

### Step 2: Apply OpenFlaw Framework

For each identified flaw, document:

1. **The Flaw** — What is it? Be specific.
2. **The Feature** — How does it actually add value?
3. **Mitigation** — What do they do about it?
4. **Examples** — Concrete quotes or incidents

### Step 3: Structure the Output

```markdown
# OpenFlaw: [Subject Name]

## Summary
[2-3 sentence overview]

## Known Flaws / Transparency Record

### Flaw 1: [Name]
- **The Flaw:** [Description]
- **The Feature:** [How it's useful]
- **Evidence:** [Quotes, links, incidents]
- **Mitigation:** [What they do about it]

### Flaw 2: [Name]
[...]

## Unresolved Issues
[Any flaws that remain unaddressed]

## Verdict
[Does this subject embody #OpenFlaw principles?]
```

### Step 4: Quality Checks

- Verify all claims with sources
- Ensure fair representation
- Include both strengths and weaknesses
- Make it actionable (others can learn from it)

## Output

A markdown document saved to the workspace that:
- Is 800-2000 words
- Includes 3-7 specific flaws/features
- Has inline citations where possible
- Ends with a verdict on #OpenFlaw alignment

## Examples

See the main manifesto showcase for reference:
- People: Elon Musk, Richard Branson
- Software: Linux Kernel, Docker, WordPress
- Organizations: Tesla, Basecamp, GitHub

## Notes

- Be objective — don't glorify or vilify
- Focus on transparency, not just success
- If subject is controversial, acknowledge it
- Always provide evidence for claims
