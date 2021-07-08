# Personal Portfolio
## Description
The goal of this project was to create a personal portfolio page that showcases my work and skillset. For this assignment, there was no starter code, which meant I had the opportunity to create the entire project from scratch! This process helped me practice and refine my HTML and CSS skills by requiring me to rely on my own knowledge and to research solutions when hitting roadblocks. It also helped reinforce the lessons from the last assignment, where I developed a stronger understanding of the importance of semantics and organization when coding.

## Process
I started by creating a new HTML document and two CSS files — one to implement my desired styles and the other to reset the inherent page styles. Once the stylesheets were both linked, I began setting up the page's structure and content with HTML. While creating the different elements, I was intentional about how I defined and structured the sections in order to style them better. For example, I kept in mind where I'd want to use flexbox, making sure to structure the parent containers and child elements accordingly. 

Once the basic structure of the page was in place, I moved onto styling. I really wanted to add some custom fonts to the page, so I did a bit of research and found two different ways to do so! The first way was by uploading a .WOFF file, then calling it with the @font-face rule via CSS. I did this to add a custom serif font to use for some headings. I also learned that I could link a Google font via HTML, which is what I did to add the custom body font used throughout the site. 

One of the first challenges I faced when trying to style the page was adding a background image to the banner section. But after a bit of Googling, I realized that the error was in the way I was trying to call the file — I was using the wrong path structure. After reviewing a few online resources, I was able to correctly structure the path and get the background image to appear! 

Another challenge I faced was getting the titles of each section ("About Yasi", "Work", and "Contact") to be both vertically and horizontally aligned in their respective containers. For this, I consulted a tutor who was able to help guide me on a more effective way of using flexbox to achieve this goal. 

When styling the "Work" section, I chose to add GIFs instead of images to showcase some of the more interesting features of each project. Overall, I wanted to keep the design of the page really simple by using neutral colors and simple thin gridlines around each section, then adding GIFs to the Work section to add dynamism. 

After finalizing the structure and site styles, my last step was to optimize the layout for mobile. I used a media query to define the new styles that would be displayed on screens 767px or smaller. I didn't change too much  — I mostly adjusted the flex-direction of the elements to have eveything appear in columns instead of rows. I'm happy with both the desktop and mobile versions of the page!

## Usage
[Here](https://go-yasi.github.io/yasis-portfolio/) is a link to the deployed appilication.  
Below is a screenshot of the webpage: 
    ![Screenshot of completed personal portfolio webpage](assets/images/screenshot.png)


## Conclusion
In conclusion, I feel very satisfied with how the page turned out. I like the structure and the simplicity of the styling. By keeping it simple, I can continue to add more projects that may have their own very distinct styles and not worry if they will clash with the overall page. 