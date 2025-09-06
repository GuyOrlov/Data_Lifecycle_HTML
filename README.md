# Data Lifecycle – Stacked Cards (Power BI HTML)

An accessible, no-JavaScript stacked-card walkthrough of the data lifecycle (Business Understanding → Visualisation). Built for easy embedding in **Power BI** via an HTML measure, and also usable as a standalone web page.

> **Why this?**  
> It’s lightweight (pure HTML/CSS), accessible (screen-reader friendly), and ideal for step-by-step storytelling inside dashboards.

---

## Preview

<!-- Add your own screenshot or GIF here -->
![Preview of stacked cards UI](Screenshot%202025-09-06%20215850.png)

---

## Features

- ✅ **No JavaScript** – works in Power BI’s HTML/HTML Content visuals  
- ✅ **Keyboard & screen-reader friendly** – radio inputs remain accessible  
- ✅ **Responsive** – single column on mobile, two-column layout on larger screens  
- ✅ **Customisable** – colours, stack depth, heights, images, and copy are easy to tweak  
- 🔁 **Looping flow** – last card jumps back to the first for continuous navigation

---

## Quick Start

### Option A — Use in Power BI (recommended)
1. Create a text measure in Power BI called **`Data_Lifecycle_HTML`** and paste the provided string (the version with `Data_Lifecycle_HTML = "…"`).
2. Add an **HTML Content** visual (or your preferred HTML visual) to a report page.
3. Bind the visual to the `Data_Lifecycle_HTML` measure.
4. (Optional) Replace image URLs with org-approved assets or local links via a content proxy.

### Option B — Use as a plain web page
1. Create `index.html`.
2. Copy the *inner HTML* (without the `Data_Lifecycle_HTML =` and outer quotes) into `index.html`.
3. Serve locally with any static server (e.g., VS Code Live Server) or host on GitHub Pages.

---

## Repository Structure

