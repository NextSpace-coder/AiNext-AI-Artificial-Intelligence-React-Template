# AI Technology Solutions

A modern AI technology landing page template built with React, featuring responsive design and interactive components for showcasing AI solutions and services.

## Project Type

Landing Page / Portfolio - AI Technology Solutions showcase website

## Features

- **Responsive Design**: Mobile-first responsive layout
- **Interactive Components**: Animated sections with Framer Motion
- **Multi-page Navigation**: About, Portfolio, Blog, Contact pages
- **Contact Forms**: Interactive contact and inquiry forms
- **Gallery Showcase**: Image galleries and portfolios
- **Team Section**: Meet the team components
- **Pricing Plans**: Service pricing displays
- **Blog System**: Article and news sections
- **Testimonials**: Client feedback displays

## Technology Stack

- **Frontend Framework**: React 18+
- **Build Tool**: Vite
- **Styling**: Bootstrap 5.3.2 + Custom CSS
- **Routing**: React Router Dom 6.22.0
- **Animations**: Framer Motion 11.0.5
- **Sliders**: Swiper 11.0.6
- **Counters**: React Slot Counter 2.2.5
- **Backend Integration**: Supabase (configured, ready to use)

## Project Structure

```
├── src/
│   ├── components/          # Reusable components
│   │   ├── common/         # Shared components (Button, Cards, etc.)
│   │   ├── about.jsx       # About section component
│   │   ├── banner.jsx      # Hero banner component
│   │   ├── gallery.jsx     # Gallery component
│   │   └── ...
│   ├── pages/              # Page components
│   │   ├── about-us.jsx    # About page
│   │   ├── blog.jsx        # Blog listing page
│   │   ├── contact.jsx     # Contact page
│   │   ├── portfolio.jsx   # Portfolio showcase
│   │   └── ...
│   ├── layout/             # Layout components
│   │   ├── header.jsx      # Site header/navigation
│   │   ├── footer.jsx      # Site footer
│   │   └── root.jsx        # Root layout
│   ├── route/              # Routing configuration
│   ├── assets/             # Static assets (images, fonts, styles)
│   ├── integrations/       # Third-party integrations
│   │   └── supabase/       # Supabase configuration
│   └── utils/              # Utility functions
```

## Pages

- **Home (/)**: Main landing page with hero section, features, and call-to-action
- **About (/about-us)**: Company information and team showcase
- **Portfolio (/portfolio)**: Project gallery and case studies
- **Blog (/blog)**: Article listings and blog posts
- **Contact (/contact)**: Contact form and company information
- **Pricing (/pricing)**: Service pricing plans
- **Team (/team)**: Team member profiles
- **Blog Details (/blog-details)**: Individual blog post pages

## Getting Started

1. Install dependencies:
   ```bash
   pnpm install
   ```

2. Start development server:
   ```bash
   pnpm run dev
   ```

3. Build for production:
   ```bash
   pnpm run build
   ```

## Features Ready for Integration

- **Supabase Integration**: Database client configured and ready to use
- **Contact Forms**: Form components ready for backend integration
- **User Authentication**: Infrastructure ready for login/signup features
- **Content Management**: Blog and portfolio sections ready for dynamic content

## Customization

The template uses a modular component structure that makes it easy to:
- Modify styling through CSS files in `src/assets/css/`
- Add new pages by creating components in `src/pages/`
- Extend functionality through the component system
- Integrate additional services through the integrations folder

## Browser Support

- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile responsive design
- Progressive Web App capabilities