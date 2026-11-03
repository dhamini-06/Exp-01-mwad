# Ex01 Portfolio
## Date:03-11-2026

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
index.html
```

<!DOCTYPE html>
<html>
<head>
    <title>Dhamini S | Portfolio</title>
</head>

<body bgcolor="white" text="#333333">

    <table width="100%" bgcolor="#17365D" cellpadding="20">
        <tr>
            <td>
                <h1><font color="white">DHAMINI S</font></h1>
                <font color="white">Personal Portfolio</font>
            </td>
            <td align="right">
                <a href="index.html"><font color="white">Home</font></a> |
                <a href="about.html"><font color="white">About</font></a> |
                <a href="skills.html"><font color="white">Skills</font></a> |
                <a href="projects.html"><font color="white">Projects</font></a> |
                <a href="contact.html"><font color="white">Contact</font></a>
            </td>
        </tr>
    </table>

    <br><br>

    <table width="85%" align="center" cellpadding="20">
        <tr>
            <td width="35%" align="center" bgcolor="#EAF1F8">
                <img src="c:\Users\admin\Desktop\dhamini.png"
                     width="180" height="180"
                     alt="Dhamini's Photo">

                <h2>Dhamini S</h2>
                <p>Engineering Student</p>
                <p>Programmer | ML Enthusiast</p>
            </td>

            <td width="65%" valign="middle">
                <h1>Hello, Welcome to My Portfolio!</h1>

                <h3>
                    <font color="#17365D">
                        Aspiring Developer and Technology Enthusiast
                    </font>
                </h3>

                <p>
                    I am passionate about programming, Artificial
                    Intelligence, and Machine Learning. I enjoy
                    developing creative projects and learning
                    new technologies.
                </p>

                <p>
                    My aim is to develop technical skills and
                    build innovative solutions for real-world problems.
                </p>

                <br>

                <a href="about.html">Explore More About Me</a>
            </td>
        </tr>
    </table>

    <br><br>

    <center>
        <h2><font color="#17365D">Welcome to My Digital Space</font></h2>
        <p>Explore my skills, projects and achievements.</p>
    </center>

    <br><br>

    <table width="100%" bgcolor="#17365D" cellpadding="15">
        <tr>
            <td align="center">
                <font color="white">
                    © 2026 Dhamini S | All Rights Reserved
                </font>
            </td>
        </tr>
    </table>

</body>
</html>
```

 about.html

 ```
 
<!DOCTYPE html>
<html>
<head>
    <title>About | Dhamini S</title>
</head>

<body bgcolor="white" text="#333333">

    <table width="100%" bgcolor="#17365D" cellpadding="20">
        <tr>
            <td><h2><font color="white">DHAMINI S</font></h2></td>
            <td align="right">
                <a href="index.html"><font color="white">Home</font></a> |
                <a href="about.html"><font color="white">About</font></a> |
                <a href="skills.html"><font color="white">Skills</font></a> |
                <a href="projects.html"><font color="white">Projects</font></a> |
                <a href="contact.html"><font color="white">Contact</font></a>
            </td>
        </tr>
    </table>

    <br><br>

    <center>
        <h1><font color="#17365D">About Me</font></h1>
    </center>

    <table width="80%" align="center" cellpadding="25"
           bgcolor="#EAF1F8">
        <tr>
            <td>
                <h2>Who Am I?</h2>

                <p>
                    I am Dhamini S, an engineering student at
                    Saveetha Engineering College.
                </p>

                <p>
                    I have an interest in programming, web development,
                    Artificial Intelligence and Machine Learning.
                </p>

                <p>
                    I enjoy building practical projects, analysing
                    data and exploring emerging technologies.
                    I continuously work on improving my technical
                    knowledge and problem-solving abilities.
                </p>

                <h3>My Career Goal</h3>

                <p>
                    My goal is to become a skilled technology
                    professional and develop innovative solutions
                    that make a positive difference.
                </p>
            </td>
        </tr>
    </table>

    <br><br>

    <center>
        <a href="index.html">Back to Home</a>
    </center>

    <br>

    <center>
        © 2026 Dhamini S | All Rights Reserved
    </center>

</body>
</html>

```

skills.html

