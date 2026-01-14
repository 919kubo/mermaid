%% title: study-dx Top Structure (L1)
%% service: PoC Blueprint
%% purpose: Landing page information architecture + demo funnel
%% updated: 2026-01-13

flowchart TB

  A_Hero["HERO<br/>PoC Blueprint<br/>Mermaidで設計し、現場で試し、実装へつなぐ"]
    --> A_Value

  A_Value["提供価値（Why）<br/>・現場負荷最小化<br/>・データフロー可視化<br/>・ナレッジ成長（利用率×弱点補完）"]
    --> A_What

  A_What["サービス概要（What）<br/>PoC有償：設計テンプレ + 個別デモ環境 + 運用導線"]
    --> A_Demo

  subgraph A_Demo["デモ導線（How）"]
    direction TB
    D1["① 紙芝居（Web）<br/>ユースケース/画面イメージ/成果物例"]
      --> D2["② リモートデモ申請<br/>Googleアドレス必須"]
    D2 --> D3["③ 個別デモ環境<br/>共有スプレ（期間限定）<br/>V/L明記で反復運用"]
  end

  A_Demo --> A_Templates

  A_Templates["テンプレート（Assets）<br/>・汎用テンプレ（L1/L2/L3）<br/>・業種別テンプレ展開<br/>・Mermaid記法 標準化"]
    --> A_Samples

  A_Samples["サンプル/実績（Proof）<br/>・トップ図サンプル<br/>・業種別サンプル<br/>・PoC成果（Before/After）"]
    --> A_Pricing

  A_Pricing["料金/進め方（Offer）<br/>・PoC有償プラン<br/>・期間/範囲/成果物<br/>・実装接続（次フェーズ）"]
    --> A_FAQ

  A_FAQ["FAQ / セキュリティ（Trust）<br/>・Google Workspace境界<br/>・データ取り扱い<br/>・ChatGPTは翻訳/標準化最小呼び出し"]
    --> A_Contact

  A_Contact["問い合わせ（CTA）<br/>・デモ申請<br/>・相談フォーム<br/>・連絡先"]
    --> A_Footer

  A_Footer["フッター<br/>・note（非エンジニア向け）<br/>・note（エンジニア向け）<br/>・X（非エンジニア）<br/>・X（エンジニア）<br/>・ポリシー/利用規約"]
