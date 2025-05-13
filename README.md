# compiler-lab-assignment-3--lexical-analysis-lex-flex-solved
**TO GET THIS SOLUTION VISIT:** [Compiler Lab Assignment 3- Lexical Analysis (LEX/Flex) Solved](https://www.ankitcodinghub.com/product/compiler-lab-assignment-3-lexical-analysis-lex-flex-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91882&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Compiler Lab Assignment 3- Lexical Analysis (LEX\/Flex) Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<u>Lab Assignment 3- Lexical Analysis (LEX/Flex)</u>

Installing Flex: sudo apt-get update sudo apt-get install flex

Editor for writing Lex/F1ex program: Use any text editor

How to compile/ execute: Check the lecture notes shared related to LEX/Flex tool.

SECTION 1

Q 1.1 Write a LEX/Flex program that recognizes binary strings containing odd number of O’s.

Q 1.2 [Optional] Write a LEX/Flex program that recognizes binary strings containing odd number of Us and even number of I’s.

Q 1.3 Write a LEX/Flex program that recognizes binary strings whose integer equivalent is divisible by 3.

SECTION 2

<table>
<tbody>
<tr>
<td width="60"></td>
</tr>
<tr>
<td></td>
<td></td>
</tr>
</tbody>
</table>
Q2. We had discussed about the lexical analyzer generator Lex/ Flex. Consider the example grammar for branching statements discussed in the class given below:

stmt -+ if expr then stmt if expr then stmt else stmt

exprterm relop term term termid number

The patterns for the tokens in the language are described below (that we have also considered in the previous assignment):

digit&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [0-9) digits number&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; digits digits)? ( E 1+—1? digits )?

letter letter ( letter I digit

then else

Q 2.1. Write a Lex/Flex program to describe the tokens of the above grammar, and generate a lexical analyzer using the Lex/Flex tool.

Q 2.2. Test the lexical analyzer with some input strings (You should show and explain the output of the lexical analyzer for the considered examples).

SECTION 3

Q 3. Construct a lexical analyzer for the following simple “C” like language using the Lex/Flex tool.

<ol>
<li>Data Type : integer (INT/int), floating point (FLOAT/float)</li>
<li>Condition constructs: if</li>
<li>Loop Constructs: for, while</li>
<li>Input / Output Constructs:
<ol>
<li>read(x) – Read into variable x</li>
<li>print(x) – Write variable x to output</li>
</ol>
</li>
<li>Relational operators, assignment and arithmetic operators</li>
<li>Only function is main(), there is no other function.</li>
</ol>
You may test it using the below example:

Example Input:

<table width="264">
<tbody>
<tr>
<td width="264">main ( )

INT 1=0;

INT sum=0; INT count;

read (count) ; for (1=0; 1&lt;10; i++)

read (x) ; sum+=x; print (sum) ;
</td>
</tr>
</tbody>
</table>
