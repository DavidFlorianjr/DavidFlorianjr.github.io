---
title: "Top-Down Designed Bike Phone Mount"
excerpt: "A robust, 360-degree rotating bike-mounted phone holder designed using top-down modeling."
header:
  image: assets/img/phone_mount_main.jpeg
  teaser: assets/img/phone_mount_main.jpeg
---

## Introduction to Top-Down Modeling

Top-down modeling is a design methodology where the assembly is defined first and then the individual components within the assembly are worked down to. Top-down modeling is a powerful design approach because it allows the designer to create a framework that dictates the shape, size, and position of every part within the context of the whole instead of building parts in isolation and struggling to ensure proper fitting and compatibility.

<figure style="text-align: center;">
  <img src="/assets/img/top_down_assembly.png" 
       alt="Top-Down Assembly Framework" 
       style="display: block; margin: 0 auto; width: 50%;">
  <figcaption>Figure 1: Top-Down Assembly framework dictating component fit.</figcaption>
</figure>

## Project Overview

The design goal of this project was to design a phone holder that can be mounted to a bike handlebar. In this design project, top-down modeling was utilized and critical as my design had many components and moving parts that would have been difficult to properly fit and size if designed independently.

## Base and Pivot Mechanisms

My design can be mounted to a handlebar of 23-25mm using a screw-based clamping mechanism. I decided to utilize a screw-based clamping mechanism because it ensures that the user can apply adequate friction between the handlebar and clamp to properly secure the phone holder. 

Moving upwards from the clamping mechanism, my design features a rotating pivot that allows the user to manipulate the vertical angle of the phone. The ability to adjust the vertical angle of the phone is convenient as it allows the user to adjust for glare, height, and more. This mechanism is mainly secured using the friction between a screw, supporting components, and a nut. This friction allows for firm control of the angle but also prevents the component holding the phone from falling during rougher rides.

<figure style="display: block; margin: 20px auto; width: 60%; text-align: center;">
  <img src="/assets/img/base_clamp_mechanism.jpg" 
       alt="Base Clamp and Pivot Mechanism" 
       style="width: 100%; height: auto; border-radius: 4px;">
  <figcaption style="margin-top: 8px; font-style: italic; color: #555;">
    Figure 2: Screw-based clamping and vertical rotating pivot mechanism.
  </figcaption>
</figure>

## Phone Support and Detent Mechanism

Moving upward from the base of the phone holder into the main section, the supporting platform for the phone features a lip on the bottom for added support to reduce the load of the horizontal clamps. This platform is designed so that the horizontal clamps do not overlap with the volume buttons, as this can cause issues with accidentally adjusting volume, power, or the ringer button. 

Moving to the back of the support platform are the two most important mechanisms in the design: the detent mechanism and the clamping mechanism. 

* **Phone-Clamping Mechanism:** This is spring-actuated, using a set of screws to clamp a spring to each inner edge to provide the clamping force to hold the phone in place. Additionally, this mechanism features a horizontal bar to act as a rail to keep the mechanism stable. At the end of this horizontal bar is a screw and a nut to provide a horizontal limit. The entire phone-clamping mechanism is designed to fit the base and Pro models of the iPhone 13 lineup and newer. It is also designed with bulky cases in mind. 
* **Detent Mechanism:** This exists to allow the phone to rotate 360 degrees in the horizontal direction. This is convenient for users who may want to utilize their device in landscape mode for consuming content. The detent mechanism features a 7mm ball bearing and a corresponding spring that fits into a pocket where the base attaches to the support platform. This mechanism clicks into place at predetermined slots, creating a smooth but sturdy user experience that is resistant to vibrations.

<figure style="display: block; margin: 30px auto; width: 70%; text-align: center;">
  <img src="/assets/img/detent_clamping.png" 
       alt="Detent and Clamping Mechanisms" 
       style="width: 100%; height: auto; border: 1px solid #eee;">
  <figcaption style="margin-top: 10px; font-weight: bold;">
    Figure 3: Detent and spring-actuated clamping mechanism details.
  </figcaption>
</figure>

## Manufacturing & Rapid Prototyping

My design was filament printed using PLA plastic. This aspect of the design approach was due to the necessities needed for rapid prototyping and multiple iterations. As a result, a lot of the holes for heat-set inserts and screws had to be expanded to account for swelling during the printing process. 

# Interactive Fusion Model
<iframe src="[INSERT_YOUR_AUTODESK_SHARE_LINK_HERE]" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

# GIF of Working Model in Action
<figure style="display: block; margin: 30px auto; width: 80%; text-align: center;">
  <img src="/assets/img/phone_mount_demo.gif" 
       alt="Phone mount model in action" 
       style="width: 100%; height: auto; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
  <figcaption style="margin-top: 12px; font-weight: bold; color: #333;">
    Figure 4: Video of the phone mount model in action.
  </figcaption>
</figure>
