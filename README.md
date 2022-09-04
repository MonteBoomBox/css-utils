# css-utils
## A set of CSS classes for margin and padding.
css-utils is a small CSS file **(6 KB)** consisting of utility classes for margin and padding. It contains CSS variables for base value and increasing factor which you can override.

So you don't have to create these everytime for a new project :)
## Usage
- Use from CDN **(Recommended)**
Just copy the below link and paste it in your HTML file.
```
https://cdn.jsdelivr.net/gh/MonteBoomBox/css-utils/css-utils.css
```
- If you want to customize the variables, override the variables in your own CSS.
```
:root {
  --margin-base: 0.5rem; /* Can be any unit */
  --margin-factor: 0.5rem;
  
  --padding-base: 10px;
  --padding-factor: 5px;
}
```
- You are good to go. Enjoy the utility classes :)
