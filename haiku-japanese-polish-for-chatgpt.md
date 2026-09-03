
# Haiku Japanese Polish (Kawagita method)

This skill captures how 川北泰徳 (Yoshinori Kawagita, as he romanises it) edits Rob's haiku — first the sequence *The Ocean Beneath the Ice* (15 haiku), then a set of five single haiku (July 2026). His edits are consistent enough to be a method. Apply it to any new haiku Rob brings.

His own definition of 添削: 言葉を換えたり、書き加えたり、削ったりして俳句の表現を変えて、よりよい俳句にすること — swap words, add, cut, to make a better haiku. All three moves are fair game.

The mora-counting rules and both full sets of Kawagita-san's before/after examples are appended below.

## Core principles (in priority order)

1. **5-7-5 is non-negotiable.** Every rewrite he produced is 5-7-5 (五・七・五の定型のリズムに整えましょう). Fix the count first. A 6-8-5 draft gets fully rebuilt, not trimmed.

1b. **Kigo: at most one, never two.** He translated the Ocean sequence "regardless of whether it includes a season word", so a kigo is not required. But when kigo appear, he insists on exactly one (季語を一つだけにしましょう). Watch for hidden pairs: 咳 and くしゃみ are both winter kigo; 花, 春の風 and 山笑う are all spring. Name the season of each kigo you keep. When a draft is short, adding a kigo is his preferred way to fill the missing 5 (梅雨晴れ間).

2. **Count mora, not syllables.** ん, っ, and ー each count as one. Small ゃゅょ do not. ガソリンスタンド = 8, ガススタンド = 6. Write the count under every segment, every time, so errors are visible. See `references/mora_counting.md`.

3. **Compact native / Sino-Japanese words beat katakana loanwords.** ガソリンスタンドに (9) → ガススタンドに (7) → 給油所に (5). The kango version is both shorter and more haiku-like. Look for the 漢語 equivalent of any loanword.

4. **Use literary (文語) verb and adjective forms.** This is the single biggest "sounds like a real haiku" lever. Kawagita's swaps:
   - 凍りし → 凍てて　｜　落ちる → 落つ　｜　越えゆく → 越ゆる
   - 押さえられない → 押さえきれざる　｜　輝く → 輝けり
   - 見る → 眺む / 仰ぐ　｜　ひらく → ひらけゆく / ひらきけり
   - 開き始める → 開き初む（そむ）　｜　青い → 青き
   Use them naturally; don't stack archaic forms until it reads as pastiche.

5. **End with a cut (切れ) where possible.** Favourite closers from the edits: 〜けり (ひらきけり, 輝けり), 〜かな (くしゃみかな), 〜む (眺む, 初む), 〜つ (落つ), and the opening や (白面や, 侘び文や). けり adds a sense of realisation; や opens with an exclamation.

6. **Turn explanation into image; turn abstraction into first-person feeling.** "The mind tries to hold the heart down" → not 頭で押さえ (head/brain, clinical) but 心では押さえきれざるわが想い — "my feelings, which my heart cannot hold down." Drop the mechanism, keep the feeling. Likewise 言葉になる前 (before becoming words — prose) → 言葉とならず (never becoming words — poetry).

7. **Reach for poetic synonyms.** 言葉 → 言の葉（ことのは）, 海 → 海原（うなばら）, 空 → 大空, 句 → 詩の言の葉. These lift register and often fix the count at the same time.

8. **Reorder freely.** Japanese lets you move the nature image to the front: 心より湧き 山越ゆる 愛の水 → 愛の水 心より湧き 山を越え. Offer both; reordering is often how a 7-5-5 becomes a clean 5-7-5.

9. **Enjambment (句跨がり) is allowed but must be labelled.** If the natural phrase boundaries land on 7-5-5, keep it as a variant, mark it `※ 句跨がり (enjambed line)`, and also give a re-cut 5-7-5 version (心より湧き / 山越ゆる → 心より / 湧き山越ゆる).

