# Custom Desktop PC Build – Group 2

**Course**: CSARCH2  
**Section**: S19
**Group Members**:  
- Aragon, Enrique Miguel M.
- Limtin, Richard  
- Reyes, Jericho Migell
- Tan, Ross David  
- Yu, Chrisander

---

## 1. Introduction
For this build, our group was tasked to build an Intel-based desktop that allows gaming on a budget while still using modern parts. Specifically, we must follow a budget of Php 40,000 (with a leeway of ±5%), as well as selecting parts from the current era (2024 onwards). Hence, we primarily focused on maximizing GPU performance with our budget as the GPU is the component most heavily utilized by games, especially more modern ones, which is why we selected the RTX 5050, which should be sufficient for 60fps gaming on most modern games provided you're willing to compromise a bit with quality. 

That said, since we spent a good amount of budget on the GPU, we had to settle for cheaper parts for the rest. This is most evident with the CPU, where we settled with a 14th Generation Intel Core i3. Though it may be the lowest tier in Intel's Core lineup of processors offering only 4 cores 8 threads, it is no slouch and can still deliver good performance for most general use cases. This necessitated a compatible LGA1700 socket motherboard, and due to the new parts restriction, the one we did find also required DDR5 memory, severly constraining our budget. Keeping all of the above in mind, we only had the budget for a 500gb SSD, however this is upgradable, with an extra M.2 slot allowing for another SSD. It should be noted that while we did cheap out on some aspects due to budget constraints, all of the parts selected are still good enough to perform the tasks expected of them while complying with the given specifications, as seen with the power supply being certified 80+ Silver.

---

