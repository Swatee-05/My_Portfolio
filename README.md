# My_Portfolio
My website and about me.
<!DOCTYPE html>
<html lang="en">
<head>
    /* Reset some basic elements */
body, h1, h2, p, ul {
    margin: 0;
    padding: 0;
}
h1 {
  text-align: center;
  color: green;
}
body, html {
  height: 100%;
  margin: 0;
}

.animated-background {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  background: linear-gradient(-45deg, #262626, #121212, #262626, #121212);
  background-size: 400% 400%;
  animation: gradientBG 15s ease infinite;
  color: #fff;
  text-align: center;
  font-family: 'Arial', sans-serif;
}

@keyframes gradientBG {
  0% {
    background-position: 0% 50%;
  }
  50% {
    background-position: 100% 50%;
  }
  100% {
    background-position: 0% 50%;
  }
}

.animated-background h1 {
  font-size: 3rem;
  text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.6);
}

.animated-background p {
  font-size: 1.5rem;
  margin-top: 20px;
  opacity: 0.8;
}

body, html {
  height: 100%;
  margin: 0;
}

.animated-background {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  background: linear-gradient(-45deg, #24C6DC, #514A9D, #FF512F, #F09819);
  background-size: 400% 400%;
  animation: gradientBG 15s ease infinite;
}

@keyframes gradientBG {
  0% {
    background-position: 0% 50%;
  }
  50% {
    background-position: 100% 50%;
  }
  100% {
    background-position: 0% 50%;
  }
}

body {
    font-family: 'Arial', sans-serif;
    line-height: 1.6;
    color: #333;
    background-color: #e4f9f5; /* Light green background */
}

nav {
    background: #0f4c75; /* Dark blue */
    color: #fff;
    padding: 10px 20px;
    text-align: center;
}

nav ul {
    list-style: none;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

section {
    padding: 20px;
    margin: 20px 0;
}

#home {
    background-color: #30e3ca; /* Turquoise */
}

#about, #contact {
    background-color: #11999e; /* Teal */
}

#portfolio {
    background-color: #40514e; /* Dark green */
    color: #fff;
}

h1, h2 {
    margin-bottom: 10px;
}

    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>

<div class="animated-background">
  <h1>Welcome to My Portfolio</h1>
  <p>Discover the mysteries that lie beneath...</p>
</div>

<body>
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#portfolio">Portfolio</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <section id="home">
        <h1>Welcome to My Portfolio</h1>
        <p>Hello, I'm a Scientist who works in the Quantum Realm. Take a look around!</p>
    </section>

    <section id="about">
        <h2>About Me</h2>
        <p>Leveraging my expertise in quantum optics, I contribute to the cutting-edge research at the Indian Institute of Science's Quantum Optics and Quantum Information Processing Laboratory. As a Project Associate, I specialize in generating entangled photons in both polarization and path degrees of freedom using the SPDC process.

Research in Quantum Technologies ignites my passion for unraveling the universe's fundamental mysteries, and I'm driven to contribute to upcoming breakthroughs. This cutting-edge research holds immense potential for advancements in quantum computing and communication, and I'm thrilled to be contributing to this exciting field.

Fascinated by the potential of quantum technology, I currently delve into the world of project execution within this exciting field. But my curiosity doesn't stop there! Inspired by the power of data and its potential to solve complex problems, I'm actively exploring the world of machine learning and data science. I see these fields as complementary forces, pushing the boundaries of technology and impacting various industries. Driven by a thirst for knowledge and a collaborative spirit, I'm eager to connect with like-minded individuals and engage in projects that utilize the synergy of these innovative domains.</p>
    </section>

    <section id="portfolio">
        <h2>My Work</h2>
        <p>I am working on generating entangled photons in both polarization and path degrees of freedom using the SPDC process (TADA!! Quantum Hyperentanglement!).</p>
        <!-- Insert project details or links here -->
    </section>

    <section id="contact">
        <h2>Contact Me</h2>
        <p>Let's get in touch. You can reach me at: sushreeswateeprajnyabehera@gmail.com</p>
        <!-- Add more contact details or a form here -->
    </section>

    <script src="script.js"></script>
</body>
</html>
