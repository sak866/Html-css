# Html-css
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Document</title>
</head>
<body>
    guvi
    <div>
        Lorem ipsum dolor sit amet consectetur adipisicing elit.
        <div>
            <div>
                Guvi Geek Network
            </div>
        </div>
    </div>
</body>
</html>
2. Try the below one

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Document</title>
</head>
<body>
    guvi
    <div>
        Lorem ipsum dolor sit amet consectetur adipisicing elit.
        <div>
            <div>
                Guvi Geek Network
            </div>
        </div>
    </div>
</body>
</html>
3. Design a contact us form with all fields as required.

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Contact Us</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: #f2f2f2;
            padding: 20px;
        }

        .contact-form {
            background: #fff;
            padding: 30px;
            max-width: 500px;
            margin: auto;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }

        .contact-form h2 {
            margin-bottom: 20px;
        }

        .contact-form label {
            display: block;
            margin-top: 10px;
            margin-bottom: 5px;
            font-weight: bold;
        }

        .contact-form input,
        .contact-form textarea {
            width: 100%;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }

        .contact-form textarea {
            resize: vertical;
            height: 120px;
        }

        .contact-form button {
            margin-top: 15px;
            padding: 10px 20px;
            background-color: #28a745;
            border: none;
            color: white;
            font-size: 16px;
            border-radius: 4px;
            cursor: pointer;
        }

        .contact-form button:hover {
            background-color: #218838;
        }
    </style>
</head>
<body>

<div class="contact-form">
    <h2>Contact Us</h2>
    <form action="#" method="POST">
        <label for="name">Full Name *</label>
        <input type="text" id="name" name="name" required>

        <label for="email">Email Address *</label>
        <input type="email" id="email" name="email" required>

        <label for="phone">Phone Number *</label>
        <input type="tel" id="phone" name="phone" required>

        <label for="subject">Subject *</label>
        <input type="text" id="subject" name="subject" required>

        <label for="message">Message *</label>
        <textarea id="message" name="message" required></textarea>

        <button type="submit">Send Message</button>
    </form>
</div>

</body>
</html>
4. Use certain HTML elements to display the following in a HTML page.

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Technology Stack</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            padding: 20px;
        }

        h1 {
            color: #2c3e50;
        }

        h2 {
            color: #34495e;
        }

        ul {
            margin-bottom: 20px;
        }

        li {
            margin-left: 20px;
        }
    </style>
</head>
<body>

    <h1>Technology Stack</h1>

    <h2>Programming Languages</h2>
    <ul>
        <li>JavaScript
            <ul>
                <li>Angular</li>
                <li>React</li>
                <li>Vue.js</li>
            </ul>
        </li>
        <li>Python
            <ul>
                <li>Django Framework</li>
                <li>Flask Framework</li>
            </ul>
        </li>
        <li>Java
            <ul>
                <li>Spring</li>
                <li>Maven</li>
                <li>Hibernate</li>
            </ul>
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
5. Create an element that helps you to open the https://google.com in separate new tab

<a href="https://google.com" target="_blank">Open Google</a>
6. In the form, add two radio buttons with grouping them for employee type(Salaried and own business)

<form action="#" method="POST">
    <!-- Existing fields like Name, Email, etc. -->

    <label for="employee-type">Employee Type *</label><br>
    <input type="radio" id="salaried" name="employee_type" value="salaried" required>
    <label for="salaried">Salaried</label><br>

    <input type="radio" id="own-business" name="employee_type" value="own_business" required>
    <label for="own-business">Own Business</label><br><br>

    <!-- Other fields like Subject, Message, etc. -->
    <button type="submit">Send Message</button>
