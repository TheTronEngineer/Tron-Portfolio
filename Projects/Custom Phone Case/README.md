# Wireless Speaker 

*Date: December 2025 - March 2025*

<img src="./Pictures/Case Back.jpg" alt="Phone Case" width="250"/>
---

**Description**<br>
A custom designed and printed phone case for a 'client' (friend). This was a very impulsive project, as I recognized that my friend didn't have a phone case and there offered to design and print him one, however looking back, this project was the fullest representation from client idea to product that I have completed

---

## Project Overview

**Objective:**<br>
The goal of this project was to provide a phone case for my client that both provided adequate protection, but also looked and felt good. This means the case had to be:
* The right thickness
    * Too thick and it wouldn't feel good to hold; too thin and it wouldn't protect the phone
* To have a cool design
    * This 'coolness' factor also could not just be my opinion, but my friends opinion

**Constraints:**<br>
* Phone
    * My client had an IPHone 12, so the designed case should be able to fit and hold on well to this particular model of phone, as well as allow for regular use of the device


**Role/contribution**<br>
* Engineering lead
    * I was responsable for helping with meeting with the client and talking about design style, modelling the phone case, and manufactuing the case

---

## Engineering Process

**Design/Planning:**<br>
After the initial suggestion of this impulsive idea, me and a second friend, (who is in school for industrial design), sat down with my friend (the 'client') to talk about what kind of phone case he would want. The designer and I asked various questions to both understand the type of case the client wanted, (rugged, thin, sharp, modern, ect.), as well as specific design themes or pieces to include. After talking about potential ideas, these were some main takeaways that guided the design:
* The client preferred a rugged, almost millitary, tough, style of phone case
* The thickness of the case was not a specific prefrance, and was ok having the thickness larger
* The case should be durable enough to survive a construction environment, as this is where the client is working
* The client wanted the design to center around a Hebrew character Ben, as it was significant to him ([Read more on the Hebrew character here](https://www.ancient-hebrew.org/definition/son.htm))
* Out of the colours of TPU filament I had, the client preferred a black with blue highlights colour scheme

This gave me and the designer a good direction to head for the case. At this point, the designer took this information and started working on sketches for case designs. Ultimately, the designer came back settled on the following design:
<table>
  <tr>
    <td><img src="./Pictures/Cardboard model Left.jpg" height="250"></td>
    <td><img src="./Pictures/Cardboard model Left.jpg" height="250"></td>
  </tr>
</table>
While the designer was working through potential case designs, I took the time to make a cardboard model of the clients IPhone 12. This was made in case I wanted to test the fit of the case after I had printed it to ensure it was ready and usable for the client. The cardboard model was made by layering thin pieces of cardboard, held together with hot glue. This formed a rigid frame that I was then able to attach buttons and a camera block to. The model was made to be as accurate as possible to ensure the printed case would fit the phone and the model the same.
<table>
  <tr>
    <td><img src="./Pictures/Cardboard model Left.jpg" height="250"></td>
    <td><img src="./Pictures/Cardboard Model Right.jpg" height="250"></td>
    <td><img src="./Pictures/Cardboard Model.jpg" height="250"></td>
  </tr>
</table>

**Building/Iterating:**<br>
After the design was finalised and approved by the client, I moved on to modelling the phone case. Using Fusion 360 I designed the case. Some notable design choices include: 
* Overhangs
    * Many of the overhangs used a chamfer and a really small layer height to avoid bridging and the use of supports
* Colour wrap around
    * With the design, the design on the back is intended on being blue, along with the piece that wraps around the side. Because my printer only has one extruder, I could not do a multi-colour print to match the design. Instead, I designed a seperate piece that was printed flat on the bed that could be inserted and super glued afterward to match the wrap-around effect of the design

This was the final model that I created:
<table>
  <tr>
    <td><img src="./Pictures/Modelled Phone Case.png" height="250"></td>
    <td><img src="./Pictures/WrapAround Missing Piece.png" height="250"></td>
    <td><img src="./Pictures/WrapAround Coloured Piece.png" height="250"></td>
  </tr>
</table>
The case could now move to be printed. As I had designed and printed plenty of cases before, this was a familiar step for me. However, there was one major difference with this design that needed a solution. The design stuck out from the back of the case, leaving large overhangs that couldn't be printed midair. Usually the solution for this would be to enable supports, however printing with TPU, the printed supports would only fuse to the case. To get around this, I increased the distance between the top of the supports and the case, paused the print when it had finished printing the supports, and then cut and placed painters tape over top of the supports. This way the printer would still have a surface to print the overhangs on, but here the painters tape protected the case from fusing to the supports. 
<img src="./Pictures/Case Printing Support Tape.jpg" alt="Phone Case" width="250"/>
This worked really well and gave a pretty clean back surface. This was the result after printing:
<table>
  <tr>
    <td><img src="./Pictures/Case Back.jpg" height="250"></td>
    <td><img src="./Pictures/Case Back Angle.jpg" height="250"></td>
    <td><img src="./Pictures/Case Front Angle.jpg" height="250"></td>
  </tr>
  <tr>
    <td><img src="./Pictures/Case Left.jpg" height="250"></td>
    <td><img src="./Pictures/Case Right.jpg" height="250"></td>
  </tr>
</table>

**Testing:**<br>
Unfortunately I wasn't able to use the cardboard model to test the fit of the case, as the client had come for a visit before I had a chance to test. So this was the ultimate test, to see if both the case fit, and the client enjoyed the look and feel of the case! Thankfully, the case did fit well and held on snugly to the phone. This was also the moment where I realised I forgot to model a charging port... So after a second print, the case was finished and fit well. (The client also mentioned that the case with the charging port covered could be handy to block sawdust and other particles getting into the charging port, so that's a win!)

---

## Reflection

**Achievements and Accomplishments:**<br>
* Expansion of my consulting and full-project skills
    * This was exciting as it was my most complete engineering project. It started with a client need, and their ideas for a project. I then delegated the design to a designer. From there I was responsible for modelling, manufacturing, and overcoming challenges inbetween. I really enjoyed seeing both the impact of my work for my friend, but also enjoyed the full design and prototyping workflow
* Back design
    * If you are familiar with TPU, it is somewhat difficult to deal with, especialy with overhands and parts that need supports. Getting such a clean result while using supports in a TPU print is a big accomplishment for me, and definitely skills that I will use and improve in the future
* General modelling
    * As I have designed a multitude of cases for myself, I have been able to hone lots of skills in creating a good design that will fit and function well. This case included lots of those stratagies, (chamfered overhands, inside tolerances, button and camera bump-out design, ect.), and I was really happy with how they ended up working

**Future Improvements:**<br>
Although I was happy with much of the case, there were still parts I wanted to improve on for the future.

* Button design
    * After printing the design, I realised the thickness of the case made the buttons REALLY stiff and hard to press. My friend didn't mind the extra excersise pressing the buttons, (he's a pretty strong guy), however this definitely made me reconsider my button design, and have since included cutouts to help the button presses happen easier
* Flip-out stand
    * One piece of the design that might seem like it is missing from the final product is the piece at the bottom with the text. This was intended on being a flip-out stand for the phone that would include some text that related to the design. I did work on this part, and intended to use a piece of filament as a hinge, however I ran out of time to finalize and print the design. this is something I would have liked to finish to truly complete the case

---

## Author

Aiden Nickel 
Mechatronic Systems Engineer | Western University

[LinkedIn](www.linkedin.com/in/aiden-nickel) | nickelaiden@gmail.com
