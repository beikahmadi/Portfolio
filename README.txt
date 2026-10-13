MEHRAN WEB STUDIO — BUSINESS WEBSITE, DRAFT VERSION
===================================================

WHAT THIS IS
A new, original, responsive single-page website design for an independent
web design/development service targeting Canadian small-business clients.

FILES
index.html — complete standalone website with CSS and JavaScript embedded.
favicon.svg — brand icon for browser tabs.
robots.txt and sitemap.xml — basic search-engine discovery files.

SUGGESTED DEPLOYMENT (YOUR EXISTING GITHUB + CLOUDFLARE)
1. Back up the current index.html in beikahmadi/Portfolio (for example:
   rename it to old-index-backup.html in Codespaces).
2. Upload index.html, favicon.svg, robots.txt, and sitemap.xml at the
   repository root, replacing the old index.html.
3. Run `git add index.html favicon.svg robots.txt sitemap.xml old-index-backup.html` (if renaming it),
   `git commit -m "Launch web design business site"`, and
   `git push origin main`.
4. Cloudflare is connected to that repo; check Deployments and retry a build
   if it doesn't run automatically.
5. Open https://portfolio.mehranbeikahmadi.workers.dev and test the menu,
   links and mailto contact button on desktop and phone.

IMPORTANT BEFORE GOING PUBLIC
- "Mehran Web Studio" is a working name, NOT a registered-business claim.
- Contact currently uses m_beikahmadi@shaw.ca. Replace globally if preferred.
- Case studies cite ONLY actual public repositories and described experience,
  not invented clients, reviews, results or pricing.
- Mailto opens an email client: there is no backend inquiry form.
- Remove or archive old Colorlib template source and unused assets once the
  new site is safely running; confirm licensing and keep needed backups.
- If you change your production domain, update the canonical and OG URLs,
  and JSON-LD structured data in index.html.
- Verify the claims, wording and email address before publishing.
- This package doesn't change or publish anything to GitHub or Cloudflare.
