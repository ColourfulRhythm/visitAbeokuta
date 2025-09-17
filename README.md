# Real Estate Tracker - Kobape Developments

A Bloomberg-style real estate tracking application for Kobape, Abeokuta, Nigeria.

## Features

- 14 Kobape Real Estate Developments
- Interactive MapTiler Integration
- Bloomberg-style Dark Theme
- Search & Filter Functionality
- Development Comparison Tool
- News Feed & Analytics

## Quick Start

1. Install dependencies:
   ```bash
   npm install
   ```

2. Run development server:
   ```bash
   npm run dev
   ```

3. Open [http://localhost:3000](http://localhost:3000)

## Deployment

Deploy to Vercel for the best experience:

1. Go to [vercel.com](https://vercel.com)
2. Import this repository
3. Add environment variables:
   - `NEXT_PUBLIC_MAPTILER_API_KEY=Pd85kmLr2NsBZ7APc3eK`
   - `NEXT_PUBLIC_MAPTILER_STYLE_URL=https://api.maptiler.com/maps/streets-v2/style.json?key=Pd85kmLr2NsBZ7APc3eK`
4. Deploy!

## Tech Stack

- Next.js 14
- TypeScript
- TailwindCSS
- Supabase
- MapTiler
- shadcn/ui

## License

MIT
