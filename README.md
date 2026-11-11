# Lola's Sneakers: Responsive Store Landing Page

## Design choices

**Layout and structure**
The page uses semantic HTML: a header with navigation, a main section
for products, and a footer. Each product is an <article> because it is a
self-contained item. All styling lives in one external file, style.css,
and every section is commented to keep the code clean.

**Colors**
I used a dark slate header and footer (#1f2933) with an orange accent
(#e8590c) for the "Shop Now" buttons and the line under the section
heading. The page background is a soft grey so the white product cards
stand out.

**Typography**
I chose Poppins from Google Fonts because it is clean and easy to read
on both large and small screens, with Arial as a fallback.

**Product cards**
Each card has an image, name, short description and a "Shop Now" button.
Images use object-fit: cover so they stay the same size without
stretching. Cards have a soft shadow and lift slightly on hover to give
visual feedback.

**Navigation**
The header is sticky, so the menu stays visible while scrolling. Links
scroll smoothly to each section.

**Responsive design**
I built mobile-first. On phones the cards stack in one column and the
logo sits above the menu. Media queries switch to two columns at 600px
and four columns at 992px. I tested the layout in Chrome's device
toolbar and on a real phone.

## Live site
https://roheemlola07-bot.github.io/store-landing-page/