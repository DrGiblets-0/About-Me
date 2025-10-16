# Mini-Project: Bio Page from Screenshot

## Objective
Recreate a simple **one-page bio** from the provided screenshot mockup using HTML + CSS.
This is a *visual-matching* exercise (reasonable approximation) using **plain selectors only**.

## Provided
- `Unsolved/mockups/bio-wireframe.png` (screenshot to emulate)
- Starter files in `Unsolved/` with empty CSS shell and basic HTML structure

## Tasks
1. Open `Unsolved/index.html` and `css/styles.css`.
2. Structure the page to match the screenshot sections:
   - Header with your name and role (e.g., "Student • Web Beginner").
   - A left column with a photo and quick info (email or links as plain text).
   - A right column with sections: About, Skills (simple list), and Links.
3. Use **plain selectors** only (`*`, `h1`, `.class`, `#id`). No pseudo-classes yet.
4. Layout with **widths, margins, and display** (avoid flex/grid this week).
5. Keep colors/typography simple but readable.

## Acceptance Criteria
- Header, left, and right sections are present in the correct order.
- Typography sizes are sensible (h1 bigger than section headings, etc.).
- A local image `assets/profile.jpg` is displayed.
- The overall look is recognizably similar to the screenshot.
- No advanced selectors or layout systems used.

## Tips
- Set a fixed `max-width` for the page and center it with margins.
- Use `display: inline-block` for two-column effect (left and right).
- Add spacing with `padding` and `margin` to separate sections.
