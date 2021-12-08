# LGA1200 ITX Buyer's Guide

Here is a detailed roundup of all the relevant ITX LGA1200 boards.

`"Why should I go ITX?"`

ITX is an underrated platform that many people do not know in depth about. Small form factor cases can be very space efficient and transportable, even with no compromises. 

`"What is 'ITX Tax?"`

'ITX Tax' is a term used regarding the extra cost of going the ITX route. ITX systems do usually cost more, but noawadays it's not bad at all. It can definitely be worth it if you want to go this route.

`"Where should I buy one of these boards?"`

If you are able to find them for a good price new go ahead, but it's much more common for the prices to be better in the used market.



# Low End - Midrange Boards
These boards are for low-mid range CPUs such as the 10105F, 10400F, 10700F ect. They do not have CPU overclocking capabilities, since such CPUs won't either. This means that VRMs won't matter as much. However, they still do have XMP, so you are able to overclock your memory.

## ASRock B560M-ITX/ac
- 6 Phase 50A Dr.MOS
- 4x SATA, 1x M.2 (PCIe Gen4)
- 5x USB 3.2 Gen1 (2x Rear, 2x Front, 1x Front Type-C)
- 4x USB 2.0 (2x Rear, 2x Front) 
- Intel Gigabit LAN
- Intel 802.11ac WiFi + Bluetooth 4.2
- Realtek ALC897 Audio

##### Notes: 
The cheapest board out of the good options. It's able to handle lower end CPUs, but make sure to note that it has a 1.45v VDIMM limit and 1 less M.2 slot than the other boards.

