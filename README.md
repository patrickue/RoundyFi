## RoundyFi
<img src= "https://github.com/sbcshop/RoundyFi/blob/main/images/img.png" />
<img src= "https://github.com/sbcshop/RoundyFi/blob/main/images/img1.png" />


### RoundyFi is a round LCD display based on ESP-12E along with a compact and stylish 1.28-inch display module of 240×240 resolution, 65K RGB colors, clear and colorful displaying effect, expand its engagement with your project. RoundyFi comes with an embedded GC9A01 Driver and SPI Interface that minimize the required IO pins.
<img src= "https://github.com/sbcshop/RoundyFi/blob/main/images/img3.png" />


## Steps To Setup The RoundyFi
1. Download and install Arduino IDE 
   https://www.arduino.cc/en/software

2. Open Arduino IDE
   <img src= "https://github.com/sbcshop/RoundyFi/blob/main/images/img6.JPG" />

3. Now install Esp8266 board, for this go to file -> preferences
   <img src= "https://github.com/sbcshop/RoundyFi/blob/main/images/img7.png" />
  
   * Paste two urls,in "additional board manager urls"
   
     ```http://arduino.esp8266.com/stable/package_esp8266com_index.json```
     
     ```https://dl.espressif.com/dl/package_esp32_index.json```
     
     <img src= "https://github.com/sbcshop/RoundyFi/blob/main/images/img8.png" />
   
   * Now install ESP8266 board, go tools -> boards -> board manager
     <img src= "https://github.com/sbcshop/RoundyFi/blob/main/images/img9.png" />
     
   * Write ESP8266 in search bar
     <img src= "https://github.com/sbcshop/RoundyFi/blob/main/images/img10.png" />
    
   * Lets, check boards are install or not, go to tools -> boards
     <img src= "https://github.com/sbcshop/RoundyFi/blob/main/images/img11.png" />
  
 4. Now go to sketch -> include library -> manage libraries
     <img src= "https://github.com/sbcshop/RoundyFi/blob/main/images/img12.png" />
     
 5. Install all libraries which is mention below
    <img src= "https://github.com/sbcshop/RoundyFi/blob/main/images/img13.JPG" />
    <img src= "https://github.com/sbcshop/RoundyFi/blob/main/images/img14.JPG" />
    <img src= "https://github.com/sbcshop/RoundyFi/blob/main/images/img15.JPG" />
    
 6. Choose Port and ESP8266 board from board manager
    <img src= "https://github.com/sbcshop/RoundyFi/blob/main/images/img16.png" />
    <img src= "https://github.com/sbcshop/RoundyFi/blob/main/images/img17.png" />
  
  
     
See there is a folder name RoundyFi, inside this folder, there are various applications(Example codes):-
  * **Display Weather** -> Display the current weather via the "OpenWeatherMap" website, first of all, you need to make an account in OpenWeatherMap
    https://openweathermap.org/api and copy the API key and paste in the code, 
    <img src= "https://github.com/sbcshop/RoundyFi/blob/main/images/img2.png" />
  
  * **Make Server**  -> Make server using RoundyFi. 
    From this, we can communicate between server and client. for example, we make the mobile phone a client and RoundyFi as a server
    <img src= "https://github.com/sbcshop/RoundyFi/blob/main/images/img4.png" />

  * **Wifi Clock**  -> Make smart clock using wifi, it displays current time and week, using the internet. 
    <img src= "https://github.com/sbcshop/RoundyFi/blob/main/images/img5.png" />

