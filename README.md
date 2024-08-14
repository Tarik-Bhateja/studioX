# studioX

## Situation
- **Context:** A tattoo studio owner in my hometown wanted a solution to manage his studio operations remotely as he was relocating abroad.
- **Objective:** Develop a comprehensive web platform to handle online appointment scheduling, portfolio management, staff administration, client communication, and consent management.

## Task
- **Your Role:** I was responsible for understanding the client's requirements and developing the backend of the platform.
- **Challenges:** 
  - Assisting a non-technical client in understanding different solutions.
  - Handling a large number of tattoo photographs for the portfolio.
  - Designing an easy-to-use interface for the staff.
  - Considering edge cases for better functionality.

## Action
- **Steps Taken:**
  - Developed the backend using Django, integrated with Cloudinary for image handling, and set up PostgreSQL for the database.
  - Deployed the website on AWS EC2 using Nginx and Gunicorn for server management.
  - Implemented features for:
    - **Online Appointments:** Users can book appointments by selecting their preferred artist and tattoo style.
    - **Staff/Admin Management:** Admins can create staff accounts, approve portfolio submissions, and assign appointments. Staff can update their portfolios, manage consent forms, and handle certificates.
    - **Public Tattoo Gallery:** A gallery for showcasing tattoo images, with options for consent downloads and certificate verification.
    - **Client Interaction:** Integrated Brevo (formerly SendinBlue) for a chatbot and newsletter service.
  - **Tools & Technologies:** Django, Cloudinary, Brevo SMTP, Brevo Chatbot, Brevo Newsletter, Google Analytics, HTML, CSS, JavaScript, AWS EC2, Nginx, Gunicorn.

## Result
- **Outcome:** The platform successfully automated studio operations, improving efficiency and client satisfaction. The owner could manage his studio remotely, while the staff found it easier to handle their tasks.
- **Learnings:** Gained experience in developing user-friendly interfaces, managing large media files, and integrating cloud-based services.

