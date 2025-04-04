<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> D S NITHYANANDHAM | Portfolio</title>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.2/gsap.min.js"></script>
    <style>
        /* General Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Poppins', sans-serif;
        }

        body {
            background: linear-gradient(135deg, #1e1e2f, #3a3a5a);
            color: #fff;
            text-align: center;
            padding: 20px;
        }

        /* Header */
        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px;
            background: rgba(0, 0, 0, 0.5);
            border-radius: 10px;
        }

        .hero-title {
            font-size: 2.5rem;
            font-weight: bold;
            text-transform: uppercase;
            letter-spacing: 2px;
            color: #ffcc00;
        }

        nav ul {
            list-style: none;
            display: flex;
        }

        nav ul li {
            margin: 0 15px;
        }

        nav ul li a {
            text-decoration: none;
            color: #fff;
            font-size: 1rem;
            transition: color 0.3s ease;
        }

        nav ul li a:hover {
            color: #ffcc00;
        }

        /* Sections */
        .section {
            margin: 30px auto;
            padding: 40px;
            max-width: 800px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 15px;
            box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.3);
        }

        h2 {
            font-size: 2rem;
            margin-bottom: 15px;
            color: #ffcc00;
        }

        p, ul {
            font-size: 1.1rem;
            line-height: 1.6;
        }

        /* Profile Image */
        .profile-img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
            margin-top: 20px;
        }

        /* Button */
        .btn {
            display: inline-block;
            padding: 10px 20px;
            background: #ffcc00;
            color: #1e1e2f;
            font-size: 1rem;
            font-weight: bold;
            border-radius: 5px;
            text-decoration: none;
        }

        .btn:hover {
            background: #e6b800;
        }
    </style>
</head>
<body>
    <header>
        <h1 class="hero-title">NITHYANANDHAM D S </h1>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#education">Education</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#resume">Resume</a></li>
            </ul>
        </nav>
    </header>

    <section id="about" class="section">
        <h2>About Me</h2>
        <img src="https://github.com/Nithyanandham772006/Resume/blob/main/WhatsApp%20Image%202025-04-03%20at%209.40.13%20PM.jpeg">
        <p>Hi, I'm D S NITHYANANDHAYAM ,</p>
    </section>

    <section id="education" class="section">
        <h2>Education</h2>
        <p>B.Sc Computer Science - GOVERNMENT ARTS AND SCIENCE COLLAGE</p>
    </section>

    <section id="skills" class="section">
        <h2>Skills</h2>
        <ul>
            <li>Python</li>
            <li>Data Analytics</li>
            <li>Machine Learning</li>
            <li>Web Development</li>
            <li>HTML</li>
            <li>CSS</li>
            <li>JavaScript</li>
            <li>Java</li>
            <li>Microsoft Office</li>
        </ul>
    </section>

    <section id="projects" class="section">
        <h2>Projects</h2>
        <ul>
            <li>Portfolio Website - A personal portfolio showcasing my skills and projects.</li>
            <li>Data Analysis on COVID-19 - Analyzed pandemic data using Python and visualized trends.</li>
            <li>Machine Learning Model - Built a predictive model for customer churn analysis.</li>
        </ul>
    </section>
         
    </section>

    <section id="resume" class="section">
        <h2>Resume</h2>
        <a href="" download class="btn">Download Resume</a>
    </section>

    <section id="contact" class="section">
        <h2>Contact</h2>
        <p>Email: <a href="mailto:dsnnithi@gmail.com" style="color: #ffcc00;">dsnnithi@gmail.com</a></p>
    </section>

    <script>
        gsap.from(".hero-title", {duration: 1, y: -50, opacity: 0, ease: "bounce"});
        gsap.from(".section", {duration: 1.5, y: 50, opacity: 0, stagger: 0.3, ease: "power2.out"});
    </script>
</body>
</html>
