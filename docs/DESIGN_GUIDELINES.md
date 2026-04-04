# Forcen AI - Design & Brand Guidelines

---

## Brand Identity

### Brand Values
- **Innovative** - Cutting-edge AI solutions
- **Trustworthy** - Reliable, proven track record
- **Professional** - Enterprise-grade quality
- **Accessible** - Making AI approachable
- **Results-Driven** - Focus on measurable outcomes

### Brand Voice & Tone
- **Professional yet approachable** - Not overly technical
- **Confident but humble** - We know our expertise but don't boast
- **Clear and direct** - Communicate value clearly
- **Forward-thinking** - Future-focused, innovative
- **Client-centric** - Always focused on client success

---

## Visual Identity

### Color System

#### Primary Colors
| Color | Hex | RGB | Usage |
|-------|-----|-----|-------|
| Primary Blue | `#0066ff` | 0, 102, 255 | Buttons, links, accents |
| Secondary Cyan | `#00d4ff` | 0, 212, 255 | Highlights, hover states |
| Accent Pink | `#ff006e` | 255, 0, 110 | Call-outs, important elements |

#### Neutral Colors
| Color | Hex | RGB | Usage |
|-------|-----|-----|-------|
| Dark Background | `#0f0f1e` | 15, 15, 30 | Main background |
| Light Text | `#ffffff` | 255, 255, 255 | Primary text |
| Gray Text | `#b0b0c0` | 176, 176, 192 | Secondary text |
| Light Gray | `#d0d0e0` | 208, 208, 224 | Tertiary text |

#### Semantic Colors (When Needed)
| Color | Hex | Usage |
|-------|-----|-------|
| Success | `#00ff88` | Positive actions, confirmations |
| Warning | `#ffaa00` | Alerts, cautions |
| Error | `#ff4444` | Errors, critical alerts |

### Color Usage Guidelines

