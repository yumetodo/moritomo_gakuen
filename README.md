# 森友学園への国有地売却の決裁文書をめぐる財務省の調査結果をMarkdown書き起こしする

朝日新聞の

[森友学園への国有地売却の決裁文書をめぐる財務省の調査結果：朝日新聞デジタル](https://www.asahi.com/articles/ASL3D5H10L3DUTIL041.html)

にある財務省公開資料のコピーと思われる

http://www.asahicom.jp/news/esi/ichikijiatesi/moritomo-list/20180312/all.pdf

をMarkdown書き起こしする。

## お知らせ

現在改竄前のみを書き起こしています。改竄後は別のbranchを切ってそっちに書き起こしたいのですが、いいbranch名が浮かばないというただそれだけの理由で作業していません。

いい名前が浮かんだ人は  
https://github.com/yumetodo/moritomo_gakuen/issues/5  
まで。

## Directory構成

Direcotry名を文章名とし、その下に`README.md`を置き書き起こす。`master`ブランチは書き換え前のものを置く。

文章名を英訳するのは不可能なのでヘボン式ローマ字とする。

ref: http://www.pref.kanagawa.jp/osirase/02/2315/hepburn.html

`「」（）`は`_`に置換する。また`（平成yy年m月dd日）`は省略して命名する。末尾の`_`は省略する。

1. [貸付決議書①「普通財産決議書（貸付）」（平成27年4月28日）](./kashittsukekessaiketsugisho1_futsuuzaisansho_kashitsuke/README.md)
2. 貸付決議書②「普通財産決議書（貸付）」（平成27年5月27日）
3. 売払決議書「普通財産売払決議書」（平成28年6月14日）
4. [特例承認の決裁文書①「普通財産の貸付けに係る承認申請について」（平成27年2月4日）](./tokureishouninnokessaibunsho1_futsuuzaisannokashitsukenikakawarushouninshinseinitsuite/README.md)
5. 特例承認の決裁文書②「普通財産の貸付けに係る特例処理について」（平成27年4月30日）
6. 承諾書の提出について（平成26年6月30日）
7. 未利用国有地等の処分等の相手方の決定通知について（平成27年2月20日）
8. 予定価格の決定について（年額貸付料（定期借地））（平成27年4月27日）
9. 特別会計所属普通財産の処理方針の決定について（平成27年4月28日）
10. 有益費支払いに関する意見について（照会）（平成28年2月25日）
11. 有益費支払いに関する三者合意書の締結について（平成28月3月29日）
12. 国有財産の鑑定評価委託業務について（平成28年4月14日）
13. 予定価格の決定（売払価格）及び相手方への価格通知について（平成28年5月31日）
14. [特別会計所属普通財産の処理方針の決定について（平成28年6月14日）](./tokubetsukaikeishozokufutsuuzaisannoshorihoushinnnoketteinitsuite/README.md)

## ファイルの規約

- 紙の文章であることに起因する折返しは再現しない
- 段落は再現する
- トップレベルの順序付き箇条書きはh3タグ相当のMarkdown構文を利用する。
- 経緯のようにタイムラインがあるものは表にする(Markdown構文利用) (ref: [#6](https://github.com/yumetodo/moritomo_gakuen/pull/6))

## LICENSE

行政文書は著作権が発生しないのでそれを尊重しCC0とする。

## コミット規約

コミットメッセージは英語か日本語で書くこととしそれ以外は自由。

複数のファイルを変更するコミットは不必要に作るべきではない。

## 編集に参加するには

### 私(@yumetodo)の知り合いの場合

Twitterに声をかけていただくのが速い。

新規に文章書き起こしをする場合は**Issueで宣言してから**作業を開始する。

### それ以外の方

このrepoをforkして編集に参加する。

新規に文章書き起こしをする場合は

```sh
git commit --allow-empty -m "書き起こし文章名"
```

で空commitを作成してその時点で**Pull Requestを投げてから**作業を開始する。

## 書き起こしミスを発見した場合

まずGithubのアカウントを取得する。

### 対象文章が現在編集中(Issue/Pull Requestが立っている)場合

当該Issue/Pull Requestにコメントする

### それ以外

このrepoをforkして修正しPull　Requestを投げてください。

### よくわからないとき

**とりあえずIssueを立てる**。誰かが治すと思う。

もしくは私(@yumetodo)にTwitterでリプを投げる。多分代わりにIssueを立てるはず。

## 参考

テキスト起こしを完全手動でやるのは大変なのでOCRを使うとよいです。  
例えば、Google DriveにPDFの一部を切り抜いた画像を上げてWriterで開くとOCRしてくれます。
