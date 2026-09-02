# Carousel playbook

Instructions for a Claude session turning a published Yoga Australia article into a social carousel. The person you are working with supplies the article and makes every call. You mine it, draft the words, run the checks, then build the design in Canva and hand it over finished and editable.

This repo is public. Everything in it is on the open internet. Member data, unpublished drafts, and font files stay out.

## Before you start

You need the **Canva connector** switched on in this account, signed into the Yoga Australia team. Check it early, because step 6 depends on it. Without it you can still do steps 1 to 5. Say so at the start, never at the end.

Ask questions one at a time, in plain text, each carrying your recommendation so a yes is enough. Keep them to the ones that change the build.

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
- **Photographs.** Take them in this order. The article's own photographs lead. The connector cannot fetch a picture from yogaaustralia.org.au (tested 2 September 2026, the fetch fails), so if the article's picture is wanted she drags it from the article page into Canva Uploads, and you place it from there. Then the team's library folders in Canva, `Yoga Images` and `Photos`, which you list and choose from by name and tags. Then anything she names or uploads herself. For each frame recommend one picture and say in a line why it fits the slide, then let her decide. Never invent a photo slot the template lacks.

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

## Step 6. Build it in Canva

Do not hand over a block of text for her to paste. Build the design. This step was run end to end on 2 September 2026, a copy of the article carousel filled with five text slots and four photographs in one pass, every operation returning success, so the route below is proven.

1. **Find the template.** Search Canva designs for the plain name from the table above, `YA article carousel` and so on. The live titles carry a TEST suffix while the set is still being cleared, and the search finds them either way. Confirm you have the right one by its page count.
2. **Copy it.** Duplicate the template into a new design. Never edit the template, which every future carousel starts from.
3. **Rename the copy** to the article and the date, so it is findable later.
4. **Open an editing transaction on the copy** and read what is in it. You get the text elements with their current words and the image frames with their fills, each with its own element id. Those ids belong to this copy alone, so read them out of your own transaction.
5. **Replace the text**, one element at a time, matching your slide text to the element that holds the equivalent placeholder. Slide one carries a short label of about twelve characters and a display heading of three short lines. Body slides carry one paragraph each, and the speaker's name goes at the end of the same paragraph after a blank line.
6. **Place the photographs** into the image frames. A library picture is placed by its asset id, which the folder listing gives you. Leave the logo frames alone, they hold the Yoga Australia mark on every slide. The frame crops the picture to fit, so look at the result and say plainly when a subject is cut badly. Leaving her to find it is the failure.
7. **Commit the transaction.** Nothing is saved until you do.
8. **Read the design back** and confirm every slide carries the words you intended.

Pushing files into this repo, and importing a finished PowerPoint, are operator jobs described in `LANES.md`. A carousel session never needs them.

If the Canva connector is missing, stop here and say so plainly. Give her the words and the caption, tell her the template name, and say the build step needs the connector turned on. Do not pretend the pasting route is the design.

## Step 7. Hand over

Give her these three things in this order, and nothing else.

- The link to the finished design.
- The caption, ready to copy.
- Anything you could not do, named plainly. A photo frame left empty, a heading that had to be trimmed, a crop worth checking.

Every element in that design is live. Text, pictures, colours, nothing flattened and nothing locked. The last pass is hers, so resist specifying sizes, positions or colours. The template already knows them.
