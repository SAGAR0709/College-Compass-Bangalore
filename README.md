# College Compass Bangalore

College Compass is a React-based web application that helps students discover, compare, and shortlist colleges in Bangalore across Engineering, BBA, and B.Com programs.

## Features

- **College Discovery** — Browse and search colleges by category (Engineering, BBA, B.Com)
- **Side-by-Side Comparison** — Compare colleges on fees, placements, rankings, admission mode, and more
- **Favorites** — Save colleges to a shortlist for quick access
- **Filtering** — Filter by fee range, admission mode, and search keywords
- **Detailed Profiles** — View comprehensive college data including reviews, recruiters, and facilities
- **ROI Analysis** — Compare fee vs placement outcomes to find the best value

## Tech Stack

- **React 19** with Vite
- **React Router v7** for client-side routing
- **Lucide React** for icons
- **CSS** with utility classes and responsive design
- **Oxlint** for linting

## Setup

```bash
git clone https://github.com/SAGAR0709/College-Compass-Bangalore.git
cd College-Compass-Bangalore
npm install
npm run dev
```

## Available Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Start development server |
| `npm run build` | Build for production |
| `npm run preview` | Preview production build |
| `npm run lint` | Run Oxlint |

## Project Structure

```
src/
  components/     — Reusable UI (Navbar, Footer, CollegeCard)
  pages/          — Route pages (Home, CourseListing, Compare, etc.)
  context/        — React Context for global state
  data/           — College data as JS module
  assets/         — Images and static assets
```

## Data

College data is stored in `src/data/colleges.js` with a structured schema covering fees, placements, rankings, reviews, facilities, and recruiters across 3 categories.
