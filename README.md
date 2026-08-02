# slide-wireframe

16:9スライドのワイヤーフレーム レイアウトテンプレート集（Claude Code スキル）。

白・黒・グレーのみ、テキストは全てダミー。1280×720固定でブラウザからそのままPDF化できる。

## インストール

各端末で1回だけ。

```bash
git clone https://github.com/hiroho-t/slide-wireframe.git ~/.claude/skills/slide-wireframe
```

`~/.claude/skills/` に置くと、プロジェクトを問わず全セッションで使える。

## 更新

```bash
cd ~/.claude/skills/slide-wireframe && git pull
```

## 収録

| カテゴリ | 数 |
|---|---|
| `cover/` 表紙 | 8 |
| `toc/` 目次 | 6 |
| `section/` 中見出し | 9 |
| `company/` 会社概要 | 7 |
| `message/` 社長挨拶・メッセージ | 4 |
| `member/` メンバー紹介 | 3 |
| `faq/` よくある質問 | 1 |

型の一覧と選び方は [SKILL.md](SKILL.md) を参照。

## 注意

参考にした実資料のスクリーンショットは他社の著作物のため、このリポジトリには含めない（`.gitignore` で画像を除外している）。
