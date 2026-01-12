# Stairs and Tread Co

Website for Stairs and Tread Co - Custom staircases and treads specialist based in Melbourne, VIC.

**Live Site:** https://stairs-and-tread-co.vercel.app

## Project Setup

- **Hosting**: Vercel
- **Repository**: https://github.com/seammedia/stairs-and-tread-co
- **Tech Stack**: HTML, CSS, JavaScript (Vanilla)
- **Fonts**: Poppins (Google Fonts)

## Site Structure

### Pages/Sections
1. **Home** - Hero section with full background image, overlay, and CTA
2. **Clients** - Trusted industry partners logos
3. **Services Cards** - Outdoor Stairs & Custom Staircases & Mezzanines
4. **Limited Time Offer** - Promo section for VIC homeowners
5. **Stairs** - Stair types and services information
6. **Treads** - Custom tread information and anti-slip features
7. **Gallery** - Project showcase with lightbox popup
8. **About Us** - Company background and experience
9. **Contact** - Contact form and details
10. **Footer** - Quick links, contact info, newsletter signup, social links

### Navigation
- Home, Stairs, Treads, Gallery, About Us, Contact Us
- Mobile hamburger menu for responsive navigation

## Key Features

### Hero Section
- Full-width background image with dark overlay
- "Custom Staircase Designs" headline
- "Elevate Your Space With Quality Craftsmanship" tagline
- "Learn More" CTA button

### Gallery Lightbox
- Click any gallery image to open fullscreen popup
- Close with X button, clicking outside, or Escape key
- Smooth fade animations

### Client Feedback Implementation
Based on client feedback documents (Website changes.pdf, Website changes V2.pdf):

- **About Us Text**: Updated to Melbourne-based, 10+ years experience, structural treated pine focus
- **Treads Text**: Custom anti-slip finish in Treated Pine and Merbau
- **Stairs Types**: Treated Pine, Mezzanine, Merbau, Spotted Gum Stairs
- **Limited Time Offer**: Changed NSW to VIC, removed shop button
- **Footer Text**: "We build custom staircases and treads to suit all your outdoor needs, combining durability, safety and expert craftsmanship."
- **Buttons**: "Enquire Now" instead of "Shop" throughout
- **Instagram**: Linked to https://www.instagram.com/stairsandtreadco/
- **Mobile**: Responsive navigation with header options at top

### Contact Information
- **Address**: Reservoir, Melbourne, VIC
- **Email**: stairsandtreadco@outlook.com
- **Phone**: 0447 019 773

### Client Logos
- Allspex Building Services
- Securetech
- Vanscope Fitout

## File Structure

```
stairs-and-tread-co/
├── index.html          # Main HTML file
├── styles.css          # All CSS styles
├── script.js           # JavaScript functionality
├── images/             # All images and logos
│   ├── Logo.jpg        # Main company logo
│   ├── allspex.jpg     # Client logo
│   ├── securetech logo.jpg
│   ├── vanscope fitout logi.jpeg
│   └── [project images...]
├── .gitignore
├── .vercel/            # Vercel configuration
└── README.md           # This file
```

## Deployment

### Auto-Deploy
Push to `main` branch triggers automatic Vercel deployment.

### Manual Deploy
```bash
vercel --prod
```

### Commands
```bash
# Push changes and deploy
git add -A && git commit -m "message" && git push origin main

# Deploy to production
vercel --prod --yes
```

## Design Decisions

### Colors
- **Primary (Orange)**: #F7931E
- **Dark**: #1a1a1a
- **Gray**: #666
- **Light**: #f8f8f8

### Typography
- Font Family: Poppins
- Weights: 300, 400, 500, 600, 700, 800

### Responsive Breakpoints
- Desktop: > 992px
- Tablet: 768px - 992px
- Mobile: < 768px

## Future Considerations

- Add more gallery images as projects are completed
- Add more client logos as partnerships grow
- Consider adding testimonials section
- Form could be connected to email service (currently opens mailto:)

## Copyright

2026 Stairs & Tread Co. All rights reserved.
