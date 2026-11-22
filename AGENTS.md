# AGENTS.md — jonathanmccallum-sw (Swahili mirror of jonathanmccallum.com)

Swahili mirror site. Same theme and design as the main site (Paper Light),
content translated into Swahili, meaning-first. Repo: streamjonathan/jonathanmccallum-sw.
Live (when approved): sw.jonathanmccallum.com. Proof: jonathanmccallum-sw.pages.dev.

## Mission

Mirror jonathanmccallum.com in Swahili — every article translated for meaning,
not word for word, in Jonathan's voice: plain short sentences, friendly, positive,
never preachy. An average person interested in Jesus, not an expert or theologian.

## Roles

- **Bobby (Muse) is the lead builder.** He coordinates, builds, pushes to GitHub
  and deploys to Cloudflare. He is the ONLY one who pushes or deploys.
- **Claude advises and reviews** translation quality. He does not push or deploy.
- **Helper Muses translate** one article at a time, drafts only.

## The one rule above all

**Never publish or alter live production assets without Jonathan's clear
permission.** The Swahili site goes live on sw.jonathanmccallum.com only when
he says so, after reading the pilot article(s). Drafts stay drafts until he
approves them. Work on a branch, never straight on main. Give Bobby a preview URL.

## Translation rules

- English repo (streamjonathan.github.io) is the source of truth. Articles are
  translated from the English Markdown, keeping the same date, slug, source_video
  and shareImage. Only the title and body are translated.
- Lewis quotations: use the published Swahili translation where one exists
  (cite it); otherwise translate fresh and mark it "translated for this site".
- Bible verses: use the Swahili Union Version (SUV) wording, never re-translate from the English article. No direct verse quotations appear in the 5 proof articles and SUV wording could not be verified online — check against a printed SUV before quoting any verse directly.
- Names (never vary): Yesu, Mungu, Aslan, Narnia, Lucy, Digory, Tirian, Adamu na Hawa. Book titles are kept in English (The Chronicles of Narnia, The Magician's Nephew, The Great Divorce, The Space Trilogy, The Last Battle) — flagged for Jonathan, as no published Swahili translation was found.
- Voice: Register: warm personal 'wewe', short plain sentences, no preaching.
- No emojis, no newsletter form, no links the English article does not have.
- Never invent facts, dates, links or details.

## Site facts

- Eleventy 3, Cloudflare Pages, Paper Light theme (Fraunces + Newsreader).
- No Ask chat and no note Worker on this site yet — search (Pagefind) works,
  Ask and notes come later. The Ask floating button and ask.js are removed.
- CSS is preloaded, not inlined (CSP blocks inline style). Bump the `?v=` query
  on any CSS/JS file you change.
