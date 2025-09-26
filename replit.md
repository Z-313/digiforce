# Overview

Digi Force is a modern digital transformation company website built with React and TypeScript. The application showcases the company's AI-powered business solutions, automation services, and consulting offerings through an elegant, futuristic interface inspired by premium tech companies like Tesla and Apple. The website serves as the primary marketing platform to attract enterprise clients seeking digital transformation and AI implementation services.

# User Preferences

Preferred communication style: Simple, everyday language.

# System Architecture

## Frontend Architecture
The application follows a component-based React architecture with TypeScript for type safety:

- **Framework**: React 18 with TypeScript for robust client-side rendering
- **Routing**: Wouter for lightweight client-side routing
- **Styling**: Tailwind CSS with shadcn/ui component library for consistent design system
- **State Management**: TanStack Query for server state management and caching
- **Animations**: Framer Motion for smooth transitions and interactive effects
- **Build Tool**: Vite for fast development and optimized production builds

## Backend Architecture
Express.js server with modular structure:

- **Server Framework**: Express.js with TypeScript
- **Development Setup**: Hot reloading with Vite integration in development
- **API Structure**: RESTful API endpoints with `/api` prefix
- **Error Handling**: Centralized error handling middleware
- **Request Logging**: Custom middleware for API request logging and performance monitoring

## Data Storage Solutions
Hybrid storage approach with database-ready infrastructure:

- **Development Storage**: In-memory storage using Map-based implementation for rapid prototyping
- **Production Ready**: Drizzle ORM configured for PostgreSQL with Neon Database integration
- **Schema Management**: Shared TypeScript schemas with Zod validation
- **Migration Support**: Drizzle Kit for database schema migrations

## Design System
Professional design system following premium tech company aesthetics:

- **Color Palette**: Dark theme with deep blacks, metallic silver, and Porsche red accents
- **Typography**: Inter/Poppins fonts with structured hierarchy
- **Component Library**: shadcn/ui components with custom styling
- **Responsive Design**: Mobile-first approach with Tailwind breakpoints
- **Visual Effects**: Glass-morphism cards, gradient backgrounds, and particle animations

## Content Architecture
Structured content delivery focused on business transformation:

- **Hero Sections**: Animated quantum-themed hero components for different service pages
- **Service Showcases**: Modular components for AI solutions and automation demos
- **Contact Integration**: Form handling with toast notifications (ready for backend integration)
- **Static Assets**: Organized asset management for design references and templates

# External Dependencies

## UI and Design
- **shadcn/ui**: Comprehensive React component library built on Radix UI primitives
- **Tailwind CSS**: Utility-first CSS framework for rapid styling
- **Framer Motion**: Production-ready motion library for React animations
- **Lucide Icons**: Modern icon library with consistent design language

## Data and State Management
- **TanStack Query**: Powerful data synchronization and caching for React applications
- **React Hook Form**: Performant forms library with minimal re-renders
- **Zod**: TypeScript-first schema validation library

## Database and ORM
- **Drizzle ORM**: Lightweight TypeScript ORM with excellent developer experience
- **Neon Database**: Serverless PostgreSQL database platform
- **PostgreSQL**: Robust relational database for production data storage

## Development Tools
- **Vite**: Next-generation frontend build tool with fast HMR
- **TypeScript**: Static type checking for enhanced code reliability
- **ESBuild**: Fast JavaScript bundler for production builds
- **Wouter**: Minimalist routing library for React applications

## External Services (Ready for Integration)
- **Email Services**: Contact form ready for email service integration
- **Analytics**: Structured for Google Analytics or similar tracking
- **CRM Integration**: Architecture supports Zapier/Make automation workflows
- **Payment Processing**: Extensible for future payment gateway integration