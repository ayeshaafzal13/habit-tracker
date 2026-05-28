# Assessment Answers

## 1. How to Run

Open `index.html` in any web browser. Double click the file. No installation needed.

## 2. Stack & Design

**Stack:** Plain HTML/CSS/JS - No frameworks, runs anywhere.

**Design decisions:**
- Week starts Monday (work week alignment)
- Today column has orange highlight (instant orientation)
- Horizontal scroll on mobile (keep 7-day view)

## 3. Responsive & Accessibility

**Responsive:** On phone (360px) - table scrolls sideways, buttons stack. On laptop (1440px) - full view.

**Accessibility:** Keyboard tab works on checkboxes. Focus states visible. Color contrast meets WCAG.

**Skipped:** Screen reader announcements (would be noisy for streak updates)

## 4. AI Usage

Used ChatGPT to understand streak calculation and localStorage. 

Changed AI's recursive streak function to a simple loop for easier debugging. AI gave complex table responsive solution; I used simple overflow-x:auto instead.

## 5. Honest Gap

No edit habit feature. You must delete and re-add to rename.

**Fix with another day:** Add edit button that pops up prompt to rename without losing history.