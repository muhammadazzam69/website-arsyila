# ARSYILA TOURS - Professional Multi-Page Travel Website

A complete, production-ready multi-page travel website system for Karimunjawa Tour & Travel. Built with modern web standards and designed to be easily converted into a WordPress theme.

## 🌟 Features

### Complete User Flow
- ✅ **Homepage** → Package List → Package Detail → Booking → Payment
- ✅ Real navigation between all pages (no demo alerts)
- ✅ WhatsApp integration for direct customer contact
- ✅ Mobile-responsive design across all devices

### Pages Included
1. **index.html** - Homepage with hero, featured packages, testimonials
2. **packages.html** - Complete package listing
3. **package-detail-2d1n.html** - 2 Days 1 Night package details
4. **package-detail-3d2n.html** - 3 Days 2 Nights package details
5. **package-detail-honeymoon.html** - Honeymoon package details
6. **booking.html** - Comprehensive booking form with live summary
7. **payment.html** - Payment instructions with bank/e-wallet options

### Design System
- **Color Palette**: Ocean Blue, White, Light Gray, Sunset Orange
- **Typography**: Plus Jakarta Sans (headings), Inter (body)
- **Layout**: Modern, clean, generous white space
- **Animations**: Smooth, subtle, professional transitions

### Key Features
- 🎨 Premium, modern design
- 📱 Fully responsive (mobile-first)
- 🚀 Fast loading times
- ♿ Accessible (WCAG 2.1 compliant)
- 🔍 SEO-friendly structure
- 💼 Business-ready (no placeholder alerts)
- 📧 Real WhatsApp integration
- 💳 Complete booking & payment flow

## 📁 Project Structure

```
/workspace/
├── index.html                      # Homepage
├── packages.html                   # Package listing page
├── package-detail-2d1n.html        # 2D1N package detail
├── package-detail-3d2n.html        # 3D2N package detail
├── package-detail-honeymoon.html    # Honeymoon package detail
├── booking.html                    # Booking form
├── payment.html                    # Payment page
├── styles.css                      # Complete CSS system
├── README.md                       # This file
├── WORDPRESS-THEME-GUIDE.md        # WordPress conversion guide
└── todo.md                         # Development tracking
```

## 🚀 Quick Start

### Option 1: Direct File Opening
1. Download all files
2. Open `index.html` in your browser
3. Navigate through the website

### Option 2: Local Server (Python)
```bash
# Navigate to project directory
cd /workspace

# Start Python HTTP server
python3 -m http.server 8050

# Open browser
# Go to: http://localhost:8050
```

### Option 3: VSCode Live Server
1. Install [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.liveserver) extension
2. Right-click on `index.html`
3. Select "Open with Live Server"

## 📄 Page Descriptions

### 1. Homepage (index.html)
**Sections:**
- Hero section with ocean imagery and CTAs
- Experience highlights (Snorkeling, Island Hopping, Sunset, Honeymoon)
- Featured tour packages (3 best sellers)
- Trust section (Why Arsyila Tours)
- Customer testimonials
- Final CTA section
- Complete footer

**Key Features:**
- Real navigation to all pages
- Package cards link to detail pages
- Floating WhatsApp button

### 2. Package List (packages.html)
**Features:**
- Grid layout with 6 package options
- Each package shows: name, duration, price, highlights
- Real links to detail pages
- Filter-ready structure
- Responsive grid (3-2-1 columns)

### 3. Package Detail Pages
**Each Includes:**
- Hero section with package image
- Package info grid (duration, pax, hotel, activities)
- Day-by-day itinerary
- Included/excluded facilities
- Terms & conditions
- Booking button (pre-fills form)
- WhatsApp chat integration
- Related packages section

**Packages Available:**
- 2 Days 1 Night - Rp 850.000/person
- 3 Days 2 Nights - Rp 1.250.000/person
- Honeymoon - Rp 2.500.000/couple

### 4. Booking Page (booking.html)
**Form Fields:**
- Personal information (name, phone, email)
- Package selection (dropdown)
- Travel date picker
- Number of participants
- Additional notes

**Features:**
- Live order summary (updates automatically)
- Form validation
- WhatsApp booking option
- Price calculation based on selection
- Data stored in sessionStorage for payment page

