# ai-sanbo-report ─ 今日のまとめレポート（AI参謀）

AI参謀（1日訪問）の最後に、**今日やったこと・作ったスキル・使いみちを1枚のレポート**にまとめるスキルです。
同意をいただいた範囲だけ、数字・人名・お客様の情報を抜いたうえで、スキルとレポートを「回収用」フォルダにまとめます。

- 最初に、掲載の範囲を3択で確認します（A 社名あり／B 社名なし／C 社内のみ）
- 数字・人名・お客様の情報・社内の固有の呼び名は書きません
- 送信・アップロードはしません。zipを作るところまでです。送るのはご本人です

## 入れ方

使っているAIの仕事部屋（参謀室など）を開いた状態で、次の文章を貼って送ってください。

**ChatGPT（Codex）の場合**
```
次のGitHubのリポジトリから、skills/ai-sanbo-report フォルダを、このフォルダの .agents/skills/ の中にそのままコピーしてください。
https://github.com/yujirotn/ai-sanbo-report-skill
コピーしたら、中の SKILL.md を読んで、何をするスキルか3行で教えてください。
```

**Claude（Claude Code）の場合**
```
次のGitHubのリポジトリから、skills/ai-sanbo-report フォルダを、このフォルダの .claude/skills/ の中にそのままコピーしてください。
https://github.com/yujirotn/ai-sanbo-report-skill
コピーしたら、中の SKILL.md を読んで、何をするスキルか3行で教えてください。
```

ダウンロードの許可を聞かれたら許可してください（このページから取ってくるためです）。

## 使い方

```
$ai-sanbo-report で、今日のまとめを作ってください。
```
（Claude の場合は `/ai-sanbo-report`）

## 中身

```
skills/ai-sanbo-report/
├── SKILL.md              手順（同意 → 集める → 伏せる → レポート → 回収用 → 確認）
└── assets/template.html  1枚レポートのひな形
```

提供：株式会社SHO-SAN
