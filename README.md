# This repository contains the code for FED CA1 

The folder structure is as follows:

- [This repository contains the code for FED CA1](#this-repository-contains-the-code-for-fed-ca1)
- [Index.html Documentation](#indexhtml-documentation)
- [style.css Documentation](#stylecss-documentation)
  - [Global Styles](#global-styles)
  - [**`body`**](#body)
  - [**`Container`** ](#container-)
  - [**`links`** ](#links-)
  - [Specific Styles](#specific-styles)
  - [**`hero`**](#hero)
  - [**`button`**](#button)
  - [**`popup`**](#popup)
  - [**`icon-container`**](#icon-container)
  - [**`footer`**](#footer)
- [Empower.html](#empowerhtml)
  - [CSS Styles](#css-styles)
    - [Global styles](#global-styles-1)
    - [Header styles](#header-styles)
    - [Content styles](#content-styles)
  - [CSS Documentation - style1.css](#css-documentation---style1css)
    - [Global styles](#global-styles-2)
    - [Link styles](#link-styles)
    - [Header styles](#header-styles-1)
    - [Typography styles](#typography-styles)
    - [Image alignment](#image-alignment)
- [Feedback](#feedback)




The final Draft is [here](/CA1)

# Index.html Documentation
This HTML code is a webpage for a project called "Save the Earth". It includes a header with a logo and navigation menu, a hero section with a call-to-action button, a popup section with three buttons, a main content section with information about the author's values, interests, and personality, and a footer with copyright information.

The webpage uses CSS to style the layout and fonts, and includes a Google Fonts link for the Montserrat font. It also includes JavaScript code for opening and closing the popup section.

The webpage is designed to promote sustainability and encourage visitors to take action towards a more sustainable future.

The `<meta>` element with the `name="viewport"` attribute is used to control the layout and scaling of the webpage on different devices. The content attribute specifies the width of the viewport and the initial zoom level.

In this specific case, the content attribute is set to `"width=device-width,` initial-scale=1.0", which means that the width of the viewport will be set to the width of the device, and the initial zoom level will be set to 1.0. This ensures that the webpage is displayed properly on different devices, including mobile devices.

# style.css Documentation
The style.css file is a CSS file that contains styles for a webpage. It is linked to the HTML file of the webpage using the <link> element in the <head> section of the HTML file.

## Global Styles
The `style.css` file includes global styles for the `body, container`, and `links`  elements. These styles apply to all instances of these elements on the webpage.

## **`body`**

The `body` element is the top-level element of the webpage. The global styles for the body element include:

`font-family: Arial, sans-serif;: `This sets the default font family for the webpage to Arial or a similar sans-serif font.

- `font-family: Arial, sans-serif;:` This sets the default font family for the webpage to Arial or a similar sans-serif font.
- `font-size: 16px;:` This sets the default font size for the webpage to 16 pixels.
  
- `line-height: 1.5;:` This sets the default line height for the webpage to 1.5 times the font size.

- `color: #333;:` This sets the default text color for the webpage to a dark gray color.

## **`Container`** <br>
The `container` element is a wrapper element that contains the main content of the webpage. The global styles for the `container` element include:

- `max-width: 1200px;:` This sets the maximum width of the `container` element to 1200 pixels.
- `margin: 0 auto;:` This centers the `container` element horizontally on the webpage.
  
## **`links`** <br>
The `links` element includes styles for all `links` on the webpage. The global styles for the `links` element include:

- `color: #0077cc;:` This sets the default color for links to a blue color.
- `text-decoration: none;:` This removes the underline from links.
- 
## Specific Styles
The `style.css` file also includes specific styles for the following elements:

`header`
This style applies to the header section of the webpage, which includes a logo and navigation menu. The specific styles for the `header` element include:

- `background-color: #fff;:` This sets the background color of the header element to white.
- ` box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);:` This adds a subtle shadow to the `header` element.
- `padding: 20px;:` This adds padding to the `header `element.
- `display: flex;:` This sets the display property of the header element to flex, which allows for flexible layout options.
- `justify-content: space-between;:` This aligns the child elements of the `header `element to the left and right edges of the element.
## **`hero`**
This style applies to the hero section of the webpage, which includes a call-to-action button. The specific styles for the `hero` element include:

- `background-image: url('hero-bg.jpg');: `This sets the background image of the` hero` element to a file named hero-bg.jpg.
background-size: cover;: This scales the background image to cover the entire hero element.
- `background-position: center;:` This centers the background image within the `hero` element.
- `height: 500px;:` This sets the height of the `hero` element to 500 pixels.
- ` display: flex;:` This sets the display property of the `hero` element to flex.
- `align-items: center;:` This centers the child elements of the `hero` element vertically.
- `justify-content: center;:` This centers the child elements of the `hero` element horizontally.
## **`button`**
This style applies to all button elements on the webpage. The specific styles for the `button` element include:

- `background-color: #0077cc;: `This sets the background color of the `button` element to blue.
- `color: #fff;:` This sets the text color of the `button` element to white.
- `border: none;:` This removes the border from the `button` element.
- `padding: 10px 20px;:` This adds padding to the `button` element.
## **`popup`**
This style applies to the popup section of the webpage, which includes three buttons. The specific styles for the `popup` element include:

- `background-color: rgba(0, 0, 0, 0.5);:` This sets the background color of the `popup` element to a semi-transparent black color.
- `position: fixed;:` This sets the position of the `popup` element to fixed, which keeps it in the same position even when the user scrolls the webpage.
- `top: 0;:` This sets the top position of the `popup` element to 0 pixels.
- `left: 0;:` This sets the left position of the `popup` element to 0 pixels.
- `width: 100%;:` This sets the width of the `popup` element to 100% of the viewport width.
- `height: 100%;:` This sets the height of the `popup` element to 100% of the viewport height.
- `display: flex;:` This sets the display property of the `popup` element to flex.
- `align-items: center;:` This centers the child elements of the `popup` element vertically.
- `justify-content: center;:` This centers the child elements of the `popup` element horizontally.
## **`icon-container`**
This style applies to the container for the icons in the popup section. The specific styles for the `icon-container` element include:

- `display: flex;:` This sets the display property of the `icon-container` element to flex.
- `justify-content: space-between;:` This aligns the child elements of the -
- `icon-container `element to the left and right edges of the element.
- `width: 200px;:` This sets the width of the `icon-container` element to 200 pixels.
## **`footer`**
This style applies to the footer section of the webpage, which includes copyright information. The specific styles for the ``footer`` element include:

`background-color: #f2f2f2;:` This sets the background color of the `footer` element to a light gray color.
`padding: 20px;:` This adds padding to the `footer` element.
- `text-align: center;:` This centers the child elements of the `footer` element horizontally.
- **`Media Queries`**
The `style.css` file includes media queries for responsive adjustments on smaller screens. These media queries adjust the layout and styling of the webpage to ensure that it is displayed properly on different devices.

# Empower.html

- `<!DOCTYPE html>` declaration defines the document type as HTML5.
- The `<html>` element wraps the entire HTML content of the page.
- The `<head>` section contains metadata and external resource references.
- The `<body>` section contains the actual content displayed on the webpage.

## CSS Styles
The code includes inline CSS styles applied to various elements. Here's a breakdown of the styles used:

### Global styles
- `body`: Sets the font family, size, line height, margin, and padding for the body.
- `.container`: Sets the maximum width, margin, and padding for the container class.
- `a`: Sets the color and text decoration for links.
- `a:hover`: Sets the color for links on hover.

### Header styles
- `header`: Sets the background color, box shadow, position, and height for the header container.
- `header .container`: Sets the display, alignment, and width for the header container's contents.
- `header h1`: Sets the font size for the header's main heading.
- `header nav ul`: Sets the display, alignment, margin, padding, and list style for the header navigation ul.
- `header nav li`: Sets the margin for the header navigation li.
- `header nav li:first-child`: Removes the margin for the first header navigation li.
- `header nav a`: Sets the font size for the header navigation links.

### Content styles
- `h1, h2, p`: Sets the font family for headings and paragraphs.
- `img.align-right`: Sets the float, margin, maximum width, and height for right-aligned images.

## CSS Documentation - style1.css

### Global styles

- `body`: Applies the following styles to the `body` element:
  - `font-family`: Sets the font family to 'Montserrat', sans-serif.
  - `font-size`: Sets the font size to 16 pixels.
  - `line-height`: Sets the line height to 1.5.
  - `margin`: Sets the margin to 0.
  - `padding`: Sets the padding to 0.

- `.container`: Applies the following styles to elements with the class `container`:
  - `max-width`: Sets the maximum width to 960 pixels.
  - `margin`: Sets the top and bottom margin to 0 and left and right margin to auto (center aligns the container).
  - `padding`: Sets the padding to 10 pixels (you can adjust this value as needed).

### Link styles

- `a`: Applies the following styles to anchor (`<a>`) elements:
  - `color`: Sets the text color to #333 (a dark gray).
  - `text-decoration`: Removes the underline decoration for links.

- `a:hover`: Applies the following styles to anchor elements on hover:
  - `color`: Sets the text color to #007bff (a light blue).

### Header styles

- `header`: Applies the following styles to the `header` element:
  - `background-color`: Sets the background color to #fff (white).
  - `box-shadow`: Adds a box shadow with a color and blur effect.
  - `position`: Sets the position to fixed, so the header stays fixed at the top of the page.
  - `top`: Sets the top position to 0.
  - `left`: Sets the left position to 0.
  - `width`: Sets the width to 100%.
  - `z-index`: Sets the z-index to 1.

- `header .container`: Applies the following styles to elements within the header with the class `container`:
  - `display`: Sets the display to flex, enabling flexible layout.
  - `align-items`: Aligns items vertically in the center.
  - `justify-content`: Aligns items horizontally with space between.
  - `height`: Sets the height to 60 pixels.
  - `width`: Sets the width to 100%.

- `header h1`: Applies the following styles to `h1` elements within the header:
  - `font-size`: Sets the font size to 24 pixels.
  - `margin`: Sets the margin to 0.

- `header nav ul`: Applies the following styles to unordered lists (`ul`) within the header navigation:
  - `display`: Sets the display to flex.
  - `align-items`: Aligns items vertically in the center.
  - `justify-content`: Aligns items horizontally to the right.
  - `margin`: Sets the margin to 0.
  - `padding`: Sets the padding to 0.
  - `list-style`: Removes the bullet points from list items.

- `header nav li`: Applies the following styles to list items (`li`) within the header navigation:
  - `margin-left`: Sets the left margin to 20 pixels.

- `header nav li:first-child`: Applies the following styles to the first list item within the header navigation:
  - `margin-left`: Removes the left margin.

- `header nav a`: Applies the following styles to anchor elements within the header navigation:
  - `font-size`: Sets the font size to 18 pixels.

### Typography styles

- `h1, h2, p`: Applies the following styles to

 `h1`, `h2`, and `p` elements:
  - `font-family`: Sets the font family to 'Montserrat', sans-serif.

### Image alignment

- `img.align-right`: Applies the following styles to images with the class `align-right`:
  - `float`: Sets the float to right, allowing the text to wrap around the image on the left.
  - `margin`: Sets the margin to 10 pixels.
  - `max-width`: Sets the maximum width to 50% of the parent container.
  - `height`: Sets the height to auto, maintaining the aspect ratio of the image.

These are all the styles defined in the `style1.css` file, along with their corresponding descriptions.



# Feedback 
Enter name and class
Code Banner

Colours, might not be the right choice, padding issues