# Challenger

A 35-key gaming keypad powered by ZMK.

## Features

- 35 MX-compatible keys
- Wireless (nice!nano)
- nice!view display
- Hotswap sockets

## Bill of Materials

### PCB

| Qty | Part | Description |
|-----|------|-------------|
| 1 | Challenger PCB | |
| 35 | MX switches (of your choice) |  |
| 35 | Kailh MX hot-swap sockets | Switch sockets |
| 35 | 1N4148W diodes | SMD switch diodes |
| 1 | [nice!nano v2](https://nicekeyboards.com/nice-nano/) | Wireless microcontroller |
| 2 | Mill-Max [315-43-112-41-003000](https://www.digikey.ca/en/products/detail/digikey-va/315-43-112-41-003000/4455232) | Female header, 12-pin, microcontroller socket |
| 2 | Mill-Max [350-10-112-00-006000](https://www.digikey.ca/en/products/detail/digikey-va/350-10-112-00-006000/4456133) | Pin header, 12-pin, microcontroller socket |
| 1 | Panasonic [EVQ-PUL02K](https://www.digikey.ca/en/products/detail/panasonic-industry/EVQ-PUL02K/286340) | Tactile switch, as the reset button |
| 1 | Alps Alpine [SSSS811101](https://www.digikey.ca/en/products/detail/alps-alpine/SSSS811101/19529062) | Slide switch, as the power switch |
| 1 | [3.7v 110mAh 301230 LiPo battery](https://www.aliexpress.com/item/1005005348368664.html) | Positive terminal must be on the right side of the connector
| 1 | JST [S2B-PH-K-S](https://www.digikey.ca/en/products/detail/jst-sales-america-inc/S2B-PH-K-S/926626) | Battery connector, 2-pin |

The [EVQ-PUJ02K](https://www.digikey.ca/en/products/detail/panasonic-industry/EVQ-PUJ02K/286338), the [EVQ-PUA02K](https://www.digikey.ca/en/products/detail/panasonic-industry/EVQ-PUA02K/286334), or the [EVQ-PUC02K](https://www.digikey.ca/en/products/detail/panasonic-industry/EVQ-PUC02K/286336) could be used instead for the reset button, since they only differ in operating force or boss (aligning plastic tab on the underside).

The battery connector model number can have a different last letter or no at all (e.g. [S2B-PH-K-K](https://www.digikey.ca/en/products/detail/jst-sales-america-inc/S2B-PH-K-K/27506616), S2B-PH-K-H, [S2B-PH-K](https://www.digikey.ca/en/products/detail/jst-sales-america-inc/S2B-PH-K/28540441)), which only represents its color.

### Case

| Qty | Part | Description |
|-----|------|-------------|
| 1 | Switch plate PCB | |
| 1 | Bottom plate PCB | |
| 4 | M2 x 7 mm standoffs | Case standoffs |
| 8 | M2 x 5 mm screws | Case screws |

M2 x 4 mm screws might be able to be used instead of the M2 x 5 mm screws.

### Display

> The display cover has not been designed yet. Some parts listed are for future reference.

| Qty | Part | Description |
|-----|------|-------------|
| 1 | [nice!view](https://nicekeyboards.com/nice-view) | Display |
| 2 | M2 x 10 mm standoffs | Cover standoffs |
| 2 | M2 x 5 mm screws | Cover standoff screws |

M2 x 4 mm screws might be able to be used instead of the M2 x 5 mm screws.

## Firmware

Built with [ZMK](https://zmk.dev).

## License

[MIT](LICENSE)
