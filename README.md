# Volt React Dashboard

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![React](https://img.shields.io/badge/React-16.13.1-blue.svg)](https://reactjs.org/)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-5.0.0--beta1-purple.svg)](https://getbootstrap.com/)

A modern admin dashboard template powered by **React.js** and **Bootstrap 5**. Built with modern technologies and best practices for building professional admin panels and dashboard applications.

## ✨ Features

- **React 16** - Built with React.js for a component-based architecture
- **Bootstrap 5** - Modern, responsive design with Bootstrap 5 styling
- **SCSS Styling** - Customizable styles with Sass/SCSS
- **Interactive Charts** - Data visualization with Chartist.js
- **Font Awesome Icons** - Rich icon library integration
- **React Router** - Client-side routing for seamless navigation
- **Responsive Design** - Mobile-first approach for all screen sizes
- **Pre-built Pages** - Ready-to-use dashboard pages and components

## 📋 Pages Included

### Dashboard
- **Overview** - Main dashboard with widgets, charts, and statistics
- **Transactions** - Transaction management and listing
- **Settings** - User settings and preferences
- **Bootstrap Tables** - Data tables with Bootstrap styling

### Authentication
- Sign In
- Sign Up
- Forgot Password
- Reset Password
- Lock Screen

### Error Pages
- 404 Not Found
- 500 Server Error

### Utility Pages
- Billing
- Invoice
- Upgrade

## 🧩 Components

The dashboard includes a rich library of reusable components:

- Accordion
- Alerts
- Badges
- Breadcrumbs
- Buttons
- Charts
- Forms
- Modals
- Navigation (Navbar, Navs)
- Pagination
- Popovers
- Progress Bars
- Tables
- Tabs
- Tooltips
- Toasts
- Widgets

## 🚀 Getting Started

### Prerequisites

- Node.js (v12 or higher recommended)
- npm or yarn

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/sam-mohsin01/volt-daashboard.git
   cd volt-daashboard
   ```

2. **Install dependencies**
   ```bash
   npm install --legacy-peer-deps
   ```

3. **Start the development server**
   ```bash
   NODE_OPTIONS=--openssl-legacy-provider npm start
   ```

4. **Open your browser**
   
   Navigate to [http://localhost:3000](http://localhost:3000) to view the dashboard.

## 📦 Available Scripts

| Command | Description |
|---------|-------------|
| `npm start` | Runs the app in development mode |
| `npm run build` | Builds the app for production |
| `npm run build-local` | Builds with relative paths for local file serving |
| `npm test` | Runs the test suite |
| `npm run eject` | Ejects from Create React App |

## 📁 Project Structure

```
volt-react-dashboard/
├── public/                 # Static assets and HTML template
│   ├── index.html
│   ├── favicon.ico
│   └── manifest.json
├── src/
│   ├── assets/            # Images, fonts, and static resources
│   ├── components/        # Reusable React components
│   ├── data/              # Static data and mock content
│   ├── pages/             # Page components
│   ├── scss/              # SCSS stylesheets
│   ├── index.js           # Application entry point
│   └── routes.js          # Route definitions
├── package.json
└── README.md
```

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| [React](https://reactjs.org/) | UI Framework |
| [React Router](https://reactrouter.com/) | Client-side routing |
| [Bootstrap 5](https://getbootstrap.com/) | CSS Framework |
| [Chartist](https://gionkunz.github.io/chartist-js/) | Chart library |
| [Font Awesome](https://fontawesome.com/) | Icon library |
| [Sass](https://sass-lang.com/) | CSS preprocessor |
| [Moment.js](https://momentjs.com/) | Date/time handling |

## 🔧 Configuration

The project uses Create React App for build configuration. To customize:

- **Environment Variables**: Create a `.env` file in the root directory
- **SCSS Theming**: Modify files in `src/scss/` to customize the appearance
- **Routes**: Edit `src/routes.js` to add or modify application routes

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE.md](LICENSE.md) file for details.
