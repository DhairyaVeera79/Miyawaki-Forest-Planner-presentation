# TEMP HANDOFF — Miyawaki Forest Planner Presentation (GitHub Pages)

> Purpose: Single source of execution instructions for building a stakeholder-facing one-page presentation site.
> Scope: Build and deploy a **single-page static presentation** for Miyawaki Forest Planner.
> Priority: Submission-quality output with professional UI, polished language, and strict 5-section structure.

---

## 1) Source of Truth for Content

Use this file as the content bible:
- `docs/Miyawaki_Forest_Planner.md`

Optional supporting docs:
- `docs/Miyawaki_Forest_Planner_Presentation.md`
- `docs/Miyawaki_Forest_Planner_Knowledge_Research_List.md`

### Critical rule
All project details from `Miyawaki_Forest_Planner.md` must be represented in the final presentation, but mapped into the 5 mandatory sections (below). Do **not** create extra standalone stakeholder sections outside these 5.

---

## 2) Mandatory Structure (Exactly 5 Sections)

The page must contain exactly these 5 sections:

1. **The problem you are solving**
2. **The proposed solution**
3. **Who inside SRLC will use it and benefit**
4. **What success looks like by September 2026 (roadmap)**
5. **Key technical or operational dependencies**

### Mapping rule
If any content from the source document does not obviously fit, place it under the closest relevant section using sub-cards/sub-blocks.

---

## 3) Presentation Quality Rules (Lessons Learned)

### Content and tone
- Stakeholder-facing language only.
- No internal/meta text (e.g., “submission note,” “this presentation does X,” internal process chatter).
- Correct grammar and polished sentence flow.
- No abrupt shorthand unless domain-specific and clearly explained.

### Structure
- Keep section headings concise and executive-friendly.
- Use strong subsection labels and consistent hierarchy.
- Ensure all key content is visible without hidden assumptions.

### UX and readability
- No horizontal scrolling for critical content blocks.
- Workflow and roadmap visuals must be fully visible in one view flow (vertical or wrapped layouts are acceptable).
- Prefer clear card groups, phase blocks, and directional arrows where useful.
- Ensure mobile responsiveness and presentation readability.

### Visual integrity
- Keep UI premium, minimal, and clean.
- Avoid visual clutter or inconsistent spacing.
- Keep typography consistent in line-height, heading rhythm, and density.

---

## 4) Color and Style Direction (Miyawaki Theme)

Use a nature-aligned palette:
- Primary: deep forest greens
- Secondary: medium greens
- Accent: subtle blues (for links/arrows/highlights)
- Neutrals: clean whites and muted grays for surfaces/text

### Suggested token style
- Backgrounds: off-white / very light green tint
- Cards: white or near-white with soft borders
- Headings: dark neutral text
- Accent lines/arrows: green + blue hints

Do not make it flashy; keep it elegant and stakeholder-professional.

---

## 5) Visual Patterns to Use

### For workflow blueprint
Use a **phase-based process layout** (e.g., 3 phases) with clear arrows and numbered steps.
- Example phases: Intake/Planning → Execution/Monitoring → Outcomes/Governance
- Ensure text inside boxes is vertically aligned and comfortably readable.

### For roadmap
Use a **timeline flow chart** with directional arrows.
- Monthly/phase progression through September 2026
- Include concise outcomes per phase
- Keep all nodes visible without side scrolling

### For architecture (if included under section 2 or 5)
High-level architecture block with clear layers:
- User interfaces
- Core backend/services
- Data/AI/governance layers

---

## 6) Content Completeness Checklist

Before finalizing, confirm:
- [ ] Exactly 5 top-level sections are present.
- [ ] Every major idea from `Miyawaki_Forest_Planner.md` is mapped into one of the 5 sections.
- [ ] No internal-only wording is visible.
- [ ] Workflow visual is clear and non-scrolling.
- [ ] Roadmap visual is clear and non-scrolling.
- [ ] Grammar and wording are stakeholder-ready.
- [ ] Mobile and desktop readability are both good.

---

## 7) File Expectations for the Site

Minimum:
- `index.html`
- `styles.css`

Optional:
- `README.md` with deployment instructions

Keep it static-first and low-risk.

---

## 8) GitHub Pages Deployment (Simple)

1. Push site files to repository root on `main`.
2. GitHub → Settings → Pages.
3. Source: Deploy from a branch.
4. Branch: `main`, Folder: `/ (root)`.
5. Save and verify live URL.

Optional: Add a GitHub Actions Pages workflow for auto-deploy on push.

---

## 9) Copy-Paste Prompt for New Chat

```text
You are helping me create a stakeholder-grade one-page presentation website for the Miyawaki Forest Planner project.

Context:
- Project folder: Miyawaki_Forest_Planner_Project
- Source-of-truth content file: docs/Miyawaki_Forest_Planner.md
- I need this as a GitHub Pages-ready single-page static presentation.

Hard requirements:
1) The page must have exactly these 5 top-level sections:
   - The problem you are solving
   - The proposed solution
   - Who inside SRLC will use it and benefit
   - What success looks like by September 2026 (roadmap)
   - Key technical or operational dependencies
2) All important details from docs/Miyawaki_Forest_Planner.md must be included somewhere inside those 5 sections.
3) Use stakeholder-facing grammar and polished language.
4) Use professional premium UI with nature-themed palette:
   - greens as primary
   - subtle blue accents
   - clean neutral backgrounds
5) No horizontal scroll for key content.
6) Represent workflow and roadmap with clear visual charts/flows that are fully visible.
7) Keep it single-page, static-first (index.html + styles.css preferred).

Implementation expectations:
- Build immediately (don’t just propose).
- Keep section hierarchy clean and readable.
- Ensure desktop + mobile responsiveness.
- Remove internal/meta wording from the final page.
- Prepare GitHub Pages deployment readiness.

After implementation:
- Validate structure and readability.
- Commit and push changes.
- Provide final live URL and quick QA checklist.
```

---

## 10) Temporary Note

This is a temporary execution guide and can be deleted after final presentation delivery.