## 2. Draft Build (PCPartPicker)
This build uses **PCPartPicker System Builder** for compatibility check. 
PCPartPicker Permalink: (https://pcpartpicker.com/list/YTXX8Q)

### Summary Table 
| Component       | Model | Price (USD/Php) | Notes |
|-----------------|-------|-----------------|-------|
| CPU             | ...   | ...             | ...   |
| CPU Cooler      | ...   | ...             | ...   |
| Motherboard     | ...   | ...             | ...   |
| RAM             | ...   | ...             | ...   |
| Storage 1       | ...   | ...             | ...   |
| Storage 2       | ...   | ...             | ...   |
| Graphics Card   | ...   | ...             | ...   |
| Power Supply    | ...   | ...             | ...   |
| Case            | ...   | ...             | ...   |
| Case Fans       | ...   | ...             | ...   |
| **Total**       |       | **XXX USD/Php**     |       |

---

## 3. Local Manila Build
This build uses **locally available parts** from Manila vendors.
Google spreadsheet link: _________  

### Local Build Table
| Component       | Model                               | Vendor & Link      | Price (Php)    | Compatibility Notes                  |
|-----------------|-------                              |--------------------|----------------|--------------------------------------|
| CPU             | Intel i3-14100F                     | [Dynaquest](https://dynaquestpc.com/products/intel-core-i3-14100f-12mb-up-to-4-50ghzlga-1700-processor)  | 5,340.00            |                                      |
| CPU Cooler      | Stock                               |                    | -            |                                      |
| Motherboard     | Gigabyte B760M DS3H WiFi6E Gen5 DDR5| [DataBlitz](https://ecommerce.datablitz.com.ph/products/gigabyte-b760m-ds3h-wifi6e-gen5-ddr5-intel-ultra-durable-motherboard)  | 7,495.00            |                                      |
| RAM             | Lexar Thor RGB 32GB Kit             | [EasyPC](https://easypc.com.ph/products/lexar-thor-rgb-ddr5-32gb-6000mhz-gaming-memory?srsltid=AfmBOoqUt495qeqWePYjocHmOXrUTsiVlfxfILEiNcPCi0vaH82RKssy)     | 4,995.00            |                                      |
| Storage 1 (SSD) | Adata Legend 860 500GB              | [DataBlitz](https://ecommerce.datablitz.com.ph/products/adata-legend-860-500gb-pcie-gen4-x4-m-2-2280-internal-ssd-sleg-860-500gcs)  | 2,295.00            |                                      |
| Storage 2 (HDD) | ...                                 |                    | -            |                                      |
| GPU             | Palit RTX 5050 DUAL 8GB DDR6        | [Dynaquest](https://dynaquestpc.com/collections/graphics-card/products/palit-rtx-5050-dual-8gb-gddr6-graphics-card-ne65050019p1-gb2070d)  | 16,485.00            |                                      |
| PSU             | Gigabyte P550SS Silver 550W ATX 3.0 80+ Power Supply GP-P550SS      | [Dynaquest]([https://dynaquestpc.com/collections/components-power-supply-500-650-watts/products/msi-mag-a550bn-bronze-550w-80-power-supply](https://dynaquestpc.com/collections/components-power-supply-500-650-watts/products/gigabyte-p550ss-silver-550w-atx-3-0-80-power-supply-gp-p550ss))  | 2,595.00            |                                      |
| Case            | Darkflash DB330M mATX PC Case       | [DataBlitz](https://ecommerce.datablitz.com.ph/products/darkflash-db330m-m-atx-pc-case)  | 1,590.00            |                                      |
| Case Fans       | (3 pcs) Arctic P12 Pro PWM Fan      | [DataBlitz](https://ecommerce.datablitz.com.ph/collections/chasis-fan/products/arctic-p12-pro-single-pack-120mm-pwm-fan-with-cable-splitter-black-acfan00305a)  | 885.00            | 120mm                                |
| **Total**       |                                     |                    | **41,680 Php** | Within budget                        |

---

## 4. Compatibility Justification
**CPU + Motherboard**: The Gigabyte B760M DS3H WiFi6E Gen5 DDR5 is compatible with the Intel i3-14100F. The Gigabte B760M DS3H WiFi6E Gen5 DDR5 has a LGA1700 socket which supports 12th, 13th, and 14th Intel CPU generations.

**RAM + Motherboard**: The Gigabyte B760M DS3H WiFi6E Gen5 requires a DDR5 RAM. The Lexar Thor RGB 32GB Kit are composed of 2 DDR5 16 GB RAM sticks with 6000MHz, this will allow for smooth gaming for modern games.

**CPU + GPU**: The i3-14100F and RTX 5050 allows for smooth graphics and fps for 1080p gaming:

Cyberpunk 1080p ULTRA AVG 69 FPS
God Of War Ragnarok 1080p ULTRA AVG 84 FPS
CSGO 2.0 1080p ULTRA AVG 348 FPS

source: https://www.youtube.com/watch?v=eJjRRr90BHk&t

**PSU**: According the PcParts Picker, the estimated wattage consumption of our compotents is 325 Watts, therefore the Gigabyte P550SS Silver 550W ATX 3.0 80+ Power Supply GP-P550SS with a 550 wattage will allow for flexibility in terms of electricity usage of components. 

**Case**: The matx case will be able to fit the Gigabyte B760M DS3H WiFi6E Gen5 motherboard as it is also an matx motherboard. Whilst the Gigabyte P550SS Silver 550W ATX 3.0 80+ Power Supply is an atx size, the case will still be able to accomodate its size. 

---

## 5. Budget Analysis
- **Budget Limit**: ₱XX,000  
- **Final Total**: ₱XX,000  
- ✅ Within budget / ❌ Over budget  
- Notes on trade-offs (e.g., cheaper RAM, higher PSU wattage, no aftermarket cooler, etc.).

---

## 6. Conclusion & Learnings
Reflections on:  
- Price differences (international vs. Manila vendors)  
- Challenges in finding stock or cheaper equivalents  
- What the group learned about PC components and system design  

---
## 7. Video pitch
- Your video link here  

## 8. References

- Vendor links (PCX, VillMan, etc.)  
- PCPartPicker build link  
- Any technical documentation consulted  

## PC Part References

- [DynaQuest PC](https://dynaquestpc.com/)  
- [EasyPC](https://easypc.com.ph/)  
- [DataBlitz](https://ecommerce.datablitz.com.ph/)  
- [Amazon](https://www.amazon.com/) *(used to check part release dates)*














