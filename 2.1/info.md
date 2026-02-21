# Information

## Version Check - v2.1.10 (February 9th, 2026)

## Schematics for Upload Labs v2.1.x

The following information is a companion guide to the text file schematics located in the same folder.

Download the text file associated with the schematic you want. Open text file → Select All / Copy → In-Game Import. If you fail to copy the whole text file contents into your clipboard, your import will fail.

### Applications (8)

- Virus Extractor
- Obfuscator
- Re-downloader
- Flipper
- Splicer
- Imprinter
- Brute-force Decryptor
- Duplicator

### Optimizations (41)

| Optimization | Points Needed |
| :--- | :---: |
| Optimized Debugging | 3 |
| Antivirus Pro | 1 |
| Compression | 2 |
| Enhancement | 2 |
| Refinement | 1 |
| Pre-analysis | 2 |
| Torrent Browsing | 3 |
| Trojan Injection | 1 |
| Learning | 4 |
| Distillation | 1 |
| Decompilation | 1 |
| Decomposition | 1 |
| Demux | 1 |
| Scrapping | 1 |
| Rip | 1 |
| Unzipping | 1 |
| Virus Extraction | 1 |
| Obfuscation | 1 |
| Redownload | 1 |
| Torrent Filtering | 2 |
| Brute-force | 2 |
| Splicing | 1 |
| Flipping | 3 |
| Imprinting | 2 |
| Duplication | 2 |

## Summary

| Code | Points Needed |
| :--- | :---: |
| Application | 8 |
| Optimization | 41 |

## Auxiliary Achievement Target

`The Works` baseline is `41` Optimization Points.

`Back-End Dev` achievement target is `59` Optimization Points.

- Additional Optimization Points needed above The Works baseline (`41 -> 59`): `18`
- Standalone schematic path: `2.1/Aux/Back-End Dev.txt`
- Intent: high-quality Optimization Code generation in an isolated coding schematic

## First-Run Order (Quick Start)

1. Turn on `Hacking` first (or second with `Coding`) after portal.
2. In `The Works` hardware toggles, start with Toggle A `ON` and Toggle B `OFF`.
3. Turn on `Coding` and build until you reach `8` Application Points and `41` Optimization Points.
4. Purchase required coding/optimization upgrades as soon as they unlock (especially `Optimized Debugging` at 3 Optimization Points).
5. Once setup purchases are done, switch into production by toggling both A and B as directed in The Works.

## Recommended AR / Considerations

Minimum AR Recommendation: ~150 Advanced Research Spent

**CPU:Network:GPU**
I would consider a 1:1:1 AR Offset Ratio. You may go with a +1 GPU Offset to increase the download usage from its current low usage (approx `1:3.1` DL:UL) if you prefer that over going Upload Speed Heavy.
**Hacking:Research**
Overall these two should be higher than others; it's worth the extra cost in Advanced Research to increase Hack and Research Nodes by a few offsets from Hardware.
**Coding**
You need 8 Application Points and 41 Optimization Points for this setup. Once you are in a comfortable position to get these required points from building Applications and Optimizations, you are done here. You will not need to increase purchases in the future once you are happy with your coding speed (AGI considered, there may be a time down the road when you want to take some points out).

| CPU | Network | GPU | Hacking | Research | Coding |
| :---: | :---: | :---: | :---: | :---: | :---: |
| 1 | 1 | 1 | 3 | 3 | 1 |
| 3 | 3 | 3 | 5 | 6 | 5 |
| 5 | 5 | 5 | 8 | 8 | 8 |
| 8 | 8 | 9 | 10 | 11 | 8 |

Note: This chart is **not** a suggested progression path and is for **Reference Only**. It showcases ratio offsets at various Advanced Research investments.

## 2.1 Schematic Index

1. `2.1/1. The Works.txt`
2. `2.1/2. Hardware.txt`
3. `2.1/3. Main Production.txt`
4. `2.1/4. Virus.txt`
5. `2.1/5. AGI.txt`
6. `2.1/6. Research.txt`
7. `2.1/7. Hacking.txt`
8. `2.1/8. Coding.txt`
9. `2.1/9. Mini-Factory.txt`

## 2.1 Auxiliary Schematic Index (Standalone)

1. `2.1/Aux/Back-End Dev.txt`

### The Works (281 Nodes)

This schematic holds all others. Specific Works-Wide notes can be found in individual sections below.

#### Hardware

This Node Group houses the resource generating nodes for Network(5), CPU(2), and GPU(2). It features overclocking for 5:2:2 Hardware setup and CPU Processing Seller/ GPU Mine Tether for early-game ramp up.

- Toggle Group A: Processing Seller (Start of Run) + GPU Mine Tether (Start of Run) + Mine Token (End of Run)
- Toggle Group B: Thread Management Export to Outside Groups

