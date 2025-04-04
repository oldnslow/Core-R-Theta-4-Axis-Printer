# The Core R-Theta Printer

This is intended to be a series of FreeCAD versions of jyjbird's 4 axis, polar, "core-RΘ" 3D printer – an entirely new type of multi axis 3D printer designed from the ground up. To start a FreeCAD version of the "original" (f8d197c circa 16 Mar 2025 commit) will be generated.

Check out jyjbird's [youtube video](https://www.youtube.com/watch?v=VEgwnhLHy3g) to see it in action!
[![Watch the video](https://github.com/user-attachments/assets/1704345d-5ec4-4803-8fbe-49bbeaa76b13)](https://www.youtube.com/watch?v=VEgwnhLHy3g)


### Slicer
A multi axis printer is pretty hopeless without a non-planar slicer, which is why I built this quick [radial slicer](https://github.com/jyjblrd/Radial_Non_Planar_Slicer) for the printer. This leverages the printer's rotating nozzle to print simple parts without supports, but there are some limitations to it which I cover in the YouTube video. I'm also working on an optimization based slicer which will be able to print any object without support so stay tuned for that!

<img src="https://github.com/user-attachments/assets/190a966d-61a4-4c94-bd4a-7c1860c525db" width="500" />

### Assembly
There is a wealth of knowledge in the Discussions, Pull Requests and Issues tabs of this repo. The printer is by no means "plug and play", and there are no instructions as of yet, but the information in the discussions should help you get started. Feel free to post questions on the discussions tab.

You can view the [3d model online](https://viewer.autodesk.com/id/dXJuOmFkc2sub2JqZWN0czpvcy5vYmplY3Q6YTM2MHZpZXdlci1wcm90ZWN0ZWQvdDE3NDM1MjM1ODlfN2I3YjNkNzYtYTQ2NC00Y2YzLTgxZDYtYjk0MGJjMjlhMTJmLmYzZA?sheetId=eyJ0eXBlIjoiRGVzaWduIiwiYXNzZXQiOiJmOWE5MWRhYS0yMTc3LTQ2NTMtOTE1NC05ZmQ5YTM4ODhkMTkifQ) to see how to assemble the printer. Everything is 3D printable, however I got the extruder mount made out of metal by JLCPCB as there is quite a bit of torque on that part. I've also included the gerber files to make your own PCB buildplate, but a sheet of MDF wood would also work.


### BOM
Some links are included so you know what to get, but they are by no means the best source to get the parts.
|                          | Qty |                                                                                                                                                                                                                                                                                                                                                                                                                                | Note            |
| ------------------------ | --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------- |
| Frame                    |     |                                                                                                                                                                                                                                                                                                                                                                                                                                |                 |
| 2040 Extrusion 350mm     | 1   | [Aliexpress](https://www.aliexpress.us/item/1005005037443914.html?pdp_npi=4%40dis%21USD%21US%20%244.70%21US%20%242.87%21%21%214.70%212.87%21%402101585f17218160977374631e6f09%2112000031411902085%21sh%21HK%213408833611%21X&spm=a2g0o.store_pc_allItems_or_groupList.new_all_items_2007532827729.1005005037443914&gatewayAdapt=glo2usa)                                                                                             |                 |
| 2040 Extrusion 100mm     | 1   | [Aliexpress](https://www.aliexpress.us/item/1005005037443914.html?pdp_npi=4%40dis%21USD%21US%20%244.70%21US%20%242.87%21%21%214.70%212.87%21%402101585f17218160977374631e6f09%2112000031411902085%21sh%21HK%213408833611%21X&spm=a2g0o.store_pc_allItems_or_groupList.new_all_items_2007532827729.1005005037443914&gatewayAdapt=glo2usa)                                                                                             |                 |
| 2020 Extrusion 150mm     | 1   | [Aliexpress](https://www.aliexpress.us/item/1005005037443914.html?pdp_npi=4%40dis%21USD%21US%20%244.70%21US%20%242.87%21%21%214.70%212.87%21%402101585f17218160977374631e6f09%2112000031411902085%21sh%21HK%213408833611%21X&spm=a2g0o.store_pc_allItems_or_groupList.new_all_items_2007532827729.1005005037443914&gatewayAdapt=glo2usa)                                                                                             |                 |
| 2020 Extrusion 250mm     | 1   | [Aliexpress](https://www.aliexpress.us/item/1005005037443914.html?pdp_npi=4%40dis%21USD%21US%20%244.70%21US%20%242.87%21%21%214.70%212.87%21%402101585f17218160977374631e6f09%2112000031411902085%21sh%21HK%213408833611%21X&spm=a2g0o.store_pc_allItems_or_groupList.new_all_items_2007532827729.1005005037443914&gatewayAdapt=glo2usa)                                                                                             |                 |
| 2020 corner bracket      | 10  | [Aliexpress](https://www.aliexpress.us/item/1005002883833150.html?pdp_npi=4%40dis%21USD%21US%20%248.00%21US%20%245.36%21%21%218.00%215.36%21%402101585f17218162290038619e6f09%2112000022608302408%21sh%21HK%213408833611%21X&spm=a2g0o.store_pc_allItems_or_groupList.new_all_items_2007532827729.1005002883833150&gatewayAdapt=glo2usa)                                                                                             |                 |
|                          |     |                                                                                                                                                                                                                                                                                                                                                                                                                                |                 |
| Hardware                 |     |                                                                                                                                                                                                                                                                                                                                                                                                                                |                 |
| 2020 T Nuts              | 50  | [Aliexpress](https://aliexpress.us/item/1005003023734101.html?pdp_npi=4%40dis%21USD%21US%20%243.50%21US%20%242.27%21%21%213.50%212.27%21%402101585f17218164046887395e6f09%2112000023289976894%21sh%21HK%213408833611%21X&spm=a2g0o.store_pc_allItems_or_groupList.new_all_items_2007532827729.1005003023734101&gatewayAdapt=glo2usa)                                                                                                 |                 |
| MGN9 250mm Rail          | 1   | [Aliexpress](https://www.aliexpress.us/item/1005004908405311.html?spm=a2g0o.detail.0.0.3bb48SF18SF1v1&mp=1&gatewayAdapt=glo2usa)                                                                                                                                                                                                                                                                                                     |                 |
| MGN12 250mm Rail         | 2   | [Aliexpress](https://www.aliexpress.us/item/1005004908405311.html?spm=a2g0o.detail.0.0.3bb48SF18SF1v1&mp=1&gatewayAdapt=glo2usa)                                                                                                                                                                                                                                                                                                     |                 |
| MGN9C Block              | 2   | [Aliexpress](https://www.aliexpress.us/item/1005004908405311.html?spm=a2g0o.detail.0.0.3bb48SF18SF1v1&mp=1&gatewayAdapt=glo2usa)                                                                                                                                                                                                                                                                                                     |                 |
| MGN12H Block             | 2   | [Aliexpress](https://www.aliexpress.us/item/1005004908405311.html?spm=a2g0o.detail.0.0.3bb48SF18SF1v1&mp=1&gatewayAdapt=glo2usa)                                                                                                                                                                                                                                                                                                     |                 |
| M4 Screw Set             |     | [Aliexpress](https://www.aliexpress.us/item/1005002109863123.html?spm=a2g0o.productlist.main.17.7fe82c812tBHeu&algo_pvid=9b3adcc2-eaa7-49f5-827b-65c76ebec4ab&algo_exp_id=9b3adcc2-eaa7-49f5-827b-65c76ebec4ab-8&pdp_npi=4%40dis%21USD%2114.98%218.24%21%21%2114.98%218.24%21%402101364217218106530737554e0d29%2112000018775202479%21sea%21HK%213408833611%21&curPageLogUid=3mmH5TGniEUf&utparam-url=scene%3Asearch%7Cquery_from%3A) |                 |
| M3 Screw Set             |     |                                                                                                                                                                                                                                                                                                                                                                                                                                | Need 40mm screw |
| M3 Square Nut            | 50  | [Aliexpress](https://www.aliexpress.us/item/1005001612157787.html?spm=a2g0o.productlist.main.1.5d017e8aeZHkcO&algo_pvid=3c10a105-0205-4d35-910a-e991c6a990df&algo_exp_id=3c10a105-0205-4d35-910a-e991c6a990df-0&pdp_npi=4%40dis%21USD%212.68%212.28%21%21%212.68%212.28%21%402102f6cb17218121155956718ec6aa%2112000028150283667%21sea%21HK%213408833611%21&curPageLogUid=DIoZCeJsWn29&utparam-url=scene%3Asearch%7Cquery_from%3A)    |                 |
| MR85ZZ (5x8x2.5)         | 4   | [Aliexpress](https://www.aliexpress.us/item/1005002702288640.html?pdp_npi=4%40dis%21USD%21US%20%248.00%21US%20%245.20%21%21%218.00%215.20%21%402101585f17218166743287595e6f09%2112000021776689177%21sh%21HK%213408833611%21X&spm=a2g0o.store_pc_allItems_or_groupList.new_all_items_2007532827729.1005002702288640&gatewayAdapt=glo2usa)                                                                                             | B axis          |
| 6810ZZ (50x65x7)         | 2   | [Aliexpress](https://www.aliexpress.us/item/32862403898.html?spm=a2g0o.productlist.main.3.28051f017e5Tbz&algo_pvid=e4d6ce69-5943-4ac6-adf3-921e6b8d509a&algo_exp_id=e4d6ce69-5943-4ac6-adf3-921e6b8d509a-1&pdp_npi=4%40dis%21USD%215.39%214.31%21%21%215.39%214.31%21%402140e84617218120288452517e1693%2165529151447%21sea%21HK%213408833611%21X&curPageLogUid=G0ytiQ8Lm1Mz&utparam-url=scene%3Asearch%7Cquery_from%3A)   | C axis          |
| 5 x 50 mm Cylindrical Pin or Rod  |   1 | [Aliexpress](https://www.aliexpress.com/store/912228060)                                                                                                                                                                                                                                                                                                                                | B axis          |
| 5mm Flange Coupling      |  1  | [Aliexpress](https://www.aliexpress.com/store/1100176438)                                                                                                                                                                                                                                                                                                                                      | B Axis          |
| 5 x 11 x 6mm Retaining Ring Shaft Collar| 1   | [Aliexpress](https://jznb.aliexpress.com/store/3204060)                                                                                                                                                                                                                                                                                                          | B axis          |
|                          |     |                                                                                                                                                                                                                                                                                                                                                                                                                                |                 |
| Drive                    |     |                                                                                                                                                                                                                                                                                                                                                                                                                                |                 |
| NEMA 17 Stepper Motor 40mm with 300 mm T8\*8 Lead Screw | 1   | [Aliexpress](https://www.aliexpress.us/item/1005005575285492.html?spm=a2g0o.productlist.0.0.5d017e8aeZHkcO&mp=1&gatewayAdapt=glo2usa)                                                                                                                                                                                                                                                                                                |                 |
| T8\*8 Lead Screw Nut     | 1   | [Aliexpress](https://www.aliexpress.us/item/32957828816.html?pdp_npi=3%40dis%21USD%21%21US%20%240.80%21%21%21%21%21%4021410c4117218088288495225e8dd8%21%21im%21%21&gatewayAdapt=glo2usa)                                                                                                                                                                                                                                             |                 |
| Nema 17 34mm             | 3   |                                                                                                                                                                                                                                                                                                                                                                                                                                |                 |
| GT2 Belt Loop 410mm      | 1   |                                                                                                                                                                                                                                                                                                                                                                                                                                |                 |
| GT2 Belt Loop 760mm      | 1   |                                                                                                                                                                                                                                                                                                                                                                                                                                |                 |
| GT2 Pully 16T            | 2   | [Aliexpress](https://www.aliexpress.us/item/1005004314084512.html?pdp_npi=4%40dis%21USD%21US%20%241.33%21US%20%241.13%21%21%211.33%211.13%21%402101585f17218179467507717e6f09%2112000034179345936%21sh%21HK%213408833611%21X&spm=a2g0o.store_pc_allItems_or_groupList.new_all_items_2007567262458.1005004314084512&gatewayAdapt=glo2usa)                                                                                             |                 |
| GT2 Idler 16T w/o Teeth  | 4   |                                                                                                                                                                                                                                                                                                                                                                                                                                |                 |
| GT2 Pully 40T            | 1   |                                                                                                                                                                                                                                                                                                                                                                                                                                |                 |
| GT2 Idler 16T w/ Teeth   | 2   | [Aliexpress](https://www.aliexpress.us/item/32817328238.html?spm=a2g0o.productlist.main.1.154a6eafY9AYrN&algo_pvid=2e5559f6-0e2b-4699-af66-2900a6241a77&algo_exp_id=2e5559f6-0e2b-4699-af66-2900a6241a77-0&pdp_npi=4%40dis%21USD%210.83%210.80%21%21%210.83%210.80%21%402141069c17218103868312197ecd23%2112000030774036536%21sea%21HK%213408833611%21&curPageLogUid=WzjkJAxiIMiS&utparam-url=scene%3Asearch%7Cquery_from%3A)         |                 |
|                          |     |                                                                                                                                                                                                                                                                                                                                                                                                                                |                 |
| Electronics              |     |                                                                                                                                                                                                                                                                                                                                                                                                                                |                 |
| 5-Axis RRF Control Board | 1   | [Aliexpress Mellow 3D](https://mellow.aliexpress.com/store/1531088)                                                                                                                                           |Search in store for Fly RRF E3 Pro V3.0 |
| Micro SD Card &le; 32GB, Speed &ge; Class 4 | >1 | [Aliexpress MicroStick](https://www.aliexpress.com/store/2393021)                                                                                                                                           |Take your chances online, good to have a backup |
| 24V 10A Power Brick      | 1   | [Aliexpress](https://www.aliexpress.us/item/1005003088055215.html?spm=a2g0o.productlist.main.1.274c1017SLo2cI&algo_pvid=fc15f3c2-4225-43e2-b9f1-1ec7c4a5bb77&algo_exp_id=fc15f3c2-4225-43e2-b9f1-1ec7c4a5bb77-0&pdp_npi=4%40dis%21USD%217.80%214.68%21%21%217.80%214.68%21%402102f64217218109525782817ef4f1%2112000024005691633%21sea%21HK%213408833611%21X&curPageLogUid=nAQanWwxCNH1&utparam-url=scene%3Asearch%7Cquery_from%3A)   |                 |
| 5.5x2.5 plug             | 1   | [Aliexpress](https://www.aliexpress.us/item/33034810979.html?spm=a2g0o.productlist.main.15.74b863c0UZ5tpX&algo_pvid=a17ee02e-b212-4259-a89a-ef6d215554bc&algo_exp_id=a17ee02e-b212-4259-a89a-ef6d215554bc-7&pdp_npi=4%40dis%21USD%212.00%211.76%21%21%212.00%211.76%21%402101584517218110655627764e3a68%2112000037068940694%21sea%21HK%213408833611%21&curPageLogUid=KXHREOg0VjR1&utparam-url=scene%3Asearch%7Cquery_from%3A)        |                 |
| long nozzle              | 1   | [Aliexpress](https://www.aliexpress.com/item/1005007437644929.html?spm=a2g0o.order_list.order_list_main.39.6df81802pwJpHi)                                                                                                                                                                                                                                                                                                           |                 |
| aquarium pump            | 1   | [Aliexpress](https://aliexpress.com/item/1005005987431203.html?spm=a2g0o.order_list.order_list_main.219.6df81802pwJpHi)                                                                                                                                                                                                                                                                                                              |                 |
| BIQU H2 V2S extruder     | 1   | [Aliexpress](https://www.aliexpress.com/item/1005002027842161.html?spm=a2g0o.order_list.order_list_main.274.6df81802pwJpHi)                                                                                                                                                                                                                                                                                                          |



Bibtex Citation:
```
@software{Bird_Core_R-Theta_Printer,
author = {Bird, Joshua},
license = {View repository for custom license.},
title = {{Core R-Theta Printer}},
url = {https://github.com/jyjblrd/Core-R-Theta-4-Axis-Printer}
}
```
