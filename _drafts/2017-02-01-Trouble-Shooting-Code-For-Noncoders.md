---
layout: post
title: Trouble Shooting Code for Non-Coders
author: Steven Croft
bgimage:  
---

We know it is intimidating to try and help your student with their code if you have never coded before. If you see some red or pink on the coding page there are errors. These 5 tips will help you trouble shoot code even as a non-coder. It's easier than you think! 

## Trouble Shooting Code for Non-Coders
-----

### Tip #1: Check the Spelling
Often the simplest and quickest fix is just to check the spelling on the page. Pay close attention to what is inside the "< >" symbols. These are called tags and they tell the website how to draw the elements on the screen. If the spelling is not correct it may look funny. The most common mistake is writing <code><h1></h1></code> as <code><hi></hi></code>. They look very similar and it is an easy mistake to make if you are coding for the first time. <code><hi></hi></code> is not a tag and will not work properly. This same process can be applied to all code. Just check that the spelling matches the spelling in the video. 

To go along with this make sure there are spaces where they need to be. The most common one to see is inside the img tag <code><img src="imageName.png" width="300"></code>. Students often forget the space before the word width. This is key to the code functioning.

### Tip #2: Make Sure File Names are Accurate
The spell check extends to file names, like the name of the images used in the page. When the image is saved off of the internet the names are often long and complicated or just named download(1).jpg or the like. These file names have to be replicated exactly when typing them in the code. The biggest problem is that spaces, special characters, and the like can cause some problems. If there is a space in the name you will see %20 in the file name inside the code. This wont inherently cause problems but it is easier to check spelling if there are now spaces in the file name. Special characters like ( ) also cause problems when the site tries to render the image. The easiest way to avoid all of these problems is to use camel case when naming files. Camel case looks like this: thisIsCamelCase. The first letter of the file is lowercase but each subsequent word is capitalized without any any spaces. This eliminates any problems you might run into with file names. 

### Tip #3: Make Sure Each Bracket has a Matching Bracket 
With web based languages every open must have a close. This means that for every < or ( or { or [ there must be a matching >, ), }, or ]. This isn't a huge problem when first starting out as a coder. Most of the first few videos are fairly simple and the number of tags and such are small. Allowing you to see everything pretty clearly. But as the code gets more complex these matching brackets are hard to catch, and they don't always throw an error. The easiest way to check this is to do a command + f or control + f to open up the search box. Inside the search box enter the opening bracket. The box will tell you how many of those exist, then type in the closing one only and check to see if these numbers match. If they do not then you know what to look for. It is still tough to find the missing one but at least you know what is missing.

### Tip #4: Check for Tags Inside Tags
Tags should be outside of other tags. Nested tags, or tags inside tags, don't come until much later, at which point your student will have a firm grasp of where tags should sit. At the beginning stages of building a website it is important to watch where the open and closing tags are living. This: <code><h1>This is a big heading</h1> <img src="chosenImage.png"></code> is correct. The image tag comes outside of the h1 tag. However this: <code><h1>This is a big heading <img src="chosenImage.png"></h1></code> will cause some problems. It will still show on the screen but it will look a little off. Tags should exist outside of each other. Sometimes these are hard to notice so just check back to the video and walk through it step-by-step and make sure everything matches, be meticulous.


### Tip #5: Check Where the Files are Stored
If they are coding in Thimble this is not too big of an issue. As long as they have the file dragged into Thimble it is part of the file system and they can use it. However if they are coding in Brackets it gets a bit more complicated. Brackets does not have an internal file system like Thimble, it uses the folder system. Which means if there are any files, such as pictures, they have to be in the same folder that the student is coding in. If they are not in the folder Brackets has no idea that it exists and wont be able to use it.

### Bonus Tip: Post the code to the Help! Forum on app.hackingtons.com
If all else fails, which it does sometimes, post a link to the project on the Help! tab inside of app.hackingtons.com. The teachers of Hackingtons all review that tab and answer questions daily. We can take a look directly at the code and see what went wrong. If the student would like a more conversation style explanation come hang out with us during our live stream every Tuesday, Thursday, and Friday at 3:30pm. Here we answer questions, do live coding demos and interact with students through the chat. That way they can ask follow-up questions and get feedback right away.

# Happy Coding!
