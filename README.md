# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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


## Overview

It's simple Qr code component by scanning it you redirect to perticular web address. It's responsive so tha anyone can access it in mobile devices without any problem.

### Screenshot

### Desktop version
![qr-1](https://user-images.githubusercontent.com/99991521/181359642-e4845a6b-28fa-4539-8586-41cd857eb1ab.PNG)

### Mobile version
![qr-2](https://user-images.githubusercontent.com/99991521/181359698-02cc2431-cb6c-496b-bcb2-d3518b38d74e.PNG)


### Links

- Solution URL: [Solution URL here](https://github.com/mihir2226/qr-code-component-main)
- Live Site URL: [Live site URL here](https://mihir2226.github.io/qr-code-component-main/)

## My Process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS media query

### What I learned

```css
@media screen and (max-width:376px) {
      
      body {
        padding-top: 95px;
        max-width: 375px;
      }
      
      img {
        width: 90%;
        height: auto;
        margin: 0;
        margin-top: 10px;
      }

      .container {
        width: auto;
        margin: auto 30px;
        padding-top: 5px;
      }

      .attribution {
        display: none;
      }
    }

    @media screen and (min-width:377px) {
      h2{
        font-size: 28px;
      }
      p{
        font-size: 17;
      }
    }
```

### Continued development

i used media query to make it responsive and i'm not that much confertable with some css properties lately. i would look further to cover all the topics in future projects.

### Useful resources

- [Example resource 1](https://fonts.google.com) - This helped me in importing new fonts. which i used in my component.
- [Example resource 2](https://www.w3schools.com) - This is an amazing website where you can learn about all the things about web development.

## Author

- Website - [Mihir Nayak](https://www.your-site.com)
- Frontend Mentor - [@mihir2226](https://www.frontendmentor.io/profile/@mihir2226)
