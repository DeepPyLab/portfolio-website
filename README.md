# Portfolio Website

Welcome to my portfolio website repository! This is a fully functional and visually engaging personal portfolio to showcase my skills and projects in frontend and backend development, manual testing, and test automation engineering.

## Project Overview

This portfolio site includes:

- **Home Page**: An introduction with a call-to-action.
- **About Me**: A summary of my background, skills, and experience.
- **Projects**: A showcase of my major projects with links to live demos and GitHub repos.
- **Skills**: Display of technical skills and proficiencies.
- **Contact**: A form to send me messages directly.

## Built With

- **Frontend**: [React](https://reactjs.org/) - A JavaScript library for building user interfaces.
- **Backend**: [Node.js](https://nodejs.org/) with [Express](https://expressjs.com/) - Server-side functionality to handle contact form submissions.
- **Styling**: CSS, with options to expand to SCSS or TailwindCSS for advanced styling.
- **Email Service**: [Nodemailer](https://nodemailer.com/) - For handling contact form submissions and notifications.

## Features

- **Responsive Design**: Optimized for desktop and mobile devices.
- **Interactive UI**: Smooth navigation and animations for better user experience.
- **Contact Form**: Users can reach out to me directly through the contact form, with backend support to send emails.
- **Project Showcase**: Detailed pages for each project, including technologies used and links.

## Getting Started

### Prerequisites

- **Node.js**: Make sure you have Node.js installed (https://nodejs.org/).
- **Git**: Ensure Git is installed to clone the repository.

### Installation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/DeepPyLab/portfolio-website.git
    cd portfolio-website
    ```

2. **Install Dependencies**:

   - **Frontend**:
     ```bash
     cd frontend
     npm install
     ```

   - **Backend**:
     ```bash
     cd ../backend
     npm install
     ```

3. **Set Up Environment Variables**:
   - In the `backend` folder, create a `.env` file:
     ```
     EMAIL_USER=your-email@gmail.com
     EMAIL_PASS=your-email-password
     ```

### Running the Application

1. **Start Backend Server**:
   ```bash
   cd backend
   node server.js

2. **Start Frontend Server**

    Open a new terminal, go to the `frontend` folder, and run:

    ```bash
    cd frontend
    npm start

**The frontend will be available at http://localhost:3000 and the backend at http://localhost:5000**

### Project Structure

    ```bash
    portfolio-website/
    ├── frontend/          # React frontend application
    └── backend/           # Node.js/Express backend server

### Deployment

This project is set up to be easily deployable on services like Vercel (for frontend) and Render (for backend). For deployment instructions, see the respective platforms' documentation.

### Contributing

Feel free to open a pull request if you'd like to suggest any improvements or add features.

### Contact

If you have any questions, feel free to reach out:

Email: yashwanthgowda.mys@gmail.com

LinkedIn: [My_LinkedIn](https://www.linkedin.com/in/yashwanth-gowda-sathish-23842315a/)
