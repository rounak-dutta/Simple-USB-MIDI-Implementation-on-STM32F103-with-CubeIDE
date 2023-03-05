# Simple-USB-MIDI-Implementation-on-STM32F103-with-CubeIDE

This is a simple project to demonstrate the USB MIDI implementation on STM32F103 device using CubeIDE and its inbuilt-libraries. Here the stm32f103c8t6 based board, also known as blue-pill is programmed such that it sends MIDI-Note-On and MIDI-Note-off messages to the host alternatively every 0.5 seconds. The code here can be upgraded to a full fledged MIDI keyboard, by adding switches/ buttons to the microcontroller to send the appropriate notes w.r.t each button press.

Youtube Video:
  

References:
  https://www.usb.org/sites/default/files/midi10.pdf
  https://en.wikipedia.org/wiki/MIDI#:~:text=MIDI%20notes%20are%20numbered%20from,A0%20to%20C8.
  https://www.midi.org/specifications-old/item/table-1-summary-of-midi-message
  https://www.midi.org/specifications-old/item/table-2-expanded-messages-list-status-bytes
  https://github.com/essigt/SpareFaders
