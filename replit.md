# Overview

This is a React + TypeScript portfolio application showcasing modern web development skills through a collection of interactive components and mini-applications. The project demonstrates proficiency in component-based architecture, state management, API integration, and responsive design patterns. It includes a counter app, theme switcher, card components, weather app, todo app, and an integrated dashboard that combines all features.

# User Preferences

Preferred communication style: Simple, everyday language.

# System Architecture

## Frontend Architecture
- **Framework**: React 18 with TypeScript for type safety and modern component patterns
- **Build Tool**: Vite for fast development and optimized production builds
- **Routing**: Wouter for lightweight client-side routing
- **State Management**: 
  - React Context API for theme management
  - useReducer hook for complex state logic (todo app)
  - Custom hooks for encapsulating business logic
- **Styling**: 
  - Tailwind CSS for utility-first styling with CSS custom properties
  - SCSS modules for component-scoped styles
  - shadcn/ui component library for consistent UI primitives

## Backend Architecture
- **Server**: Express.js with TypeScript
- **Development Setup**: Vite middleware integration for seamless dev experience
- **Storage Interface**: Abstracted storage layer with in-memory implementation
- **API Structure**: RESTful endpoints with `/api` prefix (currently minimal setup)

## Component Architecture
- **Atomic Design**: Reusable UI components in `/components/ui`
- **Feature Components**: Specialized components for each app (counter, weather, todo, etc.)
- **Layout Components**: Header, sidebar, and navigation components
- **Custom Hooks**: Encapsulated logic for todos, weather, and mobile detection

## State Management Patterns
- **Theme Context**: Global theme state with localStorage persistence
- **Todo Reducer**: Complex state transitions with typed actions
- **Weather Hook**: API state management with loading and error handling
- **Form State**: Controlled components with React Hook Form integration

## Styling Strategy
- **Design System**: Consistent color palette with CSS custom properties
- **Responsive Design**: Mobile-first approach with Tailwind breakpoints
- **Component Variants**: Class variance authority for systematic component styling
- **Theme Support**: Light/dark mode with CSS variable switching

# External Dependencies

## Database
- **Drizzle ORM**: Type-safe database queries with PostgreSQL dialect
- **Neon Database**: Serverless PostgreSQL for production (configured but not actively used)
- **Database Schema**: User table with UUID primary keys and unique constraints

## UI Libraries
- **Radix UI**: Headless component primitives for accessibility
- **Tailwind CSS**: Utility-first CSS framework
- **Lucide React**: Icon library for consistent iconography
- **Class Variance Authority**: Component variant management

## Development Tools
- **TanStack Query**: Server state management (configured for future API integration)
- **React Hook Form**: Form validation and management
- **Zod**: Runtime type validation and schema validation

## External APIs
- **OpenWeather API**: Weather data integration with environment variable configuration
- **JSONPlaceholder**: Mock API for dashboard data demonstration

## Development Environment
- **Replit Integration**: Custom plugins for development environment
- **TypeScript**: Strict type checking with path mapping
- **ESBuild**: Fast bundling for production builds
- **PostCSS**: CSS processing with Autoprefixer

## Session Management
- **Connect PG Simple**: PostgreSQL session store (configured but not implemented)
- **Express Session**: Session middleware setup for future authentication