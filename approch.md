You’re **progressing exactly the right way**.
This new assignment is not harder than the last one — it’s **broader**, not deeper.

I’ll explain **how to approach it like a frontend engineer**, not like a tutorial follower.

---

Now this new task is about:

> “Can you design a REAL product page structure and keep it clean, responsive, and polished?”

---

# 1️⃣ How NOT to approach this ❌ (important)

Don’t:

- Start writing CSS randomly
- Copy a landing page design pixel-by-pixel
- Try to be fancy with gradients/animations
- Jump into JS early

This will slow you down and create messy code.

---

# 2️⃣ Correct Mental Model (THIS IS KEY)

Think in **layers**, not sections.

### Layer 1 – Structure (HTML)

> “Does this page make sense with CSS turned off?”

### Layer 2 – Layout (Flexbox)

> “Can this layout adapt to different screen sizes?”

### Layer 3 – Visual polish (CSS)

> “Is spacing, contrast, hierarchy clear?”

### Layer 4 – Motion (Transitions & animation)

> “Does it feel smooth and intentional?”

### Layer 5 – Minimal JS

> “Do small interactions enhance UX?”

You move **top → bottom**, not randomly.

---

# 3️⃣ Step-by-Step Approach (DO THIS IN ORDER)

## STEP 1: Plan the page (10 minutes, no code)

On paper or notes, define this structure:

```
<header>
  nav
</header>

<main>
  <section class="hero"></section>
  <section class="features"></section>
  <section class="pricing"></section>
</main>

<footer></footer>
```

If you can’t describe the page in words, don’t code yet.

---

## STEP 2: Write ONLY semantic HTML (30–40 mins)

No CSS at first except maybe `font-family`.

Use:

- `<header>`, `<nav>`
- `<main>`, `<section>`
- `<article>` for feature & pricing cards
- `<footer>`

At this stage:

- Everything will look ugly
- That’s GOOD

You’re building **structure**, not beauty.

---

## STEP 3: Layout with Flexbox (MOST IMPORTANT)

### Navigation bar

- `display: flex`
- `justify-content: space-between`
- logo left, links middle/right, button right

### Hero section

- Two columns (text + image)
- On mobile → stack column

### Features section

- Flex container
- 3 cards
- `flex-wrap: wrap`

### Pricing section

- Similar to features
- Cards should be same height

📌 Rule:

> If Grid feels tempting, DON’T use it yet. Flexbox only.

---

## STEP 4: Add spacing & hierarchy (THIS MAKES IT LOOK “REAL”)

Focus on:

- Section padding (top/bottom)
- Gap between cards
- Font size differences:

  - Product name (big)
  - Section titles (medium)
  - Body text (small)

Ask yourself:

> “Where should the eye go first?”

---

## STEP 5: Hover effects (simple but consistent)

### Cards:

- `transform: translateY(-6px)`
- Shadow increase
- Smooth transition

### Buttons:

- Background color change
- Slight scale OR darker shade

Consistency > creativity.

---

## STEP 6: Page load animation (keep it minimal)

Use **one keyframe animation only**.

Example ideas:

- Hero section fades + slides up
- Cards fade in

This is enough to tick the checkbox.

---

## STEP 7: Responsiveness (don’t overthink)

You only need:

- `max-width`
- `flex-wrap`
- One media query (e.g. `max-width: 768px`)

If:

- Text doesn’t overflow
- Cards stack
- Buttons remain clickable

You win.

---

## STEP 8: Minimal JavaScript (VERY LIGHT)

They said “a little JS”.

Good options:

- Add/remove class on page load
- Smooth scroll to sections
- Button click console log

Do NOT:

- Build sliders
- Overengineer

---

# 4️⃣ How they will evaluate you (read carefully)

They are NOT checking:
❌ Business logic
❌ Complex JS
❌ Framework knowledge

They ARE checking:
✅ Can you structure a page
✅ Can you manage spacing
✅ Can you use Flexbox correctly
✅ Can you animate intentionally
✅ Does it look like a real website

If it **feels clean**, you pass.

---

# 5️⃣ What would impress them (without extra effort)

If you:

- Use semantic tags correctly
- Keep CSS readable
- Use consistent spacing
- Add smooth hover effects
- Don’t break mobile layout

They’ll think:

> “This person understands frontend fundamentals.”

That’s exactly what they want.

---

# 6️⃣ Suggested execution timeline

**Day 1**

- HTML structure
- Basic layout with Flexbox

**Day 2**

- Styling
- Hover effects
- Responsiveness
- One animation
- Clean up code

---

# 7️⃣ Final mindset (important)

This is not a test of speed.
It’s a test of **clarity + discipline**.

You’re already doing:

- Iteration
- Taking feedback
- Improving structure

That puts you **ahead of most interns**.

---

TASK:
Product Landing Page
The goal of this task is to build a simple product landing page using HTML, CSS and a little JavaScript.
This is meant to look like a real company website, not a demo page.

You should focus on layout, spacing, responsiveness, and smooth UI effects.

What to build

Create a single page with these sections:

A top navigation bar
A hero section
A features section
A pricing section

Navigation Bar

Include:
A logo or product name
Three links (Home, Features, Pricing)
One action button (Get Started / Sign Up)

Hero Section

This should include:
Product name
A short one-line description
A main button (like “Start Free Trial”)
A product image or placeholder

Add a simple animation when the page loads.

Features Section
Create three feature cards. Each card should have:
An icon or emoji
A title
A short description

On hover, the card should lift slightly and show a shadow or color change or better ideas are encouraged.

Pricing Section
Create three plans (Free, Pro, Enterprise).Each plan should show:
Plan name
Price
A few bullet points
A button

On hover, the card should highlight and the button should change style.

Responsive Design

On smaller screens:
Sections should stack vertically
Layout should not break or overflow

Animations & Effects

Use CSS transitions and transforms for:
Card hover
Button hover
Page load animation

At least one keyframe animation should be used.

What will be checked:
Use of Flexbox
Clean spacing and alignment
Mobile layout
Hover and animation effects
Overall UI quality
