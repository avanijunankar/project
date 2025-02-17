# React Assignment Project

A feature-rich React application built with TypeScript, showcasing various React capabilities and modern web development practices.

## Features

- Interactive Counter with Animated Background
- User Data Form with Local Storage
- Rich Text Editor
- Analytics Dashboard with Charts
- Authentication System
- Protected Routes
- Responsive Design

## Tech Stack

- React 18
- TypeScript
- Chakra UI
- React Router DOM
- React Spring (for animations)
- React Quill (rich text editor)
- Recharts (for data visualization)
- Redux Toolkit (state management)

## Prerequisites

- Node.js (v14 or higher)
- npm (comes with Node.js)

## Installation

1. Install dependencies:
   ```bash
   npm install
   ```

2. Start the development server:
   ```bash
   npm run dev
   ```

3. Open [http://localhost:5173](http://localhost:5173) in your browser.

## Project Structure

- `/src`
  - `/components` - Reusable UI components
  - `/pages` - Main page components
  - `/store` - Redux store configuration
  - `App.tsx` - Main application component
  - `main.tsx` - Application entry point

## Features Overview

### Counter
- Increment, decrement, and reset functionality
- Background color changes with counter value
- Smooth animations using React Spring

### User Form
- Input validation
- Local storage persistence
- Unsaved changes detection
- Auto-generated user ID

### Text Editor
- Rich text formatting options
- Content persistence
- User data visualization

### Dashboard
- Interactive charts
- Data visualization using Recharts
- Responsive layout

### Authentication
- Mock authentication system
- Protected routes
- Google Sign-in button (mock)
