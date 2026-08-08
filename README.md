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

## 一覧を見る

- ローカル：`index.html` をブラウザで開く（サーバー不要）
- Web：https://hiroho-t.github.io/slide-wireframe/

## 収録

| カテゴリ | 数 |
|---|---|
| `cover/` 表紙 | 20 |
| `toc/` 目次 | 17 |
| `section/` 中見出し | 19 |
| `company/` 会社概要 | 21 |
| `message/` 社長挨拶・メッセージ | 12 |
| `member/` メンバー紹介 | 16 |
| `service/` サービス紹介 | 14 |
| `problem/` 課題提起 | 5 |
| `chart/` 組織図・チャート | 1 |
| `flow/` フロー・体制 | 9 |
| `price/` 料金 | 3 |
| `clients/` 導入企業・実績 | 9 |
| `voc/` お客様の声 | 4 |
| `media/` メディア掲載 | 2 |
| `faq/` よくある質問 | 2 |
| `contact/` お問い合わせ | 6 |

型の一覧と選び方は [SKILL.md](SKILL.md) を参照。

## 注意

参考にした実資料のスクリーンショットは他社の著作物のため、このリポジトリには含めない（`.gitignore` で画像を除外している）。
