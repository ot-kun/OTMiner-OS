# OTMiner-OS

## Introduction
BM1700 BTC ASICs Miner OS, controller using ESP32, hardware refine to achieve 10J/T or even lower, (in my own)theoretical works. I know someone may said phyically impossible, then please use others, thanks. A new hardware involved, including new PCB design and electronics. Main purpose is to design it looks like a space heater and goes fanless. There will be no OC option(Why I need it to be OC able while I can add more chips).

## Firmware
A new firmware will be made for this miner, only works on self design PCB. I would like the product looks like a space heater. 

## Ethernet option
In my proof of concept, I made a adpator board on nerdqaxe++ with my rewritten firmware and I do think ethernet option should be great. Why don't go wireless!? I don't have bluetooth power supply, some wires/cables always attached to the board.

## PCB
- 12 phase 24 MOSFETs@30A, should safely running @15A better thermal management, support up to 24x ASICs
- for much stable unload, the ASIC will run under frequent and undervoltage.
- lowest fan cooling, simulation done.
- Actually not really a single board, there is a special design to make the whole project possible

## TODOS
- 4 ASICs will be the 1st proof of concept to make it works
- The release version should be about 16 ASICs in total on a singe board

## Timeline
- Should be really long since I have limited funding and just 1 man. No one actually knowing how/what I am doing, just wasting time. So once it is able to release it to the public, no one really care about this. Again, it is a fun project for myself.

## Short story
I am a so called crazy code tuner, having evil mindset on tuning the code. Nothing needed to be right, just make it possible. Not sure if I would release the whole firmware opensource(Not willing to be commend on my coding style, you do you), nor selling the whole product.

Supports & Donations
- Welcome to buy me a coffee, better to have a bag of coffee beans. ;)
- Bitcoin : 1AnNcAMkYaagAW8A3V2gjgbbnpEWuqv7JH
