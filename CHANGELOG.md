# CHANGELOG

## [0.0.2] - 2026-04-20
### Major Release - Complete React Refactor & Feature Expansion

#### Framework & Build
- Migrated from vanilla JavaScript to React 19 with TypeScript
- Implemented Vite as modern build system
- Added TypeScript strict mode for type safety

#### Styling & UI
- Implemented Tailwind CSS 4 with PostCSS
- Created comprehensive theme system with CSS variables
- Added dark/light mode toggle functionality
- Responsive design across all screen sizes (mobile, tablet, desktop)
- Smooth animations with motion/react library

#### Core Features
- **Real-time Monitoring Dashboard**
  - Live user statistics from Duino-Coin API
  - Total hashrate calculation and formatting
  - Worker/miner count display
  - Auto-refresh every 15 seconds

- **Detailed Miner Analytics**
  - Worker table with software, identifier, hashrate, efficiency metrics
  - Accepted/rejected shares tracking
  - Pool information display
  - Thread ID and type identification
  - Status indicators (online/offline)

- **Global Statistics**
  - Miner distribution pie chart
  - Total miners count
  - Network-wide mining distribution breakdown

- **Financial Dashboard**
  - Account balance display
  - USD valuation calculation
  - Earned coins estimation (Min/Max/Average)
  - 24-hour earning projections

- **Transaction History**
  - Recent transaction tracking
  - Incoming/outgoing transfer indicators
  - Timestamp display
  - Memo field support

- **User Management**
  - Multi-user support with username search
  - Favorite users bookmarking system
  - LocalStorage persistence for favorites

#### Internationalization (i18n)
- Russian (Русский)
- English
- Polish (Polski)
- Language toggle in header

#### Data Visualization
- Hashrate chart with area graphs
- Real-time data updates (up to 40 data points)
- Interactive tooltips
- Recharts library integration

#### UI Components
- Card-based layout system
- Modal dialogs (Privacy Policy)
- Animated page transitions
- Hover effects and interactive states
- Loading spinners
- Error message displays
- Icon system with Lucide React

#### DevOps & Deployment
- GitHub Actions CI/CD workflow
- Automated deployment to GitHub Pages
- Build optimization
- Node.js environment configuration

#### Code Quality
- TypeScript for type safety
- Modular component structure
- Clean separation of concerns
- Utility functions (formatHashrate, cn)

#### Dependencies
- react: ^19.0.0
- react-dom: ^19.0.0
- typescript: ~5.8.2
- tailwindcss: ^4.1.14
- recharts: ^3.8.1
- lucide-react: ^0.546.0
- motion: ^12.23.24
- @tailwindcss/vite: ^4.1.14
- clsx: ^2.1.1
- tailwind-merge: ^3.5.0

#### Documentation
- Privacy Policy in Russian and English
- Comprehensive UI with clear labels
- Intuitive navigation

### Performance
- Client-side data processing
- No backend server (static deployment)
- Efficient API calls with Promise.all()
- Optimized component rendering

### Security
- No sensitive data storage
- No password collection
- Public API usage only
- Client-side only processing

## [0.0.1] - 2026-04-04
### Initial Release
- Introduced the Hleb-Duco Monitor application
- Added core features including monitoring and reporting functionality
- Basic user interface implemented