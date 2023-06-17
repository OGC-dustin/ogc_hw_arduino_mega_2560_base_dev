# OGC.Engineering
## ogc_hw_arduino_mega_2560_base_dev
Developer contact - dustin ( at ) ogc.engineering

---
## Description:
* Hardware description of the Arduino Mega 2560 base development board and the ATMega2560 microcontroller
* ATMega2560 - 8 bit microcontroller running at 16 MHz Atmel IC now owned by Microchip
* up to 54 digital pins, 15 PWM outputs, 16 analog inputs, 4 hardware serial ports
* 4 KB EEPROM
* 8 KB SRAM
* 256 KB Flash
* 7 - 12 Volt inputs
* 5 Volt I/O at 20 mA max per I/O pin

---
## Pin cross reference to Arduino:
```
A0     PF0 ADC0
A1     PF1 ADC1
A2     PF2 ADC2
A3     PF3 ADC3
A4     PF4 ADC4 TCK
A5     PF5 ADC5 TMS
A6     PF6 ADC6 TDO
A7     PF7 ADC7 TDI

A8     PK0 ADC8 PCINT16
A9     PK1 ADC9 PCINT17
A10    PK2 ADC10 PCINT18
A11    PK3 ADC11 PCINT19
A12    PK4 ADC12 PCINT20
A13    PK5 ADC13 PCINT21
A14    PK6 ADC14 PCINT22
A15    PK7 ADC15 PCINT23

D0     PE0 RXD0 PCINT8
D1     PE1 TXD0
D2     PE4 OC3B INT4
D3     PE5 OC3C INT5
D4     PG5 OC0B
D5     PE3 AIN1 OC3A
D6     PH3 OC4A
D7     PH4 OC4B

D8     PH5 OC4C
D9     PH6 OC2B
D10    PB4 OC2A PCINT4
D11    PB5 OC1A PCINT5
D12    PB6 OC1B PCINT6
D13    PB7 OC0A OC1C PCINT7 ( Built in LED )

D14    PJ1 TXD3 PCINT10
D15    PJ0 RXD3 PCINT9
D16    PH1 RXD1 
D17    PH0 RXD2 
D18    PD3 TXD1 INT3
D19    PD2 RXD1 INT2
D20    PD1 SDA INT1
D21    PD0 SCL INT0

D22    PA0 AD0( external memory address and data bit 0 )
D23    PA1 AD1( external memory address and data bit 1 )
D24    PA2 AD2( external memory address and data bit 2 )
D25    PA3 AD3( external memory address and data bit 3 )
D26    PA4 AD4( external memory address and data bit 4 )
D27    PA5 AD5( external memory address and data bit 5 )
D28    PA6 AD6( external memory address and data bit 6 )
D29    PA7 AD7( external memory address and data bit 7 )
D30    PC7 A15( external memory address bit 15 )
D31    PC6 A14( external memory address bit 14 )
D32    PC5 A13( external memory address bit 13 )
D33    PC4 A12( external memory address bit 12 )
D34    PC3 A11( external memory address bit 11 )
D35    PC2 A10( external memory address bit 10 )
D36    PC1 A9( external memory address bit 9 )
D37    PC0 A8( external memory address bit 8 )
D38    PD7 T0( Timer/Counter0 Clock Input )
D39    PG2 ALE( Address Latch Enable to external memory )
D40    PG1 RD!( Read Strobe to external memory )
D41    PG0 WR!( Write Strobe to external memory )
D42    PL7 
D43    PL6 
D44    PL5 OC5C( Timer 5 PWM output C )
D45    PL4 OC5B( Timer 5 PWM output B )
D46    PL3 OC5A( Timer 5 PWM output A )
D47    PL2 T5( Timer/Counter5 Clock Input )
D48    PL1 ICP5( Timer/Counter5 Input Capture Trigger )
D49    PL0 ICP4( Timer/Counter4 Input Capture Trigger )
D50    PB3 MISO PCINT3
D51    PB2 MOSI PCINT2
D52    PB1 SCK PCINT1
D53    PB0 SS! PCINT0
```
