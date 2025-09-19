# Design Guidelines for AN Enterprise E-commerce Landing Page

## Design Approach
**Selected Approach:** Reference-Based (E-commerce)
Drawing inspiration from premium e-commerce platforms like Shopify and Etsy, with emphasis on natural, earthy aesthetics that reflect the home décor and kitchen product focus.

## Core Design Elements

### A. Color Palette
**Primary Colors:**
- Dark Olive: 75 32% 31% (Primary brand color - #636B2F)
- Sage Green: 75 27% 67% (Secondary - #BAC095) 
- Light Green: 75 58% 72% (Accent - #D4DE95)
- Deep Forest: 75 14% 22% (Text/Headers - #3D4127)

**Supporting Colors:**
- Warm White: 60 9% 96% (Background)
- Soft Gray: 0 0% 45% (Secondary text)
- Pure White: 0 0% 100% (Cards, modals)

### B. Typography
**Font Stack:** Google Fonts
- **Primary:** Inter (headings, buttons, UI elements)
- **Secondary:** Source Sans Pro (body text, descriptions)
- **Accent:** Playfair Display (hero titles, section headers)

**Scale:**
- Hero Title: 3xl-4xl weight-bold
- Section Headers: 2xl-3xl weight-semibold  
- Product Names: lg-xl weight-medium
- Body Text: base weight-normal
- Captions: sm weight-light

### C. Layout System
**Spacing Units:** Tailwind spacing of 2, 4, 6, 8, 12, 16
- Component padding: p-6, p-8
- Section margins: mb-12, mb-16
- Grid gaps: gap-4, gap-6, gap-8
- Button padding: px-6 py-3, px-8 py-4

### D. Component Library

**Navigation:**
- Sticky header with logo left, navigation center, cart icon right
- Clean minimal design with subtle shadows
- Mobile: Hamburger menu with slide-out drawer

**Product Cards:**
- Rounded corners (rounded-lg)
- Subtle drop shadows (shadow-md)
- Hover elevation (hover:shadow-lg)
- Image aspect ratio 4:3
- Price prominence with original/sale pricing

**Buttons:**
- Primary: Dark olive background, rounded-md, medium weight
- Secondary: Outline style with olive border
- Cart CTAs: Larger sizing (px-8 py-4)
- Quick actions: Smaller, subtle styling

**Modals & Overlays:**
- Quick View: Large modal with product carousel
- Cart Slide-in: Right-side drawer with backdrop
- Rounded corners and generous padding
- Smooth transitions (300ms ease)

### E. Animations
**Minimal Approach:**
- Subtle hover states on cards (transform scale-105)
- Smooth cart drawer slide-in
- Gentle fade-ins for product loading
- No complex or distracting animations

## Images Section

**Hero Carousel Images (3 images):**
- Large lifestyle images (1200x600px) showing products in beautiful home settings
- Natural lighting with earthy, warm tones
- Kitchen scenes: Wooden counters, ceramic dishes, plants
- Living spaces: Cozy textures, natural materials, soft lighting

**Product Images:**
- Square format (400x400px) with consistent white/light backgrounds
- Multiple angles for Quick View carousel
- High quality, professional photography
- Lifestyle context shots where appropriate

**Value Proposition Icons:**
- Simple line icons (shipping, returns, quality, support)
- Consistent stroke weight and style
- Olive green color (#636B2F)

**Background Elements:**
- Subtle texture overlays for sections
- Soft gradients in sage green tones for section dividers
- No busy patterns - maintain clean, premium feel

## Key Design Principles
1. **Natural Elegance:** Earthy palette reflects organic, home-focused products
2. **Clean Hierarchy:** Clear visual paths from hero to products to conversion
3. **Trust Building:** Prominent testimonials, guarantees, and security badges
4. **Mobile-First:** Responsive design prioritizing mobile shopping experience
5. **Performance Focus:** Optimized images and minimal JavaScript for fast loading

## Accessibility Notes
- AA+ contrast ratios maintained across all color combinations
- Focus indicators visible on all interactive elements
- Alt text for all product and decorative images
- Keyboard navigation support for all functionality
- Screen reader friendly product information structure