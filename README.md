# Flask Talk
### Summary
At the end of year of tutoring in my high school's AP Computer Science Principles class, I was offered the opportunity to create a ciricculum for a week of class. I decided to teach Flask, a microframework that creates backends, in conjunction with Jinja, a templating engine. While Flask isn't a full MVC framework, it can create and send templated HTML to the client, allowing limited web development function.

I wrote a backend in Flask (available at /backend) that processed frontend requests and used a SQLite database to track posts and user accounts. I deployed the master backend to Heroku and wrote some starter code that my students could use to create a smaller backend that returned templated HTML. While not a true backend/frontend setup, this simplified backend allowed students to visualize backend concepts without having to deal with databases or  complex data types.

The best part of this master/secondary backend setup was that every project was connected to the same database, so when each student finished their project, the finished projects could communicate with each other, creating an interactive albeit easy to make project.
### Reflection
While the code worked perfectly, in hindsight the amount of code required to fully finish the website was too much for one week, and while some students were able to finish their projects, some students were unable to fully interface their projects with other projects. If I were to do it again, I would fully write a simple route (/post), allowing students to follow the example already in their code instead of having to follow my lecture

---
### Technologies Used
 - Python
 - HTML/CSS
 - Flask (web microframework)
 - Jinja (HTML Templating Engine)
 - SQLite (SQL Database)
 - SQLAlchemy (SQL ORM) 
 - Google Slides/Google Docs for printouts/lecture slides.
