# College Compass - Your Guide to Bangalore's Best Colleges

Discover the perfect college match in Bangalore! Explore top-ranked Engineering (IITs, PESU, RVCE), BBA (SJCC, Christ University), and B.Com (NMKRV, MCC) colleges with real data on fees, placements, and rankings.

💡 **What you'll find:**
- 📊 Compare up to 3 colleges side-by-side
- 💰 Filter by fees, rankings, and placement packages
- ⭐ Save your favorites for later review

🚀 **Start your journey →**

## Quick Start

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn

### Installation

```bash
# Clone the repository
https://github.com/SAGAR0709/College-Compass-Bangalore.git

cd College-Compass-Bangalore

# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build
```

### Live Demo
Visit the deployed version at: https://college-compass-bengalore.pages.dev

## College Data Overview

The platform provides comprehensive data on over 100 colleges across three main categories:

### Engineering Colleges
- **Top Tier**: IITs (IISc), PES University, RV College of Engineering
- **Mid Tier**: BMSCE, MS Ramaiah IT, Dayanand Sagar
- **Budget Options**: UVCE, AIT, Presidency University

### BBA Colleges
- **Premium**: Christ University, SJCC (Best ROI), PESU
- **Affordable**: Presidency, Kristu Jayanti College
- **Women-focused**: Mount Carmel College

### B.Com Colleges
- **Top Options**: Christ University, SJCC (Best ROI)
- **Value Options**: NMKRV (Lowest fees), Presidency
- **Niche**: Jain University (ACC-A CCIA)

#### Data Categories
Each college includes:
- Fees and admission modes
- Placement statistics and top recruiters
- NIRF rankings and NAAC grades
- Student reviews and ratings
- Campus facilities and hostel details
- ROI calculations and comparisons

## Features

### 🎯 Smart College Matching
- Search by college name, course, or location
- Filter by category, fees, ranking, and placement package
- Compare up to 3 colleges simultaneously
- Get personalized recommendations based on budget and preferences

### 📊 Comprehensive Comparison
- Side-by-side comparison of 3 colleges
- Fee and scholarship comparison
- Placement statistics and hiring patterns
- Academic rankings and reputation
- Campus facilities and infrastructure

### ⭐ Favorites Management
- Save colleges to your favorites list
- Create shortlists for future reference
- Compare colleges saved in your favorites
- Share your selections with peers

### 🔍 Advanced Search
- Keyword-based college search
- Category-based filtering (Engineering/BBA/B.Com)
- Price range filters
- Placement package thresholds
- Ranking-based filtering

### 📱 Mobile-Friendly Design
- Responsive layout for all devices
- Touch-friendly comparison interface
- Adaptive components for optimal viewing experience

## Technical Architecture

### Framework
- **Frontend**: React with Vite for rapid development
- **Routing**: React Router for SPAs
- **Styling**: CSS modules for scoped styles
- **Icons**: Lucide-react for consistent icon library

### Data Structure
- Centralized college data store in `src/data/colleges.js`
- Categorized organized structure for easy maintenance
- Standardized data schema for consistency across all entries
- Comprehensive review system with rating and comments

### Component Architecture
```
src/
├── components/           # Reusable UI components
│   ├── Navbar.jsx
│   ├── Footer.jsx
│   ├── CollegeCard.jsx
│   └── Toast.jsx
├── pages/               # Page components
│   ├── Home.jsx
│   ├── CourseListing.jsx
│   ├── CollegeDetails.jsx
│   ├── Compare.jsx
│   └── Favorites.jsx
├── context/             # React context for app state
│   ├── context.js
│   └── AppContext.jsx
├── data/                # Data files
│   └── colleges.js
└── hooks/              # Custom React hooks
    └── useToast.js
```

### Performance Optimizations
- Code splitting with React.lazy where applicable
- Vite-powered fast refresh
- Optimized bundle sizes
- Efficient state management with React Context

## Code Structure

### Main Application Flow
1. **Landing Page** - College Compass homepage with search
2. **College Search** - Browse and filter colleges by category
3. **College Details** - Comprehensive profile information
4. **Compare Tool** - Side-by-side college comparison
5. **Favorites** - Saved colleges for later review

### Key Components

#### CollegeCard
Compact college presentation with essential information:
- College logo and name
- Category and ranking
- Average placement package
- Fee range (visual indicator)
- Quick action buttons

#### Comparison Interface
Advanced table-based comparison:
- Multi-sort and filtering
- Real-time price updates
- Visual indicators for rankings
- Export comparison data

### State Management
- AppContext provides global state
- Toast notifications for user feedback
- Favorites managed locally with localStorage
- Search history for improved UX

## Contributing

### Development Workflow
1. Fork the repository
2. Create a feature branch
3. Follow conventional commits:
   - `feat: add new college filtering`
   - `fix: resolve comparison bug`
   - `docs: update README with new college`
4. Run tests and linting:
   ```bash
   # Lint and typecheck
   npm run lint
   ```

### Adding New Colleges
To add a new college to the database:
1. Navigate to `src/data/colleges.js`
2. Add the college object in the appropriate category section
3. Ensure data follows the established schema
4. Include all required fields (feeValue, avgPkgValue, etc.)
5. Add 2-3 sample reviews with ratings (1-5)

### Code Quality
- Follow Prettier formatting
- Use ESLint with Oxlint rules
- Write meaningful commit messages
- Ensure code passes linting

## Support

### Issues
Submit issues at: https://github.com/SAGAR0709/College-Compass-Bangalore/issues

### Documentation
- GitHub Wiki: https://github.com/SAGAR0709/College-Compass-Bangalore/wiki
- Project Documentation: Available in the repository

### Community
Join the community on Discord: https://discord.gg/collegecompass

## License

This project is open-source and available under the MIT License. See LICENSE file for details.

## Contact

For support and inquiries:
- GitHub: https://github.com/SAGAR0709
- Email: contact@collegecompass.dev

## Acknowledgements

- Data provided by Bangalore University's college database
- Icons by Lucide React team
- Built with React and Vite
- Deployed on Cloudflare Pages

© 2024 College Compass - All rights reserved.