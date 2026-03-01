Portfolio Reflection – Juan Davila

Project Overview

This project demonstrates the development of a full-stack dashboard application connected to a MongoDB database using a custom-built CRUD Python module. The application allows dynamic querying, filtering, and visualization of animal rescue data to support Grazioso Salvare’s operational needs. The program integrates database management, backend logic, and front-end dashboard interactivity into a cohesive system.


I focused on writing maintainable and adaptable programs using best practices. I started with separation of concerns, modular design, and clear documentation. In Project One, I built a dedicated CRUD Python module responsible solely for database operations. This allowed Project Two’s dashboard code to remain clean and focused only on user interaction and visualization logic. By separating database access from the front-end components, I improved readability, reduced duplication, and made debugging significantly easier.

The advantage of this design was flexibility. Because the CRUD module abstracts MongoDB operations into reusable methods, I can easily reuse it in future projects that require database connectivity, such as web applications, analytics dashboards, or API-based services. If the database schema changes or authentication needs to be updated, I only need to modify the CRUD module rather than the entire application. This approach aligns with industry best practices for scalable and maintainable software development.


When approaching the database and dashboard requirements requested by Grazioso Salvare, I began by analyzing the functional requirements and identifying the necessary data queries. I translated client needs—such as filtering by breed, age, or rescue category—into structured MongoDB queries using operators like $in, $gte, $lte, and regex filtering.

Compared to earlier assignments in other courses, this project required more system-level thinking. Instead of solving isolated programming problems, I designed an integrated system where the database, backend logic, and user interface worked together. I approached the problem incrementally:

1. Establish database connectivity.

2. Validate CRUD functionality independently.

3. Integrate the module into the dashboard.

4. Implement callback logic for dynamic updates.

5. Test and debug query results.

In the future, I would continue using this layered development strategy, along with schema planning, indexing considerations, and early validation testing to ensure performance and scalability for client-driven database systems.

What Computer Scientists Do and Why It Matters

Computer scientists design systems that transform raw data into meaningful, actionable information. In this project, I built a system that enables Grazioso Salvare to quickly identify suitable rescue dogs using real-time filtering and visualizations. Instead of manually reviewing large datasets, the organization can use an interactive dashboard to make data driven decisions efficiently.

This type of solution improves productivity, reduces human error, and supports better operational planning. For organizations like Grazioso Salvare, the ability to query and visualize data directly impacts how effectively they can coordinate rescue efforts.

