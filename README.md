# CS-340
Client/Sever Development

CS-340 Portfolio Reflection: Grazioso Salvare Dashboard

Kaley Lavery

Writing Maintainable, Readable, and Adaptable Programs

Throughout this course, I focused on writing code that is modular, readable, and easy to maintain. This was especially evident in the development of my CRUD Python module in Project One, which I reused in Project Two to connect the dashboard to the MongoDB database.

By separating database logic into its own CRUD module, I avoided duplicating database code throughout the dashboard. This made the application easier to debug, update, and extend. For example, if authentication details or database queries need to change in the future, they can be updated in one place without modifying the dashboard logic.

This approach also makes the CRUD module reusable beyond this project. In the future, I could use the same module to support a different dashboard, a REST API, or an analytics script that accesses the same MongoDB data. Designing reusable components improved both code quality and development efficiency.

Approaching Problems as a Computer Scientist

When working on the Grazioso Salvare dashboard, I approached the problem by first understanding the client’s requirements and breaking them into smaller, manageable tasks. I identified the database as the model, the dashboard widgets as the view, and the CRUD module and callbacks as the controller, following the MVC design pattern.

This project differed from earlier assignments in other courses because it required integrating multiple technologies—MongoDB, Python, Dash, and data visualization—rather than solving isolated problems. I had to consider how user interactions would affect data queries and visual outputs in real time.

In the future, I would apply this same structured approach by clearly defining requirements, designing the database schema to support client needs, and building flexible queries that allow for expansion as requirements change.

What Computer Scientists Do and Why It Matters

Computer scientists design systems that transform raw data into meaningful information that supports decision-making. In this project, the dashboard enables Grazioso Salvare to efficiently identify animals that may be suitable for different types of rescue training.

By automating filtering, visualization, and geolocation mapping, this application reduces manual effort, minimizes user error, and improves operational efficiency. Projects like this matter because they help organizations work faster, make better decisions, and focus on their mission rather than on managing data.

My work on this project demonstrates how software solutions can directly support real-world goals, such as improving rescue operations and saving lives.

Portfolio Artifacts

This repository includes the following artifacts from CS-340:

ProjectTwoDashboard.ipynb – Interactive MongoDB dashboard

CRUD_Python_Module.py – Reusable database access module

README.docx – Project Two documentation with screenshots

Dashboard screenshots demonstrating all required filters and functionality

Conclusion

This project strengthened my understanding of database-driven applications, modular design, and client-focused development. It represents a strong example of my ability to design, implement, and document a full-stack application suitable for inclusion in my professional portfolio.
