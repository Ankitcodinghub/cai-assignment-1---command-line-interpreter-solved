# cai-assignment-1---command-line-interpreter-solved
**TO GET THIS SOLUTION VISIT:** [CAI Assignment 1 – Command Line Interpreter Solved](https://www.ankitcodinghub.com/product/cai-assignment-1-command-line-interpreter-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91962&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CAI Assignment 1 – Command Line Interpreter Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (3 votes)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Assignment 1 – Command Line Interpreter

In this assignment, you will write a Command Line Interpreter (CLI) for your operating system.

Your CLI should allow the user to enter the input through the keyboard. After the user writes the command and presses enter, the string is parsed, and the indicated command executed.

The CLI will keep accepting different commands from the user until the user writes “exit”, then the CLI terminates.

Your program structure and the list of required commands are listed below.

Program Structure:

Your program should contain 2 major classes: Parser &amp; Terminal.

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>class Parser {
   String commandName;
   String[] args;
</pre>
//This method will divide the input into commandName and args //where “input” is the string command entered by the user

public boolean parse(String input){…}

public String getCommandName(){…}

<pre>   public String[] getArgs(){...}
}
</pre>
</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>public class Terminal {
   Parser parser;
</pre>
//Implement each command in a method, for example:

public String pwd(){…}

public void cd(String[] args){…} // …

</div>
</div>
<div class="layoutArea">
<div class="column">
}

</div>
</div>
<div class="layoutArea">
<div class="column">
//This

<pre>public
public
</pre>
</div>
<div class="column">
method will choose the suitable command method to be called

<pre>void chooseCommandAction(){...}
static void main(String[] args){...}
</pre>
</div>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Required Commands: (You will choose only 12 commands to implement)

</div>
</div>
<div class="layoutArea">
<div class="column">
Command Name

echo pwd

</div>
<div class="column">
What You Must Implement

Takes 1 argument and prints it.

Takes no arguments and prints the current path.

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
cd

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Implement all these cases:

1. cdtakesnoargumentsandchangesthecurrentpathtothepath

of your home directory.

2. cd takes 1 argument which is “..” (e.g. cd ..) and changes the current directory to the previous directory.

3. cd takes 1 argument which is either the full path or the relative (short) path and changes the current path to that path.

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
ls ls -r

</div>
<div class="column">
Takes no arguments and lists the contents of the current directory sorted alphabetically.

Takes no arguments and lists the contents of the current directory in reverse order.

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
mkdir

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Takes 1 or more arguments and creates a directory for each argument. Each argument can be:

<ul>
<li>Directory name (in this case the new directory is created in the current directory)</li>
<li>Path (full/short) that ends with a directory name (in this case the new directory is created in the given path)</li>
</ul>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
rmdir

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Implement all these cases:

1. rmdir takes 1 argument which is “*” (e.g. rmdir *) and

removes all the empty directories in the current directory.

2. rmdir takes 1 argument which is either the full path or the relative (short) path and removes the given directory only if it is empty.

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
touch

cp cp -r

</div>
<div class="column">
Takes 1 argument which is either the full path or the relative (short) path that ends with a file name and creates this file.

Takes 2 arguments, both are files and copies the first onto the second.

Takes 2 arguments, both are directories (empty or not) and copies the first directory (with all its content) into the second one.

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
rm Takes 1 argument which is a file name that exists in the current directory and removes this file.

cat Takes 1 argument and prints the file’s content or takes 2 arguments and concatenates the content of the 2 files and prints it.

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
&gt;

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Format: command &gt; FileName

Redirects the output of the first command to be written to a file. If the

file doesn’t exist, it will be created.

If the file exists, its original content will be replaced.

Example:

<pre>echo Hello World &gt; myfile.txt
ls &gt; file
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
&gt;&gt; Like &gt; but appends to the file if it exists. Notes:

<ul>
<li>You must implement the “exit” command which will allow the CLI to terminate.</li>
<li>If the user enters a wrong command or bad parameters (invalid path, file instead of directory in certain commands, etc.), the program should print some error messages without terminating.</li>
<li>You must handle all the mentioned cases in each command.</li>
<li>You can refer to the lab document for further information on the commands.
Assignment Rules:
</li>
</ul>
• Your program should be written in Java.

• You can add more attributes/methods, but you can’t change the given

classes’ structure, or you will lose 1 mark (from 5).

• You can use built-in functions and predefined classes in Java. Do not use “exec” to implement any of these commands or you will lose marks.

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
Sample Input &amp; Output:

—————————————————————————————————- *Files and folders must be manipulated on your OS.

</div>
</div>
</div>
