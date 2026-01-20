# Trophy Portfolio Website — Full Project Scope & Plan

Target Stack: HTML / CSS / JavaScript  
Hosting: Cloudflare Pages (static), Cloudflare Workers (future backend)

---

## Project Goals

- Learn real-world web development fundamentals (no site builders)
- Build a polished, animated trophy portfolio website
- Deploy as a static site on Cloudflare Pages
- Prepare architecture for future chatbot and Three.js enhancements

---

## High-Level Scope

### In Scope (MVP)

- Semantic HTML structure
- Responsive CSS layout and animations
- JavaScript-driven interactions and scroll effects
- SVG trophy animation and section reveals
- Accessibility and reduced-motion support
- Static deployment on Cloudflare Pages

### Planned for Later (Not MVP)

- Chatbot via Cloudflare Worker (API proxy)
- Optional Three.js 3D scene
- Persistent data or auth (Supabase or Cloudflare D1)

### Out of Scope (MVP)

- CMS
- Payments
- User accounts
- Traditional backend server

---

## Project Phases Overview

| Phase     | Description                | Estimated Time  |
| --------- | -------------------------- | --------------- |
| Phase 1   | HTML Foundations           | 4–5 hours       |
| Phase 2   | CSS Styling & Layout       | 12–15 hours     |
| Phase 3   | JavaScript Interactivity   | 10–12 hours     |
| Phase 4   | Final Integration & Polish | 3–4 hours       |
| Phase 5   | Cloudflare Deployment      | 1–2 hours       |
| **Total** |                            | **30–38 hours** |

---

# Phase 1: HTML Foundations (Complete ✓)

**Total time: ~4–5 hours**

### 1.1 Document Structure (30 min)

- `<!DOCTYPE html>`
- `<html>`, `<head>`, `<body>`

### 1.2 Metadata (35 min)

- `<meta charset>`
- `<meta viewport>`
- `<title>`

### 1.3 Content vs Structure (40 min)

- Headings
- Paragraphs
- `<strong>`, `<em>`

### 1.4 Semantic Elements (35 min)

- `<header>`
- `<main>`
- `<section>`
- `<footer>`

### 1.5 Links and Lists (40 min)

- `<a>`
- `<ul>`, `<li>`

### 1.6 Embedded Content (45 min)

- `<img>`
- Inline SVG basics

### 1.7 Page Flow Concepts (40 min)

- Section flow
- Fixed positioning concepts
- `z-index` awareness

---

# Phase 2: CSS Styling & Layout

**Total time: ~12–15 hours**

### 2.1 How CSS Connects to HTML (45 min)

- Inline vs internal vs external styles (15 min)
- When to use each (15 min)
- Add internal stylesheet (15 min)

### 2.2 Selectors (60 min)

- Element selectors (15 min)
- Class selectors (20 min)
- ID selectors (10 min)
- Combining selectors (15 min)

### 2.3 Box Model (75 min)

- Content, padding, border, margin (30 min)
- `box-sizing` (20 min)
- Debugging with DevTools (25 min)

### 2.4 Typography (60 min)

- Font families and Google Fonts (20 min)
- Size, weight, line-height (20 min)
- Color and text styling (20 min)

### 2.5 Layout Fundamentals (55 min)

- Block vs inline elements (20 min)
- `display` property (20 min)
- Normal document flow (15 min)

### 2.6 Flexbox (80 min)

- Flex containers and items (20 min)
- Main vs cross axis (20 min)
- `justify-content`, `align-items` (25 min)
- Header + contact links layout (15 min)

### 2.7 CSS Grid (70 min)

- Grid containers and items (20 min)
- Rows, columns, gap (25 min)
- Skills grid layout (25 min)

### 2.8 Positioning (75 min)

- Static, relative, absolute, fixed (35 min)
- `z-index` and stacking contexts (20 min)
- Trophy scene layout setup (20 min)

### 2.9 Colors & Backgrounds (60 min)

- CSS variables (20 min)
- Gold color scheme (20 min)
- Gradients and backgrounds (20 min)

### 2.10 Transitions & Animations (70 min)

- `transition` property (20 min)
- Hover effects (20 min)
- Keyframe animations (30 min)

### 2.11 Responsive Design (60 min)

- Media queries (25 min)
- Mobile-first approach (20 min)
- DevTools testing (15 min)

---

# Phase 3: JavaScript Interactivity

**Total time: ~10–12 hours**

### 3.1 What JavaScript Does (45 min)

- Role of JS (15 min)
- DOM concept (20 min)
- Script placement (10 min)

### 3.2 Variables & Data Types (60 min)

- `let`, `const` (20 min)
- Strings, numbers, booleans (25 min)
- Arrays and objects (15 min)

### 3.3 Selecting Elements (50 min)

- `querySelector` (20 min)
- `querySelectorAll` (15 min)
- Storing references (15 min)

### 3.4 Events (65 min)

- `addEventListener` (20 min)
- Click events (15 min)
- Scroll events (20 min)
- Event object basics (10 min)

### 3.5 Changing Elements (55 min)

- `classList` (20 min)
- Inline styles (20 min)
- Changing content (15 min)

### 3.6 Scroll Detection (60 min)

- `window.scrollY` (15 min)
- Scroll progress math (25 min)
- Throttling/performance (20 min)

### 3.7 JS Animation (70 min)

- Dynamic transforms (25 min)
- Easing functions (25 min)
- Opacity + scroll mapping (20 min)

### 3.8 Putting It Together (80 min)

- SVG shard processing (25 min)
- Explosion parameters (25 min)
- Full animation loop (30 min)

---

# Phase 4: Final Integration & Polish

**Total time: ~3–4 hours**

### 4.1 Trophy SVG Integration (60 min)

- Import Illustrator SVG (20 min)
- Connect shard logic (20 min)
- Debug and test (20 min)

### 4.2 Section Reveal Animations (45 min)

- Intersection Observer (30 min)
- Fade/slide effects (15 min)

### 4.3 Accessibility & Polish (60 min)

- Reduced motion preference (20 min)
- Keyboard navigation (20 min)
- Cross-device testing (20 min)

---

# Phase 5: Hosting & Deployment (Cloudflare)

**Total time: ~1–2 hours**

### 5.1 Project Setup (30 min)

- Initialize Git repository
- Push to GitHub

### 5.2 Cloudflare Pages Deployment (45 min)

- Create Cloudflare Pages project
- Connect GitHub repo
- Configure static build (no framework)

### 5.3 Domain & Validation (30 min)

- Confirm HTTPS
- Test direct page loads
- Verify assets and caching

---

## Future Phases (Planned)

### Phase 6: Chatbot (Later)

- Frontend chat UI
- Cloudflare Worker `/api/chat`
- Environment variables for API keys
- Rate limiting and validation

### Phase 7: Three.js Enhancements (Later)

- Canvas or scene mount point
- Lazy-load Three.js
- Performance fallbacks

---

## Definition of Done (MVP)

- Deployed static site on Cloudflare Pages
- Responsive across devices
- No console errors
- Accessible navigation and content
- Clean structure ready for backend extensions
