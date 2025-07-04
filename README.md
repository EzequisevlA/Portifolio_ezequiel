Professional Portfolio – Ezequiel Marcos
This is a professional portfolio developed in React for Ezequiel Marcos, Senior Customer Support Specialist.

🚀 Features
Responsive Design: Perfectly adapts to desktop, tablet, and mobile devices

Smooth Animations: Transitions and animations that enhance user experience

Intuitive Navigation: Fixed navigation menu with links to all sections

Complete Sections:

Hero/Intro

About Me

Professional Experience (with timeline)

Education

Skills (with animated progress bars)

Contact (with functional form)

🛠️ Technologies Used
React 18: JavaScript framework for building the UI

Vite: Fast and modern build tool

Tailwind CSS: CSS framework for styling

Lucide React: Icon library

React Router: Routing for navigation

shadcn/ui: Modern and accessible UI components

📦 Installation and Running
Prerequisites
Node.js (version 18 or higher)

pnpm (package manager)

Steps to run locally:
Clone or download the project

bash
Copiar
Editar
cd portfolio-ezequiel
Install dependencies

bash
Copiar
Editar
pnpm install
Run the development server

bash
Copiar
Editar
pnpm run dev
Open in your browser

arduino
Copiar
Editar
http://localhost:5173
🏗️ Production Build
To generate optimized files for production:

bash
Copiar
Editar
pnpm run build
The files will be output in the dist/ folder, ready for deployment.

📁 Project Structure
graphql
Copiar
Editar
src/
├── components/
│   ├── layout/
│   │   ├── Header.jsx          # Header with navigation
│   │   ├── Footer.jsx          # Footer
│   │   └── Layout.jsx          # Main layout
│   ├── sections/
│   │   ├── Hero.jsx            # Intro section
│   │   ├── About.jsx           # About me
│   │   ├── Experience.jsx      # Professional experience
│   │   ├── Education.jsx       # Education
│   │   ├── Skills.jsx          # Skills
│   │   └── Contact.jsx         # Contact
│   ├── ui/
│   │   ├── button.jsx          # Button component
│   │   ├── card.jsx            # Card component
│   │   ├── input.jsx           # Input component
│   │   ├── textarea.jsx        # Textarea component
│   │   ├── progress.jsx        # Progress bar component
│   │   └── responsive.css      # Responsive styles
│   └── HomePage.jsx            # Main page
├── lib/
│   └── utils.js                # Utilities
├── App.jsx                     # Main component
├── App.css                     # Global styles
└── main.jsx                    # Entry point
🎨 Customization
Colors and Theme
The project uses Tailwind CSS with a customizable color system. Primary colors can be adjusted in the Tailwind configuration file.

Content
To update personal information, edit the components inside src/components/sections/:

Hero.jsx: Name, title, and intro description

About.jsx: Detailed personal information

Experience.jsx: Professional experiences

Education.jsx: Academic background

Skills.jsx: Technical and personal skills

Contact.jsx: Contact information

Animations
Animations are controlled in the responsive.css file and can be customized as needed.

📱 Responsiveness
The site was built with a mobile-first approach and is fully responsive:

Mobile: < 576px

Tablet: 768px - 991px

Desktop: > 992px

🔧 Maintenance
Updating Dependencies
bash
Copiar
Editar
pnpm update
Checking for Issues
bash
Copiar
Editar
pnpm run lint
📞 Support
For questions or technical support, please use the contact information provided in the portfolio's contact section.

📄 License
This project was specifically developed for Ezequiel Marcos. All rights reserved.

Developed with ❤️ using React and modern technologies by Ezequiel Marcos.
