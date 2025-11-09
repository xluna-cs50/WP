Practicl 1A type Hello FY data science

<html>
<head>
<title>
hello
</title>
</head>
<body>
Hello FY data science
</body>
</html>


Practical 1B use formatting tags
<html>
<head>
<title>formatting tags</title>
</head>
<body>
<b>this is a bold tag</b><br>
<strong>this is a strong tag</strong><br>
<i>this is a italic tag</i><br>
<em>this is a emphasize tag</em><br>
<del>this is a delete tag</del><br>
<mark>this is a mark tag</mark><br>
<u>This is a underline tag</u><br>
<big>this is a big tag</big><br>
<small>this is a small tag</small><br>
x<sup>4</sup><br>
CO<sub>2</sub><br>
</body>
</html>

practical 1C create a link

<html>
<head>
<title>
creating a link
</title>
</head>
<body>
<a href="program 1A.html">Click here</a><br>
<a href="google.com">Google</a><br>
</body>
</html>


Practical 1D(A) ordered list

<html>
<head>
<title>ordered list
</title>
</head>
<body>
<h5>Web programming topics</h5>
<ol type="a">
<li>html</li>
<li>list</li>
<li>comments</li>
<li>headings</li>
</ol>
<h5>Web programming topics</h5>
<ol type="1">
<li>html</li>
<li>list</li>
<li>comments</li>
<li>headings</li>
</ol><h5>Web programming topics</h5>
<ol type="i">
<li>html</li>
<li>list</li>
<li>comments</li>
<li>headings</li>
</ol>
</body>
</html>

Practcal 1D(B) unordered list

<html>
<head>
<title>unordered list</title>
</head>
<body>
<h5>List of available courses</h5>
<ul type="square">
<li>introduction to data science</li>
<li>Web programming</li>
<li>FOS</li>
<li>MIS</li>
</ul>
<h5>List of available courses</h5>
<ul type="circle">
<li>introduction to data science</li>
<li>Web programming</li>
<li>FOS</li>
<li>MIS</li>
</ul>
<h5>List of available courses</h5>
<ul type="disk">
<li>introduction to data science</li>
<li>Web programming</li>
<li>FOS</li>
<li>MIS</li>
</ul>
</body>
</html>

Practical 1D(C) multi-nested list (ordered list)
<html>
<head>
<title>
mukti-nested list
</title>
</head>
<body>
<h5>Web programming topics</h5>
<ol>
<li>html</li>
<li>web programming</li>
<ol type="a">
<li>html<li>
<li>single line</li>
<li>multi-line</li>
</ol>
<li>javascript</li>
<ol type="1">
<li>loop</li>
<ol type="i">
<li>for loop</li>
<li>while loop</li>
<li>do loop</li>
</ol>
<li>functions</li>
</ol>
</body>
</html>

Practical 1D(D) multi-nested list (unordered list)
<html>
<head>
<title>
mukti-nested list
</title>
</head>
<body>
<h5>Web programming topics</h5>
<ul>
<li>html</li>
<li>web programming</li>
<ul type="disc">
<li>html<li>
<li>single line</li>
<li>multi-line</li>
</ul>
<li>JavaScript</li>
<ul type="circle">
<li>loop</li>
<ul type="square">
<li>for loop</li>
<li>while loop</li>
<li>do loop</li>
</ul>
<li>functions</li>
</ul>
</body>
</html>


Practical 1E table

<!DOCTYPE html>
<html>
<head>
    <title>Seminar Schedule</title>
</head>
<body>

    <h2 align="center">3-Day Seminar Schedule</h2>

    <table border="1" align="center" cellpadding="8" cellspacing="0">
        <tr bgcolor="lightblue">
            <th>Day</th>
            <th bgcolor="yellow">Schedule</th>
            <th>Topic</th>
        </tr>
        <tr>
            <td>Monday</td>
            <td bgcolor="yellow">10:00 AM - 1:00 PM</td>
            <td>Introduction to AI</td>
        </tr>
        <tr>
            <td>Tuesday</td>
            <td bgcolor="yellow">10:00 AM - 1:00 PM</td>
            <td>Machine Learning Basics</td>
        </tr>
        <tr>
            <td>Wednesday</td>
            <td bgcolor="yellow">10:00 AM - 1:00 PM</td>
            <td>Future of Technology</td>
        </tr>
    </table>

</body>
</html>



Practical 1F form 

<!DOCTYPE html>
<html>
<head>
    <title>Student Information Form</title>
