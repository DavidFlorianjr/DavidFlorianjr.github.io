---
title: "Print-in-Place Multi-Material Pliers"
excerpt: "A functional needle-nose plier design exploring the intersection of rigid structural components and flexible elastomeric springs."
header:
  image: assets/img/Pliers_Header.jpeg
  teaser: assets/img/Pliers_Header.jpeg
---

# Redefining Mechanical Prints
**Print-in-place** parts are functional multi-component designs that require no post-printing assembly or manipulation to fulfill their requirements. By printing internal hinges or interlocking joints simultaneously, you can pull a fully moving machine straight off the build plate.

Common applications for this technique include:
* **Tools:** Like these [Print-in-place Pliers](https://www.printables.com/model/1161-phonetablet-stand-flat-fold-print-in-place).
* **Consumer Goods:** Such as [Foldable Phone Cases](https://www.printables.com/model/1161-phonetablet-stand-flat-fold-print-in-place) and [Spring-Loaded Boxes](https://www.instructables.com/Print-in-Place-Spring-Loaded-Box/).
* **Complex Kinematics:** High-precision [Planetary Gears](https://www.reddit.com/r/3Dprinting/comments/1m5cwq0/printinplace_planetary_gear/) used in robotics.

## The Solution: Multi-Material Integration
The secret to high-performance print-in-place design is **designing parts with a flexible element from a second elastomeric material.** This allows the part to perform as a true kinetic object with reliable "snap-back" action.

---

# Interactive CAD Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH90d2dQT28d5b60281150a9839c181a78af?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true" frameborder="0"></iframe>

---

# Design & Iterative Process
The goal was to create a pair of needle-nose pliers capable of picking up small through-hole resistors, a task requiring both precision and a reliable return spring.

### Early Concepts & Failure
My initial design utilized organic splines for a high-end aesthetic. However, I attempted to print the entire rigid portion in one go with a separate spring insert. The pivoting mechanism relied on a flared rod, but the overhangs failed to print correctly.

### Iteration 2: Refined Geometry
The next version shifted to "blockier" handles for better dimensional control. While easier to measure, the rod overhangs still warped. More importantly, the spring geometry was too thick, failing to compress sufficiently.

### The Final Evolution
The final design moved to a **three-component assembly**. The TPU spring was redesigned with a thinner profile to reduce material resistance, ensuring the pliers pop open effortlessly.

---

# Technical Specifications
| Feature | Specification |
|:--- |:--- |
| **Jaw Type** | Needle Nose |
| **Jaw Length** | ~ 26 mm |
| **Jaw Capacity** | ~ 37 mm |
| **Primary Material** | PLA (Rigid) |
| **Spring Material** | TPU (95A Elastic) |

---

# Print Settings
| Setting | Rigid Components (PLA) | Elastic Spring (TPU) |
|:--- |:--- |:--- |
| **Printer / Nozzle** | Voron_300 / 0.4mm | Voron_300 / 0.6mm |
| **Infill Density** | 20% | 15% |

---

# Gallery & Operation

### Iteration History
![Iteration 1](assets/img/Pliers_Iteration_1.png)
*Initial spline-based ergonomic concept.*

![Iteration 2](assets/img/Pliers_Iteration_2.png)
*Second iteration focusing on dimensional accuracy.*

![Final Iteration](assets/img/Pliers_Iteration_Final.png)
*Final multi-material design with optimized TPU spring.*

### Functionality Demonstration
![Pliers Operation](assets/img/Pliers_Gif.gif)
*GIF showing the spring-back action and jaw precision.*

---
