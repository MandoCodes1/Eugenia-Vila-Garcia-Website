# Dr. Eugenia Vila Garcia - Professional Dental Portfolio

A professional bilingual portfolio website showcasing dental expertise, patient testimonials, and career accomplishments. Designed to serve two distinct audiences: UK recruiters (English) and Málaga patients (Spanish).

## 🌟 Features

### Bilingual Support
- **Default Language**: Spanish (for local Málaga patients)
- **Language Toggle**: 🇪🇸 Spain / 🇬🇧 UK flag buttons
- **Audience-Specific Content**:
  - **English Version**: Professional recruitment focus with CV, LinkedIn, and contact details
  - **Spanish Version**: Patient booking focus with WhatsApp and Google Maps integration

### Professional Design
- **Color Palette**: Wimbledon & Wellness (sophisticated green #1A535C and elegant plum #5A5480)
- **Responsive Design**: Mobile-first approach, optimized for all devices
- **Clean Layout**: Medical-grade professional styling throughout

### Key Sections

#### 🏠 Home
- Full-body professional photo in hero section
- Audience-specific call-to-action buttons
- Quick stats: GDC Registered, 30+ Years Experience, 5-Star Rated
- **English**: Get In Touch, View CV, View Cases + Email, LinkedIn, Phone icons
- **Spanish**: Casos, Reseñas + WhatsApp, Google Maps icons

#### 👤 About
- Comprehensive professional biography
- Qualifications & Experience with GDC verification
- Career highlights and specializations
- Languages: English (Fluent), Spanish (Native)

#### 📋 Dental Cases Portfolio
- 6 sample cases with before/after placeholders
- Filter by treatment type: All, Invisalign, Bonding, Implants, Whitening, Veneers
- Professional case descriptions
- Location tags (London, Manchester, Birmingham)

#### ⭐ Reviews (57 Total)
- **Featured Carousel**: 14 handpicked passionate reviews on home page
- **Full Reviews Tab**: All 57 patient testimonials
- **Two Display Styles**: Dr. Kalia (compact) and Dr. Martin (detailed) layouts
- **Bilingual Reviews**: English and Spanish translations
- **Avatar Integration**: Real profile pictures from Google/Trustpilot
- **Star Ratings**: 5-star rating system with source badges
- **Direct Links**: Click through to original review sources

#### 🛍️ Recommended Products
- 6 curated dental product recommendations
- Amazon Associates integration ready
- Product features: Electric Toothbrush, Toothpaste, Water Flosser, Interdental Brushes, Mouthwash, Tongue Scraper
- Professional descriptions and pricing

#### 📞 Contact
- **English Version**: Email (eugeniavila63@gmail.com), LinkedIn, UK Phone (+44 7309281723)
- **Spanish Version**: Spanish Phone (+34 679975580)
- GDC Registration: 287705 (with verification link)
- Current Location: Dental Art Implant Clinics, London
- Professional Memberships: GDC, RCSI, Colegio Oficial de Dentistas de Málaga
- Comprehensive professional summary

#### 📄 CV Tab
- Embedded PDF viewer for inline resume viewing
- Download CV button
- Fallback for browsers without PDF support
- Quick stats display

### Spanish Version Extras
- **Google Maps Integration**: Clinic location (Av. Juan Sebastián Elcano, 191, Málaga-Este, 29017 Málaga, Spain)
- **WhatsApp Button**: Direct booking via WhatsApp (+34 679975580)
- **"Cómo Llegar" Button**: Google Maps directions (styled in Maps blue #4285F4)

## 📁 Directory Structure

```
_site/
├── index.html              # Main single-page application (2296 lines)
├── README.md              # This file
├── .gitignore             # Git ignore rules
├── assets/
│   └── images/
│       ├── full_body.png  # Full-body professional photo (hero section)
│       └── profile.png    # Profile photo (alternative/fallback)
├── documents/
│   └── cv.pdf            # Curriculum Vitae (PDF format)
└── data/
    └── reviews.csv       # 57 patient reviews with avatars and translations
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Custom styling with CSS variables
- **Tailwind CSS**: Utility-first CSS framework (via CDN)
- **Font Awesome 6**: Professional iconography
- **Vanilla JavaScript**: Tab navigation, language switching, review carousel
- **Google Fonts**: Playfair Display (headings), Inter (body text)

## 🎨 Design System

### Color Palette
```css
--wimbledon-green: #1A535C     /* Primary actions, links, accents */
--wimbledon-green-light: #2a6d78  /* Hover states */
--elegant-plum: #5A5480        /* Secondary actions */
--elegant-plum-light: #6a6490  /* Hover states */
--gold-accent: #C5A572         /* Awards, achievements */
```

### Typography
- **Headings**: Playfair Display (serif, elegant)
- **Body**: Inter (sans-serif, clean and modern)

## 🚀 Deployment

This is a static website that can be deployed to:

### Recommended Platforms
1. **Cloudflare Pages** ⭐ (recommended)
   - Fast global CDN
   - Free SSL certificate
   - Automatic deployments from GitHub
   - Zero configuration

2. **GitHub Pages**
   - Free hosting
   - Custom domain support
   - Easy setup with repository

3. **Netlify**
   - Continuous deployment
   - Form handling
   - Serverless functions support

4. **Vercel**
   - Optimized for performance
   - Preview deployments
   - Analytics included

### Deployment Steps
1. Upload the entire `_site/` directory contents to your hosting provider
2. Set `index.html` as the root file
3. Configure custom domain (optional)
4. Enable HTTPS (usually automatic)

## 📝 Content Updates

### To Update Reviews
1. Edit `data/reviews.csv` with new patient testimonials
2. Reviews are embedded in HTML (manual update required in `reviewsData` array)
3. Include: name, text (EN/ES), rating, source, avatar URL, origin link

### To Update CV
Replace `documents/cv.pdf` with the updated version

### To Update Photos
- **Hero Image**: Replace `assets/images/full_body.png` (recommended: professional full-body or upper-body photo)
- **Alternative**: Replace `assets/images/profile.png` (recommended: 800x800px headshot)

### To Update Contact Information
Edit the Contact tab section in `index.html` (lines ~1205-1410)

### To Update Dental Cases
Edit the Dental Cases section in `index.html` (lines ~637-924)

## 👥 Target Audiences

### English Version (🇬🇧)
- **Goal**: Professional Credibility
- **Audience**: Recruiters, clinic owners, professional colleagues in the UK
- **Focus**: Showcase qualifications, experience, GDC registration, CV
- **Actions**: Email, LinkedIn, Phone, View CV

### Spanish Version (🇪🇸)
- **Goal**: Patient Bookings
- **Audience**: Local patients in Málaga, Spain
- **Focus**: Build trust immediately, easy appointment booking
- **Actions**: WhatsApp booking, Google Maps directions, View cases

## 📊 Website Statistics

- **Total Lines of Code**: 2,296
- **Patient Reviews**: 57 (14 featured on home page)
- **Dental Cases**: 6 sample cases
- **Product Recommendations**: 6 items
- **Languages**: 2 (English, Spanish)
- **Tabs/Sections**: 7 (Home, About, Dental Cases, Reviews, Products, Contact, CV)

## 📞 Contact Information

**Dr. Eugenia Vila Garcia**
- **GDC Registration**: 287705 ([Verify](https://olr.gdc-uk.org/SearchRegister/SearchResult?RegistrationNumber=287705))
- **Email**: eugeniavila63@gmail.com
- **LinkedIn**: [linkedin.com/in/eugenia-vila-garcia](https://www.linkedin.com/in/eugenia-vila-garcia/)
- **UK Phone**: +44 7309 281723
- **Spain Phone**: +34 679 975 580
- **Clinic Address**: Av. Juan Sebastián Elcano, 191, Málaga-Este, 29017 Málaga, Spain

## 🏆 Achievements

- **Dentist of the Year 2024** - Dental Art Implant Clinics, London
- **30+ Years** of clinical experience
- **20,000+** patients treated
- **5/5** average patient rating
- **GDC Registered** in the UK
- **Bilingual** practitioner (English/Spanish)

## 📄 License

This website is the professional portfolio of Dr. Eugenia Vila Garcia. All rights reserved.

---

**Website Version**: 1.0  
**Last Updated**: October 2025  
**Maintained by**: Miguel (Developer)

