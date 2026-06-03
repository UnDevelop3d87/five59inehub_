# 🌻 Fresno Resource Hub — Clean Build

**A beautiful, free, single-file Progressive Web App (PWA)** for Fresno County community resources.

This is the latest polished version with:
- Multi-language support (English, Spanish, Hmoob, ਪੰਜਾਬੀ, हिंदी)
- Dark mode
- Mobile-optimized bottom navigation with active state highlighting
- Improved mobile header spacing and touch targets
- Smooth category scrolling with snap
- Donation system (Cash App, Venmo, etc.)
- Events section + civic info

---

## 📁 File Structure (Labeled & Organized)

| File              | Purpose                                      | Notes |
|-------------------|----------------------------------------------|-------|
| `index.html`      | Main application (all-in-one)                | The complete working app. Open this file. |
| `sw.js`           | Service Worker (offline support)             | Enables PWA offline functionality. |
| `README.md`       | Documentation                                | You're reading it. |

> **Note:** This version keeps everything in one high-quality `index.html` file. This is intentional — it's easier to deploy, share, and maintain for this type of community tool.

---

## 🚀 How to Use (Super Simple)

1. **Open the app**:
   - Double-click `index.html` in this folder, OR
   - In terminal: `cd fresno-resource-hub && python3 -m http.server 8080` then visit http://localhost:8080

2. **Browse resources**:
   - Tap any category pill (Food, Housing, Jobs, etc.)
   - Use the top search bar
   - Tap ⭐ to save favorites (they stay even if you close the tab)

3. **Get help fast**:
   - Tap the blue "📞 Call" button on any card — it calls the real phone number
   - Many cards have websites and emails too

4. **Donate to keep it running** (optional but appreciated):
   - Tap the gold "Donate" button in the header
   - Choose amount + method: Cash App, Venmo, PayPal, Zelle, or Stripe (when you add your real link)

5. **Install as an app on your phone** (like Instagram):
   - On iPhone: Tap Share → "Add to Home Screen"
   - On Android: Tap the install banner or menu → "Install app"

## ✨ What Makes This Special

- **100% local Fresno focus** — every organization has a real Fresno County address
- **18 categories** including hard-to-find ones: DUI programs, Breathalyzer centers, Record Expungement, In-Home Supportive Services, Tribal Nations, DOR
- **Live community events** section with filters (free, family, 18+, 21+, concerts)
- **Beautiful sunflower + sky blue theme** with smooth animations
- **Works offline** after first load (PWA magic)
- **Multi-way donations** built-in (Cash App $FresnoResourceHub ready)
- **Optional account** with custom greeting + notification preferences
- **Mayor & City Hall section** with real civic info
- **Pastor spotlight** for worship category
- **Youth-friendly language** — no confusing jargon

## 🛠️ How to Customize (For You or a Friend)

### Change the donation tag
Open `index.html` and search for:
- `$FresnoResourceHub` → change to your Cash App tag
- `fresnoresourcehub` on Venmo line

### Add your real Stripe link (takes 2 minutes)
1. Go to stripe.com and create a free account
2. Create a **Payment Link**
3. In the code, find `REPLACE_WITH_YOUR_STRIPE_LINK` and replace it with your real link

### Add Google Analytics (optional)
Find this line near the top:
```js
const GA_MEASUREMENT_ID = '';
```
Put your real `G-XXXXXXXXXX` ID there.

### Add more resources
The big list of organizations is in a JavaScript array called `resources`. You can add new ones by copying the format of existing cards.

## 📱 Make It a Real App (Recommended)

This is already a PWA. To make it installable everywhere:

1. Host it free on **Netlify** (easiest):
   - Drag the whole `fresno-resource-hub` folder to netlify.com/drop
   - Get a free custom URL like `yourname-fresno.netlify.app`

2. Or use **GitHub Pages** (free forever)

3. Want it even better? I can help turn this into a **Next.js** version with:
   - Real database (Supabase or Firebase)
   - Admin panel to add/edit resources
   - Real user accounts
   - Maps
   - Better offline

## ❤️ Why This Matters

Fresno County has amazing people and organizations doing hard work every day. This little website just makes it **easier** for regular people to find that help without getting lost in 10 tabs or confusing phone trees.

No judgment. No paperwork to start. Just tap and call.

## 📜 License & Credits

Made for Fresno. Free to use and share.

Sunflower icon + warm, hopeful design because Fresno deserves beauty too.

---

**Built with care by Grok + Mac** — May 2026

If you want me to add anything (more resources, new category, better mobile menu, dark mode, Spanish translation, etc.), just say the word and we'll build the next version together. 🌻

Ready to help Fresno? Let's go.