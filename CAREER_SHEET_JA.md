# 職務経歴書 (Curriculum Vitae / Career Sheet)

**最終更新日:** 2026年10月25日  
**氏名:** ナビエフ・オキルジョン (Okiljon Nabev)  
**生年月日:** 2004年生まれ  
**居住地:** 日本・北海道（出身: ウズベキスタン ナマンガン州）  
**学歴:** 岩谷学園 ひがし北海道IT専門学校 地域未来情報テクノロジー科（2027年3月卒業見込）  
**連絡先:** [okiljonnabev@gmail.com](mailto:okiljonnabev@gmail.com)  
**ポートフォリオ:** [https://okiljon04344.github.io/](https://okiljon04344.github.io/)  
**GitHub:** [https://github.com/okiljon04344](https://github.com/okiljon04344)

---

## 1. 職務要約 (Professional Summary)

Flutter × Firebase を中核としたクロスプラットフォーム（Mobile / Web / Desktop / Android TV）エンジニアです。  
専門学校在学中より、韓国で事業を展開する企業向けECアプリ「**Million Halal (MILLION MARKET)**」の実案件（受託開発・商用資産のためコード非公開）において、**4名チームのプロジェクトマネージャー（PM）兼リードエンジニア**として要件定義・タスク設計・開発マネジメントを行い、約6か月で納品を完了させました。  
また、個人開発プロジェクト「**EduPlanner AI**」では、Firebase Cloud Functions と Google Gemini API を連携させ、学生の学習計画立案・AI相談・理解度テスト生成を全自動化するフルスタックAIアプリを構築。静的解析（`flutter analyze` 0 issues）およびユニット・ウィジェットテスト（118テスト全通過）を徹底した高品質な設計を得意としています。

---

## 2. 保有スキル・技術スタック (Technical Skills)

| 分野 | 技術要素 | 経験年数・習熟度 |
| :--- | :--- | :--- |
| **開発言語** | Dart, Python, Java, SQL, HTML5 / CSS3 / JavaScript | Java は高校在学中に独学開始、Dart は2023年頃から独学（個人開発・受託案件1件） |
| **フレームワーク** | **Flutter** (Mobile, Web, Desktop, Android TV 10-foot UI) | 2023年頃から独学（設計・状態管理・テスト）、受託案件1件で実務経験 |
| **状態管理** | Riverpod, Provider, StateNotifier | feature 単位のレイヤー分割（UI / Provider / Repository） |
| **バックエンド・BaaS**| Firebase (Auth, Firestore, Cloud Functions, FCM, Realtime DB), Supabase | 2年（セキュリティルール・クエリ最適化） |
| **AI / LLM 連携** | Google Gemini API (`google_generative_ai`), REST API, Function Calling | プロンプトエンジニアリング、構造化出力、自動テスト |
| **CI / CD・ツール** | Git, GitHub, GitHub Actions, Firebase Emulator, Android Studio, VS Code, Figma | 静的解析・ユニットテスト・セキュリティルールテストの自動実行 |
| **語学力** | **日本語: ビジネスレベル (JLPT N2)**、ウズベク語: ネイティブ、英語: 技術ドキュメント読解・会話 | 多国籍チームでのコミュニケーション・PM実績あり |

---

## 3. 主な開発実績 (Featured Projects)

### ①【受託開発・実案件】Million Halal (MILLION MARKET)
* **リポジトリ:** ※商用クライアントワークのためソースコード非公開（Private Repository）
* **概要:** 韓国で事業を展開する企業向けハラール食品ECアプリケーション
* **開発体制:** 4名チーム（**役割: プロジェクトマネージャー & Flutter開発**）
* **開発期間:** 約6か月
* **担当工程:** 要件定義、基本設計、UI設計、タスク配分・スケジュール管理、Flutterアプリ実装、API連携、納品
* **主な機能:** 商品検索・カテゴリ絞り込み、カート・注文管理、セール・ポイント還元、卸売業者登録機能
* **工夫した点・成果:**
  - 多言語・多国籍チーム間の認識ズレを防ぐため、Figmaを用いたプロトタイプとNotionによるチケット管理を徹底。納期遅延ゼロでクライアントへの納品を達成。
  - ※商用資産保護のためソースコードは非公開ですが、PMとしてのタスク設計、アーキテクチャ、画面設計、課題解決のプロセスについては面談時に詳細をご説明可能です。

---

### ②【個人開発・自主開発】EduPlanner AI (エデュプランナーAI)
* **リポジトリ:** [https://github.com/okiljon04344/eduplaner_ai](https://github.com/okiljon04344/eduplaner_ai)
* **使用技術:** Flutter 3.x, Dart, Riverpod, `go_router`, Firebase, Cloud Functions, Google Gemini API
* **役割:** 企画・設計・開発・テスト（個人開発）
* **主な機能:**
  - 時間割・講義管理、課題提出・リマインダー通知
  - 週間学習時間・成績推移のインタラクティブグラフ可視化
  - **Gemini API 連携:** 弱点分野に基づいた学習アドバイス、および多肢選択式理解度テスト問題の自動生成
* **技術的成果:**
  - APIキーをクライアント側に露出させないセキュアな Cloud Functions バックエンド設計。
  - **118件のユニット・ウィジェットテスト**を作成し、`flutter test` 100% 通過、`flutter analyze` 0 warnings を達成。

---

### ③【個人開発】Universal Restaurant App (QR テーブルオーダー & 飲食店舗管理システム)
* **リポジトリ:** [https://github.com/okiljon04344/restoranapp](https://github.com/okiljon04344/restoranapp)
* **使用技術:** Flutter, Riverpod, `go_router`, Cloud Firestore, Firebase Auth, i18n
* **主な機能:**
  - 来店客用: テーブルQRコード読み取り、リアルタイム注文・カート管理
  - キッチン用（KDS）: 注文状況（調理中・配膳済）のリアルタイムステータス更新
  - 管理者用: 売上集計ダッシュボード、メニュー・在庫・材料原価管理
  - 日本語・英語・ウズベク語の3言語リアルタイムローカライズ
* **セキュリティ・品質:**
  - 管理者・キッチン権限を Firebase Auth **Custom Claims** で管理（メールアドレス判定を廃止）
  - 注文データの形式・金額・ステータス遷移を `firestore.rules` で検証し、Firestore Emulator 上の自動テスト（14件）を GitHub Actions で実行

---

### ④【個人開発】Smart TV Streaming App (Android TV 動画配信プラットフォーム)
* **リポジトリ:** [https://github.com/okiljon04344/smart_tv_app](https://github.com/okiljon04344/smart_tv_app)
* **使用技術:** Flutter, Android TV 10-foot UI, D-Pad Remote Navigation, `video_player`, YouTube Player
* **主な機能:**
  - **専用 TV リモコンエンジン (`tv_key_helper.dart`):** リモコンの十字キー（上下左右）、決定キー（Select / Enter）、戻るキーの2重発火を防止し、フォーカス状態を視覚的にアニメーション表示。
  - ハイブリッド動画再生（MP4およびYouTubeストリーム）、10秒スキップ、視聴進捗自動保存（Continue Watching）。
  - リモコン1タップでログイン不要で全機能を体験できる **TV Demo / ゲストモード** 搭載。
  - 管理者権限を **Custom Claims** で管理し、Realtime Database ルールを Emulator 上の自動テスト（8件）で検証。

---

## 4. 自己PR (Self PR)

### ① チームを動かし、最後までやり抜くプロジェクト推進力 (PM力)
留学生でありながら、日本語でのビジネスコミュニケーション（JLPT N2）を強みに、多国籍メンバー4名を率いて実案件ECアプリ開発を納期通りに納品しました。「技術的に可能か」だけでなく「クライアントの事業にどう貢献できるか」を常に考え、要件の優先順位付けと課題解決を主導できます。

### ② 生成AI・新技術をスピーディにプロダクトへ落とし込む実装力
ただAPIを叩くだけでなく、Cloud Functions を介したセキュアな設計や、Gemini API のストリーミング生成、構造化JSONレスポンスのパースなど、実用的なAI機能の統合を素早く実現できます。

### ③ 保守性・セキュリティとテスト自動化へのこだわり
「動けばいい」コードではなく、Riverpod を用いた feature 単位の保守性の高いディレクトリ構成を心がけています。主要リポジトリ（EduPlanner AI・Restaurant App・Smart TV App）には GitHub Actions を導入し、静的解析（`flutter analyze`）・ユニット／ウィジェットテスト・セキュリティルールのテストを自動実行しています。

---

## 5. 表彰・資格 (Awards & Certifications)

- 🏆 **国際ビジネスアイデアコンテスト チーム第1位**（4か国参加・メンタルヘルス×医師連携アプリの企画・プロトタイプ提案）
- 📜 **日本語能力試験 (JLPT) N2 認定**
- 🚗 **日本普通自動車第一種運転免許 取得済**