</head>
<body>

    <h2 align="center">Student Information Form</h2>

    <form align="center">

        <label>Enter your name:</label><br>
        <input type="text" name="username"><br><br>

        <label>Enter your password:</label><br>
        <input type="password" name="password"><br><br>

        <label>Enter your number:</label><br>
        <input type="number" name="number"><br><br>

        <label>Enter your email:</label><br>
        <input type="email" name="email"><br><br>

        <label>Choose a file:</label><br>
        <input type="file" name="file"><br><br>

        <label>Hobbies:</label><br>
        <input type="checkbox" name="hobby" value="dancing"> Dancing<br>
        <input type="checkbox" name="hobby" value="singing"> Singing<br>
        <input type="checkbox" name="hobby" value="drawing"> Drawing<br><br>

        <label>Select your class:</label><br>
        <input type="radio" name="class" value="11"> Class 11<br>
        <input type="radio" name="class" value="12"> Class 12<br><br>

        <label>Select your batch:</label><br>
        <select name="batch">
            <option>Batch 1</option>
            <option>Batch 2</option>
            <option>Batch 3</option>
        </select><br><br>

        <label>Feedback:</label><br>
        <textarea rows="10" cols="50" name="feedback"></textarea><br><br>

        <button type="button">Click Here</button>
        <input type="submit" value="Submit">
        <input type="reset" value="Reset">

    </form>

</body>
</html>


Practical G(A) inserting images in a html document 

<htmL>
<head>
<title>
Inserting Images
</title>
</head>
<body>
<img src="saved image" height="100" width="200"><br><br>
<img src="GIF link" height="100" width="200"><br><br>
<img src="image link" height="100" width="200"><br><br>
</body>
</html>


Practical G(B) inserting audio and video file

<html>
<head>
<tile>
audio and video
</title>
</head>
<body>
<audio controls>
<source src="Audio source">
</audio>
<br><br>
<video controls height="300" width="300">
<source src="video source">
</video>
</body>
</html>




Practial 2A(1) inline css

<html>
<head>
<title>inline css</title>
</head>
<body>
<p style="color:red">Hello</p><br>
<p style="border:10px dashed green">September</p>
</body>
</html>


Practical 2A(2) internal css

<html>
<head>
<style>
p{color:blue;border:10px dotted red;}
h6{text-align:right}
</style>
</head>
<body>
<p>Hello</p>
<p>September</p>
<h6>FYDS</h6>
</body>
</html>


Practical 2A(3) external css

.css 
p{color:blue; border:10px dotted red;}
h6{color:red; border:10px dotted green;}
h6{color:blue; border:10px dotted blue;}

.HTML
<html>
<head>
<link rel="stylesheet" href="style.css">
</head>
<body>
<p>Hello</p>
<p>september</p>
<h6>FYDS</h6>
</body>
</html>


Practical 2B(1)

<html> 
<style> 
p{text-align:right;color:blue} 
</style> 
<body> 
<p>Hello</p> 
<p>FYDS</p> 
<h1>Hello</h1> 
</body> 
</html>


2B[2] 
<!DOCTYPE html> 
<html> 
<head> 
        <title>CSS 2B</title> 
    <style> 
        div>span { 
            text-align: right; 
            color: red; 
        } 
    </style> 
</head> 
<body> 
<div> 
    <span> I am red! </span> 
    <p>FYDS</p> 
    <h1>Hello</h1> 
</div> 
</body> 
</html>


2B[3] 
<html> 
  <head> 
    <style> 
      .p1 { 
 font-size: 18px; 
 margin-bottom: 20px; 
        text-align: right; 
        color: blue; 
      } 
    </style> 
  </head> 
  <body> 
    <p class="p1">Hello</p> 
    <p class="p1">FYDS</p> 
    <h1>Hello</h1> 
  </body> 
</html>


 
2B[4] 
<html> 
  <head> 
    <style> 
      p, h4 { 
        text-align: right; 
        color: blue; 
      } 
    </style> 
  </head> 
  <body> 
    <p>Hello</p> 
    <h4>FYDS</h4> <!-- Changed </p> to </h4> --> 
    <h1>Hello Friends</h1> 
  </body> 
</html>



2C[1] 
<html> 
<style> 
p{text-align:center} 
h1{text-indent:100px} 
h2{text-decoration:line-through} 
h3{text-transform:Capitalize} 
</style> 
<body> 
<p>Mallakhamba or mallakhamb is a traditional sport, originating from the 
Indian subcontinent, in which a gymnast performs aerial yoga or gymnastic 
postures and wrestling grips in concert with a vertical stationary or hanging 
wooden pole, cane, or rope. The word "mallakhamb" also refers to the pole 
used in the sport.</p> 
<h1>FYDS</h1> 
<h2>October</h2> 
<h3>hello</h3> 
</body> 
</html>




