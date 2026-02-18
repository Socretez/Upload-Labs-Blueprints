# Information

## Version Check - v2.0.21

You'll need a fairly chunky amount of AR and have portaled at least once. You will need to be able to get at least 6 application points and 44 optimization points in order to take advantage of all the cpu/gpu threading baked in. Any modifications will require readjustment of manual clocking. Current threading is based on a 1:1:1 CPU:Network:GPU AR ratio.

- Applications not needed: Compile apps, torrent filter
- Optimizations not needed: Compile apps, torrent filter, crypto

## How to use

Download the text file associated with the schematic you want. Open text file → Select All / Copy → In-Game Import

## Recommended AR / Considerations

**CPU/GPU:Network**
I would consider a 1:1:1 AR set up. Potentially a 1:1 GPU:CPU with a +1 network offset 'Just enough'
**Hacking / Research**
Priority spends
Theorized: +10 each from hardware AR, maybe +12-15 depending on your playstyle/preferences
**Coding**
You want just enough to gg 44 optimization points. 10 points in the final AR node is about good enough for me. 15 would be overkill. Anything slower than a 10 would increase the time to 44 optimization points, until the bug is fixed I don't recommend too much delay here.

## Index

- The Answer to Everything (All Nodes).txt
- Hardware.txt
- All-in-One.txt
- Research.txt
- Hacking.txt
- Coding.txt
- Factory.txt
- Mini Factory.txt

### The Answer to Everything (358 Nodes)

This schematic holds all others.

### Hardware

The ratios baked in here are suited for 1:1:1 CPU:Network:GPU AR ratios for the All-in-One, Outputs are on the far left. This includes slider switches to control the flow of Download:Upload and GPU:CPU. The heatsinking is completed with the reduced heat AR points taken.

For ease, all you have to do is plug the output of the far right managers to the inputs of the All-in-One. 

### All-in-One Production

Simply plug in the CPU:Network:GPU manager nodes from hardware into the inputs of this block and let it roll. Makes all 6 file types in ratios that generates AGI, server from Games to Images, and produces excess games which can be decompiled further into research files as needed. I attempted to label important parts to make it easier to understand where to make modfiications.

Example change: Going from image research to sound research simply replace the Decomposer to a Demuxer and that's all you need to do, just connect the CPU to the same slots and the files. To go from Sounds to Video just delete the Demuxer, connect the file paths, and reduce the cpu clocks (or leave em alone for extra lazy)

### Research

All you need to do is turn on or off either the AR or the Auto Collector depending on your needs. Still working on the research tree? Turn off the Advanced Research. Finished the tree/upgrades, etc? Turn off the auto collector.

The auto collector is included for NG+ where you need some research to increase generated file value.

### Hacking

Generic hacking setup, nothing special here.

### Factory

This is factory balanced out to T4. As usual, separate each tier by 7 levels. This is an extra 4 router assemblers worth of PCBs being made if you want to take advantage of it.

Machines (98):

- Tier 1
  - 20 Router Assembler
  - 8 GPU Assembler
  - 8 CPU Assembler
- Tier 2
  - 16 PCB Solder
  - 6 Wafer Cutter
- Tier 3
  - 8 Wire Mill
  - 8 Polymerizer
  - 6 Wafer Synthesizer
- Tier 4
  - 4 Oil Refiner
  - 4 Metal Press
  - 4 Silicon Purifier
- Tier 5
  - 3 Miner
  - 2 Oil Pump
  - 1 Excavator

### Mini Factory

This is my starter factory that I use to feed the main factory for the majority of the run. This will honestly be good enough for most people for most of your run if not all of your run. Just throw in 1-20% of your income into it. What I do is connect the output of this to the last input slot of the Main Factory's container's and connect the main factory to my hardware. Just feed this your income and you can send the top split of money to your auto collector.

Machines (9):

- Tier 1
  - 5 Router Assembler
  - 2 GPU Assembler
  - 2 CPU Assembler
