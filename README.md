<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Salman Ahmed - Portfolio</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f4f4f4;
            color: #333;
        }

        h1, h3 {
            font-weight: bold;
        }

        .main-header {
            background: linear-gradient(90deg, #ff6347, #4682b4);
            color: white;
            padding: 50px 0;
            text-align: center;
        }

        .skills-section img {
            width: 50px;
            margin: 10px;
            transition: transform 0.3s ease;
        }

        .skills-section img:hover {
            transform: scale(1.2);
        }

        .profile-stats {
            margin-top: 20px;
        }

        .stats-container {
            display: flex;
            justify-content: space-evenly;
            flex-wrap: wrap;
            gap: 20px;
            padding: 30px 0;
        }

        .stats-container img {
            width: 350px;
            height: auto;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px 0;
        }

        footer a {
            color: #ff6347;
            text-decoration: none;
        }

        footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>

<body>
    <header class="main-header">
        <img src="https://cdn.dribbble.com/users/1162077/screenshots/3848914/programmer.gif" alt="Coding" class="img-fluid rounded-circle mb-3" style="width: 150px;">
        <h1>Hi 👋, I'm Salman Ahmed</h1>
        <h3>
            Passionate and innovative AI-ML Engineer with 2 years of hands-on corporate experience. Skilled in integrating
            technologies like AI/ML, DL, quantum computing, and cybersecurity.
        </h3>
        <a href="mailto:sh13jj2648@gmail.com" class="btn btn-light mt-3"><i class="fas fa-envelope"></i> Contact Me</a>
    </header>

    <section class="container mt-5">
        <h2 class="text-center">About Me</h2>
        <p class="text-center">
            🔭 Current Projects:
            <ul>
                <li>Optimization Problem for PSP</li>
                <li>Research with CERN on Particle Data Analysis</li>
            </ul>
            🌱 Learning Focus: Agentic Framework Building <br>
            💬 Ask Me About: Agentic Framework, GenAI, AI/ML, Quantum Computing, and Deep Learning.
        </p>
    </section>

    <section class="container skills-section">
        <h2 class="text-center">Skills & Tools</h2>
        <div class="d-flex justify-content-center flex-wrap">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="C">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="C++">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="Docker">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="MySQL">
            <img src="https://www.vectorlogo.zone/logos/pytorch/pytorch-icon.svg" alt="PyTorch">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/tensorflow/tensorflow-original.svg" alt="TensorFlow">
        </div>
    </section>

    <section class="container profile-stats">
        <h2 class="text-center">Profile Stats</h2>
        <div class="stats-container">
            <img src="https://github-readme-stats.vercel.app/api?username=SalmanAhmed1326&show_icons=true&theme=radical" alt="GitHub Stats">
            <img src="https://github-readme-streak-stats.herokuapp.com/?user=SalmanAhmed1326&theme=radical" alt="GitHub Streak">
            <img src="https://github-readme-stats.vercel.app/api/top-langs?username=SalmanAhmed1326&show_icons=true&theme=radical&layout=compact" alt="Top Languages">
        </div>
    </section>

    <footer>
        <p>© 2024 Salman Ahmed - <a href="https://linkedin.com/in/salman-ahmed13" target="_blank">Connect on LinkedIn</a></p>
    </footer>
</body>

</html>
