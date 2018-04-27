# プログラミング言語matsumu-lang
この言語は、サポーターズのさりーさんをネタにした言語です。

# 仕様
- わびに肉奢るわ -> ポインタを１進める
- オッスオラ元ツイ廃！ -> ポインタの指す要素の値を１増やす
- かーたーさんばいばーい -> ポインタを１戻す
- ワロタｗｗｗｗｗｗｗｗｗｗｗｗｗｗｗ -> ポインタの指す要素の値を１減らす
- 焼肉するかぁ -> ポインタの指す要素の値が 0 だったら対応する次の 焼肉するかぁ までジャンプ
- アラサーが調子に乗ってごめんな… -> 対応する前の 焼肉するかぁ までジャンプ
- まだ若いもん！！！！ -> ポインタの指す要素の値を外に出力
- こんなの絶対おかしいよ -> 外から値を入力して、 ポインタの指す場所へ入れる

# サンプル
## matumura.sari
```

わびに肉奢るわオッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！焼肉するかぁかーたーさんばいばーいオッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！わびに肉奢るわワロタｗｗｗｗｗｗｗｗｗｗｗｗｗｗｗアラサーが調子に乗ってごめんな…かーたーさんばいばーいまだ若いもん！！！！わびに肉奢るわオッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！焼肉するかぁかーたーさんばいばーいオッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！わびに肉奢るわワロタｗｗｗｗｗｗｗｗｗｗｗｗｗｗｗアラサーが調子に乗ってごめんな…かーたーさんばいばーいオッスオラ元ツイ廃！まだ若いもん！！！！オッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！まだ若いもん！！！！まだ若いもん！！！！オッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！まだ若いもん！！！！焼肉するかぁワロタｗｗｗｗｗｗｗｗｗｗｗｗｗｗｗアラサーが調子に乗ってごめんな…わびに肉奢るわオッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！焼肉するかぁかーたーさんばいばーいオッスオラ元ツイ廃！オッスオラ元ツイ廃！
オッスオラ元ツイ廃！オッスオラ元ツイ廃！わびに肉奢るわワロタｗｗｗｗｗｗｗｗｗｗｗｗｗｗｗアラサーが調子に乗ってごめんな…かーたーさんばいばーいまだ若いもん！！！！わびに肉奢るわオッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！焼肉するかぁかーたーさんばいばーいオッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！わびに肉奢るわワロタｗｗｗｗｗｗｗｗｗｗｗｗｗｗｗアラサーが調子に乗ってごめんな…かーたーさんばいばーいまだ若いもん！！！！わびに肉奢るわオッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！焼肉するかぁかーたーさんばいばーいオッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！わびに肉奢るわワロタｗｗｗｗｗｗｗｗｗｗｗｗｗｗｗアラサーが調子に乗ってごめんな…かーたーさんばいばーいまだ若いもん！！！！オッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！まだ若いもん！！！！ワロタｗｗｗｗｗｗｗｗｗｗｗｗｗｗｗワロタｗｗｗｗｗｗｗｗｗｗｗｗｗｗｗワロタｗｗｗｗｗｗｗｗｗｗｗｗｗｗｗワロタｗｗｗｗｗｗｗｗｗｗｗｗｗｗｗワロタｗｗｗｗｗｗｗｗｗｗｗｗｗｗｗワロタｗｗｗｗｗｗｗｗｗｗｗｗｗｗｗまだ若いもん！！！！ワロタｗｗｗｗｗｗｗｗｗｗｗｗｗｗｗワロタｗｗｗｗｗｗｗｗｗｗｗｗｗｗｗワロタｗｗｗｗｗｗｗｗｗｗｗｗｗｗｗワロタｗｗｗｗｗｗｗｗｗｗｗｗｗｗｗワロタｗｗｗｗｗｗｗｗｗｗｗｗｗｗｗワロタｗｗｗｗｗｗｗｗｗｗｗｗｗｗｗワロタｗｗｗｗｗｗｗｗｗｗｗｗｗｗｗワロタｗｗｗｗｗｗｗｗｗｗｗｗｗｗｗまだ若いもん！！！！焼肉するかぁワロタｗｗｗｗｗｗｗｗｗｗｗｗｗｗｗアラサーが調子に乗ってごめんな…わびに肉奢るわ
オッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！焼肉するかぁかーたーさんばいばーいオッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！わびに肉奢るわワロタｗｗｗｗｗｗｗｗｗｗｗｗｗｗｗアラサーが調子に乗ってごめんな…かーたーさんばいばーいオッスオラ元ツイ廃！まだ若いもん！！！！焼肉するかぁワロタｗｗｗｗｗｗｗｗｗｗｗｗｗｗｗアラサーが調子に乗ってごめんな…オッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！オッスオラ元ツイ廃！まだ若いもん！！！！
```
## 実行
```
./matsumura matumura.sari
```
## 結果
```
Hello World!
```
