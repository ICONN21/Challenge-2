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
Adding images to the page was relatively straigthforward. I had some difficulty when tring to airdorp the pictures from my phone to my computer. The pictures were not appearing in the correct fromat. While I could have convereted the images into a different format, I found if is imply screenshot the pictures, the links worked great and I was able to acomplish the intended goal. From there, it was simply a matter of styling the images to the desired format. 

Part 2: 
Linking the Nav links to the sections of the webpage requires a bit of research but in the end was rather simple. Creating unique ID's to the different sections of the webpage and filling them in after the "href" worked perfectly. The requirement for the images to be titles required adding an additonal 'p' tag to the ul. Giving the 'p tags' a class of "image-caption" made it easier to apply some styling to get things to line up how I wanted them.

Part 3:
In order to make the first image appear larger than the other two, I origanally added a class called 'larger-image'. The changes were not sticking due to other styleing that was taking precedence. By chaing the class to an id, the styling stuck and my image increased in size. After playing around with it a bit more to get the correct width and ensuring that it did not cover any other information when hoving over with the mouse, I got my intended design. 

Part 4:
Linking the image to the desired webpage was pretty straightforward. The trick here was that given I am still in the beginning of my development career, I only had one project to link to! Becuase of this I created a couple other links to some popular websites in order to keep witht he design of the webpage and make things look better. I will continue to update the webpage with additional projects as they deevlop. 

Part 5:
The final step in this process was to style the page to fit different formats such as mobile and desktop. To acheive this I used the

    