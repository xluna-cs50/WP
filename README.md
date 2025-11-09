# WP Practical Assignments

This repository contains solution snippets for Web Programming practicals and exercises. Each practical is organized with explanations and corrected sample code for clarity.

---

## Practical 1A: Hello FY Data Science

```html
<!-- Practical 1A -->
<!DOCTYPE html>
<html>
<head>
  <title>Hello FY Data Science</title>
</head>
<body>
  Hello FY Data Science
</body>
</html>
```

---

## Practical 1B: Formatting Tags

```html
<!DOCTYPE html>
<html>
<head>
  <title>Formatting Tags</title>
</head>
<body>
  <b>This is a bold tag</b><br>
  <strong>This is a strong tag</strong><br>
  <i>This is an italic tag</i><br>
  <em>This is an emphasized tag</em><br>
  <del>This is a deleted tag</del><br>
  <mark>This is a mark tag</mark><br>
  <u>This is an underline tag</u><br>
  <big>This is a big tag</big><br>
  <small>This is a small tag</small><br>
  x<sup>4</sup><br>
  CO<sub>2</sub><br>
</body>
</html>
```

---

## Practical 1C: Create a Link

```html
<!DOCTYPE html>
<html>
<head>
  <title>Creating a Link</title>
</head>
<body>
  <a href="program1A.html">Click here</a><br>
  <a href="https://google.com" target="_blank">Google</a><br>
</body>
</html>
```

---

## Practical 1D(A): Ordered List

```html
<!DOCTYPE html>
<html>
<head>
  <title>Ordered List</title>
</head>
<body>
  <h5>Web Programming Topics</h5>
  <ol type="a">
    <li>HTML</li>
    <li>List</li>
    <li>Comments</li>
    <li>Headings</li>
  </ol>
  <h5>Web Programming Topics</h5>
  <ol type="1">
    <li>HTML</li>
    <li>List</li>
    <li>Comments</li>
    <li>Headings</li>
  </ol>
  <h5>Web Programming Topics</h5>
  <ol type="i">
    <li>HTML</li>
    <li>List</li>
    <li>Comments</li>
    <li>Headings</li>
  </ol>
</body>
</html>
```

---

## Practical 1D(B): Unordered List

```html
<!DOCTYPE html>
<html>
<head>
  <title>Unordered List</title>
</head>
<body>
  <h5>List of Available Courses</h5>
  <ul type="square">
    <li>Introduction to Data Science</li>
    <li>Web Programming</li>
    <li>FOS</li>
    <li>MIS</li>
  </ul>
  <h5>List of Available Courses</h5>
  <ul type="circle">
    <li>Introduction to Data Science</li>
    <li>Web Programming</li>
    <li>FOS</li>
    <li>MIS</li>
  </ul>
  <h5>List of Available Courses</h5>
  <ul type="disc">
    <li>Introduction to Data Science</li>
    <li>Web Programming</li>
    <li>FOS</li>
    <li>MIS</li>
  </ul>
</body>
</html>
```

---

## Practical 1D(C): Multi-Nested Ordered List

```html
<!DOCTYPE html>
<html>
<head>
  <title>Multi-nested List</title>
</head>
<body>
  <h5>Web Programming Topics</h5>
  <ol>
    <li>HTML</li>
    <li>Web Programming
      <ol type="a">
        <li>HTML</li>
        <li>Single Line</li>
        <li>Multi-line</li>
      </ol>
    </li>
    <li>JavaScript
      <ol type="1">
        <li>Loop
          <ol type="i">
            <li>For Loop</li>
            <li>While Loop</li>
            <li>Do Loop</li>
          </ol>
        </li>
        <li>Functions</li>
      </ol>
    </li>
  </ol>
</body>
</html>
```

---

## Practical 1D(D): Multi-Nested Unordered List

```html
<!DOCTYPE html>
<html>
<head>
  <title>Multi-nested Unordered List</title>
</head>
<body>
  <h5>Web Programming Topics</h5>
  <ul>
    <li>HTML</li>
    <li>Web Programming
      <ul type="disc">
        <li>HTML</li>
        <li>Single Line</li>
        <li>Multi-line</li>
      </ul>
    </li>
    <li>JavaScript
      <ul type="circle">
        <li>Loop
          <ul type="square">
            <li>For Loop</li>
            <li>While Loop</li>
            <li>Do Loop</li>
          </ul>
        </li>
        <li>Functions</li>
      </ul>
    </li>
  </ul>
</body>
</html>
```

---

## Practical 1E: Table

```html
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
```

---

## Practical 1F: Form

```html
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
```

---

