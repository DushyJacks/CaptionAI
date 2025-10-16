<div align="center">
  <h1>🎬 SmartCaption AI</h1>
  <p><strong>Intelligent Caption Generation Powered by AI</strong></p>
  
  <p>
    <img src="https://img.shields.io/badge/React-18.x-61DAFB?style=for-the-badge&logo=react" alt="React" />
    <img src="https://img.shields.io/badge/TypeScript-5.x-3178C6?style=for-the-badge&logo=typescript" alt="TypeScript" />
    <img src="https://img.shields.io/badge/Vite-5.x-646CFF?style=for-the-badge&logo=vite" alt="Vite" />
    <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase" alt="Supabase" />
  </p>
</div>

## ✨ Features

- 🤖 **AI-Powered Captions** - Generate contextual captions using advanced AI models
- 🎨 **Smart Content Analysis** - Automatic image/video content recognition
- 💾 **Cloud Storage** - Secure media storage with Supabase
- 👤 **User Authentication** - Seamless login/signup with Supabase Auth
- 📱 **Responsive Design** - Works perfectly on desktop and mobile
- ⚡ **Real-time Processing** - Fast caption generation and updates
- 🔒 **Secure & Private** - End-to-end encryption for user data

## 🚀 How It Works

1. **Upload Media** → Users upload images or videos to the platform
2. **AI Analysis** → Advanced AI models analyze visual content and context
3. **Caption Generation** → Smart algorithms generate relevant, engaging captions
4. **Customization** → Users can edit, refine, and personalize generated captions
5. **Save & Share** → Captions are saved to user's library for future use

## 🛠️ Tech Stack

- **Frontend**: React 18 + TypeScript + Vite
- **Backend**: Supabase (Database + Auth + Storage)
- **AI Services**: OpenAI GPT-4 Vision API
- **Styling**: Tailwind CSS
- **Deployment**: Vercel

## 🚀 Quick Start

```bash
# Clone the repository
git clone https://github.com/DushyJacks/CaptionAI.git
cd smartcaption-ai

# Install dependencies
npm install

# Start development server
npm run dev
```

## ⚙️ Environment Setup

Create a `.env` file in the root directory:

```env
# Supabase Configuration
VITE_SUPABASE_URL=your_supabase_project_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key

# AI Service Configuration
VITE_OPENAI_API_KEY=your_openai_api_key


## 🔑 API Keys Setup

### Supabase
1. Create a project at [Supabase](https://supabase.com)
2. Go to Settings → API
3. Copy your Project URL and anon/public key

### OpenAI
1. Visit [OpenAI Platform](https://platform.openai.com/api-keys)
2. Create a new API key
3. Add billing information for API usage

### Security Best Practices
- ✅ Never commit `.env` files to version control
- ✅ Use environment variables in production
- ✅ Rotate API keys regularly
- ✅ Set up API key usage limits
- ✅ Monitor API usage and costs

## 🌐 Deployment

### Vercel (Recommended)

```bash
# Install Vercel CLI
npm install -g vercel

# Deploy to production
vercel --prod
```

**Environment Variables Setup:**
1. Go to your Vercel dashboard
2. Navigate to Settings → Environment Variables
3. Add all variables from your `.env` file

### Netlify

```bash
# Build the project
npm run build

# Deploy dist/ folder to Netlify
# Or connect your GitHub repo for automatic deployments
```

### Other Platforms

```bash
# Build for production
npm run build

# The dist/ folder contains your production-ready app
# Upload to any static hosting service
```

## 📋 Environment Variables Reference

| Variable | Description | Required | Example |
|----------|-------------|----------|----------|
| `VITE_SUPABASE_URL` | Supabase project URL | ✅ | `https://xxx.supabase.co` |
| `VITE_SUPABASE_ANON_KEY` | Supabase anonymous key | ✅ | `eyJhbGciOiJIUzI1NiIs...` |
| `VITE_OPENAI_API_KEY` | OpenAI API key | ✅ | `sk-proj-xxx...` |
| `VITE_ANTHROPIC_API_KEY` | Anthropic Claude API key | ❌ | `sk-ant-xxx...` |
| `VITE_GOOGLE_AI_KEY` | Google AI API key | ❌ | `AIzaSyC...` |

## 🏗️ Build Commands

```bash
# Development
npm run dev          # Start dev server
npm run dev:host     # Start dev server with network access

# Production
npm run build        # Build for production
npm run preview      # Preview production build locally

# Code Quality
npm run lint         # Run ESLint
npm run type-check   # Run TypeScript checks
```

## 📁 Project Structure

```
src/
├── components/          # Reusable UI components
├── pages/              # Application pages
├── hooks/              # Custom React hooks
├── services/           # API services (Supabase, OpenAI)
├── types/              # TypeScript type definitions
├── utils/              # Utility functions
└── styles/             # Global styles and themes
```

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<div align="center">
  <p>Made with ❤️ by [Your Name]</p>
  <p>
    <a href="#">🌟 Star this repo</a> •
    <a href="#">🐛 Report Bug</a> •
    <a href="#">💡 Request Feature</a>
  </p>
</div>
