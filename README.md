# 後端工程師面試作答整理

本儲存庫集中整理使用者系統 API 設計、Debug 問題分析，以及使用 AI 的提問與討論紀錄，供面試閱讀與說明。

## 作答文件

| 文件 | 內容 |
|---|---|
| [使用者系統 API 設計報告](使用者系統_API設計報告.md) | 註冊、登入、查詢本人資料的 endpoint、資料表與設計理由 |
| [Debug 問題分析](Debug問題分析.md) | API 回應約 3 秒與 500 萬筆 logs 查詢的原因分析及改善方式 |
| [AI 協作過程簡述](AI協作過程簡述.md) | AI 使用方式、主要提問、討論與結論節錄 |

## 設計範圍

- 使用者為一般會員，登入後只能查詢自己的資料。
- 以 Node.js、Express、PostgreSQL、TypeORM、bcrypt 與 JWT 為設計基礎。
- 文件沿用既有健身課程專案的 API 路徑，並明列設計建議與程式現況的差異。
- 本儲存庫提供本次作答文件，既有程式碼與啟動方式請見下方參考專案。

## 參考專案

- [FitConnect 健身課程預約平台](https://github.com/AndyLinStrongtyping/node-js-final-2026)
- [既有專案 OpenAPI 規格](https://github.com/AndyLinStrongtyping/node-js-final-2026/blob/main/docs/openapi.yaml)
- [後端程式碼講義合規檢查](https://github.com/AndyLinStrongtyping/node-js-final-2026/blob/main/後端程式碼_講義合規檢查_不含容器化.md)
- [驗證與授權流程講義合規檢查](https://github.com/AndyLinStrongtyping/node-js-final-2026/blob/main/驗證與授權流程_講義合規檢查.md)
