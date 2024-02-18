# Windows Skinnable Clock
Skinnable Clock for Windows - is one of the demonstration apps for **krpRegions Library**

![image](https://github.com/karpolan/windows-skinnable-clock/assets/1213313/39a7946d-2513-4908-afc0-02f0ba60e193)

[Download Skinnable Clock for Windows](https://github.com/karpolan/windows-skinnable-clock/raw/main/Clock.exe)

## Built with
The code was written for **Borland Delphi** in 1998 and still works :)

## krpRegions Library
**krpRegions Library** was a set of components for **Borland Delphi** and **Borland C++Builder** designed to create **skinnable user interfaces**. 

It was initially distributed by **[KARPOLAN](https://karpolan.com)** from 1998 to 2000 and later by **ABF software, Inc.** from 2000 to 2010.

The library is now considered **outdated**.

## AREA_BY_COLOR algorithm
This algorithm, developed in 1998 by **[KARPOLAN](https://karpolan.com)**, revolves around the use of a **multi-color mask**, be it a bitmap or other graphic, to **designate areas with different colors**. 

The **multi-color mask** is illustrated below:

![image](https://github.com/karpolan/windows-skinnable-clock/assets/1213313/a330b302-c3cb-4177-b907-9f2693001112)

- Each color area on the mask represents a distinct working area.
- The **gray** area typically signifies the application's body.
- **Yellow**, **Aqua**, **Red**, **Fucsia** areas correspond to buttons, and so forth.

The algorithm involves **detecting the color** under the cursor and **triggering events** associated with the **area of that color**. 

Additionally, you can create **a region for each color area**, allowing the identification of **the currently active region** (as implemented in the **krpRegions Library**).

As a result, the user perceives a **non-rectangular window** that aligns with the outer shape defined by the mask:

![image](https://github.com/karpolan/windows-skinnable-clock/assets/1213313/34e59231-e71f-4ea7-b983-6418206479d5)

When the user **clicks a on a specific area**, the algorithm renders **the "active" version** of the skin on the screen:

![image](https://github.com/karpolan/windows-skinnable-clock/assets/1213313/871b395c-5669-4751-8774-c40c9c27f77a)

**Hover** and **disable** states are achieved by incorporating **skin versions** specifically designed for these states. 
