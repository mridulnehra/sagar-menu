Product Overview: Sagar Digital Menu
1. Project Mission
To build a high-performance, mobile-first digital menu for "Sagar" (formerly Shahar Garden Café & Kitchen). The goal is to replace physical menus with a fast, interactive QR-code web experience that highlights the visual appeal of the food.

2. Core Features
Scan-to-View: Instant access via QR code.

Dual-View Experience:

Splash Screen: Builds brand ambiance.

Menu Feed: A vertical scroll "feed" of dishes (Instagram-style).

Smart Filtering:

Veg/Non-Veg Toggles: Instantly hides irrelevant dietary options.

Categories: Horizontal scroll (Starters, Main Course, Drinks).

Search: Real-time text filtering.

Visual Badging: "Chef's Favourite" stars and Spicy indicators.

3. Design System ("The Bella Aesthetic")
The UI follows a modern, centered layout focusing on "appetite appeal."

Color Palette:

Primary (Action): #2E8B57 (Garden Green) - Used for buttons, active states, and dish titles.

Accent (Value): #F4B400 (Mustard Yellow) - Used for prices and star badges.

Background: #FFFFFF (Pure White) - Ensures maximum contrast.

Text: #333333 (Charcoal) for readability.

Typography: Clean Sans-Serif (e.g., Poppins, Inter, or Open Sans).

Card Layout:

Images: Large, circular images (border-radius: 50%) with soft drop shadows to create a "plate" effect.

Alignment: All text (Title, Desc, Price) is centered below the image.

4. User Flow
Entry: User scans QR code.

Splash Screen: User sees the "Sagar" logo and a "View Menu" button on a clean/branded background.

Transition: Clicking "View Menu" slides the splash screen away.

Discovery: User sees the Search bar and Veg/Non-Veg toggles at the top.

Selection: User scrolls through circular dish images. They can click "Add" (visual feedback only) or browse categories.

5. Technical Implementation
Stack: HTML5, CSS3, Vanilla JavaScript (No frameworks).

Hosting: GitHub Pages (Static hosting).

Performance:

Images: WebP format, max-width 400px.

Loading: Native loading="lazy" attribute on all dish images.

Data Source: A local JSON array (menu-data.js) for easy updating.

6. Data Structure (JSON Schema)
The menu data will follow this strict schema:

JSON

[
  {
    "id": 1,
    "name": "Paneer Tikka",
    "category": "Starters",
    "price": 240,
    "isVeg": true,
    "isChefFav": true,
    "description": "Cottage cheese marinated in indian spices and grilled to perfection.",
    "image": "./assets/images/paneer-tikka.webp"
  }
]
7. Asset Strategy
Logo: logo.png (To be provided by user).

Dish Photos: Stored in assets/images/. User will convert these to WebP for speed.

Icons: Use SVG or Unicode characters (🟩, 🟥, ⭐) to reduce HTTP requests.