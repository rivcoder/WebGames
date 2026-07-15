# Data-Heist - Development Rules

Version: 1.0

---

# Objective

Build Data-Heist as a scalable, production-ready web application with clean architecture, modern UI, maintainable code, and excellent developer experience.

Never sacrifice code quality for speed.

---

# General Principles

- Always prioritize readability.
- Write modular code.
- Avoid duplicated logic.
- Prefer composition over repetition.
- Follow SOLID principles when applicable.
- Keep functions small and focused.
- Every feature should be reusable.

---

# Tech Stack

Frontend
- Next.js (App Router)
- TypeScript
- Tailwind CSS
- Framer Motion
- Shadcn UI

Backend
- FastAPI
- SQLAlchemy

Database
- PostgreSQL

Visualization
- Plotly

Authentication
- Clerk/Auth.js

AI
- OpenAI API

Deployment
- Vercel
- Railway

---

# Project Structure
Make the code structure simple, readbale and understandable.

# Coding Standards

Always

- Use meaningful variable names.
- Write reusable components.
- Separate UI from business logic.
- Use environment variables for secrets.

Never

- Hardcode API keys.
- Duplicate code.
- Use inline CSS.
- Leave console.log statements.
- Ignore TypeScript errors.
- Create huge components.

---

# UI Rules

The interface should feel like a premium game.

Design principles

- Dark theme
- Smooth animations
- Rounded corners
- Glassmorphism where appropriate
- Consistent spacing
- Responsive layout
- Minimal but modern

Animations should improve UX, not distract.

---

# Component Rules

Every component must

- Have a single responsibility
- Be reusable
- Be typed
- Receive props through interfaces

---

# API Rules

Every endpoint must

- Validate input
- Return proper HTTP status codes
- Handle errors gracefully
- Return structured JSON

Example

{
    "success": true,
    "data": {},
    "message": ""
}

---

# Database Rules

- Never use raw SQL unless necessary.
- Use SQLAlchemy ORM.
- Normalize tables.
- Add indexes where needed.
- Use UUIDs when appropriate.

---

# Security

Always

- Validate user input
- Sanitize SQL queries
- Protect API keys
- Hash passwords
- Use HTTPS
- Implement rate limiting

Never trust client-side validation alone.

---

# Performance

- Lazy load heavy components.
- Optimize database queries.
- Cache repeated requests.
- Minimize unnecessary re-renders.
- Optimize images and assets.

---

# Error Handling

Every function must

- Handle expected failures
- Return useful error messages
- Never crash the application

---

# Accessibility

- Keyboard navigation
- Proper button labels
- Sufficient color contrast
- Semantic HTML
- Responsive design

---

# AI Rules

The AI assistant should

- Explain SQL concepts
- Give hints before answers
- Never reveal solutions immediately
- Explain mistakes clearly
- Encourage learning

---

# Code Quality

Before generating code

Always ask

- Is this reusable?
- Is this scalable?
- Is this readable?
- Can this be simplified?

If yes, improve it before returning code.

---


# Documentation

Every major feature must include

- Comments where necessary
- README updates
- Type definitions
- API documentation

---

# Final Goal

Every piece of code should be production-ready, scalable, readable, and easy to extend.

The project should demonstrate strong skills in web development, data analytics, and AI integration while providing an enjoyable game experience.