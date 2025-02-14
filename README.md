# this is for html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FORM</title>
</head>
<body>
    <!-- section-1: Student form -->
    <section id="student-form">
        <h1 style="text-align: center;"><u>Hey Welcome to student portal!<br><strong>Sign up here.</strong></u></h1>
        <form style="text-align: center;" action="project2.html" method="get">
            <h2><u>STUDENT FORM:</u></h2>
            <table style="margin: auto; border-collapse: collapse;" border="1">
                <tr>
                    <td>
                        <h3>Enter Name:</h3>
                        <input type="text" placeholder="Type username here" required><br><br>
                        <h3>Enter DOB:</h3>
                        <input type="date" placeholder="Select DOB"><br><br>
                        <h3>Enter Password:</h3>
                        <input type="password" placeholder="Type password here"><br><br>
                        <h3>Select Class:</h3>
                        <label for="01">
                            <input type="radio" value="class XI" name="class" id="01"><span style="color: rgb(255, 0, 0);">Class XI</span>
                        </label>
                        <label for="02">
                            <input  type="radio" value="class XII" name="class" id="02"><span style="color:rgb(255, 0, 0);">Class XII</span>
                        </label>
                        <h3>Select Subjects:</h3>
                        <label for="1">
                            <input type="checkbox" value="Maths" name="subject" id="1"><span style="color: rgb(8, 0, 255);">Maths</span>
                        </label>
                        <label for="2">
                            <input type="checkbox" value="English" name="subject" id="2"><span style="color: rgb(8, 0, 255);">English</span>
                        </label>
                        <label for="3">
                            <input type="checkbox" value="Science" name="subject" id="3"><span style="color: rgb(8, 0, 255);">Science</span>
                        </label>
                        <label for="4">
                            <input type="checkbox" value="Computer" name="subject" id="4"><span style="color: rgb(8, 0, 255);">Computer</span>
                        </label>
                        <label for="5">
                            <input type="checkbox" value="Physical" name="subject" id="5"><span style="color: rgb(8, 0, 255);">Physical</span>
                        </label>
                    </td>
                </tr>
            </table>
            <h3>Press the button below to submit the form</h3>
            <button type="submit">Submit</button>
        </form>
    </section>
    <hr> 
</body>
</html>

<!-- project-1 -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Submit</title>
</head>
<body>
    <!-- section-2: Form submission -->
    <h1>Thanks for submission of form.</h1>
    <strong>To continue further , click on the button below.</strong><br><br>
    <a href="project2.html">Continue</a><br><br>
    <strong>Navigate back to home page.</strong><br><br>
    <a href="project.html">Home</a>
    <hr>
</body>
</html>

<!-- project-2 -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Study</title>
</head>
<body>
    <!-- section-3: Studyhub -->
    <h1><U>Welcome to study hub!</U></h1>
    <h2>As per your needs navigate accordingly.</h2>
    <table border="1">
        <tr>
            <th>Sno.</th>
            <th>Subject</th>
            <th>Links</th>
        </tr>
        <tr>
            <td>1</td>
            <td>Maths</td>
            <td><a href=""></a></td>
        </tr>
        <tr>
            <td>2</td>
            <td>English</td>
            <td><a href=""></a></td>
        </tr>
        <tr>
            <td>3</td>
            <td>Science</td>
            <td><a href=""></a></td>
        </tr>
        <tr>
            <td>4</td>
            <td>Computer Science</td>
            <td><a href=""></a></td>
        </tr>
        <tr>
            <td>5</td>
            <td>Physical</td>
            <td><a href=""></a></td>
        </tr>
        </table>
        
        <h2>For Study Material:</h2>
        <strong style="background-color: rgba(118, 240, 42, 0.67);">Flipkart</strong>
        <iframe src="https://www.flipkart.com/" width="500" height="300">flipkart</iframe>
        <br><br><br>
        <strong style="background-color: rgba(118, 240, 42, 0.67);">Openstax</strong>
        <iframe src="https://openstax.org/" width="500" height="300"title="Openstax Educational resources"></iframe>
        
        <h2>For video lectures</h2>
        <strong style="background-color: rgba(118, 240, 42, 0.67);">For class X:</strong>
        <a href="https://www.youtube.com/@PW-Foundation" target="_blank">Vist to Phyics Wallah channel</a><br><br>
        <strong style="background-color: rgba(118, 240, 42, 0.67);">For class XII</strong>
        <a href="https://www.youtube.com/@NCERTWallahPW" target="_blank">Visit to Phyics Wallah channel</a><br><br>
        <strong>Navigate back to home page.</strong><br><br>
        <a href="project.html">Home</a>
    <hr>
</body>
</html>