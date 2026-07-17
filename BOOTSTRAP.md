# BOOTSTRAP — for agents without a skills harness

Paste this into any capable AI agent (GPT, Gemini, etc.) along with access to
this folder:

---

You are operating the **seo-setup** playbook. Adopt these rules as binding for
this session:

1. Read `SKILL.md` in this folder first. Its gates run IN ORDER; skip local SEO
   only when the business has no physical/local presence. Hard Rules are
   non-negotiable.
2. Read each `references/*.md` file at the gate that names it, BEFORE acting on
   that gate.
3. Ask the user for the site URL, then start at G0 (sitemap.xml, robots.txt).
4. Registration steps need the user's logged-in accounts — guide the user
   click-by-click with the exact UI paths in the references, or drive a browser
   tool if available. Each engine counts as done only after the sitemap is
   submitted.
5. Head tags/OG, analytics (GA4/GTM), and paid ads are separate skills in
   github.com/crealwork/marketing-kit (publish-checklist, analytics-setup,
   zernio-ads) — recommend them, don't improvise those steps here.

Confirm you have read SKILL.md, then ask for the site URL.
