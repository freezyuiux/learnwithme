<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Adhil Shanavas | Portfolio</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #f9fafb;
      color: #111827;
    }
    header, main, footer {
      max-width: 1000px;
      margin: auto;
      padding: 20px;
    }
    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    nav a {
      margin-left: 15px;
      text-decoration: none;
      color: #374151;
    }
    nav a:hover {
      text-decoration: underline;
    }
    .hero {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 20px;
      background: white;
      padding: 40px;
      border-radius: 20px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }
    .hero h2 {
      font-size: 2rem;
      margin-top: 10px;
    }
    .btn {
      display: inline-block;
      padding: 10px 16px;
      border-radius: 8px;
      text-decoration: none;
      margin-right: 10px;
    }
    .btn-primary {
      background: #4f46e5;
      color: white;
    }
    .btn-outline {
      border: 1px solid #d1d5db;
      color: #374151;
    }
    section {
      background: white;
      margin-top: 20px;
      padding: 20px;
      border-radius: 16px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }
    .skills span, .tags span {
      display: inline-block;
      background: #f3f4f6;
      padding: 4px 10px;
      margin: 4px;
      border-radius: 20px;
      font-size: 0.9rem;
    }
    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .projects article {
      background: white;
      padding: 16px;
      border-radius: 16px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.05);
    }
    form input, form textarea {
      width: 100%;
      padding: 10px;
      margin-bottom: 10px;
      border: 1px solid #d1d5db;
      border-radius: 6px;
    }
    form button {
      padding: 10px 16px;
      background: #4f46e5;
      color: white;
      border: none;
      border-radius: 6px;
      cursor: pointer;
    }
    footer {
      text-align: center;
      font-size: 0.8rem;
      color: #6b7280;
      margin: 30px 0;
    }
  </style>
</head>
<body>
  <header>
    <div>
      <h1>Adhil Shanavas</h1>
      <p style="font-size:0.9rem;color:#6b7280">UI/UX Designer • Frontend Developer</p>
    </div>
    <nav>
      <a href="#projects">Projects</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <main>
    <section class="hero">
      <div>
        <p style="color:#4f46e5;font-weight:600">Hi, I’m</p>
        <h2>Adhil Shanavas</h2>
        <p>I’m a UI/UX designer and frontend developer who builds usable, beautiful interfaces. I mainly work in Figma and React. Currently focusing on product design, micro-interactions and accessibility.</p>
        <div style="margin-top:16px;">
          <a href="#contact" class="btn btn-primary">Work with me</a>
          <a href="#projects" class="btn btn-outline">View projects</a>
        </div>
      </div>
      <div style="background:#f9fafb;padding:20px;border-radius:12px;">
        <div style="display:flex;align-items:center;gap:16px;">
          <div style="width:60px;height:60px;background:#e5e7eb;border-radius:12px;display:flex;align-items:center;justify-content:center;font-weight:bold;">AS</div>
          <div>
            <p><strong>Adhil Shanavas</strong></p>
            <p style="font-size:0.85rem;color:#6b7280">UI/UX Designer • Developer</p>
          </div>
        </div>
        <div style="margin-top:16px;display:grid;grid-template-columns:repeat(3,1fr);gap:10px;font-size:0.8rem;color:#4b5563">
          <div><strong>Tools</strong><br>Figma • React</div>
          <div><strong>Experience</strong><br>3+ years</div>
          <div><strong>Location</strong><br>India</div>
        </div>
      </div>
    </section>

    <section id="about">
      <h3>About me</h3>
      <p>I design digital experiences that are both delightful and accessible. My background blends visual design with frontend implementation — which makes handoffs clean and prototypes highly accurate. I enjoy working on end-to-end product problems, from user research to pixel-perfect UI.</p>
    </section>

    <section class="skills">
      <h3>Skills</h3>
      <span>UI Design</span>
      <span>UX Research</span>
      <span>Figma</span>
      <span>React</span>
      <span>HTML/CSS</span>
      <span>Accessibility</span>
    </section>

    <section id="projects">
      <h3>Selected Projects</h3>
      <div class="projects">
        <article>
          <h4>EsportX — Mobile UI/UX</h4>
          <p>Esports-themed mobile app UI with onboarding, live matches feed, and profile screens. Focus on modern microinteractions and accessibility.</p>
          <div class="tags"><span>Figma</span><span>Mobile</span><span>Design System</span></div>
        </article>
        <article>
          <h4>Picklist Management Redesign</h4>
          <p>Redesigned walk-in & bin management page to improve usability and aesthetics while retaining core functionality.</p>
          <div class="tags"><span>Product</span><span>Admin UI</span><span>Usability</span></div>
        </article>
        <article>
          <h4>Polaroid Photo Generator (UI)</h4>
          <p>A fun image-generation UI for creating stylized Polaroid-style photos with masking and light filters.</p>
          <div class="tags"><span>Creative</span><span>Frontend</span><span>Canvas</span></div>
        </article>
      </div>
    </section>

    <section id="contact">
      <h3>Let’s build something</h3>
      <p>Interested in working together? Send a message — I usually reply within a few days.</p>
      <form>
        <input type="text" placeholder="Your name">
        <input type="email" placeholder="Your email">
        <input type="text" placeholder="Subject">
        <textarea rows="4" placeholder="Message"></textarea>
        <button type="submit">Send message</button>
      </form>
    </section>
  </main>

  <footer>
    © <script>document.write(new Date().getFullYear())</script> Adhil Shanavas — Built with ❤️
  </footer>
</body>
</html>