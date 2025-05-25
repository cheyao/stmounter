---
title: "Stmounter"
author: "Chengyin Yao"
description: "STM32 Development Board"
created_at: "2025-05-23"
---

# Stmounter

Damn I can't think of a better name >.<

-------------------

## 23/05

But I've started the schematic! Progress looking quite good right now. The stm32 looks like an easy chip.

![](https://hc-cdn.hel1.your-objectstorage.com/s/v3/42b2bad4cae87a297e4a6db87b6074c069d7d9ba_image.png)

- Time spent: 1h

-------------------

## 24/05

I've researched a toooon about the usb c shield connection: resistor cap pair, ferrite bear, no conenction, connect directly etc. Figured that the best way to connect it is directly to a gnd pour.

Also started designing the schematic!

![](https://hc-cdn.hel1.your-objectstorage.com/s/v3/8725ff5e66c77cbc8abd74d020878d1579b7f67d_image.png)

- 2h

-------------------

Decided on a raspi pico form factor because why not ;p It'll be a drop-in replacement.

![](https://hc-cdn.hel1.your-objectstorage.com/s/v3/a8aa822c855e84da45cb67c2745a2116cfdb3cf4_image.png)

- 1.5h

-------------------

Finally found a stm32 [getting started manual](https://www.st.com/resource/en/application_note/cd00164185-getting-started-with-stm32f10xxx-hardware-development-stmicroelectronics.pdf)! This will make my like easier ;p

Only 29 pages tho, how little.

- 2h

-------------------

Okay I've opened like 4 pdfs now, in datasheet hell... Welp this is easier then my fpga though. Calculating oscillator capacitance rn.

I've calculated the capacitance and continued routing:

![](https://hc-cdn.hel1.your-objectstorage.com/s/v3/dec76b14eacd9b7ff63ca8b475f83e7c250f3a60_image.png)

- 1.5h

-------------------

## 25/05

Okay I've finished routing the v1 of the board!

![](https://hc-cdn.hel1.your-objectstorage.com/s/v3/119a3979a1ce198a5a1e3578c5b36359293e24e3_image.png)

Buuuut I think I messed up the chip selection... I need a 2.5$ chip for the USB programming option :(

Time for v2

- 2.5h

-------------------

Started drawing the schematic for the STM32F373CCT, also reorganized the top part of the PCB.

![](https://hc-cdn.hel1.your-objectstorage.com/s/v3/314d028570596e333a9e7ee3eeb3c6cca9fc5f1f_image.png)

- 1h

-------------------

Okay I spent the whole afternoon on this, finished rev 2!!!

![](https://hc-cdn.hel1.your-objectstorage.com/s/v3/97cce543af2ca7ceb31d24cd7f10e65cd9ff5115_image.png)

- 2.5h
