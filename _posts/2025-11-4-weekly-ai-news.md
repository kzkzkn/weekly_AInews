---
layout: post
title: "今週のAIニュース (2025/10/27 ~ 11/4)"
date: 2025-11-04 23:00:00 +0900
---

## 概要

今週は、AIプラットフォームの地政学的な動きが際立ちました。OpenAIがMicrosoftとの関係を再定義しつつ、新たにAWSとも提携を発表。これにより、OpenAIが特定のクラウドインフラに縛られない「上位レイヤー」としての地位を確立したことが鮮明になりました。

時を同じくして、競合のAnthropicが東京オフィスを開設し、日本政府との協力を発表。米Menlo VCの調査ではエンタープライズAPI利用率でOpenAIを抜き首位に立つなど、市場の勢力図が大きく変動しています。

また、OpenAIは「AIがAIを監視する」安全性モデル（gpt-oss-safeguard）や脆弱性自動修正（Aardvark）を相次いで発表。これは、先週から指摘される「AIエージェント」の強大な能力をいかに統治・制御するかという、AIガバナンスの新しいフェーズに突入したことを示しています。

国内では、リコー、パーソル、DeNAなど、特定業務に特化した「Vertical AI」の具体的な成果報告が相次ぎ、AI活用が実証（PoC）段階から実装・成果測定の段階へ移行しています。

---

## 主要なAIプラットフォームの動向

### OpenAI

