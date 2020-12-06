# ESP8266-Remote-Message-Board
A wifi connected message board to display messages of your choice on an LED matrix display.

Connect to the ESP web-server, enter your message and it is displayed in a scrolling banner on the attached LED Matrix display.

Display type: MAX7219 4 serial connected 8x8 LED matrix units

NOTE: The LED matrix displays come in many different formats, so you may need to rotate your displays differently! The code has provision for that.

1. Download the ESP_Message_Board_V2 code

2. Compile and upload

3. Wait for the ESP to start

4. Check your aviable WiFi networks, look for 'MessageBoard', then connect to it

5. In your browser enter http://192.168.4.1/

6. Enter some new text to be displayed

7. The message board is a self-contained system, so no WiFi required.

8. If you want to change the IP address modifiy the code accordingly.
