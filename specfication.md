# 技術規格 
WF8266T由台灣通聯行動創意科技有限公司設計發展, 其核心晶片為 ESP8266 上海樂鑫公司設計, 台積電負責生產, 採用 CMOS 40nm 先進製程, 實現了高達 27dBm 的大功率, 並通過歐盟 FCC CE MSDS RoHS 標準檢驗.

## Wi-Fi 晶片 ESP12E

* WiFi Direct (P2P)、soft-AP
* 整合 TCP/IP 協議
* 整合 TR switch、 balun、LNA、 PA 和 matching network
* 整合 PLLs、穩壓器、DCXO 和電源管理單元
* 802.11b模式下 +19.5dBm 的輸出功率
* 小於 10uA 的漏电流
* 整合低功耗 32 位元 CPU，可以兼作應用處理器
* SDIO 1.1/2.0、 SPI、UART
* STBC、 1×1 MIMO、2×1 MIMO
* A-MPDU & A-MSDU 聚合 & 0.4ms 的保護間隔
* 2ms 之内唤醒並開始傳送資料
* 待機狀態消耗功率少於 1.0mW (DTIM3)
 

## 其它晶片
* USB serial bridge controller PL2303SA
* 128 LEDs controller TM1629

## WF8266T
![](imgs/WF8266T-PCBPin.png)
* 9個 GPIO
* 1個 ADC
* 1個 LED (GPIO2)
* 2個 按鍵 UPDATE(GPIO0) / RST(RST)
* 3V3 輸出
* 5V 輸入
* 2組 Rx Tx (3V3)
* SPI
* I2C
* I2S
* 4 MBytes Flash

