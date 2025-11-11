# AI-Assistant-Project

AI Portfolio Assistant 🤖

A full-stack JavaScript web application that generates professional portfolio content using AI. Built with Node.js, Express, and modern web technologies.

🚀 Features

Professional Bio Generator - Create engaging personal bios

Project Summary Creator - Generate comprehensive project descriptions

Learning Reflection Writer - Craft thoughtful learning experiences

Responsive Design - Works perfectly on desktop and mobile

Real-time AI Processing - Generate content instantly

🛠️ Tech Stack
Frontend:

HTML5, CSS3, JavaScript (ES6+)

Responsive CSS Grid/Flexbox

Modern gradient design

Backend:

Node.js runtime

Express.js web framework

CORS enabled for cross-origin requests

Environment variable configuration

📁 Project Structure
text
ai-portfolio-assistant-group/
├── server.js              # Express.js backend server
├── package.json           # Project dependencies and scripts
├── public/               # Frontend assets (served statically)
│   ├── index.html        # Main application interface
│   ├── style.css         # Responsive styling and design
│   └── script.js         # Frontend logic and API calls
├── .env.example          # Environment variables template
├── .gitignore           # Git ignore rules
└── README.md            # Project documentation
👥 Team Members & Responsibilities

MuziSitsha: Frontend Developer
Responsibilities: UI/UX design, responsive layout, user interaction

Files: public/index.html, public/style.css, public/script.js

Branch: frontend-by-Muziwakhe

MpiloG29: Backend Developer
Responsibilities: Server setup, API development, error handling

Files: server.js

Branch: backend-by-CelimpiloGumede

Katleho-Lephuting10111: Project Manager & AI Specialist
Responsibilities: Project coordination, documentation, AI integration

Files: package.json, README.md, .gitignore, .env.example

Branch: main

🚀 Installation & Setup
Prerequisites
Node.js (v14 or higher)

npm (Node Package Manager)

Quick Start
bash
# Clone the repository
git clone https://github.com/your-username/ai-portfolio-assistant-group.git

# Navigate to project directory
cd ai-portfolio-assistant-group

# Install dependencies
npm install

# Start the development server
npm start

# Open your browser and visit:
# http://localhost:5000
Development Scripts
bash
npm start          # Start production server
npm run dev        # Start development server with nodemon
🎯 How to Use
Select Content Type - Choose between Bio, Project Summary, or Learning Reflection

Enter Your Information - Provide details about your experience, projects, or learning journey

Generate Content - Click the button to create professional AI-powered content

Copy & Use - Use the generated content in your portfolio, LinkedIn, or applications

Example Inputs:
Bio: "2 years web development, Python, JavaScript, React projects"

Project: "E-commerce website with shopping cart and payment processing"

Reflection: "Learning Git version control and Agile methodologies"

🔧 API Endpoints
POST /generate
Generates AI-powered content based on user input.

Request Body:

json
{
  "type": "bio|project|reflection",
  "input": "User description here"
}
Response:

json
{
  "success": true,
  "content": "Generated professional content..."
}
🏗️ Development Workflow
Branch Strategy
main - Production-ready code

frontend-ui - Frontend development

backend-api - Backend development

project-setup - Project configuration

Contributing
Create a feature branch from main

Make your changes and commit with descriptive messages

Push your branch and create a Pull Request

Request review from teammates

Merge after approval

Git Commands
bash
# Create and switch to new branch
git checkout -b feature-branch-name

# Add and commit changes
git add .
git commit -m "Descriptive commit message"

# Push to GitHub
git push origin feature-branch-name
📋 Agile Methodology
User Stories
✅ As a user, I want to generate professional bios

✅ As a user, I want to create project summaries

✅ As a user, I want to write learning reflections

✅ As a developer, I want a responsive web interface

✅ As a developer, I want a robust backend API

Kanban Board
We use GitHub Projects with columns:

To Do - Planned features

In Progress - Currently being developed

Review - Ready for code review

Done - Completed and tested

🐛 Troubleshooting
Common Issues
Port already in use:

bash
# Change port in server.js
const PORT = process.env.PORT || 5001;
Dependencies not installed:

bash
npm install
CORS errors:

Ensure cors middleware is enabled in server.js

🌐 Deployment
Environment Variables
Create a .env file based on .env.example:

env
PORT=5000
OPENAI_API_KEY=your_api_key_here
Production Deployment
The application is ready for deployment on:

Heroku

Vercel

Netlify

Railway

Any Node.js hosting platform

📞 Support
For issues and questions:

Check existing GitHub issues

Create a new issue with detailed description

Tag relevant team members

📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

🎓 Learning Outcomes
This project demonstrates:

Full-stack JavaScript development

Agile team collaboration

Git version control workflows

REST API design and implementation

Responsive web design principles

AI integration concepts

Built by INNIT!


