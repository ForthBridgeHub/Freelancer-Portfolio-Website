# 🌐 Project 3: Freelancer Portfolio Website

A multi-page portfolio website for a freelance developer or designer.  
This project helps you learn **multi-page structure**, **navigation**, and **Tailwind CSS styling**.

---

## 🧭 Overview

You’ll build a **4-page portfolio website** that introduces a freelancer, showcases their work, and provides a contact form.

Your job is to:
- Write the base HTML structure.
- Use **Tailwind CSS** for all styling.
- Make the design responsive and clean.

---

## 🧱 Folder Structure

freelancer-portfolio/
├── index.html
├── about.html
├── projects.html
├── contact.html
├── js/
│ └── main.js
└── assets/
└── profile.jpg


---

## 🛠️ Tech Stack

- HTML5  
- Tailwind CSS (via CDN or CLI build)  
- JavaScript (for small interactivity)

---

## 📄 Page Requirements

Each page should include:

- A **Navbar** (common across all pages)
- A **Footer** (common across all pages)
- Tailwind utility classes for styling
- Mobile-responsive design

---

## 🏠 `index.html` (Home Page Skeleton)

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Home | My Portfolio</title>
    <!-- Include Tailwind CSS via CDN -->
  </head>
  <body>
    <!-- Navbar -->
    <nav>
      <h1>MyPortfolio</h1>
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="about.html">About</a></li>
        <li><a href="projects.html">Projects</a></li>
        <li><a href="contact.html">Contact</a></li>
      </ul>
    </nav>

    <!-- Hero Section -->
    <main>
      <h2>Hi, I'm [Your Name]</h2>
      <p>A Frontend Developer passionate about web design.</p>
      <a href="projects.html">View My Work</a>
    </main>

    <!-- Footer -->
    <footer>
      <p>© 2025 [Your Name]. All rights reserved.</p>
    </footer>
  </body>
</html>
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>About | My Portfolio</title>
  </head>
  <body>
    <!-- Navbar -->
    <nav>
      <!-- Same as index.html -->
    </nav>

    <!-- About Section -->
    <main>
      <h2>About Me</h2>
      <img src="assets/profile.jpg" alt="Profile picture" />
      <p>[Short bio goes here]</p>

      <h3>Skills</h3>
      <ul>
        <li>HTML</li>
        <li>CSS</li>
        <li>JavaScript</li>
        <li>React</li>
        <li>Tailwind CSS</li>
      </ul>
    </main>

    <!-- Footer -->
    <footer>
      <p>© 2025 [Your Name]. All rights reserved.</p>
    </footer>
  </body>
</html>
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Projects | My Portfolio</title>
  </head>
  <body>
    <!-- Navbar -->
    <nav>
      <!-- Same as index.html -->
    </nav>

    <!-- Projects Section -->
    <main>
      <h2>My Projects</h2>

      <section>
        <article>
          <img src="https://via.placeholder.com/400x250" alt="Project 1" />
          <h3>Project One</h3>
          <p>Short description of the project.</p>
        </article>

        <article>
          <img src="https://via.placeholder.com/400x250" alt="Project 2" />
          <h3>Project Two</h3>
          <p>Short description of the project.</p>
        </article>

        <article>
          <img src="https://via.placeholder.com/400x250" alt="Project 3" />
          <h3>Project Three</h3>
          <p>Short description of the project.</p>
        </article>
      </section>
    </main>

    <!-- Footer -->
    <footer>
      <p>© 2025 [Your Name]. All rights reserved.</p>
    </footer>
  </body>
</html>
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Contact | My Portfolio</title>
  </head>
  <body>
    <!-- Navbar -->
    <nav>
      <!-- Same as index.html -->
    </nav>

    <!-- Contact Section -->
    <main>
      <h2>Contact Me</h2>

      <form id="contactForm">
        <input type="text" placeholder="Your Name" required />
        <input type="email" placeholder="Your Email" required />
        <textarea placeholder="Your Message" required></textarea>
        <button type="submit">Send Message</button>
      </form>
    </main>

    <!-- Footer -->
    <footer>
      <p>© 2025 [Your Name]. All rights reserved.</p>
    </footer>

    <script src="js/main.js"></script>
  </body>
</html>

