<h1>🐤 piko </h1>
<p>
  <a href="">
    <img alt="npm version" src="https://badgen.net/github/commits/ahsanu123/keling">
  </a>
  <a href="">
    <img alt="npm" src="https://badgen.net/github/contributors/ahsanu123/keling">
  </a>
  <a href="">
    <img alt="npm" src="https://badgen.net/github/branches/ahsanu123/keling">
  </a>
  <a href="https://github.com/ahsanu123/piko/blob/main/LICENSE">
    <img alt="licence" src="https://badgen.net/github/license/ahsanu123/keling">
  </a>
</p>

<p align="center">    
  <img width="1679" height="738" alt="image" src="https://github.com/user-attachments/assets/b34e94b8-6019-47bf-834d-d898f1074e11" />
</p>

<p align="center">CMSIS DAP Probe</p>

### 🧺 Schematic

![schematic](./documentation/PicoLink.svg)

## 🌳 Log

- 12 September 2025, ⏰ 19:17. success to flash [yapicoprobe-0124-pico-9aff542.uf2](https://github.com/rgrr/yapicoprobe/releases/tag/v1.24) firmware
  - to upload firmware connect usb c to pc while press reset button, there will new usb mass device detected, copy `uf2` file into that rp2040 usb mass device, and chip will be flashed.
- 12 September 2025, ⏰ 19:49, 🐛 BUG 1, remove 100 ohm resistor between SWDIO, SWCLK and pinhead connector, adding 100 ohm resistor make probing not work.
