# airbnb-clone-project
## Overview
This project is a clone of the Airbnb web application. It aims to replicate the core functionalities of the AirBnB platform including user authentication, property listings, bookings, and reviews. The main objective is to practise and understand how professional software systems are built from the ground up.
## Project goals
- Understand and define the project scope.
- Identify key features and implementation plans.
- Adhere to timelines and milestones.
- Leverage modern web development tools and technologies.
- Collaborate effectively in a simulated team environment.
## 💻 Tech Stack

### Frontend
<div>
    <img src="https://img.shields.io/badge/-React-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
    <img src="https://img.shields.io/badge/-TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
    <img src="https://img.shields.io/badge/-Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white" />
    <img src="https://img.shields.io/badge/-TailwindCSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" />
</div>

### Backend
<div>
    <img src="https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
    <img src="https://img.shields.io/badge/-Django-092E20?style=for-the-badge&logo=django&logoColor=white" />
    <img src="https://img.shields.io/badge/-MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
</div>

### State Management & Tools
<div>
    <img src="https://img.shields.io/badge/-Redux-764ABC?style=for-the-badge&logo=redux&logoColor=white" />
    <img src="https://img.shields.io/badge/-Context%20API-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
    <img src="https://img.shields.io/badge/-REST%20API-FF6F00?style=for-the-badge&logo=api&logoColor=white" />
    <img src="https://img.shields.io/badge/-Jest-C21325?style=for-the-badge&logo=jest&logoColor=white" />
</div>

## UI/UX Design Planning

Creating a seamless and intuitive user experience is central to the success of the AirBnB Clone Project. Our design approach focuses on simplicity, responsiveness, and clarity to ensure users can easily search, view, and book properties.

---

### 🔍 Design Goals

- Create a clean and responsive layout for all screen sizes (mobile-first design).
- Ensure fast and intuitive navigation between pages.
- Highlight essential booking information (price, location, availability).
- Provide feedback through UI elements (loaders, error messages, confirmation).
- Reduce friction in booking flow to improve user conversion.

---

### 📌 Key UI Features

- **Responsive Navigation Bar** with links to Home, Explore, and Bookings.
- **Search Bar** with location, date, and guest filters.
- **Card-Based Property Listings** with hover effects.
- **Detailed Modal/Pages** for each property with full information.
- **Interactive Calendar** for date selection.
- **Checkout View** with a breakdown of pricing, guest details, and payment simulation.

---

### 🗂 Primary Pages

| Page Name               | Description                                                                 |
|-------------------------|-----------------------------------------------------------------------------|
| **Property Listing View** | Displays a grid/list of available properties. Each item includes thumbnail, location, rating, and price. |
| **Listing Detailed View** | Shows full details of a selected property: gallery, description, host info, reviews, and date selector. |
| **Simple Checkout View** | Summarizes booking information. Allows users to confirm details, simulate payment, and complete reservation. |

---

### 💡 Importance of User-Friendly Design

In any booking system, **user experience directly impacts engagement and conversions**. A confusing interface can cause users to abandon the process. By prioritizing intuitive layouts, quick feedback, and easy navigation, we ensure:

- **Reduced cognitive load** for users making decisions.
- **Faster task completion**, especially for mobile users.
- **Trust-building** through a consistent and visually appealing design.
- **Accessibility** for all users, regardless of device or ability.


### 🎨 Figma Design Properties

#### Typography

| Role             | Font Family     | Weight     | Size             |
|------------------|------------------|------------|------------------|
| Primary Font     | Circular         | Medium (500) | 16px           |
| Headings         | Circular         | Bold (700)   | 24px – 32px     |
| Secondary Text   | Circular         | Book (400)   | 14px            |

#### Color Styles

| Role             | Hex Code   | Usage Example                      |
|------------------|------------|------------------------------------|
| Primary          | #FF5A5F    | Main buttons, call-to-actions      |
| Secondary        | #008489    | Tags, accents                      |
| Background       | #FFFFFF    | General backgrounds                |
| Text             | #222222    | Main content text                  |
| Secondary Text   | #717171    | Descriptive or muted text          |


These colors are applied to different components such as buttons, texts, icons, and containers based on context within the Figma mockup.


### Importance of Identifying Design Properties

Understanding and documenting the design properties of a mockup is essential because:

-  It ensures **visual consistency** across the project.
-  It speeds up development by reducing back-and-forth with designers.
-  It improves **readability and accessibility**.
-  It strengthens **collaboration** between design and dev teams.

  ## 👥 Project Roles and Responsibilities

In this project, the following roles and responsibilities are assigned to ensure smooth collaboration and successful delivery of the Airbnb Clone application. Each role contributes to the project’s success through focused efforts and teamwork.

| **Role**              | **Responsibilities**                                                                 |
|-----------------------|--------------------------------------------------------------------------------------|
| **Project Manager**   |  Oversee project timeline and ensure milestones are met. <br>  Coordinate the team to ensure collaboration and communication. <br>  Manage project deliverables and resources. <br>  Track and mitigate risks to ensure project success. |
| **Frontend Developers**  |  Implement UI components based on the design mockups. <br>  Ensure a responsive and mobile-friendly design. <br>  Work closely with designers to maintain design consistency. <br>  Integrate frontend components with backend APIs. |
| **Backend Developers**  |  Develop and maintain server-side logic for the application. <br>  Manage the database and design efficient data models. <br>  Build and integrate APIs for seamless communication with the frontend. <br>  Implement security measures and optimize server performance. |
| **Designers**         |  Create wireframes, mockups, and prototypes. <br>  Maintain and update the design system to ensure visual consistency. <br>  Ensure a high-quality user experience (UX) by designing intuitive layouts. <br>  Collaborate with frontend developers to implement the UI designs. |
| **QA/Testers**       |  Write test cases and perform thorough testing of the application. <br>  Conduct both manual and automated testing. <br>  Identify, document, and report bugs and issues. <br>  Verify bug fixes and perform regression testing. |
| **DevOps Engineers**  |  Manage deployment and continuous integration/continuous deployment (CI/CD) pipelines. <br>  Maintain server infrastructure and cloud-based environments. <br>  Monitor application performance and ensure high uptime. <br>  Implement security measures and ensure production environment compliance. |
| **Product Owner**     |  Define and prioritize product features and user requirements. <br>  Represent stakeholders’ interests and act as the liaison between the team and clients. <br>  Ensure that the product delivers value to the end-users. <br>  Make key decisions regarding scope and approve completed work. |
| **Scrum Master**     |  Facilitate Agile processes, ensuring the team follows Scrum practices. <br>  Remove blockers and obstacles hindering the team’s progress. <br>  Organize Scrum ceremonies, such as daily stand-ups and sprint planning meetings. <br>  Foster a collaborative and productive team environment. <br>  Ensure continuous improvement through retrospectives and feedback. |

These roles are critical to the success of the **Airbnb Clone Project**. Each role contributes to the project by ensuring effective communication, smooth execution, and high-quality deliverables. Clear responsibilities help align team efforts and streamline the development process.
