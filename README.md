# Basic-Portfolio
#### Francisco Fabian Flores

## Description
This project contains a basic personal portfolio page. The website consists of three sections: brief bio, portfolio projects, and contact information. There is also a "social media" section which has links to personal github, linkedin and stackoverflow content.

## Approach to project
### HTML
First, I defined three html pages to get the basic structure of each page. The `header` section of each page contains a box with my name, a navigation bar with three links to the sections of the website, a height of 100 pixels with the specified background color.
The `main content` of each page contains two boxes. One box is structured as a content box (650px wide), the other as an `aside` section common to each page (270px wide). The width, per the requirements, of the entire content is 960 pixels wide. Currently, the website is not responsive.
In the portfolio.html file, to be able to represent a portfolio image with text across, I used a `figure` tag. Within the `figure` tag, I included an `a` tag with an `img` content and a `figcaption` element. I linked two existing small software projects which by no means are intended to be included in a "final version" of my portfolio; these were used for presentation purposes. The other portfolio images are simply self-referencing placeholder images.
There is common `footer` section for each html file.
I used `validator.w3.org` to validate the html files.

### CSS
I leveraged the `reset.css` stylesheet to start off on a blank slate, and have the website contain the same fonts, spacing and the like across different brand browsers.
The stylesheet `style.css` is divided into three sections, 1) block elements, 2) class elements and 3) id elements. As to the colors and fonts, I followed the project specifications. For the background image pattern, I used circles-light.png. 
The `header` element is styled as a `box` which contains the `h1` and `nav` elements.
The `main_content` class contains a `section` element and an `aside` element. In order to align the main content area, I leveraged the `clearfix` class. In order to have the width of the section and aside elements fit the 960 pixels correctly, I set separate css classes (`main_box` class for `section` and `media_links` id) to set the positioning and padding of each box.
To have the footer section always appear at the bottom of the content, I used a `sticky footer` content wrapper. I centered the `copyright` text based on the 960px, the content, and not the screen size.
I added a few custom styles for when the user hovers over a text or image link, or the `submit` button on the contact.html page.

