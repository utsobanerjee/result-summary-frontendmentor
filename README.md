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
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

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


- Learned how to  the hsla metric of color property . In the summary section to get the the background color of each subject close to the design , had to experiment with changing the 'alpha' value of property .

```css

  .reaction{
    background-color: hsla(0,100%,67%,0.1);
    border-radius: 10px;
}

```


### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**
