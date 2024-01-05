# レジュメ

## プロフィール

```
{
  "name"         : "Toshimitsu Mizutani",
  "age"          : 32,
  "capabilities" : ["Ruby on Rails", "NLP", "HTML/CSS", "Vue.js"],
  "hobbies"      : ["音楽", "バンド", "ドラム", "漫画", "登山", "二郎"]
}
```

自然言語処理(NLP)とWebアプリケーション開発の２足の草鞋を履くシステムエンジニアです。

2014年卒で生命保険系SIerに入社。業務システムの開発・プロジェクトマネージャーを経てR＆D部門に異動。R＆D部門ではAI・主に自然言語処理領域の実証実験をリード。
新規事業企画のためのMVP構築をCTO相当の立場で遂行。

2020年から副業で、SaaS開発企業にジョイン。申請WFの電子化や、インフラ・言語のバージョンアップ対応に従事。

---

## 経歴

### 副業:猟師向けSaaS開発企業（2020-10〜現在）
- Web系エンジニア
  - 技術: Ruby, Ruby on Rails, JQuery, Bootstrap, PostgreSQL, Heroku,　AWS (S3)
- 帳票・申請ワークフローの電子化:
  - 捕獲情報を元にしたWeb帳票を作成し、行政手続きのワークフローを電子化することにより、ジビエ処理施設の手続きが効率化。
- 言語・フレームワーク、インフラのマイグレーション:
  - Herokuの保守切れに伴い、Heroku Stack・Ruby・Railsのマイグレーションを実施することにより、アプリケーションのセキュリティが向上。
  - Bootstrap3の保守切れに伴い、Bootstrap5にバージョンアップすることにより、UI/UXが向上。
      
### 生命保険系SIer（2014-04〜現在）
#### 新規事業の企画、先端技術のリサーチ/検証（PoC）(2020-04〜現在) 
  - AI・自然言語処理の業務適用の検証:
    - BERTを用いたQAアプリケーションの構築(2021):
      - 技術: Flask, ElasticSearch, Pytorch, Huggingface, BERT, Azure (Virtual Machines)
      - QA業務の効率化のために、BERTによるトピック分類および、ベクトル検索によるFAQとドキュメント検索アプリケーションを構築した。
      - BERTのファインチューニングはAzure VMのGPUで実施。推論サーバーもAzure VMに構築し、FlaskのAPI経由で推論を行う。
      - 最終的な精度は80%以上を達成。トピック分類タスクのファインチューニングモデルを利用することにより、ベクトル検索の精度が向上することを検証した。
  
    - LangChainを用いたQAアプリケーション/報告書要約アプリの構築(2023)
      - 技術: Streamlit, LangChain, Azure (App Service, OpenAI, Cognitive Search), Docker
      - QA業務の効率化のために、LLM (AOAI)によるRAGのアプリケーションを構築。報告書要約業務の効率化のために、LLMによる報告書要約アプリを構築した。

  - 事業企画のためのMVBの構築
    - MVP （Minimum Viable Product）構築(2022)
      - 技術: Vue.js, Azure Functions (Node.js), CosmosDB, Firebase
      - 男性向け健康サービスのフィージビリティ検証のためのWebアプリケーション構築を実施。
      - CTO相当の立場で技術の選定からMVPの構築までを担当し、3ヶ月間で100人の社内ユーザーが利用。現在構築したLPを元に、協業先の企業を募集中。
      - 次ステップでは社外ユーザー向けのビジネス検証を行い、結果次第で本番ローンチ見込み。

#### ホールセール領域の業務システム開発（2014-04〜2020-03）
  - 保険金支払ワークフローシステム開発:
    - 60人月規模のプロジェクトのマネジメントを担当。
    - 技術: VB.Net, SQLServer
   
### 趣味:バンドのホームページ開発
- [OLDTIMER - Official](https://oldtimer-official.netlify.app/)
  - 技術: Vue.js, microCMS, Netlify, Netlify Functions (Node.js, Bootstrap

---

## 学歴

### 早稲田大学文化構想学部（2010-04〜2014-03）
### 早稲田大学高等学院（2007-04〜2010-03）

---

## スキル

### 主要スキル
- **Webアプリケーション開発**:
  - 言語: **Ruby**, **Python**, VB.Net
  - フレームワーク: **Ruby on Rails**, Flask, .NET Framework
  - フロントエンド: HTML/CSS, **JavaScript**, **Vue.js**, JQuery, Bootstrap
  - コンテンツ管理: microCMS
- **自然言語処理 (NLP)**:
  - 言語: Python
  - フレームワーク: Flask
  - ライブラリ: Pytorch, TensorFlow, Huggingface (BERT), LangChain, Streamlit

### プログラミング言語
- Ruby
- Python
- JavaScript
- VB.Net

### データベース
- PostgreSQL
- CosmosDB
- SQLServer

### クラウドとインフラ
- Azure: Virtual Machines, App Service, Database, Container Registry, Functions (Node.js), Blob Storage, OpenAI, Cognitive Search
- AWS: Lambda, DynamoDB, S3
- デプロイメントとCI/CD: Heroku, Netlify
- コンテナ技術: Docker

### AI/ML
- QAシステム構築、分類・固有表現抽出モデル構築

### プロジェクト管理とコミュニケーション
- GitLab, GitHub
- Microsoft Teams, Slack
- Jira, Trello
- Miro

---

## やりたいこと
- スピード感のある環境で、ユーザー中心のアプリケーション開発に携わりたいです。事業やプロダクトにも興味があるため、戦略的な意思決定にも積極的に携わっていきたいです。
- 将来的には、プロダクトマネジメントの役割を担い、技術とビジネスを橋渡しするポジションを目指します。

---

## メディア出版物
- [秘密計算技術の活用](https://www.dlri.co.jp/report/ld/174276.html) - 第一生命経済研究所, 2021年10月20日
- [データ活用次の一手～差分プライバシーで攻めのプライバシー保護を～](https://www.dlri.co.jp/report/ld/232558.html) - 第一生命経済研究所, 2023年1月30日

---

## 興味のある領域
- フロントエンド: TypeScript, React/Next.js, Prisma
- プライバシー強化技術: 合成データ、差分プライバシー、秘密計算
- 生成AI: GitHub Copilot

---

## その他触ったことのある技術
- データ分析: Tableau Desktop
- フロントエンド: React, Tailwind
- ブロックチェーン技術: HyperLedger Fabric, Corda (Kotlin)
- 検索エンジン: Elasticsearch
- GCP: CCAI, Dialogflow
