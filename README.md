<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            padding: 0;
            background-color: #f0f0f0;
        }

        h1,
        h2 {
            color: #333;
        }

        header,
        section {
            background-color: #fff;
            border-radius: 8px;
            padding: 20px;
            margin-bottom: 20px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        a {
            color: #007bff;
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }

        ul {
            list-style-type: none;
            padding: 0;
        }

        li {
            margin-bottom: 10px;
        }

        .fade-in {
            animation: fadeIn 2s ease-in;
        }

        @keyframes fadeIn {
            from {
                opacity: 0;
            }

            to {
                opacity: 1;
            }
        }

        .skill-bar {
            position: relative;
            display: block;
            margin-bottom: 15px;
            background-color: #e0e0e0;
            border-radius: 4px;
            overflow: hidden;
        }

        .skill-bar div {
            height: 20px;
            background-color: #3b82f6;
            width: 0;
            border-radius: 4px;
            animation: loadSkill 3s forwards;
        }

        @keyframes loadSkill {
            0% {
                width: 0;
            }

            100% {
                width: 100%;
            }
        }
    </style>
</head>

<body>
    <header>
        <h1 class="fade-in">Michał Matsalak</h1>
    </header>
    <main>
        <section class="fade-in">
            <h2> 🎓 📝 Link to my resume (Polish)</h2>
            <a href="https://docs.google.com/document/d/16oTEUSwQh29ZVxFjT-9pltRWmo1XrJ7m/edit?usp=sharing&ouid=105718250807664062014&rtpof=true&sd=true">
                My CV PL</a>

            <h2> 🎓 📝 Link to my resume (English)</h2>
            <a href="https://docs.google.com/document/d/1-5vOvb7sHmVqcopIgygMq0KubF8zZD7v/edit?usp=sharing&ouid=105718250807664062014&rtpof=true&sd=true">
                My CV EN</a>
        </section>

        <section class="fade-in">
            <h2>Contact Information</h2>
            <ul>
                <li>Address: Juliusza Lea 53, 30-052 Kraków</li>
                <li>Phone number: (+48) 578 742 682</li>
                <li>Email: matsalakmichal@gmail.com</li>
                <li>Date of birth: 13.11.2001</li>
            </ul>
        </section>

        <section class="fade-in">
            <h2>Summary</h2>
            <p>I am a student at the National Education Commission University in Kraków, majoring in Technical and IT Education. I am passionate about technology and am pursuing a career as a full stack developer. I am eager to take on new challenges and continuously expand my skills in both front-end and back-end development.</p>
        </section>

        <section class="fade-in">
            <h2>Experience</h2>
            <ul>
                <li><strong>Sabre Poland, Kraków – Software Developer I</strong><br>
                    07/2023<br>
                    - Designed and developed microservices for scalable and flexible systems.<br>
                    - Created and optimized user interfaces using React and integrated with backend microservices.<br>
                    - Developed applications in TypeScript, enhancing code safety and readability.<br>
                    - Used LESS to manage advanced style sheets, enabling efficient application styling.</li>

                <li><strong>Capital Alliance, Kraków – Web Administrator</strong><br>
                    06/2021 – 08/2021<br>
                    - Shaped the architecture of web applications.<br>
                    - Implemented technological and design improvements.<br>
                    - Managed a SaaS e-commerce platform (Shoper).</li>

                <li><strong>WWP Capital, Kraków – Web Developer</strong><br>
                    07/2019 – 12/2019<br>
                    - Developed applications for the Android platform.<br>
                    - Participated in application design processes and advanced interfaces.<br>
                    - Actively collaborated with other departments in the company.</li>
            </ul>
        </section>

        <section class="fade-in">
            <h2>Education</h2>
            <ul>
                <li><strong>National Education Commission University in Kraków, Kraków – Master’s Degree</strong><br>
                    2024 - 2025<br>
                    Field of Study: Technical and IT Education</li>

                <li><strong>Cracow University of Technology, Kraków – Bachelor’s Degree in Engineering</strong><br>
                    2020 - 2024<br>
                    Field of Study: Applied Computer Science</li>
            </ul>
        </section>

        <section class="fade-in">
            <h2>Certificates</h2>
            <ul>
                <li>Spring Boot – Udemy</li>
                <li>Basics of Internet Marketing – Google</li>
                <li>Certificate TELC B2 – SJO</li>
            </ul>
        </section>

        <section class="fade-in">
            <h2>Skills</h2>
            <ul>
                <li>React.js</li>
                <li>TypeScript</li>
                <li>JavaScript</li>
                <li>Java</li>
                <li>Spring Boot</li>
                <li>RESTful API</li>
                <li>HTML5, CSS</li>
                <li>LESS</li>
                <li>MySQL</li>
                <li>React Testing Library</li>
                <li>JUnit</li>
                <li>Git</li>
                <li>Node.js</li>
                <li>Docker</li>
                <li>GraphQL</li>
                <li>Python</li>
                <li>AWS</li>
                <li>CI/CD</li>
            </ul>
        </section>

        <section class="fade-in">
            <h2>Languages</h2>
            <ul>
                <li>Polish: C2</li>
                <li>Ukrainian: C2</li>
                <li>English: B2</li>
                <li>Russian: C1</li>
            </ul>
        </section>

        <section class="fade-in">
            <h2>Social Links</h2>
            <ul>
                <li><a href="https://github.com/yourusername">GitHub - Portfolio</a></li>
                <li><a href="https://linkedin.com/in/yourusername">LinkedIn - Profile</a></li>
            </ul>
        </section>
    </main>
</body>

</html>
