# Blog Application

A full-stack blog application built with Next.js, featuring dynamic content rendering, comment functionality, and search capabilities.

## Features

- **Dynamic Post Rendering**: View detailed blog posts with dynamic routing
- **Comment System**: Users can add and view comments
- **Search Functionality**: Search posts by title or content
- **Responsive Design**: Optimized for all screen sizes
- **Real-time Updates**: Instant UI updates for new comments

## Technologies

- **Next.js 14**: App Router and Server Components
- **React 18**: State management and UI rendering
- **TypeScript**: Type-safe development
- **Tailwind CSS**: Modern styling framework
- **ESLint/Prettier**: Code quality and formatting

## Getting Started

### Prerequisites

- Node.js v18+
- npm v9+ or yarn v1.22+
- Git

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/blog-app.git
   cd blog-app
2. install dependencies:
   npm install
3. Start development server:
   npm run dev
4. Open in your browser: http://localhost:3000

**Project Structure**
   src/
├── app/
│   ├── posts/
│   │   └── [postId]/
│   │       └── page.tsx  # Dynamic post page
├── components/
│   ├── BlogContainer.tsx # Post card component
│   ├── BlogPosts.tsx     # Posts listing
│   ├── CommentForm.tsx   # Comment submission
│   └── CommentList.tsx   # Comments display
├── lib/
│   └── api.ts            # API handlers
public/                   # Static assets
