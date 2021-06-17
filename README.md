# UCB-refactorWebsite-HW
# Description
The repository ("UCB-refactorWebsite-HW") is where all the files associated with the Horiseon website and where the refactored source code will be located. The Source code is available for everyone under standard License.

This Project is a refactoring of the Source code Provided by Horiseon Solutions. For this Project, I refactored the source code of the website in order to follow semantic HTML conventions to better optimize search engine results and accessibility. Originally, the source code seperated content within  Included within this README.md file is a list of all the changes to the source code made. This project did not change any of the content or styling of the webpage, just the structuring and labeling of the html and corresponding elements. All functionality with the original structure is still in place, index.html is now more precise and organized with original content.  



# Installation 

## Text Editor
All code was written within visual studio code, any other text editor should work with these files but listed below is the editor used to write this project. Local machine should be able to run files with index.html and style.css. Images are attached inside the assets folder.

[Visual studio Code] (https://code.visualstudio.com/)

## Files and Site address
Located below is a link to the github and the live deployed site:

* [Github] https://github.com/PN-Barnes/UCB-refactorWebsite-HW
* [Deployed] https://pn-barnes.github.io/UCB-refactorWebsite-HW/


## Built with:

* [HTML] (https://developer.mozilla.org/en-US/docs/Glossary/HTML).
* [CSS] (https://developer.mozilla.org/en-US/docs/Web/CSS).

# Refactoring 


### `<html>`
1. Spaced all content between the `<html>` tags to format under the parent to add better legibility.
2. The whole page needed to be properly indented with their relative position within the page. 

### `<head>`
1. in `<head>` I added a website title of "Horiseon" in the `<title>` tags.
2. Spaced a line between the `<head>`  and `<body>`  tags to seperate sections.

### `<body>`
1. in class `<header>` I changed the `<div>` tag to a `<header>` tag in order to seperate the information in the layout, creating the top of the body.
2. In `<header>` added `<nav>`tags for the link navigation list items. Also changed the CSS rule in order to select `<nav>` tags with the list items. 
3. commented out each section to make legible labels for each part of content
4. Added alt="" attributes to each image as well as descriptions for images
5. reorganized the `<h>` tags to be in order for page to evenly flow the size of headings throughout the page.
6. Changed all `<div>` tags to coincide with more appropriate labels of division for the content.
7. the content section changed from `<div>` tags to `<article>` as these sections are main content. 
8. Benefits section changed `<div>` tags to `<aside>` tags to coincide with their sidebar information.
9. Wrapped the `<div>` with class of hero  with a figure tag due to the presence of an image being used within. `<figure>` is used to better label what that section is used as.
10. Created an unordered list within the Navigation bar found in the header. 

Overall, this project took place mostly inside the index.html file and fixed the structure of the html in order to make the legibility of the source code much easier to modify and follow.

# Credits 

All code refactoring was done through **Visual studio code**.

Original content and source code was provided by **Horiseon Social Solution Services, inc.** all content is reserved by Horiseon.

This Project was provided by **The University of Berkely Coding Bootcamp**.