## Practical G(A): Inserting Images in a HTML Document

```html
<!DOCTYPE html>
<html>
<head>
  <title>Inserting Images</title>
</head>
<body>
  <img src="savedimage.jpg" height="100" width="200" alt="Saved Image"><br><br>
  <img src="image.gif" height="100" width="200" alt="GIF"><br><br>
  <img src="image.png" height="100" width="200" alt="Image"><br><br>
</body>
</html>
```

---

## Practical G(B): Inserting Audio and Video File

```html
<!DOCTYPE html>
<html>
<head>
  <title>Audio and Video</title>
</head>
<body>
  <audio controls>
    <source src="audio.mp3" type="audio/mp3">
    Your browser does not support the audio element.
  </audio>
  <br><br>
  <video controls height="300" width="300">
    <source src="video.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</body>
</html>
```

---

## Practical 2A(1): Inline CSS

```html
<!DOCTYPE html>
<html>
<head>
  <title>Inline CSS</title>
</head>
<body>
  <p style="color:red">Hello</p>
  <p style="border: 10px dashed green;">September</p>
</body>
</html>
```

---

## Practical 2A(2): Internal CSS

```html
<!DOCTYPE html>
<html>
<head>
  <title>Internal CSS</title>
  <style>
    p { color: blue; border: 10px dotted red; }
    h6 { text-align: right; }
  </style>
</head>
<body>
  <p>Hello</p>
  <p>September</p>
  <h6>FYDS</h6>
</body>
</html>
```

---

## Practical 2A(3): External CSS

**style.css**
```css
p { color: blue; border: 10px dotted red; }
h6 { color: red; border: 10px dotted green; }
h6 { color: blue; border: 10px dotted blue; }
```

**index.html**
```html
<!DOCTYPE html>
<html>
<head>
  <title>External CSS</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <p>Hello</p>
  <p>september</p>
  <h6>FYDS</h6>
</body>
</html>
```

---

## Practical 2B(1): Selectors

```html
<!DOCTYPE html>
<html>
<head>
  <title>CSS 2B[1]</title>
  <style>
    p { text-align: right; color: blue; }
  </style>
</head>
<body>
  <p>Hello</p>
  <p>FYDS</p>
  <h1>Hello</h1>
</body>
</html>
```

---

## Practical 2B[2]: Child Selector

```html
<!DOCTYPE html>
<html>
<head>
  <title>CSS 2B[2]</title>
  <style>
    div > span {
      text-align: right;
      color: red;
    }
  </style>
</head>
<body>
  <div>
    <span>I am red!</span>
    <p>FYDS</p>
    <h1>Hello</h1>
  </div>
</body>
</html>
```

---

## Practical 2B[3]: Class Selector

```html
<!DOCTYPE html>
<html>
<head>
  <title>CSS 2B[3]</title>
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
```

---

## Practical 2B[4]: Multiple Selectors

```html
<!DOCTYPE html>
<html>
<head>
  <title>CSS 2B[4]</title>
  <style>
    p, h4 {
      text-align: right;
      color: blue;
    }
  </style>
</head>
<body>
  <p>Hello</p>
  <h4>FYDS</h4>
  <h1>Hello Friends</h1>
</body>
</html>
```

---

## Practical 2C[1]: Text Formatting

```html
<!DOCTYPE html>
<html>
<head>
  <title>CSS 2C[1]</title>
  <style>
    p { text-align: center; }
    h1 { text-indent: 100px; }
    h2 { text-decoration: line-through; }
    h3 { text-transform: capitalize; }
  </style>
</head>
<body>
  <p>
    Mallakhamba or mallakhamb is a traditional sport, originating from the 
    Indian subcontinent, in which a gymnast performs aerial yoga or gymnastic 
    postures and wrestling grips in concert with a vertical stationary or hanging 
    wooden pole, cane, or rope. The word "mallakhamb" also refers to the pole 
    used in the sport.
  </p>
  <h1>FYDS</h1>
  <h2>October</h2>
  <h3>hello</h3>
</body>
</html>
```

---

## Practical 2C[2]: Color Formatting

```html
<!DOCTYPE html>
<html>
<head>
  <title>CSS 2C[2]</title>
  <style>
    p { color: blue; }
    h1 { color: #006400; }
    h2 { color: rgb(150,10,1); }
    h3 { color: rgba(150,10,1,0.5); }
    h4 { color: hsl(120,10%,50%); }
    h5 { color: hsla(65,100%,30%,0.5); }
  </style>
</head>
<body>
  <p>October</p>
  <h1>FYDS</h1>
  <h2>SYDS</h2>
  <h3>TYDS</h3>
  <h4>Hello</h4>
  <h5>September</h5>
</body>
</html>
```