```

<!DOCTYPE html>
<html>
<head>
    <title>Skills | Dhamini S</title>
</head>

<body bgcolor="white" text="#333333">

    <table width="100%" bgcolor="#17365D" cellpadding="20">
        <tr>
            <td><h2><font color="white">DHAMINI S</font></h2></td>
            <td align="right">
                <a href="index.html"><font color="white">Home</font></a> |
                <a href="about.html"><font color="white">About</font></a> |
                <a href="skills.html"><font color="white">Skills</font></a> |
                <a href="projects.html"><font color="white">Projects</font></a> |
                <a href="contact.html"><font color="white">Contact</font></a>
            </td>
        </tr>
    </table>

    <br><br>

    <center>
        <h1><font color="#17365D">Technical Skills</font></h1>
        <p>My technical knowledge and abilities</p>
    </center>

    <br>

    <table width="75%" align="center" cellpadding="20"
           cellspacing="5">

        <tr bgcolor="#EAF1F8">
            <td align="center">
                <h3>Programming</h3>
                Python
                <br>
                Java
            </td>

            <td align="center">
                <h3>Web Technologies</h3>
                HTML
                <br>
                Web Development
            </td>
        </tr>

        <tr bgcolor="#F4F4F4">
            <td align="center">
                <h3>Database</h3>
                SQL
            </td>

            <td align="center">
                <h3>Technical Knowledge</h3>
                Machine Learning
                <br>
                Data Analysis
            </td>
        </tr>

        <tr bgcolor="#EAF1F8">
            <td colspan="2" align="center">
                <h3>Other Skills</h3>
                Problem Solving
            </td>
        </tr>

    </table>

    <br><br>

    <center>
        <a href="index.html">Back to Home</a>
        <p>© 2026 Dhamini S | All Rights Reserved</p>
    </center>

</body>
</html>

```

projects.html

```

<!DOCTYPE html>
<html>
<head>
    <title>Projects | Dhamini S</title>
</head>

<body bgcolor="white" text="#333333">

    <table width="100%" bgcolor="#17365D" cellpadding="20">
        <tr>
            <td><h2><font color="white">DHAMINI S</font></h2></td>
            <td align="right">
                <a href="index.html"><font color="white">Home</font></a> |
                <a href="about.html"><font color="white">About</font></a> |
                <a href="skills.html"><font color="white">Skills</font></a> |
                <a href="projects.html"><font color="white">Projects</font></a> |
                <a href="contact.html"><font color="white">Contact</font></a>
            </td>
        </tr>
    </table>

    <br><br>

    <center>
        <h1><font color="#17365D">My Projects</font></h1>
        <p>Some of my academic and personal projects</p>
    </center>

    <br>

    <table width="85%" align="center" cellpadding="20"
           cellspacing="8">

        <tr bgcolor="#EAF1F8">
            <td width="25%">
                <h2><font color="#17365D">01</font></h2>
            </td>
            <td>
                <h2>Community Recovery Hub</h2>
                <p>
                    A disaster relief management application designed
                    to organise disaster reports, relief requests,
                    volunteers, NGOs and resource distribution.
                </p>
            </td>
        </tr>

        <tr bgcolor="#F4F4F4">
            <td>
                <h2><font color="#17365D">02</font></h2>
            </td>
            <td>
                <h2>AquaSentinel</h2>
                <p>
                    A smart water monitoring project that analyses
                    flow, pressure and usage data to identify
                    possible leaks and reduce water wastage.
                </p>
            </td>
        </tr>

        <tr bgcolor="#EAF1F8">
            <td>
                <h2><font color="#17365D">03</font></h2>
            </td>
            <td>
                <h2>Personal Portfolio</h2>
                <p>
                    A personal website showcasing my background,
                    skills, projects and interests using HTML.
                </p>
            </td>
        </tr>

    </table>

    <br><br>

    <center>
        <a href="index.html">Back to Home</a>
        <p>© 2026 Dhamini S | All Rights Reserved</p>
    </center>

</body>
</html>
```

contact.html

```

<!DOCTYPE html>
<html>
<head>
    <title>Contact | Dhamini S</title>
</head>

<body bgcolor="white" text="#333333">

    <table width="100%" bgcolor="#17365D" cellpadding="20">
        <tr>
            <td><h2><font color="white">DHAMINI S</font></h2></td>
            <td align="right">
                <a href="index.html"><font color="white">Home</font></a> |
                <a href="about.html"><font color="white">About</font></a> |
                <a href="skills.html"><font color="white">Skills</font></a> |
                <a href="projects.html"><font color="white">Projects</font></a> |
                <a href="contact.html"><font color="white">Contact</font></a>
            </td>
        </tr>
    </table>

    <br><br>

    <center>
        <h1><font color="#17365D">Get In Touch</font></h1>
        <p>Feel free to contact me for opportunities and collaboration.</p>
    </center>

    <br>

    <table width="65%" align="center" bgcolor="#EAF1F8"
           cellpadding="25">

        <tr>
            <td align="center">

                <h2>Contact Information</h2>

                <p><b>Name:</b> Dhamini S</p>

                <p>
                    <b>College:</b>
                    Saveetha Engineering College
                </p>

                <p>
                    <b>GitHub:</b>
                    <a href="https://github.com/divya0610m">
                        GitHub Profile
                    </a>
                </p>

                <p>
                    <b>Email:</b>
                    <a href="mailto:dhaminisubramani@gmail.com">
                        dhaminisubramani@gmail.com
                    </a>
                </p>

            </td>
        </tr>

    </table>

    <br><br>

    <center>
        <a href="index.html">Back to Home</a>
        <p>© 2026 Dhamini S | All Rights Reserved</p>
    </center>

</body>
</html>
```

## OUTPUT

![alt text](1.png)

![alt text](2.png) 

![alt text](3.png)

![alt text](4.png) 

![alt text](5.png)

## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.