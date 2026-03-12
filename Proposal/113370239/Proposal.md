# Abstract

遊戲名稱：Super Mario Bros. 

組員：

- 113370239 徐法恩

# Game Introduction

**遊戲簡介** <br>
Super Mario Bros 是經典的2D橫向捲軸遊戲。玩家需要操作角色在關卡中移動、跳躍，躲避敵人與障礙物，同時收集金幣並探索地圖。成功抵達關卡終點則代表完成關卡。

[遊戲影片](https://www.youtube.com/watch?v=R59Pb_rVbto)

**期望完成內容** <br>
本專案將使用 C++ 與 PTSD (Practical Tools for Simple Design) Engine 開發。預計實作角色移動與跳躍的物理系統、Tilemap 地圖讀取、碰撞偵測系統，以及敵人與道具互動。遊戲也會包含基本 UI（分數、生命值等）與關卡完成判定，使整體遊戲流程完整且可遊玩。

# Development timeline

- Week 2：蒐集素材與熟悉環境
  - [ ] 蒐集 Mario 相關 Sprite 與音效
  - [ ] 熟悉 PTSD Engine 的基本操作
  - [ ] 測試 Sprite 的載入與顯示

- Week 3：OOP 架構設計
  - [ ] 設計 GameObject 基底類別
  - [ ] 設計 Player / Enemy / Block 等主要類別
  - [ ] 實作基本 update() / draw() 流程

- Week 4：玩家移動系統
  - [ ] 實作角色左右移動
  - [ ] 加入跳躍機制
  - [ ] 建立基本重力系統

- Week 5：Tilemap 地圖系統
  - [ ] 建立 tilemap 地圖資料格式
  - [ ] 載入地圖並渲染地板與磚塊

- Week 6：碰撞系統
  - [ ] 玩家與地面碰撞
  - [ ] 玩家與磚塊碰撞

- Week 7：敵人系統
  - [ ] 實作基本敵人（Goomba）
  - [ ] 處理玩家與敵人的互動

- Week 8：Camera 與系統整合
  - [ ] 實作 Camera 跟隨玩家移動
  - [ ] 加入 coin 收集系統
  - [ ] 建立基本 UI

---

- Week 9：期中 Demo
  - [ ] 展示目前完成的遊戲系統

Demo 預計內容：
  - [ ] 角色可左右移動
  - [ ] 角色可跳躍
  - [ ] 地圖系統運作
  - [ ] 出現敵人
  - [ ] 可踩敵人
  - [ ] 可收集金幣

---

- Week 10：關卡系統
  - [ ] 建立 Level Loader
  - [ ] 設計關卡資料結構

- Week 11：關卡內容擴充
  - [ ] 設計新的關卡地形
  - [ ] 配置敵人與金幣

- Week 12：特殊場景
  - [ ] 建立地下或特殊場景
  - [ ] 加入水管傳送等機制

- Week 13：進階關卡設計
  - [ ] 設計不同地形配置
  - [ ] 增加平台與障礙物

- Week 14：過關機制
  - [ ] 實作旗桿或終點判定
  - [ ] 完成關卡轉換邏輯

- Week 15：UI 與音效
  - [ ] 顯示分數與生命值
  - [ ] 加入遊戲音效與背景音樂

- Week 16：測試與優化
  - [ ] 修復 bug
  - [ ] 調整遊戲平衡與操作手感

- Week 17：提交與驗收
  - [ ] 錄製遊戲展示影片
  - [ ] 製作期末簡報
  - [ ] 整理並提交專案