</form>
7. Design form shown in the link (http://evccit.info/cit040/formguide/card_0.png)

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Form</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        .form-container {
            width: 100%;
            max-width: 600px;
            margin: 50px auto;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            padding: 20px;
        }
        .form-header {
            text-align: center;
            margin-bottom: 20px;
        }
        .form-header h2 {
            margin: 0;
            font-size: 24px;
            color: #333;
        }
        .form-header p {
            font-size: 14px;
            color: #777;
        }
        .form-body {
            display: flex;
            flex-direction: column;
        }
        .form-body label {
            font-size: 14px;
            color: #555;
            margin-bottom: 5px;
        }
        .form-body input,
        .form-body textarea {
            padding: 10px;
            font-size: 14px;
            border: 1px solid #ddd;
            border-radius: 4px;
            margin-bottom: 15px;
        }
        .form-body input[type="radio"] {
            width: auto;
            margin-right: 5px;
        }
        .form-footer {
            text-align: center;
        }
        .form-footer button {
            padding: 10px 20px;
            font-size: 16px;
            background-color: #28a745;
            color: #fff;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }
        .form-footer button:hover {
            background-color: #218838;
        }
    </style>
</head>
<body>

<div class="form-container">
    <div class="form-header">
        <h2>Contact Us</h2>
        <p>We'd love to hear from you!</p>
    </div>
    <form class="form-body">
        <label for="name">Full Name *</label>
        <input type="text" id="name" name="name" required>

        <label for="email">Email Address *</label>
        <input type="email" id="email" name="email" required>

        <label for="phone">Phone Number *</label>
        <input type="tel" id="phone" name="phone" required>

        <label for="subject">Subject *</label>
        <input type="text" id="subject" name="subject" required>

        <label for="message">Message *</label>
        <textarea id="message" name="message" required></textarea>

        <label>Employee Type *</label>
        <input type="radio" id="salaried" name="employee_type" value="salaried" required>
        <label for="salaried">Salaried</label>
        <input type="radio" id="own_business" name="employee_type" value="own_business" required>
        <label for="own_business">Own Business</label>

        <div class="form-footer">
            <button type="submit">Send Message</button>
        </div>
    </form>
</div>

</body>
</html>
8. Use the table tag to design given image Click here.

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Form</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            padding: 20px;
        }
        .form-container {
            width: 60%;
            margin: 0 auto;
            background-color: #fff;
            border-radius: 8px;
            padding: 20px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        table {
            width: 100%;
            border-collapse: collapse;
        }
        td {
            padding: 10px;
        }
        label {
            font-size: 14px;
            color: #555;
        }
        input[type="text"],
        input[type="email"],
        input[type="tel"],
        textarea {
            width: 100%;
            padding: 10px;
            font-size: 14px;
            border: 1px solid #ddd;
            border-radius: 4px;
        }
        input[type="radio"] {
            width: auto;
            margin-right: 5px;
        }
        button {
            padding: 10px 20px;
            background-color: #28a745;
            color: #fff;
            font-size: 16px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            margin-top: 20px;
        }
        button:hover {
            background-color: #218838;
        }
    </style>
</head>
<body>

<div class="form-container">
    <h2 style="text-align: center;">Contact Us</h2>
    <form action="#" method="POST">
        <table>
            <tr>
                <td><label for="name">Full Name *</label></td>
                <td><input type="text" id="name" name="name" required></td>
            </tr>
            <tr>
                <td><label for="email">Email Address *</label></td>
                <td><input type="email" id="email" name="email" required></td>
            </tr>
            <tr>
                <td><label for="phone">Phone Number *</label></td>
                <td><input type="tel" id="phone" name="phone" required></td>
            </tr>
            <tr>
                <td><label for="subject">Subject *</label></td>
                <td><input type="text" id="subject" name="subject" required></td>
            </tr>
            <tr>
                <td><label for="message">Message *</label></td>
                <td><textarea id="message" name="message" required></textarea></td>
            </tr>
            <tr>
                <td><label>Employee Type *</label></td>
                <td>
                    <input type="radio" id="salaried" name="employee_type" value="salaried" required>
                    <label for="salaried">Salaried</label>
                    <input type="radio" id="own_business" name="employee_type" value="own_business" required>
                    <label for="own_business">Own Business</label>
                </td>
            </tr>
        </table>
        <button type="submit">Send Message</button>
    </form>
</div>

</body>
</html>
9. Write HTML input tags snippet to show default values for all Form elements.

<form action="#" method="POST">
    <label for="name">Full Name *</label>
    <input type="text" id="name" name="name" value="John Doe" required><br><br>

    <label for="email">Email Address *</label>
    <input type="email" id="email" name="email" value="john.doe@example.com" required><br><br>

    <label for="phone">Phone Number *</label>
    <input type="tel" id="phone" name="phone" value="+1234567890" required><br><br>

    <label for="subject">Subject *</label>
    <input type="text" id="subject" name="subject" value="General Inquiry" required><br><br>

    <label for="message">Message *</label><br>
    <textarea id="message" name="message" required>I'd like to inquire about your services.</textarea><br><br>

    <label>Employee Type *</label><br>
    <input type="radio" id="salaried" name="employee_type" value="salaried" checked>
    <label for="salaried">Salaried</label>
    <input type="radio" id="own_business" name="employee_type" value="own_business">
    <label for="own_business">Own Business</label><br><br>

    <label for="newsletter">Subscribe to Newsletter</label>
    <input type="checkbox" id="newsletter" name="newsletter" checked><br><br>

    <label for="dob">Date of Birth *</label>
    <input type="date" id="dob" name="dob" value="1990-01-01" required><br><br>

    <label for="city">City</label>
    <input type="text" id="city" name="city" value="New York"><br><br>

    <button type="submit">Send Message</button>
</form>
11. In your, HTML page add the below line and Highlight it without using any CSS.

“HTML & CSS is awesome”
<form action="#" method="POST">
    <!-- Other form elements -->

    <p><strong>HTML & CSS is awesome</strong></p>

    <!-- Other form elements -->
</form>
12. Create an HTML page, which should contain all types of input elements.

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Form with All Input Elements</title>
</head>
<body>

<h1>Form with All Input Elements</h1>

<form action="#" method="POST">

    <!-- Text Input -->
    <label for="text">Text Input</label><br>
    <input type="text" id="text" name="text" placeholder="Enter your name"><br><br>

    <!-- Password Input -->
    <label for="password">Password Input</label><br>
    <input type="password" id="password" name="password" placeholder="Enter your password"><br><br>

    <!-- Email Input -->
    <label for="email">Email Input</label><br>
    <input type="email" id="email" name="email" placeholder="Enter your email"><br><br>

    <!-- Number Input -->
    <label for="number">Number Input</label><br>
    <input type="number" id="number" name="number" min="1" max="100" placeholder="Enter a number"><br><br>

    <!-- Telephone Input -->
    <label for="tel">Telephone Input</label><br>
    <input type="tel" id="tel" name="tel" placeholder="Enter your phone number"><br><br>

    <!-- Date Input -->
    <label for="date">Date Input</label><br>
    <input type="date" id="date" name="date"><br><br>

    <!-- Time Input -->
    <label for="time">Time Input</label><br>
    <input type="time" id="time" name="time"><br><br>

    <!-- File Input -->
    <label for="file">File Input</label><br>
    <input type="file" id="file" name="file"><br><br>

    <!-- Checkbox Input -->
    <label for="subscribe">Subscribe to newsletter</label><br>
    <input type="checkbox" id="subscribe" name="subscribe" value="yes"><br><br>

    <!-- Radio Button Input -->
    <label for="gender">Gender</label><br>
    <input type="radio" id="male" name="gender" value="male"> Male
    <input type="radio" id="female" name="gender" value="female"> Female<br><br>

    <!-- Range Input -->
    <label for="range">Range Input (1-10)</label><br>
    <input type="range" id="range" name="range" min="1" max="10"><br><br>

    <!-- Color Input -->
    <label for="color">Color Input</label><br>
    <input type="color" id="color" name="color"><br><br>

    <!-- URL Input -->
    <label for="url">URL Input</label><br>
    <input type="url" id="url" name="url" placeholder="Enter a website URL"><br><br>

    <!-- Search Input -->
    <label for="search">Search Input</label><br>
    <input type="search" id="search" name="search" placeholder="Search..."><br><br>

    <!-- Textarea -->
    <label for="message">Message</label><br>
    <textarea id="message" name="message" rows="4" cols="50" placeholder="Enter your message"></textarea><br><br>

    <!-- Submit Button -->
    <button type="submit">Submit</button>

</form>

</body>
</html>


