# Frontend Mentor - Results summary component solution

This is a solution to the [Results summary component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

![](./Screenshot-Frontend%20Mentor%20Results%20summary%20component.png)



### Links

- Solution URL: [Github Repo link](https://github.com/utsobanerjee/result-summary-frontendmentor)
- Live Site URL: [Live site hosted by vercel](https://utso-result.vercel.app/)

## My process

### Built with

- HTML5 markup
- CSS custom properties
- Flexbox



### What I learned

- First Major learning through from the project was basics of how to use and navigate through figma . Both of the articles provided by Frontend Mentor was really great with good interactive lessons .

I used figma extensively to get the desktop design done . I haven't done the mobile view now . Will do it later .

- I learned how to use CSS Gradient property . Read about all the three types of Gradient property .

- Learned how to make a circle shaped div by manipulating its border radious property 

```css

  .circle{
    border-radius: 50%;
    background-image: linear-gradient(hsla(256, 72%, 46%, 1),hsla(241, 72%, 46%, 0));
    height: 200px;
    width: 200px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    
}
```


- Learned how to use the hsla metric of color property . In the summary section to get the the background color of each subject close to the design , had to experiment with changing the 'alpha' value of property .

```css

  .reaction{
    background-color: hsla(0,100%,67%,0.1);
    border-radius: 10px;
}

```

- Learned how to use the box-shadow property

```css

  .report-card-right {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-around;
    flex-grow: 1;
    border-radius: 20px 0px 20px 0px;
    box-shadow: 0px 30px 60px 0px hsla(224, 82%, 58%, 0.5);
  }

```


### Useful resources

- [“Everything Developers Need To Know About Figma” article on Smashing Magazine](https://www.smashingmagazine.com/2020/09/figma-developers-guide/) - This helped me get started with figma .

-  ["Introduction to Figma for Developers" video with Ryan Warner and Jason Lengstorf on Learn with Jason](https://www.learnwithjason.dev/introduction-to-figma-for-developers) - An Introductory lecture on Figma


## Author

- Frontend Mentor - [@utsobanerjee](https://www.frontendmentor.io/profile/utsobanerjee)
- Twitter - [@banerjee_utso](https://twitter.com/banerjee_utso)


