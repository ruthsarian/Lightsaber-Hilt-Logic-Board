# Lightsaber Hilt Logic Board
This is an Arduino IDE sketch for a custom/replacement Galaxy's Edge lighstaber hilt logic board.

This project was started when the microcontroller on my Savi's Workshop lightsaber hilt logic board went bad. In order to provide minimal lightsaber hilt functionality I designed a replacement PCB based on an ATTiny85. The PCB design files are [available on EasyEDA](https://oshwlab.com/ruthsarian/savi-s-logic-board). 

The replacement board does not support reading RFID tags of kyber crystals and instead the blade color can be controlled by turning the hilt off and on. The color will change with each power cycle of the lightsaber hilt. The replacement board does not support sound or swing detection either. It's only purpose is to ignite the blade.

Not much as been done with this code since it was first created. Plans to expand its features have been put aside for the moment, but perhaps someone may find this code useful.
