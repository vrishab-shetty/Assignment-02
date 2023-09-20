
# Stacked is a Social Media website

###### Tags include:

1. *html*: HTML5 Boilplate
2. *header*: to display name and description of the website 
3. *footer*: to add contact details
4. *menu*: to create gender options in the form
5. *h1*: Highest text font size
6. *head*: Boilplate
11. *li*: to create a list
12. *nav*: to create navigation menu
13. *a*: to create hyperlink
14. *p*: describe the element in multiple line
15. *h2*: Second Highest text font size
16. *img*: to add images
17. *video*: to add video
18. *details*: to add summary
19. *title*: to add a title in the website
20. *form*: to create a eform
21. *input*: adds an input field
22. *textarea*: adds a large input field
23. *label*: to label the input field
24. *audio*: to add audio
25. *button*: to add button
26. *hr*: horizontal line across the website
26. *table*: creates a table
27. *tr*: adds a row
28. *td*: adds a data into the row
29. *link*: to link external css file and favicon


# Layout

###### Used *"display: grid"* and *"grid-template-area"*  to create column layout.
    - Home: I have a layout template as "sidebar main"
    - My Stacks: I have a layout template as "main"
    - Others: I have a fixed column size.

![ReferenceImage](/screenshots/Home.png)


# Navigation Menu

###### Used *"display: flex"* and *"media query"*  to make website responsive to different screen configuration changes.
```CSS
@media screen and (max-width: 538px) {
  .menu {
    gap: 0.6rem;
  }
}

@media (max-width: 768px) {
  .menu {
    flex-direction: row;
    position: absolute;
    background-color: #03c988;
    right: 0;
    left: 0;
    text-align: center;
    padding: 16px 0;
  }

  .menu li:hover {
    display: inline-block;
    background-color: #4c9e9e;
    transition: 0.3s ease;
  }

  .menu li {
    margin-top: 12px;
  }

  input[type="checked"]:checked ~ .menu {
    display: block;
  }

  .hamburger:hover ~ .menu {
    display: block;
  }

  .hamburger {
    display: block;
  }

  .dropdown {
    left: 50%;
    top: 30px;
    transform: translateX(35%);
  }

  .dropdown li:hover {
    background-color: #4c9e9e;
  }
}
```

# Table

###### Used *"table"* element and to create column layout template for details of the product.


![ReferenceImage](/screenshots/Details.png)

# SideBar

###### On the Home page, depending on the screen size the layout changes. 


![ReferenceImage](/screenshots/Home-Mobile.png)

# Gallery
###### Create a photo gallery for certification with hover effect and figure captions.

![ReferenceImage](/screenshots/Gallery.png)

# Other Features

###### Have implemented different *"media query"* to enhance the user experience. You can check it out by playing with Chrome's Developer Tool.



