<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Pratik Mondal | Data Analyst Portfolio</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <style>
    body { font-family: 'Open Sans', Arial, sans-serif; background: #F7FBFF; color: #222; margin: 0; }
    .header { background: #17334D; color: #fff; padding: 30px 10%; }
    .header h1 { margin: 0; font-size: 2.8em; }
    .header h2 { margin: 10px 0 0 0; font-size: 1.5em; color: #A2C2E2; }
    nav { background: #235185; text-align: center; padding: 10px 0; }
    nav a { color: #fff; text-decoration: none; margin: 0 15px; font-weight: 600; }
    nav a:hover { color: #FFD700; }
    section { padding: 40px 10%; border-bottom: 1px solid #eaeaea; }
    .card { background: #fff; padding: 25px; border-radius: 7px; margin-bottom: 30px; box-shadow: 0 3px 12px rgba(0,0,0,0.05); }
    .skills { display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 25px;}
    .skills div { background: #E9F3FB; padding: 18px; border-radius: 5px;}
    .timeline { border-left: 3px solid #235185; padding-left: 30px; }
    .timeline-entry { margin-bottom: 30px; }
    .timeline-title { font-size: 1.15em; color: #235185; font-weight: bold; }
    .project-list { display: grid; grid-template-columns: repeat(auto-fit, minmax(320px, 1fr)); gap: 25px; }
    .project-card { background: #E9F3FB; padding: 20px; border-radius: 5px; }
    .button { background: #235185; color: #fff; border: none; padding: 10px 22px; border-radius: 4px; font-size: 1em; text-decoration: none; margin-top: 8px; }
    .button:hover { background: #17334D; color: #FFD700; }
    .contact-info { font-size: 1.1em; line-height: 1.8; }
    @media (max-width: 600px) {
      section { padding: 25px 4%; }
      .header { padding: 25px 4%; }
      .card { padding: 15px;}
      .skills, .project-list { grid-template-columns: 1fr;}
    }
  </style>
</head>
<body>

  <div class="header">
    <h1>Pratik Mondal</h1>
    <h2>Aspiring Data Analyst & Business Intelligence Enthusiast</h2>
    <div>Kolkata, West Bengal | <a href="mailto:mondalpratik499@gmail.com" style="color:#FFD700;">mondalpratik499@gmail.com</a></div>
    <a href="https://www.linkedin.com/in/pratik-mondal-295748213" class="button" target="_blank">LinkedIn Profile</a>
  </div>

  <nav>
    <a href="#about">About</a>
    <a href="#skills">Skills</a>
    <a href="#experience">Experience</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about">
    <div class="card">
      <h2>About Me</h2>
      <p>
        Aspiring Data Analyst with a strong foundation in Power BI, SQL (MySQL, PostgreSQL), and data analysis. Skilled in dashboard design, data modeling, and transforming business needs into insights. Passionate about data visualization and storytelling, with hands-on experience in DAX, Power Query, and strategic analytics.
      </p>
    </div>
  </section>

  <section id="skills">
    <div class="card">
      <h2>Skills</h2>
      <div class="skills">
        <div><strong>Power BI</strong><br>DAX, Power Query, Dashboard Design</div>
        <div><strong>SQL</strong><br>MySQL, PostgreSQL, Query Optimization</div>
        <div><strong>Excel</strong><br>Advanced Formulas, Data Cleaning</div>
        <div><strong>ETL</strong><br>Extract, Transform, Load</div>
        <div><strong>Data Modeling</strong><br>KPI Development, Business Insights</div>
        <div><strong>Languages</strong><br>English, Hindi, Bengali</div>
      </div>
    </div>
  </section>

  <section id="experience">
    <div class="card timeline">
      <h2>Experience & Education</h2>
      <div class="timeline-entry">
        <div class="timeline-title">Team Lead, Project Team-29 (Excelerate)</div>
        <div>Spearheaded a 3-member team for project charter development and alignment. Led team/sponsor meetings and ensured timely deliverables.</div>
      </div>
      <div class="timeline-entry">
        <div class="timeline-title">Associate Data Analyst Intern (Excelerate)</div>
        <div>Built & maintained Power BI dashboards, cleaned large datasets with SQL, delivered measurable analytics, reduced reporting effort by 30%.</div>
      </div>
      <div class="timeline-entry">
        <div class="timeline-title">Education</div>
        <div>Bachelor in Commerce (Honours in Accountancy)<br>Kalinga University, 2019-2021, 70%</div>
      </div>
      <div class="timeline-entry">
        <div class="timeline-title">Certifications</div>
        <div>
          Microsoft Power BI Data Analyst (Coursera)<br>
          SQL Practice Queries (CodeChef, June 2025)
        </div>
      </div>
    </div>
  </section>

  <section id="projects">
    <div class="card">
      <h2>Projects</h2>
      <div class="project-list">
        <div class="project-card">
          <strong>Classic Model Sales Dashboard</strong><br>
          Real-time dashboard with advanced KPIs & interactive visuals.<br>
          <a class="button" href="https://github.com/pratikk609/power-bi-projects/blob/main/classic%20model.pbix" target="_blank">View Project</a>
        </div>
        <div class="project-card">
          <strong>Pizza Sales Analysis</strong><br>
          Sales trends, patterns via interactive dashboard for inventory/marketing.<br>
          <a class="button" href="https://github.com/pratikk609/power-bi-projects/blob/main/pizza%20sales.pbix" target="_blank">View Project</a>
        </div>
        <div class="project-card">
          <strong>Spotify 2023 Insights</strong><br>
          Streaming/listener data with ranking, segmentation.<br>
          <a class="button" href="https://github.com/pratikk609/power-bi-projects/blob/main/Spotify%202023.pbix" target="_blank">View Project</a>
        </div>
        <div class="project-card">
          <strong>EDA & Dashboard Pipeline</strong><br>
          SQL/Power BI, master analysis tables with KPI dashboards.<br>
          <a class="button" href="https://www.linkedin.com/in/pratik-mondal-295748213/recent-activity/all" target="_blank">View on LinkedIn</a>
        </div>
      </div>
    </div>
  </section>

  <section id="contact">
    <div class="card">
      <h2>Contact</h2>
      <div class="contact-info">
        <div><strong>Email:</strong> mondalpratik499@gmail.com</div>
        <div><strong>Phone:</strong> 8235441843</div>
        <div><strong>Location:</strong> Kolkata, WB</div>
        <div>
          <a class="button" href="https://www.linkedin.com/in/pratik-mondal-295748213" target="_blank">LinkedIn Profile</a>
        </div>
      </div>
    </div>
  </section>

</body>
</html>
