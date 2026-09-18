# Personal Budget Tracker - Week 2 Project

A semantic HTML5 and styled CSS application for tracking everyday expenses, built as part of the Week 2 Web Development Assignment.

## Features & Implementation Details

### 1. Structured Expense Table
* Implemented using semantic `<table>`, `<thead>`, `<tbody>`, `<tr>`, `<th>`, and `<td>` tags.
* Contains 5 hardcoded initial sample expense rows.
* Styled in CSS using `border-collapse: collapse`, cell padding, custom header colors, and alternating zebra stripes using `tr:nth-child(even)`.

### 2. Upgraded Add Expense Form
* Enclosed all input controls inside a proper `<form>` element.
* Added a `<select>` dropdown populated with 5 category options (`Food`, `Transport`, `Rent`, `Entertainment`, `Other`).
* Configured clear `id` attributes on all form fields (`expense-name`, `expense-amount`, `expense-category`, `expense-date`) for future JavaScript integrations.
* Added a standalone `<button type="button">` labeled "Add Expense".

### 3. Multimedia Integration
* **Logo Image**: Integrated a visual header logo using an `<img>` tag with complete `src`, `alt`, and `width` attributes.
* **Embedded Video**: Incorporated a helpful YouTube video on financial management using an `<iframe>` configured with standard attributes (`width`, `height`, `title`, `frameborder`, `allow`).

### 4. Interactive Elements
* Added an expandable `<details>` section with a `<summary>` element providing instructions on how to use the tracker.
* Added interactive `:hover` state transition rules on table rows (`tr:hover`).
* Set `cursor: pointer` on form elements and summary triggers for improved UX feedback.

### 5. Advanced CSS Selectors Applied
* **Descendant Selector**: `.expenses-section td` for targeted cell styling.
* **Pseudo-Class based on Position**: `tr:nth-child(even)` for table striping.
* **Focus State**: `input:focus, select:focus` for active field highlight styling.
* **Negation Pseudo-Class**: `input:not([type="button"])` to style all data text input elements simultaneously without altering buttons.

# Budget Tracker - Visual Design Enhancement

## Description
This project enhances the visual appearance of the Budget Tracker web application using CSS. The focus of this update is to improve readability, apply a cohesive design system, and implement modern layout principles without altering the existing HTML structure.

## What Was Built & Applied
1. **Intentional Color Palette:** 
   - Uses CSS custom properties (`:root`) for consistency.
   - Primary Accent: Indigo (`#4f46e5`) for buttons and headers.
   - Backgrounds: Light gray (`#f3f4f6`) with crisp white card containers (`#ffffff`).
2. **Typography:**
   - Integrated **Poppins** for headings and **Inter** for readable body text via Google Fonts.
3. **Table & Form Styling:**
   - Input fields and buttons feature padding, focus states, and rounded corners (`border-radius`).
   - Tables include alternating row shading (`nth-child(even)`), structured cell padding, and explicit header styling.
4. **CSS Box Model:**
   - Applied margins, padding, subtle shadows, and borders to convert the header, form, and table into distinct visual "cards."