# Tera Term向けマクロ
- 1台に複数のグローバルIPを割り当てる為にSquidConfigを書き換えるマクロ
  - [ref](https://meetup-jp.toast.com/2558)

## 使い方
- `pemファイル`を同じディレクトリに配置する
- `SquidConfSetup.ttl`をメモ帳などで開き、IPアドレスを接続対象のインスタンスのFloatingIPを指定する
- Tera Termからマクロを実行する