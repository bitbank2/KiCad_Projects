A collection of KiCad PCB projects. I've included the Gerber files (zipped) so that you can directly order these PCBs from your favorite PCB supplier without having to use KiCad.<br>


<img align="left" width="240" src="/images/ds3231.png" />

# DS3231 Plus 

A DS3231 realtime clock breakout board modelled after the RPI RTC boards. The 5 pin header matches the pinout of the Raspberry Pi and adds the interrupt pin (pulled up to 3.3v). It includes a QWIIC connector (JST 4-pin 1mm) and I also added a small switch to completely disconnect the backup battery if you plan on leaving it unused for an extended period of time. There's a small CR44 backup battery soldered to the back side.<br>
<br>
<br>
<br>

<img align="left" width="240" src="/images/lcd_64x32.png" />

# LCD_64x32_Breakout

A tiny breakout board to make it easier to work with the tiny ST7567 32x64 monochrome LCD display. There's nothing really unique about this board, but it certainly makes it easier to work with LCD panels that use flex cables with odd pin spacing (0.6mm in this case). The 8-pin header order was chosen to match the very popular 'blue' LCDs sold by several vendors in China.<br>

<br>
<br>
<br>
<br>
<br>

<img align="left" width="240" src="/images/lcd_hat.png" />

# LCD_HAT

A breakout board to make it easier to connect either a Feather or Nano to the popular 'blue' LCDs available from several vendors in China. These LCDs range from a tiny 0.85" 128x128 ST7735 to a 3.5" 320x480 ILI9488. The PCB also offers a QWIIC I2C connector, 2 momentary push buttons and male 2-pin headers for measuring the power consumption of the QWIIC device or the LCD.<br>

<br>
<br>
<br>

<img align="left" width="240" src="/images/rv3032.png" />

# RV-3032-C7 RTC Breakout

A breakout board modelled after the RPI RTC boards. The 5 pin header matches the pinout of the RPI and adds the interrupt pin (pulled up to 3.3v). It includes a QWIIC connector (JST 4-pin 1mm), and a pad for the CLKOUT signal. There's a small CR44 backup battery on the back. The RV3032 is similar to the DS3231 in that it's a temperature adjusted (very accurate) clock, but it's much smaller, much lower power and about the same price.<br>
<br>
<img align="left" width="240" src="/images/Xiao_Sharp_LCD.png" />

# Xiao Sharp Memory LCD Breakout

A breakout board for QT Py / Xiao MCU boards to easily control Sharp Memory LCDs. These LCDs require a square wave input to balance the charge; this is provided by the onboard RV3032 RTC. It also includes 2 pushbuttons and a QWIIC I2C connector.<br>
<br>
<br>
<img align="left" width="240" src="/images/xiao_lcd_hat.png" />

# Xiao LCD HAT

A breakout board for QT Py / Xiao MCU boards to easily connect SSD1306 OLEDs and 'blue' 7/8-pin LCD breakout boards. It also includes 2 pushbuttons and a QWIIC I2C connector.<br>
<br>
<br>
<img align="left" width="240" src="/images/sharp_feather_nano.png" />

# Sharp Feather/Nano breakout

A breakout board for Feather and Nano MCU boards to easily connect Sharp Memory LCDs. It also includes a RV3032 RTC to drive the VCOM signal of the LCD and act as a low power+reliable realtime clock, 2 pushbuttons and a QWIIC I2C connector.<br>
<br>
<br>
<img align="left" width="240" src="/images/ch32v003_breakout.png" />

# CH32V003 (QFN20) breakout

A breakout board for the WCH CH32V003 RISC-V MCU. This breakout is for the QFN20 version of the chip. I've made the QFN20 footprint easier to hand solder by reducing the size of the center ground pad. This leaves a bit more gap to the pins. I solder them without a stencil by mixing the solder paste with a little extra flux to avoid shorts under the chip body.<br>

