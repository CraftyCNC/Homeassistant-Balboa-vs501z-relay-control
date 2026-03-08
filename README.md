# Homeassistant-Balboa-vs501z-relay-control
Stuff for controlling a hot-tub spa pack via a esphome controlled relay


This gives the setup for an 'open loop' control of an older Balboa vs501z spa pack.  A 6 channel esp32 relay board (Waveshare used as example) is used to control the hot tub via the second rj45 ethernet jack on the control board.  The relay board dry contacts are used to activate the 4 control pannel buttons, Pump1, Pump2, Temp, and Light.  espHome is used on the relay, with the ability to change modes pre-programmed into the espHome yaml file.


<img width="1519" height="1179" alt="balboa-esphome-6ch relay" src="https://github.com/user-attachments/assets/5a325007-baa3-40c7-a98f-57b48d50e292" />
