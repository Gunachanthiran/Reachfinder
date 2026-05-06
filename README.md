# ReachFinder — Free HR Contact Intelligence Tool
## Complete Setup Guide (Free Forever)

---

## 🚀 Step 1: Host on GitHub Pages (Free Forever)

1. Go to https://github.com/new
2. Create repo named: `reachfinder` (or any name)
3. Set it to **Public**
4. Upload `index.html` to the repo root
5. Go to **Settings → Pages → Source → main branch → / (root)**
6. Your site will be live at: `https://YOUR_USERNAME.github.io/reachfinder`

---

## 🔑 Step 2: Get Your Free API Keys

### 1. Google Gemini (FREE — No monthly limit)
- Go to: https://aistudio.google.com/app/apikey
- Click "Create API key"
- Copy the key (starts with `AIza...`)
- **Quota:** Unlimited on free tier (15 req/min limit)

### 2. Hunter.io (FREE — 25 searches/month)
- Go to: https://hunter.io/users/sign_up
- Sign up with email
- Go to Dashboard → API → Copy your API key
- **Quota:** 25 email finds/month, resets on 1st of each month
- **Tip:** Create 2-3 free accounts with different emails for more quota

### 3. Apollo.io (FREE — 50 exports/month)
- Go to: https://developer.apollo.io
- Sign up free → Settings → API Keys → Create Key
- **Quota:** 50 contact exports/month free
- **Tip:** Free tier also gives 5 phone number reveals/month

---

## ⚙️ Step 3: Configure the Tool

1. Open your hosted site
2. Click **⚙ API Keys** in the top right
3. Paste your API keys
4. Fill in your profile (name, email, LinkedIn, GitHub)
5. Click **Save All Keys Locally**

Keys are stored in your browser's localStorage — **never sent to any server**.

---

## 📈 How to Maximize Free Quota

| Strategy | Result |
|---|---|
| Use Gemini for discovery first | Unlimited searches |
| Save Hunter quota for top contacts only | Stretch 25 → verify best leads |
| Apollo for bulk HR title filters | 50 real contacts/month |
| Export CSV and track outreach | No repeat searches |
| Reset monthly on 1st | Fresh quota each month |

### Monthly workflow:
1. **Week 1:** Run Gemini search for all 3 cities (BLR + CHN + HYD) — unlimited
2. **Week 2:** Use Hunter.io on your top 25 best leads for verified emails
3. **Week 3:** Use Apollo.io 50 credits for new company searches
4. **Week 4:** Outreach using generated messages + CSV tracking

---

## 🆓 100% Free Stack Summary

| Component | Tool | Cost |
|---|---|---|
| Hosting | GitHub Pages | Free forever |
| AI Search | Google Gemini API | Free (15 req/min) |
| Email Finding | Hunter.io | Free 25/month |
| Contact DB | Apollo.io | Free 50/month |
| Email Pattern | Built-in engine | Free forever |
| CSV Export | Built-in | Free forever |
| Message Gen | Built-in AI | Free forever |

**Total monthly cost: ₹0**

---

## 🔄 Optional Upgrades (If You Want More)

| Upgrade | Cost | What you get |
|---|---|---|
| Hunter.io Starter | $49/mo | 500 searches |
| Apollo.io Basic | $49/mo | Unlimited exports |
| Gemini 1.5 Pro | Pay-per-use | Better AI quality |
| Snov.io Free | Free | Extra 50 emails/mo |
| Skrapp.io Free | Free | Extra 100 emails/mo |

---

## 💡 Pro Tips for Job Search

1. **Personalize every message** — the tool generates a template, edit it with 1 specific detail about the company
2. **LinkedIn + Email combo** — send LinkedIn connection request first, then email 2 days later
3. **Reference the tech stack** — mention Selenium/Playwright/Python BDD specifically
4. **GitHub link** — always include your GitHub portfolio link
5. **Follow up once** — follow up exactly 1 week later if no reply
6. **Track in CSV** — export contacts, add columns: Contacted Date, Reply Status, Interview Stage

---

## 📁 File Structure

```
reachfinder/
├── index.html          ← Main app (single file, works standalone)
└── README.md           ← This guide
```

No npm, no build step, no server required. Pure HTML/CSS/JS.

---

## 🛠️ Customization

To add more companies to demo data, edit the `getDemoData()` function in index.html.
To change default profile, edit the `loadKeys()` defaults in index.html.
To add more cities, add `<option>` to the city select and update filter logic.

---

Built by Gunachanthiran K | github.com/Gunachanthiran
