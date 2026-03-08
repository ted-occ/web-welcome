# web-welcome

TED 開発チーム（ted-occ）の Welcome ページおよびメンバー参加申請用リポジトリです。

**Welcome ページ:** https://ted-occ.github.io/web-welcome/

## ミッション

> 信頼できるソフトウェアを、持続可能な方法で届け続ける

TED 開発チームは、顧客・社内・社会に対して価値あるソフトウェアを提供します。その開発プロセスそのものが信頼に値するものであることを、ルールと文化で保証します。

## 参加方法

Pull Request で参加申請を行います。PR がマージされると Organization への招待が届きます。

### 手順

1. このリポジトリを **Fork** する
2. `members/` に自分の GitHub ユーザー名でファイルを作成する（例: `members/your-github-username.md`）
3. [members/_template.md](members/_template.md) をコピーして、自己紹介・希望ロール・参加動機を記入する
4. `main` ブランチに向けて PR を作成する（タイトル: `Join request: @your-github-username`）
5. TED-Administrator が確認後、マージされると招待メールが届きます

## リポジトリ構成

```
web-welcome/
├── index.html           # Welcome ページ
├── members/
│   └── _template.md     # 参加申請テンプレート
└── README.md
```

## ロール

| ロール | 説明 |
|--------|------|
| **FD-E** | Engineering（技術） |
| **FD-C** | Coordinating（顧客・事業） |

技術（FD-E）と顧客・事業（FD-C）は上下関係ではなく、相互補完の関係です。

## ライセンス

&copy; 2026 ted-occ
