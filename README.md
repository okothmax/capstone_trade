# Global Market Analyzer Pro

## 🔖 Project Description
**Global Market Analyzer Pro** is a cutting-edge web application designed to analyze global stock indices and their derivative contracts (futures, options, CFDs) to identify and recommend the best trading opportunities. The platform is tailored for retail traders, portfolio managers, and financial analysts who need actionable market insights without spending hours on manual analysis.

### Key Features
- Real-time market data aggregation
- AI-powered trade opportunity identification
- Customizable watchlists and alerts
- Performance analytics and backtesting
- User-friendly dashboard with intuitive visualization

## 🛠️ Tech Stack

### Frontend
- **Framework**: Next.js 14 (React)
- **Language**: TypeScript
- **UI Components**: Shadcn UI + Tailwind CSS
- **State Management**: React Query + Zustand
- **Data Visualization**: Recharts / TradingView Lightweight Charts

### Backend
- **Runtime**: Node.js 18+ with TypeScript
- **API Layer**: Next.js API Routes
- **Authentication**: NextAuth.js
- **Database**: Supabase (PostgreSQL)
- **Real-time**: Supabase Realtime

### Data & AI
- **Market Data**: Alpha Vantage API, Polygon.io
- **AI/ML**: Python (scikit-learn, pandas) for analysis
- **Vector Database**: Pinecone for semantic search
- **LLM Integration**: OpenAI GPT-4 for natural language insights

## 🚀 Getting Started

### Prerequisites
- Node.js 18+
- npm or yarn
- Supabase account
- API keys for market data providers

### Installation

1. Clone the repository
```bash
git clone https://github.com/okothmax/capstone_trade.git
cd global-market-analyzer-pro
```

2. Install dependencies
```bash
npm install
```

3. Set up environment variables
```bash
cp .env.example .env.local
# Update the environment variables with your API keys
```

4. Run the development server
```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the application.

### Environment Variables
Create a `.env.local` file with the following variables:
```
NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
ALPHA_VANTAGE_API_KEY=your_alpha_vantage_key
# Add other API keys as needed
```

## 🧠 AI Integration Strategy

### Code Generation
- **Scaffolding**: Use GitHub Copilot and ChatGPT to generate boilerplate code
- **Component Generation**: AI-assisted creation of reusable UI components
- **API Integration**: Automate API client generation from OpenAPI/Swagger specs

### Testing
- **Unit Tests**: AI-generated test cases with Jest and React Testing Library
- **Integration Tests**: AI-assisted test scenarios for critical user flows
- **E2E Testing**: Generate Cypress tests from user stories

## 📊 Project Structure
```
.
├── src/
│   ├── app/                    # Next.js 13+ app directory
│   ├── components/             # Reusable components
│   ├── lib/                    # Utility functions and configs
│   ├── models/                 # TypeScript interfaces/types
│   ├── services/               # API and business logic
│   └── styles/                 # Global styles
├── public/                     # Static assets
├── tests/                      # Test files
└── types/                      # Global TypeScript types
```

## 🤝 Contributing
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments
- Market data provided by Alpha Vantage and Polygon.io
- Built with Next.js and Supabase
- Icons from Lucide React
- AI assistance from GitHub Copilot and OpenAI

---

*This project was created as a capstone project for [Your Institution/Program].*
