# 🏆 GainzClan - Transform Your Workouts Into Epic Clan Battles

[![Next.js](https://img.shields.io/badge/Next.js-15.4.6-black?style=for-the-badge&logo=next.js)](https://nextjs.org/)
[![React](https://img.shields.io/badge/React-19.1.0-blue?style=for-the-badge&logo=react)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0-blue?style=for-the-badge&logo=typescript)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-4.0-black?style=for-the-badge&logo=tailwind-css)](https://tailwindcss.com/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/Platform-Web%20%7C%20Mobile%20%7C%20PWA-lightgrey.svg)](https://nextjs.org/docs)

<div align="center">
  <img src="public/next.svg" alt="GainzClan Logo" width="120" height="120">
  <h3>AI-Powered Fitness Gaming Platform</h3>
</div>

## 📱 Download & Links

<div align="center">

[![Google Play](https://img.shields.io/badge/Google_Play-414141?style=for-the-badge&logo=google-play&logoColor=white)](https://play.google.com/store/apps/details?id=com.gainzclan.app)
[![App Store](https://img.shields.io/badge/App_Store-0D96F6?style=for-the-badge&logo=app-store&logoColor=white)](https://apps.apple.com/app/gainzclan)
[![Website](https://img.shields.io/badge/Website-000000?style=for-the-badge&logo=About.me&logoColor=white)](https://gainzclan.com/)

</div>

## 📖 Table of Contents

- [About](#-about)
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Architecture](#-architecture)
- [Getting Started](#-getting-started)
- [Project Structure](#-project-structure)
- [API Integration](#-api-integration)
- [State Management](#-state-management)
- [Testing](#-testing)
- [Deployment](#-deployment)
- [Contributing](#-contributing)
- [Support](#-support)
- [License](#-license)

## 🎯 About

**GainzClan** is a revolutionary AI-powered fitness gaming platform that transforms traditional workouts into engaging, competitive experiences. Built with Next.js and React, the platform combines cutting-edge AI technology with gamification mechanics to create an addictive fitness ecosystem where every rep counts and every workout becomes an epic battle.

### Key Highlights

- 🧠 **AI-Powered Detection**: 99% accurate real-time rep counting and form analysis
- 🏆 **Competitive Gaming**: Live battles, clan wars, and eSports integration
- 🤝 **Social Fitness**: Build unbreakable bonds through shared victories
- 🎮 **Gamified Progress**: Achievement systems, badges, and progression mechanics
- 📱 **Cross-Platform**: Web platform with mobile app integration
- 🌍 **Global Community**: Connect with fitness warriors worldwide
- 📊 **Real-Time Analytics**: Live leaderboards and performance tracking
- 🎯 **Personalized Coaching**: AI-generated workout plans and recommendations

## ✨ Features

### Core Features
- **AI Workout Detection**
  - Real-time rep counting with 99% accuracy
  - Form analysis and correction feedback
  - Multi-exercise support (50+ exercises)
  - Computer vision-based movement tracking

- **Competitive Gaming System**
  - Live battle mode with real-time updates
  - Clan formation and team challenges
  - Global leaderboards and rankings
  - Tournament system with prizes

- **Social Fitness Community**
  - Create and join fitness clans
  - Friend challenges and competitions
  - Community events and challenges
  - Social sharing and motivation

- **Gamification & Motivation**
  - Achievement badge system (100+ badges)
  - Level progression and skill trees
  - Streak tracking and consistency rewards
  - Milestone celebrations and rewards

### Advanced Features
- **Progressive Web App**: Offline functionality and app-like experience
- **Dark Mode**: Complete dark theme support
- **Multi-language Support**: English with expansion plans
- **Real-time Notifications**: Battle updates and motivation
- **Analytics Dashboard**: Comprehensive progress tracking
- **Subscription Plans**: Free, Premium, and Elite tiers

## 🛠️ Tech Stack

### Frontend
- **Framework**: [Next.js](https://nextjs.org/) 15.4.6
- **Language**: [TypeScript](https://www.typescriptlang.org/) 5.0
- **UI Library**: [React](https://reactjs.org/) 19.1.0
- **Styling**: [Tailwind CSS](https://tailwindcss.com/) 4.0

### UI/UX Libraries
- **Animations**: [Framer Motion](https://www.framer.com/motion/) 12.23.12
- **Icons**: [Lucide React](https://lucide.dev/) 0.539.0
- **Components**: [Headless UI](https://headlessui.com/) 2.2.7
- **Utilities**: [Class Variance Authority](https://cva.style/) 0.7.1

### Development Tools
- **Package Manager**: npm with package-lock.json
- **Linting**: ESLint with Next.js configuration
- **Code Formatting**: Built-in formatting
- **Type Checking**: TypeScript strict mode

### Additional Libraries
- **State Management**: React Hooks and Context API
- **Notifications**: [Sonner](https://sonner.emilkowal.ski/) 2.0.7
- **Utilities**: [clsx](https://github.com/lukeed/clsx) 2.1.1, [tailwind-merge](https://github.com/dcastil/tailwind-merge) 3.3.1

## 🏗️ Architecture

The platform follows a modern Next.js 13+ app directory architecture:

```
src/
├── app/                    # Next.js 13+ app directory
│   ├── about/             # About page
│   ├── blog/              # Blog section
│   ├── community/         # Community features
│   ├── exercises/         # Exercise library
│   ├── privacy/           # Privacy policy
│   ├── quiz/              # Fitness assessment
│   ├── support/           # Support center
│   ├── team/              # Team information
│   ├── terms/             # Terms of service
│   ├── globals.css        # Global styles
│   ├── layout.tsx         # Root layout
│   └── page.tsx           # Homepage
├── components/            # Reusable components
│   ├── ui/               # Base UI components
│   │   ├── Button.tsx    # Button component
│   │   └── Card.tsx      # Card component
│   ├── AchievementBadgeWall.tsx
│   ├── AppSimulationTeaser.tsx
│   ├── ClanStorySpotlight.tsx
│   ├── DailyMotivationalQuote.tsx
│   ├── DynamicMotivationalHero.tsx
│   ├── FitnessStreakHeatmap.tsx
│   ├── FitnessTipsCarousel.tsx
│   ├── GlobalChallengeCountdown.tsx
│   ├── Navigation.tsx
│   ├── PrivacySection.tsx
│   ├── SupportSection.tsx
│   ├── TeamSection.tsx
│   └── TermsSection.tsx
├── hooks/                 # Custom React hooks
│   └── useClientOnly.ts  # Client-side only hook
└── lib/                   # Utility libraries
    └── utils.ts          # Helper functions
```

### Design Patterns
- **Component-Based Architecture**: Reusable UI components
- **Custom Hooks**: Logic encapsulation and reusability
- **Utility Functions**: Common helper functions
- **Responsive Design**: Mobile-first approach with Tailwind CSS

## 🚀 Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) 18.0 or higher
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)
- [Git](https://git-scm.com/)
- [VS Code](https://code.visualstudio.com/) (recommended)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/ssgit/gainz-clan-website.git
   cd gainz-clan-website
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Configure environment variables**
   ```bash
   # Copy .env.example to .env.local and fill in your values
   cp .env.example .env.local
   ```

4. **Run the development server**
   ```bash
   npm run dev
   ```

5. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

### Available Scripts

```bash
# Development server
npm run dev

# Production build
npm run build

# Start production server
npm start

# Lint code
npm run lint

# Type checking
npm run type-check
```

## 📁 Project Structure

```
gainz-clan-website/
├── src/                   # Source code
│   ├── app/              # Next.js app directory
│   ├── components/       # React components
│   ├── hooks/            # Custom React hooks
│   └── lib/              # Utility libraries
├── public/               # Static assets
├── .next/                # Build output
├── node_modules/         # Dependencies
├── package.json          # Project configuration
├── next.config.ts        # Next.js configuration
├── tailwind.config.js    # Tailwind CSS configuration
├── tsconfig.json         # TypeScript configuration
└── README.md             # Project documentation
```

## 🔌 API Integration

The platform is designed to integrate with:

- **AI Services**: Computer vision and machine learning APIs
- **Authentication**: User management and security
- **Real-time Services**: WebSocket connections for live features
- **Payment Processing**: Subscription and transaction management
- **Analytics**: User behavior and performance tracking

### API Features
- **RESTful Design**: Standard API patterns
- **Real-time Updates**: Live data synchronization
- **Error Handling**: Comprehensive error management
- **Security**: Authentication and authorization
- **Scalability**: Designed for high-performance

## 📊 State Management

The platform uses modern React patterns:

- **React Hooks**: Built-in state management
- **Context API**: Global state sharing
- **Custom Hooks**: Reusable logic encapsulation
- **Local State**: Component-level state management

### Key Hooks
- **useClientOnly**: Client-side rendering utilities
- **Custom Hooks**: Platform-specific functionality
- **State Patterns**: Efficient state management strategies

## 🧪 Testing

### Testing Strategy
```bash
# Run unit tests
npm run test

# Run integration tests
npm run test:integration

# Run end-to-end tests
npm run test:e2e

# Generate coverage report
npm run test:coverage
```

### Testing Tools
- **Jest**: Unit and integration testing
- **React Testing Library**: Component testing
- **Playwright**: End-to-end testing
- **MSW**: API mocking and testing

## 🚀 Deployment

### Production Build
```bash
# Build the application
npm run build

# Start production server
npm start
```

### Deployment Platforms
- **Vercel**: Next.js optimized hosting
- **Netlify**: Static site hosting
- **AWS**: Cloud infrastructure
- **Docker**: Containerized deployment

## 🤝 Contributing

We welcome contributions! Please follow these steps:

### Contribution Guidelines
1. Fork the repository
2. Create a feature branch: `git checkout -b feature/amazing-feature`
3. Commit your changes: `git commit -m 'Add amazing feature'`
4. Push to the branch: `git push origin feature/amazing-feature`
5. Open a Pull Request

### Code Standards
- Follow TypeScript strict mode
- Use ESLint configuration
- Maintain component structure
- Add tests for new features
- Update documentation as needed

## 📞 Support

### Contact Information
- **Lead Developer**: ENG. MOHAMMAD ALREFAIE
- **Email**: eng.mohammad.uae@gmail.com
- **UAE Phone**: +971567561512
- **Syria Phone**: +963996696170
- **Address**: UAE - Dubai

### Company Information
- **Company**: Smart Science Gate Information Technology (SSGIT)
- **Website**: [https://ssgit.ae/](https://ssgit.ae/)
- **Office**: Office 406, IVORY - SHOPA Tower, Dubai, UAE
- **Phone**: +971 04 568 1333
- **Email**: info@ssgit.ae

### Developer Profiles
- 💼 **LinkedIn**: [https://www.linkedin.com/in/muhammad-al-rifai/](https://www.linkedin.com/in/muhammad-al-rifai/)
- 🐙 **GitHub**: [https://github.com/Mohammad-al-rifai](https://github.com/Mohammad-al-rifai)

### Getting Help
- 📧 **Email Support**: eng.mohammad.uae@gmail.com
- 📱 **UAE Phone Support**: +971567561512
- 📱 **Syria Phone Support**: +963996696170
- 🐛 **Report Issues**: Create an issue on GitHub
- 💼 **Business Inquiries**: info@ssgit.ae

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### License Terms
- **Commercial Use**: Allowed for commercial purposes
- **Modification**: Allowed to modify and distribute
- **Distribution**: Allowed to distribute and sublicense
- **Liability**: No warranty or liability provided
- **Patent Use**: No patent rights granted

## 🙏 Acknowledgments

- **Next.js Team**: For the amazing React framework
- **React Team**: For the powerful UI library
- **Tailwind CSS**: For the utility-first CSS framework
- **Framer Motion**: For beautiful animations
- **Open Source Community**: For continuous inspiration and support
- **Beta Testers**: For valuable feedback and testing
- **Fitness Community**: For domain expertise and guidance
- **Claude Code**: For AI assistance and development support

---

## 🚀 Ready to Transform Fitness?

Join the fitness revolution where gaming meets gains. Every rep counts, every battle matters, and every victory brings you closer to legendary status.

**Download GainzClan today and start your epic fitness journey!**

- [iOS App Store](#) 🍎
- [Google Play Store](#) 🤖
- [Web Platform](#) 🌐

---

<div align="center">
  <p>Made with ❤️ by <a href="https://ssgit.ae/">SSGIT Team</a></p>
  <p>⭐ Star this repository if you find it helpful!</p>
</div>

**Transforming fitness through technology and community**
