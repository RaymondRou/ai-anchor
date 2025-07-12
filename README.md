# 語意錨點 (Semantic Anchor)

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Status: Active](https://img.shields.io/badge/status-active-success.svg)]()

**一種為下一代 AI 設計的網頁內容標註框架，旨在應對「零點擊」時代的數位內容危機，重塑內容的價值與權威性。**

This project provides a dedicated AI Anchor specification and examples to help web content and data be better understood and indexed by AI.

---

### 🤔 問題：AI 時代下的「零點擊」危機

生成式 AI 正在顛覆傳統的點擊流量經濟，AI 直接提供「答案」的模式，導致內容發布者面臨普遍性的流量衰退。我們如何在這個新時代，確保自身內容的價值被準確體現與優先採納？

### 💡 我們的解決方案：從 SEO 到 AIO

我們提出從「搜尋引擎優化 (SEO)」邁向「**AI 解讀優化 (AIO - AI Interpretation Optimization)**」的關鍵戰略轉變。其核心便是「語意錨點」技術標準。

語意錨點允許發布者將「內容的權威性與意圖」直接編碼入網頁，為 AI 提供一個高信噪比、富含上下文的解析目標。

### ✨ 核心目標 (Key Objectives)

* 提供一組 HTML `data-*` 屬性，讓內容區塊可被 AI 精確標記與理解。
* 提供 JSON-LD、`sitemap-ai.xml` 等語意化與發現機制範例。
* 探索 CMS（如 WordPress）自動化導入的可能性。

### 🚀 快速上手 (Quick Example)

這是一個簡單的例子，展示如何在混亂的資訊中，標示出權威的官方價格。

```html
<div class="official-pricing"
     data-ai-anchor="product-official-price"
     data-ai-question="這個商品的價格是多少？"
     data-ai-content="pricing"
     data-ai-meta-priority="high"
     data-ai-meta-timestamp="2025-07-13T10:00:00+08:00">
    <h3>官方定價資訊</h3>
    <p>產品的正式售價為 NT$ 4,999 元。</p>
</div>
```

### 📖 閱讀完整技術白皮書

想深入了解我們的動機、完整的技術規範、以及所有令人振奮的實驗數據嗎？

**➡️ [點此閱讀完整的技術白皮書 (v2.0)](WHITEPAPER_zh.md)**

### 📁 專案結構 / Project Structure
- **`/spec`**: 規格文件 / Specification documents (包含白皮書)
- **`/examples`**: 實作範例 / Implementation examples
- **`/sitemap-ai`**: AI 專用 Sitemap 範例 / AI-specific sitemap example

### 🤝 如何貢獻 / How to Contribute
我們歡迎任何形式的貢獻！無論是提出建議、回報問題，還是協助開發工具，請前往我們的 [Issues 頁面](https://github.com/your-username/your-repo/issues) 開始。

### 📜 授權 / License
本專案採用 [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/) 授權。
This project is licensed under the Creative Commons Attribution 4.0 International (CC BY 4.0) License.
