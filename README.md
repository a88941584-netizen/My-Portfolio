<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My portfolio</title>
    <style>
        body {
            font-family: Georgia, 'Times New Roman', Times, serif;
            margin: 0;
            padding: 0;
            background-color: #FFF8F0;
        }

        h1 {
            position: sticky;
            top: 0px;
            background-color: #ffc0cb;
            margin: 0;
            padding: 0;
            color: rgb(73, 50, 206);
            font-weight: bold;
        }

        img {
            border-radius: 200px;
            height: 80px;
        }


        /* navbar */

        nav ul {
            font-weight: bold;
            background-color: black;
            box-sizing: border-box;
            display: flex;
            justify-content: center;
            list-style: none;
            margin: 0;
            padding: 0;


        }

        nav li {
            box-sizing: border-box;
            padding: 18px;
            margin: 12px;
        }

        /* designs of anchor tag */
        a {
            color: purple;
        }

        a:hover {
            color: pink;
            text-decoration: underline;
        }

        a:visited {
            color: rgb(122, 216, 135);
        }

        /* heading styles */
        h2 {
            font-weight: bold;
            color: rgb(73, 50, 206);
            background-color: pink;
        }

        h3 {
            color: rgb(73, 50, 206);
            background-color: rgb(242, 165, 178);
        }

        /* 2nd ul */
        main>ul {
            list-style-type: square;
        }

        main>ul>li {
            border: 3px solid rgb(73, 50, 206);
            list-style-type: square;
            padding: 10px;
        }

        /* table */
        table {
            border: 3px solid rgb(73, 50, 206);
        }

        th,
        td {
            padding: 10px;
            border: 3px solid rgb(73, 50, 206);
        }



        .container {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }

        .me {
            background-color: pink;
            color: rgb(5, 4, 10);
            padding: 15px;
            border: 3px solid rgb(73, 50, 206);
            border-radius: 10px;
            text-align: center;
            flex: 1 1 250px;
        }

        .me:hover {
            transform: translateY(-5px);
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
            transition: all 0.3s ease;
        }

        form {
            background-color: pink;
            padding: 20px;
            box-shadow: 0 0 5px rgba(0, 0, 0, 0.2);
        }

        input,
        textarea {
            padding: 30px;
            width: 100%;
            margin-bottom: 15px;
            border-radius: 5px;
            border: 1px solid #ccc;
        }

        button {
            padding: 10px 20px;
            background-color: rgb(73, 50, 206);
            color: pink;
            cursor: pointer;
            border-radius: 5px;
        }

        footer {
            background-color: pink;
            color: rgb(73, 50, 206);
            padding: 0px 20px;
            text-align: center;
        }

        
           
        @media (max-width: 768px) {
            h1 {
                font-size: 3rem;
            }

            nav ul {
                flex-direction: column;
                align-items: center;
            }

            .container {
                flex-direction: column;
                align-items: center;
            }
        }

        @media (max-width: 480px) {
            h1 {
                font-size: 2.2rem;
            }

            .me {
                flex: 1 1 100%;
                min-width: 100%;
            }

            table,
            th,
            td {
                font-size: 0.9rem;
            }
        }
    </style>
</head>

<body>
    <header>
        <h1 style="font-size: 100px;">
            <!-- <img src="Snapchat-49930113.jpg" alt="Profile Picture"> -->
            My portfolio
        </h1>

        <nav class="about-me">
            <ul>
                <li><a href="/home">Home</a></li>
                <li><a href="/about.me">About</a></li>
                <li><a href="/contact.me">Contact</a></li>
                <li><a href="/skills.html">Skills</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h2>About me</h2>
        <p>I am a passionate web developer, having completed small projects, and now eager to work on new opportunities
            to
            enhance my skills.
        </p>
        <h3>Hobbies</h3>
        <ul>
            <li>Creating websites</li>
            <li>Learning new skills</li>
            <li>Reading books</li>
        </ul>
        <h3>Education</h3>
        <table>
            <tr>
                <th>Degree</th>
                <th>Duration</th>
                <th>Achievments</th>
                <th>Relevant courses</th>
            </tr>
            <tr>
                <td>Matric</td>
                <td>2015-2016</td>
                <td>Scholarship</td>
                <td>Computer Science</td>
            </tr>
            <tr>
                <td>Intermediate</td>
                <td>2017-2018</td>
                <td>High GPA 90%</td>
                <td>ICS </td>
            </tr>
            <tr>
                <td>Bachelors</td>
                <td>2019-2023</td>
                <td>High GPA </td>
                <td>BSC, Web development, Java, JavaScript </td>
            </tr>
        </table>
        <h2>Skills</h2>
        <div class="container">
            <div class="me">
                <h3>HTML</h3>
                <p> Creating structured content for websites</p>
            </div>
            <div class="me">
                <h3> CSS </h3>
                <p>Styling web pages with colors, fonts, and layouts</p>
            </div>
            <div class="me">
                <h3> JavaScript </h3>
                <p> Making websites interactive</p>
            </div>
        </div>
        <div>
            <h2>Mini project</h2>
            <p>This is a simple contact form using HTML&CSS</p>
            <form>
                <input type="text" placeholder="Your Name" required>
                <input type="email" placeholder="Your Email" required>
                <textarea placeholder="Your Message" rows="4" required></textarea>
                <button type="submit">Send Message</button>
            </form>
        </div>
    </main>
    <footer>
        <div class="footer-container">
            <p>&copy; 2025 Shiffa. All rights reserved.</p>
            <p>
                <a href="a88941584@gmail.com">Email</a>
            </p>
        </div>
    </footer>
</body>

</html>
