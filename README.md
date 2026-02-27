# ADOS Landing Page — ados.dev

ADOS の公式ランディングページです。  
GitHub Pages + カスタムドメイン `ados.dev` で配信しています。

## 開発

```bash
# ローカルプレビュー
npx serve .
# or
python3 -m http.server 8080
```

## デプロイ

`main` ブランチに push するだけで GitHub Pages に自動デプロイされます。

## 構成

```
index.html    — ランディングページ本体（単一 HTML）
CNAME         — カスタムドメイン設定
.nojekyll     — Jekyll 処理を無効化
```

## カスタムドメイン設定

DNS で以下を設定済み:

| Type  | Name | Value                      |
|-------|------|----------------------------|
| CNAME | @    | 1cll.github.io             |

or (A レコード for apex domain):

| Type | Name | Value           |
|------|------|-----------------|
| A    | @    | 185.199.108.153 |
| A    | @    | 185.199.109.153 |
| A    | @    | 185.199.110.153 |
| A    | @    | 185.199.111.153 |

## リンク

- **LP**: https://ados.dev
- **ダッシュボード**: https://ados-platform-dashboard.web.app
- **GitHub**: https://github.com/1cll/ados
