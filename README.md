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
| 1 | nice!nano v2 | Wireless microcontroller |
| 2 | Mill-Max 315-43-112-41-003000 | Female header, 12-pin, microcontroller socket |
| 2 | Mill-Max 350-10-112-00-006000 | Pin header, 12-pin, microcontroller socket |
| 1 | Panasonic EVQPUL EVQPUC | Tactile switch, as the reset button |
| 1 | Alps Alpine SSSS811101 | Slide switch, as the power switch |
| 1 | [3.7v 110mAh 301230 LiPo battery](https://www.aliexpress.com/item/1005005348368664.html) | Positive terminal must be on the right side of the connector
| 1 | JST S2B-PH-K-S | Battery connector, 2-pin |

The Panasonic EVQPUJ EVQPUA button can be used instead for the reset button, as it only lacks the boss (aligning plastic pins on the underside).

The battery connector can have a different last letter, which only represents its color.

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
| 1 | nice!view | Display |
| 2 | M2 x 10 mm standoffs | Cover standoffs |
| 2 | M2 x 5 mm screws | Cover standoff screws |

M2 x 4 mm screws might be able to be used instead of the M2 x 5 mm screws.

## Firmware

Built with [ZMK](https://zmk.dev).

## License

[MIT](LICENSE)
