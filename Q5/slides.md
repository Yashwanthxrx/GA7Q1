---
marp: true
theme: custom
paginate: true
---

<!--
Custom theme CSS for Marp
You can customize colors, fonts, etc.
-->
<style>
section {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  color: #333;
  background-color: #f9f9f9;
}
h1, h2, h3 {
  color: #1a237e;
}
footer {
  font-size: 0.8em;
  color: #666;
  text-align: right;
  padding-right: 1em;
  font-style: italic;
}
</style>

<!--
Define the theme for Marp via YAML and CSS
-->
<!--
You can also define CSS variables here if you want to override Marp default theme variables.
-->

<!--
Note: Marp custom themes usually go in separate CSS files, but inline CSS works for simplicity.
-->

<!-- First slide -->
# Product Documentation

**Technical Writer: Your Company**

Contact: <23f3004008@ds.study.iitm.ac.in>

<footer>Page 1</footer>

---

<!-- Slide with background image -->
<!-- Marp directive for background image -->
<!-- The image URL should be accessible locally or via URL -->

<!-- Background image slide -->
<!-- You can replace the URL with any image you want -->

<!-- Use class: lead to make text bigger -->

<!-- Using Marp directive to add background image -->
<!-- Add custom styling below -->

<!--
background-image: url('https://images.unsplash.com/photo-1504384308090-c894fdcc538d?auto=format&fit=crop&w=1350&q=80')
background-size: cover
background-position: center
-->

<!--
Add this directive in YAML for Marp or as a comment above slide
-->

<!-- Slide with background image and overlay for readability -->
<!-- We'll do a dark overlay with CSS on this slide -->

<!-- Markdown slide -->
<!-- Add background image directive in frontmatter for this slide -->

<!-- Using comment style: -->

<!--
_backgroundImage: https://images.unsplash.com/photo-1504384308090-c894fdcc538d?auto=format&fit=crop&w=1350&q=80
_backgroundSize: cover
_backgroundPosition: center
-->

<!-- Marp recommends using comments with underscores for background settings -->

<!-- So putting it together: -->

<!-- Next slide -->

<!--
---
_backgroundImage: https://images.unsplash.com/photo-1504384308090-c894fdcc538d?auto=format&fit=crop&w=1350&q=80
_backgroundSize: cover
_backgroundPosition: center
---
-->

<!-- Now actual content -->

---
_backgroundImage: https://images.unsplash.com/photo-1504384308090-c894fdcc538d?auto=format&fit=crop&w=1350&q=80
_backgroundSize: cover
_backgroundPosition: center
_class: dark-overlay
---

# Key Features

- Easy to maintain documentation
- Supports version control
- Multi-format export (PDF, PPTX, HTML)
- Customizable themes

<footer>Page 2</footer>

<style>
section.dark-overlay {
  position: relative;
  color: white;
}
section.dark-overlay::before {
  content: "";
  position: absolute;
  inset: 0;
  background: rgba(0,0,0,0.5);
  z-index: 0;
}
section.dark-overlay > * {
  position: relative;
  z-index: 1;
}
</style>

---

# Algorithmic Complexity

The time complexity of our main sorting algorithm is given by:

$$
T(n) = O(n \log n)
$$

Where:

- \( n \) = number of elements to sort
- The algorithm efficiently scales for large datasets

<footer>Page 3</footer>

---

# Custom Styling Example

:::info
This slide uses a custom "info" block styled with Marp directives.
:::

<style>
/* Styling for info block */
section .remark-slide-content blockquote.info {
  background: #e8f0fe;
  border-left: 6px solid #1a237e;
  padding: 1em 1.5em;
  color: #1a237e;
  font-style: normal;
  border-radius: 4px;
}
</style>

<footer>Page 4</footer>

---

# Thank You!

For more info contact:

**23f3004008@ds.study.iitm.ac.in**

<footer>Page 5</footer>
