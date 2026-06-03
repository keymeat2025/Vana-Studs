# Vana Studs — Official Website

> **Horse Riding · Breeding · Boarding | Vellore's Indigenous Horse Academy**

![Vana Studs](https://images.unsplash.com/photo-1553284965-83fd3e82fa5a?w=1200&q=85&fit=crop)

---

## 🐴 About This Project

This is the official website for **Vana Studs**, Vellore's premier indigenous horse riding academy. The site was designed and built as a single-page HTML website — no frameworks, no dependencies, just clean HTML, CSS and JavaScript.

**Live Site:** `https://YOUR-USERNAME.github.io/vanastuds/`  
**Instagram:** [@vana_studs](https://www.instagram.com/vana_studs/)

---

## 📁 File Structure

```
vanastuds/
│
├── index.html          ← Main website (single file, everything inside)
└── README.md           ← This file
```

> All CSS, JavaScript and content is embedded inside `index.html` — no external files needed.

---

## 📄 Page Sections

| Section | Description |
|---|---|
| **Top Bar** | Phone, email, hours, social links |
| **Navigation** | Sticky nav with smooth scroll + Book Session CTA |
| **Hero** | Full-screen photo with bold headline |
| **Stats Bar** | 15 years · 40+ horses · 500+ riders · 8 trainers |
| **About** | Academy story + Est. 2009 badge |
| **Services** | Riding · Breeding · Boarding · Competition Coaching |
| **Photo Strip** | Our Herd · Arenas · Trainers |
| **Pricing** | Single Ride · Monthly Pass · Boarding |
| **Testimonials** | 3 rider reviews |
| **Instagram Reels** | Live embed from @vana_studs |
| **Contact** | Enquiry form + address/phone/hours |
| **Footer** | Links · social · Est. 2009 badge |

---

## 🎨 Design

| Property | Value |
|---|---|
| **Primary Color** | Forest Green `#1B4332` |
| **Accent Color** | Gold `#C9A84C` / `#E9C46A` |
| **Heading Font** | Playfair Display (Google Fonts) |
| **Body Font** | Source Sans 3 (Google Fonts) |
| **Icons** | Tabler Icons |
| **Images** | Unsplash (free license) |
| **Style** | BHS-inspired, editorial, professional |

---

## 📞 Contact Details (Update Before Launch)

Open `index.html` and search for the following placeholders to update with real details:

| Field | Current Value | Replace With |
|---|---|---|
| Phone | `+91 98765 43210` | Real phone number |
| Email | `hello@vanastuds.in` | Real email address |
| Address | `Old Katpadi Road, Vellore` | Real address |
| WhatsApp | `919876543210` | Real WhatsApp number |
| Google Maps | `https://maps.google.com` | Real Google Maps link |
| Instagram | `https://www.instagram.com/vana_studs/` | ✅ Already set |

---

## 🖼️ Images

All images are sourced from **Unsplash** (free for commercial use). To replace any image:

1. Find the section in `index.html`
2. Locate the `src="https://images.unsplash.com/photo-XXXXXXXXX"` attribute
3. Replace the URL with your own photo URL

| Section | Photo ID |
|---|---|
| Hero | `1553284965` |
| About — Trainer | `1612225330653` |
| Service — Riding | `1690112328825` |
| Service — Breeding | `premium_1661823534652` |
| Service — Boarding | `1566068256639` |
| Service — Competition | `1594768816441` |
| Photo Strip — Herd | `1612225330565` |
| Photo Strip — Arena | `1726209431921` |
| Photo Strip — Trainers | `1553284965` |
| Contact | `1450052590821` |

---

## 🚀 How to Host on GitHub Pages

1. Create a new **public** repository on [github.com](https://github.com)
2. Upload `index.html` — rename it to `index.html` if needed
3. Go to **Settings → Pages → Source → main branch → Save**
4. Site goes live at `https://YOUR-USERNAME.github.io/REPO-NAME/`

---

## 🌐 Custom Domain Setup (Optional)

To use `vanastuds.in` instead of the GitHub URL:

1. In your repo, create a file named `CNAME` containing just:
   ```
   vanastuds.in
   ```
2. In your domain registrar (GoDaddy/BigRock etc.), add DNS records:
   ```
   A     @     185.199.108.153
   A     @     185.199.109.153
   A     @     185.199.110.153
   A     @     185.199.111.153
   CNAME www   YOUR-USERNAME.github.io
   ```
3. Back in GitHub Pages settings → add `vanastuds.in` under **Custom domain**
4. Check **"Enforce HTTPS"**

---

## ✅ Pre-Launch Checklist

- [ ] Replace phone number with real number
- [ ] Replace email with real email
- [ ] Replace address with real address
- [ ] Update WhatsApp number
- [ ] Add real Google Maps link
- [ ] Test all images load correctly
- [ ] Test contact form (connect to Formspree or Netlify Forms)
- [ ] Test on mobile browser
- [ ] Test Instagram reel embed loads
- [ ] Verify all nav links scroll correctly
- [ ] Check WhatsApp float button works

---

## 📱 Contact Form Setup

The contact form currently has no backend. To make it functional, connect it to **Formspree** (free):

1. Go to [formspree.io](https://formspree.io) and create a free account
2. Create a new form — you'll get an endpoint like `https://formspree.io/f/XXXXXXX`
3. In `index.html`, find the `<button class="submit-btn">` and wrap the form fields in:
   ```html
   <form action="https://formspree.io/f/XXXXXXX" method="POST">
     <!-- existing fields -->
   </form>
   ```
4. Submissions will be emailed to you directly

---

## 🛠️ Built With

- Pure HTML5 + CSS3 + Vanilla JavaScript
- [Google Fonts](https://fonts.google.com) — Playfair Display + Source Sans 3
- [Tabler Icons](https://tabler-icons.io) — outline icon set
- [Unsplash](https://unsplash.com) — free horse photography
- [Instagram Embed API](https://developers.facebook.com/docs/instagram/oembed/) — reel embed

---

## 📝 License

Website design and code created for **Vana Studs**, Vellore, Tamil Nadu.  
All horse photography sourced from Unsplash under the [Unsplash License](https://unsplash.com/license).

---

*Built with ❤️ for Vana Studs — Est. 2009, Vellore, Tamil Nadu*
