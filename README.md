# Shipped With AI

Source for [mathman1111.github.io](https://mathman1111.github.io) — a real build log by a university student
in Japan, in a second language, documenting small tools built with AI coding assistants (mainly [Claude
Code](https://www.anthropic.com/claude-code)). No hype, no invented numbers: honest write-ups of what worked,
what broke, and how long things actually took.

## What's on the site

- [Why this site exists](https://mathman1111.github.io/articles/2026-08-24-why-this-site-exists.html)
- [A product catalog tool for shop owners who can't code](https://mathman1111.github.io/articles/2026-08-24-catalog-tool-for-a-shop-that-cant-code.html)
- [A free tool with a Pro tier that doesn't work yet](https://mathman1111.github.io/articles/2026-08-24-half-finished-monetization.html)
- [A pricing tool for makers guessing at their own prices](https://mathman1111.github.io/articles/2026-08-24-pricing-tool-for-makers.html)
- [Letting Claude Code subagents run a company](https://mathman1111.github.io/articles/2026-08-25-running-an-ai-agent-company.html)
- [Fixing the catalog sync bug](https://mathman1111.github.io/articles/2026-08-29-fixing-the-catalog-sync-bug.html)

## Stack

Plain static HTML/CSS, no build step, hosted on GitHub Pages. `sitemap.xml` + `robots.txt` for search engines,
[IndexNow](https://www.indexnow.org/) pinged automatically on every push via GitHub Actions
(`.github/workflows/indexnow.yml`), and privacy-respecting analytics via Cloudflare Web Analytics.

## License

Site content is © the author. Feel free to read, link, and learn from the approach — please don't republish
the articles wholesale.