The Works: Toggle Group A exports money to Main Production's Inventory (and then to Mini-Factory). Start the Run with Toggle A `ON` and Toggle B `OFF`. Once all your applications, optimizations, upgrade menu purchases are completed, you can toggle both A and B to turn on Production.

#### Main Production

This Node Group generates, processes, and uploads files for Money and Infected Computers. It consists of two sections:

- Main Line: Download → Compress → `Imprint` → Multiply (Dupe/Decomp) → AI Trainer/Gen
- Imprint Line: Download → Process and Modify → `Export to Imprinter`

The Works: This Node Group is fed Network and CPU resources from Hardware. It also distributes leftover CPU to Research. It distributes Component Boost (Drain) to Hardware. It exports Money to the Mini-Factory to both Toggle Groups. Make sure you are using a single Factory Toggle Group at a time.

#### Virus

This Node Group generates, processes, and exports a specified ratio of virus to the Imprinter Line. It generates virus using programs, while any can realistically be used, game virus requires real CPU usage (approx `1/16th` of Main Line). Using Decomp apps down to Video, Sound, Images, or Texts would make it cheaper, but it's already running off of virtually nothing (`1/3200th`). Text, for example requires `1/(6.4e11)` (about 1 in 640 billion), etc. Since ratios cannot go that low, you'll end up with surplus Virus and wasted CPU, which considering how low the usage is, the surplus Virus and wasted CPU is fine.

The Works: It is fed the exact Network and CPU resources needed to generate enough virus with a small, negligible surplus of Virus.

#### AGI

This Node Group generates, processes, and distributes AI Power Boosts to the rest of the system. You'll need to unlock the required applications and optimizations.

The Works: This Node Group receives ratioed Network and CPU resources from Hardware. Production of AGI is ratioed 1:1 with `Main Production / Virus / Research`. AGI is self-contained and isolated from other lines.

#### Research

This Node Group generates, processes, and collects all research. It features an auto-collector and an Advanced Research Node. Simply toggle `OFF` the node you do not need at the time. Make sure you only turn on the relevant File Selector Nodes (Decomp Apps). First attempts with this should use Text File (Duplicator → `Ripper → Decompiler` → Flipper). If it's generating more than `1.00e2` files, or more files than your Data Labs Node can handle (once your income and boosts stabilize), consider moving from text to images (Duplicator → `Scrapper → Decomposer` → Flipper) and so on.

The Works: This Node Group receives Research Boost from the AGI Node Group. It also receives ratioed Network from Hardware and CPU resources from Main Line, Imprinter, and Virus Sections. This was done for simplicity's sake and simplified a lot of math. There is enough CPU distributed to be meaningful for text, images, and even sounds depending on build choices.

#### Hacking

This Node Group handles all of the hacking needs. Just turn it on as soon as you portal for immediate success. Make sure you have `Auto Breach Leveling` toggled `ON` when you start your portal run. It is recommended to turn this on first or second with Coding. The purchases from Insider Trading are a must for early-game ramp up.

Recommended Vector: Build Infection

Recommended Hack Point Purchases: `Spoil x1` → `Sneak Attack x5` → `Infection Specialist x1` → `Breach.Speed:Infection.Damage x(2:1)`

The Works: This Node Group receives Hack Boost from the AGI Node Group.

### Coding

This Node Group Builds Application Points (unmodified), Optimization Points (Optimized 3x + Debug), and Drivers (Optimized 3x + Debug).

Before turning this Node Group on for the first time:

- Set Application's `0 / 1 (Build)` Toggle (0:1) to 1:1
- Set `17 / 34 (Build)` Toggle (17:16) to 34:16
  - Set Optimization's `0 / 1 (Build)` Toggle (0:1) to 1:1

Once reaching the desired Application Points: `8`, pause the whole Node Group.

- Set Application's `0 / 1 (Build)` Toggle (1:1) to 0:1
- Unpause Node Group

Once reaching the desired Optimization Points: `41`, pause the whole Node Group.

- Set `17 / 34 (Build)` Toggle (34:16) to 17:16
  - Set Optimization's `0 / 1 (Build)` Toggle (1:1) to 0:1
- Unpause Node Group

The Works: This Node Group receives Code Boost from the AGI Node Group. The default state of this schematic is in "running mode" which would be the mode you would be using for the majority of the run. **Consider the instructions above when starting a run.**

#### Mini Factory

This factory has two Toggle Groups.
**Ensure you are using ONE Toggle Group at a time**

- Toggle Group A: Main Factory - 9 Machines (5:2:2). Useful later in the run when income/boosts stabilize.
- Toggle Group B: Import - 0 Machines (5:2:2). Straight cash for boost. Useful early in run to avoid micromanagement.

The Works: In The Works, the hardware section imports Clock Sellers cash to the Mini-Factory for early game hardware boost to help reduce portal early-game ramp up time.

Machines (9):

- Tier 1
  - 5 Router Assembler
  - 2 GPU Assembler
  - 2 CPU Assembler
