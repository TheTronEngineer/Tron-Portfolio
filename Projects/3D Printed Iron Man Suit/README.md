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
* Spray paint a Metalcast red over the whole piece  <br>
Sanding and painting is where I realised that the big layer height left very visible lines after painting. However I couln't sand for too long as my patience and time for the project dwindled. Sanding the print and the primer also gummed up the sandpaper, so that made the process tricker. In the future I would want to look into wet sanding. The Metalcast red spray paint worked differently than most paints. Instead of being opaque, this was more similar to a heavy tint. So this colour needed a metallic base underneath to be shiny. This is why I painted gold everywhere, then taped off the sections to paint the red on top. This process taught me a lot about spray painting, patience and percision, especially as the Metalcast Red was quite runny.
<table>
  <tr>
    <td><img src="./Pictures/Paint Booth.jpg" height="300"></td>
    <td><img src="./Pictures/Paint Used.jpg" height="300"></td>
    <td><img src="./Pictures/Gold Helmet.jpg" height="300"></td>
    <td><img src="./Pictures/Jaw Painted.jpg" height="300"></td>
  </tr>
</table>

Another concurrent task was working on the electronics for the helmet and chestplate. I wanted the helmet to be motorized with servos, as well as have lights to create an 'alive' look and feel. I chose to use an arduino along with some servos as this is what I was familiar with from previous small projects and tinkering. Frankly Built also had a tutorial video outlining how to motorize a helmet along with [3D models](https://www.thingiverse.com/thing:4607836) and code for me to use. As I will explain later, I decided to only have the motors in the helmet and keep the rest of the electronics somewhere else. For lights, I watned the eyes to light up, as well as the centerpiece in the chestplate. For this I used some old LED strips that I could connect to an Arduino pin and to a battery pack.  
The hardest part of this was soldering. As I had not soldered much before, I was learning lots but also struggling. (I would learn later during my speaker project that I needed the heat about twice as hot...). I also decided to have the helmet opening butting embedded in the center piece of the chestplate. Keeping the white disc slightly loose on one side and putting a button underneath it provided me an easily acessable and reliable way to open my helmet. Being able to find the button easily was very important as I could hardly see out of the helmet.
<table>
  <tr>
    <td><img src="./Pictures/Messy Desk.jpg" height="400"></td>
    <td><img src="./Pictures/Helmet Wiring.jpg" height="400"></td>
  </tr>
</table>
Finally came the stage of actually putting the pieces together so they could be worn. This process was very tricky, having to work around the flexibility of my own body. The biggest help was something I learned from Frankly Built, which was having a harness underneath the suit that armour could be attched to. This simply made it easier to attach pieces to my body. For the harness, I ended up using some old ratchet straps from the garage and sewing together a harness.<br>
Before I went for the big pieces, I had to connect smaller pieces like the gloves or the bicep to the sholder piece. For this, hot glue and elastic bands were suprisingly effective. My theory is the layer lines of the prints gave the hot glue plenty of surface area to bond to. The elastic bands were perfect for allowing movement while still keeping pieces together.<br>
Moving to the bigger pieces, I used a combination of elastic bands, buckles, hot glue, and sewing to create attachment points for each piece of armour. Having these firm connections were very helpful in keep the armour in the right place as I wore the suit.<br>
The other items I secured to the harness was the electronics and the battery pack. Having these on my chest gave them a place to go that wouldn't weigh down the helmet. I ran wires for power and signalalong the back of my neck to power the helmet.  
<table>
  <tr>
    <td><img src="./Pictures/Dad Helps Adjust.jpg" height="400"></td>
    <td><img src="./Pictures/School Suited Up.jpg" height="400"></td>
  </tr>
</table>
This suit was quite restrictive with my range of motion, so I needed help putting on the whole suit, specifically the arms. But overall, this is still one of my favorite projects for both its learning and its outcome
<table>
  <tr>
    <td><img src="./Pictures/Dark Pose.jpg" height="400"></td>
    <td><img src="./Pictures/Full Suit Selfie.jpg" height="400"></td>
  </tr>
</table>

**Testing:**  
To ensure each part of this suit was both functional and compatible with other parts, lots of testing throughout the project was required. The following are areas that had to be tested as I went through the project
* Armour fit
    * Each piece of the armour had to fit around my bodily dimensions, but also not bee too big that it looked silly or not cohesive. This required measuring beforehand, but put simply I found success when I could get the piece of armour on
* Electonics and wiring
    * The electronics of the system, although I was using pre-written code, still needed tuning and adjustment. To get the right closing and opening speed, have the motors hold the helmet open, and the lights to turn on at the right time, I had to test many variations of code. Additionally I had to test battery drain as a dead battery means I wouldn't be able to open my helmet to see.
* Functionality of the fit
    * One of the trickyest parts was making sure each armour piece would stay on my body during the day, but also that it would allow me to move enough to perform school tasks for the day. This required me to do lots of walking and moving. When I could adequitely move my arms, legs, or body to be able to walk and go through school is when I knew I had a good enough fit and placement

---

## Reflection

**Achievements and Accomplishments:**  
I was incredibly happy with this project and how it turned out. Not only was it my first main engineering project, but I got many compliments from friends, family and people at school. There were a couple main points that I felt accomplished in:
* Developing my problem-solving and engineering skills
    * I felt like I had truly learned how to adapt and integrate changes to my design when I encountered problems. Since this is an essential part of engineering, really helped me not only with dealing with issues that came up, but also seeing future issues.
* It looked pretty cool
    * And not only did it look pretty cool, it also felt very cool to wear! This new suit was definitely a lot more polished and high quality than my previous cardboard model, and the integrated lights truly brought the suit to life

**Future Improvements:**  
As happy as I was with this suit, throughout the whole project I saw areas I wanted to change or improve on. None of these areas of improvement make me dislike the suit, but it rather turns my attention to future opportunities like this to try something new.
* Armour finish quality
    * One thing that was very obvious, especially after painting, is all the layer lines from the printer as well as the seams between pieces. Although the layer lines did give the suit a 'brushed metal' effect, I would love to improve on this quality in the future. I would want to use a smaller layer height, try a filling primer rather than a sanding primer, and spend more time sanding and getting the armour smooth before painting
* Electronics and its setup
    * The electronics worked ok, but it had some flaws. Pressing the button in  my chestplate was tricky with my gloves, the servo motors were a little finicky and the mask would eventually droop instead of holding open, and most importantly, the power cable from the power bank to me helmet was slightly too short, forcing me into an uncomfortable pose while wearing the suit. These items, along with the wiring in my helmet, could all be improved in many small ways to make it function better. For example, having some sort of mechanism to lock the faceplate in the 'open' position would help with drooping
* Fit and function of the suit
    * One major downside of wearing this suit, was how limiting it was. My arm flexibility was limited at best, I could hardly see through the slits and lights in the helmet, and I could say goodbye to sitting down... This obviously arises when adapting a design to a specific body, but also printing out of PLA. In the future I'd want to find a way to see better out of the helmet, have a wider range of motion, and hopefully have a way to sit down without having to take off the suit.

---

## Author

Aiden Nickel 
Mechatronic Systems Engineer | Western University

[LinkedIn](www.linkedin.com/in/aiden-nickel) | nickelaiden@gmail.com
