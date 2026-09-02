# Agency.ai

A modern, responsive digital agency landing page built with **React**, **Vite**, **Tailwind CSS**, and **Motion**.

Agency.ai presents a clean digital-agency experience with animated sections, responsive navigation, services, portfolio work, team members, contact functionality, dark mode, and a custom cursor.

## 🌐 Live Demo

**Live Website:** `https://YOUR_USERNAME.github.io/Agency.AI/`

> Replace `YOUR_USERNAME` with your GitHub username.

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

## 🚀 Getting Started

### Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/Agency.AI.git
cd Agency.AI
```

### Install dependencies

```bash
npm install
```

### Start the development server

```bash
npm run dev
```

The application will normally be available at:

```text
http://localhost:5173/
```

### Build for production

```bash
npm run build
```

### Preview the production build

```bash
npm run preview
```

## 📦 Deployment

The project uses `gh-pages` to deploy the Vite production build to GitHub Pages.

Run:

```bash
npm run deploy
```

This automatically:

1. Builds the project.
2. Creates the `dist` directory.
3. Publishes `dist` to the `gh-pages` branch.

### GitHub Pages

In your GitHub repository, open:

**Settings → Pages**

Set:

```text
Source: Deploy from a branch
Branch: gh-pages
Folder: / (root)
```

The Vite configuration currently uses:

```js
base: '/Agency.AI/'
```

Make sure this matches the exact name and casing of your GitHub repository.

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

## 🔐 Security Note

If you use Web3Forms or another external service, avoid exposing credentials that are intended to remain private.

If a credential has already been committed to a public GitHub repository, revoke/rotate it and replace it with a new credential.

## 🧹 Available Scripts

```bash
# Start development server
npm run dev

# Run ESLint
npm run lint

# Build production version
npm run build

# Preview production build
npm run preview

# Deploy to GitHub Pages
npm run deploy
```


## 🤝 Contributing

This project is mainly intended as a portfolio and learning project.

If you want to contribute:

1. Fork the repository.
2. Create a feature branch.
3. Make your changes.
4. Commit your changes.
5. Push the branch.
6. Open a pull request.

## 📄 License

This project is intended for personal and educational use.

Check the licenses of third-party assets, libraries, fonts, and services before using the project commercially.

## 👨‍💻 Author

**HF**

Built with React, Tailwind CSS, Motion, and Vite as a modern frontend development project.
