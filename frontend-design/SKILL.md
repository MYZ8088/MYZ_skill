---
name: MYZ-frontend-design
description: Create distinctive, production-grade frontend interfaces with high design quality. Use this skill when the user asks to build web components, pages, or applications. Generates creative, polished code that avoids generic AI aesthetics.
license: Complete terms in LICENSE.txt
---

This skill guides creation of distinctive, production-grade frontend interfaces that avoid generic "AI slop" aesthetics. Implement real working code with exceptional attention to aesthetic details and creative choices.

The user provides frontend requirements: a component, page, application, or interface to build. They may include context about the purpose, audience, or technical constraints.

## Design Thinking

Before coding, understand the context and commit to a BOLD aesthetic direction:
- **Purpose**: What problem does this interface solve? Who uses it?
- **Tone**: Pick an extreme: brutally minimal, maximalist chaos, retro-futuristic, organic/natural, luxury/refined, playful/toy-like, editorial/magazine, brutalist/raw, art deco/geometric, soft/pastel, industrial/utilitarian, etc. There are so many flavors to choose from. Use these for inspiration but design one that is true to the aesthetic direction.
- **Constraints**: Technical requirements (framework, performance, accessibility).
- **Differentiation**: What makes this UNFORGETTABLE? What's the one thing someone will remember?

**CRITICAL**: Choose a clear conceptual direction and execute it with precision. Bold maximalism and refined minimalism both work - the key is intentionality, not intensity.

Then implement working code (HTML/CSS/JS, React, Vue, etc.) that is:
- Production-grade and functional
- Visually striking and memorable
- Cohesive with a clear aesthetic point-of-view
- Meticulously refined in every detail

## Frontend Aesthetics Guidelines

Focus on:
- **Typography**: Choose fonts that are beautiful, unique, and interesting. Avoid generic fonts like Arial and Inter; opt instead for distinctive choices that elevate the frontend's aesthetics; unexpected, characterful font choices. Pair a distinctive display font with a refined body font.
- **Color & Theme**: Commit to a cohesive aesthetic. Use CSS variables for consistency. Dominant colors with sharp accents outperform timid, evenly-distributed palettes.
- **Motion**: Use animations for effects and micro-interactions. Prioritize CSS-only solutions for HTML. Use Motion library for React when available. Focus on high-impact moments: one well-orchestrated page load with staggered reveals (animation-delay) creates more delight than scattered micro-interactions. Use scroll-triggering and hover states that surprise.
- **Spatial Composition**: Unexpected layouts. Asymmetry. Overlap. Diagonal flow. Grid-breaking elements. Generous negative space OR controlled density.
- **Backgrounds & Visual Details**: Create atmosphere and depth rather than defaulting to solid colors. Add contextual effects and textures that match the overall aesthetic. Apply creative forms like gradient meshes, noise textures, geometric patterns, layered transparencies, dramatic shadows, decorative borders, custom cursors, and grain overlays.

NEVER use generic AI-generated aesthetics like overused font families (Inter, Roboto, Arial, system fonts), cliched color schemes (particularly purple gradients on white backgrounds), predictable layouts and component patterns, and cookie-cutter design that lacks context-specific character.

Interpret creatively and make unexpected choices that feel genuinely designed for the context. No design should be the same. Vary between light and dark themes, different fonts, different aesthetics. NEVER converge on common choices (Space Grotesk, for example) across generations.

**IMPORTANT**: Match implementation complexity to the aesthetic vision. Maximalist designs need elaborate code with extensive animations and effects. Minimalist or refined designs need restraint, precision, and careful attention to spacing, typography, and subtle details. Elegance comes from executing the vision well.

Remember: Claude is capable of extraordinary creative work. Don't hold back, show what can truly be created when thinking outside the box and committing fully to a distinctive vision.

---

## Project Reference: issueDesign

### Core Identity: Warm Organic Glassmorphism

This design pursues **warm lightness** — soft and inviting like sunlight through sheer curtains, not cold enterprise software. It creates an interface that feels like a warm analyst companion rather than a cold server.

### Design Principles

**[Principle 1] Background as Atmosphere, Layers as Depth**
- Background is not a plain canvas but a slowly breathing gradient
- Glassmorphic cards float on it, creating z-axis depth
- Warm gradient (e.g., orange → rose) defines the emotional tone
- The entire UI exists in a "living" state with subtle motion

**[Principle 2] Color as Signal, Not Decoration**
- Primary brand gradient is the universal signal color
- Used for CTAs (most important actions), progress (ongoing processes), highlights (core value)
- Subtle warm gradient in background sets emotional baseline
- Color hierarchy: warm neutrals for base, vibrant accent for emphasis

**[Principle 3] State as Animation, Process as Experience**
- Loading states include complete feedback system (progress + percentage + description)
- Users always know what the system is doing and at which stage
- "Transparent process" is the core promise — eliminate uncertainty anxiety

**[Principle 4] Interaction as Touch**
- Every interactive element has subtle physical feedback: lift, scale, shadow deepen
- Gives digital interfaces a tactile quality
- Navigation hides/shows on scroll, saving space while maintaining context
- Hover states should feel like pressing a soft button

**[Principle 5] Progressive Information Delivery**
- Content reveals progressively on scroll, list items enter in sequence
- Creates "exploration" rather than "browsing" feel
- Guides attention order, avoids information overload

### Design Language

**Glassmorphism**
- Frosted glass: `backdrop-blur-md` with semi-transparent backgrounds
- Subtle borders: translucent whites or brand-tinted borders
- Soft shadows that deepen on interaction
- Cards appear to float above the background

**Color System**
- Warm primary gradient (warm tones like orange-rose/peach, not purple-blue)
- Light warm gradient backgrounds
- Semi-transparent white base for surfaces
- Text hierarchy: dark gray (headings) → medium gray (body) → light gray (secondary)
- Semantic colors: rose/warm tones (emphasis), blue (details), purple (actions)

**Motion Philosophy: Motion as Communication**
- Entrance animations: establish spatial sense and guide focus
- Staggered animations: reveal attention sequence
- Progress animations: eliminate uncertainty
- State transitions: provide tactile feedback
- Technology: unified motion library (framer-motion recommended)

**Tactile Feedback**
- Hover: subtle lift + slight scale + shadow deepening
- Buttons have spring-like scaling effects
- Custom scrollbar integrates brand color as subtle accent

**Spacing Strategy**
- Overall "generous" with breathing room
- Adequate page-level padding for comfortable margins
- Card padding adjusts by content density
- Form elements have breathing space between them

**Input Design**
- Not pure white background, but light brand-tinted background
- Focus state with darker/different border color
- Visually blends with card background while remaining distinct