---
layout: page
title: 03 Making the Lab
permalink: /03_MakingTheLab/
---

"Making the Lab" this topic is about Fab Lab and Digital Fabrication. In the lectures, there are a couple of fabricated machines for DIY Biohacking. Also, Waag Fab Lab are introduced, demonstration of 3D modelling by Autodesk Fusion 360. Then, some DIY Biohacking Kit are introduced. Those let me remember some lectures of [Computer-Aided Design](https://vimeo.com/673168884) and [What is Digital Fabrication](https://vimeo.com/670402018) in [Fab Academy](https://fabacademy.org/2022/).

## What I did in this week

Here is the list that Georg gave us the plan of this week assignment.

```
1. Demonstrate some 3D CAD software (at least two).
2. Hands-on Group Work: Design and Make a CleanBox
3. BHA Stirrer
4. PocketPCR Case for 3D Printing
```


### 1. 3D Design Software

I have ever used some 3D CAD software. Usually, I am using Autodesk Fusion 360, and it is very easy to make models. However, recently, Autodesk limited some functions in Free-version, also, I cannot use the educational license because I left the unviersity last year. So, now I am trying to learn some opensorce 3D CAD software such as FreeCAD, OpenSCAD, Blender and so on... 

### Autodesk Fusion 360

I will introduce some of my works by Autodesk Fusion 360

**Simple Core XY Pen Plotter**

This is what I made for learning how to make the machine. Core XY is a simple and powerful mechanical system. 

![](http://fablabkamakura.fabcloud.io/FabAcademy/support-documents/simplecorexy-img/cover.jpg)

I made a 3D model of this machine by Autodesk Fusion 360.

![](http://fablabkamakura.fabcloud.io/FabAcademy/support-documents/simplecorexy-img/fig1-6.png)

The design is uploaded to the Autodesk 360 (Autodesk Cloud storage of 3D model). You can see here.

<iframe src="https://myhub.autodesk360.com/ue2bd73cf/shares/public/SH56a43QTfd62c1cd9680c153d3db3200de1?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

[Here](http://fablabkamakura.fabcloud.io/FabAcademy/support-documents/SimpleCoreXYPenPlotter/) is a documentation page of Simple Core XY Pen Plotter.


**Sensing BEETLE**

Sensing BEETLE is my final project of Fab Academy 2019. 

![](https://fabacademy.org/2019/labs/kamakura/students/tsuchiya-yosuke/presentation.png)

I designed 6-legs linked mechanism and the body frame of the BEETLE robot by Fusion 360.

![](https://fabacademy.org/2019/labs/kamakura/students/tsuchiya-yosuke/projects/img/3DModelofInsectBody.png)

6-linkaged robot mechanism is looks here:

![](https://fabacademy.org/2019/labs/kamakura/students/tsuchiya-yosuke/projects/img/3DModelofMechanicalDesign.png)

Those parts are projected to 2D Design and fabricated by laser-cutter.

![](https://fabacademy.org/2019/labs/kamakura/students/tsuchiya-yosuke/projects/2D-data-insect-sensing-robot-parts.v3.png)


![](https://fabacademy.org/2019/labs/kamakura/students/tsuchiya-yosuke/projects/img/IMG_7878.jpg)

Body frame is looks here:

![](https://fabacademy.org/2019/labs/kamakura/students/tsuchiya-yosuke/projects/img/3DModelofInsectBodyDivided.png)

The parts are exported as STL format, and load it with Flash Print (A 3D Slicer Software for FlashForge 3D Printer). 

![](https://fabacademy.org/2019/labs/kamakura/students/tsuchiya-yosuke/projects/img/3DModelofInsectBody-head-in3Dprinter.png)

Then, printed by Flashforge Dreamer.

![](https://fabacademy.org/2019/labs/kamakura/students/tsuchiya-yosuke/projects/img/IMG_7908.jpg)


The body frame is too big and it cannot print out at once. So, I separated the body into three parts printed separately. 

![](https://fabacademy.org/2019/labs/kamakura/students/tsuchiya-yosuke/projects/img/IMG_7910.jpg)

Finally, here is complete to fabricate (with using lasercutter (subtractive approach) and 3D Printer (additive approach))

![](https://fabacademy.org/2019/labs/kamakura/students/tsuchiya-yosuke/projects/img/IMG_7913.jpg)

Although the project satisfied requirements of Fab Academy Final Project, this project still have not completed in two points. One is the electronics part. It does not install the logging and visualizing mechanism via WiFi or Bluetooth (need to revise the PCB based on ESP32). Another is the design part. The mechanism and body frame of the robot is separated, and the body frame is easy to blow away.... Need to re-design the mechanism and body frame... 

#### FreeCAD

Coming Soon.....

--- 

### 2. Hands-on Group Work: Design and Make a CleanBox

We had a workshop to make a Clean Bench by Cardboard. First, we draw some sketches to make ideas what kinds of functions are installed in Cleaan Box and how to design it. 

![](../images/week03/DSC_6085.jpg)

Because I still haven't understand well the role of the CleanBox, I couldn't imagine functions of it and struggled to design it.... 

![](../images/week03/DSC_6086.jpg)

We cut and build the cardboard with following our sketches.... This is the front view of our Cleanbox. We make a square hole to put hands into. 

![](../images/week03/DSC_6091.jpg)

Finally, finished to make....

![](../images/week03/IMG_0967.jpg)

It have small holes in both side of the Cleanbox for air passage. We can set a hair driyer (for alternate of the fan) to make air. 

![](../images/week03/IMG_0959.jpg)

My Groupmate are good at to make a typography of Kanji by Vinyl Tape. So, she made "風神" (meaning: The God of Wind) on the top of our Cleanbox. 

![](../images/week03/IMG_0958.jpg)

... A Bio Expart in our Lab tried to use our Cleanbox.... Because the square hole for putting hands into our Cleanbox, she looked struggle to do her works inside there.... 

![](../images/week03/DSC_6108.jpg)

Anyway,,, it is complete to make it. In my experience of Fab Academy works, it is important to make moc-up by cardboard to understand what I want to make.... I thought I will learn more what the role of Cleanbox, and what are the role of every machines in Bio Lab....

---

### 3. Fork and Change the BHA Stirrer Repo

I forked [github repository of BHA Stirrer](https://github.com/BioClub/BHA_Stirrer) (DIY Magnetic Stirrer). 

![](../images/week03/pic-3-1.png)

Then, cloned into my PC and open it.

![](../images/week03/pic-3-2.png)

I found the BoM for Japan file, then checking the list....

![](../images/week03/pic-3-3.png)

Most of the parts in BoM could by in Japanese Online Mechanical/Electronics Parts shops, but some parts are missing the link

- 7.5W Power Supply

So, I am looking for where I can buy it.... 

### 4. 3D Printing of Pocket PCR (Preparation)

The meaning of "Preparation" is to make a CAM file (like G-Code) for 3D printing by using a slicer software.

I have my own 3D Printer, Prusa i3 MK3.

![](../images/week03/IMG_0972.jpg)

So, I will make a G-Code for this printer by using Prusa Slicer.

First, download a STL file of Pocket PCR case from [here](https://www.thingiverse.com/thing:4094823). Then, open the STL file with Prusa Slicer.

![](../images/week03/pic-3-4.png)

Rotate the model 90 degree in X-Axis.

![](../images/week03/pic-3-5.png)

Make slice the model, then we can see the preview of sliced model.

![](../images/week03/pic-3-6.png)

From to the preview, we can see it takes about 1 hour and 43 minutes for printing.

![](../images/week03/pic-3-7.png)

Then, Push "Export G-Code" on the Right Bottom side of the Slicer.

[Here](../files/PocketPCR_Case_0.15mm_PLA_MK3S_1h42m.gcode) is the G-Code file that exported.


