# alyssawoung.github.io

---
layout: default
title: "Alyssa Woung | Business Analytics Portfolio"
---

<div style="text-align:center;">
  <img src="https://via.placeholder.com/120x120.png?text=AW" alt="Alyssa Woung" style="border-radius:50%;border:3px solid #fab1e0;" />
  <h1 style="color:#fab1e0;margin-top:1rem;">Alyssa Woung</h1>
  <h2 style="color:silver;font-weight:400;margin-top:-1rem;">Business Analytics Portfolio</h2>
  <p style="margin-top:1.5rem;font-size:1.15em;color:#eceded;">
    I turn data into action with creative storytelling, visualization, and analytics. Explore my projects and connect below.
  </p>
  <div style="margin-top: 2rem;">
    <a href="https://www.linkedin.com/in/alysswoung" target="_blank" style="background:#fab1e0;color:#181718;padding:8px 18px;border-radius:8px;text-decoration:none;font-weight:bold;margin-right:10px;">LinkedIn</a>
    <a href="/projects.html" style="background:#c4c4c4;color:#181718;padding:8px 18px;border-radius:8px;text-decoration:none;font-weight:bold;">Featured Projects</a>
  </div>
</div>


---
layout: default
title: "Projects | Alyssa Woung"
permalink: /projects.html
---

## Projects

### [Mass Shooting Analysis (Tableau)](https://public.tableau.com/views/TableauProject-DSS315/MassShootingAnalysis?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
A data visualization project using Tableau that analyzes trends, locations, and statistics about mass shooting incidents to bring actionable insight to decision makers.

### Additional Projects
- Customer Churn Predictor (R & Tableau)
- Sales Dashboard using Excel
- Survey Data Analysis (R, Excel)

---
layout: default
title: "Contact | Alyssa Woung"
permalink: /contact.html
---

## Contact

Interested in working together or learning more?  
Find me on [LinkedIn](https://www.linkedin.com/in/alysswoung) or send an email below.

<form action="mailto:alyssa.email.placeholder@example.com" method="POST" enctype="text/plain">
  <label for="name">Name:</label><br>
  <input type="text" id="name" name="name" style="width:80%; margin-bottom:1rem;"><br>
  <label for="email">Email:</label><br>
  <input type="email" id="email" name="email" style="width:80%; margin-bottom:1rem;"><br>
  <label for="message">Message:</label><br>
  <textarea id="message" name="message" rows="5" style="width:80%;"></textarea><br>
  <button type="submit" style="margin-top:1rem; background:#fab1e0; color:#181718; padding:8px 18px; border-radius:8px; font-weight:bold;">Send</button>
</form>


*More details & links available on request.*


body {
  margin: 0;
  padding: 0;
  font-family: 'Montserrat', Arial, sans-serif;
  background: linear-gradient(135deg, #efb9df, #181718 70%);
  color: #eceded;
  min-height: 100vh;
}
main {
  max-width: 700px;
  margin: 3rem auto 2rem;
  background: rgba(30, 28, 38, 0.95);
  border-radius: 18px;
  padding: 2rem 2.5rem;
  box-shadow: 0 2px 12px #fab1e020;
}
.navbar {
  background: #181718;
  box-shadow: 0 2px 8px #0004;
  padding: 0.7em 0;
  text-align: center;
}
.navbar ul {
  list-style: none;
  padding: 0;
  margin: 0;
  display: inline-flex;
  gap: 1.8em;
}
.navbar li {
  display: inline;
}
.navbar a {
  color: #fff;
  text-decoration: none;
  font-weight: bold;
  letter-spacing: 1px;
  padding: 0.4em 1.1em;
  border-radius: 7px;
  transition: background 0.18s, color 0.15s;
}
.navbar a.active, .navbar a:hover {
  background: #fab1e0;
  color: #181718;
}
@media (max-width: 600px) {
  main { padding: 1em 0.3em; }
  .navbar ul { gap: 0.8em; }
}
