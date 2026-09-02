# Agency.ai

A modern, responsive digital agency landing page built with **React**, **Vite**, **Tailwind CSS**, and **Motion**.

Agency.ai presents a clean digital-agency experience with animated sections, responsive navigation, services, portfolio work, team members, contact functionality, dark mode, and a custom cursor.

## 🌐 Live Demo

**Live Website:** `https://Aryanh12345.github.io/Agency.AI/`

## ✨ Features

- Responsive design for desktop, tablet, and mobile
- Light and dark theme support
- Smooth animations using Motion
- Sticky responsive navigation
- Mobile sidebar navigation
- Animated hero section
- Interactive service cards
- Portfolio / latest work section
- Team members section
- Contact form with Web3Forms
- Toast notifications with React Hot Toast
- Newsletter subscription UI
- Custom animated mouse cursor
- Hover effects and smooth transitions
- GitHub Pages deployment support

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| React 19 | User interface |
| Vite | Development and production build |
| Tailwind CSS 4 | Styling and responsive design |
| Motion | Animations and transitions |
| React Hot Toast | Notifications |
| Web3Forms | Contact form handling |
| GitHub Pages | Hosting |

## 📂 Project Structure

```text
Agency.AI/
├── public/
│   └── favicon.ico
│
├── src/
│   ├── assets/
│   │   ├── images
│   │   ├── icons
│   │   └── assets.js
│   │
│   ├── components/
│   │   ├── ContactUs.jsx
│   │   ├── Footer.jsx
│   │   ├── Hero.jsx
│   │   ├── Navbar.jsx
│   │   ├── OurWork.jsx
│   │   ├── ServiceCard.jsx
│   │   ├── ServicesHelp.jsx
│   │   ├── Teams.jsx
│   │   ├── ThemeToggleBtn.jsx
│   │   ├── Title.jsx
│   │   └── TrustedBy.jsx
│   │
│   ├── App.jsx
│   ├── index.css
│   └── main.jsx
│
├── .gitignore
├── eslint.config.js
├── index.html
├── package.json
├── package-lock.json
└── vite.config.js
```

## 🎨 Website Sections

### Hero

A large introductory section featuring the agency message, trusted-user indicator, animated content, and hero artwork.

### Services

The services section includes:

- Advertising
- Content Marketing
- Content Writing
- Social Media

### Our Work

A portfolio section showcasing:

- Mobile App Marketing
- Dashboard Management
- Fitness App Promotion

### Meet the Team

Displays team members with their names, roles, and profile images.

### Contact Us

A responsive contact form that collects:

- Name
- Email
- Message

Submissions are handled through Web3Forms, with success and error feedback displayed using toast notifications.

### Footer

Includes:

- Navigation links
- Newsletter subscription UI
- Social media icons
- Copyright information

## 🌓 Dark Mode

Agency.ai supports both light and dark themes.

The selected theme is stored in `localStorage`, allowing the preference to persist after refreshing the page.

## 📱 Responsive Design

Tailwind CSS responsive utilities are used throughout the project.

The layout adapts to different screen sizes, including:

- Mobile phones
- Tablets
- Laptops
- Large desktop screens

The desktop navigation also changes into a sidebar navigation on smaller screens.

## 📄 License

This project is intended for personal and educational use.

Check the licenses of third-party assets, libraries, fonts, and services before using the project commercially.

## 👨‍💻 Author

**Aryan Hapaliya**

Built with React, Tailwind CSS, Motion, and Vite as a modern frontend development project.
