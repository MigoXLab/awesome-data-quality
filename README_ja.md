# Awesome Data Quality [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

データ品質に関する様々なデータタイプにわたる素晴らしいリソース、ツール、論文、プロジェクトの厳選リスト。このリポジトリは、異なる領域でデータ品質に取り組む研究者や実務者のための包括的なリファレンスを目指しています。

## 目次

- [はじめに](#はじめに)
- [従来データ](#従来データ)
  - [論文](#論文)
  - [ツール・プロジェクト](#ツールプロジェクト)
  - [データ準備度評価](#データ準備度評価)
- [大規模言語モデルデータ](#大規模言語モデルデータ)
  - [事前訓練データ](#事前訓練データ)
  - [ファインチューニングデータ](#ファインチューニングデータ)
  - [LLMデータ管理](#llmデータ管理)
  - [認知工学・テスト時スケーリング](#認知工学テスト時スケーリング)
- [マルチモーダルデータ](#マルチモーダルデータ)
  - [論文](#論文-1)
  - [ツール・プロジェクト](#ツールプロジェクト-1)
- [表形式データ](#表形式データ)
  - [論文](#論文-2)
  - [ツール・プロジェクト](#ツールプロジェクト-2)
- [時系列データ](#時系列データ)
  - [論文](#論文-3)
  - [ツール・プロジェクト](#ツールプロジェクト-3)
- [グラフデータ](#グラフデータ)
  - [論文](#論文-4)
  - [ツール・プロジェクト](#ツールプロジェクト-4)
- [データ中心AI](#データ中心ai)
  - [サーベイ](#サーベイ)
  - [データ評価](#データ評価)
  - [データ選択](#データ選択)
  - [ベンチマーク](#ベンチマーク)

## はじめに

データ品質は、あらゆるデータ駆動型アプリケーションや研究の重要な側面です。このリポジトリは、従来データ、大規模言語モデルデータ（事前訓練とファインチューニングの両方）、マルチモーダルデータなど、異なるデータタイプにわたるデータ品質に関するリソースを収集しています。

## 従来データ

このセクションは、従来の構造化・非構造化データのデータ品質をカバーします。

### 論文

- [データクリーニング：問題と現在のアプローチ](https://www.researchgate.net/publication/220423285_Data_Cleaning_Problems_and_Current_Approaches) - データクリーニングアプローチの包括的概要。(2000)
- [データ品質に関する調査：劣悪データの分類](https://ieeexplore.ieee.org/document/7423672) - データ品質問題と分類に関する調査。(2016)

### ツール・プロジェクト

- [Great Expectations](https://github.com/great-expectations/great_expectations) - データの検証、文書化、プロファイリングのためのPythonフレームワーク。(2018)
- [Deequ](https://github.com/awslabs/deequ) - Apache Spark上に構築された「データのユニットテスト」を定義するためのライブラリ。(2018)
- [OpenRefine](https://openrefine.org/) - 乱雑なデータを扱い、クリーニングし、変換するための強力なツール。(2010)
- [Pandas Profiling](https://github.com/pandas-profiling/pandas-profiling) - pandas DataFrameからプロファイルレポートを生成。(2016)
- [DataProfiler](https://github.com/capitalone/DataProfiler) - 自動データプロファイリングのためのPythonライブラリ。(2021)
- [PyDeequ](https://github.com/awslabs/python-deequ) - Deequ のPython API、「データのユニットテスト」を可能に。(2020)
- [Evidently](https://github.com/evidentlyai/evidently) - データドリフト検出のためのオープンソースML監視フレームワーク。(2021)
- [TensorFlow Data Validation (TFDV)](https://www.tensorflow.org/tfx/data_validation/get_started) - 大規模でMLデータを探索・検証するライブラリ。(2018)
- [Deepchecks](https://github.com/deepchecks/deepchecks) - MLモデルとデータを検証するPythonパッケージ。(2021)

### データ準備度評価

このサブセクションは、AIアプリケーションのデータ準備度を評価する方法とツールをカバーします。

#### 論文

- [AIのためのデータ準備度：360度調査](https://arxiv.org/abs/2404.05779) - 構造化・非構造化データセットのAI訓練におけるデータ準備度評価指標を検討する包括的調査。(2024)
- [工学教育における学生の生成AI採用の評価](https://arxiv.org/abs/2503.04696) - 教育AIアプリケーションにおけるデータ品質考慮に関する実証研究。(2025)

#### ツール・プロジェクト

- [データ準備度評価フレームワーク](https://github.com/data-readiness/framework) - AIアプリケーションのデータ品質と準備度を評価するフレームワーク。(2024)
- [AIデータ品質指標](https://github.com/ai-data-quality/metrics) - AI文脈におけるデータ品質評価の標準化指標。(2024)

## 大規模言語モデルデータ

### 事前訓練データ

このセクションは、大規模言語モデル事前訓練データのデータ品質をカバーします。

#### 論文

- [The Pile：言語モデリングのための800GBの多様なテキストデータセット](https://arxiv.org/abs/2101.00027) - 言語モデル事前訓練のための大規模キュレートデータセット。(2021)
- [一目でわかる品質：ウェブクロール多言語データセットの監査](https://arxiv.org/abs/2103.12028) - ウェブクロール多言語データセットの品質監査。(2021)
- [大規模ウェブテキストコーパスの文書化：巨大クリーンクロールコーパスのケーススタディ](https://arxiv.org/abs/2104.08758) - C4データセットの文書化。(2021)
- [ウェブのリサイクル：言語モデル事前訓練データの品質と量を向上させる方法](https://arxiv.org/abs/2506.04689) - REWire手法、ガイド付きリライトを通じて低品質ウェブ文書をリサイクル・改善し、LLM事前訓練の「データの壁」問題に対処。(2025)
- [バイリンガル言語モデル訓練におけるデータ品質の役割の評価](https://arxiv.org/abs/2506.12966) - 不平等なデータ品質がバイリンガル環境でのパフォーマンス低下の主要因であることを明らかにし、多言語モデルの実用的データフィルタリング戦略を提案する研究。(2025)

#### ツール・プロジェクト

- [Dolma](https://github.com/allenai/dolma) - 大規模言語モデル事前訓練データのキュレーションと文書化のためのフレームワーク。(2023)
- [Text Data Cleaner](https://github.com/ChenghaoMou/text-data-cleaner) - 言語モデル事前訓練用テキストデータクリーニングツール。(2022)
- [CCNet](https://github.com/facebookresearch/cc_net) - CommonCrawlデータのダウンロードとフィルタリングツール。(2020)
- [Dingo](https://github.com/MigoXLab/dingo) - 複数のデータソース、タイプ、モダリティをサポートする包括的データ品質評価ツール。(2024)

### ファインチューニングデータ

このセクションは、大規模言語モデルファインチューニングデータのデータ品質をカバーします。

#### 論文

- [人間のフィードバックで指示に従うよう言語モデルを訓練](https://arxiv.org/abs/2203.02155) - AnthropicのRLHF論文。(2022)
- [量より質：データセット設計とCLIPの堅牢性の相互作用](https://arxiv.org/abs/2112.07295) - 量よりもデータ品質の重要性に関する研究。(2021)
- [機械学習タスクのためのデータ品質](https://arxiv.org/abs/2108.02711) - 機械学習のデータ品質に関する調査。(2021)

#### ツール・プロジェクト

- [LMSYS チャットボットアリーナ](https://github.com/lm-sys/FastChat) - LLMレスポンス評価プラットフォーム。(2023)
- [OpenAssistant](https://github.com/LAION-AI/Open-Assistant) - 高品質指示追従データ作成プロジェクト。(2022)
- [Argilla](https://github.com/argilla-io/argilla) - LLM用オープンソースデータキュレーションプラットフォーム。(2021)

### LLMデータ管理

このセクションは、データ処理、ストレージ、サービングを含むLLMの包括的データ管理アプローチをカバーします。

#### 論文

- [LLM × データ調査](https://arxiv.org/abs/2505.18458) - データ処理、ストレージ、サービングをカバーする大規模言語モデルのデータ中心手法に関する包括的調査。(2025)
- [パフォーマンスを損なうデータの修正：堅牢な情報検索のためのLLMカスケードによるハードネガティブの再ラベル付け](https://arxiv.org/abs/2505.16967) - モデルパフォーマンス向上のため訓練データの偽陰性を識別・再ラベル付けする手法。(2025)

#### ツール・プロジェクト

- [awesome-data-llm](https://github.com/weAIDB/awesome-data-llm) - 「LLM × データ」調査論文の公式リポジトリ、キュレートリソース付き。(2025)
- [CommonCrawl](https://commoncrawl.org/) - 多様な言語とドメインをカバーする大規模ウェブクロールデータセット。(2008)
- [RedPajama](https://github.com/togethercomputer/RedPajama-Data) - LLaMA訓練データセットのオープンソース再現。(2023)
- [FineWeb](https://huggingface.co/datasets/HuggingFaceFW/fineweb) - 言語モデル訓練のための大規模高品質ウェブデータセット。(2024)

### 認知工学・テスト時スケーリング

このセクションは、強化された推論と思考プロセスを通じてデータ品質を改善する認知工学とテスト時スケーリング手法に焦点を当てます。

#### サーベイ

- [生成AI第二幕：テスト時スケーリングが認知工学を推進](https://arxiv.org/abs/2504.13828) - テスト時スケーリングと強化学習による認知工学の包括的調査。(2025)
- [言語モデルの深い思考の解放：推論時スケーリングと強化学習による認知工学](https://gair-nlp.github.io/cognition-engineering/) - テスト時スケーリングパラダイムによるAI思考能力開発フレームワーク。(2025)

#### データエンジニアリング2.0

- [O1ジャーニー--パート1](https://github.com/GAIR-NLP/O1-Journey) - 長い思考連鎖を持つ数学推論データセット。(2024)
- [Marco-o1](https://github.com/AIDC-AI/Marco-o1) - Qwen2-7B-Instructから合成された推論データセット。(2024)
- [STILL-2](https://github.com/RUCAIBox/Slow_Thinking_with_LLMs) - 数学、コード、科学、パズル領域の長形式思考データ。(2024)
- [OpenThoughts-114k](https://github.com/open-thoughts/open-thoughts) - DeepSeek R1から抽出された大規模推論軌跡データセット。(2024)

#### 訓練データ品質

- [高影響サンプル選択](https://arxiv.org/abs/2502.11886) - 学習影響測定に基づく訓練サンプル優先順位付け手法。(2025)
- [ノイズ削減フィルタリング](https://arxiv.org/abs/2502.03373) - 汎化改善のためのノイズウェブ抽出データ除去技術。(2025)
- [長さ適応訓練](https://arxiv.org/abs/2504.05118) - 訓練データの可変長シーケンス処理アプローチ。(2024)

## マルチモーダルデータ

このセクションは、画像-テキストペア、ビデオ、オーディオを含むマルチモーダルデータのデータ品質をカバーします。

### 論文

- [LAION-5B：次世代画像-テキストモデル訓練のためのオープン大規模データセット](https://arxiv.org/abs/2210.08402) - 大規模画像-テキストペアデータセット。(2022)
- [DataComp：次世代マルチモーダルデータセットの探求](https://arxiv.org/abs/2304.14108) - データキュレーション戦略評価ベンチマーク。(2023)

### ツール・プロジェクト

- [CLIP-Benchmark](https://github.com/LAION-AI/CLIP-Benchmark) - CLIPモデル評価ベンチマーク。(2021)
- [img2dataset](https://github.com/rom1504/img2dataset) - 画像-テキストデータセットの効率的ダウンロード・処理ツール。(2021)

## 表形式データ

このセクションは、表形式データのデータ品質をカバーします。

### 論文

- [動的データ取り込みのためのデータ品質検証の自動化](https://ieeexplore.ieee.org/document/8731379) - データ品質検証自動化フレームワーク。(2019)
- [実践における機械学習のデータ品質調査](https://arxiv.org/abs/2103.05251) - 機械学習におけるデータ品質問題の調査。(2021)

### ツール・プロジェクト

- [Pandas Profiling](https://github.com/pandas-profiling/pandas-profiling) - pandas DataFrameからプロファイルレポートを生成するツール。(2016)
- [DataProfiler](https://github.com/capitalone/DataProfiler) - データプロファイリングとデータ品質検証のためのPythonライブラリ。(2021)
- [Spreadsheet Data Quality Audit - Fictional Sample](https://github.com/ja9740913/spreadsheet-data-quality-audit-sample) - 固定された架空の XLSX 入力と、機密値を除いた Excel、Markdown、JSON 形式の監査出力。サンプルのみで、監査エンジンは含みません。(2026)

## 時系列データ

このセクションは、時系列データのデータ品質をカバーします。

### 論文

- [時系列データクリーニング：現状、課題、機会](https://arxiv.org/abs/2201.05562) - 時系列データクリーニングに関する調査。(2022)
- [深層学習のための時系列データ拡張：調査](https://arxiv.org/abs/2002.12478) - 時系列データ拡張に関する調査。(2020)

### ツール・プロジェクト

- [Darts](https://github.com/unit8co/darts) - 時系列予測と異常検出のためのPythonライブラリ。(2020)
- [tslearn](https://github.com/tslearn-team/tslearn) - 時系列データ専用機械学習ツールキット。(2017)

## グラフデータ

このセクションは、グラフデータのデータ品質をカバーします。

### 論文

- [グラフデータのノイズとエラーに対するグラフクリーニング手法調査](https://arxiv.org/abs/2201.00443) - グラフクリーニング手法の調査。(2022)
- [グラフデータ品質：データベース観点からの調査](https://arxiv.org/abs/2201.05236) - データベース観点からのグラフデータ品質調査。(2022)

### ツール・プロジェクト

- [DGL](https://github.com/dmlc/dgl) - グラフ深層学習のためのPythonパッケージ。(2018)
- [NetworkX](https://github.com/networkx/networkx) - 複雑ネットワークの作成、操作、研究のためのPythonパッケージ。(2008)

## データ中心AI

このセクションは、データ中心AIパラダイムに従って機械学習モデルのデータ品質管理に焦点を当てます。データ評価、データ選択、MLパイプラインにおけるデータ品質評価ベンチマークに関連する論文とリソースを含みます。

### サーベイ

- [機械学習のためのデータ品質次元とツールに関する調査](https://arxiv.org/pdf/2406.19614) - MLアプリケーションの17のデータ品質ツールに関する包括的調査。[GitHubリソース](https://github.com/haihua0913/awesome-dq4ml)。(2024)
- [データ品質意識：従来データ管理からデータサイエンスシステムへの旅路](https://arxiv.org/pdf/2411.03007) - 従来データ管理と現代データサイエンスシステムにわたるデータ品質意識の包括的調査。(2024)
- [言語モデルのデータ選択調査](https://arxiv.org/pdf/2402.16827.pdf) - 言語モデルのデータ選択技術に焦点を当てた調査。(2024)
- [信頼できるAI用データ作成の進歩、課題、機会](https://www.nature.com/articles/s42256-022-00516-1) - AI用高品質データ作成の課題と機会を議論するNature Machine Intelligence論文。(2022)
- [データ中心人工知能：調査](https://arxiv.org/pdf/2303.10158.pdf) - データ中心AIアプローチの包括的調査。(2023)
- [大規模言語モデルのデータ管理：調査](https://arxiv.org/pdf/2312.01700.pdf) - 大規模言語モデルのデータ管理技術調査。(2023)
- [訓練データ影響分析と推定：調査](https://arxiv.org/pdf/2212.04612.pdf) - 訓練データのモデルパフォーマンスへの影響を分析・推定する手法の調査。(2022)
- [機械学習のデータ管理：調査](https://luoyuyu.vip/files/DM4ML%5FSurvey.pdf) - 機械学習データ管理技術のTKDE調査。(2022)
- [機械学習におけるデータ評価：「成分」、戦略、オープンチャレンジ](https://www.ijcai.org/proceedings/2022/0782.pdf) - 機械学習におけるデータ評価手法のIJCAI論文。(2022)
- [説明ベースNLPモデル人間デバッグ：調査](https://aclanthology.org/2021.tacl-1.90.pdf) - 説明ベースNLPモデルデバッグのTACL調査。(2021)

### データ評価

- [データShapley：機械学習データの公平評価](https://proceedings.mlr.press/v97/ghorbani19c/ghorbani19c.pdf) - 訓練データ評価のためのデータShapley手法を紹介するICML論文。(2019)
- [最近傍アルゴリズムの効率的タスク特化データ評価](https://vldb.org/pvldb/vol12/p1610-jia.pdf) - 最近傍アルゴリズムの効率的データ評価に関するVLDB論文。(2019)
- [Shapley値に基づく効率的データ評価に向けて](https://proceedings.mlr.press/v89/jia19a/jia19a.pdf) - Shapley値を用いた効率的データ評価のAISTATS論文。(2019)
- [影響関数によるブラックボックス予測の理解](https://arxiv.org/pdf/1703.04730.pdf) - モデル予測理解のための影響関数を紹介するICML論文。(2017)
- [SGD訓練モデルのデータクリーニング](https://proceedings.neurips.cc/paper%5Ffiles/paper/2019/file/5f14615696649541a025d3d0f8e0447f-Paper.pdf) - SGD訓練モデルのデータクリーニングに関するNeurIPS論文。(2019)

### データ選択

- [MIRA: Mid-training Rubric Anchoring for Source-Aware Data Selection](https://arxiv.org/abs/2605.30288) - データ源ごとに評価基準を発見し、その判定をスケーラブルなスコアモデルに蒸留することで、コード中心のLLM中間学習に用いるデータを選別する手法。(2026)
- [Modyn：データ中心機械学習パイプライン編成](https://arxiv.org/pdf/2312.06254) - データ中心機械学習のパイプライン編成に関するSIGMOD論文。(2023)
- [最適制御による言語モデルデータ選択](https://openreview.net/pdf?id=dhAL5fy8wS) - 言語モデルデータ選択の最適制御手法に関するICLR論文。(2024)
- [適応バッチ選択によるADAM最適化](https://openreview.net/pdf?id=BZrSCv2SBq) - ADAM最適化の適応バッチ選択に関するICLR論文。(2024)
- [適応データ最適化：スケーリング法則による動的サンプル選択](https://openreview.net/pdf?id=aqok1UX7Z1) - スケーリング法則を用いた動的サンプル選択に関するICLR論文。(2024)
- [プロキシによる選択：深層学習の効率的データ選択](https://openreview.net/pdf?id=HJg2b0VYDr) - プロキシモデルを用いた効率的データ選択に関するICLR論文。(2020)

### ベンチマーク

- [DataPerf：データ中心AI開発ベンチマーク](https://openreview.net/pdf?id=LaFKTgrZMG) - データ中心AI開発ベンチマークを紹介するNeurIPS論文。(2023)
- [OpenDataVal：統一データ評価ベンチマーク](https://openreview.net/pdf?id=eEK99egXeB) - 統一データ評価ベンチマークに関するNeurIPS論文。(2023)
- [画像キャプションによるマルチモーダルデータセット改善](https://proceedings.neurips.cc/paper%5Ffiles/paper/2023/file/45e604a3e33d10fba508e755faa72345-Paper-Datasets%5Fand%5FBenchmarks.pdf) - 画像キャプションによるマルチモーダルデータセット改善に関するNeurIPS論文。(2023)
- [帰属訓練データ生成器としての大規模言語モデル：多様性とバイアスの物語](https://proceedings.neurips.cc/paper%5Ffiles/paper/2023/file/ae9500c4f5607caf2eff033c67daa9d7-Paper-Datasets%5Fand%5FBenchmarks.pdf) - LLMを訓練データ生成器として使用することに関するNeurIPS論文。(2023)
- [dcbench：データ中心AIシステムベンチマーク](https://dl.acm.org/doi/pdf/10.1145/3533028.3533310) - データ中心AIシステムベンチマークを紹介するDEEM論文。(2022)

## 貢献ガイド

貢献を歓迎します！まず[貢献ガイド](CONTRIBUTING.md)をお読みください。 
