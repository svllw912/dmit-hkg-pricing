# 香港 VPS 價格：DMIT 香港全套餐實價對比，從 $36.9/年入門款到 CN2 GIA 旗艦，按預算挑對線路

## 先給答案：香港 VPS 的價格範圍

在同一家商家、同一個香港機房裡，1 核 1GB 的規格可以從 $6.90/月賣到 $39.90/月，差 5.8 倍，而流量反而是便宜那台更多。

這不是定價混亂，是香港 VPS 這個品類的特性。你付的差價大部分不是買 CPU 和記憶體，是買路由。搞清楚這件事，任何一張香港 VPS 價格表都看得懂了。

下面用 DMIT 的香港產品線拆一遍實際價格。DMIT 是註冊在美國、由華人團隊營運的主機商，機房分佈在洛杉磯、香港與東京，香港節點位於 Equinix HK2。全線走 KVM 虛擬化，硬體是 AMD EPYC 處理器——AS3 平台為 EPYC 7003 系列，AN5 平台為 9005 系列。每個方案預設 1 個 IPv4 加 1 個 IPv6 /64。

## 香港三條線路，對應三種價格

**Premium（方案名帶 Pro）**：電信去程 CN2 GIA 直連香港 CTG、回程同樣走 CN2 GIA；聯通走 AS4837 + AS10099；移動走香港 CMI 直連。三網都做優化，全線最貴。

**Eyeball（方案名帶 EB）**：電信去程 CN2、回程 163；聯通回程 CUG + CMI 動態負載；移動回程 CMI。官方目前仍把香港 Eyeball 標記為 Beta，路由還在持續調整。

**Tier 1（方案名帶 T1）**：純國際骨幹互聯，接入 RETN、NTT 等國際 Tier 1 網絡，香港到歐洲的延遲表現不錯，但中國大陸方向完全沒有專項優化。

## 表一：HKG.AS3.T1，年付 $36.90 起

這是香港價格的窪地，也是流量最寬的一檔。最關鍵的規則差異：流量用完不會斷線，只會限速。

