# Ou CPA LLC Landing Page

## Project Overview
A professional, responsive landing page for Ou CPA LLC accounting firm built with Astro.js and optimized for Cloudflare deployment.

## Design Reference
- **Design File**: `example-design.jpg` - Modern layout with curved section dividers
- **Color Palette**: `color-palette.jpg` - Blue-gray primary with cream/beige accents
- **Background**: `src/assets/home-background.jpg` - Las Vegas night skyline for hero section

## Site Structure
4 main sections with enhanced user experience:
1. **Home** - Hero section with optimized background image, enhanced text readability, and clear CTAs
2. **About Us** - Company info, statistics, and client testimonials with 5-star reviews
3. **Areas of Practice** - 6 comprehensive service offerings with custom SVG icons
4. **Contact** - Contact form, business information, and clickable contact details

## Component Architecture
- `Layout.astro` - Main layout with global styles, CSS variables, and responsive design
- `Header.astro` - Fixed navigation with integrated contact info and mobile-responsive menu
- `Hero.astro` - Optimized hero section with Astro Image component and text shadows
- `About.astro` - Company overview with client testimonials and statistics
- `Services.astro` - Service cards with hover effects and feature lists
- `Contact.astro` - Contact form with validation and business details
- `Footer.astro` - Clean footer with service links and company information

## Color Scheme & Design System
- **Primary**: Blue-gray (#6B8CAE)
- **Secondary**: Light gray (#F8F9FA)
- **Accent Colors**: Light blue-gray (#8FA4BE), Dark blue-gray (#5A7A9A)
- **Typography**: Inter font family for professional appearance
- **Shadows**: Subtle box shadows and text shadows for depth

## Contact Information
- **Phone**: (702) 756-4507 (clickable tel: links)
- **Email**: ou.cpanotary@gmail.com (clickable mailto: links)
- **Address**: 123 Business Ave, Suite 456, City, State 12345

## Technical Features
- **Image Optimization**: Astro Image component with WebP conversion and quality=80
- **Cloudflare Integration**: imageService set to "compile" for build-time optimization
- **Responsive Design**: Mobile-first approach with progressive enhancement
- **Performance**: Optimized loading with eager loading for above-the-fold content
- **Accessibility**: Proper alt text, semantic HTML, and keyboard navigation

## Development Commands
- `npm run dev` - Start development server
- `npm run build` - Build for production with image optimization
- `npm run preview` - Preview production build with Wrangler
- `npm run deploy` - Deploy to Cloudflare
- `npm run cf-typegen` - Generate Cloudflare types

## Deployment Configuration
- **Platform**: Cloudflare Pages with Workers adapter
- **Image Service**: "compile" mode for build-time optimization
- **Build Output**: Static site with optimized assets

## Content Strategy
Professional accounting firm positioning with:
- **Trust Signals**: Client testimonials with 5-star ratings
- **Expertise Messaging**: 15+ years experience, 500+ satisfied clients
- **Service Clarity**: 6 distinct service areas with detailed descriptions
- **Easy Contact**: Multiple contact methods integrated throughout
- **Professional Credentials**: CPA Certified, Licensed, Insured badges

## Assets
- **Logo**: `public/logo.png` - Company logo in PNG format
- **Background**: `src/assets/home-background.jpg` - Optimized hero background
- **Icons**: Custom SVG icons for services and contact methods
- **Fonts**: Google Fonts (Inter) for consistent typography

## Mobile Optimization
- **Header**: Compact contact info with progressive font sizing
- **Navigation**: Hamburger menu with smooth animations
- **Images**: Responsive sizing with object-position adjustments
- **Text**: Enhanced readability with proper contrast ratios
- **Touch Targets**: Appropriately sized buttons and links