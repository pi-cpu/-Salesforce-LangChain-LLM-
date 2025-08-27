📄 README — 商談要約エージェント (Salesforce × LangChain × LLM)
1. プロジェクト概要

本プロジェクトは、Salesforce の商談（Opportunity）の説明文や活動履歴を外部 LLM（例: GPT, Claude）に渡し、要約を生成する PoC（Proof of Concept）です。

Salesforce 標準の AI 機能（Agentforce / Prompt Builder）は高機能ですが、契約コストが高額であるという課題があります。本プロジェクトは 約1/100以下のコスト で商談要約を実現できる代替案を提示します。

2. 主な機能

Salesforce API から商談レコードを取得

LangChain を利用して LLM にテキスト送信

商談の説明文を要約して返却

要約結果を Chatter に自動投稿

3. 使用技術

Salesforce API (REST / Apex Callout)

LangChain (Pythonベースの LLM フレームワーク)

外部LLM API（例: OpenAI GPT-4o-mini, Claude 3 Sonnet）

Heroku / Localhost（動作環境例）

4. システム構成図（イメージ）
