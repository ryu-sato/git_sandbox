## このリポジトリについて

- git 操作練習用

## branch 戦略

### branch

1. main
1. staging
1. production

### 開発フロー

- 開発用ブランチを作成したら、1. main, 2. staging, 3. production の順にマージする
    - ブランチは production から派生させる
    - ブランチは流用する
- production branch にマージされた内容は production branch から staging branch へ、staging branch から main branch へと backport する
