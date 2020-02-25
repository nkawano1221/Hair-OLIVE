リセットCSS
~~~~
インターネットを閲覧するためのブラウザにはいくつかの種類がありますが、それぞれ独自のCSSをデフォルトで持っています。つまり、同じ<h1>...</h1>で指定しても、ブラウザごとに文字の大きさが異なったり上下の幅が異なったりします。

何らかのトラブルで、Webページ作成者が用意したCSSファイルが読み込まれなかった時、ブラウザ側で最低限の見た目を保障するために、各ブラウザが独自のデフォルトCSSを持っています。

しかし、これが時に、Webページ作成者が用意したCSSファイルと影響しあって見た目を崩してしまうことがあります。これを防ぐために通常、各ブラウザが用意しているデフォルトのCSSを上書きするCSSを書いておきます。これをリセットCSSと呼びます。


レイアウトを読み解こう

HTMLを実装する際に、以下を常に意識する必要があります。

HTMLとは左上に重力のある積み木である
積み木の一つ一つは中身によって大きさの変わる箱であり、入れ子構造になっている

①  HTMLとは左上に重力のある積み木である

