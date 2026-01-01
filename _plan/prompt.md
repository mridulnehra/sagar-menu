**Project:** Mobile-First Digital Menu for "Sagar" (Restaurant).
**Tech Stack:** HTML, CSS, Vanilla JS (Single file or separated).
**Design Style:** Replicate the "Bella" UI layout (Modern, Centered, Clean).

**Instructions:**
Create a responsive, mobile-optimized web page with two distinct views (Splash Screen & Menu Feed). Use CSS Variables for colors so I can match my logo later.

**1. CSS Variables (Default Palette):**
- `--primary-color`: #2E8B57 (Garden Green - for buttons/active states)
- `--accent-color`: #F4B400 (Mustard - for prices/stars)
- `--bg-color`: #FFFFFF (White)
- `--text-main`: #333333
- `--text-light`: #888888

**2. View 1: The Landing/Splash Screen (Full Height)**
- **Layout:** Centered content on a clean background (or background image with overlay).
- **Elements:**
  - Large Logo Placeholder (Img tag with class `logo-splash`).
  - Heading: "Welcome to Sagar".
  - Button: Large, wide "View Menu" button at the bottom third.
- **Interaction:** Clicking "View Menu" slides this view up/away to reveal View 2.

**3. View 2: The Menu Feed (Bella Style Layout)**
- **Header:** Sticky top bar containing a rounded "Search" input field.
- **Filters (Row 1):** Two clickable toggles side-by-side: "🔴 Non-veg" and "🟢 Veg".
- **Categories (Row 2):** Horizontal scrolling text links (Starters, Main Course, Drinks). Active category has a thick underline.
- **Dish List:** Vertical scrolling list.
  - **Card Design:**
    - Image: Large, Centered, Circular Image (border-radius: 50%, width: 180px, shadow).
    - Content: Centered text below the image.
    - Title: Bold, Dark.
    - Description: Light gray, max 2 lines.
    - Tags: Small icons for Veg/Non-Veg + "Chef's Fav" Star Badge.
    - Price: Bold, Accent Color.
    - Button: "Add" pill-shaped button.

**4. Data & Logic:**
- Create a `const menuItems` array with 5 sample items (mix of Veg/Non-Veg).
- Implement the "Veg/Non-Veg" filter logic (hide items that don't match).
- Implement the Search bar logic (filter by name).
- Use `loading="lazy"` on all images.

**5. Image Handling:**
- Use generic placeholders (e.g., `https://placehold.co/400`) for now.
- Add comments in the code: `` so I know where to drop my files.

**6. Hosting:**
- Deploy on GitHub Pages.
- Use GitHub Actions for CI/CD.

**7. Additional Notes:**
- Use comments in the code: `` so I know where to drop my files.
- all views are mobile responsive and work well on mobile devices,tablets and desktops
- all views are dark and light mode friendly
- start by asking me to provide the logo and menu items 
- start by asking me clarifying questions to understand the project better
