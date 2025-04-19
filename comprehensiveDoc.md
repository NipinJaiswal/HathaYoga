# Hatha Yoga Web Application - Comprehensive Documentation

## Overview
This web application is dedicated to sharing Sadhguru's teachings on Hatha Yoga, providing authentic yogic practices for transformation. The application features a responsive design with multiple sections explaining different aspects of Hatha Yoga, its origins, science, benefits, and programs.

## Project Structure

### Frontend Components
The application is built with React and organized into modular components:

1. **NavBar**: Navigation menu for the website with links to different sections
2. **HeroSection**: Main banner with a yoga image background and call-to-action
3. **WhatIsHathaYoga**: Explanatory content about what Hatha Yoga is
4. **ScienceBehindYoga**: Information about the scientific basis of yoga practices
5. **OriginsOfYoga**: Historical context of yoga's development
6. **BenefitsOfYoga**: Cards highlighting mental clarity, physical wellbeing, and energy balance
7. **ProgramsSection**: Display of available yoga programs with details
8. **TestimonialSection**: User stories and experiences with yoga
9. **NewsletterSection**: Email subscription form for updates
10. **Footer**: Site information, quick links, resources, and contact details

### Backend Structure
- **Express.js Server**: Handles API requests and serves the frontend
- **In-Memory Storage**: Stores user data and newsletter subscriptions
- **API Routes**: Endpoints for user authentication and newsletter subscriptions

### Data Models
- **User**: For authentication (username, password)
- **NewsletterSubscription**: For storing newsletter subscriptions (email, createdAt)

## Design Elements

### Color Palette
- Primary Color (Blue): #4A90E2
- Secondary Color (Green): #68A678
- Accent Color: Changes based on context
- Neutral Light (Beige): #F5F2EB
- Neutral Dark (Gray): #333333

### Typography
- Headings: Playfair Display (serif)
- Body Text: Open Sans (sans-serif)

### UI Components
The application uses custom components built with Tailwind CSS and shadcn/ui, including:
- Buttons
- Cards
- Forms
- Icons (from Lucide React)
- Responsive grid layouts

## Features

### Current Features
1. **Informational Sections**: Detailed content about Hatha Yoga
2. **Responsive Design**: Optimized for mobile, tablet, and desktop
3. **Newsletter Subscription**: Email subscription functionality
4. **Programs Showcase**: Display of available yoga programs

### Future Development Plans
1. **User Authentication**: Allow users to create accounts and login
2. **Detailed Program Pages**: Individual pages for each yoga program
3. **Blog Section**: Regular content updates with yoga articles
4. **Video Integration**: Embed instructional yoga videos
5. **Booking System**: Allow users to book spots in programs
6. **User Dashboard**: Personal space for tracking progress
7. **Membership Plans**: Offer premium membership options

## Technical Implementation

### Frontend
- **React**: Component-based UI
- **Tailwind CSS**: Utility-first styling
- **shadcn/ui**: UI component library
- **React Query**: Data fetching and state management
- **React Hook Form**: Form validation and submission

### Backend
- **Express.js**: RESTful API server
- **In-Memory Storage**: Data persistence (can be replaced with a database)
- **API Endpoints**: 
  - `/api/newsletter`: Newsletter subscription

### Development Guidelines
1. **Component Structure**: Keep components modular and reusable
2. **Styling Consistency**: Use Tailwind classes consistently across components
3. **Responsive Design**: Test all components on different screen sizes
4. **Performance Optimization**: Minimize unnecessary re-renders
5. **API Integration**: Use React Query for data fetching and caching

## Installation and Setup

### Prerequisites
- Node.js (v20.x recommended)
- npm (v10.x recommended)

### Installation Steps
1. Clone the repository:
   ```
   git clone <repository-url>
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Start the development server:
   ```
   npm run dev
   ```
   This will start both the Express backend server and the Vite development server.

4. Access the application:
   ```
   http://localhost:5000
   ```

### Using the Workflow on Replit
If you're using Replit, you can simply:

1. Click on the "Run" button in Replit, or
2. Use the "Start application" workflow which executes `npm run dev`

The application will automatically be available in the Replit webview.

## Deployment
The application is designed to be deployed on Replit, with automatic handling of build processes, hosting, TLS, and health checks.

## Maintenance

### Regular Updates
- Update content to reflect latest teachings
- Add new programs as they become available
- Refresh testimonials with recent user experiences

### Technical Maintenance
- Keep dependencies updated
- Monitor performance and user experience
- Implement feedback and feature requests

## References
- Sadhguru's teachings on Hatha Yoga
- Scientific research on yoga benefits
- Historical texts and traditions of yoga

---

*This documentation will be maintained and updated as the project evolves.*