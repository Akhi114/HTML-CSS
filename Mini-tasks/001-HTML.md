# [Guvi Zen](https://www.guvi.io/zen/)

## HTML Task to know usage of basic tags.

1. Fix the bugs in below snippet

```HTML
    <html lang="en">
    <head>
        <title>Document guvi</title>
    </head>

    <body>
        <div>
            Lorem ipsum dolor sit amet consectetur adipisicing elit.
        </div>
        <div>
            Guvi Geek Network
        </div>
    </body>
    </html>
```
2. Try the below one

```HTML
<html lang="en">
    <head>
        <title>Document guvi</title>
    </head>

    <body>
        <div>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
        </div>
        <div>
            Guvi Geek Network
        </div>
    </body>
</html>
```

---

3. Design a contact us form with all fields as required.
```HTML
<html lang="en">
<head>
    <title>Contact Us</title>
</head>
<body>

    <h2>Contact Us</h2>
    <form>
        <label for="name">Full Name:</label>
        <input type="text" id="name" name="name" required><br><br>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required><br><br>

        <label for="subject">Subject:</label>
        <input type="text" id="subject" name="subject" required><br><br>

        <label for="message">Message:</label><br>
        <textarea id="message" name="message" rows="5" required></textarea><br><br>
        <input type="submit" value="Submit">
    </form>
</body>
</html>
```

---

4. Use certain HTML elements to display the following in a HTML page.

- Programming Language
  - JavaScript
    1. Angular
    2. React
    3. Vue.js
  - Python
    1. Django Framework
    2. Flask Framework
  - Java
    1. Spring
    2. Maven
    3. Hibernate
- Database
  - MySQL
  - MongoDB
  - Cansandra

```HTML
<html lang="en">
<head>
    <title>Programming & Database</title>
</head>
<body>

    <h2>Programming Language</h2>
    <ul>
        <li><h3>JavaScript</h3>
            <ol>
                <li>Angular</li>
                <li>React</li>
                <li>Vue.js</li>
            </ol>
        </li>
        <li><h3>Python</h3>
            <ol>
                <li>Django Framework</li>
                <li>Flask Framework</li>
            </ol>
        </li>
        <li><h3>Java</h3>
            <ol>
                <li>Spring</li>
                <li>Maven</li>
                <li>Hibernate</li>
            </ol>
        </li>
    </ul>

    <h2>Database</h2>
    <ul>
        <li>MySQL</li>
        <li>MongoDB</li>
        <li>Cassandra</li>
    </ul>

</body>
</html>
```
---

5. Create an element that helps you to open the https://google.com in separate new tab.
```HTML
<html lang="en">
<body>
    <h2>Opening google in new tab</h2>
    <a href="https://google.com" target="_blank">Click here to search on Google</a>
</body>
</html>
```
---

6. In the form, add two radio buttons with grouping them for employee type(Salaried and own business)
```HTML
<html lang="en">
<head>
    <title>Contact Us</title>
</head>
<body>

    <h2>Employee type!</h2>
    <form action="submit_form.php" method="post">
        <label>Employee Type:</label><br>
        <input type="radio" id="salaried" name="employee_type" value="Salaried" required>
        <label for="salaried">Salaried</label><br>

        <input type="radio" id="own_business" name="employee_type" value="Own Business" required>
        <label for="own_business">Own Business</label><br><br>

        <input type="submit" value="Submit">
    </form>
</body>
</html>
```
---

