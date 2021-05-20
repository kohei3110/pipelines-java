[![Build Status](https://dev.azure.com/koheisaito/Demo/_apis/build/status/kohei3110.pipelines-java?branchName=master)](https://dev.azure.com/koheisaito/Demo/_build/latest?definitionId=1&branchName=master)

# Azure DevOps Tutorial

## Fork the following repository to your GitHub account
https://github.com/MicrosoftDocs/pipelines-java

## Create a new Java pipeline
1. Azure DevOps 組織にサインインし、プロジェクトに移動する。
2. プロジェクト内で、「パイプライン」ページに移動する。
3. ソースコードの場所として、GitHub を選択する。
4. サインイン画面に遷移するので、認証情報を入力する。
5. リポジトリの一覧が表示されたら、対象となるアプリケーションのリポジトリを選択する。
6. Azure Pipeline によってリポジトリが分析される。上記のサンプルリポジトリは、Maven パイプラインテンプレートが推奨される。<br>
   [Save and run]を選択し、適宜 Commit message を入力する。[Commit directly to the master branch]を選択し、[Save and run]を選択する。
   パイプラインは、プロジェクトのルートに作成される `azure-pipelines.yml` にて定義する。

## Add a status badge to the repository
1. Azure Pipelines で、[Pipeline]ページにアクセスし、パイプラインの一覧を表示する。前のセクションで作成したパイプラインを選択する。
2. パイプラインのコンテキストメニューで、[Status badge]を選択する。
3. サンプルマークダウンが表示されるので、コピーする。
