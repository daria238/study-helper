# Flashcard Master — UI Style Guide (Design Tokens)

This document outlines the **colors, typography, and component styles** based on the provided UI screenshot.

---

## 1) Color Palette

### Primary (Brand / CTA)
Used for: primary buttons, “Add Subject”, “Create Subject”, app icon background.

- **Primary:** `#2563EB` (blue-600)
- **Primary Hover:** `#1D4ED8` (blue-700)
- **Primary Active:** `#1E40AF` (blue-800)
- **On Primary (Text/Icon):** `#FFFFFF`

---

### Backgrounds
- **Page Background:** `#F8FAFC` (slate-50)
- **Surface / Card Background:** `#FFFFFF`

---

### Borders / Dividers
- **Border:** `#E5E7EB` (gray-200)

---

### Text
- **Text (Main / Headings):** `#0F172A` (slate-900)
- **Text (Muted / Secondary):** `#64748B` (slate-500)

---

### Optional (Illustration / Empty State)
The empty-state icon uses accent colors (green/red/blue) that are **decorative**, not core UI tokens.

---

## 2) Typography

### Font Family
Recommended stack (matches modern SaaS dashboards):

```css
font-family: Inter, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
