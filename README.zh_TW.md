<!--
  * browser: maturity-models
  * tracker: f44c30d1b876f8987cf78c727e573542
  * version: 7.1.0
  * updated: 2021-12-14T03:24:14Z
  * contact: Joel Parker Henderson (http://joelparkerhenderson.com)
  * options: commentable
-->

# 成熟度模型（Maturity Models）

[English README](README.md)

<img src="README.png" alt="成熟度模型" style="width: 100%;"/>

成熟度模型是一種商業工具，用於評估人員／文化、流程／結構，以及物件／技術。

參見：https://zh.wikipedia.org/wiki/成熟度模型

## 目錄

- [成熟度模型（Maturity Models）](#成熟度模型maturity-models)
  - [目錄](#目錄)
  - [成熟度模型等級](#成熟度模型等級)
  - [成熟度模型範例](#成熟度模型範例)
  - [成熟度模型流程觀點](#成熟度模型流程觀點)
  - [自上而下 vs. 自下而上](#自上而下-vs-自下而上)
  - [建模成熟度等級](#建模成熟度等級)
  - [對成熟度模型的反駁](#對成熟度模型的反駁)
  - [相關評估指標](#相關評估指標)
  - [常見問題](#常見問題)
    - [我可以創建成熟度模型嗎？](#我可以創建成熟度模型嗎)
    - [誰決定成熟度模型的內容？](#誰決定成熟度模型的內容)
    - [成熟度模型是時間快照還是未來規劃？](#成熟度模型是時間快照還是未來規劃)
    - [成熟度模型是描述性還是規範性？](#成熟度模型是描述性還是規範性)
    - [成熟度模型可以隨時間演進嗎？](#成熟度模型可以隨時間演進嗎)
    - [成熟度模型有終點嗎？](#成熟度模型有終點嗎)
    - [成熟度模型與科學模型有何不同？](#成熟度模型與科學模型有何不同)
    - [成熟度模型可驗證嗎？](#成熟度模型可驗證嗎)

## 成熟度模型等級

成熟度模型等級通常是一系列的成熟步驟，例如：

- 等級 0：不適用
- 等級 1：啟動
- 等級 2：發展
- 等級 3：標準化
- 等級 4：管理
- 等級 5：協同

各行業對成熟度模型等級的術語有所不同，例如：

- 等級 0：無、從未、可忽略、不適用
- 等級 1：啟動、調查、隱含、個人導向、非正式使用
- 等級 2：發展、描述、複製、直接導向、部門使用
- 等級 3：標準化、規範、擴展、服務導向、區段使用
- 等級 4：管理、衡量、主流、任務導向、大規模使用
- 等級 5：協同、創新、持續、機會導向、超大規模使用

## 成熟度模型範例

歡迎提供成熟度模型範例。如果您知道任何成熟度模型，請透過建立 GitHub issue 或 pull request 告知我們。

一般成熟度模型：

- [美國國家衛生研究院（NIH）能力等級量表](examples/skill/us-nih-proficiency-scale/index.md)
- [Dreyfus 技能習得模型](examples/skill/dreyfus-model-of-skill-acquisition/index.md)

主題成熟度模型：

- 敏捷
  - [敏捷團隊成熟度羅盤](examples/agile/agile-compass-for-maturity-in-agile-teams/index.md)
  - [敏捷流暢度模型](examples/agile/agile-fluency/index.md)
  - [HPE 敏捷 DevOps 成熟度模型](examples/agile/agile-devops-maturity-model-by-hewlett-packard-enterprise-hpe/index.md)
  - [ThoughtWorks 敏捷成熟度模型（AMM）](examples/agile/agile-maturity-model-by-thoughtworks/index.md)
  - [Prowareness 敏捷團隊成熟度模型](examples/agile/agile-team-maturity-model-by-prowareness/index.md)
- 能力
  - [卡內基美隆 SEI 能力成熟度模型整合（CMMI）- 開發](http://resources.sei.cmu.edu/asset-files/TechnicalReport/2006-005-001-14771.pdf)
  - [卡內基美隆 SEI 能力成熟度模型整合（CMMI）- 採購](http://resources.sei.cmu.edu/asset-files/TechnicalReport/2007-005-001-14897.pdf)
- 持續改進
  - [持續改進會議成熟度模型](continuous-improvement-meetings-maturity-model/index.md)
- 持續交付
  - [Xebia 持續交付成熟度模型](examples/continuous-delivery/continuous-delivery-maturity-model-by-xebia/index.md)
- 資料中心
  - [Xebia 資料中心自動化成熟度模型](examples/data-center/data-center-automation-maturity-model-by-xebia/index.md)
- 企業架構
  - [TOGAF 企業架構成熟度模型](examples/software/enterprise-architecture/togaf-maturity-model/index.md)
  - [基於 CMMI CM SEI 的企業架構成熟度模型](examples/software/enterprise-architecture/enterprise-architecture-maturity-model-based-on-cmmi-cm-sei/index.md)
- 企業資訊管理（EIM）
  - [Gartner EIM 成熟度模型](examples/eim/gartner-eim-maturity-model/index.md)
- 綠色軟體
  - [綠色軟體成熟度矩陣](https://maturity-matrix.greensoftware.foundation/)
- 身分與存取管理（IAM）
  - [Gartner IAM 計畫成熟度模型](examples/iam/iam-program-maturity-model-by-gartner/index.md)
- 基礎設施即程式碼（IaC）
  - [Joel Parker Henderson 基礎設施即程式碼成熟度模型](examples/infrastructure-as-code/infrastructure-as-code-maturity-model-by-joel-parker-henderson/index.md)
  - [Stafford 基礎設施即程式碼成熟度模型](examples/infrastructure-as-code/infrastructure-as-code-maturity-model-by-stafford/index.md)
- 資訊科技（IT）
  - [IVI IT 能力成熟度框架](examples/it/it-capability-maturity-framework-by-innovation-value-institute/index.md)
  - [Poss 技術領導職涯階梯](examples/it/technical-leadership-career-ladder-by-poss/)
- 管理
  - [Gartner 計畫與投資組合管理成熟度模型](examples/management/program-and-portfolio-management-maturity-model-by-gartner/index.md)
  - [Priority Systems 專案投資組合管理成熟度等級](examples/management/project-portfolio-management-maturity-levels-by-priority-systems/index.md)
  - [OGC P3M3 投資組合、計畫與專案管理成熟度模型](examples/management/porfolio-programme-project-management-maturity-model-p3m3-by-ogc/index.md)
- 開源
  - [開源成熟度模型](examples/software/open-source/opensource-maturity-model/index.md)
- 產品
  - [Kwan 產品需求層級](examples/product/kwans-hierarchy-of-product-needs/index.md)
- 專業服務（PS）
  - [SPI Research PS 成熟度評分卡](examples/ps/ps-maturity-scorecard-by-spi-research/index.md)
- 技能
  - [程式設計師能力矩陣](examples/programming/programmer-competentcy-matrix/index.md)
  - [Prowareness 技能成熟度模型](examples/skill/skills-maturity-model-by-prowareness/index.md)
- 六標準差
  - [精實六標準差成熟度模型](examples/six-sigma/lean-six-sigma-maturity-model/index.md)
  - [六標準差成熟度模型 ™](examples/six-sigma/six-sigma-maturity-model/index.md)
- 社群媒體
  - [社群媒體成熟度模型](examples/social-media/social-media-maturity-model/index.md)
- 軟體文件
  - [README 成熟度模型](examples/software-documentation/readme-maturity-model/index.md)
- 團隊
  - [novumAVI 團隊能力成熟度模型](examples/team/team-capability-maturity-model-by-novumavi/index.md)
  - [團隊績效成熟度模型](examples/team/team-performance-maturity-model/index.md)
- 供應商
  - [Apache 專案成熟度模型](https://community.apache.org/apache-way/apache-project-maturity-model.html)

## 成熟度模型流程觀點

P3M3® 描述了流程觀點，可於所有成熟度模型等級進行評估。

- 控制管理：組織對現行專案的控制能力
- 效益管理：組織如何定義、追蹤並確保投資帶來的績效提升
- 財務管理：組織如何透過商業案例與預算控制管理投資
- 利害關係人管理：專案如何與外部環境互動，降低負面影響
- 組織治理：組織如何將投資與企業策略對齊
- 風險管理：組織如何聚焦並降低威脅、把握機會
- 資源管理：組織如何培養人才並善用供應鏈資源

## 自上而下 vs. 自下而上

設計成熟度模型有兩種方法：

- 自上而下：先定義成熟度階段，再以特徵（如評估項目）佐證階段假設
- 自下而上：先定義特徵或評估項目，再歸納分群為成熟度階段

## 建模成熟度等級

建模成熟度等級（Modeling Maturity Levels）由 Anneke Kleppe 與 Jos Warmer 在其著作《MDA Explained》中提出。該等級描述建模在軟體專案中的角色，與能力成熟度模型（CMMI）有相似之處。

參見：

- https://en.wikipedia.org/wiki/Modeling-Maturity-Levels
- http://www.devx.com/enterprise/Article/26664

共分六級：

- **等級 0：無規格**：軟體規格未書面化，僅存於開發者腦中
- **等級 1：文字規格**：以自然語言（如中文、英文）撰寫於文件中
- **等級 2：文字加模型**：以文字為主，輔以模型說明系統結構
- **等級 3：模型加文字**：以模型為主，文字輔助說明細節、背景與動機
- **等級 4：精確模型**：以模型完整描述，文字僅作註解
- **等級 5：僅模型**：模型足以自動產生完整程式碼，開發者無需檢查產生碼

## 對成熟度模型的反駁

- [James Bach：成熟度模型的不成熟](http://www.satisfice.com/blog/archives/581)
- [Michael Bolton：成熟度模型本末倒置](http://www.developsense.com/blog/2009/10/maturity-models-have-it-backwards/)
- [James Bach：沒有最佳實踐](http://www.satisfice.com/blog/archives/27)
- [CMM 的不成熟](http://www.satisfice.com/articles/cmm.shtml)
- [Barry O'Reilly：為什麼成熟度模型行不通](https://barryoreilly.com/explore/blog/why-maturity-models-dont-work/)

## 相關評估指標

- [Tom Peters 卓越審核十大指標](examples/the-excellence-audit-top-ten-by-tom-peters/index.md)
- [Tom Peters 優秀專業服務公司](examples/great-professional-service-firms-by-tom-peters/index.md)

## 常見問題

### 我可以創建成熟度模型嗎？

可以。任何人都可以創建成熟度模型。許多組織會根據公開模型或內部資訊自行設計，或諮詢專家顧問。本專案收錄了來自不同組織與個人的多種成熟度模型。

### 誰決定成熟度模型的內容？

創建團隊自行決定內容。建議使用「決策記錄」來協助團隊研究、記錄選擇，方便他人理解與應用。

### 成熟度模型是時間快照還是未來規劃？

是時間快照。優秀團隊會以快照為基礎，規劃未來提升成熟度的路徑。

### 成熟度模型是描述性還是規範性？

描述性。成熟度模型描述等級與項目，不規範如何晉級。少數模型會附加建議，但這屬於模型本身特性。

### 成熟度模型可以隨時間演進嗎？

可以。組織成長時，成熟度模型也可調整。例如每年檢視模型，確保其持續有用並依目標更新。

### 成熟度模型有終點嗎？

有。當模型對團隊不再有用時即為終點。例如團隊已達最高等級或能力，或決定現狀已足夠。

### 成熟度模型與科學模型有何不同？

不同。成熟度模型是協助團隊溝通現況與規劃未來的簡明工具。「模型」意指代表更大、更複雜或抽象事物的小型事物。科學模型則用於解釋與預測現實系統行為，如視覺化模型或預測模型。

### 成熟度模型可驗證嗎？

可以。成熟度模型可用質性或量化指標描述等級與項目。例如程式設計師可用「等級 1：寫出 Hello World 程式」到「等級 5：協同運作全球分散式系統」來驗證。
