# 職務経歴 (Shouya Higuchi)

## 概要
- フロントエンドエンジニア経験: 2〜3年
- バックエンドエンジニア経験: 3〜4年
- プロダクトマネージャー経験: 1〜2年
- ディレクション経験: 2~3年（PM/ディレクション含む）

| 期間 | 企業 | 役割 | 概要 |
|:--|:--|:--|:--|
| 2025.09 - 現在 | アセンド株式会社 | プロダクトエンジニア | 物流SaaS / 労務管理ドメイン |
| 2024.08 - 2025.08 | 株式会社X Mile | プロダクトオーナー | 運送業 Vertical SaaS |
| 2022.01 - 2024.07 | 株式会社インディバース | テックリード | アフィリエイト分析SaaS |
| 2021.05 - 2023.10 | フリーランス | フルスタックエンジニア | SaaS開発の業務委託 |
| 2018.03 - 2021.05 | 株式会社div | PM / ディレクター | eラーニング教材 |

## スキル

### Backend
<p>
  <img src="https://img.shields.io/badge/Ruby-CC342D?style=for-the-badge&logo=ruby&logoColor=white" alt="Ruby" />
  <img src="https://img.shields.io/badge/Ruby_on_Rails-CC0000?style=for-the-badge&logo=rubyonrails&logoColor=white" alt="Ruby on Rails" />
  <img src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express" />
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white" alt="Prisma" />
</p>

### Frontend
<p>
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React Native" />
</p>

### Infrastructure & Others
<p>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white" alt="AWS" />
  <img src="https://img.shields.io/badge/Heroku-430098?style=for-the-badge&logo=heroku&logoColor=white" alt="Heroku" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" alt="Firebase" />
  <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
</p>

<p>
  <img src="https://img.shields.io/badge/Ruby_on_Rails-CC0000?style=for-the-badge&logo=ruby-on-rails&logoColor=white" alt="Rails" />
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white" alt="AWS" />
</p>

## 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=shouya31&show_icons=true&hide_border=true&line_height=24" alt="Shouya's GitHub Stats" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=shouya31&hide_border=true" alt="GitHub Streak" />
</div>


---

## 職歴

### アセンド株式会社 (2025年09月 - 現在)
**役割:** プロダクトエンジニア

**事業内容:** 物流業界向けマルチテナントSaaS（労務管理ドメイン）

**利用技術:** TypeScript, React, Next.js, Express, PostgreSQL, Prisma, AWS（EC2, ECS, CloudWatch, IAM）

**開発環境:** モノレポ構成 / デプロイ基盤: Kubernetes, Argo CD

**主な業務・実績:**
- **SaaSドメインモデリングとフルスタック開発:**
  - 労務関連法規や業界固有の監査基準をエンティティ化し、DDDに基づくレイヤードアーキテクチャにてDB設計からAPI、UIまでを一貫して実装。
  - 台帳管理機能をゼロから設計・リリース（Prismaマイグレーション、CRUD API、React一覧画面・ドロワーの実装、監査要件の不備自動判定機能の構築）。
- **複雑な業務ロジックのアルゴリズム設計とテスト実装:**
  - 労働時間規制に基づく違反検出アルゴリズムを設計・実装。
  - 区間またぎのバグ修正、境界値を含む網羅的なテストケースの整備を実施。検出結果を集計APIおよびUI（指標列、ハイライト、ドロワー）へ統合。
- **フロントエンドアーキテクチャ設計・パフォーマンスチューニング:**
  - Feature-Sliced Designを導入し、依存関係の構造化とアーキテクチャ境界の自動検証環境を構築。
  - レンダリングの安定化・パフォーマンス改善を実施。
- **段階的リリース制御・データ連携基盤構築:**
  - FeatureFlagを利用したテナント単位の段階的リリースを設計し、既存ユーザーへの影響を制御（3機能以上で運用）。
  - テナント固有のCSVフォーマットに対応するインポート基盤を構築。トランザクション制御とユニーク制約によりデータ整合性を担保。
- **技術的負債の計画的な解消:**
  - フロントエンド・バックエンド横断でバリデーションライブラリの移行（YupからZodへ）を実施し、チーム展開用の移行パターンを標準化。
  - 適切なHTTPステータスコードへの変換やUIのエラー境界（Error Boundary）整備など、エラーハンドリングを体系化。

### 株式会社X Mile (2024年08月 - 2025年07月)
**役割:** プロダクトオーナー (マネージャー)

**事業内容:** 運送業 Vertical SaaS

**チーム規模:** 10-50人 (業務委託エンジニア15名、PO3名体制)

**利用技術:** AWS, Docker, Ruby on Rails, TypeScript, React

**主な業務・実績:**
- **エンタープライズ向けSaaS開発とプロジェクト推進:** 大企業からの受注に伴い、要件定義および各ステークホルダーとの合意形成を行い、開発からリリースまでを管理。
- **アーキテクチャ設計とドキュメント化:** 要件定義書、ADRの作成、および仕様面のコードレビューを実施。
- **開発組織の立ち上げ:** 開発生産性と品質課題の解決に向け、スクラム開発体制およびQA組織の立ち上げを主導。

### 株式会社インディバース (2022年01月 - 2024年07月)
**役割:** フルスタックエンジニア / テックリード（社員1人目エンジニア）

**事業内容:** アフィリエイト向け分析サービス

**チーム規模:** 1-10人

**利用技術:** Ruby on Rails, TypeScript, React, JavaScript, Docker, Heroku, Firebase

**主な業務・実績:**
- **SaaSアーキテクチャへの移行（マルチテナント化）:** クローズド版からSaaSへの移行にあたり、テーブルにテナント識別カラムを持たせた行単位制御によるマルチテナント化を自ら設計・実装。
- **フロントエンドの刷新とUX改善:** ReactおよびTypeScriptを導入し、チャートを用いた直感的な分析機能を新規開発。
- **インフラのパフォーマンスチューニング:** ユーザー増加に伴うバックグラウンドジョブの処理遅延に対し、Redisサーバーのスケールアウトを実施し、処理の安定化を実現。
- **監視体制の構築:** リリース後の継続的な運用に向け、SentryやDatadogを導入し、システムフェイル時の通知フローを設計・実装。
- **技術的負債の解消とチーム開発環境の整備:** 外部エンジニアの参画に向け、頻出箇所を中心にコードのリファクタリングを実施し、ドメイン知識がなくても開発に着手できる環境を整備。

### フリーランス / 業務委託 (2021年05月 - 2023年10月)
※ 株式会社インディバースとの兼業期間あり（2022年01月〜2023年10月）
**役割:** フルスタックエンジニア

**参画先:** freee株式会社（旧Why株式会社）、株式会社ジンジャーアップなど

**チーム規模:** 1-10人

**利用技術:** Ruby on Rails, TypeScript, React

**主な業務・実績:**
- SaaSアカウント管理の自動化ツールにおいて、フロントエンドおよびバックエンドの設計・実装を担当。Ruby on RailsによるAPI開発とReactによる管理画面の構築を遂行。

### 株式会社div (2018年03月 - 2021年05月)
**役割:** プロジェクトマネージャー

**事業内容:** プログラミング教材の作成・運用

**チーム規模:** 10-50人

**主な業務・実績:**
- eラーニングプロダクトにおけるサービスコンテンツ制作、サービス企画、プラットフォーム改修のディレクションを担当。
- 新規教育事業のサービスコンテンツ制作、オペレーション責任者を担当。