### 5. Payment Page (payment.html)
**Features:**
- Order summary from booking data
- Payment method selection (Bank Transfer / E-Wallet)
- Copy-to-clipboard functionality
- Payment instructions
- WhatsApp confirmation
- Multiple bank accounts supported
- E-wallet options (GoPay, OVO, Dana, ShopeePay)

## 🎨 Customization

### Changing Colors
Edit CSS variables in `styles.css`:
```css
:root {
  --color-ocean-blue: #0a4d68;
  --color-sunset-orange: #f97316;
  /* More colors... */
}
```

### Updating Images
Replace image URLs in HTML files:
```html
<!-- Current -->
<img src="https://images.unsplash.com/photo-..." alt="Description">

<!-- Your own -->
<img src="assets/images/your-image.jpg" alt="Description">
```

### Modifying Content
All text content is editable in HTML files. Look for:
- Headings: `<h1>`, `<h2>`, etc.
- Paragraphs: `<p>` tags
- Lists: `<ul>`, `<li>` tags
- Package details in each package detail page

## 📱 Responsive Design

The website is fully responsive with breakpoints for:
- **Desktop**: > 1024px
- **Tablet**: 768px - 1024px
- **Mobile**: < 768px

All components adapt automatically to screen size.

## 🔧 WordPress Theme Conversion

Complete guide available in `WORDPRESS-THEME-GUIDE.md`:

**Conversion Includes:**
- Custom Post Type for "Packages"
- ACF fields for package details, itinerary, facilities
- Template files for all pages
- Navigation menus
- Shortcodes for package grids
- Complete theme functions

**Key Features for WordPress:**
- Editable content via WordPress dashboard
- Package management with custom fields
- Dynamic package listings
- Easy booking form integration
- Media library for images

## 📊 Technical Details

### HTML5 Semantic Structure
- Proper use of semantic tags (`header`, `nav`, `main`, `section`, `footer`)
- Accessibility attributes (ARIA labels, alt text)
- SEO meta tags included

### CSS Architecture
- CSS Variables for easy theming
- BEM-like naming convention
- Mobile-first responsive design
- Smooth animations and transitions
- No external CSS frameworks (pure CSS)

### JavaScript Features
- Navigation scroll effects
- Smooth scroll for anchor links
- Mobile menu toggle
- Form validation
- Live price calculation
- SessionStorage for booking data
- Copy-to-clipboard functionality

## 🌐 Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📞 Contact & Support

### WhatsApp Integration
Floating WhatsApp button links to:
```
https://wa.me/6281234567890
```

Replace with your actual WhatsApp business number.

### Email Contact
Update email addresses in:
- Footer section
- Contact forms
- Booking confirmation

## 📦 Deployment

### Static Hosting (Free)
- **Netlify**: Drag & drop folder
- **Vercel**: Install CLI and run `vercel`
- **GitHub Pages**: Push to GitHub and enable Pages

### Custom Domain
1. Choose hosting provider
2. Point DNS to hosting
3. Upload files
4. Configure SSL certificate

### WordPress
Follow the complete conversion guide in `WORDPRESS-THEME-GUIDE.md`

## 🔒 Security Notes

- No sensitive data stored on client
- All booking data stored in sessionStorage (cleared on browser close)
- WhatsApp links open in new tab
- No external tracking or analytics included

## 📝 License

This project is created for ARSYILA TOURS. All rights reserved.

## 🙏 Credits

### Images
All placeholder images from Unsplash:
- https://unsplash.com

### Fonts
- Plus Jakarta Sans: Google Fonts
- Inter: Google Fonts

### Icons
SVG icons embedded directly in HTML

---

## 📚 Additional Documentation

- **WORDPRESS-THEME-GUIDE.md** - Complete WordPress conversion guide
- **styles.css** - Well-commented CSS with design tokens

## 🎯 Next Steps

1. **Customize Content**: Update all text to match your business
2. **Replace Images**: Add your own Karimunjawa photos
3. **Update Contact Info**: Change WhatsApp, email, phone numbers
4. **Adjust Pricing**: Modify package prices as needed
5. **Test Flow**: Go through complete booking process
6. **Deploy**: Choose hosting and deploy website
7. **WordPress Conversion** (optional): Follow conversion guide

---

**Created with ❤️ for ARSYILA TOURS**

For questions or support, refer to the WordPress Theme Conversion Guide or contact the development team.