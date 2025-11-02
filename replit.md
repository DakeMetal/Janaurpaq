# JANA URPAQ - Travel Agency Website

## Overview
JANA URPAQ is a modern, multi-page travel agency website offering flight tickets, beach holidays, mountain tours, hotel bookings, and guided excursions.

**Slogan**: "See more. Feel more. Be JANA URPAQ"

## Project Structure
```
/
├── index.html          # Home page with hero, services preview, testimonials
├── services.html       # All services with detailed descriptions
├── destinations.html   # Popular destinations with booking options
├── about.html          # Company information, mission, vision, stats
├── contact.html        # Contact form and contact information
├── style.css           # Complete CSS with animations and responsive design
├── script.js           # Interactive JavaScript (forms, animations, navigation)
├── img/                # Image directory (replace with your own photos)
│   ├── logo.png        # JANA URPAQ logo (sun and waves)
│   ├── hero.jpg        # Hero section background
│   ├── destination1.jpg # Tropical beach destination
│   ├── destination2.jpg # Mountain destination
│   ├── destination3.jpg # City exploration destination
│   ├── destination4.jpg # Cultural heritage destination
│   └── about.jpg       # About section image
└── replit.md           # This file
```

## Features

### Pages
1. **Home (index.html)** - Hero section, services preview, testimonials, CTA
2. **Services (services.html)** - All 6 services with detailed descriptions
3. **Destinations (destinations.html)** - 4 destinations with hover effects and "Why Choose Us" section
4. **About (about.html)** - Company story, mission/vision, statistics
5. **Contact (contact.html)** - Working contact form, agent information, office hours

### Interactive Elements
- **Multi-page navigation** - Click navigation links to visit different pages
- **Working contact form** - Collects visitor information and displays success message
- **Mobile-responsive menu** - Hamburger menu on small screens
- **Smooth animations** - Fade-in effects on scroll
- **Hover effects** - Interactive cards and buttons
- **Active page highlighting** - Navigation shows current page in yellow
- **Testimonials** - Customer reviews with star ratings
- **WhatsApp integration** - Direct links to contact via WhatsApp

### Design
- **Colors**: Dark blue (#083c5f), Golden yellow (#FFD700), White
- **Typography**: Modern, clean fonts (Segoe UI)
- **Layout**: Fully responsive (mobile, tablet, desktop)
- **Icons**: Font Awesome icons for services and features

## Contact Information
- **Kudaibek Ramazan**: +7 775 784 6785
- **Khemedenov Daulet**: +7 702 645 3655
- **Instagram**: [@janaurpaq.kz](https://instagram.com/janaurpaq.kz)

## How to Replace Images
All images in the `/img/` folder are placeholders. To use your own photos:

1. Prepare your images:
   - `logo.png` - Your company logo (current logo is user's actual logo)
   - `hero.jpg` - Hero background (1920x1080px recommended)
   - `destination1-4.jpg` - Destination photos (1200x800px recommended)
   - `about.jpg` - About section image (800x600px recommended)

2. Replace files in the `/img/` folder with your images (keep the same filenames)

3. Refresh the website to see your images

## Contact Form
The contact form on the contact page:
- Collects: Name, Email, Phone, Service Interest, Destination, Message
- Shows success message when submitted
- Form data is logged to console (ready for backend integration)
- Optional WhatsApp integration available in script.js

## Running the Project
The website runs on a Python HTTP server on port 5000. The workflow starts automatically.

## Technologies Used
- HTML5 (Multi-page structure)
- CSS3 (Flexbox, Grid, Animations, Responsive Design)
- Vanilla JavaScript (Form handling, scroll effects, mobile menu)
- Font Awesome Icons (via CDN)

## Recent Changes
- November 2, 2025: Major upgrade to multi-page website
  - Converted from single-page to multi-page structure
  - Added separate pages for Services, Destinations, About, and Contact
  - Implemented working contact form with validation
  - Added testimonials section with customer reviews
  - Added "Why Choose Us" features section
  - Added Mission/Vision/Values cards
  - Added statistics section
  - Integrated user's actual JANA URPAQ logo
  - Enhanced responsive design for all new pages
  - Added WhatsApp contact links
  - Added office hours information
