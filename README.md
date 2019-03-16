# Product Cards
One-page locally hosted site to practice styling in HTML and CSS.

### Result
- Styled based on the initial [exercise](https://github.com/nss-nightclass-projects/exercise-vault/blob/master/HTML_CSS_product_cards.md) requirements
- Challenges
  - Challenge 1: Switch up the colors!
    - I initially started coloring using the [Material Palette](https://www.materialpalette.com/) tool, then further adjusted colors
  - Challenge 2: Switch up the font!
    - I picked the Lato font from [Google Font](https://fonts.google.com/)
  - Challenge 3: Sold out.
    - HTML: I first placed the Sold Out image within the same container as the unavailable product image in the DOM and assigned it the class `imgNotAvailable`
    - CSS:  I styled `.imgNotAvailable` as follows:
      - `position: absolute;` was used to later define the placement relative it's nearest container/ancestor
      - `width: 90%;` to fit within the container
      - `top: 4%;` and `left: 4%;` to place the image over the unavailable product image
  - Challenge 4: Display responsively on any size screen!
    - I defined two media queries for this Challenge.
      - `@media only screen and (min-width: 968px) {` was used as my default view for tablets and desktops.
        - The styling option within was a pet project used to see if I could display *no more than* three cards at the top.
      - `@media only screen and (max-width: 989px) {` was used for phones.  To test if this works, I centered the content within the body and removed the `margin-right` from the previous media query so that the items wrap correctly.
    

## Screenshots
![image of product cards website for tablets and desktops - scrolled to top](https://raw.githubusercontent.com/bobbybaxter/product_cards/master/img/product_cards_screenshot1.png)
![image of product cards website for tablets and desktops - scrolled to bottom](https://raw.githubusercontent.com/bobbybaxter/product_cards/master/img/product_cards_screenshot2.png)
![image of product cards website for phones](https://raw.githubusercontent.com/bobbybaxter/product_cards/master/img/product_cards_screenshot3.png)
![image of product cards website for phones, minimized](https://raw.githubusercontent.com/bobbybaxter/product_cards/master/img/product_cards_screenshot4.png)

## Getting Started
Clone the repo:
```
$git clone https://github.com/bobbybaxter/product_cards
```

### Prerequisites
Download HTTP Server, to be able to serve the site locally in your browser:
```
$npm install -g http-server
```

## Running
Browse to the product_cards/ directory and run HTTP Server by typing the following command into the terminal:
```
$ hs -p 5000
```

In your web browser, copy and paste this:

 `localhost:5000`