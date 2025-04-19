Project Title

My Portfolio Website

Description

This is a personal portfolio website built with React.js and integrated with EmailJS to provide a contact form that sends messages directly to my email. It showcases my skills, projects, and work experience in an interactive, responsive design.

Features

Home Section: Introduction and a brief overview of who I am and what I do.

About Section: Detailed biography, skills, and tools I use.

Projects Section: Showcase of selected projects with links to live demos and GitHub repositories.

Contact Section: Interactive form powered by EmailJS for direct messaging without a backend server.

Responsive Design: Fully optimized for desktop, tablet, and mobile viewports.

Smooth Animations: Fade-in effects on scroll using a custom RevealOnScroll component.

Tech Stack

Frontend: React.js, Tailwind CSS

Email Service: EmailJS (no backend required)

Tooling: Vite, npm

Installation

Clone the repository:

git clone https://github.com/your-username/your-portfolio.git

Navigate to the project directory:

cd your-portfolio

Install dependencies:

npm install

Create a .env file in the root directory and add your EmailJS credentials:

VITE_SERVICE_ID=your_service_id
VITE_TEMPLATE_ID=your_template_id
VITE_PUBLIC_KEY=your_public_key

Start the development server:

npm run dev

Usage

Access the live website at http://localhost:3000.

Fill out the contact form and click "Send Message" to test the EmailJS integration.

Configuration

Modify the following environment variables in the .env file:

VITE_SERVICE_ID: Your EmailJS service ID.

VITE_TEMPLATE_ID: Your EmailJS template ID.

VITE_PUBLIC_KEY: Your EmailJS public key.

Contributing

Contributions are welcome! Please open an issue or submit a pull request on GitHub.

License

This project is licensed under the MIT License. See the LICENSE file for details.

Thank you for visiting my portfolio! Feel free to connect with me on LinkedIn or GitHub.

