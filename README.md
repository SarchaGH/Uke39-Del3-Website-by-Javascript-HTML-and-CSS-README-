# Uke39-Del3-Website-by-Javascript-HTML-and-CSS-README

## Explore Thailand website

### 1. Project Overview
Hello! In this project, I designed a website to explore *Thailand*, my homeland. 
I used JavaScript, HTML, and CSS to manage and decorate my website. 
This website shows 6 regions of Thailand (Central, Northern, Northeastern/Isan, Eastern, Western, and Southern).

### 2. Features 
- General information about Thailand and a link that sends users to *Wikipedia* to read more.
- Light and Dark mode button: This button helps users change the theme of the website between Light and Dark mode by clicking on it.
- Region buttons: These buttons will bring users to the *Google Maps* of the region they click. There is also a hover effect on these buttons.
- Alert!: I made a simple feature that greets users when entering the website.

*Alert EXP.*
```javascript
alert("Welcome!");
```

### 3. How code works
- **HTML:** Used for building the structure of the website.

**EXP: how I use HTML in this project(Theme switcher)**
 ```html
 <button onclick="toggleTheme()" class="theme-btn"> Dark/Light Mode </button>
 ```
 This use for create a button then triggers when user clicked.

- **CSS:** Used for decorating the website like colors, themes.

**EXP: Define light mode (default) and dark mode styles with a smooth color transition.**
```css
/* Default Light Mode */
body {
    background-color: #f8f9fa;
    color: #212529;
    transition: 0.3s;
}

/* Dark Mode */
.dark-mode {
    background-color: #121212;
    color: #e0e0e0;
}
```

- **JavaScript:** Used for running commands, functions, and interactive features.

**EXP: this is how I use CSS to toggle the dark-mode**
```Javascript
function toggleTheme() {
    document.body.classList.toggle("dark-mode");
}
```


### 4. What did I learn?

- How to use **HTML, CSS, JS** together for EXP:








**Note:** I chose to use English to explain this project because it is easier for me to express my thoughts in my own words this way!
