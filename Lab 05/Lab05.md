# Lab 05: Links and Images

**Course:** HTML & CSS Development Lab (BCS554)  
**Student Name:** Mohd Javed Khan  
## Student ID :- LBCS2025023 **

---

## 🎯 Aim
Establish inter-page navigation between multiple HTML documents using anchor (`<a>`) tags and integrate images using explicit dimension attributes and descriptive fallback `alt` text.

---

## 📄 Tasks Completed

### Task 1: Home Page with External Link (`home.html`)
Created `home.html` featuring a hyperlink targeting `portfolio.html`.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Home Page</title>
</head>
<body>
    <h1>Welcome to My Site</h1>
    <p>Check out my <a href="portfolio.html">portfolio</a>.</p>
</body>
</html>
```

---

### Task 2: Target Page with Return Link (`portfolio.html`)
Created `portfolio.html` containing reciprocal navigation pointing back to `home.html`.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Portfolio Page</title>
</head>
<body>
    <h1>My Portfolio</h1>
    <p><a href="home.html">Back to Home</a></p>
</body>
</html>
```

---

### Task 3: Embedded Image Component (`portfolio-image.html`)
Embedded an image from a relative subfolder path (`images/`), explicitly defining explicit `width="200"`, `height="200"`, and accessibility `alt` text.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Portfolio Image</title>
</head>
<body>
    <h1>My Portfolio Photo</h1>
    <img src="./Images/MRKHAN08.png" width="200" height="200" alt="Sample portfolio image display">
</body>
</html>
```

---
## 📁 File Structure
```text
Lab 05/
├── home.html              # Task 1 HTML page
├── portfolio.html         # Task 2 HTML page
├── portfolio-image.html   # Task 3 HTML page
├── images/                # Assets directory
│   └── sample.jpg         # Portfolio image asset
└── README.md              # Lab 05 documentation
```