---

# JavaScript Practicals

## PRACTICAL 3A: Display Name Using JS Alert and Document Write

```html
<!DOCTYPE html>
<html>
<body>
<script>
  alert('Swati');
  document.write('Swati');
</script>
</body>
</html>
```

---

## PRACTICAL 3B: Even or Odd Number

```html
<!DOCTYPE html>
<html>
<body>
<script>
  var a = parseInt(prompt("Enter the number"));
  if (a % 2 == 0) {
    document.write("Even");
  } else {
    document.write("Odd");
  }
</script>
</body>
</html>
```

---

## PRACTICAL 3C: Greatest of Three Numbers

```html
<!DOCTYPE html>
<html>
<body>
<script>
  var a = parseInt(prompt("Enter a"));
  var b = parseInt(prompt("Enter b"));
  var c = parseInt(prompt("Enter c"));
  if (a > b && a > c) {
    document.write("a is greatest");
  } else if (b > a && b > c) {
    document.write("b is greatest");
  } else {
    document.write("c is greatest");
  }
</script>
</body>
</html>
```

---

## PRACTICAL 3D: Display Month of the Year

```html
<!DOCTYPE html>
<html>
<body>
<script>
  var a = parseInt(prompt("Enter a number"));
  switch (a) {
    case 1: document.write("January"); break;
    case 2: document.write("February"); break;
    case 3: document.write("March"); break;
    case 4: document.write("April"); break;
    case 5: document.write("May"); break;
    case 6: document.write("June"); break;
    case 7: document.write("July"); break;
    case 8: document.write("August"); break;
    case 9: document.write("September"); break;
    case 10: document.write("October"); break;
    case 11: document.write("November"); break;
    case 12: document.write("December"); break;
    default: document.write("Invalid input");
  }
</script>
</body>
</html>
```

---

# JavaScript Loops Practicals

## PRACTICAL 4A: Print 1-10 Using All 3 Loops

```html
<!DOCTYPE html>
<html>
<body>
<script>
  document.write('Using for Loop');
  for (var i = 1; i <= 10; i++) {
    document.write('<br>' + i);
  }
</script>
<br>
<script>
  document.write('Using while Loop');
  var i = 1;
  while (i <= 10) {
    document.write('<br>' + i);
    i++;
  }
</script>
<br>
<script>
  document.write('Using do-while Loop');
  var i = 1;
  do {
    document.write('<br>' + i);
    i++;
  } while (i <= 10);
</script>
</body>
</html>
```

---

## PRACTICAL 4B: Print Numbers from m to n

```html
<!DOCTYPE html>
<html>
<body>
<script>
  document.write('Using for Loop');
  var m = parseInt(prompt("Enter m:"));
  var n = parseInt(prompt("Enter n:"));
  for (var i = m; i <= n; i++) {
    document.write('<br>' + i);
  }
</script>
</body>
</html>
```

---

## PRACTICAL 4C: Numbers from m to n with a Jump of 3

```html
<!DOCTYPE html>
<html>
<body>
<script>
  document.write('Using for Loop');
  var m = parseInt(prompt("Enter m:"));
  var n = parseInt(prompt("Enter n:"));
  for (var i = m; i <= n; i += 3) {
    document.write('<br>' + i);
  }
</script>
</body>
</html>
```

---

## PRACTICAL 4D: Numbers m to n in Descending Order

```html
<!DOCTYPE html>
<html>
<body>
<script>
  document.write('Using for Loop');
  var m = parseInt(prompt("Enter m:"));
  var n = parseInt(prompt("Enter n:"));
  for (var i = m; i >= n; i--) {
    document.write('<br>' + i);
  }
</script>
</body>
</html>
```

---

## PRACTICAL 4E: Print Even Numbers from m to n

```html
<!DOCTYPE html>
<html>
<body>
<script>
  var m = parseInt(prompt("Enter m:"));
  var n = parseInt(prompt("Enter n:"));
  for (var i = m; i < n; i++) {
    if (i % 2 == 0) {
      document.write('<br>' + i);
    }
  }
</script>
</body>
</html>
```

---

## PRACTICAL 4F: Multiplication Table

```html
<!DOCTYPE html>
<html>
<body>
<script>
  var m = parseInt(prompt("Enter m"));
  for (var i = 1; i <= 10; i++) {
    document.write('<br>' + m + ' x ' + i + ' = ' + (m * i));
  }
</script>
</body>
</html>
```

---

*All code examples have been formatted, and syntax errors have been corrected.*
