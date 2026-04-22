# Meal Planner 🍽

Your friendly Indian meal planner — works as an iPhone home screen app.

## 🌐 Live App

👉 **[kpanchamia.github.io/foodapp](https://kpanchamia.github.io/foodapp)**

## 📱 Add to iPhone Home Screen

1. Open the link above in **Safari** (must be Safari, not Chrome)
2. Tap the **Share** button (box with arrow ↑)
3. Scroll down → tap **"Add to Home Screen"**
4. Tap **Add** → done!

## ✨ Features

- 50+ vegetarian recipes across Breakfast, Lunch, Evening Snacks & Dinner
- Cuisines: Gujarati, South Indian, North Indian, Indo-Chinese, Italian, Mexican, Maharashtrian & more
- Stable daily meal picks — swapping one slot never affects the others
- ⭐ Mark favourites for higher recommendation frequency
- 👍 / 👎 Like or dislike items to refine suggestions
- 🔄 Swap icon to instantly get an alternate suggestion
- Long-press any card for more options (swap, choose manually, edit, send to cook)
- 📲 Send recipe to your cook via WhatsApp
- 📷 Food photos for all recipes
- Nutrition tags (Protein, Carbs, Vitamins, Fiber, Calcium)
- 🥚 Egg toggle — include or exclude egg-based dishes
- Week view — plan this week and next week, Mon–Sun
- Set weekly templates (pin a dish to every Monday, etc.)
- Day view with prev/next navigation
- Add your own recipes with cuisine, recipe, ingredients & video URL
- Remove items from the database
- All settings, favourites & picks saved on-device (works offline)
- Installable as a PWA (Progressive Web App)

## 🗂 Project Structure

```
foodapp/
├── index.html       # Full app (single file)
├── manifest.json    # PWA manifest
├── sw.js            # Service worker (offline support)
├── icons/
│   ├── icon-192.png
│   └── icon-512.png
└── README.md
```

## 🛠 Tech

Pure HTML / CSS / JavaScript — no frameworks, no build step, no dependencies.
Data is stored in `localStorage` on the user's device.
