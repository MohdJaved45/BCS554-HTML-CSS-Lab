# Lab 06: Types of HTML Lists

**Course:** HTML & CSS Development Lab (BCS554)  
**Student Name:** Mohd Javed Khan  
**Student ID:** LBCS2025023  

---

## 🎯 Aim
Implement and demonstrate various HTML list elements (`<ul>`, `<ol>`, and `<dl>`), including unordered bulleted lists, nested ordered lists, and description lists formatted for structured content such as FAQs.

---

## 📄 Tasks Completed

### Task 1: Unordered List Component (`shopping-list.html`)
Created `shopping-list.html` utilizing the `<ul>` (unordered list) and `<li>` (list item) elements to display a bulleted items list containing Notebook, Pen, and Bag.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Shopping List</title>
</head>
<body>
    <h1>Shopping List</h1>
    <ul>
        <li>Notebook</li>
        <li>Pen</li>
        <li>Bag</li>
    </ul>
</body>
</html>
```

---

### Task 2: Nested Ordered List Component (`canteen-menu.html`)
Created `canteen-menu.html` demonstrating sequential list structure using `<ol>` elements. Implemented a nested ordered list under the primary "Sandwich" item to render sub-options (Cheese and Vegetable).

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Canteen Menu</title>
</head>
<body>
    <h1>Canteen Menu</h1>
    <ol>
        <li>Samosa</li>
        <li>Sandwich
            <ol>
                <li>Cheese</li>
                <li>Vegetable</li>
            </ol>
        </li>
    </ol>
</body>
</html>
```

---

### Task 3: Description List Component (`faq.html`)
Created `faq.html` using description list containers (`<dl>`), terms (`<dt>`), and definitions (`<dd>`) to display structured Question & Answer pairs.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>FAQ Page</title>
</head>
<body>
    <h1>Frequently Asked Questions</h1>
    <dl>
        <dt>How many books can I borrow?</dt>
        <dd>You can borrow up to three books at a time.</dd>
        <dt>Is the library open on Sunday?</dt>
        <dd>No, the library is closed on Sundays.</dd>
    </dl>
</body>
</html>
```

---

## 📁 File Structure
```text
Lab 06/
├── shopping-list.html      # Task 1 HTML page
├── canteen-menu.html       # Task 2 HTML page
├── faq.html                # Task 3 HTML page
└── README.md               # Lab 06 documentation
```