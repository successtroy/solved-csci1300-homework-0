Download Link: https://assignmentchef.com/product/solved-csci1300-homework-0
<br>
<h1>1. Objectives</h1>

<ul>

 <li>Set up your Moodle account</li>

 <li>Apply for an AWS educate account</li>

 <li>Set up AWS Cloud 9 IDE</li>

 <li>Set up VS code</li>

 <li>Introduction to Linux</li>

 <li>Submit a zip file with HelloWorld.cpp, HelloVSCode.cpp, and profile.txt to Moodle.</li>

</ul>

2.2 Set up AWS educate account and Cloud 9 IDE:

In recitation today, you will be getting started with AWS Cloud9, a cloud-based development environment, which is designed to provide a consistent development environment for all students. Follow the steps below. If you need help ask your TA or one of the CAs.

There are three phases for setting-up your AWS Cloud 9 IDE:

<ol>

 <li>Apply for an AWS Educate account</li>

 <li>Log-in to the student portal and go to the AWS classroom</li>

 <li>Set up AWS Cloud 9 workspace</li>

</ol>

You can find <a href="https://moodle.cs.colorado.edu/mod/resource/view.php?id=45303">AWS cloud 9 set up guid</a>​    <a href="https://moodle.cs.colorado.edu/mod/resource/view.php?id=45303">e</a> on Moodle​

2.3 Upload a profile.txt to AWS Cloud 9 IDE:

You can find Profile.txt file found on the first Moodle topic (“Introduction to Computers and Programming” – Topic 1)  Download the profile.txt and upload it on your Cloud 9 workspace. Then, Insert your answers. Be sure to save your file!

<ol>

 <li>From the menu bar on the top, choose <strong>File</strong>​ -&gt; ​         <strong>Upload Local Files…</strong>​</li>

 <li>Then, drag and drop the file you want to upload.</li>

 <li>Insert your answer and save it.</li>

</ol>

2.4 Create a Hello World program:

The “Hello, World!” program is one of the simplest programs in a programming language, and it is often used to illustrate the basic syntax of a programming language.

<ol>

 <li>From the menu bar, choose ​<strong>File</strong>​ -&gt; ​<strong>New From Template</strong>​ -&gt; ​<strong>C++ File </strong></li>

 <li>Save your file. ​<strong>Important:</strong>​ The filename should be named with ​<strong>CamelCase</strong>​ (the first letter of each word in a compound word is capitalized) end with ​<strong>.cpp</strong>​. Your file name should be ​<strong>cpp</strong></li>

 <li>Click “Run” button on the top. You will see the output at the bottom of the page. The last line means that the program ended successfully.</li>

 <li>Let’s add a statement to use the <em>standard namespace</em>​ ​. Insert using namespace​   std; at the beginning of the code, then we can remove the std prefixes. Be sure to click​            “Run” button again to make sure that your code still compiles and runs.</li>

</ol>




<ol start="5">

 <li>Let’s modify the file to print “<strong>Hello world! Hello CSCi 1300</strong>​ ”. The text inside of the​            quotation marks is printed as it is. It’s case sensitive too!</li>

</ol>

Congratulations! You did the 1st C++ programming!

You will learn more C++ syntax over the semester to build your programming and problem-solving skills. Here is a snapshot of your program.

2.5 Learn how to use Terminal:

Switch to the <em>bash</em>​   ​ tab and let’s learn some useful Linux commands.

You see: vocstartsoft:~/environment $​

<ul>

 <li><strong>~/</strong> (i.e. everything else before the ​ <strong>$</strong>​ )​ = your current directory (think of a directory as the folder you’re in).</li>

 <li><strong>~</strong> is shorthand for the current user’s home directory.​</li>

 <li><strong>$</strong> represents the end of prompt for entering a command.​</li>

</ul>

File browsing using the terminal is like using Windows explorer or like clicking on folders and navigating to different folders on your laptop. In the terminal, instead of clicking on folders we use commands to tell the computer what we want. If we want to go to a folder where we saved our last homework, we can type the commands to navigate to that folder and display its contents.

<strong>Try these commands:</strong>

<h2><strong>ls</strong> — list directory contents​</h2>




