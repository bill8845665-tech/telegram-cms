# Telegram Messenger Landing Page

A modern, responsive landing page clone of Telegram Messenger built with Next.js 14, TypeScript, and Tailwind CSS v4.

## Features

- 🎨 Official Telegram design and color scheme
- 📱 Fully responsive across all devices
- ⚡ Built with Next.js 14 App Router
- 🎭 Tailwind CSS v4 with semantic design tokens
- ♿ SEO optimized with proper heading hierarchy
- 🔗 Complete internal linking structure
- 📄 Multiple pages: Home, FAQ, Apps, API, Protocol

## Tech Stack

- **Framework:** Next.js 14
- **Language:** TypeScript
- **Styling:** Tailwind CSS v4
- **Animations:** Framer Motion, tw-animate-css
- **Icons:** Lucide React
- **UI Components:** Radix UI

## Getting Started

### Prerequisites

- Node.js 18.x or higher
- npm 9.x or higher

### Installation

1. Clone the repository:
\`\`\`bash
git clone <your-repo-url>
cd telegram-landing-page
\`\`\`

2. Install dependencies:
\`\`\`bash
npm install
\`\`\`

3. Run the development server:
\`\`\`bash
npm run dev
\`\`\`

4. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Project Structure

\`\`\`
telegram-landing-page/
├── app/
│   ├── page.tsx                 # Home page
│   ├── faq/
│   │   ├── page.tsx            # FAQ page wrapper
│   │   └── client-page.tsx     # FAQ client component
│   ├── apps/
│   │   └── page.tsx            # Apps page
│   ├── api-docs/
│   │   └── page.tsx            # API documentation page
│   ├── protocol/
│   │   └── page.tsx            # Protocol page
│   ├── layout.tsx              # Root layout
│   └── globals.css             # Global styles & design tokens
├── components/
│   ├── telegram/
│   │   ├── navbar.tsx          # Navigation bar
│   │   ├── hero.tsx            # Hero section
│   │   ├── features.tsx        # Features section
│   │   ├── apps.tsx            # Apps section
│   │   ├── stats.tsx           # Statistics section
│   │   └── footer.tsx          # Footer
│   └── ui/                     # Reusable UI components
├── lib/
│   └── utils.ts                # Utility functions
├── public/
│   └── telegram-logo.png       # Telegram logo
└── package.json
\`\`\`

## Design System

The project uses semantic design tokens defined in `app/globals.css`:

### Colors
- `--primary`: Telegram blue (#0088cc)
- `--background`: White background
- `--foreground`: Dark text
- `--telegram-blue`: Brand color
- `--telegram-light-blue`: Light accent

All components use these semantic tokens for consistent theming.

## Pages

### Home (`/`)
- Hero section with download buttons
- Key features showcase
- Platform statistics
- Footer with links

### FAQ (`/faq`)
- Searchable FAQ sections
- Accordion-style Q&A
- Categories: General, Basics, Groups, Security, etc.

### Apps (`/apps`)
- Official apps (Mobile, Desktop, Web)
- TDLib information
- Source code links
- Bug bounty program

### API (`/api-docs`)
- Bot API documentation
- TDLib documentation
- Gateway API
- Telegram API

### Protocol (`/protocol`)
- MTProto protocol information
- API reference
- Security documentation

## SEO Optimization

- Proper H1/H2/H3 heading hierarchy
- Meta tags for all pages
- Open Graph tags
- Semantic HTML
- Internal linking structure
- Descriptive alt texts

## Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint
- `npm run type-check` - Run TypeScript type checking

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This is a demonstration project for educational purposes.

## Acknowledgments

- Design inspired by [Telegram](https://telegramoc.com/)
- Built with [Next.js](https://nextjs.org)
- Styled with [Tailwind CSS](https://tailwindcss.com)
