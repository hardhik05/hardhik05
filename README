<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="description" content="Advocate Hardhik R | Legal services in Chennai. Specializing in civil, criminal, family, and commercial law.">
  <title>Advocate Hardhik R - Legal Services in Chennai</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&family=Playfair+Display:wght@700&display=swap" rel="stylesheet">
  <style>
    :root {
      --bg-color: #2c3e50; /* Dark Charcoal Gray */
      --surface-color: #ffffff;
      --text-color: #f1f1f1; /* Lighter gray for better readability */
      --accent-color: #2980b9; /* Blue Accent for clarity */
      --font-main: 'Poppins', sans-serif;
      --font-title: 'Playfair Display', serif;
      --card-bg-color: #34495e; /* Darker card background */
      --hover-bg-color: #1abc9c; /* Hover effect color */
      --card-text-color: #ecf0f1; /* Lighter card text */
      --header-text-color: #ffffff; /* White text in header */
      --floating-window-bg: #34495e; /* Dark background for floating window */
      --floating-window-text: #ffffff; /* White text in the floating window */
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: var(--font-main);
      background-color: var(--bg-color);
      color: var(--text-color);
      line-height: 1.6;
    }

    nav {
      background-color: #1a252f; /* Slightly darker */
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    }

    nav h1 {
      font-family: var(--font-title);
      font-size: 1.8rem;
      color: var(--header-text-color);
    }

    nav ul {
      list-style: none;
      display: flex;
      gap: 1.5rem;
    }

    nav a {
      color: var(--header-text-color);
      text-decoration: none;
      font-weight: 600;
      transition: color 0.3s ease;
    }

    nav a:hover {
      color: var(--accent-color);
    }

    header {
      background: url('https://images.unsplash.com/photo-1565072202-9d957e62504d?auto=format&fit=crop&w=1600&q=80') center/cover no-repeat;
      color: var(--header-text-color);
      text-align: center;
      padding: 8rem 1rem;
    }

    header h2 {
      font-size: 3rem;
      font-family: var(--font-title);
      text-shadow: 2px 2px 6px rgba(0, 0, 0, 0.3);
    }

    header p {
      font-size: 1.3rem;
      margin-top: 1rem;
    }

    header a {
      display: inline-block;
      margin-top: 1.5rem;
      padding: 0.75rem 1.5rem;
      background-color: var(--accent-color);
      color: #ffffff;
      border-radius: 5px;
      font-weight: 600;
      text-decoration: none;
    }

    section {
      padding: 4rem 1rem;
      max-width: 1100px;
      margin: auto;
    }

    h3 {
      font-size: 2.2rem;
      font-family: var(--font-title);
      color: var(--accent-color);
      text-align: center;
      margin-bottom: 1.5rem;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 2rem;
      text-align: center;
    }

    .card {
      background: var(--card-bg-color);
      padding: 2rem;
      border-radius: 10px;
      box-shadow: 0 0 15px rgba(0, 0, 0, 0.05);
      transition: transform 0.3s, box-shadow 0.3s;
    }

    .card:hover {
      transform: translateY(-5px);
      box-shadow: 0 4px 20px rgba(52, 152, 219, 0.3);
    }

    .card p {
      color: var(--card-text-color);
    }

    .contact {
      background: var(--surface-color);
      padding: 2rem;
      border-radius: 10px;
      text-align: center;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.05);
      color: #34495e;
    }

    footer {
      background-color: #34495e;
      color: var(--text-color);
      text-align: center;
      padding: 2rem 1rem;
      font-size: 0.9rem;
    }

    footer a {
      color: var(--accent-color);
      text-decoration: underline;
    }

    .floating-contact {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background-color: var(--accent-color);
      color: #fff;
      padding: 0.75rem 1rem;
      border-radius: 50px;
      text-decoration: none;
      font-weight: bold;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.4);
      transition: transform 0.3s ease;
    }

    .floating-contact:hover {
      transform: scale(1.1);
    }

    .floating-window {
      position: fixed;
      bottom: 100px;
      right: 20px;
      background-color: var(--floating-window-bg);
      color: var(--floating-window-text);
      border-radius: 10px;
      padding: 2rem;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
      width: 280px;
      z-index: 9999;
      transition: transform 0.3s ease;
      opacity: 0;
      visibility: hidden;
    }

    .floating-window.show {
      opacity: 1;
      visibility: visible;
      transform: translateY(0);
    }

    .floating-window h4 {
      margin-bottom: 1rem;
      color: var(--accent-color);
    }

    .floating-window p {
      font-size: 1rem;
      margin-bottom: 1rem;
      color: #ffffff;  /* White text for better visibility */
    }

    .floating-window button {
      padding: 0.75rem 1.5rem;
      background-color: var(--accent-color);
      color: #fff;
      border: none;
      border-radius: 5px;
      font-weight: 600;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }

    .floating-window button:hover {
      background-color: #1abc9c;
    }

    @media (max-width: 600px) {
      header h2 {
        font-size: 2rem;
      }

      nav ul {
        flex-direction: column;
        gap: 0.5rem;
      }
    }
  </style>