7. Design form shown in the link (http://evc-cit.info/cit040/formguide/card_0.png)
 ---> The form is not shown in the link, it seems server is been shut!
---

8. Use the table tag to design given image [Click here](https://www.bapugraphics.com/assets/img/port_upload_dir/table-4.jpg).

 ---> This image is also not shown here!

---

9. Write HTML input tags snippet to show default values for all Form elements.
```HTML
<html lang="en">
<body>
    <form>
    
        <!-- Text Input! -->
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" value="John Doe"><br><br>
    
        <!-- Email Input! -->
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" value="john.doe@example.com"><br><br>
    
        <!-- Password Input! -->
        <label for="password">Password:</label>
        <input type="password" id="password" name="password" value="defaultpassword"><br><br>
    
        <!-- Number Input! -->
        <label for="age">Age:</label>
        <input type="number" id="age" name="age" value="25"><br><br>
    
        <!-- Date Input! -->
        <label for="dob">Date of Birth:</label>
        <input type="date" id="dob" name="dob" value="2000-01-01"><br><br>
    
        <!-- Radio Buttons! -->
        <label>Gender:</label>
        <input type="radio" id="male" name="gender" value="Male" checked>
        <label for="male">Male</label>
        <input type="radio" id="female" name="gender" value="Female">
        <label for="female">Female</label><br><br>
    
        <!-- Checkbox! -->
        <label>Interests:</label>
        <input type="checkbox" id="coding" name="interests" value="Coding" checked>
        <label for="coding">Coding</label>
        <input type="checkbox" id="music" name="interests" value="Music">
        <label for="music">Music</label><br><br>
    
        <!-- Dropdown! (Select) -->
        <label for="country">Country:</label>
        <select id="country" name="country">
            <option value="USA" selected>USA</option>
            <option value="UK">UK</option>
            <option value="Canada">Canada</option>
        </select><br><br>
    
        <!-- Textarea! -->
        <label for="message">Message:</label><br>
        <textarea id="message" name="message" rows="4" cols="30">Hello, this is a default message.</textarea><br><br>
    
        <!-- File Input! -->
        <label for="file">Upload File:</label>
        <input type="file" id="file" name="file"><br><br>
    
        <!-- Submit Button! -->
        <input type="submit" value="Submit">
    </form>
</body>
</html>
```
---

10. In your, HTML page add the below line and Highlight it without using any CSS.

- "HTML & CSS is awesome"
```HTML
<html lang="en">
<head>
    <title>Highlight without CSS</title>
</head>
<body>

    <p><mark>HTML & CSS is awesome</mark></p>

</body>
</html>
```
---

11. Create an HTML page, which should contain all types of input elements.
```HTML
<html lang="en">
<head>
    <title>All Input Elements</title>
</head>
<body>

    <h2>All Input Elements using Form!</h2>
    <form action="submit_form.php" method="post">

        <!-- Text Input! -->
        <label for="text">Text:</label>
        <input type="text" id="text" name="text" placeholder="Enter text"><br><br>

        <!-- Password Input! -->
        <label for="password">Password:</label>
        <input type="password" id="password" name="password"><br><br>

        <!-- Email Input! -->
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" placeholder="example@mail.com"><br><br>

        <!-- Number Input! -->
        <label for="number">Number:</label>
        <input type="number" id="number" name="number" min="1" max="100"><br><br>

        <!-- Date Input! -->
        <label for="date">Date:</label>
        <input type="date" id="date" name="date"><br><br>

        <!-- Time Input! -->
        <label for="time">Time:</label>
        <input type="time" id="time" name="time"><br><br>

        <!-- Date-Time Input! -->
        <label for="datetime">Date-Time:</label>
        <input type="datetime-local" id="datetime" name="datetime"><br><br>

        <!-- Color Picker! -->
        <label for="color">Pick a Color:</label>
        <input type="color" id="color" name="color"><br><br>

        <!-- File Input! -->
        <label for="file">Upload File:</label>
        <input type="file" id="file" name="file"><br><br>

        <!-- Radio Buttons! -->
        <label>Gender:</label>
        <input type="radio" id="male" name="gender" value="Male">
        <label for="male">Male</label>
        <input type="radio" id="female" name="gender" value="Female">
        <label for="female">Female</label><br><br>

        <!-- Checkboxes! -->
        <label>Interests:</label>
        <input type="checkbox" id="coding" name="interest" value="Coding">
        <label for="coding">Coding</label>
        <input type="checkbox" id="music" name="interest" value="Music">
        <label for="music">Music</label><br><br>

        <!-- Dropdown! (Select) -->
        <label for="country">Country:</label>
        <select id="country" name="country">
            <option value="USA">USA</option>
            <option value="UK">UK</option>
            <option value="India">India</option>
        </select><br><br>

        <!-- Textarea! -->
        <label for="message">Message:</label><br>
        <textarea id="message" name="message" rows="4" cols="30"></textarea><br><br>

        <!-- Range Slider! -->
        <label for="range">Range:</label>
        <input type="range" id="range" name="range" min="0" max="100"><br><br>

        <!-- Search Input! -->
        <label for="search">Search:</label>
        <input type="search" id="search" name="search"><br><br>

        <!-- URL Input! -->
        <label for="url">Website:</label>
        <input type="url" id="url" name="url" placeholder="https://example.com"><br><br>

        <!-- Telephone Input! -->
        <label for="tel">Phone Number:</label>
        <input type="tel" id="tel" name="tel" placeholder="123-456-7890"><br><br>

        <!-- Hidden Input! -->
        <input type="hidden" name="hidden_value" value="12345">

        <!-- Buttons! -->
        <input type="submit" value="Submit">
        <input type="reset" value="Reset">
        <button type="button" onclick="alert('Button Clicked!')">Click Me</button>

    </form>

</body>
</html>

```
