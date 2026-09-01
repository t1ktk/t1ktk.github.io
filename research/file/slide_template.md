---
marp: true
paginate: true
style: |
  /* --- 全スライド共通設定（コンテンツスライド用） --- */
  section {
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
    align-items: flex-start;
    text-align: left;
    font-family: "BIZ UDPGothic", "BIZ UDPゴシック", sans-serif;
    background-color: #fafafa;
    padding: 15px 60px 50px 60px;
    color: #000;
  }

  /* コンテンツスライドのタイトル（h3）と下線 */
  h3 {
    width: calc(100% + 120px);
    margin-left: -60px;
    margin-right: -60px;
    padding-left: 40px;
    padding-right: 60px;
    padding-bottom: 0.3rem;
    box-sizing: border-box;
    font-size: 1.5rem;
    font-weight: normal;
    letter-spacing: 0.02em;
    margin-top: 0;
    margin-bottom: 1rem;
    border-bottom: 1px solid #000;
    color: #000;
  }

  /* 中見出し（h4） */
  h4 {
    font-size: 1.3rem;
    font-weight: normal;
    margin: 0.5rem 0 0.2rem 0;
    color: #000;
  }

  /* 本文・リストの調整 */
  p, li {
    font-size: 1.05rem;
    line-height: 1.5;
    letter-spacing: 0.02em;
    margin: 0.2rem 0;
    color: #000;
  }

  ul {
    margin: 0.2rem 0 0.4rem 1.5rem;
    padding-left: 0;
  }

  /* 特定範囲の中央揃え用クラス */
  .center {
    width: 100%;
    text-align: center;
    margin: 1rem 0;
  }

  /* 下部ヘッダー位置調整 */
  header {
    position: absolute;
    bottom: 3px;
    top: auto;
    left: 0;
    right: 0;
    padding-left: 60px;
    padding-right: 60px;
    box-sizing: border-box;
    display: flex;
    align-items: center;
    font-size: 0.75rem;
    line-height: 1.3;
    color: #808088;
    border-top: 1px solid #808088;
    padding-top: 4px;
  }

  /* ヘッダー内の各列を等幅（flex: 1）にする */
  header > * {
    flex: 1;
    text-align: center;
  }

  /* 端のテキスト位置調整 */
  header > *:first-child {
    text-align: left;
  }

  header > *:last-child {
    text-align: right;
  }

  /* --- ページ番号を右下に配置 --- */
  section::after {
    position: absolute !important;
    bottom: 8px !important;
    top: auto !important;
    right: 60px !important;
    font-size: 1rem !important;
    line-height: 1.3 !important;
    padding: 0 !important;
    padding-top: 4px !important;
    color: #808088 !important;
    background: transparent !important;
  }

  /* メールアドレスのリンク無効化と指定 */
  a {
    color: inherit !important;
    text-decoration: none !important;
    pointer-events: none;
    cursor: default;
  }

  .email {
    font-size: 0.8rem;
    letter-spacing: -0.05em;
  }

  /* --- 表紙専用スタイル（_class: title） --- */
  section.title {
    justify-content: center;
    align-items: center;
    text-align: center;
    padding: 40px 60px;
  }

  /* 表紙ではページ番号を非表示にする */
  section.title::after {
    display: none !important;
  }

  section.title h1 {
    font-size: 2.5rem;
    font-weight: 300;
    line-height: 1.25;
    letter-spacing: 0.03em;
    margin-top: 0;
    margin-bottom: 0rem;
    border: none;
    color: #000;
  }

  section.title h2 {
    font-size: 1.5rem;
    font-weight: 300;
    line-height: 1.25;
    letter-spacing: 0.03em;
    margin-top: 0;
    margin-bottom: 2rem;
    border: none;
    color: #000;
  }

  section.title p {
    font-size: 0.9rem;
    line-height: 1.6;
    letter-spacing: 0.1em;
    margin: 0;
    color: #000;
  }
---

<!-- _class: title -->

# titleだよーん
## :subtitleだよーん

実施年月日（JST）
於：会場大学会場キャンパス
**学会大会名称【セッション名】**
所属
名前
<span class="email">mail<span>@</span>adress</span>

---

<!-- header: <span>イベント名</span><span>発表タイトル</span><span></span> -->

### スライドタイトル

ここは通常の左揃えテキストです。

<div class="center">
中央揃え

この範囲に入っているテキストは中央に配置
</div>

- ここからは再び通常の左揃えリスト
  - 階層②
