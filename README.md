# cse-320-computer-project-5-solved
**TO GET THIS SOLUTION VISIT:** [CSE 320   Computer Project #5 Solved](https://www.ankitcodinghub.com/product/cse-320-computer-project-5-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;49289&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE 320 &nbsp; Computer Project #5 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<h1>Assignment Overview</h1>
<strong>&nbsp;</strong>

This assignment develops familiarity with the C programming language, the “gcc” compiler, number systems, and twos complement representation.

&nbsp;

It is worth 40 points (4% of course grade) and must be completed no later than 11:59 PM on Thursday, 10/3.

&nbsp;

<h1>Assignment Deliverables</h1>
&nbsp;

The deliverables for this assignment are the following files:

<strong>&nbsp;</strong>

<strong>proj05.makefile </strong>– the makefile which produces <strong>proj05</strong> <strong>proj05.support.c</strong> – the source code for your library module <strong>proj05.driver.c </strong>– the source code for your driver module

&nbsp;

Be sure to use the specified file names and to submit them for grading via the CSE handin system before the project deadline.

&nbsp;

<h1>Assignment Specifications</h1>
&nbsp;

An input/output library in a programming environment will include a method for converting from internal representation (bit patterns) to external representation (character strings).&nbsp; For example, function “printf” in the C standard library allows the user to display a character string representing the contents of a variable.

&nbsp;

Consider the following example:

&nbsp;

<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; int A = 0x5d;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; // A: 00000000000000000000000001011101 </strong>

<strong>&nbsp;</strong>

<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; printf( “%d”, A ); </strong>

&nbsp;

The declaration places the twos complement representation of the value 5d base 16 into variable “A”

(00000000000000000000000001011101).&nbsp; The call to “printf” places the characters “93” into the output buffer.

&nbsp;

<ol>
<li>You will develop a library module which supports the conversion of signed integer values between twos complement internal representation and external representation. The library module will consist of function “decode” and any additional helper functions which you choose to implement.&nbsp; The interface to the module is:</li>
</ol>
&nbsp;

<strong>int decode( int, const char[], char[] ); </strong>

&nbsp;

The first argument is the value which is to be converted into external representation.

&nbsp;

The second argument specifies the base into which the first argument is to be converted.&nbsp; Valid specifiers are “bin” (binary), “oct” (octal), “dec” (decimal), and “hex” (hexadecimal).

&nbsp;

The third argument is the address of an array where function “decode” will store the external representation of the value as a null-terminated sequence of ASCII characters.&nbsp; If the conversion is successful, that representation will be in the form “+N” or “-N”, where “N” is the sequence of digits representing the value.&nbsp; Otherwise, it will be the empty string.

&nbsp;

Function “decode” will return the integer value 1 if the conversion is successful, and the integer value 0 otherwise.

&nbsp;

<ol start="2">
<li>You will develop a driver module to test your implementation of the library module. The driver module will consist of function “main” and any additional helper functions which you choose to implement.&nbsp; All output will be appropriately labeled.</li>
</ol>
<strong>&nbsp;</strong>

<h1>Assignment Notes</h1>
<strong>&nbsp;</strong>

<ol>
<li>Your library module and your driver module must be in separate source code files.</li>
</ol>
&nbsp;

<ol start="2">
<li>Your source code must be translated by “gcc”, which is a C compiler and accepts C source statements.</li>
</ol>
&nbsp;

<ol start="3">
<li>You must supply a “makefile” (named “proj05.makefile”), and that makefile must produce an executable program named “proj05”.</li>
</ol>
&nbsp;

<ol start="4">
<li>Your driver module may not be written as an interactive program, where the user supplies input in response to prompts. Instead, your test cases will be included in the source code as literal constants.</li>
</ol>
&nbsp;

<ol start="5">
<li>You may not call any C library functions from your library module. That is, you may not call functions such as “printf”, “scanf”, “atoi”, or “isspace” from “decode” or any other function in your library module.</li>
</ol>
&nbsp;

<ol start="6">
<li>Your library module must convert between integers and characters without using any C library functions. The equivalent integer value of a character from the set {‘0’..’9′} representing a decimal digit may be obtained by:</li>
</ol>
&nbsp;

<strong>char ch; int value = ch – ‘0’; </strong>

&nbsp;

The equivalent integer value of a character from the set {‘A’..’F’} representing a hexadecimal digit may be obtained by:

&nbsp;

<strong>char ch; </strong>

<strong>int value = (ch – ‘A’) + 10; </strong>

&nbsp;

A similar strategy can be used for a character from the set {‘a’..’f’} representing a hexadecimal digit.

&nbsp;

<ol start="7">
<li>Consider the following, which shows the character strings produced by a series of successful conversions.</li>
</ol>
&nbsp;

<strong>int A = 127; int B = -6; char C[80]; </strong>

<strong>&nbsp;</strong>

<strong>decode( A, “dec”, &amp;C[0] );&nbsp; ==&gt;&nbsp; C contains “+127” decode( A, “hex”, &amp;C[0] );&nbsp; ==&gt;&nbsp; C contains “+7F” decode( A, “bin”, &amp;C[0] );&nbsp; ==&gt;&nbsp; C contains “+1111111” decode( B, “dec”, &amp;C[0] );&nbsp; ==&gt;&nbsp; C contains “-6” decode( B, “oct”, &amp;C[0] );&nbsp; ==&gt;&nbsp; C contains “-6” decode( B, “bin”, &amp;C[0] );&nbsp; ==&gt;&nbsp; C contains “-110”&nbsp; </strong>

For unsuccessful conversions, the character string should be empty.

&nbsp;
