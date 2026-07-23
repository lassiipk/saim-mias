## Journal Entry - 02

> Date: **22th July, 2026**
> 
> Time: 10:20

---

> ~~*First Journal was written on 12th July and this one is being written today (2nd-Journal_22th-July). There is a 10 days big gap between these two journals. You may ask: "Why is that?". Well, the answer is very simple: its because, I'm at my Hometown and I got no personal Computer and I got Power outage issue over here, So i got no time at all to work on this project. Its a pure shame for me that im contributing less and less on ths project.*~~

Alright. I'm almost done with the research about our development of the mouse. First I'll layout my research → All of this research is beign done using ***Google Gemini AI Chat Bot***, I'm thinking to add that Chat inside my Git REPO for record as a part of journaling (Maybe or maybe not!).

---

### Plan:

The plane is to use selective components to lock the plan in place and focus onit. No Bullshit! like; adding it unreasonable and unreachable features - I'll make sure to make a mouse that can be made from a rusty idea of mine into a reality.

I have created a list of components to use and they are quite easy to find over the internet and in my country/ region (I suppose!, 😋😁).

---

### Components

- **Microcontroller:**  
The first thing I figured out and locked it into place is a Microcontroller. While I was searching I got Suggestion about using: ***Nordic nRF52840 (or its smaller sibling, the nRF52832).***  
→ After looking its IRL Images I instantly droped it out of my project; Due to following reasons:  
1. **Size:** Its Size is Hella Small. Like crazy! Such as 7x7mm, 6x6mm, and 3.5x3.6mm.How the hell will i solder it to the PCB? I got no baking stuff like hot plate for soldring such things and its hella advance step!

![](https://github.com/lassiipk/saim-mias/blob/main/Assets/Images/Screenshots/MCU/Screenshot%202026-07-23%20210000.png)

2. **Other Components and understanding:** If i choose it then i'll have to lean other things as well such as things to get it working.

**Selected Part:**  
Instead of choosing this I got something better!, far more batter. and I've used it in past of my projects... Seeed XIAO Microcontroller - **Seeed Studio XIAO ESP32-S3**.

**Reasoning:**  
Why this one instead of others? well, the answer is very simple: 
Extremely tiny footprint in size and its kida cute!, pre-assembled, cost-effective, and includes native USB circuitry on-chip (requires no external USB-to-serial converter IC). Its 11 GPIO pins perfectly match the simplified, wired pin budget. Best suited for my project due to its compact size and secondly its reliability of using. I can simply boot my code into it as I've used **Seeed XIAO RP2040** in one of my first project and it was very easy to use and understand.

**Usefull link:**  
[Seeed-Wiki](https://wiki.seeedstudio.com/xiao_esp32s3_getting_started/)  
[Aliexpress]()  
[Seeed-Studio-Shop](https://www.seeedstudio.com/XIAO-ESP32S3-p-5627.html)  

---

- **Mouse Tracking Sensor:**  

**Selected Part:**  
PixArt PAW3395 (paired with LM19-LSI glass lens)

**Reasoning:**  
Flagship-tier tracking (up to 26,000 DPI), native 3.3V logic levels (no logic translation needed for the ESP32-S3), and highly active open-source firmware community support.