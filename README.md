# csci151-homework-4-solved
**TO GET THIS SOLUTION VISIT:** [CSCI151 Homework 4 Solved](https://www.ankitcodinghub.com/product/csci151-homework-4-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;97037&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCI151 Homework 4 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
CSCI 151 Fall 2018 Homework 4

Objectives: in addition to the Objectives of HW3 (i.e., file I/O, function operations and string functions/operations) ,

<ol>
<li>Practice arrays of pointers operations.</li>
<li>Practice linked lists operations with dynamic memory allocation</li>
</ol>
Notes:

What is the Palindrome? What is the substring?

Rules:

This programming assignment will be graded on style and structure as well as correctness. First, the use of goto and global variables are prohibited. Second, you are ONLY ALLOWED to use the standard stdio.h, malloc() and free() in stdlib.h and string.h functions except strstr(). There should be comments and indentation, variables and functionsshouldhavemeaningfulnames,and theprogramshouldhaveaclear,simplestructure.

The programming assignment must be individual work. Do not discuss it with your classmates except understanding of this problem and clarifying your idea/pseudo code. Do not share your solution with anyone, in person or electronically, until the end of the semester. Do not discuss the assignment online, or copy online solutions. If you find some codes online, you MUST cite both the website domain and the source codes, which will be counted as deduction points; in other words it is strictly prohibited to copy some or most of the source codes online. (How to cite will be shown in the end of this file.)

Your program will be run through an automated plagiarism checker. If you are found to have cheated on any single programming assignment, you will receive a 0 on ALL the programming assignments, past and future, so consider this carefully. Late work on this assignment will be accepted, with a penalty of 20% per day.

Write a program that:

Counts each number of lines from the two files (subStrings.txt and iStrings.txt), and then reads lines and saves them to each array of pointers (i.e., two arrays of pointers), after declaring the arrays of pointers using the number of lines; you need to declare a new linked list, which will be written to oString.txt file in the final phase of this program. Your program should then check to see how many non-overlapping occurrences of the three-letter substring occur in that string and test whether the string is a palindrome; then the program should update into the output linked list, which will contain each string of the original data, the number of substring occurrences and palindrome test results on the next like the below output format. After that, the first substring from the substring array of pointers and the output linked list should be written to the output file, oStrings.txt, and then the file writing process should be repeated like the below output example.

Input File is formatted such that each line is a string to be tested. Leading and trailing whitespace for each line must be deleted before processing (i.e., assuming that input files do not have leading and trailing whitespace(s) and blank line(s)). And, we assume that each line of any input or output strings does not exceed 50 characters.

Input Files:

subStrings.txt iStrings.txt

NOTE: Input files should end with a newline, please simply use after downloading the input files, not hard-coding. Output Format is:

Original_data_without_leading_or_trailing_whitespace + “\t” + str(count) + “\t” + is_or_not_Palindrome + “\n” An example: “Astana” + “\t” + “1” + “\t” + “Not_Palindrome” + “\n”

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
NOTE: The output string format MUST be like this because we will use an automatic tool for grading. (It is student’s responsibility not to follow this REALLY crucial rule).

Programming requirements:

You must write the below functions for implementing this assignment, with the following signatures.

NOTE: If the required functions and parameter types are not used, you will have deduction points for each function. (even if the output file is perfectly correct).

You must use the following hard-code file names (not user input(s)): subStrings.txt, iStrings.txt and oStrings.txt NOTE: This requirement is also very important because we will use an automatic tool for grading. (It is student’s responsibility not to follow this REALLY crucial rule).

The input and output files should be opened and checked for validity.

NOTE: This requirement is also very important because we will use an automatic tool for grading. (It is student’s responsibility not to follow this REALLY crucial rule).

NOTE: If you use a Mac or Linux machine, no problem. But, you MUST double check your file and results before your submission on one of Lab Windows machines. (It is student’s responsibility not to follow this REALLY crucial rule).

Please submit only your *.c file on the moodle (one c file). Programming details

You MUST NOT change function names, parameter types, and even parameter names due to the auto-grading (NOTE: please just copy and paste the prototypes for function declaration). In addition to the required functions, parameters and parameter names, it is allowed for you to add your own functions if it is needed.

Assume that the linked list node is given to you, and please check each function step by step from the bottom (i.e., main()). For your information, the functions to be updated are high-lighted with blue color.

typedef struct _Node{ char strData[50];

struct _Node *next; }Node;

<ul>
<li>● &nbsp;Write a function: void writeFile2(char fileName[], char ssData[], Node **oLinkedList);
<ul>
<li>○ &nbsp;Takes in the output file’s name, and the checked substring, output data in the linked list</li>
<li>○ &nbsp;Opens the file</li>
<li>○ &nbsp;Writes the checked substring to the file</li>
<li>○ &nbsp;Writes the data in the output linked list out to the file</li>
<li>○ &nbsp;Closes the file</li>
</ul>
</li>
<li>● &nbsp;Write a function: int isPalindrome(char str[]);
<ul>
<li>○ &nbsp;This function check if the string passed in is a palindrome, from the sample text file below, an
example parameter is isPalendrome(“owlwo”)
</li>
<li>○ &nbsp;Returns True if it is a palindrome</li>
<li>○ &nbsp;Returns False if not ○</li>
</ul>
</li>
<li>● &nbsp;Write a function: char *getPalindrome(char str[]);
<ul>
<li>○ &nbsp;This function calls isPalindrome(txt) to check if the string is palindrome</li>
<li>○ &nbsp;It returns “Is_Palindrome”, when the string is a palindrome</li>
<li>○ &nbsp;Returns “Not_Palindrome”, when the string is not a palindrome</li>
</ul>
</li>
<li>● &nbsp;Write a function: int howManySubstrings(char subStr[], char str[]);

○ NOTE: NOT allowed to use strstr()

○ This function check if how many non-overlapping occurrences of the three-letter substring</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
occur in the string passed in, from the sample text file below, an example parameter is

howManySubstrings(“sta”,“Astana Astana”) ○ Returns the number of occurrences

</div>
</div>
<div class="layoutArea">
<div class="column">
● Write

o Free each node consecutively, after taking the head of the linked list

</div>
</div>
<div class="layoutArea">
<div class="column">
a function: void freeLinkedlist(Node *head);

</div>
</div>
<div class="layoutArea">
<div class="column">
● Write

o Print each node consecutively, after taking the head of the linked list

</div>
</div>
<div class="layoutArea">
<div class="column">
a function: void printLinkedlist(Node *head);

</div>
</div>
<div class="layoutArea">
<div class="column">
● Write

o Create a node

</div>
</div>
<div class="layoutArea">
<div class="column">
a function: void appendNode(Node **oLinkedList, char outputLine[]);

</div>
</div>
<div class="layoutArea">
<div class="column">
o Save the output string line to the node

o Append the node to the output linked list

<ul>
<li>○ &nbsp;For each string line,</li>
<li>○ &nbsp;This function calls howManySubstrings() to check if there are how many substrings in each line</li>
<li>○ &nbsp;This function calls getPalindrome()</li>
<li>○ &nbsp;Write each output line to the oLinkedList linked list using the output format by calling
appendNode() for each line

(i.e., Original_data_without_leading_or_trailing_whitespace + “\t” + str(count) + “\t” +

is_or_not_Palindrome + “\n” )
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
a function: void checkSubstringPalindrome2(char ssData[], char *iStringData[], Node **oLinkedList, int nrIOfileLines);

</div>
</div>
<div class="layoutArea">
<div class="column">
● Write

</div>
</div>
<div class="layoutArea">
<div class="column">
● Write

<ul>
<li>○ &nbsp;Takes in the filename and the array of pointers</li>
<li>○ &nbsp;Opens the file</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
a function: void readFile2(char filename[], char *ArrayPtr[]);

</div>
</div>
<div class="layoutArea">
<div class="column">
Reads and saves the file data to the array of pointers ○ Closes File

</div>
</div>
<div class="layoutArea">
<div class="column">
● Write

○ Takes in the filename

</div>
</div>
<div class="layoutArea">
<div class="column">
a function: int countFileLines(char filename[]);

</div>
</div>
<div class="layoutArea">
<div class="column">
<ul>
<li>○ &nbsp;Opens the file</li>
<li>○ &nbsp;Counts and saves the number of lines</li>
<li>○ &nbsp;Closes File</li>
<li>○ &nbsp;Returns the number</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
● Write

○ Calls the above functions according to your design

Tips for Design and Implementation:

Every function except checkSubstringPalindrome() can be evaluated individually, please divide and conquer step by step as usual.

Sample Output file:

oStrings.txt

If the subStrings.txt and iStrings.txt files are same with the linked files, the sample output file (oStrings.txt) will be like below:

sta The First line MUST be the first line of the output file with the first substring, NOT blank line Astana 1 Not_Palindrome

Astana Astana 2 Not_Palindrome

Astana Astana Astana 3 Not_Palindrome

owlwo 0 Is_Palindrome 111111 0 Is_Palindrome 222 222 0 Is_Palindrome

</div>
</div>
<div class="layoutArea">
<div class="column">
a function main()

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
Almaty 0 Kazakhstan 1 anaana 0 AstanaanatsA anana 0

</div>
<div class="column">
Not_Palindrome Not_Palindrome Is_Palindrome

1 Is_Palindrome Is_Palindrome

</div>
</div>
<div class="layoutArea">
<div class="column">
 This line MUST be a BLANK line between each block (VERY important in automatic grading) ana

</div>
</div>
<div class="layoutArea">
<div class="column">
Astana 1

Astana Astana 2 Not_Palindrome Astana Astana Astana 3 Not_Palindrome

owlwo

111111

222 222

Almaty

Kazakhstan

anaana

AstanaanatsA

anana 1

BLANK

BLANK  By default, there will be two blank lines (one from output format, and the other from the blank between each block) , BUT the two BLANK lines will not be counted in the automatic grading (i.e., Please Never Mind).

How to cite both the website domain and the source codes:

Below the main function, please add the comments and the full domain address with the source codes like the example ( without any white spaces or indentation for http(s)). If you referred many sites, please add consecutively. (You don’t have to add the sites for checking the signatures of C standard library functions).

int main(){

// your codes

return 0; }

/*START_CITE

http://www.domain1.com (or https://xxx)

Referred code 1 (just example)

void myMemCpy(void *dest, void *src, size_t n) {

// Typecast src and dest addresses to (char *) char *csrc = (char *)src;

char *cdest = (char *)dest;

// Copy contents of src[] to dest[] for (int i=0; i&lt;n; i++)

<pre>       cdest[i] = csrc[i];
</pre>
}

https://www.domain2.com Referred code 2 END_CITE*/

</div>
</div>
<div class="layoutArea">
<div class="column">
0 0 0 0 0 2

</div>
<div class="column">
Is_Palindrome Is_Palindrome Is_Palindrome Not_Palindrome Not_Palindrome Is_Palindrome

2 Is_Palindrome Is_Palindrome

</div>
</div>
<div class="layoutArea">
<div class="column">
Not_Palindrome

</div>
</div>
</div>