* **Microsoftとの新たな確定契約（Definitive Agreement）を締結**
    OpenAIとMicrosoftが、両社のパートナーシップに関する新たな確定契約を締結したことを発表しました。
    * [https://openai.com/index/next-chapter-of-microsoft-openai-partnership/](https://openai.com/index/next-chapter-of-microsoft-openai-partnership/)

* **AWS（Amazon）との提携を発表**
    OpenAIがAWSとの提携を発表。Microsoft Azureに加え、AWSのコンピューティングインフラも活用することになります。これは、OpenAIが特定のクラウドに依存しないマルチクラウド戦略を採用し、プラットフォームとして強力な交渉力を持つことを示唆しています。
    * [https://www.aboutamazon.com/news/aws/aws-open-ai-workloads-compute-infrastructure](https://www.aboutamazon.com/news/aws/aws-open-ai-workloads-compute-infrastructure)

* **安全性判断AI「gpt-oss-safeguard」をOSSで公開**
    OpenAIが、人間の記述したルール（例：「暴力的な内容は禁止」）をAIが直接解釈し、コンテンツの安全性を自ら判断できるモデル「gpt-oss-safeguard」を開発し、オープンソースで公開しました。「AIを監視するAI」を配布することで、開発者が各サービスに合わせた安全基準を容易に実装できるようにする狙いがあります。
    * [https://openai.com/index/introducing-gpt-oss-safeguard/](https://openai.com/index/introducing-gpt-oss-safeguard/)

* **脆弱性自動検知・修正システム「Aardvark」を発表**
    AIがコードを監視し、脆弱性を自動で発見、さらに修正案まで提示するセキュリティシステム「Aardvark」を発表しました。
    * [https://openai.com/index/introducing-aardvark/](https://openai.com/index/introducing-aardvark/)

### Anthropic (Claude)

* **東京オフィスの開設と日本政府との協力を発表**
    Anthropicが日本市場への本格参入として東京オフィスの開設を発表しました。あわせて、AIの安全性と導入に関して日本政府と協力していくことも明らかにされました。
    * 東京オフィス開設: [https://www.anthropic.com/news/opening-our-tokyo-office](https://www.anthropic.com/news/opening-our-tokyo-office)
    * 日本政府との協力: [https://www.nikkei.com/article/DGXZQOUC294Z50Z21C25A0000000/](https://www.nikkei.com/article/DGXZQOUC294Z50Z21C25A0000000/)

* **金融サービス向け機能を強化**
    金融業界向けの機能強化を発表。Microsoft ExcelのサイドバーでClaudeを直接利用できるベータ版の提供や、リアルタイムの金融データとの連携を強化するコネクタが導入されます。
    * [https://www.anthropic.com/news/advancing-claude-for-financial-services](https://www.anthropic.com/news/advancing-claude-for-financial-services)

* **エンタープライズLLM API利用率で首位に（Menlo VCレポート）**
    米ベンチャーキャピタルMenlo VCの2025年中間レポートによると、エンタープライズ（企業向け）LLM APIの利用率においてAnthropicが32%で首位に立ち、OpenAI（25%）を上回ったと報告されました。
    * [https://menlovc.com/perspective/2025-mid-year-llm-market-update/](https://menlovc.com/perspective/2025-mid-year-llm-market-update/)

### Microsoft

* **Microsoft Copilotに「Computeruse」機能が追加**
    Copilotのリサーチャー機能内に、AIがユーザーのPCを直接操作してタスクを実行する「Computeruse」機能が追加されたことが発表されました。
    * [https://x.com/satyanadella/status/1983949531286008023](https://x.com/satyanadella/status/1983949531286008023)

* **ワークフロー作成Agentの登場**
    Microsoftの公式エージェントに、業務プロセスを自動化するワークフローを対話形式で作成できるAgentが登場しました。
    * [https://x.com/geekfujiwara/status/1983320065719316725](https://x.com/geekfujiwara/status/1983320065719316725)

* **Copilot 2025年9月の新機能まとめを公開**
    Microsoft 365 Copilotに関する2025年9月版の新機能概要が公式ブログで公開されました。
    * [https://blogs.windows.com/japan/2025/10/30/whats-new-in-microsoft-365-copilot-september-2025/](https://blogs.windows.com/japan/2025/10/30/whats-new-in-microsoft-365-copilot-september-2025/)

### Google

* **「Gemini 3.0」が年内リリース予定**
    Googleの次世代基盤モデル「Gemini 3.0」が、2025年内にリリースされる予定であると報じられました。
    * [https://www.itmedia.co.jp/aiplus/articles/2510/31/news110.html](https://www.itmedia.co.jp/aiplus/articles/2510/31/news110.html)

---

## 国内のAI導入事例・関連ニュース

* **リコー、AIでクラウド型文書管理システムを強化**
    リコーが、独自のAI技術を活用し、クラウド型文書管理システムにおいて書類の自動分類や高度な検索を可能にする新機能を発表しました。
    * [https://www.nikkei.com/article/DGXZQOUC273FV0X21C25A0000000/](https://www.nikkei.com/article/DGXZQOUC273FV0X21C25A0000000/)

* **DeNA、社内AIヘルプデスクで正答率80%を達成**
    DeNAが、RAG（検索拡張生成）技術の精度を改善し、社内AIヘルプデスクにおいて正答率80%を達成した軌跡を公開しました。
    * [https://engineering.dena.com/blog/2025/10/findoutai_rag/](https://engineering.dena.com/blog/2025/10/findoutai_rag/)

* **パーソル系、AIアバターが求職者の経歴ヒアリングに活用**
    パーソル系の企業が、AIアバター（バーチャル面接官）が求職者の経歴やスキルをヒアリングし、適切な求人を提案するサービスを開始しました。
    * [https://www.nikkei.com/article/DGXZQOUC291YC0Z21C25A0000000/](https://www.nikkei.com/article/DGXZQOUC291YC0Z21C25A0000000/)

* **NTT、自動運転特化の新会社「NTTモビリティ」設立へ**
    NTTが、自動運転レベル4（特定条件下での完全自動運転）関連サービスを提供するため、自動運転に特化した新会社「NTTモビリティ」の設立を発表しました。
    * [https://www.itmedia.co.jp/aiplus/articles/2511/04/news082.html](https://www.itmedia.co.jp/aiplus/articles/2511/04/news082.html)

* **富士通、AI×データ分析市場の強化に向け企業買収**
    富士通が、AI活用に不可欠なデータ分析を手掛ける国内企業を買収したと報じられました。
    * [https://www.nikkei.com/article/DGXZQOUC307CM0Q5A031C2000000/](https://www.nikkei.com/article/DGXZQOUC307CM0Q5A031C2000000/)

* **博報堂系、AI広告生成の専門チーム新設**
    博報堂DYホールディングス傘下の企業が、AIによる広告クリエイティブ生成に特化した専門チームを新設し、2030年に売上高100億円を目指すと発表しました。
    * [https://www.nikkei.com/article/DGXZQOUC23CK10T21C25A0000000/](https://www.nikkei.com/article/DGXZQOUC23CK10T21C25A0000000/)

* **NTT西日本、AI音声開発支援と信頼性確保**
    NTT西日本が、AI音声の開発支援サービスにおいて、ブロックチェーン技術を活用し学習データの信頼性を確保する仕組みを導入しました。
    * [https://www.nikkei.com/article/DGXZQOUC274720X21C25A0000000/](https://www.nikkei.com/article/DGXZQOUC274720X21C25A0000000/)

* **GMO、家庭用人型ロボットの実現に向けた取り組み**
    GMOインターネットグループが、AIロボティクス分野に注力しており、家庭用人型ロボットの実現に向けた取り組みが進んでいると報じられました。
    * [https://www.itmedia.co.jp/aiplus/articles/2510/29/news090.html](https://www.itmedia.co.jp/aiplus/articles/2510/29/news090.html)

* **AI議事録「Otter.ai」、日本語版の提供を発表**
    米国で高いシェアを持つAI議事録サービス「Otter.ai」が、日本語に対応した高精度（英語で95%）のサービスを提供すると発表しました。
    * [https://www.nikkei.com/article/DGXZQOGN24D2N0U5A021C2000000/](https://www.nikkei.com/article/DGXZQOGN24D2N0U5A021C2000000/)

---

## その他のプラットフォーム・注目トピック

* **コーディングAI「Cursor 2.0」が発表**
    AIによるコーディング支援ツール「Cursor」の次世代版「Cursor 2.0」が発表され、特にコード修正の容易さが大幅に向上していると注目されています。
    * [https://x.com/corbin_braun/status/1983573794414555314](https://x.com/corbin_braun/status/1983573794414555314)

* **Microsoft App Builder のレビュー動画**
    ノーコード/ローコードでMicrosoft製品内アプリを開発できる「App Builder」の使用感に関するレビュー動画が公開されました。
    * [https://www.youtube.com/watch?v=hU4V46nSJvo&t=2s](https://www.youtube.com/watch?v=hU4V46nSJvo&t=2s)

* **Manus、LINEボットの自動作成に対応**
    AIコーディングツール「Manus」が、LINEボットを自動で作成する機能に対応しました。
    * [https://x.com/Ashley_ManusAI/status/1984178321291452870](https://x.com/Ashley_ManusAI/status/1984178321291452870)

* **話題のツール紹介**
    * 翻訳AIツール「Nani」: [https://nani.now/ja](https://nani.now/ja)
    * 高品質プロンプト紹介サイト「OpenPrompt」: [https://openprompt.jp/](https://openprompt.jp/)

---

## 考察

先週までの「AIエージェント戦争」「特化型AI」「物理AI」「セキュリティのジレ ンマ」という4つの潮流は、今週、さらに鮮明な形で進化しました。

### 1. AIは「クラウドの上」へ――勢力図の大転換

今週最大の動きは、OpenAIのAWS提携とAnthropicの日本市場本格参入です。

**OpenAIのマルチクラウド化**

OpenAIがMicrosoft Azure一辺倒から脱却し、AWSとも手を組んだことの意味は大きい。これは、AIが特定のクラウド基盤に依存するのではなく、むしろ**クラウド事業者たちが誘致すべき「上位レイヤー」**として君臨し始めたことを示しています。AIはもはや「GAFAMのツールの1つ」ではなく、「GAFAMがこぞって取り込みたい存在」に変わったのです。

**Anthropicの企業市場制覇**

AnthropicがエンタープライズAPI利用率でOpenAIを抜き、日本政府とも連携を深める動きは、市場が「OpenAI一強」ではないことを物語っています。特に金融や文書管理といった企業用途では、Anthropicの安全性と信頼性重視の姿勢が評価され、OpenAIの強力な対抗馬として地歩を固めつつあります。

### 2. 「AIがAIを統治する」時代の幕開け

先週の考察で「セキュリティのジレンマ」を指摘しましたが、今週OpenAIが発表した「gpt-oss-safeguard」(安全性判断AI)と「Aardvark」(脆弱性修正AI)は、その明確な答えといえます。

AIの能力が高度化しすぎた結果、人間のレビュアーや開発者では、その安全性や脆弱性の監視・修正が物理的に追いつかなくなっています。この難題に対し、OpenAIは**「AIにAIを監視・統治させる」**という新しい統治の仕組みを打ち出しました。これは、NTT西日本が「ブロックチェーン」で信頼性を担保しようとする動きとも根底で繋がっており、「AIの信頼性」が技術的な最重要課題になったことを示しています。

### 3. 特化型AIは「成果を問う」段階へ

国内のAI導入事例は、もはや「AIを導入しました」という報告段階を完全に超えました。

* DeNA「正答率80%達成」
* リコー「文書管理の自動分類」
* パーソル「経歴ヒアリングの自動化」
* 博報堂「売上高100億円目標」

これらはすべて、先週の金融やインフラの事例と同様、RAG(社内文書検索)、人事、広告制作といった極めて具体的な業務領域にAIを適用し、その投資効果や成果指標をきちんと測定する段階に入ったことを物語っています。

### 4. 物理AIの事業化が本格始動

先週のAmazonスマートグラスに続き、今週はNTTによる「自動運転(レベル4)」の新会社設立、GMOの「家庭用人型ロボット」が報じられました。これらは研究開発の枠を超え、AIが物理世界――交通、家庭――に実際に介入し、具体的な「事業」として動き始めたことを意味します。「物理AI」は、もはや未来の話ではなく、現実のビジネス競争の舞台となりつつあります。

### 総括

今週、AIは「クラウドの上位層」としての地位を確立すると同時に、自らの能力を制御するための「自己統治(AIによるAIの監視)」という新しい概念を導入しました。この「基盤化」と「自律化」という2つの大きな潮流が同時進行する中、ビジネスの現場では「特化型」と「物理型」のAIが、具体的な成果と事業化を競い合う、きわめてダイナミックな局面を迎えています。