# ニケ（tegnike）

[English](https://github.com/tegnike/tegnike/blob/main/README.md) | 日本語

AIエージェントとAIキャラクターを開発しているエンジニアのニケです。ポーランドに住み、主に日本の企業とフルリモートで仕事をしています。

2018年にWebエンジニアとして働き始め、Ruby on Railsのバックエンドを中心に、フロントエンドとインフラも担当してきました。2024年からはLLMを使った開発が中心です。

## 取り組んでいること

- AIエージェント：エージェントが計画を作り、利用者が承認してから実行する業務自動化プラットフォームと、エージェントから呼べる文書変換APIを開発しています。文書変換APIにはPython SDKとMCPサーバーがあります
- AIキャラクター：ベクトル検索を使った長期記憶、音声合成、VRMアバターを開発しています。VRMアバターにはリップシンクと、感情に合わせて表情を変える仕組みを入れています
- AIコーディングエージェントの評価：エージェントにコードや設計書を作らせ、テスト通過率と正解との差分で出力を採点しています

## OSS

### [AITuberKit](https://github.com/tegnike/aituber-kit)

AIキャラクターとの会話やAITuberの配信を作れるツールキットです。TypeScript、React、Next.jsで書いていて、2023年10月から公開しています。（[デモ](https://aituberkit.com)、[ドキュメント](https://docs.aituberkit.com)）

- Starは1,100以上、Forkは230以上、リリースは120回以上で、外部の開発者約30名の変更を取り込んでいます
- 多くのLLMと音声合成サービス、2Dと3Dのキャラクターモデルに対応しています
- プロダクトの責任者として、仕様の決定、リリース、外部からの変更のレビュー、サポートを担当しています
- 商用ライセンスでも提供していて、法人向けに有償の優先開発も受けています
- 書籍『AITuberを作ってみたらプロンプトエンジニアリングがよくわかった件』（日経BP、2024年）と、MoguLive、WEELの記事で紹介されました

### そのほかのリポジトリ

- [Japanese-RP-Bench](https://github.com/tegnike/Japanese-RP-Bench)：日本語LLMのロールプレイ性能を測るベンチマークです。バージョン2では、キャラクターへの追従、長期の安定性、人格の置き換えへの耐性、失敗後の復帰を測ります（[ダッシュボード](https://japanese-rp-bench.tegnike.chatgpt.site)）
- [AITuberList](https://github.com/tegnike/aituber-list)：YouTubeで活動するAITuberの一覧です（[サイト](https://aituberlist.net)）
- [deepseek-chan-vrm](https://github.com/tegnike/deepseek-chan-vrm)：VRM 1.0のキャラクターモデルです

### AIニケちゃん

AIキャラクターの[AIニケちゃん](https://nikechan.com/about)を開発・運用しています。AIニケちゃんは2023年からX、Discord、YouTubeで活動しています。記憶と発話の仕組みは自作です。届いたメッセージの原文を保存し、人物ごとのメモとベクトル検索できる記憶にして、返答のときに相手と話題に合う記憶を検索して使います。

## 経歴

- 2024年〜現在、AIエージェントとAIキャラクターの開発（業務委託）：上に書いたエージェントのプラットフォーム、文書変換API、評価を担当しています。その前は、AIキャラクターの長期記憶ライブラリの設計を主導して記憶の保存先をベクトル検索に移し、AIキャラクターの口調でXに投稿するサービスのバックエンドを開発しました
- 2020年〜2024年、Webサービスの開発（業務委託）：予約、EC、動画視聴、オンラインくじのサービスを、主にRuby on Railsで開発しました。予約サービスではサーバーサイドのリードエンジニアを約2年務め、オンラインくじのサイトでは要件の整理から運用まで1人で開発しました
- 2018年〜2021年、業務システムの開発：JavaとC#による治験の患者登録システムと、Ruby on Railsによる業務管理システムを開発しました

## 登壇・執筆

- 登壇：AlibabaMeetupSapporo（2026年8月）、AI CONTENTS BOOST #06のゲスト登壇（2026年6月）、OpenClawで自律型のAIキャラクターを作るオンラインイベントの共同主催（2026年3月、参加登録193人）
- 展示：生成AIなんでも展示会のVol.2（2024年11月）とVol.5（2026年5月）で、AIのゲームプレイと実況を展示しました
- 記事：[note](https://note.com/nike_cha_n)に、AIエージェント、AIキャラクター、AIコーディングツールの記事を65本書いています。[開発ブログ](https://nikechan.com/dev-blog)もあります
- 書籍レビュワー：『LangChainとLangGraphによるRAG・AIエージェント［実践］入門』（技術評論社、2024年）

## 技術

- AI：LangChain、LangGraph、MCP、Claude Code、OpenAI、Anthropic、Azure OpenAI、AWS Bedrock、Langfuse、LangSmith
- 言語とフレームワーク：TypeScript、React、Next.js、Python、FastAPI、Ruby on Rails
- インフラ：AWS、GCP、Azure、Docker、GitHub Actions、Terraform

## 問い合わせ

AIエージェントとAIキャラクターの業務委託、登壇、共同企画を受け付けています。AITuberKitについては、商用ライセンスと有償の優先開発の問い合わせも受けています。

- XのDM：[@tegnike](https://x.com/tegnike)
- メールなど：[nikechan.com/developer](https://nikechan.com/developer#connect)

## リンク

- Webサイト：[nikechan.com/developer](https://nikechan.com/developer)
- X：[@tegnike](https://x.com/tegnike)
- YouTube：[@nikechan](https://www.youtube.com/@nikechan)
- 記事：[note](https://note.com/nike_cha_n)、[Zenn](https://zenn.dev/nikechan)

## GitHub stats

[![nike's GitHub stats](https://github-readme-stats-fast.vercel.app/api?username=tegnike&count_private=true&show_icons=true&theme=gruvbox)](https://github.com/Pranesh-2005/github-readme-stats-fast)

[![Top Langs](https://github-readme-stats-fast.vercel.app/api/top-langs/?username=tegnike&hide=html,css,php,ruby,hcl&layout=compact&theme=gruvbox)](https://github.com/Pranesh-2005/github-readme-stats-fast)
