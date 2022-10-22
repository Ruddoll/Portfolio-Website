#

- HTML
- CSS
- Wireframes
- git
- Markdown

## HTML

We startes creating the skeleton (! + Enter in VSCode), the we created the header, linked the CSS and the other two big containers, main and footer.

Header, contains a logo, a heading and a navigation.

```html
<header>
        <div class="logo">
            <p>My logo</p>
        </div>
        <h1>Personal training</h1>
        <nav class="nav-items">
            <a href="">Training</a>
            <a href="">About us</a>
            <a href="">Contact</a> 
        </nav>

    </header>
```

## CSS

Defined primary and secondary colors, add them to the backgrounds and text colors.

Flex box for the header to aligh the three elements incide centered and vertically.

```css
header{
    background-color: #ff9900;
    display: flex;
    flex-direction: column;
    align-items: center;
}
```

## Wireframes

!["Figma view"](./images/)
!["Browser view"](./images/)