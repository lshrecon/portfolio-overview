# 李 丞燻（イ・スンフン）｜制作・データ分析ポートフォリオ

[한국어](README.ko.md) · [画面で見るポートフォリオ](https://seunghun-data-portfolio.lsrrokmv.chatgpt.site/) · [生成AIを活用した制作記録](docs/ai-development-process.md)

身近な課題を要件に整理し、生成AIを使った制作と、Python・SQL・Power BIによるデータ分析・検証を組み合わせています。ここでは全12件の制作・分析・学習記録と、使用データ・処理の流れ・確認結果を案内します。

## 最初に見ていただきたい4件

| プロジェクト | 作ったもの・本人の担当 | 確認できる資料 |
|---|---|---|
| **BassLab** | 基礎練習と演奏の振り返りをつなぐ個人アプリ。課題設定・要件・操作の流れ・実際の動作確認を行い、コードの実装は生成AIに依頼。 | [実画面・開発の経緯](https://seunghun-data-portfolio.lsrrokmv.chatgpt.site/works/basslab.html) / [制作記録](docs/ai-development-process.md#basslab) |
| **金融ニュースRAG** | ニュース検索・ETF価格計算・説明を分けた個人プロジェクト。2025年に目的設定・収集・設計・実装・確認・発表まで一人で進め、生成AIを活用。 | [使用データと処理フロー](https://seunghun-data-portfolio.lsrrokmv.chatgpt.site/works/financial-rag.html#materials) / [現在の実行結果](https://seunghun-data-portfolio.lsrrokmv.chatgpt.site/results/financial-rag.html) |
| **財務指標ML・SQL** | PER・PBR等の特徴量設計、分類実験、株価表のSQL向け変換。学部での作業と2026年のAI支援による再評価・再実行を分けて掲載。 | [分析過程](https://seunghun-data-portfolio.lsrrokmv.chatgpt.site/works/financial-ml.html) / [指標・SQL照合](https://seunghun-data-portfolio.lsrrokmv.chatgpt.site/results/ml-sql.html) |
| **経営シミュレーションBI** | チーム授業で、8回分の結果を202行に整理しPower BIで最終発表用に可視化。前処理・BI制作と、見本を使った分担・進捗確認を担当。 | [入力例・按分・発表動画](https://seunghun-data-portfolio.lsrrokmv.chatgpt.site/works/business-simulation-bi.html) |

### BassLabの実際の画面

![BassLabのスコア入力画面](assets/basslab/score-editor.png)

① 曲名とテンポを設定 → ② リズム・弦・フレットを入力 → ③ 保存した楽譜を練習・録音につなぎます。アプリ本体の画面は韓国語です。

[基礎練習の画面](assets/basslab/training.png) · [録音結果の画面](assets/basslab/recording-results.png) · [制作・動作確認の記録](docs/ai-development-process.md)

## 使用データから結果まで

| プロジェクト | 入力 → 処理 → 結果 |
|---|---|
| BassLab | 楽譜JSON・録音 → 予定時刻と音の候補の対応 → 確認する区間を聴き直す |
| 金融ニュースRAG | ニュースの要約・ETF価格 → 検索・並べ替え・銘柄と日付の対応・変化率計算 → 出典付きレポート |
| 財務指標ML・SQL | 財務表・調整後株価 → 前処理・逆数等の特徴量・分類・比較 → 指標と元データをたどれる評価表 |
| 経営シミュレーションBI | 第0〜7期の結果レポート → 企業・ブランド・市場・期の共通表、販売比率による按分 → Power BI・発表動画 |

[データの実例・コード／数式・結果をまとめて見る](https://seunghun-data-portfolio.lsrrokmv.chatgpt.site/examples.html)

現在公開しているRAGの検索・価格結果は、2026年に生成AIの支援で保存データから再実行したものです。この実行ではLLMを呼び出していません。制作当初のLLM構成と、別入力のAI試験は詳細ページで分けています。

MLの2026年再評価（検証2,973件）では、ランダムフォレストの正解率55.36%は、常に上がらないと予測する基準55.87%を下回りました。バランス精度は55.71%対50%です。事前の上昇F1基準では常に上昇とする予測が選ばれました。

## 全12件の制作・分析・学習記録

| 取り組み | 制作の性格・本人の役割 |
|---|---|
| [BassLab · ベース練習ツール](https://seunghun-data-portfolio.lsrrokmv.chatgpt.site/works/basslab.html) | 本人：課題・要件・操作の流れ・動作確認。コード実装は生成AIを利用。 |
| [金融ニュースRAG](https://seunghun-data-portfolio.lsrrokmv.chatgpt.site/works/financial-rag.html) | 2025年に全工程を一人で制作、生成AIを活用。公開結果は2026年のAI支援による再実行。 |
| [財務指標ML・SQL](https://seunghun-data-portfolio.lsrrokmv.chatgpt.site/works/financial-ml.html) | 本人の前処理・特徴量設計・モデル実験。2026年のAI支援再評価と区別。 |
| [経営シミュレーションの可視化・Power BI](https://seunghun-data-portfolio.lsrrokmv.chatgpt.site/works/business-simulation-bi.html) | チーム授業。本人：前処理・Power BI制作、整理の見本と分担・進捗確認。 |
| [金融ニュースの固有表現認識](https://seunghun-data-portfolio.lsrrokmv.chatgpt.site/works/financial-ner.html) | 授業の例・生成AIのコードを基にした実習。本人：タグ設計・ラベル付け。 |
| [ETFモメンタムのバックテストパイプライン](https://seunghun-data-portfolio.lsrrokmv.chatgpt.site/works/quant-pipeline.html) | ETFの価格処理、スコア計算、保有・売買記録をつなぐ個人実装。 |
| [株価データの整形・MySQLへのロード](https://seunghun-data-portfolio.lsrrokmv.chatgpt.site/works/stock-etl.html) | 本人の株価表変換・SQL処理。掲載するロード・照合記録は2026年の再実行。 |
| [資産配分戦略の実装実験](https://seunghun-data-portfolio.lsrrokmv.chatgpt.site/works/asset-allocation.html) | 学習実験。乱数データ、リバランス条件、初期11か月の未来参照の問題を明示。 |
| [株価・財務データ収集ツール](https://seunghun-data-portfolio.lsrrokmv.chatgpt.site/works/stock-collection.html) | オンライン資料を参考にした収集・データベース構成の実習。 |
| [Aショッピングの顧客行動統計分析](https://seunghun-data-portfolio.lsrrokmv.chatgpt.site/works/ashopping.html) | 授業のデータを使った顧客行動の統計分析課題。 |
| [Docker・Kubernetesのデプロイ基礎](https://seunghun-data-portfolio.lsrrokmv.chatgpt.site/works/docker-k8s.html) | 講義を基にしたコンテナ・デプロイの実習。 |
| [コーディング問題演習・プログラミング学習](https://seunghun-data-portfolio.lsrrokmv.chatgpt.site/works/coding-study.html) | プログラミングと問題演習の学習記録。 |

## ソースコードの公開状況

以下は以前に公開したコードの抜粋です。現在のアプリ全体や2026年の全再検証コードと同一の版ではありません。現在の画面・入力例・結果は、上の各プロジェクトページを参照してください。

- [BassLabの以前のコード抜粋](https://github.com/lshrecon/basslab-portfolio)
- [金融ニュースRAGの以前のコード抜粋](https://github.com/lshrecon/financial-news-rag-portfolio)
- [財務指標ML・SQLの以前のコード抜粋](https://github.com/lshrecon/financial-ml-sql-portfolio)

このリポジトリは作品一覧と制作記録を整理した資料です。2026年10月21日更新。公開済み資料の参照先は [sources.json](sources.json) に記載しています。
