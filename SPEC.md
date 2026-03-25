# Portfolio Website Specification - Anirban Goswami

## Project Overview
- **Project Name**: Anirban Goswami Portfolio
- **Type**: Single-page personal portfolio website
- **Core Functionality**: Showcase skills, projects, and contact information with a futuristic/cyberpunk aesthetic
- **Target Users**: Potential employers, clients, and collaborators

## UI/UX Specification

### Layout Structure
- **Navigation**: Fixed top nav with glowing glassmorphism effect
- **Hero Section**: Full viewport height with animated background and name reveal
- **About Section**: Split layout with bio and profile visual
- **Skills Section**: Animated skill bars with neon glow effects
- **Projects Section**: Card grid with hover effects
- **Contact Section**: Futuristic form with glowing inputs
- **Footer**: Minimal with social links

### Visual Design

#### Color Palette
- **Background Primary**: #0a0a0f (deep space black)
- **Background Secondary**: #12121a (dark purple-black)
- **Accent Primary**: #00f0ff (electric cyan)
- **Accent Secondary**: #ff00aa (hot pink/magenta)
- **Accent Tertiary**: #7b2dff (electric purple)
- **Text Primary**: #ffffff
- **Text Secondary**: #a0a0b0

#### Typography
- **Headings**: 'Orbitron' (Google Fonts) - futuristic, geometric
- **Body**: 'Exo 2' (Google Fonts) - clean, tech-inspired
- **Hero Name**: 72px bold
- **Section Titles**: 48px with glow effect
- **Body Text**: 16px

#### Spacing System
- **Section Padding**: 100px vertical, 5% horizontal
- **Card Padding**: 30px
- **Element Gaps**: 20px standard

#### Visual Effects
- **Neon Glow**: box-shadow with accent colors
- **Glassmorphism**: backdrop-filter blur with semi-transparent backgrounds
- **Grid Background**: Animated perspective grid
- **Scan Lines**: Subtle CRT scan line overlay
- **Particle Effects**: Floating geometric shapes
- **Typing Animation**: For hero text
- **Scroll Animations**: Fade-in and slide-up on scroll

### Components

#### Navigation
- Logo: "AG" with glow effect
- Links: Home, About, Skills, Projects, Contact
- Hover: Underline grows from center with cyan glow

#### Hero Section
- Large animated name "ANIRBAN GOSWAMI"
- Subtitle with typing animation: "Developer | Designer | Creator"
- Floating geometric shapes in background
- Scroll indicator with pulse animation

#### About Section
- Profile placeholder with futuristic frame
- Bio text with highlight effects
- Stats: Years Experience, Projects, Clients

#### Skills Section
- Skill categories: Frontend, Backend, Tools
- Animated progress bars with gradient fill
- Skill tags with glow on hover

#### Projects Section
- Project cards with:
  - Image/Preview
  - Title and description
  - Tech stack tags
  - Hover: Scale up with enhanced glow

#### Contact Section
- Glowing input fields
- Submit button with pulse effect
- Social media icons with hover glow

## Functionality Specification

### Core Features
1. Smooth scroll navigation
2. Animated skill bars on scroll
3. Project card hover interactions
4. Form validation (client-side)
5. Responsive design (mobile, tablet, desktop)
6. Particle/background animation

### User Interactions
- Click nav links → smooth scroll to section
- Hover cards → scale and glow effect
- Scroll → trigger reveal animations
- Submit form → validation feedback

### Responsive Breakpoints
- Desktop: > 1024px
- Tablet: 768px - 1024px
- Mobile: < 768px

## Acceptance Criteria
1. Page loads with animated hero section
2. All navigation links work correctly
3. Skills animate when scrolled into view
4. Project cards have hover effects
5. Form inputs have focus glow effects
6. Fully responsive on all devices
7. No console errors
8. All fonts load correctly
