# Module 3 Coding Assignment — Food, LLC

This submission implements **only the graded, required portion** of the provided Coursera Module 3 assignment. The later three-section Chicken/Beef/Sushi version is explicitly marked as optional and ungraded in the instructions and is intentionally not mixed into this solution.

## Preview

Open `index.html` in a browser. Everything works **offline** because Bootstrap 3.4.1, jQuery, and Bootstrap's JavaScript are included locally.

- **Desktop / tablet (at least 768px):** The header shows only “Food, LLC”; the heading is centered; the page has one full-width, tall menu section.
- **Mobile (under 768px):** A three-bar button appears. Click it to open and close a full-width, contrasting menu with Chicken, Beef, and Sushi.
- **All screen sizes:** The navbar scrolls away (it is not fixed), and the single `col-xs-12` section remains full width within the Bootstrap grid.

## Files

```text
module3-solution/
├── index.html
├── css/
│   ├── bootstrap.min.css   (Bootstrap v3.4.1)
│   └── styles.css          (assignment styles)
├── js/
│   ├── jquery.min.js       (jQuery v3.7.1)
│   └── bootstrap.min.js    (Bootstrap v3.4.1)
└── README.md
```

## Submit to GitHub Pages

1. Add the entire `module3-solution` folder to your class GitHub repository.
2. In the repository's **Settings → Pages**, publish from the branch containing the folder (often `main`, root).
3. Your peer-review URL will look like `https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/module3-solution/`.
4. Check that the link opens and that the menu works when you narrow the browser window.

The three mobile menu labels navigate to the single graded menu section. The assignment only requires the three labels and the dropdown behavior; linking each label to a separate section belongs to the optional ungraded part.
