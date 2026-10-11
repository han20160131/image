# Image AI - Batch Image Generator

免費批量生成圖片的 AI 工具，使用 Pollinations 免金鑰 API。

## 功能

- 批量輸入多個 prompt（每行一個）
- 自動排隊生成（遵守免費速率限制）
- 進度條 + 狀態顯示
- 支援多種尺寸與模型
- 單張 / 全部下載
- 完全在瀏覽器執行，不需要後端

## 使用方式

1. 打開 [GitHub Pages](https://han20160131.github.io/image/) 或直接開啟 `index.html`
2. 在左側輸入多個描述（每行一個）
3. 調整尺寸、模型等設定
4. 點擊「開始批量生成」
5. 等待完成後下載圖片

## 注意事項

- 使用的是 Pollinations 免費端點，有速率限制（約每 10~15 秒一張）
- 品質受限於免費模型，不能超越商業級模型
- 建議不要一次輸入過多提示詞（建議 10~30 個）

## 技術

- 純前端 HTML + CSS + JavaScript
- 圖片來源：`https://image.pollinations.ai/prompt/...`
- 無需 API Key