![b560mitxac](https://user-images.githubusercontent.com/91910634/144919328-364bf8f5-5a55-4f9a-afdd-8a34d1484f08.png)


## ASRock H570M-ITX/ac
- 8 Phase 50A Dr.MOS
- 4x SATA, 2x M.2 (1x PCIe Gen4, 1x PCIe Gen3)
- 1x USB 3.2 Gen2x2 (Rear Type-C)
- 2x USB 3.2 Gen2 (Rear) 
- 3x USB 3.2 Gen1 (2x Front, 1x Front Type-C)
- 5x USB 2.0 (3x Rear, 2x Front) 
- Dragon Gigabit LAN, Intel Gigabit LAN
- Intel 802.11ac WiFi + Bluetooth 4.2
- Realtek ALC897 Audio

##### Notes:
Great value for a better board compared to it's B560 counterpart. VRMs will be good enough to handle 10700Fs or similar, also has good connectivity for the productivity route.

![h570mitxac](https://user-images.githubusercontent.com/91910634/144919466-b9148c1e-5283-4bbf-a0f5-69dfbd73693e.png)


## Asus STRIX B560-I GAMING WIFI
- 6+2 Phase Dr.MOS
- 4x SATA, 2x M.2 (1x PCIe Gen4, 1x PCIe Gen3)
- 1x USB 3.2 Gen2x2 (Rear Type-C)
- 2x USB 3.2 Gen2 (1x Rear, 1x Front Type-C)
- 2x USB 3.2 Gen1 (Front)
- 8x USB 2.0 (5x Rear, 1x Rear Audio Type-C, 2x Front)
- Realtek 2.5 Gigabit LAN
- Intel AX200 WiFi
- ROG SupremeFX S1220A Audio

##### Notes:
VRMs good enough to handle more powerful CPUs. More aesthetically pleasing with RGB features and has better built-in audio. Not the best when it comes to value though.

![b560istrix](https://user-images.githubusercontent.com/91910634/144919854-266c54f9-1654-42f5-982a-a701b164d1d7.png)


## MSI B560I GAMING EDGE WIFI
- 6+2+1 Phase Dr.MOS
- 4x SATA, 2x M.2 (PCIe Gen4, PCIe Gen3)
- 2x USB 3.2 Gen2 (1x Rear, 1x Rear Type-C)
- 2x USB 3.2 Gen1 (1x Front, 1x Front Type-C)
- 6x USB 2.0 (4 Rear, 2 Front)
- Realtek 2.5 Gigabit LAN
- Intel AX210 WiFi
- Realtek ALC897 Audio

##### Notes:
Sleek looks, and one of the better boards for memory overclocking, but will depend mostly on how good your IMC is. 

![b560igamingedge](https://user-images.githubusercontent.com/91910634/144920178-4ee55604-92f3-4a36-a9f5-ecf9aa074c72.png)


## Verdict

For a budget entry level system using CPUs such as the 10105F or 10400F, the ASRock B560M-ITX/AC will be the better choice. It is significantly cheaper than the other boards, while still having XMP and being able to handle such CPUs. 

For systems using a CPU like a 10700F or similar, the H570M-ITX/ac will probably be the best choice, since it has more USB ports, M.2 slots and dual LAN which means it'll be better for productivity. The VRMs will also be more suited to handle CPUs which will perform better in more productivity focused workloads, aswell as gaming



# High End Boards
These boards are for higher end, unlocked CPUs such as the 10600K, 10700K, 10900K ect. The VRMs will matter more, therefore have been much more detailed in analysis. These boards are great for CPU and memory overclocking, with some features to assist with those tasks.


## ASRock Z490 Phantom Gaming ITX
- 6+3 Phase VRM
  - Controller: ISL69269
  - VCore: 6x ISL99390 90A
  - SA/IO: 3x ISL9927 60A
- 4x SATA, 2x M.2 (PCIe Gen3)
- 1x USB-C Thunderbolt 3
- 3x USB 3.2 Gen2 (Rear)
- 4x USB 3.2 Gen1 (2x Rear, 2x Front) 
- 2x USB 2.0 (Front) 
- Phantom Gaming 2.5 Gigabit LAN
- Intel AX201 WiFi
- Realtek ALC1220 Audio
- Clear CMOS Button

Insane VRM cooling and the only ITX Z490 board to have a SODIMM board for drives and USB headers. Note that some AIOs will not fit this board, such as the NZXT Kraken series. 

![z490pgitx](https://user-images.githubusercontent.com/91910634/144762418-31a4361c-d638-41b8-b530-9b884f4063f7.png)


## Asus ROG STRIX Z490-I GAMING
- Twin 4+2 Phase VRM
  - Controller: ASP1405
  - VCore: 8x TDA21462 60A
  - SA: 2x TDA21462 60A
- 4x SATA, 2x M.2 (PCIe 3)
- 5x USB 3.2 Gen2 (3x Rear, 1x Rear Type-C, 1x Front)
- 3x USB 3.2 Gen1 (2x Rear, 1x Front)
- 3x USB 2.0 (2x Rear, 1x Front)
- Intel I225-V 2.5 Gigabit LAN
- Intel AX201 WiFi
- ROG SupremeFX S1220A Audio
- BIOS Flashback Button

##### Notes:

Great VRMs with active cooling. Interesting, but working solution for the M.2 thermals, since neither of the drives will be starved for airflow. 

![z490istrix](https://user-images.githubusercontent.com/91910634/144762559-ec80bafa-2a49-41dd-a17d-c50b68ed3d7b.png)


## Gigabyte Z490I AORUS ULTRA
- 8+1 Phase VRM
  - Controller: ISL69269
  - VCore: 8x ISL99390 90A
  - SA: 1x SIC651A 50A
- 4x SATA, 2x M.2 (PCIe Gen3)
- 2x USB 3.2 Gen2 (1x Rear, 1x Rear Type-C)
- 7x USB 3.2 Gen1 (5x Rear, 2x Front, 1x Front Type-C)
- 6x USB 2.0 (2x Rear, 4x Front)
- Intel 2.5 Gigabit LAN
- Intel AX201 WiFi
- Realtek ALC1220-VB Audio
- Q-Flash Plus Button

##### Notes:
This board has an insane rear IO for an ITX board, also being very close in VRMs to the Z490I UNIFY. The Q-Flash Plus button could definitley come in use for flashing the BIOS without a CPU. This board is for sure a good idea if you are in need of a large IO in a small system. 

![z490iaorus](https://user-images.githubusercontent.com/91910634/144762585-88904b39-c605-4071-b0cf-c7b9d6c8bc61.png)


## MSI Z490I UNIFY
- 8+2 Phase VRM
  - Controller: ISL69269
  - VCore: ISL99390 90A
  - SA/IO: ISL99390 90A + ISL99360 60A
- 4x SATA, 2x M.2 (PCIe Gen3)
- 1x USB-C Thunderbolt 3
- 2x USB 3.2 Gen2 (1x Rear, 1x Front Type-C)
- 4x USB 3.2 Gen1 (2x Rear, 2x Front)
- 4x USB 2.0 (2x Rear, 2x Front)
- Realtek 8125B 2.5 Gigabit LAN
- Intel AX201 WiFi
- Realtek ALC1220 Audio
- Clear CMOS Button
- Debug LEDs

##### Notes:
With the best VRMs and memory overclocking capabilities out of the rest of the boards, this board packs a punch. Thunderbolt 3 and the rest of the decent connevtivity features will help in tasks such as productivity, and the debug LEDs and clear CMOS button on the rear IO will definitely help with overclocking.

![z490iunify](https://user-images.githubusercontent.com/91910634/144762620-9f4d729f-1a8d-481c-9d66-f457e9728d45.png)


## Verdict 

This is a very close competition, but the winner is the MSI Z490I UNIFY. It has the best VRMs out of the boards being able to easily handle a 10900K, great RAM topology for memory overclocking, and even debug leds and a clear CMOS button to make the overclocking process more efficient. Though the Gigabyte Z490I AORUS ULTRA is a close contender due to its insane rear IO, and VRMs nearly as good as the UNIFY.



# Credits/Sources

VRM Details: [Low End - Midrange](https://docs.google.com/spreadsheets/d/1yPS3hj_K7EPT4RBWCyjdKNP56pnwDz-IgBc0975-FUg/htmlview#), [High End](https://youtu.be/TmgR9qNGKlk)

I got the rest of the details about the boards from the manafactuers' sites.

If you have any more questions, ask them on my [Discord](https://discord.gg/u6QV6s6)
