# 🤖 Google Gemini AI Chat Setup

The chat feature uses Google Gemini API (100% FREE) to provide intelligent responses about University of Lincoln courses.

## 🚀 Quick Setup (5 minutes)

### Step 1: Get Your Free API Key

1. Go to **[Google AI Studio](https://aistudio.google.com/app/apikey)**
2. Sign in with your Google account
3. Click **"Create API Key"**
4. Copy your API key

### Step 2: Add API Key to Your Project

1. Create a file named `.env.local` in the project root:
   ```bash
   # In the project folder
   touch .env.local
   ```

2. Open `.env.local` and add your API key:
   ```env
   VITE_GEMINI_API_KEY=AIzaSy...your_actual_key_here
   ```

3. Save the file

### Step 3: Restart Development Server

```bash
npm run dev
```

That's it! The chat will now use AI responses! 🎉

---

## 🔒 Security Notes

- ✅ `.env.local` is already in `.gitignore` - your API key is safe
- ✅ Never commit API keys to GitHub
- ✅ For production (Vercel), add the key to environment variables

---

## 📊 Free Tier Limits

Google Gemini Free Tier:
- ✅ **15 requests per minute**
- ✅ **1,500 requests per day**
- ✅ **1 million tokens per minute**

This is **more than enough** for a university course finder app!

---

## 🎯 What Happens Without API Key?

The chat will still work! It falls back to keyword-based responses (basic but functional). However, with Gemini AI, the chat will:
- ✅ Have natural conversations
- ✅ Remember context from earlier messages
- ✅ Provide personalized course advice
- ✅ Answer complex questions intelligently

---

## 🚀 Deploying to Vercel

1. Go to your Vercel project dashboard
2. Navigate to **Settings → Environment Variables**
3. Add:
   - **Name**: `VITE_GEMINI_API_KEY`
   - **Value**: Your API key
   - **Environment**: Production, Preview, Development
4. Redeploy your app

Done! 🎉

---

## 🧪 Testing the Chat

**Good test questions:**
- "What are the entry requirements for Computer Science?"
- "Tell me about campus life at Lincoln"
- "How do I apply for undergraduate courses?"
- "What support services are available for students?"

The AI will provide intelligent, contextual responses! 🤖

---

## 🆘 Troubleshooting

**Chat not responding?**
1. Check `.env.local` file exists
2. Verify API key starts with `AIzaSy`
3. Restart dev server (`npm run dev`)
4. Check browser console for errors

**API quota exceeded?**
- Free tier: 1,500 requests/day
- Wait 24 hours or upgrade to paid tier (optional)

---

## 📝 Notes

- The chat works offline (fallback mode) without API key
- API key is only used in browser (client-side)
- Consider backend proxy for better security in production
- Conversation history is kept in memory (not persisted)
