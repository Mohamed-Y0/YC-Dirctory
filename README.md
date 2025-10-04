# YC Directory

**Pitch, Vote & Grow** - A platform for startup founders to pitch their ideas, vote on projects, and connect with the community.

> 📺 Project from [JS Mastery](https://www.youtube.com/@javascriptmastery) YouTube tutorial

## Tech Stack

- **Next.js 15** (App Router with PPR)
- **React 19** (RC)
- **Sanity CMS** - Content management
- **NextAuth.js** - GitHub OAuth authentication
- **TailwindCSS** - Styling
- **TypeScript** - Type safety

## Getting Started

1. **Install dependencies:**

   ```bash
   npm install
   ```

2. **Set up environment variables:**
   Create a `.env.local` file with:

   ```env
   AUTH_GITHUB_ID=your_github_oauth_id
   AUTH_GITHUB_SECRET=your_github_oauth_secret
   AUTH_SECRET=your_auth_secret
   NEXT_PUBLIC_SANITY_PROJECT_ID=your_sanity_project_id
   NEXT_PUBLIC_SANITY_DATASET=production
   NEXT_PUBLIC_SANITY_API_VERSION="vX"
   SANITY_WRITE_TOKEN=your_sanity_write_token
   ```

3. **Run development server:**

   ```bash
   npm run dev
   ```

4. **Access Sanity Studio:**
   Navigate to `/studio` to manage content.

## Features

- 🚀 Submit and browse startup pitches
- 👤 GitHub authentication
- 📝 Markdown editor for content
- 🎨 Modern UI with shadcn/ui components
- 📱 Responsive design

## Deployment

Configured for deployment on Netlify with Node.js 20.
