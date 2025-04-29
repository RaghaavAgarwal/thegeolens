# TheGeoLens.co

TheGeoLens is a powerful media agency platform that cuts through propaganda and narrative manipulation to reveal the hidden power moves shaping our world. This repository contains the source code for TheGeoLens.co website.

## Features

- Interactive 3D animated background using Three.js
- Powerful, emotionally engaging visual design
- Comprehensive database integration with PostgreSQL
- React frontend with Tailwind CSS and shadcn/ui components
- Express backend with API endpoints
- Subscription functionality
- Content categories and featured stories sections

## Project Structure

- `/client`: Frontend React application
  - `/src/components`: React components
  - `/src/lib`: Utility functions and data
  - `/src/hooks`: Custom React hooks
  - `/src/pages`: Page components
- `/server`: Express backend
  - `/routes.ts`: API routes
  - `/storage.ts`: Database operations
  - `/db.ts`: Database connection
- `/shared`: Shared code between frontend and backend
  - `/schema.ts`: Database schema definitions

## Technologies Used

- React 
- TypeScript
- Three.js for 3D animations
- Tailwind CSS for styling
- shadcn/ui for UI components
- Express for backend
- PostgreSQL for database
- Drizzle ORM for database operations

## Getting Started

1. Clone the repository
2. Install dependencies with `npm install`
3. Set up a PostgreSQL database and update the connection string in `.env`
4. Run the development server with `npm run dev`

## License

Copyright © 2025 TheGeoLens.co. All rights reserved.