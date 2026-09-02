# canva-drop

Yoga Australia's staging repo for Canva. Public, so nothing confidential lives here, only public social and print assets.

**Point a fresh Claude session at this repo and at a published article, and ask it for a carousel.** It reads `PLAYBOOK.md`, works through the article with you, and builds the design as an HTML file from this repo's reference.

## Five steps

1. **Start it.** Open a new chat, paste the article link, name this repo.
2. **Hook mine.** The session reads the whole article and pulls eight to ten lines that stand on their own, ranked, each showing the paragraph it came from.
3. **Decide together.** Which lines to use, how many slides, which template, which photographs. It recommends every time, you decide every time.
4. **Build it.** The session writes every slide, places the photographs, writes the caption, runs the checks, then builds the design as an HTML file from `article-carousel.html` and shows it to you.
5. **Make it yours.** The HTML goes through the export lane into Canva as an editable design, words and pictures in place and nothing locked. Change what you like.

Every slide keeps the article's own sentences, so no tile ever carries a line the article never said.

## Contents

| File | What it is |
|---|---|
| `PLAYBOOK.md` | The instructions the Claude session follows. Written for the session to read. |
| `article-carousel.html` | The article carousel's geometry, measured off the team's own export. The session fills its slots. |
| `assets/` | The Yoga Australia lockup the reference loads. |
| `how-it-works.html` | The one-page picture of the five steps above. Download it and open it in a browser. |
| `LANES.md` | Operator notes on pushing files here and importing them into Canva. Staff sessions never need it. |
| `*.pptx` | Template and design files staged for Canva import. |

## Status, 2 September 2026

The Canva-connector ending is retired. A connector can swap words and drop a picture into a frame, and it cannot aim a crop, hold a margin or carry one photograph across a pair of slides, which is what the article carousel is. On 2 September 2026 the State of Yoga article was built through `article-carousel.html` and matched the team's export to within a pixel on every margin, with the swipe continuing the photograph across each pair. The session now builds that HTML itself.

The export lane, HTML to PowerPoint to Canva, is proven from this machine and is described in `LANES.md`. Running it without an operator is the next build.
