# Data Analysis Platform
## 概要
本GitProjectは、データ収集および分析、可視化が可能な分析基盤のプロトタイプを目的として作成している。
本GitProjectでは、AWSサービスを用いることで上記の環境をサーバーレスで構築する。
以下に本プロジェクトの特徴をまとめる。また本Projectのソースコードはブループリント

### 分析基盤の特徴

1. SQLエンジニア
2. Pythonエンジニア
3. 機械学習エンジニア
がそれぞれの手法でETLを開発し分析データを容易に作成出来る環境を目指す。

### 収集環境の特徴
本プロジェクトではデータソースとして以下を想定している。

1. Webスクレイピング
2. 公開DBのレプリケーション
3. IoT機器のログデータ

### 可視化環境の特徴
可視化にBIツールを用いる。BIツールとしては以下の２つを検討中。

1. QuickSite
2. TableauServer

## アーキテクト


## プロジェクトの構成

```bash
.
├── README.md
├── cfn  # CloudFormation
│   ├── database.template.yaml
│   ├── elb.template.yaml
│   ├── glue-job.template.yaml
│   └── role.template.yaml
├── src # ETL用のスクリプト
│   ├── athena_sql
│   ├── glue_job
│   ├── lamda_job
│   └── lib
└── test_data # テストデータ
```

## S3の構成
```bash

```

## ジョブのDeploy方法

## データベースのDeploy方法

## テストデータのDeploy方法