ls = (that’s a lowercase “L”, not an uppercase “i”) stands for list and is used to ‘list’ or show you​            everything in the current directory.




Note:  after you type the command and press ENTER, something is displayed as a result of the command, but then the prompt returns.

<h2><strong>mkdir</strong> — make directories​</h2>

To create a new directory, use the command ​mkdir &lt;my_folder&gt;

Note: Spaces are troublesome on the command line, so we’ll use underscores.

Let’s create a directory for today’s recitation, named ​rec2

$ mkdir rec2

rec2​ is now a directory/folder, nested under the folder environment. If you want to list the contents of the folder environment, you will now notice a new item: ​rec2/​, where the forward-slash (​/​) indicates ​rec2​ is a subdirectory.

You will also notice a new folder in the Environment tab, to the left of your window:

<h3><strong>cd</strong> — Change the shell working directory.​</h3>

cd = stands for change directory is just like changing folders. It means, take me to place X.

Commonly used as ​cd &lt;name_of_directory&gt;​.

<ul>

 <li><strong>Note</strong>​ that there will always be a space between cd and the name of the directory that you want to navigate to and the name of the directory will not include the carrots (side arrows) displayed above.</li>

 <li><strong>Note</strong>​: cd takes you places in reference to your current location. It’s like going into a folder, and then clicking on a folder within that folder, and then clicking on another folder within that folder. You will always navigate deeper within that folder. To back up, we use “​cd ..​” (explained in a little bit).</li>

 <li><strong>Note</strong>​: cd (and other commands) is case sensitive. ‘​rec2​’ does not equal ‘​Rec2​’. Make sure you type in directory names exactly as they are spelled.</li>

</ul>

“​cd ..​” means go to the parent of my current location. It’s essentially backing up.

<h2><strong>cp</strong> — copy files​</h2>

(​<strong>Note</strong>​:  Be very careful not to overwrite a file when copying.)




<ol>

 <li>First, click inside the editor window, where the file ​cpp​ is open. Go up to the menu and choose File -&gt; Save As and, when the dialog box opens, change the name of the file to ​hello1300.cpp​. Choose ​rec2​ as the destination folder.</li>

 <li>Once you click Save, the new file will appear in the file tree, in the Environment tab (see the figure on the right, above).</li>

 <li>Let’s make another directory named ​rec1​.

  <ol>

   <li>$ mkdir rec1</li>

  </ol></li>

 <li>Now we want to copy the file from ​rec2​ into ​rec1​. First, we go into the ​rec2​ directory:

  <ol>

   <li>$ cd rec2</li>

  </ol></li>

 <li>Ok, now we use the command for copying files:

  <ol start="1300">

   <li>$ cp hello1300.cpp hello1300v2.cpp</li>

  </ol></li>

 <li>Now let’s type ls and see what we have:</li>

</ol>

Since we did not specify the path for the file we wanted to copy, nor for where we wanted it copied, we ended up with an identical copy of the file, both of them inside the folder rec2​            .​

<ol start="7">

 <li>Let’s do this again, including the paths:</li>

 <li>If your terminal window has gotten full, you can always clear it. Right-click anywhere in it, and choose “Clear Buffer”</li>

</ol>

<strong> </strong>

<h3><strong>mv</strong> — move files​</h3>

It’s possible to move files around using the command ​mv​.  Starting in directory ​rec2​, type:

$ mv hello1300.cpp ..

Remember, two dots indicate the parent directory (one level up).  Now if we list the files in rec2​, there is only ​hello1300v2.cpp​ left. And we will move the file ​hello1300.cpp​ up in the root directory:

Let’s move one more file into the ​rec1​ directory:

<strong>zip</strong> (​ <strong>unzip</strong>​    )​ – package and compress (archive) files

An important thing to know for this class is how to zip your solution files into one assignment submission file.  To do this, there’s a convenient command called zip.  Let’s zip up the two files in the directory rec1​    into a single zip file.​

$ zip test_files.zip  hello1300.cpp hello1300v3.cpp

The first argument is the name of the zip file we want to produce. The files listed next are the files that go into this zip file.  If you list your directory now, you should see three files.  Notice that the original files are still present–zip and unzip don’t destroy any files.

