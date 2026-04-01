# Better Climate Zone LLC — Website

Production-ready HVAC website for Better Climate Zone LLC, optimized for SEO and Netlify deployment.

## 🚀 Deploy to Netlify (Step by Step)

### Step 1: Push to GitHub
1. Create a new GitHub repo (e.g., `betterclimatezone-site`)
2. Upload ALL files from this folder to the repo root
3. Make sure `index.html` is at the root level (not inside a subfolder)

### Step 2: Connect to Netlify
1. Go to [app.netlify.com](https://app.netlify.com)
2. Click **"Add new site"** → **"Import an existing project"**
3. Select **GitHub** and authorize access
4. Choose your `betterclimatezone-site` repo
5. Build settings should auto-detect. If not:
   - **Build command:** (leave blank)
   - **Publish directory:** `.`
6. Click **"Deploy site"**

### Step 3: Set Up Custom Domain
1. In Netlify Dashboard → **Domain settings**
2. Click **"Add custom domain"**
3. Enter `betterclimatezone.com`
4. Follow DNS instructions (update nameservers at your domain registrar to point to Netlify)
5. Netlify will auto-provision a free SSL certificate

### Step 4: Enable Form Notifications
1. Go to **Site settings** → **Forms**
2. You should see `quote-request` listed after first deploy
3. Click **Form notifications** → **Add notification** → **Email notification**
4. Enter your email address to receive lead submissions

### Step 5: Verify Everything Works
- [ ] Homepage loads at your domain
- [ ] Favicon shows in browser tab
- [ ] All nav links scroll to correct sections
- [ ] Mobile hamburger menu opens/closes
- [ ] Phone number links trigger dialer on mobile
- [ ] Form submits successfully (test it!)
- [ ] 404 page shows for non-existent URLs

---

## 📁 File Structure

```
├── index.html          # Main website (all SEO, schema, styles included)
├── 404.html            # Custom 404 error page
├── sitemap.xml         # XML sitemap for search engines
├── robots.txt          # Crawler directives
├── manifest.json       # Web app manifest (PWA support)
├── netlify.toml        # Netlify build & header config
├── _headers            # Security headers (backup)
├── _redirects          # URL redirects (www → non-www)
├── favicon.ico         # Browser favicon
├── favicon-16x16.png   # 16px favicon
├── favicon-32x32.png   # 32px favicon
├── apple-touch-icon.png # iOS home screen icon (180px)
├── icon-192.png        # Android/PWA icon (192px)
├── icon-512.png        # Android/PWA icon (512px)
├── og-image.png        # Social media sharing image (1200x630)
└── README.md           # This file
```

---

## 🔍 SEO Features Included

- **Structured Data:** HVACBusiness, FAQPage, Service, and Review JSON-LD schemas
- **Meta Tags:** Optimized title, description, keywords, canonical URL
- **Open Graph:** Full OG tags + Twitter Card for social sharing
- **Sitemap:** XML sitemap auto-discoverable via robots.txt
- **Semantic HTML5:** Proper heading hierarchy (H1→H2→H3), ARIA labels, landmark roles
- **Mobile-First:** Responsive design, click-to-call links, touch-friendly targets
- **Core Web Vitals:** Single-page, minimal JS, no render-blocking resources, inline CSS
- **Security Headers:** CSP, X-Frame-Options, XSS Protection via netlify.toml

---

## 📋 Post-Launch Checklist

After deploying, complete these steps for maximum SEO impact:

1. **Submit Sitemap to Google Search Console**
   - Go to [search.google.com/search-console](https://search.google.com/search-console)
   - Add your property (betterclimatezone.com)
   - Go to Sitemaps → Submit `https://betterclimatezone.com/sitemap.xml`

2. **Submit to Bing Webmaster Tools**
   - Go to [bing.com/webmasters](https://www.bing.com/webmasters)
   - Add site and submit sitemap

3. **Test Structured Data**
   - Go to [Google Rich Results Test](https://search.google.com/test/rich-results)
   - Enter your URL and verify all schemas pass

4. **Test Page Speed**
   - Run [PageSpeed Insights](https://pagespeed.web.dev/)
   - Should score 90+ on mobile and desktop

5. **Google Business Profile**
   - Update your GBP website URL to your new domain
   - See the SEO Strategy document for full GBP optimization steps

---

## 📞 Contact

Better Climate Zone LLC
Gurnee, IL | Lake County
(224) 656-5843
betterclimatezone@icloud.com
