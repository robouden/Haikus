---
name: haiku-japanese-polish
description: Translate or polish haiku into natural 5-7-5 Japanese the way a Japanese haiku editor would — strict mora counting, literary (bungo) verb forms, kireji, compact native vocabulary instead of katakana loanwords, and 2-3 alternative renderings with furigana and per-segment counts. Use this whenever Rob shares a haiku (English, Dutch, or Japanese draft) and wants a Japanese version, asks to "check the 5-7-5", "make it sound more Japanese", "polish", "fix the rhythm", or wants to review a Japanese haiku before stamping/publishing — even if he doesn't say "translate". Also use for Japanese haiku sequences (連作) like "The Ocean Beneath the Ice".
---

# Haiku Japanese Polish (Kawagita method)

This skill captures how Yoshinori Kawagita edited Rob's sequence *The Ocean Beneath the Ice* (15 haiku, Aug 2026). His edits are consistent enough to be a method. Apply it to any new haiku Rob brings.

Read `references/kawagita_examples.md` for the full before/after set when you need a model to imitate. Read `references/mora_counting.md` if a count is in doubt.

## Core principles (in priority order)

1. **5-7-5 is non-negotiable; kigo is optional.** Kawagita's own preface: he edited "to fit the 5-7-5 syllable rhythm … regardless of whether it includes a season word." So fix the count first. A season word is a bonus — point it out when one appears (夏の空), never force one in.

2. **Count mora, not syllables.** ん, っ, and ー each count as one. Small ゃゅょ do not. ガソリンスタンド = 8, ガススタンド = 6. Write the count under every segment, every time, so errors are visible. See `references/mora_counting.md`.

3. **Compact native / Sino-Japanese words beat katakana loanwords.** ガソリンスタンドに (9) → ガススタンドに (7) → 給油所に (5). The kango version is both shorter and more haiku-like. Look for the 漢語 equivalent of any loanword.

4. **Use literary (文語) verb and adjective forms.** This is the single biggest "sounds like a real haiku" lever. Kawagita's swaps:
   - 凍りし → 凍てて　｜　落ちる → 落つ　｜　越えゆく → 越ゆる
   - 押さえられない → 押さえきれざる　｜　輝く → 輝けり
   - 見る → 眺む / 仰ぐ　｜　ひらく → ひらけゆく / ひらきけり
   - 開き始める → 開き初む（そむ）　｜　青い → 青き
   Use them naturally; don't stack archaic forms until it reads as pastiche.

5. **End with a cut (切れ) where possible.** Favourite closers from the edit: 〜けり (ひらきけり, 輝けり), 〜む (眺む, 初む), 〜つ (落つ), and the opening や (白面や). けり adds a sense of realisation; や opens with an exclamation.

6. **Turn explanation into image; turn abstraction into first-person feeling.** "The mind tries to hold the heart down" → not 頭で押さえ (head/brain, clinical) but 心では押さえきれざるわが想い — "my feelings, which my heart cannot hold down." Drop the mechanism, keep the feeling. Likewise 言葉になる前 (before becoming words — prose) → 言葉とならず (never becoming words — poetry).

7. **Reach for poetic synonyms.** 言葉 → 言の葉（ことのは）, 海 → 海原（うなばら）, 空 → 大空, 句 → 詩の言の葉. These lift register and often fix the count at the same time.

8. **Reorder freely.** Japanese lets you move the nature image to the front: 心より湧き 山越ゆる 愛の水 → 愛の水 心より湧き 山を越え. Offer both; reordering is often how a 7-5-5 becomes a clean 5-7-5.

9. **Enjambment (句跨がり) is allowed but must be labelled.** If the natural phrase boundaries land on 7-5-5, keep it as a variant, mark it `※ 句跨がり (enjambed line)`, and also give a re-cut 5-7-5 version (心より湧き / 山越ゆる → 心より / 湧き山越ゆる).

10. **Don't over-edit.** When the draft already works, say so: `(It's fine as it is.)` and stop. Four of fifteen were left untouched. Restraint is part of the method.

11. **Offer 2-3 alternatives, not one answer.** Each with a one-line gloss when the nuance differs (眺む = gaze at; 仰ぐ = look up at). Rob chooses.

12. **Back-translate when meaning shifted.** If the polished Japanese says something the English didn't (花園に → 心の花園 "garden of my heart"), add one English line under it so Rob sees what changed.

## Workflow

1. Read the source haiku (English/Dutch/Japanese). Identify the core image, the turn/cut, and any implied season.
2. Draft a literal Japanese version first — this is the "before" line, useful for showing the path.
3. Count every segment. Mark counts under each block: `5　7　5`.
4. Apply principles 3–8 to reach 5-7-5 and literary register. Produce 2-3 candidates.
5. Label enjambed variants; gloss verb choices; back-translate any meaning shift.
6. If the draft already satisfies everything, write `(It's fine as it is.)` and offer at most one optional alternative.
7. Add furigana to every kanji using Rob's format: `漢字《よみ》` (e.g. 白面《はくめん》や). Readings go after the kanji compound, not per character.

## Output format

ALWAYS use this layout (it mirrors the Kawagita manuscript):

```
## N. [Source haiku in English/Dutch]

[literal Japanese draft with furigana]

↓

[candidate 1 with furigana]　　※ note if any
　5　　　7　　　5

[candidate 2 with furigana]　　※ 句跨がり (enjambed line) / gloss
　5　　　7　　　5

[optional back-translation in English]
```

Use full-width spaces (　) between the three segments. Put `(It's fine as it is.)` at the end of the draft line when no change is needed.

## New rules found (from *Rob's poem* and *百年の灯* tanka corrections, Sept 2026)

13. **Tanka mode.** When the source has 5 images/beats instead of 3, Kawagita casts it as a 短歌《たんか》 (5-7-5-7-7, 31 mora) rather than forcing haiku. Same mora-counting and literary-form rules apply, just two more segments.

14. **He coins words when nothing existing fits.** 森霊《しんれい》 ("forest spirit / heart of the forest") is marked explicitly `coined word` — invented Sino-Japanese compound, not in any dictionary, built from the poem's recurring image. Do this sparingly and flag it as coined.

15. **He'll depart from the literal source when the poem demands it**, more freely than principle 6 implies: "I took the liberty of editing Rob's original text quite freely." Prioritize the tanka/haiku working as a poem over tracking the English 1:1.

16. **Standard humility preface**: "My corrections aren't perfect, so please just use them as a reference." Include a line like this when presenting corrections, matching his tone.

## Things to watch

- ー in katakana counts; many English-derived words are longer in mora than they look.
- 「家」 added to a surname (松岡家) makes it unambiguous that a family is meant and adds a mora.
- Kawagita keeps particles minimal in the 5s: 山眺む not 山を眺む. Drop を/は when the count demands it and the meaning survives.
- Keep Rob's multilingual intent: if the haiku exists in English and Dutch too, polish only the Japanese here; flag if the Japanese now diverges from the other two.
- For a sequence, keep recurring images consistent across poems (愛の水 / 愛の波 / 愛の海原 all echo each other on purpose).
