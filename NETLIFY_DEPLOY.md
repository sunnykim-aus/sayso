# Deploy SAYSO to Netlify — Complete Version

This is the **complete, fully working app** ready to deploy in 5 minutes.

## What's included
- ✅ 28-day curriculum with 4 weeks of career skills
- ✅ 10 phrasal verbs/day (140 total)
- ✅ 3 business vocab words/day (84 total)
- ✅ Power phrases (weak → confident rewrites)
- ✅ AI coach for conversation practice
- ✅ Progress saving (localStorage)
- ✅ TTS (text-to-speech) for everything
- ✅ Mic-ready for real speech feedback

## Deploy to Netlify (5 minutes)

### 1. Create a fresh GitHub repo
- Go to **github.com** → **＋ icon** → **New repository**
- Name: `sayso-business`
- Create it

### 2. Upload the files
- Click **Add file** → **Upload files**
- Drag ALL of these into GitHub:
  ```
  index.html
  netlify.toml
  .gitignore
  api/  (folder with claude.js)
  ```
- Make sure they're at the **root level** (not in a subfolder)
- Click **Commit changes**

### 3. Deploy on Netlify
- Go to **netlify.com**
- Click **Sign up** → **Sign up with GitHub** → authorize
- Click **Add new site** → **Import an existing project**
- Find your `sayso-business` repo → click **Deploy**
- Netlify auto-detects the files and serverless function

### 4. Add your API key
- Wait for the first deploy to complete (~1 min)
- Go to **Site settings** → **Build & deploy** → **Environment** → **Add**
- **Key:** `ANTHROPIC_API_KEY`
- **Value:** your `sk-ant-...` key from console.anthropic.com
- Click **Save**

### 5. Redeploy
- Go to **Deploys** → click **Trigger deploy** → **Deploy site**
- Wait 1-2 minutes

**You're live!** Your URL is shown at the top.

---

## Test it

1. Open your Netlify URL (looks like `https://sayso-business.netlify.app`)
2. Click **Build my plan**
3. Answer 4 quick questions
4. Start Day 1
5. Click **Start speaking 🎙️**
6. Speak for 90 seconds
7. You see "Done! 🎉"
8. Progress is saved automatically

---

## Costs

- **Netlify hosting:** $0 (free tier)
- **GitHub:** $0
- **Anthropic API:** ~$0.01–0.05/day for daily practice (set a limit in console.anthropic.com)

---

## That's it!

You now have SAYSO Business live, with:
- 28 days of speaking drills
- 140 phrasal verbs
- AI coach that gives real feedback
- Progress that saves automatically
- No build steps, no npm, just plain HTML + React from CDN

Do Day 1 today. By Day 28, speaking in meetings will feel natural. 🎉
