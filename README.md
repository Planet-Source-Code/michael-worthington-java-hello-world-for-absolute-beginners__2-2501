<div align="center">

## Java \- 'Hello World' for absolute beginners


</div>

### Description

the purpose of this tutorial is to teach beginner java programmers how to make their first program. it is a simple 'Hello World' program that they make, but it covers a lot of basics to writing, compiling, and running a program on your computer.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[michael worthington](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/michael-worthington.md)
**Level**          |Beginner
**User Rating**    |5.0 (10 globes from 2 users)
**Compatibility**  |Java \(JDK 1\.2\)
**Category**       |[Coding Standards](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/coding-standards__2-87.md)
**World**          |[Java](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/java.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/michael-worthington-java-hello-world-for-absolute-beginners__2-2501/archive/master.zip)





### Source Code

<blockquote>
     <p><font face="Verdana, Arial, Helvetica, sans-serif" size="1"><br>
      </font></p>
<hr>
    <p><font face="Verdana, Arial, Helvetica, sans-serif" size="1"><u>INTRO
     TO JAVA - WRITTEN BY: M.WORTHINGTON [12.01.01]</u><br>
     <br>
     ...so you've decided to learn a little java. yes this is java, not java
     srcipt. i'll be making tutorials as often as possible to share my knowledge
     of the programming language and allow you to learn something new.<br>
     ...first let me share my background on the topic. i'm currently a college
     freshman and am studying the language for the first time. i've had experience
     in visual basic, basic, and c++. so while i'm not an expert in java,
     i can still share what i learn each week in class. so basically you'll
     be getting a free college education of java.<br>
     ...if you've ever read and programming book they spend a couple chapters
     explaining computers and how programs methodically work. i'm not going
     to do that. for you to learn from my tutorials you'll have to have some
     basic understanding of the world of programming. even if you don't,
     you should still be able to learn from me.<br>
     ...so here we go<br>
     <br>
     while java is an internet language, you program it and run it right
     on your computer. first, you're going to need the java runtimes on your
     computer. i suggest going to <u><a href="http://java.sun.com">http://java.sun.com</a></u>
     to download JavaTM 2 SDK, Standard Edition, v 1.2.2. follow all of the
     installation instructions, because you will need to edit one line of
     text in your autoexec batch file. the instructions from the program
     should explain what to do. if you are having trouble, hit up the message
     boards for help.<br>
     <br>
     to create your programs, you can use notepad or wordpad (or basically
     any text editor). i use notepad. java is a case sensitive language,
     so you will have to go through the trouble of hitting shift or caps
     lock for making sure all the code is formatted properly.<br>
     <br>
     <u>OBJECTIVE</u> <br>
     in tradition of things, your first java program will be a 'Hello World'
     one. basically, the idea behind this will be to learn how to create
     a program you can compile and run. <br>
     <br>
     <u>PROGRAM</u><br>
     <br>
     public class FirstProgram<br>
     {<br>
     public static void main(String[] args)<br>
     {<br>
     System.out.println(&quot;Hello World&quot;);<br>
     } //main<br>
     } //class</font></p>
    <p><font face="Verdana, Arial, Helvetica, sans-serif" size="1"><u>ABOUT
     THE PROGRAM</u><br>
     we are creating a java class in this program. as well, we are putting
     a main function within it. in this program, the name of our class is
     'FirstProgram'. the brackets { and } begin and end the class as well
     as the main method. in the main method is the line 'System.out.println(&quot;Hello
     World&quot;);' this code is telling the computer to print out on one
     line 'Hello World' (minus the single quotes). what you want to be printed
     is what you want to put between the quotes. the semi-colon ';' ends
     the line of code and goes to the next of code. since the next line of
     code is simply are bracket closing the main method. it goes to the next.
     and then the class is closed. the double slashes '//' are for commenting
     out text. they become vital in complex programs when you want to make
     notes by your code. everything to the right of the slashes on the same
     line does not get compiled and is not code, so write whatever you want.<br>
     <br>
     <br>
     <u>COMPILING &amp; RUNNING</u><br>
     when you save your file, you must type on the .java extension as well
     as put the file in quotes, as seen <u><a href="http://mixednuts.8bit-religion.com/java/saving.gif">here</a></u>.
     the name of the file must be the name of the class. in this case, it
     must be 'FirstProgram' and the .java extension. remember, java is case
     sensitive.</font></p>
    <p><font face="Verdana, Arial, Helvetica, sans-serif" size="1"> to compile
     and test out your programs, you need to use MS-DOS. in case you have
     no idea about DOS commands, there are a few you need to know. use <u><a href="http://mixednuts.8bit-religion.com/java/basics.gif">this
     picture</a></u> to assist yourself. to open MS-DOS, go to START&gt;RUN and
     type 'command'. while in DOS you need to basically, when trying to move
     from folder to folder 'cd' is the command you need. example: 'cd..'
     will move you from C:\Windows to C:\ and 'cd jdk1.2.2' will move you
     from C:\ to C:\jdk1.2.2\. when you are in MS-DOS and at the C:\jdk1.2.2\bin
     (which is the default of where you should be saving your java files
     and compiling them) type 'javac'. do this one time only, just to install
     it. </font></p>
    <p><font face="Verdana, Arial, Helvetica, sans-serif" size="1">now to
     compile your program FirstProgram.java, type 'javac FirstProgram.java'
     and hit enter. if it compiles properly with no errors, you should get
     a new line simply showing the directory you are in. now to run the program
     you need to type 'java FirstProgram' and hit enter. for this particular
     program, you should get the print out 'Hello World' on the next line.
     SUCCESS!</font></p>
    <p><font face="Verdana, Arial, Helvetica, sans-serif" size="1">you've
     made your first java program. congratulations, computer nerd. now, try
     making your program print out other stuff. make it print out multiple
     lines by using the code you already know. </font></p>
    <p><font face="Verdana, Arial, Helvetica, sans-serif" size="1">please
     let me know what you think of this tutorial by going to the <a href="http://mixednuts.8bit-religion.com">message
     boards</a> or the <a href="http://mixednuts.8bit-religion.com">contact page</a> and submitting your comments.</font> </p>
    <hr>
     <p>&nbsp;</p>
    </blockquote>

