Nneka Moweta
Girlhood. Website - Technical Design Document

Project Overview

In developing this menstrual health education website, I prioritized creating an accessible, informative, and visually engaging platform that would make learning about menstrual health both comfortable and comprehensive. The project utilizes HTML and CSS to create a responsive, multi-page website with interactive features and a cohesive design language.

Design Implementation

The core of my design approach centered on creating a welcoming and professional atmosphere through the strategic use of color psychology and typography. I chose a primary color palette centered around violet (#EE82EE) and dark orchid (#9932CC) to create a feminine yet professional aesthetic. These colors were carefully selected not only for their visual appeal but also for their accessibility, ensuring sufficient contrast ratios for text readability while maintaining a cohesive aesthetic and theme throughout the site.

Firstly, on the homepage.html page that displays the title of my website “Girlhood.”, I wanted the user to click on the period to access the rest of the website’s features because they are learning more about their “period”/menstrual cycle. I wanted to add a little clever aspect to the project.

For the website's structure, I implemented a modular approach with distinct pages for different aspects of menstrual health education. The centerpiece of this design is the interactive slideshow on the phases page, which I built using a combination of CSS transitions and JavaScript functionality. The slideshow container uses relative positioning and flexbox layout to ensure content remains properly aligned and responsive across different screen sizes. I implemented this using CSS classes like `.slideshow-container` and `.slide`, with careful attention to spacing and layout through properties like `padding`, `margin`, and `gap`.

One of the most significant technical challenges was creating a responsive layout that would work seamlessly across different devices and screen sizes. For mobile devices, I implemented a breakpoint at 768px and another one at 1000px that modifies the layout and typography to maintain readability and usability on smaller screens. However, I was not able to do this with all of the pages, so my website is much more suitable for a computer layout.

To enhance user engagement, I incorporated several interactive elements throughout the site. The navigation system uses hover effects and transitions to provide visual feedback, implemented through CSS transforms and transitions. The progress dots in the slideshow provide clear visual indication of current position, while smooth transitions between slides create a polished user experience. I achieved this through careful state management in the CSS, using classes like `.active-slide` and `.dot.active` to control visibility and styling.

I used the Salina font family for headings and emphasis, paired with Arial for body text to ensure optimal readability. The type scale is carefully implemented through CSS with different sizes for various heading levels and responsive adjustments for mobile viewing. The line heights and letter spacing were fine-tuned to enhance readability across different screen sizes.

For the products and resources sections, I implemented a grid-based layout that allows for flexible content organization while maintaining visual hierarchy. The product descriptions use alternating background colors (#9932CC and #E0B0FF) to create visual separation and maintain user engagement throughout longer scroll sections. Each product section maintains consistent spacing and alignment through absolute positioning and transform properties, ensuring content remains properly organized regardless of screen size.

The mirror feature presented unique technical challenges in terms of implementing camera functionality and creating an engaging user interface. I used CSS transforms and border-radius properties to create the mirror effect while carefully trying to maintain proper aspect ratios and responsive behavior. The implementation includes fallbacks and error handling to ensure a smooth user experience across different devices and browsers.

Animation adds subtle but important dynamism to the site. I implemented keyframe animations for elements like the glowing effect on interactive elements, using CSS animations with careful timing and easing functions to ensure smooth performance. These animations enhance the user experience without being distracting or impacting performance.

I really hope you enjoyed reviewing my project!
