# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](![alt text](image.png))


- Solution URL: (https://github.com/korcakSEA/NFT-preview-card.git)
- Live Site URL: (https://korcaksea.github.io/NFT-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Mobile-first workflow
- [React](https://tailwindcss.com/) - Tailwind framework

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

My major learning is the application of hover states for interactive elements by using Tailwind

To see how you can add code snippets, see below:

```html
 <!-- Card image -->
        <div class="relative rounded-lg overflow-hidden ">
          <img src="./public/images/image-equilibrium.jpg" alt="equilibrium image" class="card__image">
          <div class="w-full h-full absolute top-0 left-0 bg-cyan-400/40 flex items-center justify-center opacity-0 rounded-lg overflow-hidden cursor-pointer hover:opacity-100 transition duration-300 ">
            <svg width="48" height="48" xmlns="http://www.w3.org/2000/svg">
              <g fill="none" fill-rule="evenodd">
                <path d="M0 0h48v48H0z" />
                <path
                  d="M24 9C14 9 5.46 15.22 2 24c3.46 8.78 12 15 22 15 10.01 0 18.54-6.22 22-15-3.46-8.78-11.99-15-22-15Zm0 25c-5.52 0-10-4.48-10-10s4.48-10 10-10 10 4.48 10 10-4.48 10-10 10Zm0-16c-3.31 0-6 2.69-6 6s2.69 6 6 6 6-2.69 6-6-2.69-6-6-6Z"
                  fill="#FFF" fill-rule="nonzero" />
              </g>
            </svg>
          </div>
        </div>
```
## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
