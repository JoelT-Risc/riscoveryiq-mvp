# RiscoveryIQ MVP

AI-Powered Employment Law Compliance & Risk Intelligence Platform

## 🚀 Deploy in 5 Minutes (No Coding Required)

### Step 1: Upload to GitHub (2 minutes)

1. **Go to GitHub** → https://github.com (create account if needed)

2. **Create new repository:**
   - Click the **+** icon (top right) → **"New repository"**
   - Name: `riscoveryiq-mvp`
   - Keep it **Public**
   - Click **"Create repository"**

3. **Upload files:**
   - On the new repo page, click **"uploading an existing file"**
   - **Drag and drop ALL files** from this folder (not the folder itself, the files inside)
   - Click **"Commit changes"**

### Step 2: Deploy to Vercel (3 minutes)

1. **Go to Vercel** → https://vercel.com
   - Click **"Sign Up"** → **"Continue with GitHub"**

2. **Import your repo:**
   - Click **"Add New Project"**
   - Find `riscoveryiq-mvp` and click **"Import"**
   - Click **"Deploy"**

3. **Wait ~2 minutes** → Your app is live! 🎉
   - You'll get a URL like: `riscoveryiq-mvp.vercel.app`

---

### Alternative: Deploy to Replit

1. Go to https://replit.com → Create account
2. Click **"Create Repl"** → **"Import from GitHub"**
3. Paste your GitHub repo URL
4. Click **"Run"**

---

## 📁 Project Structure

```
riscoveryiq-mvp/
├── src/
│   ├── app/
│   │   ├── page.tsx           # Landing page
│   │   ├── layout.tsx         # Main layout with navigation
│   │   ├── globals.scss       # Global styles
│   │   ├── dashboard/
│   │   │   └── page.tsx       # Risk dashboard
│   │   ├── assessment/
│   │   │   └── profile/
│   │   │       └── page.tsx   # Company profile form
│   │   └── glossary/
│   │       └── page.tsx       # Glossary page
│   └── components/
│       └── Chatbot.tsx        # AI chatbot component
├── package.json               # Dependencies
├── next.config.js             # Next.js config
├── tsconfig.json              # TypeScript config
└── README.md                  # This file
```

---

## 🎯 What's Included in This MVP

### ✅ Implemented
- **Landing Page** - Professional hero section, features, stats, CTA
- **Dashboard** - Risk gauge, charts, law-by-law breakdown, recommendations
- **Company Profile** - Multi-step form with real-time law applicability
- **Glossary** - Searchable definitions for 13 federal laws, risk terms
- **AI Chatbot** - Context-aware assistant (simulated responses)
- **IBM Carbon Design** - Professional enterprise UI

### 🔜 Not Yet Implemented (Production Phase)
- User authentication
- Database persistence
- Full 393 law coverage
- Monte Carlo simulation
- Document analysis
- Case management
- Real Claude API integration for chatbot

---

## 🔧 Local Development (For Developers)

If you want to run this locally:

```bash
# Install dependencies
npm install

# Run development server
npm run dev

# Open http://localhost:3000
```

---

## 📊 Demo Data

The MVP includes sample data for demonstration:
- 6 federal laws with risk scores
- Sample risk metrics (Overall: 67, Exposure: $150K)
- 13 federal law definitions in glossary
- 8 risk/analytics terms
- 5 risk level definitions

---

## 🔐 Adding Authentication (Next Step)

To add real user accounts, you can integrate Supabase:

1. Create account at https://supabase.com (free tier)
2. Create a new project
3. Get your API keys from Settings > API
4. Create `.env.local` file:
   ```
   NEXT_PUBLIC_SUPABASE_URL=your_url
   NEXT_PUBLIC_SUPABASE_ANON_KEY=your_key
   ```
5. Uncomment the Supabase code in the auth components

---

## 🤖 Enabling Real AI Chatbot

To use the real Claude API for the chatbot:

1. Get an API key from https://console.anthropic.com
2. Add to `.env.local`:
   ```
   ANTHROPIC_API_KEY=your_key
   ```
3. Create an API route at `src/app/api/chat/route.ts`
4. Update Chatbot.tsx to call your API route

---

## 💰 Costs

| Service | Free Tier | Paid |
|---------|-----------|------|
| Vercel | 100GB bandwidth/month | $20/mo for more |
| Supabase | 500MB database, 50K auth users | $25/mo |
| Claude API | $5 free credits | ~$3/1M tokens |

**For an MVP demo, you can run entirely free.**

---

## 📞 Support

For questions about RiscoveryIQ:
- Email: support@riscovery.com
- Website: riscovery.com

---

## 📄 License

© 2025 Riscovery LLC. All rights reserved.

---

## 🎉 Next Steps After Deployment

1. **Test the landing page** - Make sure it loads and looks good
2. **Try the company profile** - Fill out the form, see law applicability
3. **View the dashboard** - See sample risk data and charts
4. **Test the chatbot** - Ask questions about compliance
5. **Browse the glossary** - Search for law definitions
6. **Share with stakeholders** - Get feedback on the MVP
7. **Plan production features** - Decide what to build next
