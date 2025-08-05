<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>My Portfolio</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Segoe UI', sans-serif;
    }

    body {
      background-color: #f4f4f4;
      color: #333;
      line-height: 1.6;
    }

    header {
      background-color: #333;
      color: #fff;
      padding: 40px 20px;
      text-align: center;
    }

    header h1 {
      font-size: 2.5rem;
      margin-bottom: 10px;
    }

    header p {
      font-size: 1.2rem;
      color: #ddd;
    }

    section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }

    h2 {
      font-size: 2rem;
      margin-bottom: 20px;
      color: #444;
    }

    .about p {
      max-width: 700px;
      margin-bottom: 20px;
    }

    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .project {
      background-color: #fff;
      border: 1px solid #ddd;
      padding: 20px;
      border-radius: 5px;
      transition: box-shadow 0.3s ease;
    }

    .project:hover {
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }

    .contact form {
      display: flex;
      flex-direction: column;
      gap: 10px;
      max-width: 500px;
    }

    .contact input,
    .contact textarea {
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 4px;
    }

    .contact button {
      padding: 10px;
      background-color: #333;
      color: white;
      border: none;
      cursor: pointer;
      border-radius: 4px;
    }

    .contact button:hover {
      background-color: #555;
    }

    footer {
      background-color: #222;
      color: #ccc;
      text-align: center;
      padding: 20px;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>

  <header>
    <h1>rolex</h1>
    <p>Web Developer | Designer | Tech Enthusiast</p>
  </header>

  <section class="about">
    <h2>About Me</h2>
    <p>
      Hello! I'm a passionate developer with experience in building responsive web applications.
  I enjoy turning complex problems into simple, beautiful, and intuitive designs.I'm also an expert in online bussiness, bringing about many friutful reearchs
    </p>
  </section>

  <section>
    <h2>Projects</h2>
    <div class="projects">
      <div class="project">
        <h3>Project One</h3>
        <p>Description of your first project. What tech was used, what problem it solved, etc.</p>
      </div>
      <div class="project">
        <h3>Project Two</h3>
        <p>Overview of another project. Make sure to highlight your contributions and skills used.</p>
      </div>
      <div class="project">
        <h3>Project Three</h3>
        <p>Details of a third project. Could be personal, freelance, or coursework related.</p>
      </div>
    </div>
  </section>

  <section class="contact">
    <h2>Contact Me</h2>
    <form>
      <input type="text" placeholder="Your Name" required />
      <input type="email" placeholder="Your Email" required />
      <textarea rows="5" placeholder="Your Message" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    &copy; 2025 Your Name. All rights reserved.
  </footer>

</body>
</html>
