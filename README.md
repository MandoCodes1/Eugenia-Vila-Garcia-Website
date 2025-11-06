# Dra. Eugenia Vila Garcia - Clínica Dental en Málaga

A professional bilingual dental clinic website showcasing dental expertise, patient testimonials, and comprehensive dental services. Designed primarily for Spanish patients in Málaga with English translation support for international patients.

## 🌟 Features

### Bilingual Support
- **Default Language**: Spanish (for local Málaga patients)
- **Language Toggle**: 🇪🇸 Spain / 🇬🇧 UK flag buttons
- **Full Translation**: All content available in both Spanish and English
- **Patient-Focused**: Emphasis on appointment booking and patient care

### Professional Design
- **Color Palette**: Australian Open & Wellness (sophisticated blue #1E88E5 and elegant accents)
- **Responsive Design**: Mobile-first approach, optimized for all devices
- **Clean Layout**: Medical-grade professional styling throughout
- **Modern UI**: Intuitive navigation and user-friendly interface

### Key Sections

#### 🏠 Home
- Full-body professional photo in hero section
- Patient-focused call-to-action buttons (View Cases, Reviews)
- Quick stats: 30+ Years Experience, 5-Star Rated
- WhatsApp and Google Maps integration
- **Appointment Booking Form**: Comprehensive contact form at bottom of home page
- Featured patient reviews carousel
- Areas of expertise showcase

#### 👤 About
- Comprehensive professional biography
- Qualifications & Experience
- Career highlights and specializations
- Languages: English (Fluent), Spanish (Native)
- Professional achievements and awards

#### 📋 Dental Cases Portfolio
- 6 sample cases with before/after placeholders
- Filter by treatment type: All, Invisalign, Bonding, Implants, Whitening, Veneers
- Professional case descriptions
- Treatment details and outcomes

#### ⭐ Reviews (57 Total)
- **Featured Carousel**: 12 handpicked passionate reviews on home page
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
- **Patient-Focused Contact Information**
- Phone: +34 679 97 55 80
- WhatsApp booking integration
- Email: eugeniavila63@gmail.com
- Clinic Location: Av. Juan Sebastián Elcano, 191 (2ª planta), 29017 Málaga, España
- Professional Memberships: RCSI, Colegio Oficial de Dentistas de Málaga
- Comprehensive professional summary with appointment booking CTA

#### 📅 Appointment Booking (New!)
- **Two-Column Layout**: Contact information + Booking form
- **Contact Details**: Address, Phone, Email, Hours, Social Media
- **Booking Form Fields**:
  - Full Name
  - Email
  - Phone
  - Treatment of Interest (dropdown with multiple options)
  - Message (textarea)
  - Privacy policy acceptance checkbox
- **WhatsApp Integration**: Form submits directly to WhatsApp
- **Operating Hours**: 
  - Monday to Friday: 9:00 - 20:00
  - Saturday: 10:00 - 14:00

### Patient Booking Features
- **Google Maps Integration**: Embedded map showing clinic location
- **WhatsApp Button**: Direct booking via WhatsApp (+34 679 97 55 80)
- **"Cómo Llegar" Button**: Google Maps directions (styled in Maps blue #4285F4)
- **Social Media Links**: Facebook, Instagram, WhatsApp, LinkedIn

## 📁 Directory Structure

```
/
├── index.html              # Main single-page application
├── README.md              # This file
├── .gitignore             # Git ignore rules
├── assets/
│   └── images/
│       ├── full_body.png  # Full-body professional photo (hero section)
│       ├── profile.png    # Profile photo (alternative/fallback)
│       ├── logo.png       # Logo image
│       └── logo2.png      # Alternative logo
├── documents/
│   └── cv.pdf            # Curriculum Vitae (for reference, not linked)
├── data/
│   ├── reviews.json      # 57 patient reviews with avatars and translations
│   ├── reviews.csv       # Reviews data in CSV format
│   ├── cases.json        # Dental cases data
│   └── products.json     # Product recommendations data
└── _site/                # Build artifacts (ignored by git)
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Custom styling with CSS variables
- **Tailwind CSS**: Utility-first CSS framework (via CDN)
- **Font Awesome 6**: Professional iconography
- **Vanilla JavaScript**: Tab navigation, language switching, review carousel, form handling
- **Google Fonts**: Playfair Display (headings), Inter (body text)
- **Google Maps API**: Embedded map for clinic location

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
- **Netlify** (Recommended - Free tier, custom domains, automatic HTTPS)
- **Vercel** (Free tier, excellent performance)
- **GitHub Pages** (Free, simple)
- **Traditional Web Hosting** (cPanel, FTP upload)

### Deployment Steps
1. Upload all files to your hosting provider
2. Set `index.html` as the root file
3. Configure custom domain (optional)
4. Enable HTTPS (usually automatic)
5. Update social media links to your actual profiles

## 📝 Content Updates

### To Update Contact Information
1. Update phone number in multiple locations:
   - Hero section WhatsApp links
   - Contact tab
   - Footer
   - Appointment form submission handler (JavaScript)
2. Update email address: `eugeniavila63@gmail.com`
3. Update clinic address if relocated

### To Update Reviews
1. Edit `data/reviews.json` with new patient testimonials
2. Update the `reviewsData` array in `index.html` for embedded reviews
3. Include: name, text_en, text_es, rating, source, avatar, link, date, clinic

### To Update Photos
- **Hero Image**: Replace `assets/images/full_body.png` (recommended: professional full-body or upper-body photo)
- **Alternative**: Replace `assets/images/profile.png` (recommended: 800x800px headshot)
- **Logo**: Replace `assets/images/logo.png` and `logo2.png`

### To Update Dental Cases
Edit `data/cases.json` or the Dental Cases section in `index.html`

### To Update Social Media Links
Update social media URLs in:
- Appointment booking section (home page)
- Footer section

### To Update Operating Hours
Edit the hours in the appointment booking section:
- Current: Mon-Fri 9:00-20:00, Sat 10:00-14:00

## 🎯 Target Audience

### Primary: Spanish Patients (🇪🇸)
- **Goal**: Patient Bookings and Trust Building
- **Audience**: Local patients in Málaga, Spain and surrounding areas
- **Focus**: Easy appointment booking, WhatsApp integration, patient testimonials
- **Actions**: Book appointment, View cases, Read reviews, Contact via WhatsApp

### Secondary: International Patients (🇬🇧)
- **Goal**: Attract international patients and expats
- **Audience**: English-speaking patients in Spain or visiting Málaga
- **Focus**: Professional credentials, bilingual service, comprehensive care
- **Actions**: Book appointment, View cases, Contact for consultation

## 📊 Website Statistics

- **Patient Reviews**: 57 (12 featured on home page)
- **Dental Cases**: 6 sample cases
- **Product Recommendations**: 6 items
- **Languages**: 2 (Spanish primary, English secondary)
- **Tabs/Sections**: 6 (Home, About, Dental Cases, Reviews, Products, Contact)
- **Key Features**: Appointment booking form, WhatsApp integration, Google Maps

## 📞 Contact Information

**Dra. Eugenia Vila Garcia**
- **Clinic**: Clínica Dental Dra. Eugenia Vila
- **Address**: Av. Juan Sebastián Elcano, 191 (2ª planta), 29017 Málaga, España
- **Phone**: +34 679 97 55 80
- **WhatsApp**: +34 679 97 55 80
- **Email**: eugeniavila63@gmail.com
- **Hours**: 
  - Monday to Friday: 9:00 - 20:00
  - Saturday: 10:00 - 14:00

## 🏆 Achievements

- **Dentist of the Year 2024** - Dental Art Implant Clinics, London
- **30+ Years** of clinical experience
- **20,000+** patients treated
- **5/5** average patient rating
- **Registered** with the Colegio Oficial de Dentistas de Málaga
- **Bilingual** practitioner (English/Spanish)
- Member of Colegio Oficial de Dentistas de Málaga since 1994

## 🔧 Maintenance

### Regular Updates
- Keep patient reviews current
- Update operating hours if they change
- Refresh dental cases with new examples
- Keep social media links active
- Monitor and respond to WhatsApp inquiries

### Technical Maintenance
- Test appointment form regularly
- Check WhatsApp integration
- Verify Google Maps embed is working
- Test language switching functionality
- Ensure mobile responsiveness

## 📄 License

This website is the professional portfolio of Dra. Eugenia Vila Garcia. All rights reserved.

---

**Website Version**: 2.0 (Spanish-Focused)  
**Last Updated**: November 2025  
**Maintained by**: Miguel Orti Vila (Developer)