Let’s now move the .zip file into the rec2​     directory, and try to unzip the files:​

You should see the three files in the directory.  Note that the original zip file didn’t get destroyed.

Linux commands we’ve learned:

Here are the five useful Linux commands we just practiced:

<ul>

 <li><strong>ls</strong>:​ List directory contents. Use this command to see the list of files and folders in the current directory.</li>

 <li><strong>mkdir</strong>:​ Make directories. Create a new directory (folder).</li>

 <li><strong>cd</strong>:​ Change directory. Use this command to change the current directory (move to another folder)</li>

 <li><strong>cp</strong>:​ Copy a file</li>

 <li><strong>mv</strong>:​ Move a file</li>

 <li><strong>zip</strong>:​ Create a zip file</li>

</ul>

<h3>Fun tips and tricks</h3>

<ul>

 <li><strong>Tab Complete:</strong> if you’re typing something in the command line that’s very long, but unique, you can hit tab when you’re partially through and it will try to fill in the rest (kind of like autocomplete). If it doesn’t, and you tap tab twice, it tells you everything it has as options.</li>

 <li><strong>Command history browsing:</strong> if you have typed a command (e.g. gedit​txt)​ and want to repeat it, just press the up arrow. It will bring up your last executed command. Pressing up again will go to the one before. Pressing down will go forward in time through the list.</li>

 <li>ASCII is a character encoding standard. It includes numerical characters: 0-9, letters A-Z and a-z, punctuation, and blank spaces. These character codes represent text in computers. For example, the ASCII representation of ‘D’ is 01000100, and the ASCII representation of ‘d’ is 01100100. Notice the difference? ‘D’ is different from ‘d’, therefore, it is important for you to always make sure that you have proper capitalization and spelling when you are typing from the command line.</li>

</ul>

<strong>Want to learn more about Linux commands?</strong>

<a href="https://community.linuxmint.com/tutorial/view/244">http://community.linuxmint.com/tutorial/view/244</a> has a list of categorized Linux commands.​

Codecademy also has a course covering the command line

(<a href="https://www.codecademy.com/learn/learn-the-command-line">https://www.codecademy.com/learn/learn-the-command-lin</a>​    <a href="https://www.codecademy.com/learn/learn-the-command-line">e</a>).​

<ul>

 <li><strong>Setup for Visual Studio Code</strong>​ :​</li>

</ul>

You also need to set up a development environment locally to make sure that you can write code without an internet. Also, in case Cloud 9 goes down for maintenance, you still need to work and complete assignments.

You can find the <a href="https://moodle.cs.colorado.edu/mod/resource/view.php?id=45304">VS code set up guid</a><u>​    </u><a href="https://moodle.cs.colorado.edu/mod/resource/view.php?id=45304">e</a> on Moodle. Follow the instructions and set up it locally.​

Task3:​ Write a helloWorld in VS code as you did in section 2.4. Your program should print “Hello CSCI1300 from VS code​              ”. Be sure that your code compiles and runs on both your​     machine and cloud 9. Your .cpp file should be named “helloWorldVScode.cpp​          ”​




<ul>

 <li><strong>Back up often: </strong></li>

</ul>

It’s a good idea to create a backup of your workspace. Backing up a file only takes a few seconds. You will hate yourself if you lose hours of work before the deadline. We recommend that you backup your work once every thirty minutes.

<h3>Cloud 9</h3>

In case, Cloud 9 goes down for maintenance unexpectedly be sure to have a backup. You can simply download an entire environment.

<h3>Your computer <strong> </strong></h3>

It’s also important to backup your computer in case your computer gets broken or your dog bites your laptop. You can use:

<ul>

 <li>Dropbox</li>

 <li>Google Drive</li>

 <li>Github (be sure to use Private repository. You can get free private repository via <a href="https://education.github.com/pack">GitHu</a><u>​ </u><a href="https://education.github.com/pack">b</a></li>

</ul>

<a href="https://education.github.com/pack">Student Developer Pack</a><a href="https://education.github.com/pack">)</a><u>​</u>