</head>

<body>

  <nav>
    <h1>Adv. Hardhik R</h1>
    <ul>
      <li><a href="#expertise">Expertise</a></li>
      <li><a href="#registrations">Registrations</a></li>
      <li><a href="#credentials">Credentials</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <header>
    <h2>Advocate Hardhik R</h2>
    <p>Committed to Excellence in Legal Practice</p>
    <a href="tel:+918248890088">Call Now</a>
  </header>

  <section id="expertise">
    <h3>Practice Areas</h3>
    <div class="grid">
      <div class="card">⚖️<br> Civil & Property Disputes</div>
      <div class="card">🕊️<br> Family & Divorce Law</div>
      <div class="card">🏢<br> Corporate & Commercial Litigation</div>
      <div class="card">🧾<br> Contract Drafting</div>
      <div class="card">👨⚖️<br> Criminal Defence</div>
      <div class="card">🧠<br> Legal Consultation & Opinion</div>
    </div>
  </section>

  <section id="registrations">
    <h3>Registration Services</h3>
    <div class="grid">
      <div class="card">®️<br><strong>Trademark Registration</strong><br>Protect your brand identity with expert support.</div>
      <div class="card">💍<br><strong>Marriage Registration</strong><br>Seamless and legally compliant process.</div>
      <div class="card">🏠<br><strong>Property Registration</strong><br>Legal clarity in real estate transactions.</div>
      <div class="card">🏢<br><strong>Company Registration</strong><br>Startup & business incorporation handled.</div>
      <div class="card">📄<br><strong>Document Attestation</strong><br>Fast notarization and validation.</div>
      <div class="card">🧬<br><strong>Legal Heirship & Name Change</strong><br>Guidance from filing to approval.</div>
    </div>
  </section>

  <section id="credentials">
    <h3>Credentials</h3>
    <div class="grid">
      <div class="card">🎓 B.A. LL.B (Hons)</div>
      <div class="card">📜 Member – Bar Council of TN & Puducherry</div>
      <div class="card">🏛 Practice in High Court & Sessions Courts</div>
      <div class="card">🌐 Languages: English, Tamil, Hindi</div>
    </div>
  </section>

  <section>
    <h3>Client Testimonials</h3>
    <div class="grid">
      <div class="card">"Prompt, reliable and professional support in our property dispute."<br><strong>- Ramya S.</strong></div>
      <div class="card">"Thank you for the strong representation and detailed updates."<br><strong>- Rajesh M.</strong></div>
      <div class="card">"I appreciate the transparent legal advice throughout."<br><strong>- Sneha K.</strong></div>
    </div>
  </section>

  <section>
    <h3>Case Highlights</h3>
    <div class="grid">
      <div class="card"><strong>🏠 Property Title Secured:</strong><br> Represented client in land ownership dispute.</div>
      <div class="card"><strong>👨‍👩‍👧‍👦 Custody Case Won:</strong><br> Balanced family rights with child’s well-being.</div>
      <div class="card"><strong>📜 Business Contract Review:</strong><br> Helped avoid a ₹50L liability clause.</div>
    </div>
  </section>

  <section id="contact">
    <h3>Contact</h3>
    <div class="contact">
      <p>📞 <strong><a href="tel:+918248890088" style="color: var(--accent-color);">+91 82488 90088</a></strong></p>
      <p>📧 <a href="mailto:advocatehardhik@gmail.com" style="color: var(--accent-color);">advocatehardhik@gmail.com</a></p>
      <p>📍 Based in Chennai, Tamil Nadu</p>
      <p>🗺️ <a href="https://goo.gl/maps/Xy123YourLocation" target="_blank" style="color: var(--accent-color);">Google Maps</a></p>
    </div>
  </section>

  <footer>
    &copy; 2025 Advocate Hardhik R | All Rights Reserved<br />
    <a href="#">Privacy Policy</a> | <a href="#">Terms</a>
  </footer>

  <a class="floating-contact" href="tel:+918248890088">📞 Call Advocate</a>

  <!-- Floating Contact Window -->
  <div class="floating-window" id="floatingWindow">
    <h4>Need Help?</h4>
    <p>We are here to assist you with any legal queries.</p>
    <button onclick="location.href='tel:+918248890088'">Call Now</button>
  </div>

  <script>
    const floatingWindow = document.getElementById('floatingWindow');

    // Show the floating window after a few seconds
    setTimeout(() => {
      floatingWindow.classList.add('show');
    }, 2000);
  </script>

</body>

</html>
