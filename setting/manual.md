# manual

#### ①キーボードのkeycodeを知る

```
xev
```
#### ②現在紐づいているkeycode設定を出力

```
xmod -pke > .xmodmap
```

#### ③変更したいものを洗い出し整理した.xmodmapと同じ形式のファイルを作成

#### ④設定を反映させる
※現状の問題：.profileに下記を追記したが再起動後、リセットされてしまう

```
xmodmap ~/.xmodmap
```
