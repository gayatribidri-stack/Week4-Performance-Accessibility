# Week 4: Enhancing Web Page Performance and Accessibility

## 1. Project Title

**Accessible Student Study Planner**

## 2. Objective

The objective of this task was to improve the performance and accessibility of a static web page using HTML5 and CSS3. The page was designed to be responsive, easy to navigate, and more accessible to keyboard users.

## 3. Technologies Used

* HTML5
* CSS3
* Visual Studio Code
* Google Chrome Lighthouse
* Live Server extension

## 4. Performance Improvements

The following steps were taken to keep the website lightweight and efficient:

* Used clean and organized HTML and CSS.
* Avoided unnecessary JavaScript.
* Avoided external images, fonts, and libraries.
* Used CSS media queries to support different screen sizes.
* Kept the page layout simple and easy to load.

## 5. Accessibility Improvements

The following accessibility features were implemented:

* Semantic HTML elements such as `header`, `nav`, `main`, `section`, `aside`, and `footer` were used.
* A skip-to-main-content link was added to help keyboard users reach the main content.
* Visible focus indicators were added to help users identify the currently focused element.
* Navigation links were provided for Subjects, Schedule, and Study Goals.
* The weekly schedule uses a table caption and appropriate table headings.
* A reduced-motion CSS preference was included.

## 6. Lighthouse Testing Results

The website was tested using Google Chrome Lighthouse in Desktop mode.

| Category       |   Score |
| -------------- | ------: |
| Performance    | 100/100 |
| Accessibility  | 100/100 |
| Best Practices | 100/100 |
| SEO            | 100/100 |

## 7. Manual Testing

The following manual tests were performed:

* The skip-to-main-content link was tested using the keyboard.
* Pressing Enter on the skip link moved the page to the main content.
* Subjects, Schedule, and Study Goals navigation links were tested.
* The View my schedule button was tested.
* Visible focus outlines were confirmed on the tested interactive elements.
* Shift + Tab was used to test backward keyboard navigation.

The tested links and keyboard navigation worked as expected.

## 8. Challenges and Solutions

One challenge was testing the page with Lighthouse because the page was initially opened directly as a local file. Lighthouse required the page to be served over HTTP or HTTPS.

This was resolved by running the project with the VS Code Live Server extension. The skip link's visibility was also adjusted in CSS and tested again.

## 9. Learning Outcomes

Through this task, I learned about semantic HTML, keyboard accessibility, visible focus indicators, responsive CSS, Lighthouse testing, and the importance of manual accessibility checks.

## 10. Conclusion

The Accessible Student Study Planner achieved a Lighthouse score of 100 in Performance, Accessibility, Best Practices, and SEO. The keyboard navigation and skip link were also manually tested. This task improved my understanding of building lightweight, responsive, and accessible web pages.
