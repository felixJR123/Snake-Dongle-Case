# Snake Dongle Case
### I'm still have not finished the readme file. Please look at the pictures for assembly until the build guide is completed, the switches are held with pieces of filament inserted into the holes in the back piece.
### Before assembly make sure all the wiring is complete and the dongle is working, also leave enough slack on the cables from the screen to the mcu, the rest of the cables can be cut to size.

This is a build guide for the enclosure of the [Snake Dongle](https://github.com/joaopedropio/snake-dongle)\
There are 2 different types of enclosures for this dongle, one that use the original 6x6x8 tactile switch specified on the snake dongle repo and one that use the switches used in computer mouse. Each of those versions have a variation for #4-20 or M3 screw with plastic threads and another variation for M2 screws and M2 heatset inserts .

## Build Guide for enclosure 
### Parts needed

### Enclosure
If you choose to use the same parts specified in the dongle repo. The 3D files are located in the folder [Tactile Switches](https://github.com/felixJR123/Snake-Dongle-Case/tree/main/Files/Tactile%20Switches)\

If you choose to use the mouse switches, the rest of the parts will be the same as the dongle repo but you will need to purchase 2 mouse switches. The 3D files are located in the folder [Mouse Switches](https://github.com/felixJR123/Snake-Dongle-Case/tree/main/Files/Mouse%20Switches)
There is also a version that uses tactile switches but the screen is the waveshare 1.54in https://www.waveshare.com/1.54inch-LCD-Module.htm The 3D files are located in the folder [Waveshare Screen](https://github.com/felixJR123/Snake-Dongle-Case/tree/main/Files/Waveshare%20Screen)

### Screws 
For the M2 versions
| Qty | Description                                                       | Sample                                           |
| --- | ----------------------------------------------------------------- | ------------------------------------------------ |
| 5   | M2 x 8 thru 12mm long                                             | [Amazon](https://a.co/d/0d4cgYSR) or [Ali Express](https://www.aliexpress.us/item/3256805692722422.html?spm=a2g0o.productlist.main.2.462e2044JBRDsD&algo_pvid=e4df3f4b-0cf6-46ea-86c5-f8842f01f22e&algo_exp_id=e4df3f4b-0cf6-46ea-86c5-f8842f01f22e-1&pdp_ext_f=%7B%22order%22%3A%2237653%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21USD%211.43%211.43%21%21%211.43%211.43%21%402103212517704879980464792ef881%2112000034679037242%21sea%21US%216156200203%21X%211%210%21n_tag%3A-29919%3Bd%3A1069fc62%3Bm03_new_user%3A-29895&curPageLogUid=rxpRiNYZEcBw&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005005879037174%7C_p_origin_prod%3A)|
| 5   | M2 heat set insert with 3-3.2mm outer diameter lenght can vary    | [Amazon](https://a.co/d/08Zx6keB) or [Ali Express](https://www.aliexpress.us/item/3256807466816961.html?spm=a2g0o.productlist.main.2.6315NxKKNxKK9G&algo_pvid=0b755c8b-4d97-4c30-aa9b-1041722fc446&algo_exp_id=0b755c8b-4d97-4c30-aa9b-1041722fc446-1&pdp_ext_f=%7B%22order%22%3A%228055%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21USD%211.80%211.80%21%21%211.80%211.80%21%402101e07217704877184042871ec32b%2112000041667111405%21sea%21US%216156200203%21X%211%210%21n_tag%3A-29919%3Bd%3A1069fc62%3Bm03_new_user%3A-29895&curPageLogUid=hSg5OBDCTic5&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005007653131713%7C_p_origin_prod%3A)|

If the mounting hole in the buzzer is too large M3 x 8mm srew can be used instead of the M2 heat insert and screw

For the #4-20 or M3 plastic screw versions
| Qty | Description                                                       | Sample                                           |
| --- | ----------------------------------------------------------------- | ------------------------------------------------ |
| 5   | #4-20 or M3 screw for plastic threads 8 thru 12mm long            | [Amazon](https://a.co/d/069thOSX) or [Ali Express](https://www.aliexpress.us/item/2255800056366946.html?spm=a2g0o.productlist.main.11.3989EgwIEgwI5q&algo_pvid=b2a9beb9-6c1d-44a3-b5d8-6094c2390595&algo_exp_id=b2a9beb9-6c1d-44a3-b5d8-6094c2390595-10&pdp_ext_f=%7B%22order%22%3A%22797%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis!USD!1.52!1.48!!!1.52!1.48!%40210319b017703471897706731e17f9!12000034183485822!sea!US!6156200203!X!1!0!n_tag%3A-29919%3Bd%3A1069fc62%3Bm03_new_user%3A-29895&curPageLogUid=R8LF9aevQwlW&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A4000242681698%7C_p_origin_prod%3A)|

### Electronics
All electronics are the same as on the Snake Dongle repo with the exception of the reset and menu switches.
The tactile switch version uses 2 6x6x8 tactile switch [Amazon](https://a.co/d/02oBYbTl) or [Ali Express](https://www.aliexpress.us/item/3256809519260867.html?spm=a2g0o.productlist.main.2.191fpmZwpmZwkX&algo_pvid=d6651fe3-3b54-4dac-88ac-8a9ded964fde&algo_exp_id=d6651fe3-3b54-4dac-88ac-8a9ded964fde-1&pdp_ext_f=%7B%22order%22%3A%227%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21USD%213.64%211.82%21%21%2125.15%2112.57%21%40210328d417704882612115462eb3a3%2112000049910992171%21sea%21US%216156200203%21X%211%210%21n_tag%3A-29919%3Bd%3A1069fc62%3Bm03_new_user%3A-29895&curPageLogUid=RNHexiEzQvXp&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005009705575619%7C_p_origin_prod%3A)\
The mouse switch version uses 2 mouse switches [Amazon](https://a.co/d/0a1DLIsz) or [Ali Express](https://www.aliexpress.us/item/3256804568100432.html?spm=a2g0o.productlist.main.21.4e9efb6fV6hmwd&algo_pvid=6907cde6-52bf-4e42-9856-c91769b90653&algo_exp_id=6907cde6-52bf-4e42-9856-c91769b90653-20&pdp_ext_f=%7B%22order%22%3A%22260%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21USD%215.94%215.94%21%21%215.94%215.94%21%4021030a6217704885538576110ef35b%2112000030346558628%21sea%21US%216156200203%21X%211%210%21n_tag%3A-29919%3Bd%3A1069fc62%3Bm03_new_user%3A-29895&curPageLogUid=ja7lt2Qbhg1n&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005004754415184%7C_p_origin_prod%3A)

Disclosure: I have NO afiliation to Amazon or Aliexpress. The links are only a reference of what to purchase, feel free to browse around.

### Assembly



     
