# A.R.M FIBER TECH LTD — Website Repository

**Professional OEM Truck Parts Supplier · Jos, Plateau State, Nigeria**

---

## 📋 Project Overview

A.R.M Fiber Tech Ltd is a specialized heavy-duty truck parts supplier serving Nigerian fleet operators, transport companies, and maintenance facilities. This repository contains the production-ready website and deployment configuration.

**Company Details:**
- **Legal Name:** A.R.M TECH-FIBER INT'L LTD
- **Registration Code:** RC 1312501
- **Factory:** B13 Nepa 7 Miles Zaria Road, Jos, Plateau State, Nigeria
- **Workshop:** Behind Jengre Filling Station, Off Deeper Life Junction, 7 Miles Zaria Road, Jos, Plateau State, Nigeria

---

## 📦 Repository Structure

```
arm-fiber-tech-website/
├── index.html                          # Main homepage (production-ready)
├── README.md                           # This file
├── .gitignore                          # Git exclusions
├── DEPLOYMENT_GUIDE.html               # Interactive HTML deployment guide
└── ARM_FIBER_TECH_DEPLOYMENT_GUIDE.md  # Full technical documentation
```

---

## 🚀 Quick Start (Free Tier Deployment)

### Step 1: Clone This Repository
```bash
git clone https://github.com/YOUR_USERNAME/arm-fiber-tech-website.git
cd arm-fiber-tech-website
```

### Step 2: Deploy to Vercel (Free Tier)
1. Go to **vercel.com** → Sign up with GitHub
2. Click **"Import Project"** → Select this repository
3. **Framework Preset:** Other (static site)
4. **Root Directory:** . (current folder)
5. Click **Deploy** ✓

**Result:** Website live at `arm-fiber-tech-website.vercel.app` (automatic default domain)

### Step 3: Enable Cloudflare CDN (Free Tier)
1. Go to **cloudflare.com** → Sign up
2. **Add Site** → Enter your Vercel domain
3. Select **Free Plan**
4. Copy Cloudflare nameservers → No additional DNS setup needed
5. **SSL/TLS:** Automatic (Full encryption)

### Step 4: Supabase Database (Free Tier, Optional)
If you want to track orders automatically:
1. Go to **supabase.com** → Create Account
2. **New Project** → `arm-fiber-tech`
3. Follow embedded guide in `DEPLOYMENT_GUIDE.html`

---

## 💻 Local Development

### Prerequisites
- Any modern browser (Chrome, Firefox, Safari, Edge)
- No build tools required (pure HTML/CSS/JavaScript)

### Run Locally
```bash
# Option 1: Open directly in browser
open index.html

# Option 2: Use Python simple server
python3 -m http.server 8000
# Visit http://localhost:8000

# Option 3: Use Node.js server
npx http-server
# Visit http://localhost:8080
```

---

## 📞 Contact Information

**Phone:**
- +234 803 703 6376
- +234 805 627 3320

**Email:**
- Armtechfiber@gmail.com
- Armtechworkshop1@gmail.com

**WhatsApp Orders:** [Send Message](https://wa.me/2348037036376?text=Hello%20A.R.M%20Fiber%20Tech!%20I%20need%20truck%20parts%20for...)

---

## 🔧 Making Changes

### Update Website
1. Edit `index.html` on your computer
2. Commit and push to GitHub:
```bash
git add index.html
git commit -m "Update: [Your change description]"
git push origin main
```
3. Vercel auto-deploys automatically (2-5 minutes)
4. Check deployment status at **vercel.com/dashboard**

### View Full Deployment Guide
Open `DEPLOYMENT_GUIDE.html` in your browser for:
- Step-by-step setup instructions
- Supabase database configuration
- Cloudflare optimization
- Monitoring and maintenance
- Troubleshooting reference

---

## 📊 Deployment Architecture (Free Tier)

```
GitHub Repository
    ↓
Vercel (Auto-deploy)
    ↓
Cloudflare CDN (Optional)
    ↓
Supabase Database (Optional)
    ↓
Website Live 🌍
```

**Total Cost: ₦0/month** (all free tiers)

---

## ✅ Free Tier Limits

| Service | Limit | Notes |
|---------|-------|-------|
| **Vercel** | 100GB/month bandwidth | More than enough for 10K+ visitors/month |
| **Cloudflare** | Unlimited bandwidth | Free DDoS protection, caching, SSL |
| **Supabase** | 500MB storage, 2 concurrent connections | Perfect for order tracking |
| **Domain** | Default Vercel domain | `arm-fiber-tech-website.vercel.app` |

**When to upgrade:** Only if you exceed these limits (unlikely in first 6-12 months).

---

## 📋 Deployment Checklist

Before going live:

- [ ] Repository created on GitHub
- [ ] `index.html`, `README.md`, `.gitignore` committed
- [ ] Vercel project imported and deployed
- [ ] Website loads at Vercel default domain
- [ ] Forms test successfully (WhatsApp link works)
- [ ] Mobile responsive (test on phone)
- [ ] No console errors (F12 → Console)
- [ ] Cloudflare enabled (if desired)
- [ ] Email notifications configured (if using Supabase)

---

## 🛠️ Support & Resources

**Deployment Issues?**
1. Check `DEPLOYMENT_GUIDE.html` (interactive guide)
2. Review troubleshooting section below
3. Check Vercel logs: **vercel.com/dashboard** → Deployments tab

**Common Issues:**

| Issue | Solution |
|-------|----------|
| Website shows old version | Hard refresh: Ctrl+Shift+Delete (Windows) or Cmd+Shift+Delete (Mac) |
| Deployment fails | Check build logs in Vercel dashboard |
| WhatsApp link broken | Update phone number in `index.html` |
| Slow page loads | Enable Cloudflare CDN |

---

## 📈 Next Steps (Optional Enhancements)

**Month 2-3:**
- [ ] Monitor traffic via Cloudflare Analytics
- [ ] Add Google Analytics for visitor tracking
- [ ] Set up email notifications via Supabase webhooks
- [ ] Create admin dashboard (Supabase Studio)

**Month 3+:**
- [ ] A/B test CTA buttons (WhatsApp vs Email)
- [ ] Add parts inventory search
- [ ] Implement live chat support
- [ ] Migrate to custom domain (₦375/month)

---

## 📄 License

© 2024 A.R.M FIBER TECH LTD. All Rights Reserved.

**Production Ready** — Last Updated: May 2026

---

## 👤 Repository Maintainer

**Technical Contact:** [Your Name/Team]  
**Questions?** Open an issue or email Armtechfiber@gmail.com

---

**Next Step:** Open `DEPLOYMENT_GUIDE.html` in your browser to begin deployment.
