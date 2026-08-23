# How I Create a Haiku – Process Flow

A4 landscape friendly diagrams.  
Loops are shown with return arrows inside each phase.

---

## English Version

```mermaid
flowchart LR
    subgraph P1["1. Capture the Feeling"]
        direction TB
        A["Feeling arises"] --> B["Translate into<br/>EN / NL / JA"]
        B --> C{"Expressed<br/>correctly?"}
        C -->|No| B
        C -->|Yes| D["Choose form:<br/>Haiku / Renku / Tanka<br/>5-7-5 · 5-7-5-7-7 · 8-8-8-8<br/>or free short-long-short"]
    end

    subgraph P2["2. English Draft with AI"]
        direction TB
        E["AI writes English<br/>sentences"] --> F["I select / correct / change"]
        F --> G{"Close enough?"}
        G -->|No| E
        G -->|Yes| H["Request Japanese draft"]
    end

    subgraph P3["3. Japanese Refinement Loop"]
        direction TB
        I["AI explains meaning<br/>+ Japanese reader experience"] --> J["I correct the meaning"]
        J --> K["AI revises Japanese"]
        K --> L{"Feeling correct<br/>in Japanese?"}
        L -->|No| I
        L -->|Yes| M["Copy text + furigana"]
    end

    subgraph P4["4. Final Production"]
        direction TB
        N["Paste into custom HTML<br/>furigana styler"] --> O["Screenshot result"]
        O --> P["Paste into Word doc"]
        P --> Q["Add English text<br/>+ hanko"]
        Q --> R["Save or print"]
    end

    P1 --> P2
    P2 --> P3
    P3 --> P4

    style P1 fill:#e8f4f8,stroke:#2a7a9b,stroke-width:1.5px
    style P2 fill:#eef8e8,stroke:#3a8a4a,stroke-width:1.5px
    style P3 fill:#f8f0e8,stroke:#9b6a2a,stroke-width:1.5px
    style P4 fill:#f5e8f8,stroke:#7a3a9b,stroke-width:1.5px
```

---

## 日本語版

```mermaid
flowchart LR
    subgraph P1["1. 感情を捉える"]
        direction TB
        A["感情が湧き上がる"] --> B["英語・オランダ語・<br/>日本語に翻訳"]
        B --> C{"正しく表現<br/>できているか？"}
        C -->|いいえ| B
        C -->|はい| D["形式を選ぶ：<br/>俳句・連句・短歌<br/>5-7-5・5-7-5-7-7・8-8-8-8<br/>または自由な短長短"]
    end

    subgraph P2["2. AIと英語下書き"]
        direction TB
        E["AIが英語の文を作成"] --> F["私が選択・修正・変更"]
        F --> G{"十分近いか？"}
        G -->|いいえ| E
        G -->|はい| H["日本語下書きを依頼"]
    end

    subgraph P3["3. 日本語推敲ループ"]
        direction TB
        I["AIが意味と<br/>日本人の読み体験を説明"] --> J["私が意味を修正"]
        J --> K["AIが日本語を再修正"]
        K --> L{"日本語で感情が<br/>正しく伝わるか？"}
        L -->|いいえ| I
        L -->|はい| M["ふりがな付き<br/>テキストをコピー"]
    end

    subgraph P4["4. 最終仕上げ"]
        direction TB
        N["自作HTMLに貼り付け<br/>ふりがなを整形"] --> O["結果を<br/>スクリーンショット"]
        O --> P["Word文書に貼り付け"]
        P --> Q["英語テキストと<br/>印鑑を追加"]
        Q --> R["保存または印刷"]
    end

    P1 --> P2
    P2 --> P3
    P3 --> P4

    style P1 fill:#e8f4f8,stroke:#2a7a9b,stroke-width:1.5px
    style P2 fill:#eef8e8,stroke:#3a8a4a,stroke-width:1.5px
    style P3 fill:#f8f0e8,stroke:#9b6a2a,stroke-width:1.5px
    style P4 fill:#f5e8f8,stroke:#7a3a9b,stroke-width:1.5px
```

---

### Notes
- Designed to use page **width** (left → right phases) instead of one long vertical diagram.
- Each phase contains its own decision/loop arrows.
- Compatible with GitHub, Obsidian, Notion, VS Code, mermaid.live, etc.
