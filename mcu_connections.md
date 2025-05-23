
| Pin Number | Pin Name | Connected To | Pin Number | Comment |
|------------|----------|--------------|------------|---------|
| 1 | GPIO_A_11 | Display SPI | 13 | SPI_1_MOSI | 
| 2 | GPIO_A_12 | Display SPI | ??? | SPI_1_CLK | 
| 3 | GPIO_A_13 | BK4819 | 25 | SCK - SPI 1? // SPI_0_MISO / SPI_1_CS| 
| 4 | GPIO_A_14 | | | |
| 5 | GPIO_A_15 | Primary PTT | - | Boot Mode UART RXD |
| 6 | GPIO_A_16 | | | |
| 7 | GPIO_A_17 | | | |
| 8 | GPIO_A_18 | | | Boot Mode UART TXD |
| 9 | GPIO_A_19 | | | |
| 10 | GPIO_A_20 | | | |
| 11 | GPIO_B_11/USB_DM | | | |
| 12 | GPIO_B_10/USB_DP | | | |
| 13 | VDD_CORE_2 | | | |
| 14 | GPIO_B_09/GPADC_3 | | | |
| 15 | GPIO_B_08/GPADC_2 | Battery | | BAT_DET |
| 16 | GPIO_B_07/GPADC_1 | 4032A | 16 | Battery Charging Detect |
| 17 | GPIO_B_06/GPADC_0 | Key Matrix | D9 | |
| 18 | TST | | | |
| 19 | RESETN | | | |
| 20 | GPIO_B_05/KEYSENSE | Flashlight! | | |
| 21 | GPIO_B_04 | Green Led | | |
| 22 | GPIO_B_03 | Keypad Lights | | |
| 23 | GPIO_B_02/CBT_2 | BK1080 | 2 | FM POWER |
| 24 | GPIO_B_01/CBT_1 | Secondary PTT | - | Pulled up w/10K resistor |
| 25 | GPIO_B_00/CBT_0 | ET3157 | 6 | DT_EN (DTMF Enable). Also pulled up 10K |
| 26 | XTAL_OUT | JWT 24C12 |  | |
| 27 | XTAL_IN | JWT 24C12 | | |
| 28 | VDD_AON | | | |
| 29 | VCC | | | |
| 30 | VDD_IO | | | |
| 31 | AVSS_AUD | | | |
| 32 | AVDD_AUD | | | |
| 33 | VREF | | | |
| 34 | VMID | | | |
| 35 | MICBIAS0 | Microphone + | | |
| 36 | LIN_R_P | BK4819 | 13 | MICN | ARM Analog Out
| 37 | LIN_L_P | ET3157 | 3 | MCU Audio Output into Analog Switcher |
| 38 | MIC0_P | Microphone + | | |
| 39 | MIC0_N | GND | | |
| 40 | MIC1_P | BK4819 | 8 | EARO | ARM Analog In
| 41 | MIC1_N | GND | | |
| 42 | VDD_CORE | | | |
| 43 | VDD_IO2 | | | |
| 44 | VBK_PVSS | | | |
| 45 | VBK_SW | | | |
| 46 | VBK_IN | | | |
| 47 | GPIO_A_00/SWDCLK | | | |
| 48 | GPIO_A_01/SWDTMS | LN4898 | 1 | SD |
| 49 | GPIO_A_02 | Display Backlight LED | 20 | PWM |
| 50 | GPIO_A_03 | APC (Auto Power Control) | | |
| 51 | GPIO_A_04 | BK1080 | | I2C CLK |
| 52 | GPIO_A_05 | BK1080 | | I2C CLK |
| 53 | GPIO_A_06 | BK1080 | | I2C DATA |
| 54 | FLASH_WP_N | PY25Q32HB | 3 | WP# |
| 55 | FLASH_MISO | PY25Q32HB | 2 | SO |
| 56 | FLASH_CS_N | PY25Q32HB | 1 | CS# |
| 57 | VDD_IO_1 | | | 3V3_MCU |
| 58 | FLASH_HOLD_N | PY25Q32HB | 7 | HOLD#/RESET# |
| 59 | FLASH_CLK | PY25Q32HB | 6 | CLK |
| 60 | FLASH_MOSI | PY25Q32HB | 5 | SI |
| 61 | GPIO_A_07 | LM4898 | 1 | CE/SP_EN (Speaker_Enable)|
| 62 | GPIO_A_08 | BK4819 | 26 | SCN (Chip Select) |
| 63 | GPIO_A_09 | Display SPI | 18 | Chip Select/RW |
| 64 | GPIO_A_10 | Display SPI | 15 | Reset |
| 65 | EPAD | | | GND |


BK4819

I'll add the requested empty columns to the markdown table.

| Pin # | Name | Direction | Function | Connected To | Pin Number | Comment |
|-------|------|-----------|-----------|--------------|-------------|---------|
| 1 | GPIO5 | I/O | General purpose input/output - has internal pull-down | | | |
| 2 | GPIO6 | I/O | General purpose input/output - has internal pull-down | | | |
| 3 | VCC | Input | Digital Power Supply, 2.6V ~ 3.6V | | | |
| 4 | XO | Output | Crystal oscillator port, output | | | |
| 5 | XI | Input | Crystal oscillator port, input | | | |
| 6 | NC | - | No Connection | | | |
| 7 | NC | - | No Connection | | | |
| 8 | EARO | Output | Earpiece output | | | |
| 9 | NC | - | No Connection | | | |
| 10 | NC | - | No Connection | | | |
| 11 | VCC | Input | Analog Power supply, 2.6V to 3.6V | | | |
| 12 | NC | - | No Connection | | | |
| 13 | MICN | Input | Microphone input, negative | | | |
| 14 | MICP | Input | Microphone output, positive | | | |
| 15 | LNAIN | Input | Input of low noise amplifier | | | |
| 16 | NC | - | No Connection | | | |
| 17 | PAOUT | Output | Output of power amplifier | | | |
| 18 | VRAMP | Output | PA regulator output | | | |
| 19-24 | NC | - | No Connection | | | |
| 25 | SCK | Input | SPI clock | | | |
| 26 | SCN | Input | SPI enable | | | |
| 27 | SDATA | I/O | SPI data | | | |
| 28 | GPIO0 | I/O | General purpose input/output - has internal pull-down | LNA 2 | | |
| 29 | GPIO1 | I/O | General purpose input/output - has internal pull-down | LNA 1 | | |
| 30 | GPIO2 | I/O | General purpose input/output - has internal pull-down | PA 2 | | |
| 31 | GPIO3 | I/O | General purpose input/output - has internal pull-down | PA 1 | | |
| 32 | GPIO4 | I/O | General purpose input/output - has internal pull-down | ALC | | |
