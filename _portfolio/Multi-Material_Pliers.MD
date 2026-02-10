---
title: "Print-in-Place Multi-Material Pliers"
excerpt: "A functional needle-nose plier design exploring the intersection of rigid structural components and flexible elastomeric springs."
header:
  image: /assets/img/Pliers_Header.jpeg
  teaser: /assets/img/Pliers_Header.jpeg
---

# Redefining Mechanical Prints
**Print-in-place** parts are functional multi-component designs that require no post-printing assembly or manipulation. There are many applications in which this style of manufacturing is useful. While in theory this is a very effective way to rapidly manufacture designs without the cost or effort that typically follows 3D printing models, there are limitations that occur from print-in-place models that utilize one material. Even when given ideal conditions these models can be a struggle to produce at a high quality and tend to be rigid/experience issues with their functionality. 

Some examples of Print-in-place designs include:
* **Pliers:** [Print-in-place Pliers](https://www.printables.com/model/1161-phonetablet-stand-flat-fold-print-in-place)
* **Foldable phone stands:** [Foldable Phone Cases](https://www.printables.com/model/1161-phonetablet-stand-flat-fold-print-in-place) 
* **Planetary Gears:** [Planetary Gears](https://www.reddit.com/r/3Dprinting/comments/1m5cwq0/printinplace_planetary_gear/)

## The Solution: Multi-Material Integration
The trick to high-performance print-in-place design is utilizing a flexible element from a second elastomeric material! This is especially useful for projects where compression is essential to the functionality of the design. It should be noted that multi-material printers do exist which allow for printing in place using other materials but that complicates the manufacturing process from a maintenance and cost stand point.  

For ideal sturdiness it makes sense to use rigid materials (PLA, ABS, etc) for parts of the design that involve interacting with objects, or experiencing loads while not warping. It also just makes sense from an ergonomic standpoint. In areas where the actual part is compressing or being manipulated in some way, it makes sense to use a flexible or elastic material like TPU so that the part can actually perform as a flexible component. Combinations of materials like this allow for gaining the best of both worlds. 

---

# Interactive CAD Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH90d2dQT28d5b60281150a9839c181a78af?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

---

# Design & Iterative Process
The goal was to create needle-nose pliers capable of picking up small through-hole resistors, requiring precision and a reliable return spring. While the constraints of the project stated that the  pliers were supposed to be of the needle nose type, I wanted to pursue a design that ensued more complexity mechanically. I heavily considered parallel pliers for their satisfying feeling during use and complex mechanical workings but after further research and experimentation with real parallel pliers vs needle nose pliers I determined that needle nose pliers performed better in the given constraint of being able to pick up through-hole resistors. 

* **Iteration 1:** utilized splines for the handle to create an aesthetic and ergonomic experience while using the pliers. It also attempted to print the entire rigid portion in place using PLA and the spring component would be added separately. The spring component location was inspired by the Stanley 84-096 Needle Nose pliers, and typical multilateral plier designs that use square cutouts of TPU for the flexible portion. The pivoting mechanism of the design was based around the bottom handle being connected to a rod in the center of the pivot point. The second handle sits on top of the bottom handle with a hole for the rod, and the rod flares out on top of it preventing it from sliding off. However, after consulting the project manager it was determined that a design with better detailed dimensional constraints ( a task hard to accomplish with splines) was preferred and so that idea was scratched. 
* **Iteration 2:** Shifted to blockier handles that were well dimensioned but less aesthetic and ergonomic. To account for this fillets were used to try and improve the overall look and feel of the pliers. This set utilized the same idea of printing the entire rigid portion in place and adding the spring component separately. This design ran into issues when it came to printing due to the overhang of the rod failing to print and warping causing structural issues. The spring component also suffered issues and did not compress well enough to properly act as a spring resulting in poor functionality.
* **Final Design:** involved using a cap instead of flaring the pivot rod and also separated the bodies into 3 components to be printed to reduce printing errors and improve quality. The spring was also modified to use less material and a more functional design was chosen. 

---

# Technical Specifications & Print Settings

### **Tool Dimensions**
* **Jaw Type:** Needle Nose
* **Jaw Length:** ~ 26 mm
* **Jaw Capacity:** ~ 37 mm

### **Material Specifications**
* **Primary Body:** PLA (Rigid)
* **Spring Component:** TPU (95A Elastic)

### **Print Configuration**
| Setting | Rigid Components (PLA) | Elastic Spring (TPU) |
|:--- |:--- |:--- |
| **Printer / Nozzle** | Voron_300 / 0.4mm | Voron_300 / 0.6mm |
| **Supports** | None | None |
| **Brim** | 8 Layers (0.5mm) | 8 Layers (0.7mm) |
| **Infill Density** | 20% | 15% |

---

# Gallery & Operation

### Iteration History
![Iteration 1](/assets/img/Plier_Iteration_1.png)  
*Initial spline-based ergonomic concept.*

![Iteration 2](/assets/img/Pliers_Iteration_2.png)  
*Second iteration focusing on dimensional accuracy.*

![Final Iteration](/assets/img/Pliers_Iterations_Final.png)  
*Final multi-material design with optimized TPU spring.*

### Functionality Demonstration
![Pliers Operation](/assets/img/Pliers_Gif.gif)  
*GIF showing the spring-back action and jaw precision.*

---
