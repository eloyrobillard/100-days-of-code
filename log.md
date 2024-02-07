# 100 Days Of Code - Log

### Day 1: December 25, Monday

**Today's Progress**: Working out debounced text search in React. Also, first time using NextJS.

**Thoughts** I'm not used enough to using useCallback/useMemo. But at least it's clearer how they help solve re-render issues.

**Link(s) to work**
[Debounced user input in NextJS](https://github.com/eloyrobillard/nextjs-user-input)

### Day 2: December 26, Tuesday

**Today's Progress**: Created [DB in Supabase](https://supabase.com/dashboard/project/nuwidquxephmkslwzdxh/database/tables), and sent pokemons through with Prisma. Based on [this article](https://qiita.com/tomohiko_ohhashi/items/da804ed1f5870c9ce52d).

**TODO**: 
- API in Next
- Auth

**Thoughts**: I'm still unclear on how the whole FE+BE Next stuff will unwrap. Looking forward to tomorrow.

**Link(s)**: [day 2 commit](https://github.com/eloyrobillard/nextjs-user-input/commit/f193f6ad2bdc245d8445aed5bee2529dfe10e987)

### Day 3: December 27, Wednesday

**Today's Progress**
Made changes based on Magnus' [feedback](https://codereview.stackexchange.com/questions/288595/parsing-fetched-data-in-typescript/288603#288603):
- using typebox + typebox's TypeCompiler for JSON Schema and type validation
- removed `Result<T>` and custom JSON parsing

**TODO**: 
- Link API with FE
- Auth

**Link**: [day 3 commit](https://github.com/eloyrobillard/nextjs-user-input/commit/ef38c8f345a9b3962d83a1d3942284ba30f4cd2c), [r/codereview](https://www.reddit.com/r/codereview/comments/18ryom5/typescript_prisma_code_to_populate_db_with/)

### Day 4: December 28, Thursday

**Today's Progress**
Refactored based on [Netflix Clone React](https://github.com/NKDesign30/Netflix-Clone-React). 

**TODO**: 
- Link API with FE
- Auth

**Link**: [day 4 commit](https://github.com/eloyrobillard/nextjs-user-input/commit/81abb6a9d81d36455437d122de246c60168df4b7)

### Day 5: December 29, Friday

**Today's Progress**
Added grid for pokemon cards. Fixed, expanded, and further customized the ESLint config.

**Link**: [day 5 commit](https://github.com/eloyrobillard/nextjs-user-input/commit/e61d4d9c09eb55b4377dad2ed62184ca386791a7)

### Day 6: December 30, Saturday

**Today's Progress**
Re-populated DB with more complete pokemon data, including the sprites now shown in the UI.

**Link** [day 6](https://github.com/eloyrobillard/nextjs-user-input/commit/74008f6512cfe0965027e527caf7f3f454061797)

### Day 7: December 31, Sunday

**Today's Progress**

<details>
![image](https://github.com/eloyrobillard/100-days-of-code/assets/67062814/32ab08ad-8634-4b61-8430-bebdfaff42a8)
</details>

[Code Review](https://codereview.stackexchange.com/questions/288694/centering-ui-elements-with-flex-in-react)

**Link** [day 7](https://github.com/eloyrobillard/nextjs-user-input/commit/4fac9831a7f84c49ba6d4bdd9b16d6a7f07c356f)

### Day 8: January 1, Monday

**Today's Progress**

Added route/Link to page with pokemon details. Styling remains minimal at this point, and some data (abilities, forms) is missing.

**Link** [commit](https://github.com/eloyrobillard/nextjs-user-input/commit/de7794b7d660f223e9fd843cd0a58901794bc75c)

### Day 9: January 2, Tuesday

**Today's Progress**

Added styling to pokémon details page. Discovered it won't be easy to create the perspective effect from [pokedex-angular-app](https://github.com/HybridShivam/pokedex-angular-app/tree/master).

**Links** [commit](https://github.com/eloyrobillard/nextjs-user-input/commit/c724905ff4b15f4de8ae54c7479e27f8c03f6ae0), [code review](https://codereview.stackexchange.com/questions/288731/icon-styling-in-tailwind-react)

### Day 10: January 3, Wednesday

**Today's Progress**

Discovered it's actually easy to create the [perspective effect](https://github.com/HybridShivam/pokedex-angular-app/blob/master/src/app/pokemon-detail/pokemon-detail.component.scss#L224) from [pokedex-angular-app](https://github.com/HybridShivam/pokedex-angular-app/tree/master).
Started creating JSON parser and TS types for next Pokémon model upgrade.

**Links** [commit](https://github.com/eloyrobillard/nextjs-user-input/commit/6e093e445d81d58e8ab0af641a9100f1f725b735), [code review](https://codereview.stackexchange.com/questions/288743/debouncing-search-query-in-react-next-14)

### Day 11: 

**今日の進捗**

abilitiesフィールドとForms、Genus、Name、Statモデルを追加した。加えて、DBの更新の下準備を行なった。

**Links** [commit](https://github.com/eloyrobillard/nextjs-user-input/commit/b7ce156e2d20bce5bac974c1c643f23763cd83a6), [code review](https://codereview.stackexchange.com/questions/288760/fully-updating-db-table-with-prisma-typescript)

### Day 12:

**今日の進捗**

ポケモンは自分の分類と必ずしも名前を共有していないことに気づき、ポケモンデータから正しい分類名を使うことにした。

**Links**

[commit]([**今日の進捗**](https://github.com/eloyrobillard/nextjs-user-input/commit/e3d5152e04994bbabae7d37970824b99f186529e), [typebox issue](https://github.com/sinclairzx81/typebox/issues/719)

### Day 13, 1月6日:

今日の進歩：`populateWithFullPokemonDetails`を修正し、やっとDBのデータを拡張することができた。その一部をUIに追加した。

内省：DBのリレーションがよくわからない。あとは、なぜかポケモンの一部がDB更新時に無視される。

[commit](https://github.com/eloyrobillard/nextjs-user-input/commit/d45a0fefb6a7be46d5d3e1613345d0ca8c51eb14), [code review](https://codereview.stackexchange.com/questions/288760/fully-updating-db-table-with-prisma-typescript)

### Day 14, 1月7日

今日の進捗：CSSで詳細ページに彩りを添えた。

内省：テキスト要素の間に空間を入れるには`margin-right`よりいい方法はなんだろう。

[commit](https://github.com/eloyrobillard/nextjs-user-input/commit/9e4d3d88bde53a828bd0ce9011105e1a7b92cb7f), [code review](https://codereview.stackexchange.com/questions/288803/css-tailwind-to-display-pok%c3%a9mon-details)

### Day 15, 1月8日

進捗：ゲージアニメーションを設置した。

内省：諦めて模範を参考したから、ドリル練習にしたい。

リンク：[commit](https://github.com/eloyrobillard/nextjs-user-input/commit/8acc3728c911d3e7b272117dc2dcbf7cbfc2bab2), [code review](https://codereview.stackexchange.com/questions/288813/gauge-animation-in-css)

### 第16日、1月9日

進捗：攻撃・効果などのモデルを追加し、型コンパイラの追加を開始。

内省：PokeAPIからデータを正しく取得することが一番時間かかりそう。

リンク： [commit](https://github.com/eloyrobillard/nextjs-user-input/commit/03b9d20f4608ffed5bacc2c9a7d99e81b4fd1079)

### 第17日、1月10日

進捗：攻撃モデルとその関連モデルを追加。ポケモンモデルとポケモン分類モデルを修正・更新。

内省：populate更新はやばそう。

リンク：[commit](https://github.com/eloyrobillard/nextjs-user-input/commit/1f77d1b26f9716cce3e7dbe2c7046293bd0265a5), [code review](https://codereview.stackexchange.com/questions/288864/prisma-models-in-one-to-many-relations)

### 第18日、1月11日

進捗：攻撃データの移動のための関数を準備。テスト未完。

感想：全てのデータ要求を同時に行わなくてよさそうだから、少し安心した。

リンク：[commit](https://github.com/eloyrobillard/nextjs-user-input/commit/acb220573e383844bff03bed5718a5b7c60b5109), [review](https://codereview.stackexchange.com/questions/288864/prisma-models-with-various-relations)

### 第19日、1月12日（金）

進捗：新しいタイプモデル。ポケモンデータを再ダウンロード。debounced検索入力をサーバコンポーネントに変換。

リンク：[commit](https://github.com/eloyrobillard/nextjs-user-input/commit/acb220573e383844bff03bed5718a5b7c60b5109), [レビュー](https://codereview.stackexchange.com/questions/288895/next-js-14-debouncing-user-search-query-with-server-side-components)

### 第20日、1月13日（土）

進捗：モデル修正とpopulateからspeciesデータを送信（だが、まだバグあり）。

リンク：[commit](https://github.com/eloyrobillard/nextjs-user-input/commit/733d90904c1c276d4e2912f67b916f5302022006), [レビュー](https://codereview.stackexchange.com/questions/288904/handling-request-failure-in-next-js-server-side-component)

### 第21日、1月14日（日）

進捗：DBにポケモンと種類データを拡張した。だが分類データが見つからない。

リンク：[commit](https://github.com/eloyrobillard/nextjs-user-input/commit/5a24ed5e7314535561eb75e6154887e8e08cc5e8)

### 第22日、1月15日（月）

進捗：ID重複などのリスクの回避方法を見つけたと思ったら、どうやら、接続タイムアウトの問題が出た。

リンク：[commit](https://github.com/eloyrobillard/nextjs-user-input/commit/37bc27adf72c8251b11698a0316fd910647914c8), [質問]（https://stackoverflow.com/questions/77821467/prisma-db-connection-times-out-when-inserting-data-through-sub-queries）

### 第23日、1月16日（火）

進捗：接続タイムアウト問題を無視し、分類ボタンにポケモン図鑑別の情報を隠した。

リンク：[commit](https://github.com/eloyrobillard/nextjs-pokedex/commit/eedfffc568193317dbb7f0bc62d4fbddb62ed56d), [レビュー](https://codereview.stackexchange.com/questions/288946/display-modal-on-click-in-center-of-screen-with-react)

### 第24日、1月17日（水）

進捗：別のところにクリックすれば、ポケモン分類のポップアップが閉じるようにした。後少しレイアウトをいじった。

リンク：[commit](https://github.com/eloyrobillard/nextjs-pokedex/commit/f51c27ac9ddc2c86f3cda87f65a58778785e1b1e)、[質問](https://stackoverflow.com/questions/77830607/how-to-properly-handle-db-query-errors-in-next-14-server-side-components)

### 第25日、1月18日（木）

進捗：サーバコンポーネントからDBクエリのロジックを取り出した。あとは行の長さとオブジェクトの波括弧ルールが衝突しないようにESLintコンフィグを変更した。

リンク：[commit](https://github.com/eloyrobillard/nextjs-pokedex/commit/d98fc8c0a4cf16598102e06a522e543a21b83ca4)

### 第26日、1月19日（金）

進捗：種族値ゲージがタイプ色を使うことにした。だが色がデフォルトでめちゃくちゃ醜い。

リンク：[commit](https://github.com/eloyrobillard/nextjs-pokedex/commit/ed2fd43b97efdc19cbf9a09296ae217aed71e4ca)

### 第27日、1月20日（土）

進捗：Prismaに再帰的にデータを記入する試み続行。まだダメっぽい。

リンク：[commit](https://github.com/eloyrobillard/nextjs-pokedex/commit/c2c9be4a1fce017a82fd8140cd9e3816167b4e62), [質問](https://stackoverflow.com/questions/77850720/recursively-defining-a-recursive-model-in-prisma-postgres)

### 第28日、1月21日（日）

進捗：ツリーを配列に変換してやっとDBに進化情報を挿入できた。

リンク：[コミット](https://github.com/eloyrobillard/nextjs-pokedex/commit/1f7a9cd653261e140ecfbbbe764faf74abe082a9), [質問](https://stackoverflow.com/questions/77850720/recursively-defining-a-recursive-model-in-prisma-postgres)


### 第29日、1月22日（月）

進捗：進化の流れのUIを一部実装。進化がないとバグるし、同じ段階に複数の進化が可能なら変になる。

リンク：[コミット](https://github.com/eloyrobillard/nextjs-pokedex/commit/9309823cd2d0f8cbf73bc586366b48ad5de2c941)、[質問](https://stackoverflow.com/questions/77858339/ts-how-to-filter-null-from-the-type-of-a-single-object-field-for-an-array-of)

### 第30日、1月23日（火）

進捗：タイプデータをDBに挿入。デオキシスの進化の流れを有効化。

リンク：[コミット](https://github.com/eloyrobillard/nextjs-pokedex/commit/8c05e86fa7401bd6a8e4d29890ab0e5ebc2fc1e3)、[質問](https://stackoverflow.com/questions/77858339/how-to-filter-null-from-the-type-of-a-single-object-field-for-an-array-of-such?noredirect=1#comment137276575_77858339)

### 第31日、1月24日（水）

進捗：なし（AnkiのSet Font Sizeのバグ修正で忙しかった。ごめん）

リンク：[PR](https://github.com/cjhoward/anki-set-font-size/pull/8)

### 第32日、1月25日（木）

進捗：リレーションを活用し、ポケモン及び種類及び進化の流れデータの取得過程を大幅に改善した。

リンク：[コミット](https://github.com/eloyrobillard/nextjs-pokedex/commit/ec0d0479721ef19ab3100a1e994f3907924e3160)

### 第33日、1月26日（金）

進捗：JSONから全てのポケモンをDBに無事移動。ヌル可能なフィールドを書き換えた。

リンク：[コミット](https://github.com/eloyrobillard/nextjs-pokedex/commit/2e820c00ad1a04dccb24139fcda6ccb81a7380a6)

### 第34日、1月27日（土）

進捗：JSONから種類・進化データをDBに挿入。全JSON（〜200MiB）をgit LFSでアップした。

リンク：コミット[#1](https://github.com/eloyrobillard/nextjs-pokedex/commit/4a59ac92cb9934012c7633799af604d0e6345ff2)、[#2](https://github.com/eloyrobillard/nextjs-pokedex/commit/bea3606b5c4e0a20f98ad0216c3624991bc1c21b)

### 第35日、1月28日（日）

進捗：Chainモデルから詳細を取り出し、進化の引き金の表示をより簡単にした。

リンク：[コミット](https://github.com/eloyrobillard/nextjs-pokedex/commit/f113171803faa31430ab9100ace8f341447ede08)

### 第36日、1月29日（月）

進捗：Appsmith->releaseを本ブランチにマージ。Carbon UI Issueを検討中。

リンク：[PR](https://github.com/appsmithorg/appsmith/pull/30436)

### 第37日、1月30日（火）

進捗：AnkiのSyntax HighlightingでどうやってCSSクラスの使用を指定できるのかいろいろ調べた（未解決だが）。

### 第38日、1月31日（水）

進捗：Carbon DSをフォーク＋セットアップ。いいIssueを検索中。

リンク：[フォーク](https://github.com/eloyrobillard/carbon)

### 第39日、2月1日

進捗：Yomitanに機能依頼を投稿。

リンク：[依頼](https://github.com/themoeway/yomitan/issues/610)

### 第40日、2月2日

進捗：Issueに挙げた提案は可能だと確認した。toasted-nutbreadと話もした！The Legend本人

リンク：[依頼](https://github.com/themoeway/yomitan/issues/610)

### 第41日、2月3日

進捗：Yomitanに複数ノートビューを追加中。

リンク：（バグ修正中だからまだコミットしてない）

### 第42日、2月4日

進捗：Ankiブラウザーで全カードを表示するためのPRを投稿。

リンク：[PR](https://github.com/themoeway/yomitan/pull/636)

### 第43日、2月5日

進捗：Yomitan PRで`noteView`を安全削除できるかどうか確認した：まだ二箇所から呼び出されているので念のためnutbreadに質問した。

リンク：[コミット](https://github.com/themoeway/yomitan/pull/636/commits)、[質問](https://github.com/themoeway/yomitan/pull/636#discussion_r1477769798)

### 第44日、2月6日

進捗：Yomitan PRに関するブログ記事を補た。

リンク：[記事](https://zenn.dev/articles/bd0e1f581dd138/edit)

### 第45日、2月7日

進捗：Yomitan PRレビューを要求。記事をさらに補た。

リンクは上記同様
