# Técnico en Casa – Interactive Guide for Faucet Repair

This website offers a visual, step-by-step guide to changing the o-ring of a household faucet. Designed for non-technical users, it combines instructions, tool tips, a feedback form, and an embedded video to guide the repair process.

---

## 🚀 Project Goal

Help anyone perform a basic home plumbing repair independently, without needing prior technical knowledge.

---

## 🧑‍💻 Original Author

**Iván Szilavecz**  
Creator of the original HTML and CSS structure, content, and visual concept for the site.

---

## 🛠️ Corrections and Enhancements by Nicolás Bugedo (@caimanbrujo)

I joined the project to improve its structure, fix semantic and visual issues, and leave the site production-ready. Here are the main changes I made:

### 🧱 HTML Fixes

- ✅ Removed invalid elements like `<p2>` and improper class names like `"h2"`.
- ✅ Cleaned up list structures (`<ul>`, `<ol>`) and applied semantic best practices.
- ✅ Added proper `id`s to sections for internal navigation.
- ✅ Implemented a functional `<nav>` menu with anchor links.
- ✅ Added a structured `<footer>` with links and legal info.

### 🎨 CSS Improvements

- ✅ Replaced `rgba()` with hex+alpha (`#000000b2`, `#ffffff40`) for cleaner color code.
- ✅ Standardized spacing across all sections using consistent `padding` and `margin`.
- ✅ Refactored the header to remove unnecessary Flexbox and use simpler layout.
- ✅ Centered blocks like the procedure list, while keeping content left-aligned for readability.
- ✅ Added hover effects to tool buttons to show an image preview.
- ✅ Fixed invalid or unnecessary CSS like `margin: absolute;`.
- ✅ Added visual separators (`.separador`) with height and background color.

---

## 📦 Website Sections

- **Header**: With background image and centered title.
- **Navigation**: Internal links to tools, procedure, and feedback.
- **Tools**: Interactive buttons with image previews.
- **Procedure**: Numbered list with clear formatting and spacing.
- **Survey**: Form with required name/email and optional feedback.
- **Video**: Embedded and centered YouTube video.
- **Footer**: Instagram and WhatsApp links, and copyright.

---

## 📚 Technologies Used

- HTML5
- CSS3 (Flexbox, semantic elements, Google Fonts)
- YouTube embed (iframe)