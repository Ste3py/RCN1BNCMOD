# RCN1BNCMOD

This project is about replacing the original antenna with a BNC connector on the DJI RCN1 (not tested on RCN3).

![Warranty Void](https://img.shields.io/badge/Warranty-VOID%20if%20installed-red?style=for-the-badge&logo=skynet)

![RCN1_1](img/img_3.jpg) 
![RCN1_2](img/img_4.jpg)

Parts needed (no Affiliate links) :
- [Cable](https://aliexpress.com/item/1005003822770662.html?spm=a2g0o.productlist.main.1.58d2yOewyOew8u&algo_pvid=aee48d5e-11d2-44ac-80dc-ca920e3ed368&pdp_ext_f=%7B%22order%22%3A%2234%22%2C%22eval%22%3A%221%22%7D&utparam-url=scene%3Asearch%7Cquery_from%3A)
- [tools](https://www.ifixit.com/fr-fr/products/pro-tech-go-toolkit)
- [Heated inserts M3*4mm](https://www.ruthex.de/en/collections/gewindeeinsatze/products/ruthex-gewindeeinsatz-m3-100-stuck-made-for-voron-rx-m3x5x4-messing-gewindebuchsen-fur-3d-druck)
- [M3*5 FLat head screws (7)](https://aliexpress.com/item/1005007798633538.html?spm=a2g0o.productlist.main.11.1e053b3bzOWhai&algo_pvid=ff88c89f-80c6-4083-8a48-1f996d42fa44&pdp_ext_f=%7B%22order%22%3A%224310%22%2C%22eval%22%3A%221%22%7D&utparam-url=scene%3Asearch%7Cquery_from%3A)
- Filament (any filament is fine, but I recommend PETG or PETG-CF)
- a 3D Printer
- a Drill
- a 2.8mm drill bit

Antenna Side 
- [BNC Male to RP SMA](https://aliexpress.com/item/1005007758452385.html?spm=a2g0o.productlist.main.5.3947108aQUAhFi&algo_pvid=55851f22-6f12-454e-890f-814c01c199c4&pdp_ext_f=%7B%22order%22%3A%22177%22%2C%22eval%22%3A%221%22%7D&utparam-url=scene%3Asearch%7Cquery_from%3A)
- [Antenna](https://alfa-network.eu/apa-m25) (Any Wi-Fi antenna should work — just make sure it supports both 2.4 GHz and 5.8 GHz bands)

🛑 Disclaimer:
I won’t cover how to open the RCN1 here, because disassembly will void your warranty.
However, I will show you how to install the mod once it’s open.

1️⃣ Once the controller is open, disconnect the joysticks.

![RCN1JOYSTICK](img/img_5.jpg)

2️⃣ Unscrew these three screws.

![RCN1screw](img/img_1.jpg)

3️⃣ You now have access to the PCB.
(Ignore the modded state of my controller. I’ve already done the mod and don’t have a second RCN1 to show from scratch. The process is the same.)
Disconnect all connectors and remove the screws.
Remove the batteries first.
Be careful with the flex connector under the cage.

![RCN1MB](img/img_0.jpg)

4️⃣ Remove the motherboard.
Then unscrew these two screws and remove the two transparent parts.

![RCN1COVER](img/img_7.jpg)

At this point, your setup should look similar to mine, except you'll still have the original antenna attached.

![RCN1naked](img/img_14.jpg)

5️⃣ Remove the antenna holder by unscrewing these six screws.

![RCN1nakedalt](img/img_14_alt.jpg)

Now you have this piece out:

![RCN1holder](img/img_10.jpg)

Place it back **without screwing it in**.

![RCN1holder](img/img_12.jpg)

**Assembling the BNC Connector**
6️⃣ Install the heated insert into the main part, then mount the BNC connector.

![RCN1BNC1](img/img_8.jpg)

7️⃣ On the internal support, install the heated insert and pass the cables through the holes.
It’s a bit tedious, but there’s enough space. Just be gentle to avoid damaging the connectors.

![RCN1BNC1](img/img_9.jpg)

8️⃣ Assemble both parts using two M3*5 screws in these holes.

![RCN1BNC2](img/img_8_alt.jpg)

![RCN1BNC3](img/img_11.jpg)

9️⃣ Slide the BNC assembly into the holder.

![RCN1BNC4](img/img_13.jpg)

🔟 Mark the three small holes using the 2.8mm drill bit by hand.

![RCN1BNC5](img/img_13_alt.jpg)

1️⃣1️⃣ Remove everything and drill the holes properly.
Then use a screw to cut threads into the plastic and secure everything into place.

![RCN1BNC6](img/img_14_alt2.jpg)

1️⃣2️⃣ Route the cables as shown.
You may need to trim some plastic from the transparent parts to accommodate the thicker cables.

![RCN1BNC7](img/img_15.jpg)

1️⃣3️⃣ Reassemble everything.
Note: there’s no special place for the U.FL connector — route it carefully.

⚠ Don’t forget to connect the antenna before powering on the controller!


Shield: [![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg
