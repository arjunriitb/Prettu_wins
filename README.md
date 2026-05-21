# ✨ My Little Tasks

A cute productivity tracker made with love 💕  
Built with plain HTML + CSS + JS — no server needed!

---

## 📁 Folder Structure

```
tasks-app/
├── index.html          ← the entire app lives here
├── vercel.json         ← Vercel config (don't touch)
├── images/
│   └── cats/           ← DROP YOUR CAT PICTURES HERE
│       ├── cat1.jpg
│       ├── cat2.jpg
│       └── cat3.jpg
└── README.md
```

---

## 🐱 Adding Cat Pictures

1. Save your cat `.jpg` or `.png` files into `images/cats/`
2. Open `index.html` and find this section near the top of the `<script>`:

```js
const CAT_IMAGES = [
  "images/cats/cat1.jpg",
  "images/cats/cat2.jpg",
  "images/cats/cat3.jpg",
];
```

3. Update the filenames to match what you saved.  
   Add as many as you want — she'll get a random one each time!

---

## 🚀 Deploy to Vercel (free, runs 24/7)

### Step 1 — Push to GitHub
1. Go to [github.com](https://github.com) → sign in → click **New repository**
2. Name it `my-little-tasks`, keep it **Public**, click **Create**
3. Upload all files (drag & drop the whole `tasks-app` folder contents)
4. Click **Commit changes**

### Step 2 — Deploy on Vercel
1. Go to [vercel.com](https://vercel.com) → sign up with your GitHub account
2. Click **Add New → Project**
3. Select your `my-little-tasks` repo → click **Deploy**
4. Done! 🎉 You get a permanent URL like `my-little-tasks.vercel.app`

---

## 🔄 Making Changes Later

1. Edit `index.html` in VS Code
2. Go to your GitHub repo → open `index.html` → click the ✏️ pencil icon
3. Paste your updated code → click **Commit changes**
4. Vercel auto-deploys in ~30 seconds ✅

---

## ⭐ How Points & Rewards Work

| Task            | Points |
|-----------------|--------|
| Study Session   | 20 pts |
| Reading         | 15 pts |
| Walk Outside    | 15 pts |
| Gym Workout     | 25 pts |
| Cook a Meal     | 20 pts |
| Create a Reel   | 35 pts |
| Clean the Room  | 30 pts |

Every **50 points** = 1 cat pic reward! 🐾  
Daily tasks reset every day. Weekly tasks reset every week.

---

## 💌 Reel Ideas

- Switch the dropdown to **"From Babe"** when adding ideas for her
- She sees them labeled with 💌
- She can mark ideas as Used ✅ or delete them
