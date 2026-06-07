# CSS設計2026版 ドキュメント構成

このリポジトリは、汎用的に使えるCSS設計ルールを定義したドキュメント群です。

## ドキュメント関係図

```mermaid
graph TD
    classDef doc fill:#f9f,stroke:#333,stroke-width:2px;
    
    Top[CSS設計2026版] --> Policy(方針・概念)
    Top --> System(設計・実装)

    Policy --> D1[目的]
    Policy --> D2[基本思想]
    Policy --> D3[判断基準]
    Policy --> D4[設計原則]

    System --> D5[レイヤー設計]
    System --> D6[トークン設計]
    System --> D7[コンポーネント設計]
    System --> D8[実装ルール]

    click D1 href "目的.md"
    click D2 href "基本思想.md"
    click D3 href "判断基準.md"
    click D4 href "設計原則.md"
    click D5 href "レイヤー設計.md"
    click D6 href "トークン設計.md"
    click D7 href "コンポーネント設計.md"
    click D8 href "実装ルール.md"
```

## 各ドキュメントへのリンク

- [index.md](index.md): 全体の構成と役割の一覧です。
- [目的.md](目的.md): なぜこの設計を行うかを定義しています。
- [基本思想.md](基本思想.md): 最小限・MVP・単一責任の考え方を定義しています。
- [判断基準.md](判断基準.md): CSS機能を採用する基準を定義しています。
- [設計原則.md](設計原則.md): CSS記述前の判断順序を定義しています。
- [レイヤー設計.md](レイヤー設計.md): CSSの責務と優先順位を定義しています。
- [トークン設計.md](トークン設計.md): TypographyとSpacingを定義しています。
- [コンポーネント設計.md](コンポーネント設計.md): 再利用する部品のルールを定義しています。
- [実装ルール.md](実装ルール.md): NestingやContainer、Stateなどの実装規則を定義しています。
