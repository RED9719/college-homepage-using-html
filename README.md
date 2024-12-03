# college-homepage-using-html
1.	Design a home page which displays information about your college department using headings, HTML entities and paragraphs.
CODE
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Ramanujan College </title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f5f5f5;
            margin: 0;
            padding: 20px;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            background-color: #fff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1, h2, h3 {
            color: #333;
        }
        p {
            line-height: 1.6;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Welcome to Ramanujan College</h1>
        <h2>Department of Computer Science</h2>
        <p>Welcome to the Department of Computer Science at <strong>Ramanujan College</strong>. Our department is dedicated to providing quality education and fostering innovative research in various fields of computer science.</p>

        <h3> Our Vision </h3>
        <p>Our vision is to create a learning environment that encourages creativity, critical thinking, and collaboration. We aim to produce highly skilled professionals who can contribute to the technological advancements of society.</p>

        <h3> Academic Programs </h3>
        <p>We offer a variety of programs that cater to both undergraduate and postgraduate students. Our courses are designed to equip students with the necessary skills and knowledge to excel in the ever-evolving field of computer science.</p>
        <ul>
            <li>B.Sc in Computer Science</li>
            <li>bsc in philosophy</li>
            <li>B.SC in psychology</li>
        </ul>

        <h3> Research and Innovation </h3>
        <p>Our department is actively involved in research and innovation. We have state-of-the-art laboratories and collaborate with industry leaders to provide our students with practical experience and exposure to the latest technologies.</p>

        <h3> Contact Us </h3>
        <p>If you have any questions or need further information, please feel free to contact us:</p>
        <p>Email: <a href="mailto:csdept@ramanujancollege.edu">csdept@ramanujancollege.edu</a><br>
           Phone: +91-11-12345678</p>
    </div>
</body>
</html>
