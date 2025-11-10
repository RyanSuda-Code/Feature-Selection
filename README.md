# Feature Selection

This is a fun and interactive feature selection page built with HTML and CSS. I used hover effects and animations to enhance the user experience.

---

## SCreenshot

![](./img/Screenshot%202025-11-10%20223608.png)  
![](./img/Screenshot%202025-11-10%20223620.png) 
![](./img/Screenshot%202025-11-10%20223637.png) 

---

## Features

- Custom-styled checkboxes: Rounded, colored checkboxes that display a checkmark when selected.
- Responsive layout: Features are arranged in a flexible grid using Flexbox with wrapping.
- Hover effects: Feature cards scale and display glowing shadows on hover.
- Submit button: Interactive button with hover effects and scaling animation.

---

## Technologies

- HTML5
- CSS3
- Google Fonts

---

## Code Snippets

```css
body {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    height: 100vh;
    text-align: center;
}
```
Centering the page.


```css
input[type="checkbox"] {
    appearance: none;
    border: 2px solid #f1be32;
    width: 20px;
    height: 20px;
    border-radius: 5px;
    position: absolute;
    top: 20px;
    right: 20px;
    cursor: pointer;
}
```
Custom Checkbox Design

```css
.feature-container:hover {
    box-shadow: 4px 4px 10px #f1be32, -4px -4px 10px #f1be32;
    transform: scale(1.15);
}
```
Hover Animation

---

