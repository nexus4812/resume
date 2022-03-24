## nexus4812/resume
[職務経歴書](https://github.com/nexus4812/resume/blob/main/resume/README.pdf) とその生成ツール

### 使い方
1. resume/readme.mdを編集してcommitとpushする
2. CI上で自動で自動的にresume.pdfが生成される

ローカルにGit環境がなくても、ブラウザ経由で編集とPDFの生成が可能

### ローカルで生成したい場合
```shell
$ node -v
v14.16.0

$ npm i # 初期設定

$ npm run build # mdファイルから職務経歴書を生成する
$ npm run dev # 作成途中の職務経歴書を確認する
```
