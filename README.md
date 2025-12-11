# tripleS Fan Sites Directory 🎵

A comprehensive directory of Twitter fan accounts for all 24 tripleS members.

## 🌟 Features

- **24 Members** - Complete lineup from S1 to S24
- **88 Twitter Fan Accounts** - Curated list of active fansites
- **Beautiful UI** - Colorful circular icons with gradients
- **Search Function** - Find members quickly
- **Direct Links** - One-click access to Twitter accounts
- **Mobile Responsive** - Works perfectly on all devices

## 📱 Live Demo

Visit: `https://yourusername.github.io/triples-fansites`

## 🚀 Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/triples-fansites.git
   cd triples-fansites
   ```

2. **Test locally**
   - Open `index.html` in your browser
   - Or use a local server:
     ```bash
     python -m http.server 8000
     ```

3. **Deploy to GitHub Pages**
   - Push to GitHub
   - Go to repository Settings → Pages
   - Select `main` branch → Save
   - Your site will be live!

## 📁 Project Structure

```
triples-fansites/
│
├── index.html       # Main page with 24 member icons
├── fansites.html    # Individual member fansite listings
├── styles.css       # All styling and animations
├── script.js        # Fan site data and functionality
└── README.md        # This file
```

## 👥 All 24 Members

| Member | English Name | Fansites | Member | English Name | Fansites |
|--------|--------------|----------|--------|--------------|----------|
| S1 | Yoon Seoyeon | 10 | S13 | Nien | 3 |
| S2 | Jeong Hyerin | 1 | S14 | Park Sohyun | 4 |
| S3 | Lee Jiwoo | 3 | S15 | Xinyu | 4 |
| S4 | Kim Chaeyeon | 2 | S16 | Mayu | 3 |
| S5 | Kim Yooyeon | 4 | S17 | Lynn | 6 |
| S6 | Kim Soomin | 2 | S18 | Joobin | 1 |
| S7 | Kim Nakyoung | 6 | S19 | Jeong Hayeon | 3 |
| S8 | Gong Yubin | 4 | S20 | Park Shion | 5 |
| S9 | Kaede | 4 | S21 | Kim Chaewon | 4 |
| S10 | Seo Dahyun | 4 | S22 | Sullin | 2 |
| S11 | Kotone | 4 | S23 | Seoa | 2 |
| S12 | Kwak Yeonji | 3 | S24 | Ji Seoyeon | 4 |

**Total: 88 Twitter Fan Accounts**

## 🎨 Customization

### Add New Fan Sites

Edit `script.js` and add accounts to the respective member:

```javascript
yooyeon: {
    name: "Kim Yooyeon",
    initials: "KYY",
    gradient: "linear-gradient(135deg, #FF69B4, #FF1493)",
    fansites: [
        { name: "New Fansite", handle: "@NewHandle" },
        // Add more here
    ]
}
```

### Change Colors

Modify gradients in `script.js` or colors in `styles.css`

### Update Member Info

Edit the `fansitesData` object in `script.js`

## 🔗 Connect Custom Domain

### For wav.haus:

1. Deploy to GitHub Pages first
2. In repository Settings → Pages → Custom domain
3. Enter: `tpsxfansites.wav.haus`
4. In wav.haus panel, select "GitHub Pages"
5. Follow DNS configuration

### For other domains:

1. Add CNAME record pointing to: `yourusername.github.io`
2. Add custom domain in GitHub Pages settings
3. Wait for DNS propagation (up to 24 hours)

## 💻 Technology Stack

- **HTML5** - Structure
- **CSS3** - Styling with gradients and animations
- **Vanilla JavaScript** - No frameworks needed
- **GitHub Pages** - Free hosting

## 📄 License

Free to use for personal fan sites. Not officially affiliated with MODHAUS or tripleS.

## 🙏 Credits

- tripleS members and MODHAUS
- Fan site operators for their dedication
- tripleS fan community

## 📧 Contact

For updates or corrections, please open an issue on GitHub.

---

Made with 💜 for tripleS fans worldwide

**Last Updated:** December 2025
