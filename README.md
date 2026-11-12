# DESK PET
A desk pet called Starbie. Starbie is a tiny, starry digital pet that replaces traditional buttons with pure gesture control.
<img width="488" height="355" alt="image" src="https://github.com/user-attachments/assets/c51fd43b-7b67-4224-b421-c181de2e729b" />



# WHAT IS IT?
A desk pet is a project that is intended to sit at your desk and add some personality and fun to it. Starbie is an example of a desk pet. It does not really have any other actual use like some other projects do, but it acts as a good way to learn some useful skills needed to advance in the field of electronics while also giving u a cool desk accessory while you are at it. Who doesn't love a cute little pet right? This desk pet is no different. It has different functions depending on what u do with it (Discussed More below). 
<br>
<br>_This build of the pet includes a idle Jellyfish sprite, a shake reaction, tilt controlled radial menu, hidden stats and a extra bubbling effect !_

# WHY?
This project was made to be the project for the week 1 of Hack Club half life. It is me following a guided project as a complete beginner. It is also to learn the basics of hardware and electronics to create more unique projects in the future of my own!
<br>*(This project has a few changes like the microcontroller I used and others, to account for local availability)*

# HOW TO START MAKING?
Starbie is actually not that hard to make!. It just requirs a bit of patience and the eagerness to learn. And it is really customizable too. You can change its shape to whatever you want, add custom functions, reduce complexity if you are a beginner or add even more stuff if you know what your doing. This build of Starbie has the function to detect movement and also the environment!
MATERIALS YOU NEED:
1. Esp32-C3-Supermini (The main microprocessor)
2. DHT11 (The environment sensor)
3. MPU6050 (Gyroscope to detect movement)
4. 10k Ohm Resistor
5. Display OLED SSD1306 128x64 (The display where u actually see your pet)
6. 2x Cherry MX switches; you can use other MX switches too to reduce cost (To control the pet)
7. 2x MX compatible Keycaps

# How the parts fit:
The ESP32-C3 Supermini is the main brains of the project. It is what controls everything else. The dht11 is the environment and humidity sensor. It gives data to the esp which is then processes to perform the task assigned. Same goes for the mpu6050 which gives tilt and movement info. The Switches are to select and control the functions of the pet. The display is the part that actually makes it behave as a pet. It shows a idle jellyfish sprite and also other functions like hearts, or jumping, or bubble trails when interacted it with. <br>_You will see other more unique functions once you actually build it yourself!_

# Project Status
Designing Phase is complete. The physical board is yet to be made, tested , and recorded.
The PCB design, firmware, Schematics, Gerber Files and the BOM are uploaded here.
<br>_Further changes to the modes, features and designs could be added later_

# Project Photos:
Schematic:
<br><img width="704" height="437" alt="image" src="https://github.com/user-attachments/assets/b4de2bab-5b85-4e6e-9846-998f78f6bcd2" />

<br>PCB:
<br><img width="522" height="415" alt="image" src="https://github.com/user-attachments/assets/2a61c40c-3eaa-4dd0-8f2f-d6ed86a6137a" />


#Bill of Materials:
This bill is mostly fit for the country from where I am building this (Nepal), if if it isn't possible to buy these items from where you are, you could resort to international vendors.
| Item | Link | Price (USD) |
|---|---|---:|
| ESP32-C3-Supermini | [Ekaithau](https://ekaithau.com/products/esp32-c3-mini/) | $5.98 |
| 0.96-inch OLED Display SSD1306 128×64 | [Himalayan Solutions](https://himalayansolution.com/product/0-96-inch-oled-display-white) | $3.32 |
| DHT11 Temperature and Humidity Sensor | [Himalayan Solutions](https://himalayansolution.com/product/dht11-temperature-and-humidity-sensor) | $0.66 |
| GY-521 MPU6050 Accelerometer and Gyroscope | [Himalayan Solutions](https://himalayansolution.com/product/mpu-6050-module) | $2.33 |
| Keycaps (Pack of 21) (×1) | [Aliexpress](https://www.aliexpress.com/item/1005012239749346.html?spm=a2g0o.productlist.main.3.3f144d549mz35h&algo_pvid=506c8727-3e36-41af-bb6c-d233ef1303f6&algo_exp_id=506c8727-3e36-41af-bb6c-d233ef1303f6-2&pdp_ext_f=%7B%22order%22%3A%2215%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21NPR%211280.25%21163.79%21%21%218.52%211.09%21%402101528c17943132790031985e0ef3%2112000057855706932%21sea%21NP%216050325592%21ABX%211%210%21n_tag%3A-29910%3Bd%3A4b5c7ce9%3Bm03_new_user%3A-29895%3BpisId%3A5000000219357547&curPageLogUid=ADOSwM0hiseN&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005012239749346%7C_p_origin_prod%3A) | $1.10 |
| HMX Taro Ball Linear Switch (×2) | [ErgoKeys Nepal](https://ergokeysnepal.com/product/hmx-taro-ball-linear-switch/) | $0.84 |
| **Total** | | **$14.23** _(Including shipping)_|

_Prices may fluctuate_
<br>_PCB prices (JLCPCB)
<br> PCB price = $4
<br> Delivery fee (the reasonably priced one takes long 18-24 days) = $13.30 ; E-Post
<br> Total = $17.30 (but with a coupon for new user it becomes 13.30)
<br> *I was going to order two pcbs at the same time and get divide the shipping fee but since the second project wont get approved by then, i will not be able to do so*
<br>So pcb + other parts = 27.53$



<br> <img width="926" height="485" alt="image" src="https://github.com/user-attachments/assets/524cba19-286f-4a8c-bcb7-624ce9a709b8" />


<br> <img width="926" height="484" alt="image" src="https://github.com/user-attachments/assets/7dc236a2-9760-4abc-a74f-5275f9227b38" />
<br> <img width="927" height="484" alt="image" src="https://github.com/user-attachments/assets/4f12b5a0-153a-4b28-90aa-8ef5dcef2b49" />
<br> <img width="1855" height="967" alt="image" src="https://github.com/user-attachments/assets/2bef4912-df4f-404d-8d2a-c41c927dc6ea" />



