# Lab 04: Divs, Attributes and a Small Fix

**Course:** HTML & CSS Development Lab (BCS554)  
**Student Name:** Mohd Javed Khan  
## Student ID :- LBCS2025023 **

---

## 🎯 Aim
Group content using structural `<div>` block containers, apply custom HTML5 `data-*` attributes, and inspect/debug invalid HTML markup syntax.

---

## 📄 Tasks Completed

### Task 1: Structural Page Sections (`layout.html`)
Organized content into distinct structural blocks using `<div>` elements assigned with class attributes (`header`, `main`, and `footer`).

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Layout Demo</title>
</head>
<body>
    <div class="header">
        <h1>Header Section</h1>
    </div>
    <div class="main">
        <p>Main content section of the page.</p>
    </div>
    <div class="footer">
        <p>Footer section area.</p>
    </div>
</body>
</html>
```

---

### Task 2: Custom Data Attributes (`attributes.html`)
Created a container `<div>` with `id="profile"` containing a paragraph element enhanced with a custom dataset attribute `data-topic="hobbies"`.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Data Attributes</title>
</head>
<body>
    <div id="profile">
        <p data-topic="hobbies">I enjoy web development and coding projects.</p>
    </div>
</body>
</html>
```

---

### Task 3: HTML Syntax Debugging (`attendance-fixed.html`)
Fixed structural markup defects from broken source code (unclosed `<p>` tags and improperly nested elements) to create a valid, clean document.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Attendance</title>
</head>
<body>
    <h1>Attendance Report</h1>
    <p>Asha: 92%</p>
    <p>Rohan: 85%</p>
</body>
</html>
```

---

## 📁 File Structure
```text
Lab 04/
├── layout.html            # Task 1 HTML document
├── attributes.html        # Task 2 HTML document
├── attendance-fixed.html  # Task 3 Fixed HTML document
└── README.md              # Lab 04 documentation
```