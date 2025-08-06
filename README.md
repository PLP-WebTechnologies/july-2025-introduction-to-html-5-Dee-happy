<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <!-- SEO Metadata -->
  <title>Accessible and SEO-Friendly HTML5 Page</title>
  <meta name="description" content="A simple HTML5 page demonstrating semantic structure, accessibility best practices, and SEO optimization.">
  <meta name="keywords" content="HTML5, semantic HTML, accessibility, SEO, web structure">
  <meta name="author" content="Your Name">
</head>
<body>

  <!-- Header with Navigation -->
  <header>
    <h1>Accessible and SEO-Friendly HTML5 Page</h1>
    <nav aria-label="Main Navigation">
      <ul>
        <li><a href="#introduction">Introduction</a></li>
        <li><a href="#features">Features</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <!-- Main Content -->
  <main>
    
    <!-- Introduction Section -->
    <section id="introduction" aria-labelledby="introduction-heading">
      <h2 id="introduction-heading">Introduction</h2>
      <p>This page is a demonstration of how to use semantic HTML5 elements effectively to improve accessibility and search engine optimization (SEO).</p>
      <p>It includes proper landmark elements, a logical heading hierarchy, and accessible features that aid both users and assistive technologies.</p>
    </section>

    <!-- Features Section -->
    <section id="features" aria-labelledby="features-heading">
      <h2 id="features-heading">Key Features</h2>

      <article aria-labelledby="semantic-heading">
        <h3 id="semantic-heading">1. Semantic Structure</h3>
        <p>Semantic elements such as <code>&lt;header&gt;</code>, <code>&lt;main&gt;</code>, <code>&lt;section&gt;</code>, and <code>&lt;footer&gt;</code> give meaning to content and improve its structure for both users and search engines.</p>
      </article>

      <article aria-labelledby="accessibility-heading">
        <h3 id="accessibility-heading">2. Accessibility Enhancements</h3>
        <p>Using ARIA labels and native HTML5 landmark roles makes navigation easier for screen readers and users with disabilities.</p>
      </article>

      <article aria-labelledby="seo-heading">
        <h3 id="seo-heading">3. SEO Optimization</h3>
        <p>Well-structured headings, descriptive text, and metadata ensure that search engines understand the page content and rank it appropriately.</p>
      </article>
      
    </section>

    <!-- Contact Section -->
    <section id="contact" aria-labelledby="contact-heading">
      <h2 id="contact-heading">Contact</h2>
      <p>If you have questions or feedback about this example page, please use the form below to reach out.</p>

      <form aria-label="Contact Form">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required aria-required="true">

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required aria-required="true">

        <label for="message">Message:</label>
        <textarea id="message" name="message" rows="5" required aria-required="true"></textarea>

        <button type="submit">Submit</button>
      </form>
    </section>

  </main>

  <!-- Footer -->
  <footer>
    <p>&copy; 2025 Accessible Web Project. All rights reserved.</p>
    <p><a href="#top">Back to top</a></p>
  </footer>

</body>
</html>
