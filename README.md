# 給家長的麥塊入門指南

一份寫給爸媽的 Minecraft 入門說明——孩子在玩什麼、為什麼好玩、家長怎麼開始、怎麼一起玩。

純靜態網站，無建置步驟。

## 內容

- 麥塊的吸引力（為什麼孩子這麼投入）
- 為什麼孩子不玩卻一直看 YouTube
- 融入孩子的三個方法，以及兩個地雷
- **怎麼開始玩**：Java 版 vs 基岩版、微軟兒童帳號與家庭群組、購買管道、盜版警告
- 新手攻略：第一晚 SOP、裝備進程、名詞對照表
- 資源連結

## 本機預覽

直接用瀏覽器開啟 `index.html` 即可，或起一個簡易伺服器：

```bash
npx serve .
```

## 部署

同一份原始碼雙軌託管：

| 平台 | 方式 | 觸發 |
| --- | --- | --- |
| GitHub Pages | 由 `main` 分支根目錄部署 | push 到 `main` |
| Cloudflare Pages | Git 連結（Build command 留空，輸出目錄 `/`） | push 到 `main` |

兩者都不需要建置指令。

## 免責

本站內容為家長視角的整理，非官方資料。遊戲機制數值以 [Minecraft Wiki](https://zh.minecraft.wiki/) 為準。

Minecraft 是 Mojang Studios 的商標，本專案與 Mojang、Microsoft 無關。
