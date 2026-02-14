# Sudoku Mock Website

A mock Sudoku website built using only HTML and CSS.  
This project demonstrates layout design, navigation structure, and responsive techniques without using any JavaScript or external styling libraries.

---

## 🔗 Live Website

Github Pages Link:  
https://your-username.github.io/sudoku-mock/

---

## 📁 Repository

Github Repo Link:  
https://github.com/your-username/sudoku-mock

---

## 👥 Collaborators

Working individually.

---

## 📄 Project Overview

This website is a static mock implementation of a Sudoku platform.  
It includes multiple pages connected through a persistent navigation bar.  
All pages are built using semantic HTML and modern CSS techniques including Flexbox, Grid, transitions, and media queries etc.
---

## 🧩 Pages Included

- Home Page
- Game Selection Page
- Hard Game Page (9×9 Sudoku grid)
- Easy Game Page (6×6 Sudoku grid)
- Rules Page
- High Scores Page
- Login Page
- Register Page

---

## 📱 Responsive Design

- Desktop view
- iPhone 12 Pro size (tested using Chrome DevTools)

On mobile:
- The navbar moves to the bottom of the screen
- Content spacing adjusts automatically
- Sudoku grids scale to fit smaller screens

---

## 📹 Demo Video



---

## 📌 Notes

- All pages use folder-based routing (e.g., `/selection/`) to avoid `.html` appearing in URLs.
- Global styles are stored in `/css/global.css`.


### Write UP ###
1️⃣ What was the most challenging piece of this assignment?

The most challenging part of this assignment was not the overall structure, but the small visual details. Basic HTML layout was straightforward, but making the interface feel polished using only CSS required more experimentation than I expected. For example, implementing hover effects that felt subtle and professional — without being distracting — took several iterations. I had to carefully adjust transitions, transform scaling, and color contrast so that interactive elements felt responsive but not overwhelming.

Another challenge was styling the Sudoku board itself. Although it is just a grid visually, properly separating subgrids and ensuring consistent spacing across screen sizes required precise CSS structure. Making simple components look clean and intentional was harder than I initially assumed.


2️⃣ What decisions did you make when you made your site mobile friendly?

For mobile design, I wanted to preserve the same accessibility as the desktop version rather than hiding navigation options. Instead of collapsing everything into a hamburger menu, I designed the navbar so that users can scroll horizontally to access the same sections as on desktop. This prevents users from worrying about losing access to specific pages and keeps navigation consistent across devices.

I also moved the navigation bar to the bottom of the screen on smaller devices. This improves reachability on mobile and prevents overcrowding at the top of the screen. Spacing adjustments were added to ensure that content would not be hidden behind the fixed navigation bar.

Testing was performed using the iPhone 12 Pro simulation in Chrome DevTools to ensure consistent usability.

3️⃣ What did you take into account when you developed the design of your website?

When developing the design, I focused heavily on readability and long-term visual comfort. I chose a dark background theme to reduce eye strain, especially since Sudoku involves extended visual focus. The contrast between text and background was carefully balanced to avoid overly bright or harsh tones while still maintaining clarity.

I also introduced subtle hover animations and smooth transitions to give the interface a more modern feel. These micro-interactions help guide users visually without relying on JavaScript.


4️⃣ Given more time or resources, what additional features would you add?

Given more time, I would enhance the mock design by visually incorporating a “used numbers” section that displays which digits have already been placed on the board. This would help users track progress more easily.

I would also design a visual conflict highlighting system. If a number violates Sudoku rules (for example, duplicating a value within the same row, column, or subgrid), the conflicting cells would be highlighted. Although this assignment does not require interactive logic, implementing this feature in the future would significantly improve usability and game clarity.

5️⃣ How many hours did you spend on this assignment?

Approximately 24 hours.

6️⃣ Assumptions (Optional)

For assumptions, I assumed that the 6×6 Sudoku board would use a 2×3 subgrid structure. I also assumed that the timer and conflict detection did not need to be fully functional for this mock stage.

7️⃣ External Resources Used

MDN Web Docs for CSS reference,
Google Inter Font




