# Password Generator React App

A modern, responsive password generator built with React that allows users to create secure passwords with customizable options.

## Features

- **Customizable Length**: Generate passwords from 6 to 100 characters
- **Character Options**: 
  - Alphabetic characters (A-Z, a-z) - always included
  - Numbers (0-9) - optional
  - Special characters (!@#$%^&*) - optional
- **One-Click Copy**: Copy generated passwords to clipboard instantly
- **Real-time Generation**: Passwords are automatically regenerated when settings change
- **Responsive Design**: Works seamlessly on desktop and mobile devices

## Technologies Used

- **React 19.1.1** - Frontend framework with hooks (useState, useCallback, useEffect, useRef)
- **Vite** - Fast build tool and development server
- **Tailwind CSS 4.1.11** - Utility-first CSS framework for styling
- **ESLint** - Code linting and quality assurance

## Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/MehediHasanRapiIIT/PasswordGeneratorReact.git
cd PasswordGeneratorReact
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:5173`

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## How It Works

The app uses React hooks to manage state and effects:
- `useState` for managing password length, character options, and generated password
- `useCallback` for optimized password generation and copy functionality
- `useEffect` for automatic password regeneration when options change
- `useRef` for direct DOM manipulation during copy operation

## License

This project is open source and available under the MIT License.
