# Pioneer3

This seems to be a family that have both video capture hardware and display hardware.

## SSD210

- Dual Cortex A7
- 64MB DDR2
- 64KB SRAM (based on usb loader IPL size)
- .35mm pitch (?) 68 (+ exposed pad) pin QFN
- xx KB Boot ROM with support for booting from SPI NOR, SPI NAND, USB 

### QFN 68 Pinout

** WARNING WARNING This was worked out by looking at a blurry image **

| #  | name           | #  | name        | #  | name       | #  | name        |
|----|----------------|----|-------------|----|------------|----|-------------|
| 1  | AUD_LINEOUT_L0 | 18 | SR_IO09     | 35 | TTL6       | 52 | VDD         |
| 2  | PM_SPI_CZ      | 19 | SR_IO10     | 36 | TTL7       | 53 | USB2_DP     |
| 3  | PM_SPI_CK      | 20 | SR_IO11     | 37 | TTL8       | 54 | USB2_DM     |
| 4  | PM_SPI_DI      | 21 | DVDD_DDR_RX | 38 | GND_EFUSE? | 55 | AVDD3P3_USB |
| 5  | PM_SPI_DO      | 22 | AVDD_PLL    | 39 | TTL11      | 56 | VDD         |
| 6  | PM_SPI_HLD     | 23 | AVDDIO_DRAM | 40 | VDDP_2_3318| 57 | RESET       |
| 7  | PM_SPI_WPZ     | 24 | VDDIO_DATA  | 41 | TTL12      | 58 | PM_UART_TX  |
| 8  | VDD            | 25 | AVDDIO_DRAM | 42 | TTL13      | 59 | PM_UART_RX  |
| 9  | SR_IO00        | 26 | VDD         | 43 | TTL14      | 60 | SAR_GPIO2   |
| 10 | SR_IO01        | 27 | VDDIO_MCLK  | 44 | TTL15      | 61 | SAR_GPIO1   |
| 11 | SR_IO02        | 28 | AVDDIO_DRAM | 45 | TTL16      | 62 | SAR_GPIO0   |
| 12 | SR_IO03        | 29 | TTL0        | 46 | TTL17      | 63 | AVDD_XTAL   |
| 13 | SR_IO04        | 30 | TTL1        | 47 | TTL18      | 64 | XTAL_IN     |
| 14 | SR_IO05        | 31 | TTL2        | 48 | TTL19      | 65 | XTAL_OUT    |
| 15 | SR_IO06        | 32 | TTL3        | 49 | TTL20      | 66 | AVDD_AUD    |
| 16 | SR_IO07        | 33 | TTL4        | 50 | TTL21      | 67 | AUD_VAG     |
| 17 | VDDP_1_3318    | 34 | TTL5        | 51 | VDD        | 68 | AUD_VRM_DAC |

# strap pins 

pm_spi_do?

# Known devices

[Widora](https://sns.widora.io/topic/767/ssd210-demo%E6%9D%BF-%E4%B8%8B%E4%B8%80%E6%AD%A5%E5%87%86%E5%A4%87%E7%82%B9%E5%B1%8F)

