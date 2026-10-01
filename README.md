# saran 体験デモ

商談の場で見込み客に触ってもらうためのデモページ。

- 公開URL: https://demo.saran-cloud.com/
- 中身は `index.html` 1枚だけ（他のファイルに依存しない）

## 直し方

`index.html` を書き換えて、このフォルダで次を実行すると数分で公開に反映される。

```
git add -A
git commit -m "内容を更新"
git push
```

## 直すことが多い場所

| 直したいもの | 探す文字列 |
| --- | --- |
| 草刈りの単価・最低料金 | `RATE_FLAT` `RATE_SLOPE` `DISPOSAL` `MIN_TOTAL` |
| 配送料の距離帯・積載量 | `bandOf` `PER_LOAD` |
| 連絡先（今はプレースホルダ） | `ご相談の連絡先は、この行を書き換えて` |

単価はすべて説明用のサンプル。商談相手の業種に合わせて入れ替える。
