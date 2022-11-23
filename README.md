# DIY-Wifi-Nugget
This is a DIY version of a Cut Down less cute "Wifi-Nugget" based on the Youtube series "https://youtu.be/_snjqM2Lu70" by Alex Lynd. 

## The Story
This is basically a brain dump so when i burn out my D1 (or loose it) i have a ref guide to come back to. Please note none of my work is original and is just a combination of various legend's and their YouTube/Git repositories. (Props at the End)

## The Detail

### Purchase list
  1x D1 mini ($31.63)
  https://www.amazon.com.au/MakerFocus-NodeMcu-Development-ESP8266-Compatible/dp/B07KW54YSK/ref=sr_1_8?crid=2MTNAW5RJOQ54&keywords=ESP8266+ESP-12F&qid=1666648499&qu=eyJxc2MiOiIyLjA4IiwicXNhIjoiMC4wMCIsInFzcCI6IjAuMDAifQ%3D%3D&s=computers&sprefix=esp8266+esp-12f%2Ccomputers%2C227&sr=1-8

  1x display ($12.22)
  https://www.amazon.com.au/UCTRONICS-SSD1306-Self-Luminous-Display-Raspberry/dp/B072Q2X2LL/ref=d_pd_day0_sccl_2_1/357-0323447-1713873?pd_rd_w=mdHp3&content-id=amzn1.sym.1b47318f-807b-4d2b-bf91-b76a34a92ae4&pf_rd_p=1b47318f-807b-4d2b-bf91-b76a34a92ae4&pf_rd_r=E9S59S6AX02795AXJ3MT&pd_rd_wg=zOSZ1&pd_rd_r=80d253a7-c3e3-4c8e-a808-fea31496ec4b&pd_rd_i=B072Q2X2LL&psc=1
  
  1x breadboard ($13.99)
  https://www.amazon.com.au/ELEGOO-Breadboard-Solderless-Distribution-Connecting/dp/B0772CV9V8/ref=sr_1_1_sspa?keywords=solderless+prototype+breadboard&qid=1666834587&qu=eyJxc2MiOiIxLjU5IiwicXNhIjoiMC4wMCIsInFzcCI6IjAuMDAifQ%3D%3D&sprefix=solderless+proto%2Caps%2C267&sr=8-1-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUExSEo5NTcyWlVLV0JBJmVuY3J5cHRlZElkPUEwMzkwNzEwV1czV1RFUUVZVjhBJmVuY3J5cHRlZEFkSWQ9QTI3WURBV1ZEUUROTjEmd2lkZ2V0TmFtZT1zcF9hdGYmYWN0aW9uPWNsaWNrUmVkaXJlY3QmZG9Ob3RMb2dDbGljaz10cnVl

  1x dip button ($12.21)
  https://www.amazon.com.au/Carhar-6x6x5mm-Through-Momentary-Tactile/dp/B09SNNYWKZ/ref=sr_1_6?crid=17J3JXSDI66T7&keywords=6x6x5mm+4-pin+dip+through+hole+momentary+tactile+push+button+switch&qid=1666834007&qu=eyJxc2MiOiIxLjA1IiwicXNhIjoiMC4wMCIsInFzcCI6IjAuMDAifQ%3D%3D&sprefix=4+pin+dip%2Caps%2C237&sr=8-6

  1x breadboard jumper cables ($9.96)
  https://www.amazon.com.au/120pcs-Multicoloured-Dupont-Breadboard-arduino/dp/B01EV70C78
  
  1x perfboard ($5.50)
  https://www.jaycar.com.au/pc-boards-vero-type-strip-95mm-x-75mm/p/HP9540

### Breadboarding
#### Draw out circuit
![DIY_D1_CirDia](https://user-images.githubusercontent.com/24452466/203536504-212c60fc-d23e-4440-aa77-477c2ff474e7.jpg)
#### Build circuit
![DIY_D1_BB](https://user-images.githubusercontent.com/24452466/203517788-32b3008c-3aee-4b8b-b5c2-204810a432ca.jpg)
Note: Didnt take a pic before i had already completed `Arduino IDE/Code` and tested i could write a project. 

### Arduino IDE/Code
#### Additional Board Manager ULRs (Spacehuhn & HakCat)
https://raw.githubusercontent.com/SpacehuhnTech/arduino/main/package_spacehuhn_index.json
https://arduino.esp8266.com/stable/package_esp8266com_index.json
#### Library dependencies (oLED Driver)
https://github.com/ThingPulse/esp8266-oled-ssd1306

### Prototyping
#### Draw layout
![DIY_D1_PerfDraw](https://user-images.githubusercontent.com/24452466/203536148-29623a71-be3d-4a57-ba96-a4ce66bb36f9.jpg)
#### Build Proto
![DIY_D1_ProtoBck](https://user-images.githubusercontent.com/24452466/203536230-6c0f135e-e909-4db1-a78a-3649404cb0ef.jpg)
![DIY_D1_ProtoFnt](https://user-images.githubusercontent.com/24452466/203536305-bb78bc47-376f-4969-a4b6-c246a544cd7c.jpg)
#### Notes
- I removed one of the buttons (went to 4 from 3) to make the profile as small as possible
- I used some single GPiO pins as stand-offs to support the I2C (indicated by SO in the drawing)
- I did not have a neopixel LED but didnt end up having space for one either so left it off

## Props
https://github.com/HakCat-Tech

https://www.youtube.com/@hak5

https://github.com/ThingPulse

https://github.com/SpacehuhnTech
