# Cognia Education Website

Professional AI training website for educators across Australia. Built with React, Vite, and Tailwind CSS.

## 🌟 Features

- **Glass Morphism Design** - Modern, elegant UI with frosted glass effects
- **Animated Backgrounds** - Dynamic floating orbs and moving grid patterns
- **4-Page Structure** - Home, Course, About Us, Contact Us
- **Mobile Responsive** - Fully optimized for all devices
- **AITSL-Aligned Content** - Professional development program information
- **Contact Integration** - Email and phone contact options

## 🚀 Quick Start

### Prerequisites

- Node.js 18+ and pnpm installed
- Or use npm/yarn as alternatives

### Installation

```bash
# Install dependencies
pnpm install

# Start development server
pnpm run dev

# Build for production
pnpm run build
```

The development server will start at `http://localhost:3000`

## 📦 Build & Deploy

### Build Production Files

```bash
pnpm run build
```

This creates optimized files in `dist/public/` ready for deployment.

### Deploy to Netlify (Recommended)

**Option 1: Drag & Drop**
1. Build the project: `pnpm run build`
2. Drag `dist/public` folder to [Netlify Drop](https://app.netlify.com/drop)

**Option 2: GitHub Integration (Automatic Deployments)**
1. Push this repository to GitHub
2. Go to [Netlify](https://www.netlify.com/)
3. Click "Add new site" → "Import an existing project"
4. Connect your GitHub repository
5. Use these build settings:
   - **Build command:** `pnpm run build`
   - **Publish directory:** `dist/public`
6. Click "Deploy site"

### Deploy to Vercel

1. Push this repository to GitHub
2. Go to [Vercel](https://vercel.com/)
3. Import your GitHub repository
4. Vercel auto-detects Vite configuration
5. Click "Deploy"

## 🎨 Tech Stack

- **React** - UI framework
- **Vite** - Build tool and dev server
- **Tailwind CSS** - Utility-first CSS framework
- **Lucide React** - Icon library
- **Wouter** - Lightweight routing

## 📁 Project Structure

```
cognia-education-final/
├── client/
│   ├── src/
│   │   ├── App.jsx              # Main application component
│   │   ├── CoursePage.jsx       # Course page component
│   │   ├── assets/              # Images and logos
│   │   └── components/          # Reusable UI components
│   ├── public/                  # Static assets (favicon, etc.)
│   └── index.html               # HTML template
├── package.json                 # Dependencies and scripts
├── vite.config.ts              # Vite configuration
├── tailwind.config.js          # Tailwind CSS configuration
└── README.md                   # Technical documentation
```

## 🌐 Custom Domain Setup

After deploying to Netlify/Vercel:

1. **In your hosting platform:**
   - Go to Domain settings
   - Add your custom domain (e.g., cogniaedu.com.au)
   - Copy the DNS records provided

2. **In your domain registrar (e.g., Purelymail):**
   - Add A record: `@` → Netlify/Vercel IP
   - Add CNAME record: `www` → your-site.netlify.app
   - Keep existing MX records for email

3. **Wait for DNS propagation** (usually < 1 hour)

## 📧 Contact Information

- **Email:** admin@cogniaedu.com.au
- **Phone:** +61 0402 130 206
- **Service Area:** Australia-wide in-person delivery

## 🎯 Website Pages

1. **Home** - Hero section, trusted tools, statistics, program overview
2. **Course** - Three-module professional development program details
3. **About Us** - Company story and team profiles
4. **Contact Us** - Contact information with animated background

## 🛠️ Development

### Available Scripts

- `pnpm run dev` - Start development server
- `pnpm run build` - Build for production
- `pnpm run preview` - Preview production build locally

### Making Updates

1. Edit components in `client/src/`
2. Test locally with `pnpm run dev`
3. Build with `pnpm run build`
4. Deploy updated `dist/public` folder

## 📄 License

Copyright © 2024 Cognia Education. All rights reserved.

---

**Built for Australian educators | Deployed with ❤️**

