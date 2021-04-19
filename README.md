# devenvs
開発環境用設定ファイル類を管理するリポジトリ

## 使用方法
### vscodeを起動する前に
1. .code-workspaceファイルをrenameする。

### vscode起動後
1. 設定値の変更
    - docker-compose.yml  
    services名を変更
    - .devcontainer\docker-compose.yml  
    service名を変更
    - .devcontainer\devcontainer.json  
    nameを変更  
    service名を変更
    - vetur.config.js  
    vuejsのrootディレクトリを変更

### トラブルシューティング
1. vue-cli-service: not foundと言われる場合  
以下コマンドを実行する
    ```
    rm -rf node_modules package-lock.json && npm install
    ```
