# NoWOL

Open initiative to rule PC power supply over the net.

Узнай о чём речь здесь https://developersu.blogspot.com/2018/04/nowol-1.html

## Requirements

* Eagle CAD 7.7 (sci-electronics/eagle)

* dev-embedded/arduino

* Android 4.0 + [see android project](https://github.com/developersu/NoWOL-APK) or WEB-browser

*  Arduino nano (but not important)

  OR 

  Part     Value          Device         Package       Library       Sheet

C1       22pF           C-EUC0603      C0603         resistor      1

C2       22pF           C-EUC0603      C0603         resistor      1

C3       10uF           CC0603         C0603         eagle-ltspice 1

C4       22uF           CC0603         C0603         eagle-ltspice 1

IC1      MEGA328p       MEGA328p       TQFP32-08     avr-6         1

IC3      LM1117IMPX-3.3 LM1117IMPX-3.3 SOT223        lm1117        1

JP1                     PINHD-2X5      2X05          pinhead       1

JP3                     PINHD-1X2      1X02          pinhead       1

Q1       16MHz          XTAL/S         QS            special       1

SV1                     MA05-1         MA05-1        con-lstb      1

U1                      USB""          USB-MICRO-SMD MicroUSB      1



AND



КР293КП4А                           x2

PINHD-1X6                           x2

Resistor 450 Ω OR 470 Ω (0204/5)    x2

Resistor 330 Ω (0204/5)             x1

PINHD-1X5                           x1




## License

Source code and hardware-related documents (such as Eagle PCB layout) spreads under the GNU General Public License v.3. You can find it in LICENSE file. 

PAY ATTENTION ON EXCEPTIONS!

All rights to КР293КП4А.pdf datasheet file belongs to 'ЗАО ПРОТОН', г.Орёл, Россия.

No idea who owns eagle_files/lib, but they're NOT mine. Please let me know if you're owner and want me to remove them/update information regarding authorship.

Library ethercard-master (arduino_sketchbook/libraries/ethercard-master/) spreads under GNU GPL2. 

Information about author and more see in arduino_sketchbook/libraries/ethercard-master/README.md file.

Images, if not noted, spreads under a Creative Commons Attribution 4.0 International License. Please see http://creativecommons.org/licenses/by/4.0/ to know more.