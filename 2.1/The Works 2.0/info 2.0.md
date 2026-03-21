# Information

## Version Check - v2.1.11 (March 2nd, 2026)

## Schematics for Upload Labs v2.1.x

The following information is a companion guide to the text file schematics located in the same folder.

Download the text file associated with the schematic you want. Open text file → Select All / Copy → In-Game Import. If you fail to copy the whole text file contents into your clipboard, your import will fail.

**Note:** If you are choosing to use the Works 1.0 or 2.0, there may be different instructions.

### Applications (9)

- Virus Extractor
- Obfuscator
- Re-downloader
- Flipper
- Splicer
- Disassembler
- Imprinter
- Brute-force Decryptor
- Duplicator

### Optimizations (26)

- Optimized Debugging
- Antivirus Pro
- Compression
- Enhancement
- Refinement
- Pre-analysis
- Torrent Browsing
- Trojan Injection
- Learning
- Distillation
- Decompilation
- Decomposition
- Demux
- Scrapping
- Rip
- Unzipping
- Virus Extraction
- Obfuscation
- Redownload
- Torrent Filtering
- Brute-force
- Splicing
- Flipping
- Disassembling
- Imprinting
- Duplication

## Summary

| Code | Points Needed |
| :--- | :---: |
| Application | 9 |
| Optimization | 26 |

## Auxiliary Achievement Target

`The Works` baseline is `26` Optimization Points.

`Back-End Dev` achievement target is `38` Optimization Points.

- Additional Optimization Points needed above The Works baseline (`26 -> 38`): `12`
- Standalone schematic path: `2.1/Aux/Back-End Dev.txt`
- Intent: high-quality Optimization Code generation in an isolated coding schematic

## First-Run Order (Quick Start)

### The Works 2.0 - 1:1:1 Setup

1. Turn on `Hacking` first (or second with `Coding`) after portal.
2. In `The Works` hardware toggles, start with Toggle A `ON` and Toggle B `OFF`.
3. Turn on `Coding` and build until you reach `9` Application Points and `26` Optimization Points.
4. Purchase required coding/optimization upgrades as soon as they unlock (especially `Optimized Debugging` with your first Optimization Point).
5. Once setup purchases are done, switch into production by toggling both A and B as directed in The Works 1.0.

## Recommended AR / Considerations

Minimum AR Recommendation: ~150 Advanced Research Spent

**CPU:Network:GPU**

I would consider a 1:2:1 AR Offset Ratio. You may go with a +1 Network Offset to fully balance The Works 2.0. Alternatively, you may make adjustments to the resource allocation to AGI. By default AGI:Main Production is 1:1 (for files/second) and can be modified to adjust overall Network and CPU usage.

**Hacking:Research**

Overall these two should be close to but sub-leveled to Hardware.

**Coding**

You need 9 Application Points and 26 Optimization Points for this setup. Once you are in a comfortable position to get these required points from building Applications and Optimizations, you are done here. You will not need to increase purchases in the future once you are happy with your coding speed (AGI considered, there may be a time down the road when you want to take some points out).

| CPU | Network | GPU | Hacking | Research | Coding |
| :---: | :---: | :---: | :---: | :---: | :---: |
| 1 | 2 | 1 | 1 | 1 | 1 |
| 3 | 4 | 3 | 2 | 3 | 3 |
| 5 | 6 | 5 | 4 | 5 | 3 |
| 8 | 9 | 8 | 7 | 8 | 3 |

Note: This chart is **not** a suggested progression path and is for **Reference Only**. It showcases ratio offsets at various Advanced Research investments.

## 2.1 Schematic Index

1. `2.1/1. The Works (1:1:1).txt`
2. `2.1/2. Hardware (1:1:1).txt`
3. `2.1/3. Main Production (1:1:1).txt`
4. `2.1/4. Virus.txt`
5. `2.1/5. AGI.txt`
6. `2.1/6. Research (1:1:1).txt`
7. `2.1/7. Hacking.txt`
8. `2.1/8. Coding 2.0.txt`
9. `2.1/9. Factory (1:1:1).txt`

