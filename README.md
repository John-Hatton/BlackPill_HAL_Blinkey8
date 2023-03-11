# BlackPill HAL Blinkey 8
## (STM32 Hardware Abstraction Layer

---


## Introduction

I've been working a lot lately with the STM32F411CEU6, and I recently bought a DHT22 Temperature
and Humidity sensor. I found that just using the Arduino Library wasn't good enough. To get the 
Black Pill to talk to the DHT22, you have to specify certain timing parameters, which were often 
done in the community with STM32CubeIDE. In my experience so far, it's been splendid, working with
PlatformIO however. So I set off to re-write one of my early demos I wrote for the Black Pill, which
is called Blinkey8. It turns on the eight LEDs, each with 250ms delay in between, and then after the 
last LED is turned on, they begin to all turn off, in the same sequence.

---

## STM32CubeIDE Configuration


---

## CLion (or VS Code) w/ PlatformIO


---
