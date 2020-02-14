# Upload Google Cloud Storage by Github Actions
## 概要
Github Actionsの成果物をGoogle Cloud Storageにアップロードする
例としてJestのテスト生成物である、カバレッジのバッジをアップロードするケースを想定

## google-cloud-platform-gcp-cli-gcloud
### gsutilコマンドの使用
GCP CLIのcpコマンドを仕様するために、下記のGithub Actionsを使用する
https://github.com/marketplace/actions/google-cloud-platform-gcp-cli-gcloud

### gsutilコマンドDoc
https://cloud.google.com/storage/docs/gsutil/commands/cp?hl=ja
