# FRONTIER — 架空企業コーポレートサイト

OneBeによる企業サイトのデザインスタディ。参照サイトの砂漠を使った大きなキービジュアル、赤・黒・濃灰の配色、凝縮した英文見出し、人物チャートの操作を、架空企業のコンテンツで実装しています。

- トップ：https://onebe-inc.github.io/frontier-corporate-demo/
- 組織チャート：https://onebe-inc.github.io/frontier-corporate-demo/chart/
- 参照：https://www.tbs.co.jp/VIVANT_tbs/ および https://www.tbs.co.jp/VIVANT_tbs/chart/

## 構成

ビルド不要のHTML / CSS / JavaScript。GitHub Pagesのmainブランチ・ルートディレクトリから配信します。

`index.html` は企業トップ、`chart/index.html` はインタラクティブな組織・事業チャートです。`data.js` に9名の架空プロフィール、`app.js` に操作処理、`styles.css` にレスポンシブスタイルを収録しています。

チャートはドラッグ、ピンチ、ホイール、＋／−ボタンで操作できます。キーボードでチャート領域にフォーカスした後、矢印キーで移動、＋／−で拡大縮小、0で全体表示。人物選択でプロフィール、Escapeで閉じる。部門絞り込みと情報の一括表示も利用できます。

## 素材・コンテンツ

企業、人物、日付、ニュース、事業は架空の設定です。TBS・VIVANTおよび実在する同名企業との関係はありません。参照サイトの画像・ロゴ・ソースコードは収録していません。画像はOpenAI組み込み画像生成ツールで新規作成し、WebPへ最適化しました。ベクターイラストは使用していません。チャートの線・枠はHTML/CSSの機能的な図表要素です。

Oswaldフォント：Copyright the Oswald Project Authors。SIL Open Font License 1.1。詳細は `assets/OFL.txt`。

問い合わせ画面は入力確認のデモです。送信・保存機能はありません。アクセス解析や広告タグを設置せず、検索インデックスはnoindexで抑止しています。

## 運用

HTMLは相対パスで構成しています。新しい公開パスに移す場合はcanonicalとOGPの絶対URLを更新してください。公開後の実ユーザーCore Web Vitalsは未取得です。
