> **Moved.** This kit now lives in **https://github.com/veles-productions/veles-brand** — one repository for the Veles brand.
> Brand book: https://veles-productions.github.io/veles-brand/ · Install prompt: https://github.com/veles-productions/veles-brand/blob/main/INSTALL-PROMPT.md
> This repository is archived and no longer updated.

# Veles Brand Kit — Brand 3.2

**This is the new Veles Productions brand.** Everything the team and our AI agents need to make
materials on brand: the brand book, a one-page guide, logos, signs, colours, fonts, ready-to-paste
animated elements for the website, and a banner generator.

- **Brand book (web, with motion):** https://veles-productions.github.io/veles-brand-kit/
- **Download everything (ZIP, no account needed):** https://github.com/veles-productions/veles-brand-kit/archive/refs/heads/main.zip

## Start here

| If you want to… | Open |
|---|---|
| understand the brand | [`BRAND-BOOK.md`](BRAND-BOOK.md) or the web version |
| know the essentials in one page | [`QUICK-GUIDE.md`](QUICK-GUIDE.md) |
| put the brand into Claude Code, Gemini CLI or Cursor | [`INSTALL-PROMPT.md`](INSTALL-PROMPT.md) |
| update the website | [`website/WEBSITE-BRIEF.md`](website/WEBSITE-BRIEF.md) |
| make a banner | [`banners/banner.html`](banners/banner.html) (open in a browser) |
| add motion to a web page | [`embeds/`](embeds/) |

## What is inside

```
AGENTS.md              rules your AI agent loads (compact)
BRAND-BOOK.md          the full brand book
QUICK-GUIDE.md         one page, plus what each person should do
INSTALL-PROMPT.md      the prompt that installs the brand in your agent
index.html             the brand book as a web page
cursor/                rule file for Cursor (copy of AGENTS.md)
tokens/                tokens.css, tokens.json — colours, type, motion
assets/logo/           Logo_<colour>.png (tight crop) and Logo_big_<colour>.png (with clear space)
assets/signs/          the Veles signs (SVG) and pixel-sign grids
assets/fonts/          Manrope (OFL) — interim brand font
embeds/                pixel-sign hero, sign draw, reveal + progress, UI components
banners/               banner generator: Kadr and Red, four social sizes
website/               brief for the website update
systems/               Veles Systems preview (green, not final)
```

## Embedding animated elements (Webflow and others)

Each file in `embeds/` opens as a demo in a browser. Copy everything between
`VELES EMBED START` and `VELES EMBED END` into a Webflow **Code Embed** (or any HTML block).
No libraries, no iframes. Motion stops automatically for visitors with reduced motion.

## Rights

Logo and Veles signs © Veles Productions — for Veles team and partners working on Veles
materials only. Manrope: SIL Open Font License (`assets/fonts/Manrope-OFL.txt`).
Alliance No.2 is not included (licence pending).

Questions: Artur Paprocki.
