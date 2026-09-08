# Wireless Speaker 

*Date: December 2025 - March 2025* | Personal project during grade 12

<img src="./Pictures/Speaker-Final-Main.jpg" alt="Wireless Speaker Main Picture" width="250"/>

---

A portable, wireless speaker that offers incredible battery life, high quality audio, as well as a whole heck of a lot of bass!

---

## Project Overview

**Objective:**  
Wanting to further increase my engineering skills, a speaker seemed like an easy project to start with. I wanted to create a speaker that I could bring around with me that sounded good and that had a lot of bass (as I enjoy listening to a lot of EDM music). Also as a high school student, I wanted to keep this somewhat budget friendly, especially after my [3D Printed Iron Man Suit](https://github.com/TheTronEngineer/Tron-Portfolio/tree/main/Projects/3D%20Printed%20Iron%20Man%20Suit)

This means the speaker had to be:
* Light enough to carry
* Big enough and have enough power to output a lot of sound
* Have a portable power source to be able to use it in different locations
* As cheap as I could get the parts
* Ideally somewhat stylish
* Durable enough to take it places


**Constraints:**  
A big limiting factor that was difficult for me at the beginning was knowledge. I hadn't really played with anything more than Arduinos before, so this was a lot different trying to mix different components with little to no documentation. 

---

## Engineering Process

**Design/Planning:**  
I started off with lots of reaserch. I watched plenty of Youtube videos on people building speakers, talking about nessisary components, and showing their build process. This really familiarized me with how speakers work and how to build them. From this, I determined I needed the following parts:  
* **Speaker driver**
* **Amplifier**
* **Cabinet (enclosure)**  
Along with a couple extras such as foam/insulation for the inside of the cabinets, and anthing else I wanted to decorate the speaker with or things that added funcitonality, like a handle

After this, came more reaserch. In order for everything to work, the power source needed to match with the amplifier, and the speaker drivers needed to match resistance with the amplifier and have a greater or equal power handling than the amplifier output. **So each part needed to be chosen carefully in order to have everything work properly.** One thing that helped with this was a free subwoofer from my uncle; I used this as a fixed component and planned the rest of the components from the sub

In the end, I decided on a **2.1 system** (right and left channel, and a subwoofer). This was driven by a fairly cheap bluetooth amplifier. The whole speaker was powered by a 24V 12Ah battery. The battery was chosen from some simple calculations coming from the max output of the amplifier

Along with the components, the speaker cabinet needed careful planning as well. Each speaker driver works differently in different sized cabinets, so **finding the optimal size for each would increase the volume and quality of the speaker.** I also learned a bit about ports, and how a certain length opening in a cabinet can help boost some low end sound. To find this optimal size, I used a software called **WinISD.** this gave me a volume for the sub and the two channel speakers and the length and size of the port I needed.

And finally, style! What would be the point of a speaker if it didn't look at lease a little cool? I had done a bunch of thinking and a little bit of sketching to help invision different designs. As seen in the picture below, I settled on a mostly rectangular design with some slightly rounded corners. I also did a basic model in Fusion 360 to get an idea on size and look of the speaker  
<table>
  <tr>
    <td><img src="./Pictures/Speaker Designs.jpg" height="250"></td>
    <td><img src="./Pictures/Cabinet Design Fusion 360.jpg" height="250"></td>
  </tr>
</table>


**Building/Iterating:**  
Now this was the fun part! After about 3 months of planning, simulating, calculating and designing, I was ready to build! I ordered the parts and had everything slowly arrive. As parts arrived, I started wiring the speaker direvers to the amplifier and a 12V power supply I had on hand to test the electronics. Thankfully, the speakers worked on the first try, with me being able to stream music over bluetooth and adjust volume and a couple other parameters with the knobs on the amplifier. However the sound out of the drivers wasn't too loud because it was just playing in the open air  
<table>
  <tr>
    <td><img src="./Pictures/All Drivers.jpg" height="300"></td>
    <td><img src="./Pictures/Amplifier.jpg" height="300"></td>
    <td><img src="./Pictures/Battery Life Display.jpg" height="300"></td>
    <td><img src="./Pictures/Battery.jpg" height="300"></td>
  </tr>
</table>

After I had recieved all the electronics, I started to build the enclosure the the port for the speaker cabinet. I chose to use MDF as the cabinet material as it was a common choice online due to it's flat surfaces that would help reflect sound evenly inside the enclosure. I also put some insulation inside the left and right channel cabinet to help reduce resonant sound waves, creating a cleaner sound  
I 3D printed the port in the speaker. I was initially concerned about vibrations and resonant frequency within the print, but I made sure to print it with solid infil and out of PETG so that wouldn't be a massive issue. Unfortunately due to the lack of space, I had to cut out a bit of the port so it would fiton the side of the speaker (as seen in the 4th image below)  
As a note, I did not include insulation in the subwoofer cabinet becuase the resonant sound waves are meant to travel out the port, giving it it's extended frequency range. It was important to mount the battery with a custom printed cage to the electronics compartment so it wouldn't swing or bang around while in use  
<table>
  <tr>
    <td><img src="./Pictures/Speaker-BareFrame.jpg" height="300"></td>
    <td><img src="./Pictures/Speaker-BatteryCageDesign2.jpg" height="300"></td>
    <td><img src="./Pictures/Speaker-PaintingFrame.jpg" height="300"></td>
    <td><img src="./Pictures/Speaker-PortInstallation.jpg" height="300"></td>
  </tr>
</table>

One other fun part of this project is I got to design the control pannel for all the electronics. I modelled this in Fusion 360 with measuring components with calipers. I am very happy with how it looks, and it's held up really well!
<table>
  <tr>
    <td><img src="./Pictures/Speaker-ElectronicsInstalled2.jpg" height="400"></td>
    <td><img src="./Pictures/Speaker-Final-Controls.jpg" height="400"></td>
  </tr>
</table>

Now there were some surprise additions to this project as I went along as well. My uncle I talked about a little while back? I visited him as I was building my speaker and i brought what I had (a mostly built cabinet with working electronics) to show him. His ADHD took over during the visit, so we flipped the speaker over, drilled a hole and added a second subwoofer to the speaker! Is this optimal? Probably not. Is it twice as awesome (and louder??), heck yea!! We ended up testing the sub both in series and in parallel. Series seemed to give more general volume and a smoother sound. Parrallel seemed to add a lot of extra punch to the bass. I chose to go in series as the subs were already fairly loud, so the punch was a little harsh sometimes  
Another addition I made quite a while later was some custom printed knobs. This was partially because the gold spray paint on the current knobs was coming off, but also because I realised that the controls were not intuitive whatsoever. this gave me a change to design small images that better depicted what each knob controlled (can you guess what each does?)  
<table>
  <tr>
    <td><img src="./Pictures/Speaker-Final-Back.jpg" height="400"></td>
    <td><img src="./Pictures/Speaker New Knobs.jpg" height="400"></td>
  </tr>
</table>

I am super happy with how the speaker came out. It looks pretty professional, as well as sounding great with plenty of bass to go around  
<table>
  <tr>
    <td><img src="./Pictures/Speaker-Final-Main.jpg" height="400"></td>
    <td><img src="./Pictures/Speaker-Final-Front.jpg" height="400"></td>
  </tr>
</table>


**Testing and Validation:**  
Now especially because I was new to lots of this type of electronics and projects, I did lots of testing as I went through this project. The large amount of reaserch that I did for this project really helped me pick out the right parts for the speaker, but the tests were really the bits of motivation and verification that helped me remain confidant. These are the different landmark tests I did to ensure everything was working:  
* Tested the subwoofer with the amplifier and a 12V power supply I had on hand by plaing music from my phone over bluetooth
    * Although I didn't get a full speaker experience or much volume, I was very excited to see that I could play music from my phone on this sub!
* Tested the left and right channels with the amplifier and the 12V power supply by plaing music from my phone over bluetooth
    * This was slightly less exciting than the subwoofer, but this helped me know that I had picked good drivers to pair with the sub
* After I had wired the circuit with the switch and battery display, I tested the speaker drivers once again to ensure the speaker could run off of the battery
    * I was quite nervous doing this test, especially as a 24V 12Ah battery is no joke. I took many precautions and safties to ensure the terminals wouldn't cross or short
* Tested the speaker all assembled, minus one side panel (I still had some work to do inside before sealing)
    * I did this at my uncles when we added the second subwoofer, which also came with it's testing. This was probably the happiest I had been the entire project. Now being able to nearly close the cabinat, I could hear that the enclosure really does make the speaker much louder, and got me really excited about the end product
* Finally, I tested it before I sealed everything up, ensuring my wiring wouldn't break and I wouldn't need to access the inside again
    * After sealing it, I was free to finish any painting and play it to my hearts content!


---

## Reflection

**Achievements and Accomplishments:**  
What did you like about the project, what went well, what did you learn?


**Future Improvements:**  
What would you change for next time, what didn't go super well, what did you learn?

---

## Author

Aiden Nickel 
Mechatronic Systems Engineer | Western University

[LinkedIn](www.linkedin.com/in/aiden-nickel) | nickelaiden@gmail.com
