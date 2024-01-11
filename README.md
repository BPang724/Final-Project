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
module divfreq(input CLK, output reg CLK_div)　//除頻器 <br>
module divmove(input pause, input CLK, output reg CLK_div) //暫停畫面 <br>
module Final(input CLK,
					 input sw_L,
					 input sw_R,
					 input shoot,
					 input pause,
					 input back,
					 output [7:0] lightR,
					 output [7:0] lightG,
					 output [7:0] lightB,
					 output reg [2:0] whichCol,  //控制亮哪排
					 output EN,
					 output reg [3:0] A_count,
						output a, b, c, d, e, f, g				 
); //遊戲專案<br>

lightR[0]～lightR[7]=PIN_111~PIN_121 <br>
lightG[0]～lightG[7]=PIN_72～PIN_80 <br>
lightB[0]～lightB[7]=PIN_135～PIN_144 <br>

sw_L=PIN_65 //連接藍色按壓按鈕，板子移動<br>
sw_R=PIN_66 //連接藍色按壓按鈕，板子移動<br>
shoot=PIN_64 //連接藍色按壓按鈕，遊戲開始，並發射球 <br>
abcdefg=PIN_51~PIN_59 //連接七段顯示器 <br>


#### Demo video:<br>
因手機摔壞，故無影片與照片，已事前通知助教。
