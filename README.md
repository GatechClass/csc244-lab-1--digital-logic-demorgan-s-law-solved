# csc244-lab-1--digital-logic-demorgan-s-law-solved
**TO GET THIS SOLUTION VISIT:** [CSC244 Lab 1- Digital Logic & DeMorgan’s Law Solved](https://mantutor.com/product/csc-244-digital-systems-solved/)


---

**For Custom/Order Solutions:** **Email:** mantutorcodes@gmail.com  

*We deliver quick, professional, and affordable assignment help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;113638&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSC244 Lab 1- Digital Logic \u0026amp; DeMorgan’s Law Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
&nbsp;

I. Objectives

A. Investigate rise time and fall time of waveforms measured on an oscilloscope.

B. Learn how to specify, synthesize, download and test circuits on a DE10-Lite FPGA board using Verilog.

C. Build circuits to verify DeMorgan’s theorems.

II. Pre-Lab

It is important to complete the pre-lab work before lab so that you can finish the lab on time. Read this entire lab, and with the following guidelines, determine which portions can be done prior to lab.

Generally, prior to lab you should:

1. Perform any algebraic simplification and circuit design that is required.

2. If a circuit is to be made during lab, arrive with the circuit diagram showing what to build.

3. If any theoretical values are required, calculate and tabulate them prior to lab.

For this lab:

1. Install Quartus as part of your pre-lab work. During this lab, you’ll use Quartus to create circuits that verify DeMorgan’s Theorems, using your DE10-Lite boards. You’ll need to install the Quartus software that we use to create circuits for the boards. Detailed directions are posted in both the Class and Lab D2L shells. Please follow the directions exactly.

A. Rise/Fall Times

During the first part of this lab, you will investigate the rise/fall times of waveforms as they move through digital components.

Take a few minutes to read about rise and fall time for digital circuits on the web this is a good source. https://en.wikipedia.org/wiki/Rise_time. As pre-lab work, answer the following questions.

1. Explain rise time. ___5 pts

2. Explain fall time. ____ 5 pts

B. View the video at the link below, which shows how to measure rise time and fall time with an oscilloscope and use it to answer the questions below: https://www.youtube.com/watch?v=knvscPTVdv4

1. What is the rise time of the waveform in the video and how was it calculated? ___5 pts

2. What is the fall time? ___ 5pts

3. Why do we measure from 10% to 90% instead of from 0% to 100%? ___ 5 pts

III. Lab

C. Most of the labs in this course require you to write Verilog statements to specify circuits, synthesize them, download them into the DE10-Lite board and test them.

In this lab, we’ll create circuits to verify DeMorgan’s Theorems. Circuit diagrams for Part 1 of DeMorgan’s Theorem are shown below.

Figure 1: Part 1 of DeMorgan’s Theorem

1. Construct the circuits shown in Figure 1. Use the pin planner to connect each input to a switch and the outputs to an LEDs. Label your connections in the blanks below ___ 10 pts

A = _____ B = _____ Y =_______ Z=_____

2. Use the switches to obtain each combination in Table 1 below and record the output you observe.

A B Y Z

0 0

0 1

1 0

1 1

Table 1: Truth Table for NOR

4. Now, construct the circuit on the right-hand side of Figure 2(a). Connect each input to a switch and connect the output to an LED. Use the switches to obtain each combination in Table 2 below, and record the output you observe.

A B Y Z

0 0

0 1

1 0

1 1

Figure 2: Part 2 of DeMorgan’s Theorem

Table 2: Truth Table for NAND

IV. Grade

Activity points total

Pre Lab A 10

Pre Lab B 15

NOR 20

NAND 10

Total 55
