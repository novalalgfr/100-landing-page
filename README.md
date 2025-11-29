# 🚀 Project Hylos - UMKM Landing Page Collection

A comprehensive dataset of 100 professionally designed landing pages tailored for Indonesian UMKM (Usaha Mikro, Kecil, dan Menengah) businesses, featuring diverse design styles and layouts optimized for conversion.

## 📊 Dataset Overview

This repository contains 100 complete landing pages distributed across 5 distinct design styles, each crafted to serve different business personalities and target audiences.

### Design Styles

**Modern Minimalis** (20 pages)

- Clean whitespace with sans-serif typography
- Colors: Monochrome, blue, teal
- Vibe: Professional, trustworthy
- Perfect for: Tech services, professional consultants, modern cafes

**Warm & Friendly** (20 pages)

- Rounded elements with soft colors
- Colors: Orange, yellow, brown, coral
- Vibe: Approachable, cozy
- Perfect for: Family businesses, bakeries, children's services

**Bold & Vibrant** (20 pages)

- High contrast with dynamic layouts
- Colors: Bright colors, gradients
- Vibe: Energetic, youthful
- Perfect for: Fashion brands, creative agencies, fitness businesses

**Elegant & Luxury** (20 pages)

- Serif fonts with generous spacing
- Colors: Black, white, gold, navy
- Vibe: Premium, sophisticated
- Perfect for: Luxury products, upscale services, jewelry

**Traditional & Cultural** (20 pages)

- Cultural patterns with warm tones
- Colors: Earth tones, batik-inspired
- Vibe: Authentic, heritage
- Perfect for: Traditional crafts, cultural products, heritage brands

## 🏗 Landing Page Structure

Each landing page includes these standard sections:

### 1. Hero Section

- Brand logo and name
- Compelling headline (value proposition)
- Supporting subheadline
- Primary CTA button (WhatsApp/Order)
- Hero image or illustration
- Optional trust badges

### 2. About/Tentang Section

- Owner/business photo (optional)
- Brief business story (2-3 sentences)
- 3-4 unique selling points (USPs)
- Optional awards/achievements

### 3. Products/Services Section

- Grid or carousel of featured products (3-6 items)
- Each item includes:
  - Product photo
  - Product name
  - Price (Rp format)
  - Short description
  - CTA button (Order/Details)

### 4. Testimonial Section

- 3-6 customer testimonials
- Each includes:
  - Customer photo or initials
  - Name + role/location
  - Testimonial quote
  - Star rating (optional)

### 5. Contact/CTA Section

- WhatsApp button (primary CTA)
- Physical address with optional Google Maps embed
- Operating hours
- Social media links (Instagram, Facebook, TikTok)
- Optional contact form

### 6. Footer

- Brand name
- Quick links (About, Products, Contact)
- Social media icons
- Copyright notice
- Optional payment method logos

## 📋 UMKM Categories

The dataset covers 4 main business categories:

**Makanan/Minuman** (Food & Beverage)

- Coffee/Cafe, Catering, Frozen food, Bakery/Cakes

**Fashion/Beauty**

- Fashion, Hijab, Skincare, Accessories

**Jasa** (Services)

- Photography, Digital marketing, Event organizer, Private tutoring, Laundry

**Produk/Kerajinan** (Products/Crafts)

- Gift hampers, Furniture, Plants, Handicrafts, Digital products

## 🎨 Layout Variations

Each style features 4 distinct layout types (5 pages per layout):

**Layout A - Classic Top-Down**

- Full-width hero
- 2-column about section
- 3×2 product grid
- Carousel testimonials
- Centered contact section

**Layout B - Split Hero**

- Left/right split hero
- 4×1 product grid with sidebar
- Full-width about section
- 3-column testimonials
- 2-column contact section

**Layout C - Centered Minimal**

- Centered vertical hero
- Carousel/slider products
- Centered card about section
- Stacked testimonials
- Side-by-side form and info

**Layout D - Asymmetric Modern**

- Diagonal/angled hero
- Floating card about section
- Masonry product grid
- Overlapping testimonial cards
- Sticky sidebar contact

## 📐 Technical Specifications

### Responsive Breakpoints

- **Mobile**: 320px - 767px
- **Tablet**: 768px - 1023px
- **Desktop**: 1024px+

### Color Palettes

**Modern Minimalis**

- Primary: `#2563eb`, `#0ea5e9`, `#6366f1`
- Neutral: `#1e293b`, `#f8fafc`

**Warm & Friendly**

- Primary: `#f97316`, `#fbbf24`, `#fb923c`
- Neutral: `#78350f`, `#fef3c7`

**Bold & Vibrant**

- Primary: `#ec4899`, `#8b5cf6`, `#06b6d4`
- Neutral: `#1f2937`, `#fef2f2`

**Elegant & Luxury**

- Primary: `#000000`, `#d4af37`, `#1e3a8a`
- Neutral: `#f9fafb`, `#374151`

**Traditional & Cultural**

- Primary: `#92400e`, `#b45309`, `#065f46`
- Neutral: `#fef3c7`, `#1c1917`

### Typography

- **Modern**: Inter, Poppins, Plus Jakarta Sans
- **Warm**: Nunito, Quicksand, Comfortaa
- **Bold**: Montserrat, Raleway, Bebas Neue
- **Elegant**: Playfair Display, Cormorant, Lora
- **Traditional**: Merriweather, Lora, Crimson Text

## 📁 File Structure

```
dataset/
├── LP_001.json     # Metadata & instructions
├── LP_001.html     # HTML with Tailwind CDN
├── LP_002.json
├── LP_002.html
├── ...
└── LP_100.html
```

### JSON Metadata Format

Each JSON file contains:

- Landing page metadata
- Style classification
- Layout type
- UMKM category
- Color palette
- Typography settings
- Content instructions

### HTML Format

Each HTML file includes:

- Complete standalone page
- Tailwind CSS via CDN
- Responsive design
- Optimized for performance
- Ready to deploy

## 🎯 Use Cases

This dataset is ideal for:

- Training generative AI models for web design
- UMKM business owners seeking professional landing pages
- Web developers looking for design inspiration
- UI/UX researchers studying landing page patterns
- Digital marketing agencies serving small businesses

## 📊 Dataset Distribution Matrix

```
100 Landing Pages = 5 Styles × 4 Layouts × 5 UMKM Categories

Each Style (20 pages):
├── Layout A (5 pages): Food(2), Fashion(1), Services(1), Products(1)
├── Layout B (5 pages): Food(1), Fashion(2), Services(1), Products(1)
├── Layout C (5 pages): Food(1), Fashion(1), Services(2), Products(1)
└── Layout D (5 pages): Food(1), Fashion(1), Services(1), Products(2)
```

## 🚀 Getting Started

1. Clone this repository
2. Browse the `dataset/` folder
3. Open any HTML file in your browser to preview
4. Check the corresponding JSON file for metadata
5. Customize the content for your business needs

## 📝 License

This dataset is created as part of Project Hylos for Generative AI research and UMKM empowerment.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

---

**Project Hylos** - Empowering Indonesian UMKM through AI-powered web design
