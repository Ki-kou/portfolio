# ポートフォリオ簡易説明
1. ninリポジトリ
- 任天堂hpから、セールになっているソフトをスクレイピングし、PostgreSQLに格納する。
2. polrfolioリポジトリ.
- line-chat-bot-apiを用い、以下のQRコードから友達登録することで、requestを送ることができるようになり、
送られてきたrequestが1でスクレイピングしたデータの中にあれば"セール中です"のメッセージが届く。
# 使用した技術
python3,postgresql,heroku,flask
# 工夫した点
任天堂のセールのソフトは一日に一回、更新されるため、herokuにデプロイしたninリポジトリ内のmain.pyファイルを1日に一回、定期的に実行するようにしている。
# 改善点
現在の使用では、スクレイピングしたソフトそのままの名前をline-chat-botで送る必要がある。 (例)○ポケットモンスター ブリリアントダイヤモンド　×ダイパリメイク



![image](https://user-images.githubusercontent.com/78373206/150530521-7327e65d-8d19-4fff-9e2e-4ffada03f6f9.png)
