<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
            background-color: #f9f9f9;
            line-height: 1.6;
        }

        header {
            background-color: #0044cc;
            color: white;
            text-align: center;
            padding: 3rem 1rem;
        }

        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }

        header p {
            font-size: 1.2rem;
            margin-top: 0.5rem;
        }

        nav {
            display: flex;
            justify-content: center;
            background-color: #002a80;
            padding: 1rem 0;
        }

        nav a {
            color: white;
            text-decoration: none;
            padding: 0.5rem 1rem;
            margin: 0 0.5rem;
            font-size: 1rem;
            border-radius: 5px;
            transition: background-color 0.3s;
        }

        nav a:hover {
            background-color: #0044cc;
        }

        section {
            max-width: 1000px;
            margin: 2rem auto;
            padding: 1rem;
            background: white;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        section h2 {
            color: #0044cc;
            margin-bottom: 1rem;
        }

        .projects .project {
            margin-bottom: 2rem;
        }

        .project h3 {
            margin-bottom: 0.5rem;
        }

        .project p {
            margin-bottom: 0.5rem;
        }

        footer {
            background-color: #002a80;
            color: white;
            text-align: center;
            padding: 1rem;
            margin-top: 2rem;
        }

        .contact a {
            color: #0044cc;
        }

        .button {
            display: inline-block;
            padding: 0.7rem 1.5rem;
            color: white;
            background-color: #0044cc;
            text-decoration: none;
            border-radius: 5px;
            font-size: 1rem;
            transition: background-color 0.3s;
        }

        .button:hover {
            background-color: #002a80;
        }

    </style>
</head>
<body>
    <header>
        <h1>Your Name</h1>
        <p>Designer | Developer | Innovator</p>
    </header>

    <nav>
        <a href="#projects">Projects</a>
        <a href="#design-systems">Design Systems</a>
        <a href="#contact">Contact</a>
    </nav>

    <section id="projects">
        <h2>Projects</h2>
        <div class="project">
            <h3>Case Study: Project Name</h3>
            <p>Overview of the project. Highlight the problem, your process, and the outcome. Include technologies or frameworks used.</p>
            <a class="button" href="#">View Details</a>
        </div>
        <div class="project">
            <h3>Case Study: Another Project</h3>
            <p>Overview of the project. Highlight the problem, your process, and the outcome. Include technologies or frameworks used.</p>
            <a class="button" href="#">View Details</a>
        </div>
    </section>

    <section id="design-systems">
        <h2>Design Systems</h2>
        <p>Share insights about your approach to building design systems. Include examples, best practices, or tools like Figma or Storybook.</p>
        <div class="project">
            <h3>Design System: Freedom</h3>
            <p>Discuss the purpose of the design system, components, and implementation strategies.</p>
            <a class="button" href="#">Explore the System</a>
        </div>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>If you'd like to collaborate or learn more about my work, please reach out via <a href="mailto:youremail@example.com">youremail@example.com</a>.</p>
        <p>Connect with me on <a href="#">LinkedIn</a> or view my <a href="#">GitHub</a>.</p>
    </section>

    <footer>
        <p>&copy; 2024 Your Name. All rights reserved.</p>
    </footer>
</body>
</html>
