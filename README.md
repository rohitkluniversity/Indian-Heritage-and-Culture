# Heritage India - Cultural Heritage Showcase

A full-stack web application showcasing India's rich cultural heritage through an interactive digital platform.

![Heritage India](https://images.unsplash.com/photo-1532375810709-75b1da00537c?ixlib=rb-1.2.1&auto=format&fit=crop&w=100&q=80)

## Project Overview

Heritage India is a comprehensive digital platform designed to celebrate, preserve, and promote India's diverse cultural heritage. The application serves as a digital repository of cultural knowledge, offering users an immersive experience into the vibrant tapestry of Indian traditions, art forms, festivals, and regional diversity.

## Features

### 1. Festival Calendar
- Interactive calendar of Indian festivals throughout the year
- Filter festivals by categories (Religious, Seasonal, Harvest, National, Regional)
- Detailed information about each festival including date, description, and significance

### 2. Art Gallery
- Curated collection of traditional Indian art forms
- Categorized by different art styles (Paintings, Sculptures, Textiles, Pottery, Folk Art)
- Information about each artwork including origin and historical significance

### 3. Cultural Blogs & Articles
- Featured and regular blog posts about various aspects of Indian heritage
- Content categorized by themes (Culture, Architecture, Music, Crafts, Traditions)
- Author information and publishing dates

### 4. Regional Explorer
- Discover the unique cultural aspects of different regions across India
- Region-specific highlights of traditions, art forms, cuisines, and festivals
- Interactive Heritage Map feature (planned)

### 5. Cultural Product Picks
- Curated selection of authentic handcrafted products
- Integration with Amazon affiliate program
- Product ratings and descriptions

### 6. Admin Dashboard
- Secure admin interface with authentication
- Content management for all website sections
- CRUD operations for highlights, festivals, artworks, blogs, regions, and products

## Technical Stack

### Frontend
- React with TypeScript
- TanStack Query for data fetching
- React Hook Form for form handling
- Tailwind CSS for styling
- Shadcn UI components
- Wouter for routing

### Backend
- Node.js with Express
- In-memory storage system (with potential for database integration)
- RESTful API design

### Data Architecture
- TypeScript schema definitions with Zod validation
- Drizzle ORM integration-ready

## Project Structure

```
project/
├── client/               # Frontend React application
│   ├── src/
│   │   ├── components/   # Reusable UI components
│   │   ├── hooks/        # Custom React hooks
│   │   ├── lib/          # Utility functions and clients
│   │   ├── pages/        # Application pages
│   │   └── ...
├── server/               # Backend Express application
│   ├── index.ts          # Server entry point
│   ├── routes.ts         # API routes
│   ├── storage.ts        # Data storage implementation
│   └── ...
├── shared/               # Shared code between frontend and backend
│   └── schema.ts         # Data models and validation schemas
└── ...
```

## Getting Started

### Prerequisites
- Node.js (v20 or later)
- npm or yarn

### Installation

1. Clone the repository
   ```bash
   git clone https: https://github.com/rohitkluniversity/Indian-Heritage-and-Culture
   cd heritage-india
   ```

2. Install dependencies
   ```bash
   npm install
   # or
   yarn install
   ```

3. Start the development server
   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. Access the application at `http://localhost:5000`

5. Admin Dashboard Access
   ```
   URL: http://localhost:5000/admin
   Username: admin
   Password: admin123
   ```

## Future Enhancements

The project roadmap includes several planned enhancements:

1. **AI-based Heritage Guide** - Interactive chatbot for answering queries about Indian heritage
2. **E-commerce Integration** - Direct sales of authentic handicrafts and cultural products
3. **Multilingual Support** - Content available in multiple Indian languages
4. **Virtual Tours** - 360° virtual tours of historical monuments and cultural sites
5. **Community Features** - User accounts, comments, and content contributions