2C[2] 
<html> 
<style> 
p{color:blue} 
h1{color:#006400} 
h2{color:rgb(150,10,1)} 
h3{color:rgba(150,10,1,0.5)} 
h4{color:hsl(120,10%,50%)} 
h5{color:hsla(65,100%,30%,0.5)} 
</style> 
<body> 
<p>October</p> 
<h1>FYDS</h1> 
<h2>SYDS</h2> 
<h3>TYDS</h3> 
<h4>Hello</h4> 
<h5>September</h5> 
</body> 
</html> 



PRACTICAL 3

3A Display your name using Javascript alert and Document write. 
Source Code : 
<html> 
<body> 
<script> 
alert('Swati'); 
document.write('Swati'); 
</script> 
</body> 
</html> 
3B Write a program in JavaScript to find if a number is even or odd.  
Source Code : 
<html> 
<body> 
<script> 
var a= parseInt(prompt("Enter the number")); 
if(a%2==0) 
{ 
} 
document.write("Even"); 
else{ 
document.write("Odd"); 
} 
</script> 
</body> 
</html> 
3C Write a program in JavaScript to find greatest of three numbers. 
Source Code : 
<html> 
<body> 
<script> 
var a=parseInt(prompt("Enter a")); 
var b=parseInt(prompt("Enter b")); 
var c=parseInt(prompt("Enter c")); 
if(a>b&&a>c) 
{ 
document.write("a is greatest"); 
} 
else if(b>a&&b>c) 
{ 
document.write("b is greatest"); 
} 
else 
{ 
document.write("c is greatest"); 
} 
</script> 
</body> 
</html> 
3D Write a program to display month of the year according to user input. 
Source Code : 
<html> 
<body> 
<script> 
var a=parseInt(prompt("Enter a number")); 
switch(a) 
{ 
case 1: 
document.write("January"); 
break; 
case 2: 
document.write("February"); 
break; 
case 3: 
document.write("March"); 
break; 
case 4: 
document.write("April"); 
break; 
case 5: 
document.write("May"); 
break; 
case 6: 
document.write("June"); 
break; 
case 7: 
document.write("July"); 
break; 
case 8: 
document.write("Augest"); 
break; 
case 9: 
document.write("September"); 
break; 
case 10: 
document.write("October"); 
break; 
case 11: 
document.write("November"); 
break; 
case 12: 
document.write("December"); 
break; 
default: 
document.write("Invlid input"); 
} 
</script> 
</body> 
</html>



PRACTICAL 4

4A Write a program to print numbers from 1-10 using all the 3 loops. 
Source Code : 
<html> 
<body> 
<script> 
document.write('Using for Loop') 
var i=0; 
for (i=1;i<=10;i++) 
{ 
document.write('<br>'+i); 
} 
</script> 
<br> 
<script> 
document.write('Using While loop') 
var i=1; 
while(i<=10) 
{ 
document.write('<br>'+i); 
i++; 
} 
</script> 
<br> 
<script> 
document.write('Using Do While Loop') 
i=1; 
do{ 
document.write('<br>'+i);i++; 
}while(i<=10); 
</script> 
</body> 
</html>

 
4B Write a program to print numbers from m to n. 
Source Code : 
<html> 
<body> 
<script> 
document.write('Using For loop'); 
var i=0; 
var m=parseInt(prompt("Enter m:")) 
var n=parseInt(prompt("Enter n:")) 
for (i=m;i<=n;i++) 
{ 
document.write('<br>'+i); 
} 
</script> 
</body> 
</html> 



4C Write a program numbers from m to n with the jump of 3. 
Source Code : 
<html> 
<body> 
<script> 
document.write('Using For loop'); 
var i=0; 
var m=parseInt(prompt("Enter m:")) 
var n=parseInt(prompt("Enter n:")) 
for (i=m;i<=n;i=i+3) 
{ 
document.write('<br>'+i); 
} 
</script> 
</body> 
</html> 



4D Write a program to print numbers m to n in descending order. 
Source Code : 
<html> 
<body> 
<script> 
document.write('Using For loop'); 
var i=0; 
var m=parseInt(prompt("Enter m:")) 
var n=parseInt(prompt("Enter n:")) 
for (i=m;i>=n;i--) 
{ 
document.write('<br>'+i); 
} 
</script> 
</body> 
</html> 



4E Write a program to print  numbers from m to n number to be even. 
Source Code : 
<html> 
<body> 
<script> 
var i=0; 
var m=parseInt(prompt("Enter m:")) 
var n=parseInt(prompt("Enter n:")) 
var i; 
for (i=m;i<n;i++) 
{ 
if(i%2==0){ 
document.write('<br>'+i); 
} 
} 
</script> 
</body> 
</html> 
4F Write a program to print multiplication table. 
Source Code : 
<html> 
<body> 
<script> 
var i=0; 
var m=parseInt(prompt("Enter m")) 
for (i=1;i<=10;i++) 
{ 
document.write('<br>'+m+'x'+i+'='+m*i); 
}  
</script><p> 
</body> 
</html>

