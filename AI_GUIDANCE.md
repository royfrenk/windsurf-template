# AI Guidance for Roy Frenkiel's Personal Website

This document provides guidance for AI assistants working on this project.

## Project Overview

This is a personal website built with Next.js 14, React, TypeScript, and Tailwind CSS. The website showcases Roy Frenkiel's professional profile, skills, and portfolio.

## Project Structure

- `/app`: Contains all pages and layouts (Next.js App Router)
  - `layout.tsx`: Root layout with metadata and global structure
  - `page.tsx`: Home page with main sections
  - `globals.css`: Global styles and Tailwind imports
- `/public`: Static assets like images and fonts
- `next.config.js`: Next.js configuration
- `tailwind.config.js`: Tailwind CSS configuration

## Development Guidelines

### Styling
- Use Tailwind CSS for styling components
- Maintain the established color scheme in `globals.css`
- Use Framer Motion for animations

### Components
- Create reusable components in `/app/components`
- Use TypeScript interfaces for component props
- Follow the client/server component pattern based on needs

### Content
- Personal information should be accurate and professional
- Portfolio items should include detailed descriptions and links
- Keep text concise and focused on professional achievements

### Performance
- Use Next.js Image component for optimized images
- Minimize unnecessary re-renders
- Keep bundle size small by avoiding large dependencies

## Future Enhancements

- Blog section for articles and thoughts
- Dark/light mode toggle
- Internationalization support
- Contact form with server-side validation
- Integration with external APIs for dynamic content

## Deployment

The site is intended to be deployed on Vercel for optimal Next.js support.

---

When making changes, please document them clearly and maintain the established code style and architecture.
