# Carousel playbook

Instructions for a Claude session turning a published Yoga Australia article into a social carousel. The person you are working with supplies the article and makes every call. You mine it, draft the words, run the checks, then build the design as an HTML file from the reference in this repo and hand it over.

This repo is public. Everything in it is on the open internet. Member data, unpublished drafts, and font files stay out.

## Before you start

You need nothing switched on. The build is an HTML file you write from the reference in this repo and show as an artefact, so a plain chat session does the whole job.

Draft first, then ask. Your first reply carries the hook table with a recommended set marked, the slide text for that set, the photograph choices and the caption, then one question at most. She can take the lot with a yes or swap a line. Ask only what changes the build, one question at a time, each carrying your recommendation.

Write short. No preamble before the answer and no summary after it. Australian spelling. No em-dashes and no semicolons. Never open a sentence or a bullet on a number or a counted noun ("Two things to note"), and never build a sentence as a see-saw ("X, not Y", "rather than"). Say the thing once.

## Step 1. Hook mine

Read the article end to end. A hook is a passage that stands alone on a slide and still means what it meant in the article.

A hook is one of these.

- **Title hooks (T).** Fit for the opening slide. Usually the article title, occasionally a shorter phrase that says its core.
- **Content hooks (C).** Body passages with a single idea, claim, or image. Number them C1, C2, ... in order of appearance.
- **Closing hooks (X).** Fit for the last word, the argument's resolution or its most memorable line.

Rate every candidate 1 to 3 on each of three tests.

- **Standalone clarity.** Makes sense with the surrounding paragraphs gone. A hook needing set-up from the previous paragraph fails.
- **Fit.** 10 to 40 words reads well on a slide. Over 60 crowds any layout. Under 10 needs real strength.
- **Faithfulness.** Means on a slide what it meant in the article. A line that was ironic or conditional in context and reads declarative alone is unfaithful.

Note the source paragraph for every hook so each slide traces back to its passage.

**Show ten candidates at most, and never more.** A long article holds hundreds of possible lines and a wall of them is useless. Pick the best ten, mark your recommended set, and say in one line which part of the article you are drawing from and why. If the article is long enough to carry several carousels, say that too and ask which one this is.

Flag any hook whose meaning shifts when lifted. A past-tense habit that reads as a present claim, a fact still in progress that reads as settled, a name the slide would need and does not have.

## Step 2. Shape

Settle each of these, with your recommendation attached.

- **Slide count.** One opening slide, two to four content slides, one close. Fewer strong slides beat more thin ones.
- **Template.** From the table below. The article carousel is the default for an article argument. The story variants suit a single-idea excerpt.
- **Photographs.** The article's own pictures lead, by URL. Then this repo's `photos/` folder once it exists. Then anything she uploads and links. One photograph per pair of slides. For each recommend one picture and say in a line why it fits, then let her decide. Never invent a photo slot the template lacks.

| Template | Use |
|---|---|
| YA article carousel | An article argument over four slides, the default |
| YA article story | One excerpt as a single story |
| YA event carousel / YA event story | Event announcements |
| YA CPD carousel / YA CPD story | CPD offerings |
| YA poll story / YA ask-us-anything story | Engagement prompts |
| YA partnership story set / expanded | Partner announcements |

## Step 3. Words

For each slide, write the final text from its chosen hook.

- **The article's own sentences first.** Lift the passage exactly. Trim only where length demands it, and confirm the claim survives the trim. Paraphrase as a last resort, and record which of the three each slide is.
- **The opening heading is the one line you may write yourself.** Offer three, each smart, polite and a little sassy, and each traceable to a passage she can point to. A heading that promises, diagnoses, or claims something the article never said is out. Body slides keep the article's sentences.
- Common Sanskrit terms in italics with full diacritics, *āsana*, *prāṇāyāma*, *dhyāna*, *samādhi*, *svādhyāya*. Proper nouns roman with diacritics, Krishnamacharya, Śaṅkarācārya.
- Australian spelling. Plain, positive constructions. "program", never "programme".
- Keep each slide inside its room. A heading of 3 to 8 words on the opener, 20 to 40 words on a content slide, 8 to 15 on the close.

## Step 4. Checks

Run all four on the finished slide text. A fix in one re-runs the set.

1. **Voice.** Australian spelling, diacritics correct, sentences plain and confident, no hedge stacks.
2. **Tropes.** No see-saw contrasts, the shape that negates one thing to prop up another. A named speaker's quoted words are theirs and stay as spoken, so the trope check runs on your own lines and on any trim or paraphrase. No abstract tricolons ("Practice. Patience. Presence."). No marketing three-beat of hook, teaching and call to action. No em-dashes, no semicolons, no colons inside a sentence.
3. **Fidelity.** Every slide traces to its named passage. A claim with no passage behind it is fabricated and comes off.
4. **Risk.** No cure promises, no diagnosis, no clinical authority the article never claimed, no lineage put-downs. Check each photograph against its slide text for a bad pairing.

## Step 5. Caption

80 to 150 words. The opening sentence stands on its own, since Instagram truncates early. Name the topic and the author, give one or two sentences of context, close on a line that says something. Leave out slide-by-slide summaries, "swipe" language, and hashtags. Hashtags go in a first comment if wanted.

## Step 6. Build the HTML

Do not hand over a block of text to paste, and do not build through the Canva connector. Build the design as an HTML file from the reference in this repo, look at it, and hand the file over.

1. **Fetch the reference.** `https://raw.githubusercontent.com/yogaaustralia/canva-drop/main/article-carousel.html`. It carries the article carousel's geometry measured off the team's own Canva export, every box in its place, and the comment at its top says what each slot is. The geometry is settled. Fill the slots and change nothing else.
2. **Words into slots.** The title lines into the `.display` heading, one passage into each `.para`. Five slides are laid out; delete the fifth if the deck is four. The chip stays YOGA TODAY and the lockup stays where it is.
3. **Photographs by URL.** The article's own pictures first, by their `wp-content/uploads` address. Then this repo's `photos/` folder once it exists, then a picture she uploads and gives you the link to. One photograph serves each pair of slides: the same `src` and the same `--start` on the wide panel and the narrow strip that follows it, and the strip then shows exactly what lies to the right of the panel, so the swipe continues the picture. The seam falls 473 px into the picture. Choose `--start` so the seam cuts through floor, wall or mat and never through a face or a hand. For a portrait photograph `--start` runs from 0 to about 168.
4. **Orphans.** One word alone on the last line of a paragraph is a defect. Hold the last two or three words together with `&nbsp;` and look again. Never trim the article's words to make a line fit.
5. **Look at it.** Render the file as an artefact with `class="guides"` on `<body>` and read every slide at full size: the seam on each pair, every face whole, every paragraph inside its dashed box with a line of room to spare, the title inside its box, nothing touching an edge. Fix, look again, then remove the guides class. In a browser without Larken the fallback serif wraps a word or two differently from Canva, which is why the paragraph keeps a line of room.

## Step 7. Hand over

Give her these three things in this order, and nothing else.

- The HTML file, complete, as a downloadable artefact named for the article and the date.
- The caption, ready to copy.
- Anything you could not do, named plainly. A seam you could not clear, a passage that runs long, a photograph you could not reach.

The HTML is the design. It becomes an editable Canva design through the export lane in `LANES.md`: the file is converted to a PowerPoint at the same coordinates and imported into Canva from this repo, and every element arrives live. Until that lane runs on its own, the operator runs it. Say so in the hand-over and never say the design has reached Canva when it has not.
