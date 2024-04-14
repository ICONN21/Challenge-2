# Challenge-2
Challenge number 2 - Creating a User Profile. 

Creating this webpage presented many fun but difficult obsicles. Fortunately, we had recently covered many of the tools I deployed in class! 

The acceptance critera was as follows: 

```
GIVEN I need to sample a potential employee's previous work
WHEN I load their portfolio
THEN I am presented with the developer's name, a recent photo or avatar, and links to sections about them, their work, and how to contact them
WHEN I click one of the links in the navigation
THEN the UI scrolls to the corresponding section
WHEN I click on the link to the section about their work
THEN the UI scrolls to a section with titled images of the developer's applications
WHEN I am presented with the developer's first application
THEN that application's image should be larger in size than the others
WHEN I click on the images of the applications
THEN I am taken to that deployed application
WHEN I resize the page or view the site on various screens and devices
THEN I am presented with a responsive layout that adapts to my viewport
```

Part 1:
Incorporating images into the page proved to be a relatively straightforward task. However, I encountered a minor challenge when attempting to transfer the images from my phone to my computer via airdrop. The images weren't appearing in the correct format initially. While I could have converted the images to a different format, I found that simply screenshotting them resolved the issue, and the links worked seamlessly, allowing me to achieve the intended goal effortlessly. Subsequently, styling the images to the desired format was a straightforward process.

Part 2:
Linking the navigation links to the sections of the webpage required some initial research, but ultimately, it was a straightforward task. Creating unique IDs for the different sections of the webpage and incorporating them into the "href" attribute worked perfectly. Additionally, fulfilling the requirement for the images to have titles necessitated adding an additional 'p' tag to the 'ul'. Assigning a class of "image-caption" to the 'p' tags facilitated easier styling to ensure alignment according to my preferences.

Part 3:
To ensure that the first image appeared larger than the other two, I initially attempted to apply a class called 'larger-image'. However, I encountered difficulties as other styles were taking precedence. By changing the class to an ID, the styling persisted, resulting in the desired increase in image size. After some experimentation to determine the optimal width and ensure that it didn't obscure any other information when hovered over with the mouse, I achieved the intended design.

Part 4:
Linking the image to the desired webpage was a straightforward process. However, as I am still in the early stages of my development career, I only had one project to link to. To maintain the design consistency of the webpage and enhance its appearance, I created additional links to some popular websites. I plan to continually update the webpage with additional projects as they develop over time.

Part 5:
The final step in this process involved styling the page to accommodate various screen formats, including mobile and desktop. To achieve this, I utilized the 'flex-wrap: wrap;' property, allowing the elements to wrap around themselves as the screen size decreases. While media screen breaks could have been employed, I achieved the desired outcome efficiently with the 'flex-wrap' property, minimizing the need for additional lines of code.
    

https://github.com/ICONN21/Challenge-2

Ian Connor 