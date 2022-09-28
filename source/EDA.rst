


Basics about EDA
===================

What is EDA
-----------------
Electronic Design Automation, or EDA, is a market segment consisting of software, hardware, and 
services with the collective goal of assisting in the definition, planning, design, implementation, verification, 
and subsequent manufacturing of semiconductor devices, or chips [#]_.

.. raw:: html
   
   <iframe width="560" height="315" src="https://www.youtube.com/embed/iDhpKq09XIo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


Acronyms and Terms
------------------
Below are some explanations about TLAs & OPTs (three letter acroynyms, other pernament things) [#]_.

.. 以下为字段列表

:EDA: Electronic Design Automation 
:CAD: Compute-Aided Design
:HDL: Hardware Descriptive Language
:VHDL: VHSIC (very high speed integraed circuit) Hardware Descriptive Language
:SystemVerilog: Name of another popular HDL
:RTL: Register Transfer Level
:GDSII: Graphical Design Station (or nothing)
:ASIC: Application Specific Integrated Circuit 
:FPGA: Field-Programmable Gate Array
:Platform: Collection of EDA tools
:IP: Intellectural Property
:Semiconductor: partial conductor of electricity
:IC: Integrated Circuit (i.e., a Chip)

.. 以下插入youtube视频，嵌入链接直接从youtube视频下的share选项复制得到

.. raw:: html
   
   <iframe width="560" height="315" src="https://www.youtube.com/embed/aWjry3chYx8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
   

World of Chips -- The Switch and Other Parts
----------------------------
Below are 3 basic elements of a chip [#]_.

* Transistor: It's the switch 
* Resistor: Slows down electricity
* Capacitor: Stores electricity

How a Chip is Made  
----------------------
Below describes the major steps to make a chip [#]_.

1. Grow a giant crystal of sand (silicon).
2. Slice it up into round wafers and polish them.
3. Coat a wafer with a photograpphic chemical taht hardens when exposed to light.
4. Make a stencil for a pattern to embed in the silicon.
5. Shrink the stencil and shine a light through it.
6. Dip the wafer in acid to etch away the soft parts. 
7. Repeat steps 3 - 6 many times, producing layers of patters etched into the wafer.
8. Cut up the wafer into many square chips.
9. Glue the chip into a protective package.
10. Connect the chip to the pins of the package with tiny glod wires.
11. Put the chip on a tester machine and run a test.
12. Throw away the chips that fail the test!
13. Assemble different kinds of chips onto a board.
14. Install the board into phone, computer... 

Types and Functions of Chips
------------------------------

Kinds of Semiconductors
************************* 

* Analog

	* Electrical levels move up & down continuously
	* Mathematical description is computer - calculus and such

* Digital

	* Electrical levels are either ON or OFF
	* Simply switches
	* Mathematical description is easy - count to 1 (logic, Boolean, truth tables)

* FPGAs

	* Field Programmable Gate Arrays
	* Specially made digital semiconductors
	* Design engineer programs the electrical connection at her/his desk - 'mini-manufacturing'

A ``logic gate`` is: an easy way to describe digital semiconductor behavior

e.g. "AND" gate

Design Flow of Chips
----------------------

Step 1 to 3 is: the Design Implementation: logic

Step4 is: Verification

Step 5 to 7 is: Design Implementation: Physical/Design for Manufacturing

1. Spec your chip

	1. Describe what you want your chip to do 
	2. Write a spec -use a language like SystemVerilog or VHDL

2. Generate the gates

	1. Figure out the detailed logic gates
	2. Use a computer program (EDA tool)
	3. Synthesis
	4. Save the logic gates to use in a future design

3. Make the chip testable 

	1. Help the manufacture to find defects on the chip
	2. Add special gates that send information out of the chip

4. Ensure the gates will work
5. Layout your chip
6. Double-check your layout
7. Turn your design into silicon








.. rubric:: Footnodes
.. [#] https://www.youtube.com/watch?v=iDhpKq09XIo
.. [#] https://www.youtube.com/watch?v=aWjry3chYx8&list=PLA18F9B9E9316050E&index=3
.. [#] https://www.youtube.com/watch?v=qcVu-wOTKzY&list=PLA18F9B9E9316050E&index=5
.. [#] https://www.youtube.com/watch?v=sCSTCihe68w&list=PLA18F9B9E9316050E&index=6






