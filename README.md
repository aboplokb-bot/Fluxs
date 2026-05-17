# ⚡ FLUXS — Algorithm-Driven Energy Optimization

Real-time flux scoring system for executives, founders, and high-performers. Know your peak energy moments. Protect them.

## 🎯 What Is FLUXS?

FLUXS measures your **real-time energy state** based on 5 variables:
- Sleep quality
- Mood
- Energy level
- Focus capacity
- Interruptions

Returns a **1.0-5.0 score** → **6 levels** → **Actionable recommendations**

```
Your flux tells you:
🔴 CRITICAL (1.0-1.4)    → Leave work. Rest now.
🟠 LOW (1.5-2.4)         → Light tasks only. Walk.
🟡 MEDIUM (2.5-3.4)      → Meetings & planning.
💪 HIGH (3.5-4.4)        → Block time for deep work.
⭐ PEAK (4.5-4.9)        → Do your hardest work NOW.
💥 EUREKA (5.0)          → Idea burst. Capture everything.
```

## 📁 Project Structure

```
fluxs/
├── fluxs-working-trial.html          # Customer trial app (single file)
├── fluxs-admin-dashboard.html        # Admin system (user/revenue management)
├── FLUXS-COMPLETE-PRODUCT-SPECIFICATION.md
├── FLUXS-ADMIN-CREDENTIALS-SETUP.md
└── README.md (this file)
```

## 🚀 Deployment

### **Customer App**
```
File: fluxs-working-trial.html
Deploy to: Vercel
Domain: fluxs.store
```

**Flow:**
1. User logs in (no credit card)
2. Fills 5-input trial form
3. Gets real flux score + description + action
4. Sees hard paywall → 3 pricing tiers
5. Selects plan → Dashboard

### **Admin Dashboard**
```
File: fluxs-admin-dashboard.html
Deploy to: Vercel
Domain: admin.fluxs.store
```

**Access:**
- Email: `boplok@yahoo.co.uk`
- Password: Change on first login (forced reset)
- Features: User management, iLEAD tracking, analytics, security

## 💰 Pricing (3 Tiers)

| Tier | Price | Users | Features |
|------|-------|-------|----------|
| **Pro** | £99/mo | 1 | Unlimited check-ins, instant flux, free iLEAD |
| **Elite** | £499/mo | 5 | Pro × 5 + team dashboard + shared visibility |
| **iLead** | £999/mo | ∞ | Elite + 1:1 coaching + VIP 24/7 + custom integrations |

**Year 1 Revenue Target:** £548K ARR

## 🧮 The Algorithm

**Real flux calculation from inputs:**

```
flux = (sleep/5 × 0.2) + (mood × 0.25) + (energy/5 × 0.25) 
       + (focus × 0.15) + (1 - interruptions × 0.15) × 0.15
       
Result: 1.0-5.0 scale
```

**Why it works:**
- ✅ Results vary based on actual inputs
- ✅ No magic numbers (users trust it)
- ✅ Actionable per level
- ✅ Curiosity gap → paywall conversion

## 🔐 Admin Credentials

**Email:** boplok@yahoo.co.uk  
**Temp Password:** FLUXS@Admin2024!Secure (change on first login)

**Permissions:**
- View/edit/suspend/delete users
- Track subscriptions by tier
- Monitor iLEAD delivery
- Real-time analytics (MRR, churn, LTV:CAC)
- Access logs & security

## 📊 Admin Dashboard Tabs

### **Users & Subscriptions**
- View all customers
- See subscription status
- Track signup dates
- Edit user details
- Suspend/delete accounts

### **iLEAD Delivery**
- Track iLEAD framework distribution
- Monitor email opens
- See download rates
- Resend anytime

### **Analytics**
- Free signups count
- Trial completions
- Paid conversions
- Average order value (AOV)
- Monthly churn rate
- LTV:CAC ratio

### **Security Settings**
- Change admin password
- View access logs
- Monitor login history

## 🎯 Launch Sequence

**Day 1 (Deploy):**
1. Deploy both files to Vercel
2. Assign domains (fluxs.store + admin.fluxs.store)
3. Wait for DNS propagation (5-30 mins)

**Day 1-2 (Cold Outreach):**
1. Message 20-30 LinkedIn connections
2. Template: *"Built something. 60-second test. Free. You never know when you peak. fluxs.store"*
3. Track signups in admin dashboard

**Day 3-7 (Harvest):**
1. Monitor daily signups (Users tab)
2. Track conversion rate (Analytics tab)
3. Identify drop-off points
4. Call 5 non-converters: "Why didn't you sign up?"

**Day 8-14 (Iterate):**
1. Test one hypothesis at a time
2. Measure impact
3. Scale what works

## 🔧 Tech Stack

**Frontend:**
- Vanilla JavaScript (no dependencies)
- Mobile-first responsive design
- localStorage for persistence
- Real-time calculations

**Deployment:**
- Vercel (both files)
- Custom domains
- HTTPS automatic

**Future Integration:**
- Stripe (payments)
- Supabase (user data)
- SendGrid (email)
- Slack (notifications)

## 📈 Key Metrics to Track

- **Signups/day**
- **Trial completions**
- **Conversion rate** (free → paid)
- **MRR by tier** (Pro/Elite/iLead breakdown)
- **Churn rate** (monthly cancellations)
- **LTV:CAC ratio** (lifetime value vs acquisition cost)
- **Email open rates** (iLEAD framework)

## 🚨 Security

- ✅ Forced password reset on first admin login
- ✅ All admin actions logged
- ✅ IP tracking
- ✅ Device info stored
- ✅ 2FA ready for Vercel

## 📞 Support

**Customer App Issues:**
- Check browser console (F12)
- Verify localStorage enabled
- Test on different device/browser

**Admin Dashboard Issues:**
- Verify credentials (boplok@yahoo.co.uk)
- Check password changed on first login
- Review security settings tab

## 📝 Files

- **fluxs-working-trial.html** — Customer-facing app (single file, ~32KB)
- **fluxs-admin-dashboard.html** — Admin system (single file, ~35KB)
- **FLUXS-COMPLETE-PRODUCT-SPECIFICATION.md** — Full technical spec
- **FLUXS-ADMIN-CREDENTIALS-SETUP.md** — Security & setup guide

## 🎬 Next Steps

1. ✅ Deploy both files
2. ✅ Message 20 people
3. ✅ Track in admin dashboard
4. ✅ Get feedback (why people convert/don't convert)
5. ✅ Iterate (one thing at a time)
6. ✅ Scale (repeat #2-5)

---

**Status: 🟢 READY TO LAUNCH**

Built by: **Bopolo** (System Architect)  
Last updated: **May 17, 2026**
