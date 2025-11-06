# Dental Clinic Website

A responsive, bilingual single-page application built for my mother's dental practice in Málaga, Spain. This project demonstrates full-stack web development skills, real-world client collaboration, and user-centered design.

## 🎯 Project Overview

**Problem**: My mother needed a professional online presence to attract patients and streamline appointment bookings, but had no existing website.

**Solution**: Built a fully-featured, mobile-first website with bilingual support (Spanish/English), integrated booking system, and patient review showcase.

**Impact**: Created a production-ready website that serves as the clinic's primary digital presence.

## 🔧 Technical Stack

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Styling**: Tailwind CSS, Custom CSS variables for theming
- **APIs**: Google Maps API (clinic location), WhatsApp Business API (booking integration)
- **Data Management**: JSON-based content system for reviews, cases, and products
- **Deployment**: Static site hosting (Netlify/Vercel-ready)

## ✨ Key Features

### 1. Bilingual Interface
- Implemented client-side language switching between Spanish and English
- All content dynamically updates without page reload
- Locale persistence using browser localStorage

### 2. Dynamic Content Management
- Structured data architecture with JSON files for easy content updates
- 57 patient reviews with bilingual translations, avatars, and source links
- Portfolio of dental cases with filterable categories

### 3. Booking System Integration
- Custom form validation and WhatsApp API integration
- One-click appointment booking via WhatsApp with pre-filled message
- Embedded Google Maps with directions integration

### 4. Responsive Design
- Mobile-first approach tested across devices
- Custom CSS grid and flexbox layouts
- Optimized for accessibility (semantic HTML, ARIA labels)

### 5. Interactive Components
- Review carousel with navigation controls
- Tab-based navigation system
- Dynamic filtering for dental case portfolio

## 📁 Project Structure

```
├── index.html           # Main SPA
├── data/
│   ├── reviews.json    # 57 patient reviews (bilingual)
│   ├── cases.json      # Dental case studies
│   └── products.json   # Product recommendations
├── assets/
│   └── images/         # Optimized images and logos
└── documents/
    └── cv.pdf          # Professional credentials
```

## 🚀 Setup & Deployment

1. Clone the repository
2. Open `index.html` in a browser (no build process required)
3. For production: Deploy to any static hosting service

**Live Demo**: [Add your deployment URL here]

## 💡 What I Learned

- **Client Communication**: Gathered requirements and feedback from a real client (my mother), iterating based on her needs
- **Internationalization**: Implemented bilingual support without using heavy i18n libraries
- **API Integration**: Connected with external services (Google Maps, WhatsApp) for real business functionality
- **Performance Optimization**: Kept the entire site under 2MB with optimized images and efficient JavaScript
- **Accessibility**: Applied WCAG guidelines for semantic HTML and keyboard navigation

## 🛠️ Development Process

1. **Discovery**: Interviewed my mother to understand patient needs and business goals
2. **Design**: Created a clean, medical-grade design system inspired by modern healthcare sites
3. **Development**: Built iteratively, testing with real users (patients)
4. **Deployment**: Prepared for production hosting with proper SEO and meta tags

## 🎨 Design Decisions

- **Color Palette**: Blue tones for trust and professionalism (primary: #1E88E5)
- **Typography**: Playfair Display for elegance, Inter for readability
- **Layout**: Single-page app for simplicity and faster navigation
- **Mobile-First**: Málaga patients primarily browse on mobile devices

## 📊 Technical Highlights

- **Zero Dependencies**: No npm packages, no build system—just optimized vanilla code
- **Performance**: Fast load times with CDN-based libraries (Tailwind, Font Awesome)
- **Maintainability**: Separated data from presentation for easy content updates
- **Scalability**: JSON-based architecture allows easy expansion to CMS integration

## 🔮 Future Improvements

- Migrate to React for better component management
- Add backend with Node.js/Express for form submissions and email notifications
- Implement A/B testing for booking conversion optimization
- Add analytics dashboard for appointment tracking

---

**Built by**: Miguel Orti Vila  
**Context**: CS Sophomore Personal Project  
**Timeline**: Oct-Nov 2025
**Status**: Production-Ready
