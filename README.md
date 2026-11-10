<img width="1364" height="399" alt="image" src="https://github.com/user-attachments/assets/ccd7e7df-1d81-4c9b-a333-f68b5957412c" />
# Hacker Card 

## Made by Anshuman


### About
This was my fist ever PCB project and I started off with a simple one by making a hacker card (NFC Card).... what it does is that it acts as a wireless transmitting device which can be used by anyone and coded through their phones or any other device which accepts wireless transmission though antennas on it...

I feel like this is a pretty cool project for a beginner like me, imagine saying someone that "*I BUILT AN NFC CARD MYSELF WHICH CAN TRANSMIT DATA WIRELESS*"

Anyways, for it to look even better and match my aesthetics, I added a few patent-ish designs/blueprints of a few tech stuff like a 3d printer, motherboard, a car, and a chip..... This made the project have some depth and overall enhanced the expeience of building this from scratch 

For anyone thinking, "*Yes, Anshuman, we get it that u built an NFC card all by yourself but what about the power and energy needs of the card, will it be safe or not?*"
To answer that, this card does not need any power supply/battery to operate, it gains power wirelessly and operates entirely through the battery of the phone, hence it is completely safe for keeping near you without any problems... I KNOW ITS COOL RIGHT

What started off with just making a schematic diagram with a bit of help in understanding how the components of this card works, escalated to designing the PCB and then came the case designing part, which in my opinion was the most fun part as I could show my skills in designing a 3D model.... after all this I started making designs and bluepints on the card itself which took quite some time as I had to make it myself.
Overall I would rate this a 11/10 experience and would recommend every single teen to try this out and experience this project at least once


# Well, for the instructions on how you yourself could make this is as follows:
- The first thing is copy or download this repository and include all the files in.
  
- From there you can open the EasyEDA and navigate into schematic and PCB from the .epro src file in the src folder by importing it into EasyEDA pro (I personally would recommend using pro since I had also used it)

- Next step would be that you need to open the PCB editor from in EasyEDA and then change the text according to your needs, or even mine is fine if you like it 

- Then you need to change the QR code (If you are fine with the QR I have, then thats a plus point, since mine directs to my payment page, lol)

- Then if u dont like my patent blueprint theme (though it kinda genuinely looks cool, in my opinion), you can delete the images and then go to file > import > import image  and then import images of your choice (Make sure to import them on the front or back silkscreen not the defult front layer, trust me I have made that mistake)

- That's it, your PCB is done now all u need to do is go onto JLCPCB or PCB Way or any other PCB manufacturer and upload the gerbers (you can get all the fabrication files from easyEDA by going to file > export > gerbers/ pick and place file/ BOM)

- Then all you need to do is select the colour you want the card (From what I like, it should be black, as it just looks good)
  
- select PCBA if you dont want to assemble it yourself (Which you should as it would give you some experience and order the PCB... after waiting a bit you would be having a functional NFC card in your hands!!!


# Images (Cause why not)

<img width="803" height="523" alt="Screenshot 2026-11-10 134858" src="https://github.com/user-attachments/assets/2b7cbc7c-99e1-47fc-ad5c-d6d311b480f8" />


<img width="840" height="515" alt="Screenshot 2026-11-10 134915" src="https://github.com/user-attachments/assets/f9b85193-c4ab-4d2b-8b1b-9decc9bcb78b" />


<img width="822" height="555" alt="Screenshot 2026-11-10 134925" src="https://github.com/user-attachments/assets/3b7572b9-193d-4a2b-89e9-c3592a6b7cad" />


<img width="836" height="530" alt="Screenshot 2026-11-10 134940" src="https://github.com/user-attachments/assets/e0e5a653-aa29-4a34-bd3f-5499bde2d54f" />


<img width="1347" height="787" alt="Screenshot 2026-11-10 134950" src="https://github.com/user-attachments/assets/2f9b655d-bde3-4d07-af9a-ec08a26f5a39" />


<img width="1305" height="760" alt="Screenshot 2026-11-10 135000" src="https://github.com/user-attachments/assets/b7985f87-1dc0-4b5c-a754-8cbc2526dd81" />


<img width="940" height="806" alt="Screenshot 2026-11-09 163711" src="https://github.com/user-attachments/assets/d025b86c-bc03-4967-a925-03428f86cd8b" />


<img width="1022" height="762" alt="Screenshot 2026-11-09 163718" src="https://github.com/user-attachments/assets/3629b2db-db15-435a-93c6-b2d545540008" />


<img width="712" height="561" alt="Screenshot 2026-11-09 163728" src="https://github.com/user-attachments/assets/cf3f339e-bb1b-4848-9617-6ca9c4297d02" />


<img width="477" height="665" alt="Screenshot 2026-11-09 163752" src="https://github.com/user-attachments/assets/b51b017c-9e78-466d-b45a-c50ce12c47f7" />


<img width="1801" height="73" alt="image" src="https://github.com/user-attachments/assets/60b41bd9-7a3e-4fe7-93df-86b46347e056" />

.
## BOM ---> 

| No. | Quantity | Comment | Designator | Footprint | Value | Manufacturer Part | Manufacturer | Supplier Part | Supplier |
|:---:|:--------:|---------|------------|-----------|-------|-------------------|--------------|---------------|----------|
| 1 | 1 | 100nF | C1 | C0603 | 100nF | — | — | — | — |
| 2 | 1 | 13.56MHz | U1 | TSSOP-8_L3.0-W3.0-P0.65-LS4.9-BL | 13.56MHz | NT3H2111W0FTTJ | NXP | C2654884 | LCSC |
