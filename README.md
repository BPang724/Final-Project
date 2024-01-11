# Final-Project

### Authors: 111321023 111321057

#### Input/Output unit:<br>
* 8x8 LED 矩陣，顯示對戰畫面。<br>
* 七段顯示器，用來顯示目前得分分數。<br>
* 指撥開關，用來Reset關卡。<br>
* 藍色按壓按鈕，用來操控板子的移動、與球的發射。<br>

#### 功能說明:<br>
透過藍色按壓按鈕操控板子移動去接球，讓球反彈到上面磚塊做碰撞並消除磚塊。<br>

#### 程式模組說明:<br>
module slide_game(output reg[3:0]S //控制亮燈排數,output reg [7:0]Red //紅色燈,output reg [7:0]Green //綠色燈,
output reg [7:0]Blue //藍色燈,output reg [4:0]A_count,B_count //計分,output [6:0]O //倒計時,output reg beep //叫聲,input [1:0]button //玩家一左右,input [1:0]button2 //玩家二左右,input CLk,Clear); <br><br>
*** 請說明各 I/O 變數接到哪個 FPGA I/O 裝置，例如: button, button2 -> 接到 4-bit SW <br>
*** 請加強說明程式邏輯 <br>

#### Demo video:<br>
  因手機摔壞，故無影片與照片，已事前通知助教。
