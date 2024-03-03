

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H).
## Table of contents

  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)


### Screenshot

![Screenshot](/screenshots/screenshotQRcode.png)


### Links

- Solution URL: (https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H)

### Built with

- Semantic HTML5 markup
- CSS custom properties

### What I learned
I learnd css box model. The most dificult part was to center qr code preview card's borderbox. At this time I made it using margin and padding properties, also pseudoclasses ::before and ::after. But I think there are better way to achierve this with flexbox.

css
    *::before,
    *::after {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

### Continued development
I'm still not completely comfortable and need more practice with the box model, so I want to continue focusing on it. Besides, I want to learn more about responsive website design (flexbox and grid) in future projects.


### Useful resources

https://css-tricks.com/ - Super website about CSS. I found it from Angela Yu's bootcamp. You can dive deeper into CSS and find answers here."
https://chat.openai.com/ - ChatGPT really saved my time. I found it to be a good problem solver and helper. If you couldn't find bugs and got stuck on them, try it.


## Author

- GitHub - [@IngridaVob] (https://github.com/IngridaVob)
- Frontend Mentor - [@IngridaVob](https://www.frontendmentor.io/profile/IngridaVob)

