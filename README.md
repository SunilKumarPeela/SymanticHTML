# 🗽 New York City Blog — Semantic HTML (Project)

A single-page **HTML** blog about the Big Apple, showcasing clean semantic structure, in-page navigation, and embedded media.  
Perfect for practicing `<header>`, `<main>`, `<article>`, `<section>`, `<figure>`, `<aside>`, and `<footer>`.

---

## 🚀 Quick Preview (code left • site right)

[![Open in CodeSandbox](https://img.shields.io/badge/Open%20in-CodeSandbox-black)](https://codesandbox.io/s/github/SunilKumarPeela/NYC-Blog?file=/index.html)

---

## 📄 What This Project Shows

- **HTML semantic structure:** `<nav>`, `<header>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<figure>`, `<footer>`
- **Media embeds:** `<img>`, `<video>`, `<audio>` with captions and controls
- **In-page navigation:** anchor links to **Blog**, **Media**, and **About**
- **Separation of concerns:** external `style.css` linked in `<head>`
- **Accessible content:** descriptive `alt` text and clear heading hierarchy

---

## 💻 Full HTML Code (`index.html`)

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <title>New York City Blog</title>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <link rel="stylesheet" href="style.css" />
  </head>

  <body>
    <nav aria-label="Primary">
      <ul>
        <li><a href="#blog">Blog</a></li>
        <li><a href="#media">Media</a></li>
        <li><a href="#about">About</a></li>
      </ul>
    </nav>

    <header>
      <h1>New York City</h1>
      <p>You got this!</p>
    </header>

    <main>
      <section id="blog">
        <h2>Blog</h2>
        <article>
          <p>New York City is made up of five boroughs: Queens, Manhattan, Brooklyn, the Bronx, and Staten Island. The city is home to approximately 8 million people.</p>
          <p>In 1876, France gifted what is now known as the Statue of Liberty to New York City. It took 10 years to assemble and was unveiled in 1886. The statue stands on Liberty Island and is one of the most visited landmarks in the world.</p>
          <p>Another iconic destination is Times Square—famous for its towering buildings, Broadway shows, and bright neon signs. The square was renamed after <em>The New York Times</em> moved there; prior to that, it was called Longacre Square.</p>
          <p>NYC is also known for the bridges that connect its boroughs, enabling ease of transportation and stunning skyline views.</p>
        </article>

        <figure>
          <img src="https://content.codecademy.com/courses/Semantic%20HTML/statue-of-liberty.jpeg" alt="The Statue of Liberty on Liberty Island" />
          <figcaption>The Statue of Liberty, a popular tourist attraction on Liberty Island.</figcaption>
        </figure>

        <aside>
          <p>New York City is beloved for its incredible variety of food. Top picks include:</p>
          <ol>
            <li>Pizza</li>
            <li>Bagels</li>
            <li>Burgers &amp; Sandwiches</li>
            <li>Ramen</li>
            <li>Tacos</li>
            <li>Pasta</li>
            <li>Desserts</li>
          </ol>
        </aside>
      </section>

      <section id="media">
        <h2>The Scenery in NYC</h2>
        <article>
          <p>The views in New York are beautiful, but the sounds are less tranquil. Here’s a quick peek (and listen) at daily NYC life.</p>
        </article>

        <video src="https://content.codecademy.com/courses/Semantic%20HTML/nyc-skyline-timelapse.mp4" controls></video>
        <img src="https://content.codecademy.com/courses/Semantic%20HTML/nyc-skyline.jpeg" alt="NYC skyline at dusk" />
        <audio controls>
          <source src="https://content.codecademy.com/courses/Semantic%20HTML/nyc-sounds.mov" type="audio/quicktime" />
        </audio>
      </section>
    </main>

    <footer id="about">
      <h2>About</h2>
      <p>Contact information: <a href="mailto:Blogger@NYC.com">Blogger@NYC.com</a></p>
    </footer>
  </body>
</html>
