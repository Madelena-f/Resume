# Website Resume
#### Video Demo:  <URL HERE>
#### Description:

### Why this project? 

As I prepare to enter college, gain new knowledge, and eventually enter the job market, I realized the importance of creating a website that could serve as a real-world tool for showcasing my skills and experiences. Therefore, I decided to work on a website resume as my project. 

This project includes two pages: the homepage (index.html) which showcases some personality, and the resume page (resume.html). The website is static and is hosted on GitHub pages.


### The homepage

#### Background 

The homepage background is divided into three main portions. There are two side bars with a gradient shadow effect and a main middle section set as light purple background. The page layout divides the space into 30% for the sides and 90% for the middle viewport width, with all three sections being 150% of the viewport height.

#### Header

The home page features an h1 header at the top, prompting the user to "click computer to see resume." This header employs a fade-in effect, transitioning from 0 to 1 opacity over a 5-second duration upon page load using CSS.

#### Main

On the homepage, I've created a captivating cartoon desk image using Microsoft co-pilot. I carefully positioned the desk in the center by adjusting the left, right, top, bottom and margins to zero in CSS. The desk serves multiple purposes: it showcases my personality, provides a direct link to my resume, and hides a fun surprise. To make sure it stands out, I set the desk at a z-index of 1, placing it in front of the purple background. I used image mapping get the coordinates for the computer and linked the map to my resume page (resume.html). As for the hidden feature, users can interact with it by toggling the lamp on and off when hovering over another image map on the lap. This interactive functionality is made possible with JavaScript, which alters the display property of a trapezoid-shaped div from block to none and vice versa. The light itself, styled as a div with a z-index of 2, is cleverly positioned over the desk to give the illusion of emanating from the lamp, all thanks to the use of top, left, right, and bottom properties in CSS. The desk and the light from the lamp utilized position relative to get the desired location, I had to make sure to set the margin of the desk to be zero so that when the lamp light display non it did’t adjust the desk image position.




### The Resume page

#### Background

The resume background is divided into three main portions. There are two sidebars with a gradient shadow effect and a main middle section set as a light purple background. The page layout divides the space into 30% for the sides and 90% for the middle viewport width, with all three sections being 150% of the viewport height.

#### Main

When designing the body of the webpage, it's divided into 3 main sections: the header, the main information section, and a left sidebar. The header contains your name and contact information, while the main section showcases your skills, experiences, and education. Additionally, the sidebar displays your certifications and projects. The experience cards are created using Bootstrap and include images from co-pilot. To maintain proper formatting when the page is resized, the cards are formatted with a minimum width of 200 and a minimum height of 500. The body is set at a minimum width of 980 pixels to ensure correct formatting for printing.

#### Layout

The structure of the resume is built using various flexible boxes and division elements to achieve the desired layout. The main section of the resume utilizes a flexbox with a column layout to present the header and information divisions. Another flexbox is employed to showcase the main division (which contains skills, experience, and education) and the sidebar (which contains certification and project details) in a row format. Each division within the main section is organized in a column layout, with a flexbox in each division to arrange the contents horizontally. The sidebar division uses a flexbox to position the two internal divisions in a column layout.

#### Buttons

This page contains 2 interactive elements. The first is a styled link that resembles a button and takes users to the index.html page. The second element is a button that, when clicked, prints only the main content of the page by adjusting the CSS to hide the background gradients, providing users with a focused view of the main section.



During the writing process, Grammarly generated responses to the following AI prompts:

Prompts created by Grammarly
- "Make it more descriptive"
- "Make it sound academic"
