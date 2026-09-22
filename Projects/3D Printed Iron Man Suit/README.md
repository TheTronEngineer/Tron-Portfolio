# 3D Printed Iron Man Suit

*Date: September 2023 - October 2023*

<table>
  <tr>
    <td><img src="./Pictures/Dark Pose.jpg" height="400"></td>
    <td><img src="./Pictures/Pose Mask Open.jpg" height="400"></td>
  </tr>
</table>

---

**Description**  
A fully 3D Printed Iron Man Suit equipped with working lights and a motorized helmet

---

## Project Overview

**Objective:**  
This project was heavily influenced by the Youtuber [Frankly Built](https://www.youtube.com/@FranklyBuilt). For the most part I thought it would be really cool to be Iron Man for haloween, but underneath this, I also wanted to take on a real engineering project and start to refine my skills. I wanted to create a functional project with many different types of systems that could work together. I had also constructed an Iron Man suit the year previous out of cardboard, so here I wanted to improve on my previous knowledge and make something truly impressive.

This means I wanted to suit to meet these criteria:
* Be functional
    * I wanted each system in the suit to function consisitantly, or at least enough to get through 1 day of haloween
* Look good and cohesive
    * I wanted this suit to actually look good! Not like a small craft project, but something that looks like an engineering project
* To remain cheap...
    * As hard as this was with the scale of the project, I was still a high school student with a high school budget, so I needed to minimize the cost where possible

**Constraints:**  
* Experience
    * This would be my first major engineering project that I had undertaken with 3D printing (as this was my decided media of manufacturing). Learning how to print long prints and large prints, especially in not ideal circumstances was tricky
* My own body
    * Unfortunately I can't change how I'm shaped to fit the suit, so I would have to fit the suit to me. This proved to be tricky, especially without any fancy fitting tools
* Time
    * Since I started working on this project in September and was aiming to be finished before Haloween, time was a big constraint, only giving me 2 months for this project. Additionally, I still had a full school day that would take away from my time working on this project
* Printers + build volume
    * One other obstacle that had to be worked around was the fact that I only had 1 printer, and one with a reletively small build volume compared to the peices of armour I wanted to print. This would force me to be creative with how I printed and fabricated parts

---

## Engineering Process

**Design/Planning:**  
Now, this being my first major engineering project, lots of reaserch was nessisary to gain direction for this project. This started mainly by watching videos on Youtube, lots from Frankly Built, on others building cosplay suits with 3D printing. This was very helpful as I was able to watch as people made mistakes and gave advice through their building process.

After watching others do these builds, I was excited and motivated to start my own. This is where I started to make plans on how I wanted to go about building my suit. Here I decided to purchace suit files, as this size of modelling was to large for my skills and the time constraints. To find a 3D model of an Iron Man suit, I followed the same company as Frankly Built, D03D. Here I chose to purchace the Mark 4 armour for my suit. Additionally, I decicded to make the suit out of PLA as it was a cheap filament that was easy to print.
<table>
  <tr>
    <td><img src="./Pictures/Iron Man MK 4 refrence.jpg" height="400"></td>
  </tr>
</table>
(^Refrence Image of the suit I was building^)

**Building/Iterating:**  
To start this project, I went straight to printing the helmet. However, the printer I had only had a build volume of 256mm^3, meaning many of this files would have to be chopped into smaller pieces in order to be printed. This also meant that I needed to orecombine these peices later on somehow. I chopped the helmet, sliced the files and sent it to the printer. For the helmet to fit both me and it's electronics, I had to take measurements of my head to scale the helmet files.
<table>
  <tr>
    <td><img src="./Pictures/Printing Face Mask.jpeg" height="400"></td>
  </tr>
</table>
When looking at print settings for this peice, I had to balence both time and strength for this project to be functional in time. Here are some of the settings I used:
* 0.28mm layer height
    * This was mostly to reduce the time prints would take, especially as I did not have a speedy printer
* 2 wall loops
    * This amount of walls was a good balence between time and strength. Additionally I chose to go light on the infill since I was printing thin pieces and the shell of the piece has a bigger contribution to its strength than infill
* Rafts Enabled
    * Rafts are a essentially a mini surface the printer prints to act as a print bed for the piece. As I was printing in a shed outdoors, I had trouble with prints sticking. For some reason this seemed to make prints consistantly stick to the plate, so I kept this on
<table>
  <tr>
    <td><img src="./Pictures/Hands No Paint.jpg" height="300"></td>
    <td><img src="./Pictures/Helmet No Paint.jpg" height="300"></td>
    <td><img src="./Pictures/Upper Body No Paint.jpg" height="300"></td>
  </tr>
</table>
For many armour peices, I had to bring them into Fusion 360 to split them so they can be printed. While these pieces were being printed, I had a variety of other tasks that also needed work to pull the armour together.
* Stitching armour pieces back together (cause I split them for printing)
* Smoothing and painting armour pieces
* Wiring and coding electronics and lights for the helmet and chestplate
* Assembling armour pieces to be wearable!

First I'll talk about stitching armour pieces together. Since they had been split for printing, I needed a way to fuse them back together to get the full piece. For this, I was inspired once again by Frankly Built and other online sources to use a soldering iron to melt the plastic pieces together. This gives very good strength as melting the plastic makes the joint as if it was printed that way. All the rafts and supports from my prints supplied me with extra material to melt on top for increased strength. The downside of this method is that it left a fairly ugly seam that had to be post-processed extra well.


Post-processing the pieces was the next step in this process. The process I went through for each peice followed these steps:
* Sanded the armour pieces to knock down big layer lines
* Used a spray primer to fill in the remaining layer lines
    * Here I used 2-3 coats and came back with some sanding when necessary
* Painted the pieces with a metallic gold spray paint
    * Here I did 3 coats of the gold paint
* Tape off any section I wanted to stay gold
* Spray paint a Metalcast red over the whole piece
Sanding and painting is where I realised that the big layer height left very visible lines after painting. However I couln't sand for too long as my patience and time for the project dwindled. Sanding the print and the primer also gummed up the sandpaper, so that made the process tricker. In the future I would want to look into wet sanding. The Metalcast red spray paint worked differently than most paints. Instead of being opaque, this was more similar to a heavy tint. So this colour needed a metallic base underneath to be shiny. This is why I painted gold everywhere, then taped off the sections to paint the red on top. This process taught me a lot about spray painting, patience and percision, especially as the Metalcast Red was quite runny.
<table>
  <tr>
    <td><img src="./Pictures/Paint Booth.jpg" height="300"></td>
    <td><img src="./Pictures/Paint Used.jpg" height="300"></td>
    <td><img src="./Pictures/Gold Helmet.jpg" height="300"></td>
    <td><img src="./Pictures/Jaw Painted.jpg" height="300"></td>
  </tr>
</table>

**Testing:**  
After/during the project, how did you make sure items were working as intended? How did you measure success?

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
