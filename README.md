# cpsc319-assignment-3-graphs-solved
**TO GET THIS SOLUTION VISIT:** [CPSC319 Assignment 3-Graphs Solved](https://www.ankitcodinghub.com/product/cpsc319-solved-3/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;116159&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CPSC319 Assignment 3-Graphs Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
GOAL

Graphs are invaluable data structures. You will be given a Java source code that implements Dijkstra’s Shortest Path algorithm and prints the resulting paths. In this assignment, you will write a parser to read a text file to construct an adjacency matrix graph used in the given Java code.

INSTRUCTIONS

Extend the given Java source code “DijkstrasAlgorithm” to perform the following tasks:

1. Request the user for the name of a text file.

Example input text file “ex6”

# ex6.txt #

0 41 0 0 0 29 0 0 51 0 32 0

0 0 0 50 0 0

45 0 0 0 0 38 0 0 32 36 0 0

0 29 0 0 21 0

This ex6.txt file represents an adjacency matrix structuring the graph on the right discussed in class:

2. Write a parser to read the input file and adapt it to the given Java code. Your parser will initialize the adjacency matrix after the input text file given by the user (i.e., yellow highlighted text below)

class Asgmt3 {

public static void main(String[] args) {

int[][] matrix = AdjacencyMatrixParser.parseFile(inputFileName);

DijkstrasAlgorithm.dijkstra(matrix, 0);

}

}

Example of the resulting 6×6 matrix after parsing the input text file inputFileName = “ex6 “

int[][] matrix =

X

3. Write the output of the given Java code to a text file. Note the given Java code displays the output on the screen.

Your program should explicitly write the output to the text file with name “inputFileName_dijkstra_output”

Example of content of output file name “ex6_dijkstra_output”

GIVEN CODES &amp; TEXT FILES

1. Asgmt3.java – You should adapt it to accept the input file name (Step 2)

2. DijkstrasAlgorithm.java – Source code you should modify for the assignment

3. FileIO.java – You should adapt it in your program

4. Four input files representing cities and distances between them (you should process) and corresponding output

(for your reference)

Input Text Files Reference Output Text Files (i.e., your program must match them)

sp11 sp11_dijkstra_output

ha30 ha30_dijkstra_output

wg59 wg59_dijkstra_output

sgb128 sgb128_dijkstra_output

2

Asgmt #3 – Graphs Page 3 of 3

HAND-IN

1. Your code for Asgmt3.java, AdjacencyMatrixParser.java, FileIO.java

2. README (w/ instructions on how to run and use/interact with your program)

3. Please include all of the above items in a zipped folder titled (asgmt3-your LAST NAME-ID).zip and submit it to D2L dropbox.

LATE ASSIGNMENTS WILL NOT BE ACCEPTED – START WORKING IN YOUR ASSIGNMENT EARLY

MARKING

Source code that does not compile or produces run-time errors will receive a grade of 0%.

Item Points

1 Request the user for the name of a text file 1 point

2 Correct output format and content for the 4 given input text files. The corresponding output files are given for your reference.

4 points

Total 5 points

INDIVIDUAL WORK

• The assignment must be done individually, so you must write up the solutions on your own in your own words.

END OF THE ASSIGNMENT

3
