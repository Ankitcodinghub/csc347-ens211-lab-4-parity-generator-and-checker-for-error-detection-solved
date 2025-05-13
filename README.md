# csc347-ens211-lab-4-parity-generator-and-checker-for-error-detection-solved
**TO GET THIS SOLUTION VISIT:** [CSC347-ENS211 Lab 4-Parity Generator and Checker for Error Detection Solved](https://www.ankitcodinghub.com/product/csc347-ens211-lab-4-parity-generator-and-checker-for-error-detection-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;94101&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSC347-ENS211 Lab 4-Parity Generator and Checker for Error Detection Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (1 vote)    </div>
    </div>
<strong>Lab </strong><strong>4 Parity Generator and Checker for Error Detection</strong>

<ol>
<li><strong>Introduction </strong></li>
</ol>
The parity generating and checking technique is widely used in error detection for data transmission. Binary data may be subjected to noise so that such noise can alter 0s to 1s and 1s to 0s. A parity bit is an extra bit added to a binary message in order to make number of 1s either even or odd. The message, including the parity bit, is transmitted and then checked at the receiving end for errors. An error is detected if the checked parity does not correspond with the one transmitted. The circuit that generates the parity bit in the transmitter is called a parity generator. The circuit that checks the parity in the receiver is called a parity checker.

<ol start="2">
<li><strong>Experimental Equipment List</strong>:</li>
</ol>
Two 74<strong>86</strong> (Quad 2-input XOR gate) chips

<ol start="3">
<li><strong>Odd Parity Bit Generator</strong></li>
</ol>
The first circuit to build is a 3-bit odd parity generator. The parity generator circuit will take 3 input bits, x, y, and z, and produce one output bit, P.

<ul>
<li>Obtain the truth table for a 3-bit odd parity generator function P</li>
</ul>
&nbsp;

<table>
<tbody>
<tr>
<td width="78">x y z</td>
<td width="59">P</td>
</tr>
<tr>
<td width="78">0 0 0</td>
<td width="59">1</td>
</tr>
<tr>
<td width="78">0 0 1</td>
<td width="59">0</td>
</tr>
<tr>
<td width="78">0 1 0</td>
<td width="59">0</td>
</tr>
<tr>
<td width="78">0 1 1</td>
<td width="59">1</td>
</tr>
<tr>
<td width="78">1 0 0</td>
<td width="59">0</td>
</tr>
<tr>
<td width="78">1 0 1</td>
<td width="59">1</td>
</tr>
<tr>
<td width="78">1 1 0</td>
<td width="59">1</td>
</tr>
<tr>
<td width="78">1&nbsp; 1&nbsp; 1</td>
<td width="59">0</td>
</tr>
</tbody>
</table>
&nbsp;

<ul>
<li>Derive the Boolean function for P using <strong>XOR operation</strong>.</li>
</ul>
&nbsp;

P = (X⊕Y⊕Z)’

&nbsp;

<ul>
<li>Draw the logic diagram using <strong><u>XOR gates only</u></strong><strong>.</strong></li>
</ul>
&nbsp;

<ul>
<li>Circuit Construction on Tinkercad (<strong>DO NOT tear down</strong> the circuit after you finished this step.)</li>
</ul>
Based on the above diagram, build an odd parity generator using <strong>one 7486 chip only</strong>. <strong>You cannot use inverters.</strong> Use 3 switches to supply all three input logic levels x, y and z, and a LED to provide the parity output.

<ul>
<li>Make a copy of the starter kit from <a href="https://www.tinkercad.com/things/50ODX3g29Cl">https://www.tinkercad.com/things/50ODX3g29Cl</a></li>
</ul>
and rename the copy as “Lab 4 Parity Generator and Checker” on Tinkercad Circuits dashboard.

&nbsp;

<ul>
<li><strong>On the left breadboard</strong>, connect the XOR gates according to the logic diagram obtained in 2(c).</li>
<li>Connect the inputs (x, y, z) to three switches, and the output P to a LED.</li>
<li>Press “Start Simulation”</li>
<li>Apply all eight combinations of logic LOW and HIGH levels to the inputs using the 3 switches and observe the output if the circuit generates parity bits correctly.</li>
</ul>
&nbsp;

https://www.tinkercad.com/things/jJV5FJYsCiz-csc347-lab-4-parity-generator-and-checker-pt-1/editel?sharecode=Ms_NKNwfTDooUBfg90LPjgYQvRVe7xsFgSbC534-AgQ

&nbsp;

<ol start="4">
<li><strong>Odd Parity Bit Checker</strong></li>
</ol>
The parity checker circuit takes 4 input bits, x, y, z, and P, and produce one output error bit E. E = 0 if no error and E = 1 otherwise.

(a) Obtain the truth table for a 4-bit odd parity checker function E

&nbsp;

<table>
<tbody>
<tr>
<td width="78">x y z&nbsp; P</td>
<td width="59">E</td>
</tr>
<tr>
<td width="78">0 0 0 0</td>
<td width="59">1</td>
</tr>
<tr>
<td width="78">0 0 0 1</td>
<td width="59">0</td>
</tr>
<tr>
<td width="78">0 0 1 0</td>
<td width="59">0</td>
</tr>
<tr>
<td width="78">0 0 1 1</td>
<td width="59">1</td>
</tr>
<tr>
<td width="78">0 1 0 0</td>
<td width="59">0</td>
</tr>
<tr>
<td width="78">0 1 0 1</td>
<td width="59">1</td>
</tr>
<tr>
<td width="78">0 1 1 0</td>
<td width="59">1</td>
</tr>
<tr>
<td width="78">0&nbsp; 1&nbsp; 1 1</td>
<td width="59">0</td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td width="78">x y z&nbsp; P</td>
<td width="59">E</td>
</tr>
<tr>
<td width="78">1 0 0 0</td>
<td width="59">0</td>
</tr>
<tr>
<td width="78">1 0 0 1</td>
<td width="59">1</td>
</tr>
<tr>
<td width="78">1 0 1 0</td>
<td width="59">1</td>
</tr>
<tr>
<td width="78">1 0 1 1</td>
<td width="59">0</td>
</tr>
<tr>
<td width="78">1 1 0 0</td>
<td width="59">1</td>
</tr>
<tr>
<td width="78">1 1 0 1</td>
<td width="59">0</td>
</tr>
<tr>
<td width="78">1 1 1 0</td>
<td width="59">0</td>
</tr>
<tr>
<td width="78">1&nbsp; 1&nbsp; 1&nbsp; 1</td>
<td width="59">1</td>
</tr>
</tbody>
</table>
&nbsp;

(b) Derive the Boolean function for E using <strong>XOR operation only</strong>.

E = (X⊕Y⊕Z⊕P)’

&nbsp;

<ul>
<li>Draw the logic diagram <strong><u>using XOR gates only</u></strong>.</li>
</ul>
&nbsp;

&nbsp;

&nbsp;

&nbsp;

<ul>
<li>Circuit construction on Tinkercad (<strong>DO NOT tear down</strong> the circuit after you finished this step.)</li>
</ul>
Build an odd parity checker using <strong>another 7486 XOR chip</strong>. <strong>You cannot use inverters.</strong> Use four switches for x, y, z, P on the right breadboard, and a LED for the error output E.

<ul>
<li><strong>On the right breadboard</strong>, connect the XOR gates according to the logic diagram in 3(c).</li>
<li>Connect the inputs (x, y, z, P) to four switches on the breadboard, and the output E to a LED.</li>
<li>Press “Start Simulation”</li>
<li>Apply all 16 combinations of logic LOW and HIGH levels to the inputs using the 4 switches and observe the output if the parity checker works correctly.</li>
</ul>
<u>&nbsp;</u>

<ul>
<li><u>Take a screenshot of your circuit for submission later.</u></li>
</ul>
https://www.tinkercad.com/things/dAlAftMLTE7-csc347-lab-4-parity-generator-and-checker-pt-2/editel?sharecode=EGSheR_BL9-IiQRMB-ySo7r1bQFPszMMHoO_C0L5A10

&nbsp;

<ol start="5">
<li><strong>Connect your odd parity generator to your parity checker </strong></li>
</ol>
&nbsp;

<ul>
<li><strong>On the right breadboard</strong>, <strong>remove the 4 wires (x, y, z, P) from the switches, and reconnect them to the (x, y, z, P) on the bottom breadboard</strong>.</li>
<li>Apply all 8 combinations of logic LOW and HIGH levels to the inputs using the 3 switches on the left bread board and observe the output E. <strong><u>What is the value of E for each input combination? Why?</u></strong></li>
<li>Turn on the red switch on the bottom breadboard, then apply all 8 combinations of logic LOW and HIGH levels to the inputs using the 3 switches on the left bread board and observe the output E. <strong><u>What is the value of E for each input combination? Why?</u></strong></li>
</ul>
&nbsp;

<ul>
<li><u>Take a screenshot of your circuit for submission later.</u></li>
</ul>
https://www.tinkercad.com/things/60MTD3yI5IC-copy-of-csc347-lab-4-parity-generator-and-checker-pt-2/editel?sharecode=-4wbOZWv2FeAMHPAaWy2YQMNnwO-ZNXo0e5blsQg3ZE

<ol start="5">
<li>Homework: design and build a 4-bit even parity generator and the corresponding 5-bit even parity checker. For the 5-bit checker, you need 5 switches so replace the DIP switch with a larger one.</li>
</ol>
&nbsp;

<strong><u>Submission Instructions:</u></strong>

<u>Lab work submission</u>

<ol>
<li>Copy the link of your final circuit for sharing.</li>
<li>On the Blackboard, click on Lab 4. Attach the 2 screenshots from Steps 4(e) and 5(d) and paste the link from Step 1 into the Comments area, then hit the Submit button.</li>
</ol>
<u>Lab report submission</u>

You do not need to write a lab report for this lab but do the homework and submit the screenshots and link to the Blackboard under Lab 4 report submission. It is due one week after the lab is done.
