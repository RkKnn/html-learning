# html-scss-training

## Block
BlockにするかElementにするかの境はかなり悩みました。
そのパーツ単体で別の場所にあっても不思議ではなさそうな場合はBlockになりそうだという理解です。

headerやfooter, sidebarは、今回の場所に限らずどこにでも配置できそうなのであまり悩まずBlockとしました。

逆にmainやsection周りをどうすべきかとても悩みました。
特に、今回はsectionブロックとsection-itemブロックが生まれており、親子関係のようになっていてあまり良くないのかなとも思います・・・。
この辺りを考えていると、どれもこれもBlockに見えてきてしまう状態に陥りました。

既存サービスなどのレイアウトを見るようにして、実際だとどう組んでいるか探るのもかなり勉強になりそうだと感じています。
なかなか明確な答えが無い範囲だと思うので、とにかく経験を増やしたいところです。

## Element
親子関係が明確だとElementは作りやすいのかなという印象です。
例えば、sectionについての"title"や、sidebarについての"title"など、xxについてのyyはxx__yyが簡単にイメージできそうです。
Block視点から見ても、titleというパーツ単体で存在させると、何についてのtitleか意味不明なので単体で存在し得ずElementと出来そうです。

## Modifier
今回は使っていないですが、使用場面はかなり明確だと、今のところは思っています。
