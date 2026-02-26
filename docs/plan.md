# Project Plan — Portfolio Website Prototype

## Project Approach
This project follows a lightweight “unofficial project manager” approach:
- Define scope and success criteria first (scope statement)
- Identify risks early using TAME
- Break the work into small tasks (WBS)
- Build a working prototype quickly, then refine for quality and professionalism
- Reflect on results and process (retrospective)

---

## Risk Analysis (TAME Framework)

### T — Technical Risks
**Risk:** GitHub Pages deployment fails (wrong branch/folder, broken links).  
- **Impact:** Live site won’t load; grading penalty.  
- **Mitigation:** Use root-level `index.html`; verify Pages settings; test URLs; use relative links (`about.html`, `style.css`).  
- **Early Warning:** 404 errors or CSS not applying on live site.

**Risk:** HTML structure is not semantic or headings are inconsistent.  
- **Impact:** Accessibility/quality issues; rubric impact.  
- **Mitigation:** Use `header/nav/main/section/footer`; keep one `h1` per page; validate quickly by visually scanning heading order.

### A — Administrative Risks
**Risk:** Repo requirements missed (docs folder, required filenames, README links).  
- **Impact:** Point loss under professionalism/documentation.  
- **Mitigation:** Follow a pre-submit checklist; confirm folder structure matches the assignment exactly.

### M — Management Risks
**Risk:** Scope creep (trying to add extra pages/features).  
- **Impact:** Incomplete deliverables or rushed quality.  
- **Mitigation:** Lock scope to 2 pages + shared CSS; note future features as “out of scope”.

### E — External Risks
**Risk:** Time constraints or personal schedule conflicts.  
- **Impact:** Rushed documentation or incomplete polish.  
- **Mitigation:** Build prototype early, then reserve time for revision; keep content concise and easy to edit.

---

## Work Breakdown Structure (WBS) + Simple Schedule

### Phase 1 — Repo Setup & Planning (Day 1)
1. Create new public GitHub repository
2. Add required folder structure (`docs/`)
3. Draft `README.md` with placeholders for live links
4. Create initial versions of scope/plan docs

### Phase 2 — Build Prototype (Day 1–2)
5. Build `index.html` with semantic structure + content sections
6. Build `about.html` with consistent structure and navigation
7. Create `style.css` and confirm it applies to both pages
8. Test navigation links and responsiveness

### Phase 3 — Quality & Alignment (Day 2)
9. Validate consistency: scope goals match what the site actually does
10. Improve accessibility: focus states, readable spacing, link clarity
11. Polish design: layout, typography, spacing, and visual hierarchy

### Phase 4 — Deployment & Submission (Day 2–3)
12. Enable GitHub Pages (Settings → Pages)
13. Confirm live URL loads both pages + CSS
14. Finalize docs (`scope.md`, `plan.md`, `retrospective.md`)
15. Final review with checklist:
    - All required files present
    - README links work
    - Site works on mobile/desktop
    - No broken links, no missing assets

---

## Milestones
- **M1:** Repo created with correct structure + docs started
- **M2:** Prototype pages built and styled consistently
- **M3:** Live deployment working; final docs + README polished
