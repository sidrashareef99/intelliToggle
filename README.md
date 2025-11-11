# IntelliToggle HomePage
A recreation of a Figma design for a home page built with Twig and TailwindCSS.


## Technologies Used

---
- HTML
- TailwindCSS
- JavaScript (for mobile menu toggle)
- Images/assets from original Figma design

## Setup

----


1. Clone repository:
    ```bash
   git clone https://github.com/sidrashareef99/intelliToggle
   ```
2. Navigate to project directory: 
    ```bash
    cd intelliToggle
   ```
3. Install dependencies (Twig, if you’re using Composer):
    ```bash
    composer install
    ```

4. Start a local PHP server:
    ```bash
    php -S localhost:8000
    ```

5. Open your browser and go to  http://localhost:8000 

## Tailwind CSS

1. Install Tailwind:

```bash
    npm install -D tailwindcss 
    npx tailwindcss init 
```
2. Compile Tailwind:
```bash
  npx tailwindcss -i src/tailwind.css -o public/tailwind.css
```

---

## Pixelay Usage

1. Open the page in your browser
2. Go to Figma right click on frame you want to compare
3. Go to Plugin
4. Enter localhost url 
5. Generate link
6. Screenshot full browser


## Pixelay Screenshots

---

**Desktop Overlay:**


![Desktop Comparison](pixelay/pixelay_desktop_split_screen_overlay.png)

---

![Desktop Comparison](pixelay/pixelay_desktop_transparent_overlay.png)

---

**Mobile Overlay:**

![Mobile Comparison](pixelay/pixelay_mobile_split_screeen_overlay.png)

---

![Mobile Comparison](pixelay/pixelay_mobile_transparent_overlay.png)


## Tips: 

--- 
- Avoid unnecessary absolute positioning for Pixelay overlay
- Use responsive Tailwind classes (px-4 md:px-10) for proper seamlessness
- Use w-full max-w-md for images to scale them properly on different screens

## Notes:

---

- Pixelay did a good job of helping to see what needed to be adjusted but hard coded sizes makes it hard for responsiveness.
- Javascript toggle for mobile menu allows for seamless transition between larger and smaleer screens.
- Sections are designed for responsiveness, but spacing and alignment needs adjustment.
- Fonts and colors don't exactly match that of Figma design

## Future Improvements

---
- Fix sizing and alignments issues
- Match colors and obtain assets to enhance backgrounds and other design features
- Add JavaScript Functionality to other components and improve existing toggle menu with animation
- Build different style mode for personalized experience. 
