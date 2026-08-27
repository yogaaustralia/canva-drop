# Carousel playbook

> **Under revision, 25 August 2026.** Step 6 below is wrong and is being replaced.
> It ends by handing over a block of text to paste into Canva by hand, which is the
> manual work this pipeline exists to remove. The correct ending is the session
> building the design and landing it in Canva already populated and editable, as
> `README.md` and `how-it-works.html` describe. Steps 1 to 5 stand.

Instructions for a Claude session helping a Yoga Australia staff member turn a published article into a social carousel. The staff member supplies the article and makes the calls. You mine it, draft the words, and hand over a build sheet she pastes into Canva. Canva does the visual finish, so you never produce images or mock-ups.

This repo is public. Everything in it, and everything pushed to it, is on the open internet. Member data, unpublished drafts, and font files stay out.

## Inputs

- The article, as a link to yogaaustralia.org.au or pasted text.
- Her decisions along the way, which hooks, how many slides, which template.

Ask questions one at a time, in plain text, each with a recommendation so she can say yes or pick differently. Keep the questions to the ones that change the build.

## Step 1. Hook mine

Read the article end to end. A hook is a passage that stands alone on a slide and still means what it meant in the article.

Three kinds.

- **Title hooks (T).** Phrases fit for the opening slide. Usually the article title, occasionally a shorter phrase that says its core.
- **Content hooks (C).** Body passages each with a single idea, claim, or image. Number them C1, C2, ... in order of appearance.
- **Closing hooks (X).** Passages fit for the last word, the argument's resolution or its most memorable line.

Rate every candidate 1 to 3 on each of three tests.

- **Standalone clarity.** Makes sense with the surrounding paragraphs gone. A hook needing set-up from the previous paragraph fails.
- **Fit.** 10 to 40 words reads well on a slide. Over 60 crowds any layout. Under 10 needs real strength.
- **Faithfulness.** Means on a slide what it meant in the article. A line that was ironic or conditional in context and reads declarative alone is unfaithful.

Note the source paragraph for every hook so each slide traces back to its passage.

Mine roughly double what the carousel will use. A five-slide carousel wants eight to ten candidates, one T, several C, one or two X. Show her the full list with your recommended set marked, and let her choose.

## Step 2. Shape

Settle three things with her, each with a recommendation.

- **Slide count.** One opening slide, two to four content slides, one close. Fewer strong slides beat more thin ones.
- **Template.** The Canva templates below. She finds them by name in Canva's search. For an article the default is the article carousel. The story variants suit a single-idea excerpt.
- **Images.** For each slide with a photo frame, write one line naming subject, mood, and crop, for example "teacher working hands-on with a student, warm interior light, portrait crop". She picks the actual photographs from the team's Canva library. Never invent a photo requirement the template lacks.

Templates in the team's Canva account.

| Template | Use |
|---|---|
| YA article carousel | An article argument over 4+ slides, the default |
| YA article story | One excerpt as a single story |
| YA event carousel / YA event story | Event announcements |
| YA CPD carousel / YA CPD story | CPD offerings |
| YA poll story / YA ask-us-anything story | Engagement prompts |
| YA partnership story set / expanded | Partner announcements |

## Step 3. Words

For each slide, write the final text from its chosen hook.

- **Verbatim first.** Lift the passage exactly. Trim only where length demands it, and confirm the claim survives the trim. Paraphrase as a last resort, and record which of the three each slide is.
- Common Sanskrit terms in italics with full diacritics, *āsana*, *prāṇāyāma*, *dhyāna*, *samādhi*, *svādhyāya*. Proper nouns roman with diacritics, Krishnamacharya, Śaṅkarācārya.
- Australian spelling. Plain, positive constructions.
- Keep each slide inside its room. A heading of 3 to 8 words on the opener, 20 to 40 words on a content slide, 8 to 15 on the close.

## Step 4. Checks

Run all four on the finished slide text. A fix in one re-runs the set.

1. **Voice.** Australian spelling, diacritics correct, sentences plain and confident, no hedge stacks.
2. **Tropes.** No see-saw contrasts, the shape that negates one thing to prop up another. No abstract tricolons ("Practice. Patience. Presence."). No marketing three-beat (hook, teaching, call to action). No em-dashes.
3. **Fidelity.** Every slide traces to its named passage. A claim with no passage behind it is fabricated and comes off.
4. **Risk.** No cure promises, no diagnosis, no clinical authority the article never claimed, no lineage put-downs. Check each image note against its slide text for a bad pairing.

## Step 5. Caption

80 to 150 words. The opening sentence stands on its own, since Instagram truncates early. Name the topic and the author, give one or two sentences of context, close on a line that says something. Leave out slide-by-slide summaries, "swipe" language, and hashtags. Hashtags go in a first comment if wanted.

## Step 6. Build sheet

Hand over one block she works from directly.

```
Template:  YA article carousel  (search this name in Canva)
Slide 1:   <exact text>
           image: <one-line note>
Slide 2:   <exact text>
...
Caption:   <caption text>
```

She duplicates the template in Canva, pastes each slide's text, drops in the photographs, and adjusts by eye. That finishing pass is hers, so resist the urge to specify sizes, positions, or colours. The template already knows.
