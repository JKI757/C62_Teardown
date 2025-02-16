| Pin Number | Pin Name | Connected To | Pin Number | Comment |
|------------|----------|--------------|------------|---------|
| 1 | GPIO_A_11 | Display SPI | ??? | SPI 0? |
| 2 | GPIO_A_12 | Display SPI | ??? | SPI 0? |
| 3 | GPIO_A_13 | BK4819 | 25 | SCK - SPI 1?|
| 4 | GPIO_A_14 | | | |
| 5 | GPIO_A_15 | Primary PTT | - | |
| 6 | GPIO_A_16 | | | |
| 7 | GPIO_A_17 | | | |
| 8 | GPIO_A_18 | | | |
| 9 | GPIO_A_19 | | | |
| 10 | GPIO_A_20 | | | |
| 11 | GPIO_B_11/USB_DM | | | |
| 12 | GPIO_B_10/USB_DP | | | |
| 13 | VDD_CORE_2 | | | |
| 14 | GPIO_B_09/GPADC_3 | | | |
| 15 | GPIO_B_08/GPADC_2 | SPK? | | |
| 16 | GPIO_B_07/GPADC_1 | 4032A | 16 | IC could be the charging controller / voltage regulator, since it's connected to the batteries + and - terminals |
| 17 | GPIO_B_06/GPADC_0 | | | |
| 18 | TST | | | |
| 19 | RESETN | | | |
| 20 | GPIO_B_05/KEYSENSE | Flashlight! | | |
| 21 | GPIO_B_04 | Green Led | | |
| 22 | GPIO_B_03 | | | |
| 23 | GPIO_B_02/CBT_2 | | | |
| 24 | GPIO_B_01/CBT_1 | Secondary PTT | - | |
| 25 | GPIO_B_00/CBT_0 | | | |
| 26 | XTAL_OUT | JWT 24C12 |  | |
| 27 | XTAL_IN | JWT 24C12 | | |
| 28 | VDD_AON | | | |
| 29 | VCC | | | |
| 30 | VDD_IO | | | |
| 31 | AVSS_AUD | | | |
| 32 | AVDD_AUD | | | |
| 33 | VREF | | | |
| 34 | VMID | | | |
| 35 | MICBIAS0 | | | |
| 36 | LIN_R_P | BK4819 | 13 | MICN | ARM Analog Out
| 37 | LIN_L_P | | | |
| 38 | MIC0_P |MIC | | |
| 39 | MIC0_N | | | |
| 40 | MIC1_P | BK4819 | 8 | EARO | ARM Analog In
| 41 | MIC1_N | | | |
| 42 | VDD_CORE | | | |
| 43 | VDD_IO2 | | | |
| 44 | VBK_PVSS | | | |
| 45 | VBK_SW | | | |
| 46 | VBK_IN | | | |
| 47 | GPIO_A_00/SWDCLK | | | |
| 48 | GPIO_A_01/SWDTMS | LN4898 | 1 | SD |
| 49 | GPIO_A_02 | Display | Enable | |
| 50 | GPIO_A_03 | | | |
| 51 | GPIO_A_04 | | | |
| 52 | GPIO_A_05 | | | |
| 53 | GPIO_A_06 | | | |
| 54 | FLASH_WP_N | PY25Q32HB | 3 | WP# |
| 55 | FLASH_MISO | PY25Q32HB | 2 | SO |
| 56 | FLASH_CS_N | PY25Q32HB | 1 | CS# |
| 57 | VDD_IO_1 | | | |
| 58 | FLASH_HOLD_N | PY25Q32HB | 7 | HOLD#/RESET# |
| 59 | FLASH_CLK | PY25Q32HB | 6 | CLK |
| 60 | FLASH_MOSI | PY25Q32HB | 5 | SI |
| 61 | GPIO_A_07 | BK4819 | 27 | SDATA - SPI1?| SPI_0_CLK / SPI_1_MOSI
| 62 | GPIO_A_08 | BK4819 | 26 | SCN - SPI1? | SPI_0_CS / SPI_1_CLK
| 63 | GPIO_A_09 | Display SPI | ??? | SPI0? | SPI_0_MISO / SPI_1_CS / I2C_0_SDA
| 64 | GPIO_A_10 | Display SPI | ??? | SPI0? | SPI_0_MOSI / SPI_1_MISO / I2C_0_SCL
| 65 | EPAD | | | |


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