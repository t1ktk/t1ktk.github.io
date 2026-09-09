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
    padding: 0 60px 50px 60px;
    color: #000;
    position: relative;
  }

  /* --- スライドタイトル（黒帯） --- */
  h3 {
    width: calc(100% + 120px);
    margin-left: -60px;
    margin-right: -60px;
    margin-top: 0;
    margin-bottom: 1rem;

    padding: 0.45rem 60px 0.45rem 40px;

    box-sizing: border-box;

    font-size: 1.5rem;
    font-weight: normal;
    letter-spacing: 0.02em;

    background: #000;
    color: #fff;
    border: none;
  }

  /* 中見出し（h4） */
  h4 {
    font-size: 1.3rem;
    font-weight: normal;
    margin: 0.5rem 0 0.2rem 0;
    color: #000;
  }

  /* 本文 */
  p,
  li {
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

  /* 中央寄せ用 */
  .center {
    width: 100%;
    text-align: center;
    margin: 1rem 0;
  }

  /* フッター */
  header {
    background-color: #222222;
    color: #ffffff;
    position: absolute;
    bottom: 0;
    top: auto;
    left: 0;
    right: 0;

    padding-left: 60px;
    padding-right: 60px;
    padding-top: 4px;

    box-sizing: border-box;

    display: flex;
    align-items: center;

    font-size: 0.75rem;
    line-height: 1.3;
    color: #fff;
  }

  header > * {
    flex: 1;
    text-align: center;
  }

  header > *:first-child {
    text-align: left;
  }

  header > *:last-child {
    text-align: right;
  }

  /* ページ番号 */
  section::after {
    position: absolute !important;
    bottom: 8px !important;
    top: auto !important;
    right: 60px !important;

    font-size: 1rem !important;
    line-height: 1.3 !important;

    padding: 0 !important;
    padding-top: 4px !important;

    color: #fff !important;
    background: transparent !important;
  }

  /* メールアドレス */
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

  /* --- 表紙専用 --- */
  section.title {
    padding: 0;
    display: flex;
    flex-direction: column;
    background: linear-gradient(to bottom, #000000 0%, #000000 50%, #fafafa 50%, #fafafa 100%);
  }

  section.title::after {
    display: none !important;
  }

  /* 上半分（黒背景領域） */
  .title-top {
    height: 50%;
    width: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    box-sizing: border-box;
    padding: 20px 60px;
  }

  .title-top h1 {
    font-size: 2.5rem;
    font-weight: 300;
    line-height: 1.25;
    letter-spacing: 0.03em;
    margin: 0 0 0.5rem 0;
    color: #ffffff !important;
    text-align: center;
  }

  .title-top h2 {
    font-size: 1.5rem;
    font-weight: 300;
    line-height: 1.25;
    letter-spacing: 0.03em;
    margin: 0;
    color: #ffffff !important;
    text-align: center;
  }

  /* 下半分（白背景領域） */
  .title-bottom {
    height: 50%;
    width: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    box-sizing: border-box;
    padding: 10px 60px;
  }

  .title-bottom p {
    font-size: 0.85rem;
    line-height: 1.5;
    letter-spacing: 0.05em;
    margin: 0.15rem 0;
    color: #000000 !important;
    text-align: center;
  }
---

<!-- _class: title -->

<div class="title-top">

# titleだよーん
## subtitleだよーん

</div>
<div class="title-bottom">

年月日（JST）  
於：大学キャンパス

**【発表区分】**

所属だよーん

なまえだよーん

<span class="email">mail<span>@</span>address</span>

</div>

---

<!-- header: <span>[会場]</span><span>[メインタイトル]</span><span></span> -->

### スライドタイトルだよーん

#### 中見出しだよーん 
- 箇条書きだよーん１
  - 箇条書きだよーん２

平文だよーん
**強調平文だよーん**
