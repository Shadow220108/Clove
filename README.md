<h1 align="center">
  <br>
  <img src="https://github.com/Shadow220108/Clove/blob/main/assets/clove.png" alt="apex banner">

  <br>
  Apex
  <br>
</h1>
<h3 align="center">
First ever paw shaped tamagotchi, with 4 buttons, LEDs, screen and battery 
</h3>

| Render | 
| --- |
| ![](https://github.com/Shadow220108/Clove/blob/main/assets/clove_skelly.png) | 

| Zine |
| --- |
| ![](https://github.com/Shadow220108/Clove/blob/main/assets/clove(1).png) |


## PCB Design 
| ![](https://github.com/Shadow220108/Clove/blob/main/assets/clove3.png) |
|--- |  


 ### The PCB is 2 layers with dimensions under 100 by 100mm,   


 ### All the PCB files are [here](https://github.com/Shadow220108/Clove/tree/main/PCB) 

| PCB design |
| --- |
| ![](https://github.com/Shadow220108/Clove/blob/main/assets/PCB(withpour).png) | ![](https://github.com/Shadow220108/Clove/blob/main/assets/PCB(withoutpour).png) |


## Schematics  

Here are the schematic designs,

| Schematics |
| --- |
| ![](https://github.com/Shadow220108/Clove/blob/main/assets/schematics.png) |
  


## Why was it made?  

While using the Seed Studio Xiao RP2040 for one of my projects, I realised it doesn't have LiPo support   
and I couldn't use it, unfortunately I had to use a different MCU then, but now I designed one with  
the simplicity of RP2040 with being able to charge LiPo 

## How you can get one for yourself? 

That is pretty easy, you have all the files you will need in the production folder, order the development  
board from any PCB fab ( I chose JLC cause its cheap and has good quality ) and BINGO! You will have it  
to use for any purpose you want!  

## How do you use it?  
You can use it as any normal RP2040 Devboard, enter the boootloader mode  
by holding the BOOT buttom while connecting to your device, flash it with  
firmware and you are good to go!  I have attached a simple code to blink the LED  
available on the board.  

## BOM  

|Product                       |Description                                      |Quantity   |Unit Price  |Link      |Total cost ( Including Shipping )|
|------------------------------|-------------------------------------------------|-----------|------------|----------|---------------------------------|
|                              |                                                 |           |            |          |                                 |
|PCB                           |to connect and hold all the electronic components|5 ( MOQ )  |2$          |[Link](https://cart.jlcpcb.com/shopcart/cart/)      |12.31$                           |
|Xiao ESP32C6                  |MCU for running the screen                       |1          |7.79$       |[Link](https://robu.in/product/seeed-studio-xiao-esp32c6/)      |8.32$                            |
|0.96" OLED                    |Main display                                     |1          |1.69$       |[Link](https://robocraze.com/products/0-96in-oled-display-module-4pin?variant=40192586645657&country=IN&currency=INR&utm_medium=product_sync&utm_source=google&utm_content=sag_organic&utm_campaign=sag_organic)      |2.22$                            |
|Tactile Switch buttons (6x6mm)|To control the character                         |10 ( MOQ ) |0.10$       |[Link](https://robu.in/product/6x6x5-tactile-push-button-switch/)      |0.10$                            |
|M3x5mm Heastset Inserts       |To hold downt the top and bottom case            |8          |0.10$       |[Link](https://onlyscrews.in/products/hex-allen-csk-m3-x-8-screw-pack-of-20)      |1.50$                            |
|M3x8mm Screws                 |To hold downt the top and bottom case            |8          |0.20$       |[Link](https://onlyscrews.in/products/hex-allen-csk-m3-x-8-screw-pack-of-20)      |0.20$                            |
|Buzzer                        |to make some sounds                              |1          |0.48$       |[Link](https://robu.in/product/1-month-warranty-1248/)      |0.48$                            |
|LiPo Battery                  |To power everything!                             |1          |1.65$       |[Link](https://robu.in/product/wly502025-200mah-3-7v-single-cell-rechargeable-lipo-battery/)      |1.65$                            |
|LEDs                          |They light up                                    |12         |Self sourced|          |                                 |
|Resistors                     |for the battery voltage                          |2          |Self sourced|          |                                 |
|                              |                                                 |           |            |Total cost|26.78                            |


