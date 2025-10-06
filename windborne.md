---
layout: default
title: windborne
---

# Windborne Application!

Hi, Windborne! My name is Drew Cohen, and this is my job application for Firmware Wizard. I know this isn't a PDF, but hopefully it works as my submission url. Feels like something you guys would appreciate.

### 1. A cool thing I've built – MIDI Air Hockey

<img src="{{ '/assets/images/midi-table.JPG' | relative_url }}" 
     style="float:left; width:300px; height:300px; margin:0 1rem 1.5rem 1rem;" 
     alt="MIDI Table" />

<br/>

The most experience I have both designing PCBs and writing firmware is for music projects. MIDI Air Hockey was part of a challenge in the Tufts Music Dept. to turn a competitive game into a MIDI controller. Using an Arduino Mega, nRF52840 BLE chip, MIDI breakout adapter, and a ton of sensors, a MechE friend and I created a fully-functioning air hockey table from scratch. Particularly difficult/unusual: integrating intense mechanical requirements (airtight, physical gameplay) with precise sensing and creative data generation.

<br/><br/>

### 2. Niche microcontroller feature

I have a relatively deep background in FPGAs for a recent graduate. I've worked with the soft-core Nios processor which essentially operated as an MCU with programmable logic as needed – extremely cool. I have also heard of vice versa, hard processors with small Programmable Logic Units that can implement state machines and RTL at super high frequencies (less useful for music, but interesting for real time processing!)

### 3. Sketchy firmware fix

Another music project (on this website's 'projects', the Drum Hero game). I was running out of time and Godot, the game engine, was refusing to read pins on the raspberryPi via console commands. I just needed to get a demo working. My fix was to host Godot on my laptop, send all information serially to a keylistener that would type different letters as input. Godot reads key input easily, so it worked for the demo.

### 4. Randomly resetting PCB?!

In my experience, random resets are usually physical connectivity/power integrity related. So I would check if power cord is loose, if the soldering on supply rails or even decoupling capacitors looks good. Then I could check the MCU status registers which likely contain reset flags, confirming it's actually a reset (at this point, set up both a power and status register log to check for consistency w/ resets). From there, firmware issues, I'd check areas where state is changing and memory is accessed because it's unlikely to find faults anywhere else.

### 5. Why I am particularly awesome

I am a very solid EE graduate on embedded design and firmware, but my true specialty lies in my diversity of thought and experimentation. I genuinely enjoy and am most experienced in the lab, forming and destroying brief hypotheses drawn from optics, acoustics, or classic literature. The team and the work at Windborne seem best fit to those who can quickly learn new science, from material physics to meteorology. I am very young—honestly, I would need some mentorship to singlehandedly own the entirety of your libraries, drivers, and custom RTOS. But I would get there, and beyond. I would love to chat further about the work at Windborne.