<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Interactive portfolio of Case M. Loraine, showcasing skills, projects, and dedication to SDG 4 - Quality Education.">
    <title>Loraine Joy M Casem - Portfolio</title>
    <style>
        /* Base Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #f9f9f9;
        }

        a {
            text-decoration: none;
            color: inherit;
        }

        a:hover {
            text-decoration: underline;
        }

        img {
            max-width: 100%;
            height: auto;
        }

        /* Header Section */
        header {
            background-color: #0a0a0a;
            color: white;
            text-align: center;
            padding: 2rem 1rem;
        }

        header h1 {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
        }

        header p {
            font-size: 1.2rem;
            margin-bottom: 1rem;
        }

        header img {
            border-radius: 50%;
            width: 150px;
            height: 150px;
            object-fit: cover;
            border: 3px solid white;
        }

        /* Section Styles */
        section {
            padding: 2rem;
            margin: 1rem auto;
            max-width: 900px;
            background: white;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        section h2 {
            font-size: 1.8rem;
            color: #4CAF50;
            margin-bottom: 1rem;
        }

        /* Skills Section */
        #skills ul {
            list-style: none;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 1rem;
            padding: 0;
        }

        #skills li {
            background: #e8f5e9;
            padding: 1rem;
            text-align: center;
            border-radius: 5px;
            font-weight: bold;
        }

        /* Projects Section */
        .project {
            margin-bottom: 1.5rem;
            padding: 1rem;
            border: 1px solid #ddd;
            border-radius: 8px;
            background: #fefefe;
        }

        .project h3 {
            margin-bottom: 0.5rem;
            color: #333;
        }

        .project p {
            margin-bottom: 1rem;
        }

        .project a {
            display: inline-block;
            color: #4CAF50;
            font-weight: bold;
            transition: color 0.3s ease;
        }

        .project a:hover {
            color: #388e3c;
        }

        /* Footer Styles */
        footer {
            text-align: center;
            background-color: #1db322;
            color: white;
            padding: 1rem;
            margin-top: 2rem;
        }

        footer p {
            margin: 0;
            font-size: 1rem;
        }

        footer a {
            color: white;
            font-weight: bold;
        }

        footer a:hover {
            text-decoration: underline;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            header img {
                width: 120px;
                height: 120px;
            }

            section {
                padding: 1.5rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Loraine Joy M Casem</h1>
        <p>Aspiring web developer with a passion for building impactful digital solutions.</p>
        <img src="c:\Users\ACER\Downloads\464685532_1642342249652812_2448973275579151626_n (2).jpg" alt="Profile Picture">
    </header>

    <main>
        <section id="sdg">
            <h2>Sustainable Development Goal: 4 - Quality Education</h2>
            <p>
                Quality Education aims to ensure inclusive and equitable quality education for all and promote lifelong learning opportunities. 
                This goal aligns with my skills in creating accessible educational platforms and my aspiration to contribute to a world where everyone 
                has access to valuable learning resources. Through my projects and expertise, I hope to develop tools that empower students and educators worldwide.
            </p>
        </section>
        
        <section id="skills">
            <h2>Skills and Expertise</h2>
            <ul>
                <li>Web Developer</li>
                <li>Data Analysis</li>
                <li>Software Developer</li>
            </ul>
        </section>

        <section id="projects">
            <h2>Projects</h2>
            <div class="project">
                <h3>Personal Portfolio Website</h3>
                <p>
                    A fully responsive personal portfolio website built using HTML, CSS, and JavaScript. 
                    The site showcases my skills, projects, and professional profile with an engaging and modern design.
                </p>
                <a href="casem html.html" target="_blank" rel="noopener noreferrer">Visit Project</a>
            </div>
            <div class="project">
                <h3>Weather App</h3>
                <p>
                    A weather forecasting application that fetches real-time weather data from an API and displays it in a user-friendly interface. 
                    Developed using HTML, CSS, and JavaScript, with a focus on responsive design.
                </p>
                <li><a href="weather-app.html" target="_blank">Weather App</a></li>
            </div>
        </section>
    </main>

    <footer>
        <p>Contact: <a href="mailto:casemlorainejoy@gmail.com">casemlorainejoy@gmail.com</a> | 
        <a href="https://www.facebook.com/share/15HsSyvuJW/" target="_blank" rel="noopener noreferrer">Facebook</a></p>
    </footer>
</body>
</html>
