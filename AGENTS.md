# AGENTS.md

Rules for any AI agent working on this repository (naomiz1.github.io, the personal site of Xumeng Zhang).

## Source of truth
- Content comes from Xumeng's CV (`Xumeng_Zhang_CV_9.28.pdf`). Do not invent, inflate, or reword facts: titles, dates, numbers, and metrics must match the CV exactly.
- Keep the same section order as the CV: Education, Work Experience, Projects, Volunteer Experience, Skills.
- If the CV and the site ever disagree, flag it to Xumeng. Do not quietly "fix" either one.

## Never publish
- Phone number, home address, date of birth, or any government ID number.
- The CV PDF itself, unless Xumeng explicitly asks for it to be linked or downloadable.
- Transcripts, grades for individual courses, salary or compensation details, references, and visa/immigration status.
- Confidential employer information beyond what is already on the CV: no internal names, client names, screenshots, code, dashboards, or data from Tencent, ICBC, Gaorui, FDNY, or Ask2.ai.
- Photos of Xumeng or of other people.
- API keys, tokens, `.env` files, or anything from a credentials store.
- Analytics, tracking pixels, or third-party scripts that collect visitor data.

Allowed contact details: Columbia email (xz3456@columbia.edu), LinkedIn (https://www.linkedin.com/in/xumeng-zhang1/), and GitHub (https://github.com/naomiz1).

## Ask Xumeng first
- Before any `git push`, commit to a remote, or GitHub Pages deploy. Nothing is published without explicit approval each time.
- Before adding, removing, or rewording any CV content, including GPA, dates, metrics, and employer names.
- Before adding new pages or sections, or changing the section order.
- Before adding any external dependency (scripts, frameworks, fonts beyond Google Fonts, or embedded widgets).
- Before deleting or overwriting any existing file.
- Before adding any new contact detail or personal information.

## Style
- Tone: professional and concise. Use plain, factual language with no hype words ("passionate", "rockstar", "guru"), no emojis, and no exclamation marks.
- Colors: Columbia blue palette.
  - Columbia blue `#B9D9EB` for accents and backgrounds
  - Navy `#1D4F91` for primary links and buttons
  - Deep navy `#0C2340` for headings and text
  - Use white and off-white (`#F7FAFC`) surfaces. Text must meet WCAG AA contrast, so never put light-blue text on white.
- Typography: one clean sans-serif family (Inter, with system fallbacks).
- Navigation: a single sticky top bar with one link per CV section. No dropdowns or nested menus.
- Layout: content cards ("tiles") for each entry. The layout must be responsive with no horizontal scrolling on phones.
- Code: plain HTML and CSS in a single `index.html`, with minimal JavaScript (only for small enhancements such as highlighting the active nav link). The site must work with JavaScript disabled.
- Accessibility: semantic HTML landmarks, alt text, visible focus states, and `prefers-reduced-motion` respected.
