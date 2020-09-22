<div align="center">

## Java Native Interface by Example


</div>

### Description

Its an intro to the Java Native Interface using which you can incorporate native (C/C++ or even Assembly) code into your java programs.(Now in HTML format!!)
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Ali Ezad Abbas](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/ali-ezad-abbas.md)
**Level**          |Advanced
**User Rating**    |4.3 (108 globes from 25 users)
**Compatibility**  |Java \(JDK 1\.1\), Java \(JDK 1\.2\)
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__2-57.md)
**World**          |[Java](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/java.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/ali-ezad-abbas-java-native-interface-by-example__2-3067/archive/master.zip)





### Source Code

```
<html xmlns:o="urn:schemas-microsoft-com:office:office"
xmlns:w="urn:schemas-microsoft-com:office:word"
xmlns="http://www.w3.org/TR/REC-html40">
<head>
<meta http-equiv=Content-Type content="text/html; charset=windows-1252">
<meta name=ProgId content=Word.Document>
<meta name=Generator content="Microsoft Word 9">
<meta name=Originator content="Microsoft Word 9">
<link rel=File-List href="./Java%20Native%20Interface_files/filelist.xml">
<title>Java Native Interface</title>
<!--[if gte mso 9]><xml>
 <o:DocumentProperties>
 <o:Author>Ali Ezad Abbas</o:Author>
 <o:Template>Normal</o:Template>
 <o:LastAuthor>Ali Ezad Abbas</o:LastAuthor>
 <o:Revision>2</o:Revision>
 <o:TotalTime>123</o:TotalTime>
 <o:Created>2002-07-23T17:15:00Z</o:Created>
 <o:LastSaved>2002-07-23T17:15:00Z</o:LastSaved>
 <o:Pages>2</o:Pages>
 <o:Words>1442</o:Words>
 <o:Characters>8224</o:Characters>
 <o:Company>Macrosoft inc.</o:Company>
 <o:Lines>68</o:Lines>
 <o:Paragraphs>16</o:Paragraphs>
 <o:CharactersWithSpaces>10099</o:CharactersWithSpaces>
 <o:Version>9.2720</o:Version>
 </o:DocumentProperties>
</xml><![endif]-->
<style>
<!--
 /* Style Definitions */
p.MsoNormal, li.MsoNormal, div.MsoNormal
	{mso-style-parent:"";
	margin:0in;
	margin-bottom:.0001pt;
	mso-pagination:widow-orphan;
	font-size:12.0pt;
	font-family:"Times New Roman";
	mso-fareast-font-family:"Times New Roman";}
p.MsoBodyText, li.MsoBodyText, div.MsoBodyText
	{margin:0in;
	margin-bottom:.0001pt;
	text-align:justify;
	mso-pagination:widow-orphan;
	font-size:12.0pt;
	font-family:"Times New Roman";
	mso-fareast-font-family:"Times New Roman";}
a:link, span.MsoHyperlink
	{color:#000099;
	text-decoration:underline;
	text-underline:single;}
a:visited, span.MsoHyperlinkFollowed
	{color:purple;
	text-decoration:underline;
	text-underline:single;}
p
	{margin-right:0in;
	mso-margin-top-alt:auto;
	mso-margin-bottom-alt:auto;
	margin-left:0in;
	mso-pagination:widow-orphan;
	font-size:12.0pt;
	font-family:"Times New Roman";
	mso-fareast-font-family:"Times New Roman";}
code
	{mso-ascii-font-family:"Courier New";
	mso-fareast-font-family:"Courier New";
	mso-hansi-font-family:"Courier New";
	mso-bidi-font-family:"Courier New";}
@page Section1
	{size:595.45pt 841.7pt;
	margin:1.0in 1.25in 1.0in 1.25in;
	mso-header-margin:.5in;
	mso-footer-margin:.5in;
	mso-paper-source:0;}
div.Section1
	{page:Section1;}
 /* List Definitions */
@list l0
	{mso-list-id:307057491;
	mso-list-type:hybrid;
	mso-list-template-ids:-884322552 916905068 -750647930 654108556 1682718992 -1734603422 -1487229514 -917614898 -1293501410 1413222758;}
@list l0:level1
	{mso-level-tab-stop:.5in;
	mso-level-number-position:left;
	text-indent:-.25in;}
@list l1
	{mso-list-id:1711148618;
	mso-list-type:hybrid;
	mso-list-template-ids:-1042115708 -1049741472 -1204008484 -4816754 1155814666 -544278002 2011494398 1884293282 -1620509660 -1214101006;}
@list l1:level1
	{mso-level-tab-stop:.5in;
	mso-level-number-position:left;
	text-indent:-.25in;}
ol
	{margin-bottom:0in;}
ul
	{margin-bottom:0in;}
-->
</style>
</head>
<body lang=EN-US link="#000099" vlink=purple style='tab-interval:.5in'>
<div class=Section1>
<p class=MsoNormal style='text-align:justify'>Java Native Interface</p>
<p class=MsoNormal style='text-align:justify'><![if !supportEmptyParas]> <![endif]><o:p></o:p></p>
<p class=MsoNormal style='text-align:justify'>Java is a powerful object
oriented programming language. The real power of Java lies in its portability.
Java programs created on one platform can be run equally well on another
platform as long as a Java Virtual Machine (JVM) implementation is available
for that perticular platform. Java API (Application Programming Interface) is
another of Java’s strong points. The Java API provides most of the
functionality that a developer needs, however, there are situations where the
API can’t cater to the programmer’s needs. Java designers foresaw this problem
and provided an elegant workaround for such situations. The solution they
proposed was the Java Native Interface, commonly known as JNI.</p>
<p class=MsoNormal style='text-align:justify'><![if !supportEmptyParas]> <![endif]><o:p></o:p></p>
<p class=MsoNormal style='text-align:justify'>JNI is sort of a bridge between
the Java programming language and the native environment for which the JVM is
implemented. Simply stated, you can incorporate native code (written in C/C++
or even assembly language) into your Java programs thus enhancing the
capabilities of Java. The question arises here, why do we need to incorporate
native code in Java programs at all?? Well, there are lots of reasons for this!
For example, in Java you can’t reference memory locations directly as you can
do in C or C++ (with pointers). Pointers are to the programming community, what
“friction” is to the mechanical engineers. You hate to have it, but you can’t
do without it!! It is impossible to write drivers for various hardware
interfaces without performing direct memory references. For example, the
printer port of a PC is usually mapped to the memory location 378
(hexadecimal). If you want to do anything with your printer port you need to
reference the memory location 0x378!! Similarly, character display memory in a
PC is mapped to the memory starting at 0xB80 (0xB00 for monochrome displays).</p>
<p class=MsoNormal style='text-align:justify'><![if !supportEmptyParas]> <![endif]><o:p></o:p></p>
<p class=MsoNormal style='text-align:justify'>Referencing memory is not the
only situation where Java fails to provide support. There can be hundreds of
other situations where a Java programmer would be stuck if he didn’t have JNI
at his disposal. The standard Java API, for example, doesn’t provide any
password input stream for console applications (where you type in something and
only asterisks ‘*’ are echoed to the console).</p>
<p class=MsoNormal style='text-align:justify'><![if !supportEmptyParas]> <![endif]><o:p></o:p></p>
<p class=MsoBodyText>Writing native methods for the Java Program involves the
following steps:</p>
<ol start=1 type=1>
 <li class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
 text-align:justify;mso-list:l1 level1 lfo1;tab-stops:list .5in'>Create a
 Java class that declares the native method; this class contains the
 declaration or signature for the native method. </li>
 <li class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
 text-align:justify;mso-list:l1 level1 lfo1;tab-stops:list .5in'>Compile
 the Java class that declares the native method. </li>
 <li class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
 text-align:justify;mso-list:l1 level1 lfo1;tab-stops:list .5in'>Generate a
 header file for the native method using the “javah” program provided with
 the Java SDK.</li>
 <li class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
 text-align:justify;mso-list:l1 level1 lfo1;tab-stops:list .5in'>Write the
 implementation of the native method in the programming language of your
 choice, such as C, C++ or even assembly language. </li>
 <li class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
 text-align:justify;mso-list:l1 level1 lfo1;tab-stops:list .5in'>Compile
 the header and implementation files into a shared library file (dll in
 case of the windows platform). </li>
 <li class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
 text-align:justify;mso-list:l1 level1 lfo1;tab-stops:list .5in'>Run the
 Java program.</li>
</ol>
<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
text-align:justify'><![if !supportEmptyParas]> <![endif]><o:p></o:p></p>
<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
text-align:justify'><![if !supportEmptyParas]> <![endif]><o:p></o:p></p>
<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
text-align:justify'><![if !supportEmptyParas]> <![endif]><o:p></o:p></p>
<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
text-align:justify'>Lets follow these steps and create a simple program to
demonstrate the usage of Java Native Interface. The program we will create will
provide us with a Password Input Stream to read private information from the
console.</p>
<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
text-align:justify'>STEP 1: Write the Java Program:</p>
<p class=MsoNormal style='mso-margin-top-alt:auto;mso-margin-bottom-alt:auto;
text-align:justify'>The Java program in this case is quite simple. It defines
two methods. It defines a native method readChar() and implements a method
readLine() that in turn calls the native method. The program is listed below:</p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><span style='font-size:10.0pt;font-family:"Courier New"'>public
class PasswordInputStream {<o:p></o:p></span></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><span style='font-size:10.0pt;font-family:"Courier New"'><span
style="mso-spacerun: yes">   </span>static {<o:p></o:p></span></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><span style='font-size:10.0pt;font-family:"Courier New"'><span
style="mso-spacerun: yes">     
</span>System.loadLibrary("password");<o:p></o:p></span></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><span style='font-size:10.0pt;font-family:"Courier New"'><span
style="mso-spacerun: yes">   </span>}<o:p></o:p></span></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><span style='font-size:10.0pt;font-family:"Courier New"'><span
style="mso-spacerun: yes">   </span>public String readLine () {<o:p></o:p></span></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><span style='font-size:10.0pt;font-family:"Courier New"'><span
style="mso-spacerun: yes">      </span>String s = "";<o:p></o:p></span></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><span style='font-size:10.0pt;font-family:"Courier New"'><span
style="mso-spacerun: yes">      </span>int input = readChar();<o:p></o:p></span></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><span style='font-size:10.0pt;font-family:"Courier New"'><span
style="mso-spacerun: yes">      </span>while (input!=13) {<o:p></o:p></span></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><span style='font-size:10.0pt;font-family:"Courier New"'><span
style="mso-spacerun: yes">         </span>s = s + (char)input;<o:p></o:p></span></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><span style='font-size:10.0pt;font-family:"Courier New"'><span
style="mso-spacerun: yes">         </span>input = readChar();<o:p></o:p></span></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><span style='font-size:10.0pt;font-family:"Courier New"'><span
style="mso-spacerun: yes">      </span>}<o:p></o:p></span></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><span style='font-size:10.0pt;font-family:"Courier New"'><span
style="mso-spacerun: yes">      </span>System.out.println();<o:p></o:p></span></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><span style='font-size:10.0pt;font-family:"Courier New"'><span
style="mso-spacerun: yes"> </span><span style="mso-spacerun: yes">    
</span>return s;<o:p></o:p></span></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><span style='font-size:10.0pt;font-family:"Courier New"'><span
style="mso-spacerun: yes">   </span>}<o:p></o:p></span></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><span style='font-size:10.0pt;font-family:"Courier New"'><span
style="mso-spacerun: yes">   </span>public native int readChar ();<o:p></o:p></span></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><span style='font-size:10.0pt;font-family:"Courier New"'>}<o:p></o:p></span></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><span style='font-size:10.0pt;font-family:"Courier New"'><![if !supportEmptyParas]> <![endif]><o:p></o:p></span></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><span style='mso-bidi-font-size:10.0pt'>The “loadLibrary”
method in the System class loads the Dynamically Linked Library (dll)
associated with this program. We’ll talk about these in a moment. The static
construct will be new to a lot of people. Well just think of it as a
substitution to the main method. Since there is no main method in this simple
program (we wish to use it as a utility class), so we’re using the “static”
construct.<o:p></o:p></span></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><![if !supportEmptyParas]> <![endif]><o:p></o:p></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'>The readLine() method reads chararacters from the console
using the native method readChar() and concatenates them into a string (by the
way, 13 is the ascii code for the return key in decimal).</p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><![if !supportEmptyParas]> <![endif]><o:p></o:p></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'>The last line of the program provides the signature of the
readChar method. The keyword “native” indicates that the method will be
implemented in a native language and is thus not implemented in the program.</p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><![if !supportEmptyParas]> <![endif]><o:p></o:p></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'>STEP 2: Compile the program:</p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><![if !supportEmptyParas]> <![endif]><o:p></o:p></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'>Now that you’ve created the program, you need to compile
it in the usual manner. Use the “javac” compiler to compile it.</p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><![if !supportEmptyParas]> <![endif]><o:p></o:p></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'>STEP 3: Generate a header file:</p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><![if !supportEmptyParas]> <![endif]><o:p></o:p></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'>The next step is to generate a header file for the native
language. Header files can be thought of as interfaces with respect to Java.
These provide the native method prototypes and define various macros and
variables for the JNI. Our header file provides the C language signature for
the readChar() method.</p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><![if !supportEmptyParas]> <![endif]><o:p></o:p></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'>You can write your own header file, but you’ll need to be
familiar with C/C++ to do that. JDK solves this problem with the “javah”
program. It automatically generates a header file for you. Run it by using the
command “javah PasswordInputStream” and it will create the file
“PasswordInputStream.h”. The file is listed below:</p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><![if !supportEmptyParas]> <![endif]><o:p></o:p></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><span style='font-size:10.0pt;font-family:"Courier New"'>/*
DO NOT EDIT THIS FILE - it is machine generated */<o:p></o:p></span></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><span style='font-size:10.0pt;font-family:"Courier New"'>#include
<jni.h><o:p></o:p></span></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><span style='font-size:10.0pt;font-family:"Courier New"'>/*
Header for class PasswordInputStream */<o:p></o:p></span></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><span style='font-size:10.0pt;font-family:"Courier New"'><![if !supportEmptyParas]> <![endif]><o:p></o:p></span></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><span style='font-size:10.0pt;font-family:"Courier New"'>#ifndef
_Included_PasswordInputStream<o:p></o:p></span></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><span style='font-size:10.0pt;font-family:"Courier New"'>#define
_Included_PasswordInputStream<o:p></o:p></span></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><span style='font-size:10.0pt;font-family:"Courier New"'>#ifdef
__cplusplus<o:p></o:p></span></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><span style='font-size:10.0pt;font-family:"Courier New"'>extern
"C" {<o:p></o:p></span></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><span style='font-size:10.0pt;font-family:"Courier New"'>#endif<o:p></o:p></span></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><span style='font-size:10.0pt;font-family:"Courier New"'>/*<o:p></o:p></span></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><span style='font-size:10.0pt;font-family:"Courier New"'><span
style="mso-spacerun: yes"> </span>* Class:<span style="mso-spacerun: yes">    
</span>PasswordInputStream<o:p></o:p></span></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><span style='font-size:10.0pt;font-family:"Courier New"'><span
style="mso-spacerun: yes"> </span>* Method:<span style="mso-spacerun: yes">   
</span>readChar<o:p></o:p></span></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><span style='font-size:10.0pt;font-family:"Courier New"'><span
style="mso-spacerun: yes"> </span>* Signature: ()I<o:p></o:p></span></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><span style='font-size:10.0pt;font-family:"Courier New"'><span
style="mso-spacerun: yes"> </span>*/<o:p></o:p></span></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><span style='font-size:10.0pt;font-family:"Courier New"'>JNIEXPORT
jint JNICALL Java_PasswordInputStream_readChar<o:p></o:p></span></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><span style='font-size:10.0pt;font-family:"Courier New"'><span
style="mso-spacerun: yes">  </span>(JNIEnv *, jobject);<o:p></o:p></span></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><span style='font-size:10.0pt;font-family:"Courier New"'><![if !supportEmptyParas]> <![endif]><o:p></o:p></span></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><span style='font-size:10.0pt;font-family:"Courier New"'>#ifdef
__cplusplus<o:p></o:p></span></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><span style='font-size:10.0pt;font-family:"Courier New"'>}<o:p></o:p></span></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><span style='font-size:10.0pt;font-family:"Courier New"'>#endif<o:p></o:p></span></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><span style='font-size:10.0pt;font-family:"Courier New"'>#endif<o:p></o:p></span></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><span style='font-size:10.0pt;font-family:"Courier New"'><![if !supportEmptyParas]> <![endif]><o:p></o:p></span></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'>You don’t need to know too much about this file. Contrast
the Java method declaration: </p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><![if !supportEmptyParas]> <![endif]><o:p></o:p></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><span style='font-size:10.0pt;font-family:"Courier New"'><span
style="mso-spacerun: yes">   </span>public native int readChar ();<o:p></o:p></span></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><![if !supportEmptyParas]> <![endif]><o:p></o:p></p>
<p class=MsoNormal style='text-align:justify'>with the native signature:</p>
<p class=MsoNormal style='text-align:justify'><![if !supportEmptyParas]> <![endif]><o:p></o:p></p>
<p class=MsoNormal style='margin-left:.25in;text-align:justify;mso-layout-grid-align:
none;text-autospace:none'><span style='font-size:10.0pt;font-family:"Courier New"'>JNIEXPORT
jint JNICALL Java_PasswordInputStream_readChar<span style="mso-spacerun:
yes">     </span>(JNIEnv *, jobject);<o:p></o:p></span></p>
<p class=MsoNormal style='margin-left:.25in;text-align:justify;mso-layout-grid-align:
none;text-autospace:none'><span style='font-size:10.0pt;font-family:"Courier New"'><![if !supportEmptyParas]> <![endif]><o:p></o:p></span></p>
<p style='text-align:justify'><span style='mso-bidi-font-size:10.0pt'>You can
see that the “int” data type is mapped to the “jint” data type in the native
signature.</span> The name of the native language function that implements the
native method consists of the prefix <code><span style='font-size:10.0pt;
font-family:"Courier New"'>Java_</span></code>, the package name, the class
name, and the name of the native method. Between each name component is an
underscore "_" separator. </p>
<p style='text-align:justify'>Notice that the implementation of the native
function, as it appears in the header file, accepts two parameters even though,
in its definition on the Java side, it accepts no parameters. The JNI requires
every native method to have these two parameters. </p>
<p style='text-align:justify'>STEP 4: Write the native implementation:</p>
<p style='text-align:justify'>We are now ready to implement the readChar()
method in the native language (C in this case). The choice of the native
language is solely a choice of the developer, however, the language must have a
compiler, linker with the ability to create shared libraries (DLLs in case of
windows platform).</p>
<p style='text-align:justify'>The C code is given below:</p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><span style='font-size:10.0pt;font-family:"Courier New"'>#include conio.h<o:p></o:p></span></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><span style='font-size:10.0pt;font-family:"Courier New"'>#include stdio.h<o:p></o:p></span></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><span style='font-size:10.0pt;font-family:"Courier New"'>#include jni.h<o:p></o:p></span></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><span style='font-size:10.0pt;font-family:"Courier New"'>#include
"PasswordInputStream.h"<o:p></o:p></span></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><span style='font-size:10.0pt;font-family:"Courier New"'>JNIEXPORT
jint JNICALL Java_PasswordInputStream_readChar (JNIEnv *env, jobject obj) {<o:p></o:p></span></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><span style='font-size:10.0pt;font-family:"Courier New"'><span
style="mso-spacerun: yes">   </span>int a = getch();<o:p></o:p></span></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><span style='font-size:10.0pt;font-family:"Courier New"'><span
style="mso-spacerun: yes">   </span>if (a!=13) {<o:p></o:p></span></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><span style='font-size:10.0pt;font-family:"Courier New"'><span
style="mso-spacerun: yes">      </span>printf("*");<span
style="mso-spacerun: yes">   </span><o:p></o:p></span></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><span style='font-size:10.0pt;font-family:"Courier New"'><span
style="mso-spacerun: yes">   </span>}<o:p></o:p></span></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><span style='font-size:10.0pt;font-family:"Courier New"'><span
style="mso-spacerun: yes">   </span>return a;<o:p></o:p></span></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><span style='font-size:10.0pt;font-family:"Courier New"'>}<o:p></o:p></span></p>
<p style='text-align:justify'>For those of you not too familiar with C I’ll
briefly describe what this code means. The lines starting with the pound sign
(#) are pre-processor directives. The “include” directive simply inserts the
named file into the current file. You can do that by using a word processor and
not use the “include” directive at all!! We’re including the conio.h file
because it contains the prototype (signature) of the C library function,
“getch()”. Similarly, stdio.h contains the prototype for the “printf()” C
library function.<code><span style='font-size:10.0pt;font-family:"Courier New"'><o:p></o:p></span></code></p>
<p style='text-align:justify'>Jni.h provides information that the native
language code requires to interact with the Java runtime system. <strong><span
style='mso-fareast-font-family:"Courier New"'>When writing native methods, you
must always include this file in your native language source files.</span></strong></p>
<p style='text-align:justify'>The method simply reads a character from the
console and if its not the carriage-return (ascii code 13 decimal) then prints
an asterisk to the console.</p>
<p style='text-align:justify'><![if !supportEmptyParas]> <![endif]><o:p></o:p></p>
<p style='text-align:justify'>STEP 5: Compile the native program:</p>
<p style='text-align:justify'>Now that you have implemented the method in the
native language, you need to compile it into a shared library. You’ll need a C
compiler that can create shared libraries. I personally use Borland’s C++
Builder. Microsoft’s Visual C/C++ compiler also has the capability to compile
as a shared library. Microsoft’s Quick C compiler I heard could compile to
shared libraries but it has poor documentation and online help and I couldn’t
find the switch for the purpose!! If you want to deploy the shared library to
some platform other than Microsoft windows, then you need to create a shared
library for that platform. You can create a shared library on a Unix/Linux
variant by using the “gcc” compiler.</p>
<p style='text-align:justify'>You need to put “<jdk installation
directory>\include” and “<jdk installation directory>\include\win32”
in the “include” path of your compiler in the windows environment. </p>
<p style='text-align:justify'>The compiler will generate a .dll file. You need
to place this dll file in the directory where you java program is located or
put it in the “<jdk installation directory>\bin” for global access.</p>
<p style='text-align:justify'>STEP 6: Test/Run the program:</p>
<p style='text-align:justify'>Finally you need to test the program that you
created. Lets create a simple test program to see if everything works as
expected. The test program is listed below:</p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><span style='font-size:10.0pt;font-family:"Courier New"'>public
class test {<o:p></o:p></span></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><span style='font-size:10.0pt;font-family:"Courier New"'><span
style="mso-spacerun: yes">   </span>public static void main (String [] args) {<o:p></o:p></span></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><span style='font-size:10.0pt;font-family:"Courier New"'><span
style="mso-spacerun: yes">      </span>PasswordInputStream pis = new
PasswordInputStream();<o:p></o:p></span></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><span style='font-size:10.0pt;font-family:"Courier New"'><span
style="mso-spacerun: yes">      </span>System.out.print("Password:
");<o:p></o:p></span></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><span style='font-size:10.0pt;font-family:"Courier New"'><span
style="mso-spacerun: yes">  </span><span style="mso-spacerun:
yes">    </span>String passwd = pis.readLine();<o:p></o:p></span></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><span style='font-size:10.0pt;font-family:"Courier New"'><span
style="mso-spacerun: yes">      </span>System.out.println("You entered:
"+passwd);<o:p></o:p></span></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><span style='font-size:10.0pt;font-family:"Courier New"'><span
style="mso-spacerun: yes">   </span>}<o:p></o:p></span></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><span style='font-size:10.0pt;font-family:"Courier New"'>}<o:p></o:p></span></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><span style='font-size:10.0pt;font-family:"Courier New"'><![if !supportEmptyParas]> <![endif]><o:p></o:p></span></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><span style='mso-bidi-font-size:10.0pt'>It creates an
instance of the PasswordInputStream class and then uses the readLine instance
method to read a password. It then displays the password to the user (not a
smart move!!).<o:p></o:p></span></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'><![if !supportEmptyParas]> <![endif]><o:p></o:p></p>
<p class=MsoNormal style='text-align:justify;mso-layout-grid-align:none;
text-autospace:none'>The discussion was meant to be an introduction to JNI.
There is definitely more to it and you can learn more by going through the
various articles and tutorials at <a href="http://java.sun.com/">http://java.sun.com</a>.
</p>
<p><b>If you read this article please vote for it. It'll take less than a minute of your time!!</b></p>
<p class=MsoNormal style='text-align:justify'><![if !supportEmptyParas]> <![endif]><o:p></o:p></p>
</div>
</body>
</html>
```

