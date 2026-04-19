# STM32 Lab 5: Basic Problem

利用 STM32 (B-L475E-IOT01A) 的 TIM2 產生 PWM 訊號，應用於 LED 閃爍控制。

* **輸出腳位**：PA5 (LED1) 與 PA15 (D9)
* **PWM 參數**：頻率 2.5 Hz、工作週期 50%
* **驗證方式**：透過 ZEROPLUS 邏輯分析儀量測 D9，確認實際波形與理論設定完全吻合。
