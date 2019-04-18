# -Arduino-
語音控制Arduino機器人車（藍牙和應用）

(H/W連接)：
藍芽模組：
1. 藍牙RX連接到Arduino TX輸入
2. 藍牙TX連接到Arduino RX輸入
3. Arduino GND連接到藍牙模塊GND 
4. Arduino + 5V連接到藍牙模塊VCC

馬達模組：
1. 馬達屏蔽連接到Arduino板
2. 左直流馬達連接到馬達驅動板M1輸入
3. 右側直流馬達連接到馬達驅動板M2輸入
4. 電池扣連接到馬達驅動板+V和GND

(關於程式)：
1. 首先應該添加LIB
1-1 下載Adafruit-Motor-Shield-library-master.zip ,獲得AFMotor.h
或到下載地址：https：//github.com/adafruit/Adafruit-Motor-Shield-library
1-2 Servo.h LIB 是標準庫不用另外安裝

2. Arduino程式碼 
2-1. Arduino板連接到PC 
2-2. 打開Arduino新草圖
2-3. 複製voice-app-robot.並貼上程式碼 

3. 上傳至Arduino
3-1 上傳時，請斷開藍牙連接
3-2 下載並安裝Android手機端應用程式：BT voice control for arduino 
下載地址：https：//play.google.com/store/apps
3-3 如果出現連接錯誤，請重置Arduino並重新啟動應用程序。
