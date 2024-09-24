# Frontend Mentor - Social links profile solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS/hub). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### Screenshot

Desktop
![Desktop](./screenshots/screenshot_desktop.png)

Mobile
![Mobile](./screenshots/screenshot_mobile.png)


### Links

- Solution URL: [Add solution URL here](https://github.com/kephalosk/bento-grid)
- Live Site URL: [Add live site URL here](https://kephalosk.github.io/bento-grid/)

## My process

1. download Project


2. move Project to target folder


3. open Project in IDE


4. read README


5. add .gitignore-file


6. check files


7. check design


8. initialize repo
* create repo on GitHub
* git init
* git add .
* git commit -m "initial commit"
* git remote add origin git@github.com:kephalosk/${projectname}.git
* git push -u origin master

9. check html
* build general structure
* open index.html in browser for comparison

10. check css
* 1. margin
* 2. border
* 3. background
* 4. padding
* 5. height/width
* 6. display
* 7. font styling
* 8. image styling
* 9. color styling

11. check transitions


12. check javascript


13. check mobile/responsive design


14. check accessability
* semantic html
* headings
* alternative texts
* language
* clear language
* link texts
* keyboard control / tabindex
* img aria-hidden: true for decorative images

15. extract css


16. add screenshots


17. update README


18. publish website

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Desktop-first workflow

### What I learned

I learned to use grid-row-gap and git-column-gap.
```css
.gridRightTopLeftBottom {
  max-height: 100%;
  display: grid;
  grid-column-gap: 32px;
  grid-template-columns: calc(50% - 16px) calc(50% - 16px);

  @media (max-width: 1040px) {
    grid-column-gap: 0;
    grid-row-gap: 32px;
    grid-template-columns: 1fr;
  }
}
```

I learned to use overflow:hidden to cut off images, that are to big to display.
```css
.gridRightTopLeftBottomLeftCard {
    background-color: var(--color-lighter-grey);
    padding: 30px 24px 20px 24px;
    max-height: 100%;
    overflow: hidden;
}
```
I learned to order css properties semantically.
```css
body {
    margin: 0;
    background: var(--color-light-grey);
    max-width: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
}
```


I improved html and css, especially grid skills in general.

### Continued development

* improve html
* improve css

### Useful resources

- [w3schools](https://www.w3schools.com/) - HTML and CSS knowledge
- [selfhtml](https://wiki.selfhtml.org/wiki/HTML) - HTML knowledge

## Author

- Website - [kephalosk](https://easywebpath.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

## Acknowledgments

None.