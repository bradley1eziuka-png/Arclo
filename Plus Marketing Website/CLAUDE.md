# CLAUDE.md — Web Design + Marketing

## Skills Active This Session

Read and apply each skill file below before starting any work. No exceptions.

| Skill | File |
|-------|------|
| Frontend Design | `Frontend design skill.md` |
| Stop Slop | `stop-slop-main/SKILL.md` |
| UI/UX Pro Max | `ui-ux-pro-max-skill-main/src/ui-ux-pro-max/` |
| Context Engineering | `Agent-Skills-for-Context-Engineering-main/SKILL.md` |
| Copywriting | `marketingskills-main/skills/copywriting/SKILL.md` |
| CRO | `marketingskills-main/skills/cro/SKILL.md` |
| SEO Audit | `marketingskills-main/skills/seo-audit/SKILL.md` |

---

## When to Apply Each Skill

- **Frontend Design** — read before writing any frontend code, every session.
- **Stop Slop** — apply to all copy: headlines, body text, CTAs, microcopy, email sequences.
- **UI/UX Pro Max** — run the design system search before building any new page or component.
- **Context Engineering** — apply throughout long sessions to manage context window efficiently.
- **Copywriting** — apply when writing or rewriting any client-facing text on the site.
- **CRO** — apply to page structure and layout decisions to maximize conversions.
- **SEO Audit** — run after the build is complete to ensure search optimization.

---

## Local Server

- Always serve on localhost — never screenshot a `file:///` URL.
- Start dev server: `python3 -m http.server 3000` (serves project root at `http://localhost:3000`)
- If server is already running, do not start a second instance.

---

## Screenshot Workflow

- Always screenshot from localhost: `http://localhost:3000`
- After screenshotting, read and analyze the image directly.
- When comparing against a reference, be specific: "heading is 32px but reference shows ~24px", "card gap is 16px but should be 24px."
- Do at least 2 comparison rounds. Stop only when no visible differences remain or user says so.

---

## Output Defaults

- Single `index.html` file, all styles inline, unless user says otherwise.
- Tailwind CSS via CDN: `<script src="https://cdn.tailwindcss.com"></script>`
- Placeholder images: `https://placehold.co/WIDTHxHEIGHT`
- Mobile-first responsive.

---

## Brand Assets

- Always check the `brand_assets/` folder before designing.
- If a logo is present, use it. If a color palette is defined, use those exact values.
- Do not use placeholders where real assets are available.

---

## Reference Image Rules

- If a reference image is provided: match layout, spacing, typography, and color exactly. Do not improve or add to the design.
- If no reference image: design from scratch following the Frontend Design skill.
- Do not add sections or content not in the reference.
- Do not "improve" a reference — match it exactly.