10. **Don't over-edit.** When the draft already works, say so: `(It's fine as it is.)` and stop. Four of fifteen were left untouched. Restraint is part of the method.

11. **Offer 2-3 alternatives, not one answer.** Each with a one-line gloss when the nuance differs (眺む = gaze at; 仰ぐ = look up at). Rob chooses.

12. **Complete fragments with a thing, not a thought.** A 5-7 draft gets its final 5 from a concrete object or a kigo: 旅立つ荷, 梅雨晴れ間, 旅をして. Never pad with an abstract noun.

13. **Flag private references.** 杖の花 meant 御杖村 to Rob; to a Japanese reader it meant nothing (意味がよくわかりません). If an image only works with biographical context, say so and offer a replacement that stands alone. Rob can decide to keep the private version for himself.

14. **Check particles.** 荷を添う → 荷に添いて. A wrong particle marks a poem as non-native faster than anything else.

15. **Vary the angle across alternatives.** For the cat/koto haiku he gave three rewrites with three different stances: detached scene ending in かな, onomatopoeia (くしゅんと), and first-person domestic humour (夫のしわぶき気にせずに). Alternatives should differ in viewpoint or tone, not just word choice.

16. **Back-translate when meaning shifted.** If the polished Japanese says something the English didn't (花園に → 心の花園 "garden of my heart"), add one English line under it so Rob sees what changed.

## Workflow

1. Read the source haiku (English/Dutch/Japanese). Identify the core image, the turn/cut, and any implied season.
2. Draft a literal Japanese version first — this is the "before" line, useful for showing the path.
3. Count every segment. Mark counts under each block: `5　7　5`.
4. Check kigo count (1b), particles (14), and private references (13).
5. Apply principles 3–8 to reach 5-7-5 and literary register. Produce 2-3 candidates with different angles (15).
6. Label enjambed variants; gloss verb choices; back-translate any meaning shift.
7. If the draft already satisfies everything, write `(It's fine as it is.)` and offer at most one optional alternative.
8. Add furigana to every kanji using Rob's format: `漢字《よみ》` (e.g. 白面《はくめん》や). Readings go after the kanji compound, not per character.

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

## Things to watch

- ー in katakana counts; many English-derived words are longer in mora than they look.
- 「家」 added to a surname (松岡家) makes it unambiguous that a family is meant and adds a mora.
- Kawagita keeps particles minimal in the 5s: 山眺む not 山を眺む. Drop を/は when the count demands it and the meaning survives.
- Keep Rob's multilingual intent: if the haiku exists in English and Dutch too, polish only the Japanese here; flag if the Japanese now diverges from the other two.
- For a sequence, keep recurring images consistent across poems (愛の水 / 愛の波 / 愛の海原 all echo each other on purpose).


---

# Mora counting for haiku (音数)

Haiku count **mora (拍)**, not syllables.

| Counts as 1 | Does NOT count |
|---|---|
| every kana (あ, か, ガ …) | small ゃ ゅ ょ (きょ = 1) |
| ん | — |
| っ (sokuon) | — |
| ー (long vowel mark) | — |
| each kana of a long vowel written out (おお, こう = 2) | — |

## Worked counts

| Word | Kana | Mora |
|---|---|---|
| ガソリンスタンド | がそりんすたんど | 8 |
| ガススタンド | がすすたんど | 6 |
| 給油所に | きゅうゆしょに | 5 (きゅ・う・ゆ・しょ・に) |
| 白面や | はくめんや | 5 |
| 海原 | うなばら | 4 |
| 言の葉は | ことのはは | 5 |
| 松岡家 | まつおかけ | 5 |
| 大空へ | おおぞらへ | 5 |
| 輝けり | かがやけり | 5 |
| 押さえきれざる | おさえきれざる | 7 |

Tip: convert to hiragana, strip small ゃゅょ, then count characters.

## Common traps
- Katakana loanwords almost always run long (コンピュータ = 6, スマートフォン = 7).
- 長音 in kanji readings: 東京 = とうきょう = 4, not 2.
- Classical endings change counts: 見る (2) → 眺む (3) → 仰ぐ (3); 輝く (4) → 輝けり (5); 落ちる (3) → 落つ (2).
- The suffix ちゃん (-chan, e.g. さくらちゃん, おばあちゃん) is pronounced/counted as **one mora**, not two — an explicit exception noted by Kawagita-san (source: 夏水仙の彼方 corrections, poems 1 and 2).


---

# Worked examples: Kawagita-san's edits to "The Ocean Beneath the Ice"

Use these as the model to imitate. "↓" marks his edit; numbers under segments are mora counts; "(It's fine as it is.)" means he left the draft alone.

# Japanese translation of 'The Ocean Beneath the Ice'

by Yoshinori Kawagita

I translated it into Japanese to fit the 5-7-5 syllable rhythm.
I edited it regardless of whether it includes a season word.

*(Furigana readings are shown in 《 》 after the kanji.)*

---

## 1. White mask- at the gas station the ice begins to melt.

白面《はくめん》や　ガソリンスタンドに　氷《こおり》解《と》く

↓

白面《はくめん》や　ガススタンドに　氷《こおり》解《と》く
　5　　　　　　　　7　　　　　　　　5

白面《はくめん》や　氷《こおり》解《と》け初《そ》む　給油所《きゅうゆしょ》に
　5　　　　　　　　7　　　　　　　　　　5

## 2. Frozen in time, the ocean of love opens.

時《とき》に凍《こお》りし　愛《あい》の海《うみ》ひらく

↓

時《とき》凍《い》てて　愛《あい》の海原《うなばら》　ひらけゆく
　5　　　　　　　　7　　　　　　　　　5

時《とき》凍《い》てて　愛《あい》の海原《うなばら》　ひらきけり
　5　　　　　　　　7　　　　　　　　　5

## 3. Water erupts upward- too powerful for the heart to contain.

噴《ふ》き上《あ》がる　水《みず》は心《こころ》に　強《つよ》すぎて　(It's fine as it is.)

↓

噴《ふ》き上《あ》がる　水《みず》は心《こころ》に　満《み》ち溢《あふ》れ
　5　　　　　　　　7　　　　　　　　　5

---

## 4. The mind tries to hold the heart down, yet still it overflows.

心《こころ》を　頭《あたま》で押《お》さえ　なお溢《あふ》れ

↓

心《こころ》では　押《お》さえられない　わが想《おも》い
　5　　　　　　　7　　　　　　　　　5

心《こころ》では　押《お》さえきれざる　わが想《おも》い
　5　　　　　　　7　　　　　　　　　5

## 5. Blue drops, before becoming words, fall back into the sea.

青《あお》き雫《しずく》　言葉《ことば》になる前《まえ》　海《うみ》へ落《お》つ

↓

青《あお》き雫《しずく》　言葉《ことば》とならず　海《うみ》へ落《お》つ
　5　　　　　　　　　7　　　　　　　　　5

## 6. Poems that cannot be caught become waves.

捕《つか》まえられぬ　句《く》は波《なみ》となり

↓

詠《よ》みきれぬ　詩《し》の言《こと》の葉《は》は　波《なみ》となり　　※ 言《こと》の葉《は》 ＝ 言葉《ことば》 (word)
　5　　　　　　　7　　　　　　　　　　　5

## 7. Flowing from the heart, the waters of love cross the mountains.

心《こころ》より出《い》で　山《やま》を越《こ》えゆく　愛《あい》の水《みず》

↓

心《こころ》より湧《わ》き　山越《やまこ》ゆる　愛《あい》の水《みず》　　※ 句跨《くまた》がり (enjambed line)
　7　　　　　　　　　　5　　　　　　　　5

↓

心《こころ》より　湧《わ》き　山越《やまこ》ゆる　愛《あい》の水《みず》
　5　　　　　　　　　　7　　　　　　　　　5

愛《あい》の水《みず》　心《こころ》より湧《わ》き　山《やま》を越《こ》え
　5　　　　　　　　7　　　　　　　　　　5

---

## 8. At Matsuoka, three generations of flowers dance upon the wind.

松岡《まつおか》の　三代《さんだい》の花《はな》　風《かぜ》に舞《ま》う　(It's fine as it is.)

↓

松岡家《まつおかけ》　三代《さんだい》の花《はな》　風《かぜ》に舞《ま》う
　5　　　　　　　　　7　　　　　　　　　　5

## 9. A mother's smile, a daughter's eyes, a granddaughter's spring.

母《はは》の笑《え》み　娘《むすめ》の瞳《ひとみ》　孫《まご》の春《はる》　(It's fine as it is.)

## 10. And even among the men, flowers begin to open.

男《おとこ》たちにも　花《はな》ひらきゆく

↓

男《おとこ》らの　ためにも花《はな》は　ひらきゆく
　5　　　　　　　7　　　　　　　　　5

花開《はなひら》き初《そ》む　男《おとこ》らの　心《こころ》にも　　※ 句跨《くまた》がり (enjambed line)
　7　　　　　　　　　　　5　　　　　　　5

↓

花開《はなひら》き　初《そ》む　男《おとこ》らの　心《こころ》にも
　5　　　　　　　　　　7　　　　　　　　　5

## 11. Before we know it, the place of filling tanks has become a garden.

いつしか　給油《きゅうゆ》の場所《ばしょ》　花園《はなぞの》に

↓

知《し》らぬ間《ま》に　感謝《かんしゃ》に満《み》ちる　花園《はなぞの》に
　5　　　　　　　　　7　　　　　　　　　　5

給油所《きゅうゆしょ》は　いつしか心《こころ》の　花園《はなぞの》に
　5　　　　　　　　　　7　　　　　　　　　5

Before I know it, the gas station had turned into a garden of my heart.

---

## 12. Blue light rises between the flowers toward the sky.

青《あお》き光《ひかり》　花《はな》の間《あいだ》より　空《そら》へ昇《のぼ》る

↓

花《はな》の間《ま》を　青《あお》き光《ひかり》は　大空《おおぞら》へ
　5　　　　　　　　7　　　　　　　　　5

## 13. The mountain peaks, receiving the waves of love, shine once again.

山《やま》の峰《みね》　愛《あい》の波受《なみう》け　また輝《かがや》く

↓

山《やま》の峰《みね》　愛《あい》の波受《なみう》け　また光《ひか》る
　5　　　　　　　　7　　　　　　　　　　5

愛《あい》の波《なみ》　受《う》けまた光《ひか》る　山《やま》の峰《みね》　　※ 句跨《くまた》がり (enjambed line)
　5　　　　　　　　7　　　　　　　　　　5

愛《あい》の波《なみ》　受《う》け輝《かがや》けり　山《やま》の峰《みね》　　※ 句跨《くまた》がり (enjambed line)
　5　　　　　　　　7　　　　　　　　　　5

## 14. Without a word, only a smile, looking toward the mountain.

言葉《ことば》なく　ただ微笑《ほほえ》みて　山《やま》を見《み》る　(It's fine as it is.)

↓

言葉《ことば》なく　ただ微笑《ほほえ》みて　山眺《やまなが》む　　※ 眺《なが》む (「look at」 or 「gaze at」)
　5　　　　　　　　7　　　　　　　　　5

言葉《ことば》なく　ただ微笑《ほほえ》みて　山仰《やまあお》ぐ　　※ 仰《あお》ぐ (「look up」 or 「gaze up」)
　5　　　　　　　　7　　　　　　　　　5

## 15. Mountain and smile become one beneath the summer sky.

山《やま》と笑《え》み　ひとつになりて　夏《なつ》の空《そら》　(It's fine as it is.)

↓

睦《むつ》み合《あ》い　山《やま》と夏空《なつぞら》　笑《え》み交《か》わす

The mountains and the summer sky
　　share a gentle smile, in sweet harmony.

---

# Worked examples, set 2: 「ローブの俳句を添削しよう。」 川北泰徳　2026年7月1日

His definition of 添削（てんさく）: 言葉を換えたり、書き加えたり、削ったりして俳句の表現を変えて、よりよい俳句にすること。

## ①
しつこい咳《せき》　七匹《ななひき》のくしゃみ　琴《こと》つづく

→ 琴《こと》の音《ね》に混《ま》じりて猫《ねこ》のくしゃみかな
→ 琴《こと》の音《ね》やくしゅんと猫《ねこ》がくしゃみして
→ 琴《こと》奏《かな》づ夫《おっと》のしわぶき気《き》にせずに

「咳」「くしゃみ」は咳のことです。季語を一つ使っているので、一つだけにしましょう。五・七・五の定型のリズムに整えましょう。

*(Lesson: 咳 and くしゃみ are both winter kigo — 季重なり. Keep one. Draft was 6-8-5; all three rewrites are 5-7-5 and each takes a different angle: objective scene with かな, onomatopoeia, or first-person humour about the husband.)*

## ②
侘《わ》び文《ぶみ》や墨《すみ》の温《ぬく》みや

→ 侘《わ》び文《ぶみ》や墨《すみ》の温《ぬく》みや梅雨晴《つゆば》れ間《ま》

*(Lesson: the draft was only 5-7. He completed it by adding a kigo as the closing 5.)*

## ③
花《はな》の道《みち》　遠《とお》き世界《せかい》へ

→ 花《はな》の道《みち》遠《とお》き世界《せかい》へ旅立《たびだ》つ荷《に》

*(Lesson: again 5-7 only; completed with a concrete object, 荷, not an abstraction.)*

## ④
荷《に》を添《そ》う心《こころ》もともに

→ 荷《に》に添《そ》いて心《こころ》もともに旅《たび》をして

*(Lesson: particle correction 荷を添う → 荷に添いて; then completed to 5-7-5.)*

## ⑤
杖《つえ》の花《はな》　また山笑《やまわら》う

→ 微風《そよかぜ》と花《はな》を友《とも》とし山笑《やまわら》う

杖の花の意味がよくわかりません。「山笑う」（春の季語）「春の風」（春の季語）季語を三つ使っているので、一つだけにしましょう。

*(Lesson: 杖 was Rob's private reference to 御杖村 — unreadable to an outside reader, so he replaced it. He also flagged three spring kigo stacked in one poem.)*