### The Works 2.0 - 339 Nodes

This schematic holds all others. Specific Works-Wide notes can be found in individual sections below.

#### Hardware 1:1:1 - Setup

This Node Group houses the resource generating nodes for Network(1), CPU(1), and GPU(1). It features overclocking for 1:1:1 Hardware setup and CPU Processing Seller/ GPU Mine Tether for early-game ramp up.

- Toggle Group A: CPU Processing Seller + GPU Mine Tether - Start of Portal Run
- Toggle Group B: Thread Management Export to Outside Groups
- Toggle Group C: Token Miner - Before you enter a Portal, make sure Toggle Groups A and B are off and toggle on Group C for free tokens. Once satisfied, enter the portal.

The Works: Toggle Group A exports money to Main Production's Inventory (and then to Mini-Factory). Start the Run with Toggle A `ON` and Toggle B `OFF`. Once all your applications, optimizations, upgrade menu purchases are completed, you can toggle both A and B to turn on Production.

#### Main Production - 1:1:1 Setup

This Node Group generates, processes, and uploads files for Money and Infected Computers. It consists of two sections:

- Main Line: Download → Compress → `Imprint` → Multiply (Dupe/Decomp) → AI Trainer/Gen
- Imprint Line: Download → Process and Modify → `Export to Imprinter`

Uploader vs Server: You're given two options for uploading. Use the basic Uploader for kickstarting your server run. Toggle only one on at a time. Swap the Uploader/Server when you can generate your first `Storage Unit`.

The Works: This Node Group is fed Network and CPU resources from Hardware. It also distributes leftover CPU to Research. It distributes Component Boost (Drain) to Hardware. It exports Money to the Mini-Factory to both Toggle Groups. Make sure you are using a single Factory Toggle Group at a time.

#### Virus

This Node Group generates, processes, and exports a specified ratio of virus to the Imprinter Line. It generates viruses using texts, while any can realistically be used except Games. Game based virus generation requires real CPU usage (approx `1/16th` of Main Line). Using Decomp apps down to Programs, Video, Sound, Images, or Texts would make it cheaper. Even as large as programs, it will be running off of virtually nothing (`1/3200th`). Text, for example, requires `1/(6.4e11)` (about 1 in 640 billion), etc. Since ratios cannot go that low, you'll end up with surplus Virus and wasted CPU, which considering how low the usage is, the surplus Virus and wasted CPU is fine.

The Works: It is fed the exact Network and CPU resources needed to generate virus using negligible DL and CPU Speeds. Extra Virus can safely be ignored.

#### AGI

This Node Group generates, processes, and distributes AI Power Boosts to the rest of the system. You'll need to unlock the required applications and optimizations.

The Works: This Node Group receives ratioed Network and CPU resources from Hardware. Production of AGI is ratioed 1:1 with `Main Production / Virus / Research`. AGI is self-contained and isolated from other lines.

#### Research

This Node Group generates, processes, and collects all research. It features an auto-collector and an Advanced Research Node. Simply toggle `OFF` the node you do not need at the time. Make sure you only turn on the relevant File Selector Nodes (Decomp Apps). First attempts with this should use Text File (Duplicator → `Ripper → Decompiler` → Flipper). If it's generating more than `1.00e2` files, or more files than your Data Labs Node can handle (once your income and boosts stabilize), consider moving from text to images (Duplicator → `Scrapper → Decomposer` → Flipper) and so on. When using the File Selector, make sure you do not have multiple files toggled on. Toggle one on at a time and reconnect the output of the file selector to the Flipper in the "Post Selector" Node Group located in the bottom right.

Flow: (DL → Quantity Multipliers and Compression → Refined + Analyzed → Duplicator) → **File Selector** → (Flipper → Data Lab)

