# Implementation Plan: 2026 AI-Ready UX/UI Portfolio for Vasni Martin

**Objective**: transform the current portfolio into a "2026 Competitive" showcase that positions Vasni Martin as a top-tier Product Designer specializing in **AI & LLM Experiences**. The goal is to prove "End-to-End" capability (Design + Development) without altering the factual work history.

**Theme**: Cyber-Minimalist, Glassmorphism, "Neural" Aesthetics.
**Core Tech**: HTML5, Modern CSS (Variables, Flex/Grid), Vanilla JS (for performance and interactions).

---

## Sprint 1: Visual Identity & The "AI Atmosphere"
*Focus: Creating a visual language that screams "Future-Ready".*

1.  **Hero Section Overhaul**
    -   **Headline Refinement**: Update hero text to highlight "Designing Intelligent Interfaces for AI & LLMs".
    -   **Dynamic Background**: Implement a subtle "Neural Network" or "Constellation" particle animation in the Hero background (Canvas/JS) to signify data connectivity.
    -   **Glassmorphism Layout**: Apply the new `.glass` utility to the hero content container, adding blur and border transparency.

2.  **Global UI Polish**
    -   **Card Styles**: Update all "Services" and "Experience" cards to use the `bg-card` variable with subtle borders and glow effects on hover.
    -   **Gradients**: Apply the `electric blue` to `pink` gradient (defined in CSS) to primary buttons and key headings to create a "Neon" feel against the dark background.
    -   **Navigation**: Redesign the sticky header to be a floating "Glass Bar" (like macOS/iOS dynamic islands).

3.  **Typography & Micro-Typography**
    -   Apply `Space Grotesk` to all section headers for that "Tech Mono" feel.
    -   Increase line-height and tracking on `Inter` body text for optimal readability.

## Sprint 2: Content Positioning (The AI Narrative)
*Focus: Reframing skills and services to match Market Demand (AI/LLM) without changing work history.*

1.  **Services Section Re-Branding**
    -   Rename "UX Research" -> **"AI-User Interaction Analysis"**.
    -   Rename "Prototyping" -> **"GenAI Prototyping & Flows"**.
    -   Rename "UI Design" -> **"Intelligent Interface System Design"**.
    -   *Action*: Update icons to be more abstract/tech-focused (using existing Feather icons but styled with gradients).

2.  **Skills Section Upgrade**
    -   Visual Update: Change the "Progress Bar" style to "Holographic" filled bars.
    -   Add Skills: Explicitly list "Prompt Engineering", "LLM Context Mapping", "Model Fine-tuning UX", "Python (Basic)", "Vector Databases (Concept)".
    -   *Logic*: Show that you understand the *material* you are designing for.

3.  **Experience Section Presentation**
    -   Keep content factual (Orion, Ness, ValueLabs).
    -   Visuals: Connect the timeline items with a "Circuit Line" graphic instead of a simple border.
    -   Tags: Add "Tags" to each job entry highlighting the tech stack (e.g., "Data Vis", "System Design", "Automation").

## Sprint 3: The Interactive Portfolio Showcase
*Focus: "End-to-End" capability demonstration through complex interactions.*

1.  **Portfolio Grid "Masonry"**
    -   Refactor the Portfolio Grid to feel less like a "Bootstrap Template" and more like a "Design Museum".
    -   **Hover Effects**: When hovering a project, dim others and scale the active one. Show a "View Case Study" cursor.

2.  **"Tork AI Agent" Spotlight**
    -   Make the "Tork AI Agent" project the "Hero" of the portfolio section (double width).
    -   Add a specific "AI Badge" to this card.

3.  **Modal Dashboard**
    -   Redesign the project details modal to look like a high-tech "Head-Up Display" (HUD).
    -   Ensure images in modals load lazily and have a skeleton loading state (Engineering proof).

## Sprint 4: Operational Excellence & Engineering Proof
*Focus: Performance, Accessibility, and Mobile perfection (Reviewers check this).*

1.  **Mobile Optimization**
    -   **Thumb Zone Navigation**: Ensure the mobile menu is easily accessible at the bottom or comfortable top-right.
    -   **Touch Targets**: Increase size of all buttons for mobile users.
    -   **No-Jank Scroll**: Ensure the complex background animations stop on mobile to save battery/performance.

2.  **Lighthouse Score Attack**
    -   Add `width` and `height` attributes to all images to prevent Layout Shifts (CLS).
    -   Ensure color contrast meets WCAG AAA (crucial for "Accessibility" skill claim).
    -   Minify CSS/JS where possible.

3.  **Codebase Hygiene**
    -   Remove any remaining unused CSS from the template.
    -   Add clear, professional comments explaining complex logic (for reviewers reading the code).

---
**Ready to start?** I suggest we begin with **Sprint 1** to set the visual tone immediately. Acknowledge to proceed.
