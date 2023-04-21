# uBlacklist-scam-net-shops

## Synopsis

Found a ridiculously low price on a net shop?
Watch out for scam!<br>
バカみたいに安い商品をネットショップで見かけた？
詐欺にご注意！

- [消費者庁 - インターネット通販トラブルインターネット通販トラブル](https://www.caa.go.jp/policies/policy/consumer_policy/caution/internet/trouble/internet.html)
- [「届くのは粗悪品」謎の通販サイト◆ＳＮＳで拡散、発送元を追跡取材【時事ドットコム取材班】](https://www.jiji.com/jc/v8?id=202204soakuhin-team)

By subscribing this opensource list with [uBlacklist](https://github.com/iorate/uBlacklist),
you can exclude such suspicious net shops, from search results, that might be a scam:
Such sites probably do not deliver the goods you ordered, or deliver a cheap knock-off.<br>

このオープンソースのリストを [uBlacklist](https://github.com/iorate/uBlacklist) で購読すれば、怪しいネットショップを検索結果から除外できます。
そういったサイトは商品を発送しないか、あるいは安い粗悪品を発送するかもしれません。

Since the author is a Japanese, this list covers mainly sites written in Japanese,
but happy to include other suspicious sites in other languages.<br>
作者は日本人なので、このリストは主に日本語のサイトを対象にしていますが、他言語での怪しいサイトの追加も歓迎します。

## Example of Scum Net Shops

| image                            | Japanese description                                              | English description                                                                                                                                                                        |
|----------------------------------|-------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <img src="images/example-1.png"> | <li>やけに安い</li><li>「〜〜で購入しました」などと中古品のような説明。おそらくメルカリなどからの無断転載。</li> | <li>Overly discounted</li><li>The description of the item is as if it were a used item, such as "I bought it at ..." etc. Probably an unauthorized reproduction from Mercari or such.</li> |
| <img src="images/example-2.png"> | <li>奇妙な名前のユーザーによるレビュー</li>                                        | <li>Reviews by users of strange names</li>                                                                                                                                                 |
| <img src="images/example-3.png"> | <li>ドメイン名とサイト名があまりに違う</li><li>ネットショップとして不自然なドメイン</li>             | <li>Mismatch between domain name and site name</li><li>Domain name is not natural for a net shop.</li>                                                                                     |                                                                                                                                                                                                      
| <img src="images/example-4.png"> | <li>偽のファビコンを使い、メルカリなど有名サイトのふりをしている</li>                           | <li>Using a fake favicon to pretend to be famous sites like Mercari.</li>                                                                                                                  |

## Usage

1. Install uBlacklist.<br>uBlacklist をインストールします。
    - [Chrome Web Store](https://chrome.google.com/webstore/detail/ublacklist/pncfbmialoiaghdehhbnbhkkgmjanfhe)
    - [Firefox Add-ons](https://addons.mozilla.org/en-US/firefox/addon/ublacklist/)
    - [Apple App Store](https://apps.apple.com/jp/app/ublacklist-for-safari/id1547912640)

2. Open the uBlacklist configuration, and then click "Add a subscription".<br>uBlacklist の設定を開き、"Add a subscription"
   をクリックします。

3. Add `https://raw.githubusercontent.com/exoego/ublacklist-scam-net-shops/master/uBlacklist.txt` in the dialog.<br>
   ダイアログに `https://raw.githubusercontent.com/exoego/ublacklist-scam-net-shops/master/uBlacklist.txt` を追加します。

## Contribution

Check [CONTRIBUTING.md](CONTRIBUTING.md)
and [add new entries to the bottom of this file](https://github.com/exoego/ublacklist-scam-net-shops/edit/master/source.txt).

## Acknowledgements

- [irotate/uBlacklist](https://github.com/iorate/uBlacklist) for the exceptional browser extension
- [消費者庁 悪質な海外ウェブサイト一蘭](https://www.caa.go.jp/policies/policy/consumer_research/international_affairs/assets/consumer_research_cms209_230224_01.pdf)
- [楽天市場 「楽天を装ったWEBサイト」一覧](https://ichiba.faq.rakuten.net/detail/000009756)

## License

[Creative Commons Zero v1.0 Universal](LICENSE)
