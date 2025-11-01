# Mike-Website
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Mike Lester Ishmael - Professional Profile</title>
  <style>
    /* ===== GLOBAL STYLES ===== */
    :root {
      --primary: #004aad;
      --primary-dark: #003b8a;
      --bg: #f9f9f9;
      --text: #333;
      --light: #ffffff;
    }

    body {
      font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
      background-color: var(--bg);
      color: var(--text);
      line-height: 1.6;
      overflow-x: hidden;
    }

    /* ===== HEADER ===== */
    header {
      background: linear-gradient(135deg, var(--primary), var(--primary-dark));
      color: var(--light);
      padding: 60px 20px;
      text-align: center;
      position: relative;
    }

    header img {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      object-fit: cover;
      border: 4px solid var(--light);
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.3);
      margin-bottom: 15px;
      animation: fadeIn 1s ease-in-out;
    }

    header h1 {
      font-size: 2.2em;
      text-transform: uppercase;
      margin: 10px 0 5px;
    }

    header p {
      font-style: italic;
      opacity: 0.9;
      animation: fadeIn 2s ease-in-out;
    }

    .resume-btn {
      display: inline-block;
      margin-top: 15px;
      background-color: var(--light);
      color: var(--primary);
      padding: 12px 24px;
      border-radius: 6px;
      text-decoration: none;
      font-weight: bold;
      transition: all 0.3s ease;
    }

    .resume-btn:hover {
      background-color: var(--primary-dark);
      color: var(--light);
      transform: scale(1.05);
    }

    /* ===== CONTAINER ===== */
    .container {
      max-width: 900px;
      margin: 40px auto;
      background: var(--light);
      padding: 40px;
      border-radius: 12px;
      box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
      animation: fadeUp 0.8s ease-in-out;
    }

    h2 {
      border-bottom: 2px solid var(--primary);
      padding-bottom: 5px;
      color: var(--primary);
      margin-top: 40px;
    }

    .section {
      margin-bottom: 25px;
    }

    .skills-list,
    .work-item {
      margin-left: 20px;
    }

    .contact-info p {
      margin: 5px 0;
    }

    /* ===== TOOLS SECTION ===== */
    .tools-section {
      display: none;
      background-color: #f0f5ff;
      border: 1px solid #d0d9ff;
      padding: 20px;
      border-radius: 8px;
      margin-top: 15px;
      animation: fadeIn 0.6s ease-in-out;
    }

    .tools-btn {
      background-color: var(--primary);
      color: white;
      border: none;
      padding: 12px 24px;
      border-radius: 6px;
      cursor: pointer;
      font-size: 1em;
      transition: all 0.3s ease;
    }

    .tools-btn:hover {
      background-color: var(--primary-dark);
      transform: scale(1.05);
    }

    /* ===== FOOTER ===== */
    footer {
      text-align: center;
      padding: 20px;
      background-color: var(--primary);
      color: var(--light);
      font-size: 0.9em;
      margin-top: 40px;
    }

    /* ===== ANIMATIONS ===== */
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(10px); }
      to { opacity: 1; transform: translateY(0); }
    }

    @keyframes fadeUp {
      from { opacity: 0; transform: translateY(30px); }
      to { opacity: 1; transform: translateY(0); }
    }

    /* ===== RESPONSIVE DESIGN ===== */
    @media (max-width: 768px) {
      header h1 { font-size: 1.8em; }
      .container { padding: 25px; margin: 20px; }
      .resume-btn, .tools-btn { width: 90%; }
    }
  </style>
</head>
<body>
  <header>
    <img src="IMG_3495.jpeg" alt="Mike Lester Ishmael Photo">
    <h1>Mike Lester Ishmael</h1>
    <p>Applicant | Versatile Professional</p>
    <a href="Mike_Ishmael_CV.pdf" class="resume-btn" download>📄 Download My Résumé</a>
  </header>

  <div class="container">
    <section class="section">
      <h2>Profile</h2>
      <p>
        Versatile professional with a strong background in sales, lead generation, and customer support. 
        Proven expertise in building relationships, identifying opportunities, and delivering effective 
        solutions to meet business and client needs. Skilled in strategic communication, problem-solving, 
        and adapting to dynamic environments. Recognized for a results-driven mindset, technical proficiency, 
        and the ability to collaborate across teams to achieve organizational goals.
      </p>
    </section>

    <section class="section contact-info">
      <h2>Contact</h2>
      <p><strong>Phone:</strong> +63 927 112 0898</p>
      <p><strong>Email:</strong> <a href="mailto:ishmaelmikelester@gmail.com">ishmaelmikelester@gmail.com</a></p>
      <p><strong>Address:</strong> Gallarde St. Zone II, Digos City, Davao del Sur 8002</p>
    </section>

    <section class="section">
      <h2>Skills</h2>
      <ul class="skills-list">
        <li>Learning Proficiency</li>
        <li>Problem Solving and Troubleshooting</li>
        <li>Leadership</li>
        <li>Strong Organizational Skills</li>
        <li>Empathy</li>
        <li>Decision-Making</li>
        <li>Adaptability</li>
      </ul>
    </section>

    <section class="section">
      <h2>Education</h2>
      <p><strong>Bachelor of Science in Information Technology</strong><br>
      AMA Computer College (2017 - 2018)</p>
    </section>

    <section class="section">
      <h2>Work Experience</h2>

      <div class="work-item">
        <h3>Real Estate Cold Caller</h3>
        <p><em>M-Power Solutions | October 2023 - March 2025</em></p>
        <p>
          Generated leads and set appointments through outbound calls to prospective clients. 
          Initiated conversations with property owners and potential sellers, assessed needs, 
          and qualified them as potential leads for the real estate team.
        </p>
      </div>

      <div class="work-item">
        <h3>Lead Generation Specialist</h3>
        <p><em>Novally | April 2021 - September 2023</em></p>
        <p>
          Researched and identified prospective clients across markets and industries. 
          Conducted strategic outreach via calls and emails to initiate meaningful conversations, 
          qualify leads, and strengthen the sales pipeline to support business growth.
        </p>
      </div>

      <div class="work-item">
        <h3>Technical Support Representative</h3>
        <p><em>Teleperformance | December 2018 - December 2020</em></p>
        <p>
          Provided technical assistance to customers via phone, email, or chat. 
          Diagnosed and resolved issues promptly to ensure customer satisfaction, 
          while escalating complex cases when needed to improve overall service efficiency.
        </p>
      </div>
    </section>

    <section class="section">
      <h2>Tools & Software</h2>
      <button class="tools-btn" onclick="toggleTools()">🧰 View Tools I'm Skilled In</button>
      <div class="tools-section" id="toolsList">
        <ul>
          <li>Gladly</li>
          <li>OrderDesk</li>
          <li>Shopify</li>
          <li>STORD</li>
          <li>Outlook</li>
          <li>Excel</li>
        </ul>
      </div>
    </section>
  </div>

  <footer>
    <p>© 2025 Mike Lester Ishmael | All Rights Reserved</p>
  </footer>

  <script>
    // Toggle Tools Section
    function toggleTools() {
      const section = document.getElementById("toolsList");
      section.style.display = (section.style.display === "none" || section.style.display === "")
        ? "block"
        : "none";
    }

    // Subtle fade-in animation when page loads
    window.addEventListener("load", () => {
      document.body.style.opacity = "1";
      document.body.style.transition = "opacity 1s ease-in";
    });
  </script>
</body>
</html>
