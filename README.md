# Velocity Script Collection
During my work with Cascade CMS, I developed a collection of reusable Velocity scripts to solve repetitive templating challenges. This library includes solutions for sorting content, handling dynamic image paths, generating social media metadata, alternating layouts, and building structured course catalogs — all designed with clarity, reusability, and performance in mind.

---

## 📸 dynamic-picture
Dynamically replaces part of the image path string to switch between formats (e.g., full to cropped). Useful for responsive or alternate image display scenarios.

---

## 📘 velocity-format-facebook
Generates dynamic Open Graph metadata for Facebook sharing.  
✔️ Pulls custom image and description from the page’s `facebookContent` region if available.  
❌ Falls back to default image and description if not provided.

---

## 🔀 velocity-format-even-odd
Alternates between two CSS classes (e.g., `newsLeft` / `newsRight`) based on the index within a `#foreach` loop. Ideal for creating visually balanced layouts.

---

## 📂 sort-folder-elements
Sorts and displays pages from the current folder based on custom metadata such as `title`, `judgments`, or `code`.  
➡️ Requires the **Current Folder XML block** assigned to the correct region.

---

## 📚 course-catalog-program-script
Displays a structured list of courses for a specific program.  
Includes expandable requirements with course details and prerequisites.  
⚙️ Requires an **Index Block** configured on the calling page.

---

## ▶️ next-page-format
Enables navigation between sibling pages using clickable previous/next icons.  
Requires the **Current Folder Block** to determine sequence.

---

## 🗂 category-index-page
Pulls and displays metadata from subcategory pages (excluding `index`) and splits them into two alternating columns.  
✔️ Requires an **Index Block** on the current folder.

---

### 💡 Notes
- All snippets assume XPath-based access to Cascade CMS structured content.
- You can mix and match these scripts across templates depending on region configurations.
- Each script is production-tested and modular for adaptation.

---

### 📁 License
This repository is shared for educational and portfolio purposes.

