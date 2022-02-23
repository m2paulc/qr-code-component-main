# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - QR code component solution](#frontend-mentor---qr-code-component-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
  - [Author](#author)

## Overview

Create a QR Code Card component

### Screenshot

<img src="./design/mobile-design.jpg"/>

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it. 

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process
- [x] git init files
- [x] bring in the Outfit font
- [x] reset css for all browser uniformatty
- [x] set body background color
- [x] create card
- [x] import image
- [x] style with css 
- [x] mobile responsive


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Mobile-first workflow

### What I learned

Improving my CSS skills. 

To see how you can add code snippets, see below:

```html
<div class="card-wrapper">
			<img src="./images/image-qr-code.png" class="qrcode" alt="qr code" />
			<div class="title-wrapper">
				<h1 class="title">
					Improve your front-end skills by building projects
				</h1>
				<p>
					Scan the QR code to visit Frontend Mentor and take your coding skills
					to the next level
				</p>
			</div>
		</div>
```
```css
.card-wrapper {
	max-width: 375px;
	background-color: var(--primary-white);
	padding: 1rem;
	margin: 1rem;
	border-radius: 20px;
}

.qrcode {
	border-radius: 10px;
}
```

## Author

- Frontend Mentor - [@m2paulc](https://www.frontendmentor.io/profile/m2paulc)