**Primary Blue (#0066ff)**
- Main buttons
- Links and navigation
- Primary call-to-action elements
- Form focus states

**Secondary Cyan (#00d4ff)**
- Hover states on buttons
- Highlighted text
- Decorative elements
- Secondary CTAs
- Important numbers/metrics

**Dark Background (#0f0f1e)**
- Main page background
- Card backgrounds (transparent overlays)
- Footer background

**Light Text (#ffffff)**
- Primary body text
- Headlines
- Navigation text

**Gray Text (#b0b0c0)**
- Secondary descriptions
- Supporting information
- Placeholder text

---

## Typography

### Font Family
**Primary**: Segoe UI, Tahoma, Geneva, Verdana, sans-serif

*Rationale*: Clean, modern, excellent readability on all devices. System fonts = faster loading

### Font Weights
- **700 (Bold)** - Headlines, section titles
- **600 (Semi-bold)** - Subheadings, emphasis
- **500 (Medium)** - Labels, important text
- **400 (Regular)** - Body text, paragraphs

### Type Scale

| Element | Size | Weight | Line Height | Margin Bottom |
|---------|------|--------|-------------|---------------|
| H1 | 3.5rem | 700 | 1.2 | 1rem |
| H2 | 2.5rem | 700 | 1.3 | 1rem |
| H3 | 1.5rem | 600 | 1.4 | 0.8rem |
| H4 | 1.3rem | 600 | 1.4 | 0.6rem |
| Body | 1rem | 400 | 1.6 | 1rem |
| Small | 0.9rem | 400 | 1.5 | 0.5rem |
| Tiny | 0.75rem | 500 | 1.4 | 0.3rem |

### Typography Usage

**Headlines (H1, H2)**
- Page titles and main section headings
- Clear hierarchy and visual importance
- Use gradient text for emphasis (primary blue to cyan)

**Subheadings (H3, H4)**
- Section subtitles
- Card titles
- Feature headings

**Body Text**
- Default paragraph text
- Service descriptions
- Case study content
- Use gray text for secondary information

**Buttons & CTAs**
- Font weight: 600
- All caps or title case
- Clear visual hierarchy through color, size

---

## Spacing & Layout

### Spacing Scale
| Scale | Pixels | Usage |
|-------|--------|-------|
| 2xs | 0.25rem (4px) | Tiny margins |
| xs | 0.5rem (8px) | Small spacing |
| sm | 1rem (16px) | Standard margin |
| md | 1.5rem (24px) | Larger gaps |
| lg | 2rem (32px) | Section margins |
| xl | 3rem (48px) | Major section spacing |
| 2xl | 4rem (64px) | Large gaps |
| 3xl | 6rem (96px) | Page section padding |

### Layout Grid
- **Max content width**: 1400px
- **Standard padding**: 2rem horizontal, 6rem vertical
- **Gap between grid items**: 2rem
- **Card padding**: 2rem

### Margin Guidelines
- Elements within sections: 1-2rem apart
- Section-to-section: 6rem vertical padding
- Button/form groups: 1rem gap

---

## Buttons & Interactive Elements

### Button Styles

#### Primary Button
```
Background: Linear gradient (Primary Blue → Secondary Cyan)
Color: White
Padding: 0.75rem 1.5rem
Border: None
Border-radius: 5px
Font-weight: 600
Transition: transform 0.3s, box-shadow 0.3s
```

**States**:
- **Default**: Base style
- **Hover**: Translate up 2px, add shadow 0 10px 25px rgba(0, 102, 255, 0.3)
- **Active**: Slightly darker, no transform
- **Disabled**: 50% opacity, cursor not-allowed

#### Secondary Button
```
Background: Transparent
Border: 2px solid Primary Blue
Color: Primary Blue
```

**States**:
- **Hover**: Background rgba(0, 102, 255, 0.1)
- **Active**: Background darkens further

### Form Elements

#### Input Fields
```
Background: rgba(255, 255, 255, 0.05)
Border: 1px solid rgba(0, 102, 255, 0.2)
Border-radius: 5px
Padding: 0.75rem
Color: White
```

**Focus State**:
- Border color: Primary Blue
- Background: rgba(0, 102, 255, 0.05)
- Box-shadow: 0 0 0 3px rgba(0, 102, 255, 0.1)

#### Text Area
- Same as input fields
- Min-height: 120px
- Resize: vertical

### Link Styling
```
Color: Primary Blue
Text-decoration: None
```

**Hover**:
- Color: Secondary Cyan
- Text-decoration: Underline

---

## Cards & Components

### Service Card
- **Background**: rgba(255, 255, 255, 0.02)
- **Border**: 1px solid rgba(0, 102, 255, 0.2)
- **Border-radius**: 10px
- **Padding**: 2rem
- **Transition**: All 0.3s

**Hover State**:
- Background: rgba(0, 102, 255, 0.1)
- Border: Primary Blue
- Transform: translateY(-5px)

### Case Study Card
- **Similar to Service Card** with case study specific colors
- Include header with gradient background
- Display prominent metrics
- Add sidebar for additional info

### Testimonial Card
- **Background**: rgba(255, 255, 255, 0.02)
- **Border**: 1px solid rgba(0, 212, 255, 0.2)
- **Padding**: 2rem
- Include star ratings
- Author name and role

---

## Navigation

### Header
- **Fixed** to top of page
- **Background**: rgba(15, 15, 30, 0.95) with backdrop-filter blur
- **Border-bottom**: 1px solid rgba(0, 102, 255, 0.1)
- **Padding**: 1.5rem
- **Z-index**: 1000

### Navigation Links
- **Default Color**: Gray Text
- **Hover Color**: Secondary Cyan
- **Font-size**: 0.95rem
- **Spacing**: 0 1.5rem between links

### Active Link
- Color: Secondary Cyan
- Optional: Underline or bottom border

---

## Hero Section

### Design Elements
- **Background**: Linear gradient with overlay
- **Positioning**: Center-aligned
- **Text Hierarchy**: Main headline, supporting paragraph, CTA buttons
- **Decorative Element**: Radial gradient circle background

### Content Guidelines
- **Headline**: Catchy, benefit-focused
- **Subheadline**: Supporting statement, problem/solution
- **CTAs**: Maximum 2-3 buttons

---

## Section Layouts

### Full-width Sections
```
Padding: 6rem 2rem
Max-width: 1400px
Margin: 0 auto
```

### Alternative Backgrounds
- **Light**: rgba(0, 102, 255, 0.02)
- **Medium**: Linear gradient with transparency
- **Dark**: Transparent (default dark bg shows through)

### Section Dividers
Use color/transparency changes rather than lines:
- Alternate transparent backgrounds
- Use gradient overlays
- Subtle border-top/bottom

---

## Responsive Design Breakpoints

| Breakpoint | Width | Target Device |
|------------|-------|----------------|
| Mobile | < 480px | Small phones |
| Tablet | 480px - 768px | Tablets, larger phones |
| Desktop | 768px - 1400px | Laptops |
| Large Desktop | > 1400px | Ultra-wide monitors |

### Mobile-First Changes
- **Navigation**: Stack vertically, center align
- **Grid**: Single column
- **Padding**: Reduced to 1rem
- **Font Size**: Slightly reduced for readability
- **Buttons**: Full width or stacked

---

## Icons & Graphics

### Icon Usage
- **Font size for section icons**: 2.5rem
- **Color**: Typically Primary Blue or Secondary Cyan
- **Emoji icons**: Acceptable for approachability
- **Custom icons**: Maintain consistent style

### Gradients
**Standard gradient**:
```css
background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
```

**Direction**: 135deg (top-left to bottom-right) is default

### Images
- **Style**: Professional, modern
- **Format**: JPG for photos, PNG for graphics
- **Size**: Optimize for web (compress)
- **Alt-text**: Always include descriptive alt text

---

## Accessibility Standards

### Color Contrast
- **WCAG AA**: Ratio of 4.5:1 for normal text
- **WCAG AAA**: Ratio of 7:1 for normal text
- Current design meets AA standard

### Text Sizing
- **Minimum**: 14px (0.875rem)
- **Standard**: 16px (1rem)
- **Relative sizes**: Use rem units for scaling

### Focus States
- **All interactive elements** must have visible focus state
- Color change + border change recommended
- Avoid outline: none without alternative

### Semantic HTML
- Use proper heading hierarchy (H1 → H2 → H3, not skipping)
- Use semantic tags: `<header>`, `<nav>`, `<section>`, `<article>`, `<footer>`
- Form labels must be properly associated

---

## Animation & Transitions

### Timing
- **Fast interactions**: 0.2s (button hover)
- **Medium interactions**: 0.3s (card hover)
- **Slow animations**: 0.5s+ (scroll transitions)

### Easing
- **Standard**: ease-in-out
- **Quick feedback**: ease-out
- **Entrance**: ease-in

### Effects to Use
- ✅ Hover color changes
- ✅ Subtle elevation (translateY)
- ✅ Border color transitions
- ✅ Background opacity changes
- ❌ Avoid: Excessive animations, auto-playing videos, moving text

---

## Print Styles

When printed, website should:
- [ ] Remove navigation bar
- [ ] Remove CTAs that don't apply
- [ ] Optimize for black & white
- [ ] Ensure text is readable
- [ ] Include company contact info

---

## Brand Don'ts

❌ **DO NOT:**
- Use colors outside the defined palette without approval
- Change font families without brand update
- Make buttons smaller than 0.75rem padding
- Use Lorem ipsum in production
- Include outdated case studies
- Use low-quality images
- Add too many animations
- Use multiple brands/logos
- Deviate from color hex codes

---

## Future Design Considerations

- **Dark/Light mode toggle**: Current design is dark-mode only
- **Component library**: Create reusable styled components
- **CSS-in-JS**: Consider for dynamic theming
- **Accessibility audit**: Annual WCAG compliance check
- **Design tokens**: Move to token-based system for scaling

---

## Version History

- **v1.0** - Initial brand guidelines (April 3, 2025)

---

## Contact for Brand Questions

**Designer/Brand Lead**: Alfonso Forcén
📧 alfonso@forcen-ai.com

All brand decisions should go through brand lead before implementation.
