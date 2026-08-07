# Copacabana Co. — Official Website

Official company website for **Copacabana Co. (주식회사 코파카바나)**.

- **Live URL**: [copacabana.co.kr](https://copacabana.co.kr)
- **Deployed via**: Cloudflare Pages
- **Domain Registrar**: HostingKR

---

## Tech Stack

| Item | Detail |
|---|---|
| HTML | HTML5 |
| CSS | Vanilla CSS (custom, no framework) |
| JavaScript | Vanilla JS (minimal) |
| Font | Inter (Google Fonts — SIL OFL 1.1) |
| Deployment | Cloudflare Pages (static, no build step) |

---

## Project Structure

```
copacabana-homepage/
├── index.html          # Home
├── about.html          # About
├── service.html        # Service (Muselry)
├── contact.html        # Contact
├── _redirects          # Cloudflare Pages redirect rules
├── assets/
│   ├── css/
│   │   └── style.css   # Main stylesheet
│   ├── js/
│   │   └── main.js     # Nav toggle, scroll reveal, form handler
│   └── images/
│       └── favicon.svg # SVG favicon
└── README.md
```

---

## Cloudflare Pages Deployment

1. Go to [Cloudflare Pages](https://pages.cloudflare.com/)
2. Click **Create a project** → **Connect to Git**
3. Select this repository (`copacabana-homepage`)
4. **Build settings**:
   - Framework preset: `None`
   - Build command: *(leave empty)*
   - Build output directory: `/` (root)
5. Click **Save and Deploy**
6. Connect custom domain `copacabana.co.kr` in Pages → Custom domains

---

## DNS Settings (HostingKR + Cloudflare)

After adding the site to Cloudflare:

1. Copy the two Cloudflare nameservers shown in the dashboard
2. Log in to HostingKR → Domain management → Change nameservers
3. Replace existing nameservers with the Cloudflare ones
4. Wait for propagation (up to 24 hours)
5. In Cloudflare Pages → Custom domains → Add `copacabana.co.kr`

---

## Company

**Copacabana Co. (주식회사 코파카바나)**  
CEO: Woojin Chang  
Rm 305, 621 Hwarang-ro, Nowon-gu, Seoul, 01797, South Korea  
Email: ceo@copacabana.co.kr

---

## License

© 2026 Copacabana Co. All rights reserved.  
Font: [Inter](https://fonts.google.com/specimen/Inter) — SIL Open Font License 1.1
