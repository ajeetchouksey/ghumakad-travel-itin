# 🧳 Ghumakad - AI Travel Planner

<div align="center">
  <img src="https://img.shields.io/badge/AI%20Powered-Travel%20Planning-orange?style=for-the-badge&logo=airplane&logoColor=white" alt="AI Powered" />
  <img src="https://img.shields.io/badge/React-18+-blue?style=for-the-badge&logo=react&logoColor=white" alt="React" />
  <img src="https://img.shields.io/badge/TypeScript-5+-blue?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Azure-Cloud%20Ready-blue?style=for-the-badge&logo=microsoft-azure&logoColor=white" alt="Azure" />
</div>

## 🌟 Features

### 🤖 Meet Aarya - Your AI Travel Companion
- **Conversational Planning**: Natural language trip planning
- **Instant Itineraries**: Complete travel plans in seconds
- **Smart Recommendations**: ML-powered personalized suggestions
- **Memory & Learning**: Remembers your preferences and improves over time

### 🎯 Comprehensive Travel Planning
- **Multi-Day Itineraries**: Detailed day-by-day planning
- **Budget Tracking**: Real-time cost estimates and expense management
- **Weather Integration**: Live weather with activity recommendations
- **Route Optimization**: Minimized travel time between locations

### 🏨 Advanced Booking Integration
- **Multi-Provider Search**: Compare prices across platforms
- **Real-time Availability**: Live booking data
- **Unified Management**: Centralized reservation dashboard
- **Price Monitoring**: Automatic price drop alerts

### 🌍 Global Ready
- **15+ Languages**: Hindi, Spanish, French, German, Japanese, and more
- **Currency Conversion**: Real-time exchange rates
- **Cultural Adaptation**: Location-aware recommendations
- **Local Insights**: Hidden gems and authentic experiences

## 🚀 Quick Start

### Prerequisites
- Node.js 18+
- npm or yarn
- Modern web browser

### Installation
```bash
git clone https://github.com/ajeetchouksey/ghumakad-travel-itin.git
cd ghumakad-travel-itin
npm install
npm run dev
```

### Environment Setup
Create a `.env.local` file:
```env
VITE_WEATHER_API_KEY=your_openweather_api_key
VITE_MAPS_API_KEY=your_maps_api_key
VITE_AZURE_OPENAI_KEY=your_azure_openai_key
```

## 📱 Usage

1. **Start Planning**: Tell Aarya where you want to go
2. **Get Instant Results**: Receive complete itinerary in seconds
3. **Customize & Refine**: Chat naturally to adjust your plans
4. **Book & Manage**: Use integrated booking tools
5. **Track & Learn**: Monitor expenses and let AI learn your preferences

## 🏗️ Architecture

### Frontend Stack
- **React 18** with TypeScript
- **Tailwind CSS** for styling
- **Shadcn/ui** component library
- **Framer Motion** for animations
- **React Query** for data management

### AI & ML Integration
- **Azure OpenAI** for conversational AI
- **Custom ML Models** for recommendations
- **Reaction-based Learning** from user feedback
- **Conversation Memory** for personalization

### APIs & Services
- **Weather APIs** for real-time conditions
- **Booking APIs** for reservations
- **Maps APIs** for location services
- **Currency APIs** for exchange rates

## 🎨 Design Philosophy

Ghumakad follows modern UI/UX principles:
- **Minimalist Design** - Clean, uncluttered interface
- **Conversational UX** - Natural language interactions
- **Progressive Disclosure** - Information revealed as needed
- **Responsive First** - Mobile-optimized experience
- **Accessibility** - WCAG 2.1 AA compliant

## 🔧 Development

### Project Structure
```
src/
├── components/          # React components
├── lib/                # Utilities and APIs
├── assets/             # Static files
├── hooks/              # Custom React hooks
└── types/              # TypeScript definitions
```

### Key Components
- `ChatInterface` - Main conversation component
- `ItineraryDisplay` - Trip visualization
- `BookingHub` - Reservation management
- `MLDashboard` - AI recommendations
- `BudgetTracker` - Expense monitoring

### Contributing
1. Fork the repository
2. Create feature branch: `git checkout -b feature/amazing-feature`
3. Commit changes: `git commit -m 'Add amazing feature'`
4. Push to branch: `git push origin feature/amazing-feature`
5. Open Pull Request

## 🚀 Deployment

### Azure Deployment (Recommended)
```bash
npm run build
npm run deploy:azure
```

### Alternative Platforms
- **Vercel**: `npm run deploy:vercel`
- **Netlify**: `npm run deploy:netlify`
- **AWS S3**: `npm run deploy:aws`

## 📊 Performance

- **Lighthouse Score**: 95+ across all metrics
- **First Contentful Paint**: <1.5s
- **Time to Interactive**: <2.5s
- **Bundle Size**: Optimized and tree-shaken

## 🔒 Security

- **Data Privacy**: Local storage with encryption
- **API Security**: Secure key management
- **Input Validation**: Comprehensive sanitization
- **HTTPS Only**: Secure communication

## 🌟 Roadmap

### Near Term (Q1 2024)
- [ ] Voice interface integration
- [ ] Offline map downloads
- [ ] Group trip planning
- [ ] Advanced ML personalization

### Long Term (Q2-Q3 2024)
- [ ] Mobile app (React Native)
- [ ] AR/VR experiences
- [ ] Blockchain loyalty rewards
- [ ] Advanced analytics dashboard

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Support

- **Documentation**: [docs.ghumakad.com](https://docs.ghumakad.com)
- **Issues**: [GitHub Issues](https://github.com/ajeetchouksey/ghumakad-travel-itin/issues)
- **Discussions**: [GitHub Discussions](https://github.com/ajeetchouksey/ghumakad-travel-itin/discussions)
- **Email**: support@ghumakad.com

## 🎉 Acknowledgments

- **OpenAI** for GPT integration
- **Microsoft Azure** for cloud services
- **Shadcn/ui** for component library
- **Open source community** for various libraries and tools

---

<div align="center">
  <p>Made with ❤️ by the Ghumakad Team</p>
  <p>Happy Traveling! 🌍✈️</p>
</div>
