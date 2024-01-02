# トーストクロック

一定時間ごとにポップアップで現在時刻を表示するアプリ

![screenshot](docs/images/toast-clock.png)

----

## 設定

### コマンドライン引数

```sh
toast-clock [M]
```

- **M**: ポップアップ間隔を分単位で指定する (省略時: 30)
    - 例: `toast-clock 15` なら15分間隔でポップアップが表示される

## 付録: 自動起動

[Windowsのスタートアップ](https://support.microsoft.com/ja-jp/windows/150da165-dcd9-7230-517b-cf3c295d89dd) やタスクスケジューラを使って自動で起動するように設定すると便利です
