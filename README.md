# 伊東 店舗紹介 (ito-instagram)

伊東市の事業者を分野別に台帳形式でまとめ、一者ずつ店舗紹介ページで紹介する資料サイトです。
もともと Instagram 改善提案の資料サイトとして ito-chamber.portal の `instagram/` 配下にありましたが、単独のリポジトリとして独立し、その後 Instagram 改善提案のページとデータはすべて削除して店舗紹介サイトに切り替えました。

## 構成

- `index.html` … トップ（3分野の台帳＋ふるさと納税特設ページへの入口）
- `group/iimono/` … いとうのいいもの（伊東ブランド認定事業者）— `index.html` が認定事業者台帳、各事業者の店舗紹介ページ
- `group/okashi/` … 伊東お菓子ぃ共和国 — `index.html` が加盟店台帳、各店の店舗紹介ページ
- `group/jizakana/` … 伊豆・いとう地魚王国 — `index.html` が会員事業者台帳、各事業者の店舗紹介ページ
- `tokens.css` … 共通デザイントークン

## 公開URL

GitHub Pages: https://ryo-itojournal.github.io/ito-instagram/

## ポータルとの関係

デジタルミュージアムや各展示室、ふるさと納税プロトタイプは ito-chamber.portal 側にあり、本リポジトリからは絶対URLでリンクしています。各展示室の「部門の事業者一覧へ」から本リポジトリの台帳へ、各店舗紹介ページの「展示室へもどる」から展示室へ戻れます。
