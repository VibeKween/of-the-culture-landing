# Of The Culture — Landing Page

## Project Overview

A manifesto-style landing page for Of The Culture, a small-batch clothing studio under Tuku Group. The site maintains the ultra-minimal aesthetic of the parent company while adapting for the clothing brand's distinct voice and positioning.

**Purpose**: Position Of The Culture as a thoughtful clothing studio rooted in digital culture, with emphasis on craftsmanship, limited runs, and subtle cultural references.

---

## Design Reference

**Primary Inspiration**: Tuku Group landing page design system — ultra-minimal, manifesto-driven, type-forward approach

**Key Design Principles**:
- Stripped-down, conceptual aesthetic
- Typography as primary visual element
- Bold, declarative statements with poetic flow
- Immersive, art-like experience
- Endless whitespace and breathing room
- Consistent with parent company visual language

---

## Brand Positioning

- **Small-batch approach** — limited-run, intentional production
- **Digital culture roots** — code, remix culture, personal sovereignty
- **Craftsmanship focus** — quality over quantity, signal over noise
- **Quiet presence** — not loud, not trend-driven, thoughtful positioning

**Tone**: Artistic, sophisticated, quietly confident with cultural awareness

---

## Content Structure

### 1. Hero Statement
```
O F  T H E  C U L T U R E
A small-batch clothing studio.
Limited-run apparel.
Created with intention.
```

### 2. Brand Philosophy
```
Inspired by design.
Rooted in digital culture.
Committed to craftsmanship.
```

### 3. Cultural References
```
Subtle references:
Code. Remix culture.
Personal sovereignty.
The unspoken rituals of the internet.
```

### 4. Brand Positioning
```
Not loud.
Not trend-driven.
Each piece a signal.
A quiet presence in the sea of the everyday.
```

### 5. Contact & Footer
```
atelier@oftheculture.com
(Email subject: "Inquire — Of The Culture")

© 2025 Tuku Group, LLC.
Independent and privately held.
```

---

## Visual Design System

### Typography
- **Brand Wordmark**: ITC Avant Garde Gothic (uppercase, spaced)
  - Letter-spacing: 0.16em (desktop) / 0.14em (mobile)
  - Word-spacing: 0.16em (desktop) / 0.14em (mobile)
  - Critical: Do not substitute font for brand name
- **Body Text**: JetBrains Mono (consistent with parent company)
- **Hierarchy**: Clear distinction between wordmark and supporting copy

### Colors
- **Primary Black**: `#000000`
- **Primary White**: `#FFFFFF`  
- **Gold Accent**: `#C19A4B` (inherited from Tuku Group palette)

### Layout Principles
- **Sequential text blocks** — each concept in minimal section
- **Maximum 720px width** — single column, centered layout
- **88px vertical spacing** — breathing room between blocks (desktop)
- **52px vertical spacing** — mobile adaptation
- **Manifesto flow** — poetic content unfolds as you scroll

---

## Technical Specifications

### Typography Scale
- **Desktop (≥1024px)**: Wordmark 64px, Body 18px base
- **Tablet (768-1023px)**: Wordmark 48px, Body 16px base  
- **Mobile (≤767px)**: Wordmark 32px, Body 16px base

### Responsive Approach
- **Mobile-first** design methodology
- **Typography-focused** responsive scaling
- **Single breakpoint** system for simplicity
- **Consistent spacing** rhythm across devices

### Performance Goals
- **Sub-2 second** load time
- **Minimal dependencies** (typography, basic CSS)
- **Lightweight footprint** aligned with minimal aesthetic

---

## Content Guidelines

### Voice Principles
- **Artistic authority** — confident but not commercial
- **Cultural awareness** — understands digital culture subtleties
- **Poetic brevity** — each line serves the manifesto flow
- **Intentional language** — every word deliberate

### Copy Rules
- Maintain poetic line breaks for natural reading rhythm
- Avoid fashion industry jargon or sales language
- Lead with cultural positioning, follow with craft emphasis
- Single call-to-action: "Inquire" via email

---

## Development Approach

### Phase 1: Foundation ✅
- [x] Set up project structure matching Tuku Group standards
- [x] Implement SVG wordmark with perfect brand control
- [x] Create responsive typography system with CSS transforms
- [x] Establish layout grid and spacing rhythm

### Phase 2: Content Integration ✅
- [x] Build hero section with custom SVG wordmark
- [x] Implement manifesto sections with poetic flow
- [x] Add contact integration with branded email subject
- [x] Test responsive behavior across devices

### Phase 3: Brand Enhancement ✅
- [x] Added gold accents to cultural concept headers
- [x] Perfect alignment with parent company design language
- [x] Eliminated visual inconsistencies between sites
- [x] Final wordmark scaling and positioning optimization

---

## File Structure
```
02-LANDING-PAGE/
├── index.html
├── css/
│   └── main.css
├── fonts/ (ready for custom font files)
├── images/ (ready for assets)
├── docs/ (documentation)
├── README.md
└── DEVELOPMENT-LOG.md
```

## Deployment

**Current Status**: Production ready  
**Deployment**: Ready for GitHub Pages (following Tuku Group pattern)  
**Custom Domain**: Ready for configuration

---

## Typography Implementation Notes

### ITC Avant Garde Gothic
- Loaded via CSS font-family with system fallbacks
- Fallback stack: 'Futura', 'Century Gothic', 'Avenir', sans-serif
- Critical spacing: letter-spacing and word-spacing for proper wordmark
- Protected lockup: Do not modify spacing or substitute font

### JetBrains Mono
- Loaded via Google Fonts CDN for consistency
- Used for all body text and supporting copy
- Maintains visual connection to parent company

---

## Brand Compliance

### Wordmark Usage
- **Correct**: `O F  T H E  C U L T U R E` (spaced, uppercase)
- **Spacing**: Consistent letter and word spacing via CSS
- **Font**: ITC Avant Garde Gothic only for brand name
- **Clearspace**: Maintain proper margins around wordmark

### Parent Company Alignment
- **Color palette**: Inherited from Tuku Group
- **Layout patterns**: Sequential block structure
- **Typography system**: JetBrains Mono for body text
- **Minimal aesthetic**: Consistent with parent brand values

---

*Small-batch. Digital culture. Created with intention.*