| 方案 | vCPU | 記憶體 | SSD | 月流量 / 端口 | 超量後 | 價格 | 計費週期 | 立即入手 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| HKG.AS3.T1.WEE | 1 | 1GB | 20GB | 1TB @ 4Gbps | 限速 50Mbps 不限量 | $36.90 | 年付 | [以年付 $36.90 入手入門款](https://www.dmit.io/cart.php?region=hong-kong&generation=as3&network=tier-1&aff=12046) |
| HKG.AS3.T1.TINY | 1 | 1GB | 20GB | 2TB @ 4Gbps | 限速 100Mbps 不限量 | $6.90 | 月付 | [查看 TINY 方案](https://www.dmit.io/cart.php?region=hong-kong&generation=as3&network=tier-1&aff=12046) |
| HKG.AS3.T1.STARTER | 1 | 2GB | 40GB | 4TB @ 10Gbps | 限速 100Mbps 不限量 | $12.90 | 月付 | [查看 STARTER 方案](https://www.dmit.io/cart.php?region=hong-kong&generation=as3&network=tier-1&aff=12046) |
| HKG.AS3.T1.MINI | 2 | 2GB | 60GB | 8TB @ 10Gbps | 限速 100Mbps 不限量 | $21.90 | 月付 | [查看 MINI 方案](https://www.dmit.io/cart.php?region=hong-kong&generation=as3&network=tier-1&aff=12046) |
| HKG.AS3.T1.MICRO | 4 | 4GB | 80GB | 16TB @ 10Gbps | 限速 200Mbps 不限量 | $32.90 | 月付 | [查看 MICRO 方案](https://www.dmit.io/cart.php?region=hong-kong&generation=as3&network=tier-1&aff=12046) |
| HKG.AS3.T1.MEDIUM | 4 | 8GB | 160GB | 32TB @ 10Gbps | 限速 200Mbps 不限量 | $49.90 | 月付 | [查看 MEDIUM 方案](https://www.dmit.io/cart.php?region=hong-kong&generation=as3&network=tier-1&aff=12046) |
| HKG.AS3.T1.LARGE | 8 | 16GB | 320GB | 64TB @ 10Gbps | 限速 500Mbps 不限量 | $99.90 | 月付 | [查看 LARGE 方案](https://www.dmit.io/cart.php?region=hong-kong&generation=as3&network=tier-1&aff=12046) |
| HKG.AS3.T1.GIANT | 8 | 24GB | 640GB | 128TB @ 10Gbps | 限速 1Gbps 不限量 | $199.90 | 月付 | [查看 GIANT 方案](https://www.dmit.io/cart.php?region=hong-kong&generation=as3&network=tier-1&aff=12046) |

八個檔位裡，WEE 是唯一只賣年付的。$36.90/年這個價位基本等於「我需要一個香港 IP 存在，其他都不重要」的入場券，算下來每月約 $3。從 TINY 開始轉為月付制。

流量標示寫的是「Max (IN, OUT)」，意思是進出流量取最大值計算，不是兩者相加。

## 表二：HKG Premium（CN2 GIA），$39.90/月起

| 方案 | vCPU | 記憶體 | SSD | 月流量 | 價格 | 計費週期 | 立即入手 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| HKG.AN5.Pro.TINY | 1 | 1GB | 20GB | 500GB @ 1Gbps | $39.90 | 月付 | [查看 Pro TINY](https://www.dmit.io/cart.php?region=hong-kong&network=premium&aff=12046) |
| HKG.AN5.Pro.STARTER | 1 | 2GB | 40GB | 1TB @ 1Gbps | $79.90 | 月付 | [查看 Pro STARTER](https://www.dmit.io/cart.php?region=hong-kong&network=premium&aff=12046) |
| HKG.AN5.Pro.MINI | 2 | 2GB | 60GB | 1.5TB @ 1Gbps | $119.90 | 月付 | [查看 Pro MINI](https://www.dmit.io/cart.php?region=hong-kong&network=premium&aff=12046) |
| HKG.AN5.Pro.MICRO | 2 | 4GB | 80GB | 2TB @ 1Gbps | $159.90 | 月付 | [查看 Pro MICRO](https://www.dmit.io/cart.php?region=hong-kong&network=premium&aff=12046) |
| HKG.AN5.Pro.MEDIUM | 4 | 4GB | 160GB | 2.5TB @ 1Gbps | $179.90 | 月付 | [查看 Pro MEDIUM](https://www.dmit.io/cart.php?region=hong-kong&network=premium&aff=12046) |
| HKG.AN5.Pro.LARGE | 4 | 8GB | 240GB | 3TB @ 1Gbps | $239.90 | 月付 | [查看 Pro LARGE](https://www.dmit.io/cart.php?region=hong-kong&network=premium&aff=12046) |
| HKG.AN5.Pro.GIANT | 8 | 16GB | 320GB | 6TB @ 1Gbps | $499.90 | 月付 | [查看 Pro GIANT](https://www.dmit.io/cart.php?region=hong-kong&network=premium&aff=12046) |

超量規則跟 T1 完全不同：Pro 系列流量跑完是暫停服務，不是限速。這對跑影片分發或大流量 API 的人來說是個要提前算清楚的坑。

還有一個容易買錯的地方。官網上 Pro 系列同時存在 AS3 和 AN5 兩種平台，方案名稱裡的平台代碼要看清楚。AS3 舊款檔位的標價通常高一截，同為 2 核 2GB/60GB/1.5TB，AN5 標 $119.90/月，AS3 標 $126.90/月。DMIT 已把常規 Pro 產品線往 AN5 遷移，下單前確認一下實際拿到的平台。另外也有來源提到部分高規 AN5 Pro 檔位（4 核起、80GB 起）落在 $149.90/月以上，走的是更高規格配置，同樣以官網即時顯示為準。

## 表三：HKG Eyeball，$24.90/月起

| 方案 | vCPU | 記憶體 | SSD | 月流量 / 端口 | 價格 | 計費週期 | 立即入手 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| HKG.AS3.EB.WEE | 1 | 1GB | 20GB | 500GB @ 500Mbps | $24.90 | 月付 | [查看 EB 入門款](https://www.dmit.io/cart.php?region=hong-kong&network=eyeball&aff=12046) |
| HKG.AS3.EB.TINY | 1 | 1GB | 20GB | 800GB @ 1Gbps | $39.90 | 月付 | [查看 EB TINY](https://www.dmit.io/cart.php?region=hong-kong&network=eyeball&aff=12046) |
| HKG.AS3.EB.STARTER | 1 | 2GB | 40GB | 1.5TB @ 1Gbps | $79.90 | 月付 | [查看 EB STARTER](https://www.dmit.io/cart.php?region=hong-kong&network=eyeball&aff=12046) |
| HKG.AS3.EB.MINI | 2 | 4GB | 60GB | 2.2TB @ 1Gbps | $126.90 | 月付 | [查看 EB MINI](https://www.dmit.io/cart.php?region=hong-kong&network=eyeball&aff=12046) |
| HKG.AS3.EB.MICRO | 4 | 4GB | 80GB | 3TB @ 1Gbps | $179.90 | 月付 | [查看 EB MICRO](https://www.dmit.io/cart.php?region=hong-kong&network=eyeball&aff=12046) |
| HKG.AS3.EB.MEDIUM | 4 | 8GB | 160GB | 4TB @ 1Gbps | $239.90 | 月付 | [查看 EB MEDIUM](https://www.dmit.io/cart.php?region=hong-kong&network=eyeball&aff=12046) |

Eyeball 另有 AN5 平台的高規格版本，價格區間從 4 核 4GB/80GB 的 $149.90/月起，一路到 12 核 24GB/640GB 的 $759.90/月。這條線跟 Pro 的差價邏輯不一樣：同價位下 EB 給的流量大約是 Pro 的 1.6 倍，換掉的是線路保證。

## 把三張表疊在一起看，差價的來源就清楚了

規格完全相同的 1 核 1GB / 20GB SSD，在香港有三種價錢：

- **HKG.AS3.T1.TINY**：$6.90/月，2TB 流量、4Gbps 端口、國際線路
- **HKG.AS3.EB.TINY**：$39.90/月，800GB 流量、1Gbps 端口、CMI 回程
- **HKG.AS3.Pro.TINY**：$39.90/月，500GB 流量、1Gbps 端口、三網 CN2 GIA

最便宜那台的流量是另外兩台的四倍。所以如果你的用途只是要一個香港出口跑跨境抓取、異地備份、國際 API 中轉，T1 是唯一合理的答案，多花的錢買不到你需要的東西。

反過來，如果使用者或訪客在中國大陸，而且在意晚高峰的穩定度，T1 省下的錢會在使用者體驗上還回去。這也是香港 VPS 價格問題的核心：你需不需要中國大陸方向的優化。

## 年付真的比較便宜嗎

算一下就知道答案比想像中不直觀。DMIT 的年付定價基本上就是月付價乘 12：

- HKG.AS3.T1.STARTER：$12.90 × 12 = $154.80，年付標價剛好 $154.80
- HKG.AN5.Pro.TINY：$39.90 × 12 = $478.80，年付標價 $478.00

差距小到可以忽略。T1.TINY 是少數例外，$6.90/月 對上 $76.90/年，年付省下約 $6。

結論是：真正的折扣不在計費週期，而在優惠碼與活動。這跟很多商家的直覺相反，所以不要以為「年付一定划算」就自動把週期拉到一年——尤其在香港庫存經常告急、方案可能調整的情況下，先按月付試一段更穩妥。

## 優惠碼：目前能確認的狀態

這部分得說實話。網路上大量標著「最新優惠碼」的文章，其實是把舊活動頁翻出來重貼。DMIT 官方有一個 HKG Tier 1 升級活動頁，頁面開頭已經明寫「HKG Tier 1 系列產品升級優惠活動已結束」，但那個 45% 折扣碼還是持續在各種整理文裡流傳。

我這一輪查到的資料中，多數近期補貨通知的說法是「已是特價，暫無有效優惠碼」；少數列出代碼的來源（例如針對 HKG/TYO 系列的循環折扣碼）在現有資料裡無法交叉驗證是否仍生效。

比較實際的做法：在結帳頁選好方案和週期後，把碼填進 Validate Code 欄位驗證，通過了再下單。驗證不通過的代碼不會有任何作用，也不會產生扣款。

## 按預算的三種選法

**每月 $10 以內**：只有 T1 系列可選。$6.90 的 TINY 或 $12.90 的 STARTER，對應國際業務、開發測試、需要香港 IP 但不服務大陸使用者的場景。流量用完限速不斷線這個設計，對跑自動化任務的人特別友好，不用半夜爬起來處理流量報警。

**每月 $40 上下**：這是分水嶺。$39.90 可以買到 Eyeball 的 TINY，也可以買到 Premium 的 TINY。使用者以移動網絡為主的選 EB 性價比更高；三網都要顧、尤其電信用戶占比高的，Pro 值那筆溢價。要留意 Eyeball 官方仍標 Beta，路由可能再調。

**每月 $120 以上**：Pro 系列的中高階檔位，對應企業站、跨境電商、對延遲和丟包有硬要求的業務。到這個價位，比較對象已經不是其他香港 VPS，而是「要不要直接上獨立伺服器」。

👉 [查看 DMIT 香港目前全部在售方案與即時價格](https://www.dmit.io/aff.php?aff=12046)

## 下單前要確認的五件事

1. **平台代碼**：方案名裡的 AS3 / AN5 決定 CPU 平台，也影響同規格下的標價，別買錯。
2. **超量規則**：T1 限速不限量，Pro 與 EB 是流量用完暫停。差別極大，先算好月流量再選。
3. **Beta 標記**：香港 Eyeball 官方仍標示 Beta，路由與性能可能繼續調整，不適合當成對穩定性要求高的正式環境。
4. **庫存**：DMIT 香港經常缺貨，尤其是 Pro 的低價檔位。看到有貨就別拖。
5. **產品線變動**：DMIT 會週期性調整甚至停售香港部分產品線，過去就發生過整條系列停止服務、並向受影響用戶提供遷移折扣的情況。下單前確認當前在售狀態。

## 幾個常見問題

**香港 VPS 為什麼普遍比美國貴？**
香港機房的頻寬單位成本本來就高，加上 CN2 GIA 這類中國大陸優化線路的採購成本昂貴。同樣配置的機器，走 CN2 GIA 的價格常是普通國際線路的數倍，DMIT 自己也公開提過 IP 租賃成本近年大幅上漲。

**$36.90/年那台能拿來建站嗎？**
能跑，但要知道買的是國際線路。訪客在歐美、東南亞沒問題，訪客在中國大陸就要看具體線路表現。另外 1GB 記憶體跑完整 LNMP 棧會很吃緊。

**可以中途換線路嗎？**
不行。T1、EB、Pro 是三條獨立產品線，要換只能重新購買，資料得自己遷移。

**支援哪些付款方式？**
支付寶、微信支付、PayPal。

**同一個方案名稱，為什麼不同文章寫的價格不一樣？**
因為 DMIT 這一年多在把香港產品線從 AS3 平台往 AN5 遷移，同一個檔位的規格與標價在新舊平台間存在差異，加上檔位會補貨、停售、調整。看到任何價格表，都以官網下單頁當下顯示的數字為準。
