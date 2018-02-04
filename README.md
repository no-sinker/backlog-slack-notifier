# backlog-slack-notifier

Backlog 上の活動を Slack に通知する AWS Lambda function。

ほぼ https://qiita.com/kosuge/items/051922673cf57203f8db の記事の通り
だが一部環境に合わせて修正してある。

AWS Lambda に登録するときには、以下の環境変数を設定すること。

* BOTNAME Slack 上に表示される bot 名。
* BASEURL Slack のスペース URL。
* WEBHOOKURI Slack を Webhook で連携させる URI

