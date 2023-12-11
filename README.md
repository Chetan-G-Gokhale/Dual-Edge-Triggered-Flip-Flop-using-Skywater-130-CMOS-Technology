# Dual-Edge-Triggered-Flip-Flop-using-Skywater-130-CMOS-Technology

## Introduction
A Dual Edge-Triggered Flip-Flop (DETFF) is a critical component in digital circuits, especially in memory design. Unlike traditional flip-flops, DETFF responds to both rising and falling edges of a clock signal. In memory applications, DETFFs help optimize data storage and retrieval processes. By capturing input information on both clock transitions, DETFFs enhance memory access speed and efficiency, making them well-suited for high-performance systems like cache memories and RAM. This dual-edge sensitivity allows for faster and more precise handling of data, contributing to improved overall system responsiveness and throughput in memory operations
<br>
<br>

## Reference Circuit

The Circuit samples the input data at both positive and negative edge of the cycle using D flip flops, Then the respective outputs are given to two inputs of a 2:1 Mux with clock as its select line.
<br>
The Negative Flip Flop can be implemented using Postive latch followed by negative latch and viceversa for a positive flop.
<br>
<br>
<p align="center">
  
  <img src="https://github.com/Chetan-G-Gokhale/Dual-Edge-Triggered-Flip-Flop-using-Skywater-130-CMOS-Technology/assets/126239004/89b7b756-e480-4a91-85c7-710b9e1cade4">
</p>
<br>

# D Flip FLop (Pass Transistor Logic)
<p align="center">
  
  <img src="https://github.com/Chetan-G-Gokhale/Dual-Edge-Triggered-Flip-Flop-using-Skywater-130-CMOS-Technology/assets/126239004/479aeba8-87f5-4e21-96b0-3699224de4f4">
</p>
<br>

# 2:1 Mux (Pass Transistor Logic)
<p align="center">
  
  <img src="https://github.com/Chetan-G-Gokhale/Dual-Edge-Triggered-Flip-Flop-using-Skywater-130-CMOS-Technology/assets/126239004/03eca519-42a9-486b-acc5-acb03ac9ecaa">
</p>
<br>

# Top Level Schematic
<p align="center">
  
  <img src="https://github.com/Chetan-G-Gokhale/Dual-Edge-Triggered-Flip-Flop-using-Skywater-130-CMOS-Technology/assets/126239004/cc4117d5-2483-4ade-8e27-387a5d979318">
</p>
<br>

# Final Waveform
<p align="center">
  
  <img src="https://github.com/Chetan-G-Gokhale/Dual-Edge-Triggered-Flip-Flop-using-Skywater-130-CMOS-Technology/assets/126239004/6e3cb243-10ad-47d0-985b-38df1bd9c281">
</p>
<br>

# Reference
* [Dual Edge Triggered Flop Article] : (https://vlsi-soc.blogspot.com/2013/06/dual-edge-triggered-flip-flop.html)





