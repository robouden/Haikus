# Rob's Haikus

Working folder for Rob's haiku, tanka and renku: drafts, Japanese polish by 川北泰徳 (Yoshinori Kawagita), and print-ready output (Word/PDF with furigana and hanko).

## Flow

Full diagrams (EN/JA): [Haiku_Creation_Process.md](Haiku_Creation_Process.md) (PDFs: `Haiku_Creation_Process_A4.pdf`).

1. **Capture the feeling**: express it in EN/NL/JA, choose the form (haiku 5-7-5, tanka 5-7-5-7-7, renku 8-8-8-8, or free short-long-short).
2. **English draft with AI**: AI proposes, Rob selects/corrects until close enough.
3. **Japanese refinement loop**: AI gives a Japanese draft plus what a Japanese reader would experience; Rob corrects the meaning; repeat until the feeling is right. Copy text with furigana.
4. **Final production**: paste into the furigana HTML styler, screenshot, place in a Word doc with English text and hanko, save as `.docx`/`.pdf`, print.

## Japanese polish rules (Kawagita method)

Implemented as the Claude skill [haiku-japanese-polish.skill](haiku-japanese-polish.skill) (source: [SKILL.md](SKILL.md), JA: [SKILL.ja.md](SKILL.ja.md)). ChatGPT versions: `haiku-japanese-polish-for-chatgpt*.md`.

Key rules:

- Strict **5-7-5 by mora** (ん, っ, ー count; small ゃゅょ don't). Show the count under each segment.
- **One kigo at most**, never two; name its season.
- Prefer compact native/kango words over katakana loanwords.
- Use literary (文語) verb forms (凍てて, 落つ, 輝けり), end with a cut (けり / かな / や).
- Turn explanation into image; check particles; flag private references.
- Don't over-edit; offer 2-3 alternatives with different angles.
- Furigana format: `漢字《よみ》`.
- Disclose any omissions made to fit the meter.

Background on his editing style: [🔎 The Work Style of Yasunori Kawakita.md](<🔎 The Work Style of Yasunori Kawakita.md>) (JA version alongside).

## Tools

- Furigana converters: [Vertical](<Vertical Japanese Furigana Converter.html>), [Horizontal](<Horizontal Japanese Furigana Converter.html>) (see below).
- [Japanese-Poetry-Template/](Japanese-Poetry-Template/): haiku / renku / anthology templates and `poetry.css`.
- Artwork: `.kra` (Krita) files, hanko PNGs/JPEGs (`*hanko*.png`, `rob hanko*.png`).

## Furigana converter (browser)

No install or server: double-click the `.html` file (or open it in Firefox/Chrome via File > Open).

1. Pick a version (each has a normal and a Bold file):
   - **Vertical** (tategaki, top-to-bottom, traditional haiku look): [Vertical](<Vertical Japanese Furigana Converter.html>) / [Bold](<Vertical Japanese Furigana Converter Bold.html>)
   - **Horizontal** (left-to-right, easier to read on screen): [Horizontal](<Horizontal Japanese Furigana Converter.html>) / [Bold](<Horizontal Japanese Furigana Converter Bold.html>)
2. In the left box, replace the sample text with the poem. Write readings as `漢字《よみ》`, one line per poem line, a blank line between verses.
3. The right box updates live as you type.
4. For multi-kanji words the reading is split evenly across the characters. To control the split, use pipes: `金星《きん|せい》`. `{金星|きんせい}` also works.
5. Screenshot the output panel (e.g. Flameshot or Shift+PrtSc), then paste the image into the Word doc and add the English text and hanko.

Needs a Japanese font (Noto Serif JP / Yu Mincho / Hiragino Mincho); a fallback serif is used otherwise.

## Printing (Brother QL-700 label printer)

Two CUPS queues on the same device:

- `QL700`: ptouch-ql driver, variable length, but kanji/furigana render jaggy.
- `QL700-HQ`: original Brother driver, sharp text. Use this for haiku labels.

Register a variable-length continuous format (prints at actual length, up to the max):

```
sudo brpapertoollpr_ql700 -P QL700-HQ -n 62x240-continuous -w 62 -h 240
lpoptions -p QL700-HQ -o PageSize=<generated BrL name>
```

Remove a format: `sudo brpapertoollpr_ql700 -P QL700-HQ -d <format-name>`. Don't hand-edit PPDs or `paperinfql700` (causes a red LED or wrong length).

## Layout

| Pattern | Contents |
|---|---|
| `<Title>.docx` / `.pdf` | Finished haiku, one per file (some with `print` or `final` variants) |
| `Kawagita Yoshinori - *.md`, `*corrected*.md`, `*tanka corrections.md` | Transcripts and corrections from Kawagita-san |
| `Haiku_Creation_Process*` | Process flow diagrams |
| `*.skill`, `SKILL*.md` | Claude skill for the Japanese polish |
| `Pictures/`, `*.jpg`, `*.png` | Source photos, hanko, artwork |

## Git

Remotes: `origin` (GitHub, robouden/Haikus) and `codeberg`. Work directly on `main`.