The Works: This Node Group receives Research Boost from the AGI Node Group. It also receives ratioed Network from Hardware and CPU resources from Main Line, Imprinter, and Virus Sections. This was done for simplicity's sake and simplified a lot of math. There is enough CPU distributed to be meaningful for text, images, and even sounds depending on build choices.

#### Hacking

This Node Group handles all of the hacking needs. Just turn it on as soon as you portal for immediate success. Make sure you have `Auto Breach Leveling` toggled `ON` when you start your portal run. It is recommended to turn this on first or second with Coding. The purchases from Insider Trading are a must for early-game ramp up.

Recommended Vector: Build Infection

Recommended Hack Point Purchases: `Spoil x1` → `Sneak Attack x5` → `Infection Specialist x1` → `Breach.Speed:Infection.Damage x(2:1)`

The Works: This Node Group receives Hack Boost from the AGI Node Group.

#### Coding 2.0 Instructions

This Node Group Builds Application Points (Optimized 3x + Debug), Optimization Points (Optimized 3x + Debug), and Drivers (Optimized 3x + Debug).

This node group is set by default to build all 3 code types with the intent to shut off sections one by one.

Once reaching the desired Application Points: `9`, pause the whole Node Group.

- Set Application's `0 / 4 (Build)` Toggle (4:75) to 0:75
- Unpause Node Group
- Note: I've added Code Optimize to help create applications faster. Toggle the Application Code group off or disconnect the input to avoid wasting Optimization Code when finished making Application Points. 

Once reaching the desired Optimization Points: `26`, pause the whole Node Group.

- Set `17 / 34 (Build)` Toggle (34:16) to 17:16
  - Set Optimization's `0 / 1 (Build)` Toggle (1:1) to 0:1
- Unpause Node Group

The Works: This Node Group receives Code Boost from the AGI Node Group. The default state of this schematic is in "running mode" which would be the mode you would be using for the majority of the run. **Consider the instructions above when starting a run.**

#### 3 Stage Factory - 1:1:1 Setup

This factory has two Toggle Groups.
**Ensure you are using ONE Toggle Group at a time**

- Toggle Group A: Direct Import - 0 Machines (1:1:1). Straight cash for boost. Useful early in the run to avoid micromanagement. Utilize the default 1:1 ratio to acquire early upgrades during a portal run. After you make the relevant purchases, swap the auto-collector's allocation to 0 (1:0).
- Toggle Group B: Mini Factory - 3 Machines (1:1:1). Useful later in the run when income/boosts stabilize. Utilize a 50:50 income split to generate the same amount of Modules as the Direct Importer (but now with spendable money!)
- Toggle Group C: Main Factory - 34 Machines (4:4:4). For swapping to when the mini-factory's efficiency drops to approximately 17.65% on average while using a 50:50 income ratio with the mini-factory. This will send all income to the wallet.

The Works: In The Works, the hardware section imports Clock Sellers cash to the Mini-Factory for early game hardware boost to help reduce portal early-game ramp up time.

Mini-Factory Machines (3 Machines):

- Tier 1 (3 Machines)
  - 1x Router Assembler
  - 1x GPU Assembler
  - 1x CPU Assembler

Main Factory Machines (34 Machines):

- Tier 1 (12 Machines)
  - 4x Router Assembler
  - 4x GPU Assembler
  - 4x CPU Assembler
- Tier 2 (7 Machines)
  - 3x Wafer Cutter
  - 4x PCB Solder
- Tier 3 (7 Machines)
  - 3x Wafer Synthesizer
  - 2x Polymerizer
  - 2x Wire Mill
- Tier 4 (4 Machines)
  - 2x Silicon Purifier
  - 1x Oil Refiner
  - 1x Metal Press
- Tier 5 (4 Machines)
  - 1x Excavator
  - 2x Miner
  - 1x Extractor
  - 
