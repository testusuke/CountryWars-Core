# CountryWars-Core
## 概要
CountryWarsサーバーで使用するコアプラグインです。
## 開発環境
- Intellij IDEA 2020.2
- JDK 1.8
- Kotlin 1.3.72
- Gradle 6.1.1
- Paper 1.16.1
## コミットメッセージ
| Prefix | 意味 |
| --- | --- |
| fix | バグ修正 |
| create | 新規作成・新規ファイル追加 |
| add | コードの追加 |
| change | 機能修正 |
| clean | 整理 |
| disable | 無効化(コメントアウトなど) |
| remove | コードの削除 |
| delete | ファイル削除 |
| rename | ファイル名変更 |
| move | 移動 |
| debug | デバッグでのコード追加・削除 |  
上記のPrefixを[]で囲み、コミットメッセージの接頭辞にしてください。
## ブランチ利用
開発はdevelopブランチから新規でブランチを作成し、開発が完了したらdevelopブランチにマージしてください。
developブランチにpushされるとデバッグサーバーへ自動ビルドされ反映されます。(未実装)
masterブランチは完成後にマージしてください。