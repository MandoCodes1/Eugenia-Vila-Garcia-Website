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
- **Color Palette**: Australian Open & Wellness (sophisticated blue #1E88E5 and elegant accents)
- **Responsive Design**: Mobile-first approach, optimized for all devices
- **Clean Layout**: Medical-grade professional styling throughout

### Key Sections

#### 🏠 Home
- Full-body professional photo in hero section
- Audience-specific call-to-action buttons
- Quick stats: GDC Registered, 30+ Years Experience, 5-Star Rated
- **English**: Get In Touch, View CV, View Cases + Email, Phone icons
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
- **Featured Carousel**: 12 handpicked passionate reviews on home page
- **Curated Order**: Isabel, Nuria, Emma, Teresa, Gerson, Giuseppe, Customer, J Ainsworth, Santi, Laura, S F, Zoe King
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
- **Spanish Version**: Spanish Phone (+34 679975580), WhatsApp booking
- GDC Registration: 287705 (with verification link)
- Current Location: Dental Art Implant Clinics, London
- Professional Memberships: GDC, RCSI, Colegio Oficial de Dentistas de Málaga
- Comprehensive professional summary
- **Footer Social**: LinkedIn profile link (English version)

#### 📄 CV Tab
- Embedded PDF viewer for inline resume viewing
- Download CV button
- Fallback for browsers without PDF support
- Quick stats display

### Spanish Version Extras
- **Google Maps Integration**: Clinic location (Clinica Dental Dra. Eugenia Vila, Málaga, Spain)
- **WhatsApp Button**: Direct booking via WhatsApp (+34 679975580)
- **"Cómo Llegar" Button**: Google Maps directions (styled in Maps blue #4285F4)

## 📁 Directory Structure

```
/
├── index.html              # Main single-page application (2296 lines)
├── README.md              # This file
├── .gitignore             # Git ignore rules
├── assets/
│   └── images/
│       ├── full_body.png  # Full-body professional photo (hero section)
│       ├── profile.png    # Profile photo (alternative/fallback)
│       └── logo.png       # Logo image
├── documents/
│   └── cv.pdf            # Curriculum Vitae (PDF format)
└── data/
    ├── reviews.json      # 57 patient reviews with avatars and translations
    ├── reviews.csv       # Reviews data in CSV format
    ├── cases.json        # Dental cases data
    └── products.json     # Product recommendations data
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
/* Australian Open & Wellness Color Palette */
--primary-blue: #1E88E5          /* Primary actions, links, accents */
--primary-blue-light: #42A5F5    /* Hover states, highlights */
--primary-blue-dark: #1565C0     /* Footer, headers, emphasis */
--secondary-blue: #A0D3F1        /* Secondary accents */
--secondary-blue-light: #EBF8FF  /* Backgrounds, subtle highlights */
--gold-accent: #d4af37           /* Awards, achievements */
```

### Typography
- **Headings**: Playfair Display (serif, elegant)
- **Body**: Inter (sans-serif, clean and modern)

## 🚀 Deployment

This is a static website that can be deployed to:

### Recommended Hosting Platforms
- **GitHub Pages** (Free, simple)
- **Netlify** (Free tier, custom domains)
- **Vercel** (Free tier, excellent performance)
- **Traditional Web Hosting** (cPanel, FTP upload)

### Deployment Steps
1. Upload all files to your hosting provider
2. Set `index.html` as the root file
3. Configure custom domain (optional)
4. Enable HTTPS (usually automatic)

## 📝 Content Updates

### To Update Reviews
1. Edit `data/reviews.json` with new patient testimonials
2. Update the `reviewsData` array in `index.html` for embedded reviews
3. Include: name, text_en, text_es, rating, source, avatar, link, date, clinic

### To Update Review Order
The first 12 reviews are curated in this order:
1. Isabel, 2. Nuria Salido Iniesta, 3. Emma, 4. Teresa Vez luque, 5. Gerson Suaznabar, 6. Giuseppe Tinaglia, 7. customer, 8. J Ainsworth, 9. Santi Barreche Pelaez, 10. Laura Scott, 11. S F, 12. Zoe King

### To Update CV
Replace `documents/cv.pdf` with the updated version

### To Update Photos
- **Hero Image**: Replace `assets/images/full_body.png` (recommended: professional full-body or upper-body photo)
- **Alternative**: Replace `assets/images/profile.png` (recommended: 800x800px headshot)
- **Logo**: Replace `assets/images/logo.png`

### To Update Contact Information
Edit the Contact tab section in `index.html`

### To Update Dental Cases
Edit `data/cases.json` or the Dental Cases section in `index.html`

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
- **Patient Reviews**: 57 (12 featured on home page)
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
- **Spain Clinic**: Clinica Dental Dra. Eugenia Vila, Málaga, Spain
- **UK Clinics**: Dental Art Implant Clinics (Balham & East Finchley), London

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
**Last Updated**: November 2025  
**Maintained by**: Miguel Orti Vila (Developer)
