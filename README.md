![Samba Sales Co-Pilot Logo](https://sambanova.ai/hubfs/sambanova-logo-black.png)

# Samba Co-Pilot

An intelligent sales and research assistant powered by SambaNova AI. This application helps sales teams and researchers by automatically:
- Generating sales information with company insights
- Creating detailed research reports and educational content
- Intelligently routing queries to the appropriate service
- Supporting voice input for natural interaction

## Features

### Intelligent Query Routing
The application automatically determines whether your query is best suited for:
- Sales lead Information Gathering
- Educational content/research creation
- Financial Analysis and Market Research
- More tasks to come!

### Sales Lead Information
When in sales mode, Samba Co-Pilot will:
- Find relevant companies matching your criteria
- Extract key company information
- Provide funding status and insights
- Generate customized sales approaches

Example Sales Queries:
- "Find AI startups in Silicon Valley with Series B funding"
- "Which healthcare companies in Boston are working on drug discovery?"
- "Show me cybersecurity companies in Israel with enterprise clients"
- "Find sustainable energy startups in Nordic countries"
- "Which fintech companies received funding in the last 6 months?"
- "Show me B2B SaaS companies in Singapore with over 100 employees"

### Research & Content Generation
For research queries, the system will:
- Analyze topics in-depth
- Create structured research reports
- Provide educational content
- Include relevant citations and sources

Example Research Queries:
- "Explain quantum computing and its applications in cryptography"
- "How does CRISPR gene editing work in modern medicine?"
- "What's the relationship between AI and neuromorphic computing?"
- "Explain the impact of blockchain on supply chain management"
- "How do machine learning algorithms handle natural language processing?"
- "What are the latest developments in fusion energy research?"

### Financial Analysis & Market Research
For financial queries, Samba Co-Pilot will:
- Analyze company financial performance
- Track market trends and competitive positioning
- Evaluate stock performance and valuation metrics
- Generate investment insights
- Monitor industry-specific metrics
- Compare companies within sectors

Example Financial Queries:
- "Analyze Tesla's recent performance and future growth prospects"
- "How is the semiconductor industry performing this quarter?"
- "Compare cloud revenue growth between Microsoft Azure and AWS"
- "What's the market outlook for AI chip manufacturers?"
- "Evaluate Apple's financial health considering recent product launches"
- "Compare profitability metrics between major EV manufacturers"

### Voice Input Support
- Click the microphone icon to start voice input
- Automatic transcription of speech to text
- Hands-free operation support

### Additional Features
- 🔐 Secure API key management with encryption
- 📜 Chat history tracking
- 📥 Results export functionality
- 🔄 Real-time query routing
- 📊 Detailed company insights
- 💹 Financial analysis and market trends
- ✍️ AI-generated outreach templates

## Technical Setup

### Prerequisites
- Node.js 16+
- NPM or Yarn
- API Keys:
  - SambaNova API key
  - Serper API key (for web search)
  - Exa API key (for company data)

### Installation
```bash
npm install
```

### Development
```bash
npm run dev
```

### Production Build
```bash
npm run build
```

## Environment Variables

Create a `.env` file with:
```env
VITE_API_URL=your_api_url
```

## API Keys Setup

Access the settings modal to configure your:
- SambaNova API key
- Serper API key
- Exa API key

All keys are encrypted before storage in localStorage.

## Architecture

Built with:
- Vue 3 + Composition API
- Vite
- TailwindCSS
- Clerk for authentication
- Axios for API calls

## Tech Stack

### Frontend
- Vue.js 3 (Composition API)
- TailwindCSS for styling
- Vite for build tooling
- Clerk for authentication

### Backend Integration
- FastAPI
- CrewAI
- SambaNova Agentic Cloud
- Exa Search API
- Financial Data APIs

## Usage

1. **Configure API Keys**
   - Open settings
   - Enter your API keys
   - Keys are securely encrypted

2. **Start Searching**
   - Type your query or use voice input
   - System automatically determines query type
   - Receive structured results

3. **View Results**
   - Sales information displayed as cards
   - Research shown as structured reports
   - Export functionality available
   - Save important searches

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request

## License

[MIT License](LICENSE)