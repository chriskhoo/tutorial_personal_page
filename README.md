# tutorial_personal_page
This is a tutorial that uses the basic HTML &amp; CSS to build a personal site.

## End product 
Click [here](https://chriskhoo.github.io/tutorial_personal_page) to see a sample of what we're building today. 

## Step by step instructions
Getting started
1. Create a folder in your desktop
2. In atom, create a blank document called index.html
3. In atom, create a blank document called style.css
4. Now use a boiler plate HTML 
5. Download normalize.css 
6. Link the normalize.css file to your HTML file
7. Link the style.css file to your HTML file below the normalize.css (ORDER MATTERS!!!)


In the HTML
1. Begin by using a boilerplate HTML template
2. Within the body, let's create a header 
3. In the header, add a photo of yourself
4. Then, add the title e.g. Chris' Blog
5. Create navigational bar, this is just is essentially a list of links, we'll use an unordered list to do this
6. Add 3 items: "About Me" | "My Favourite Dogs" | "My Favourite food"
7. Now, let's wrap these in "<a>" tags and for now, we'll just reference it to "#"

In the CSS - style the header
1. We'll begin by aligning all the text to the center of the header
2. Starting from the top, the face is looking too crammed let's give a margin on the top (40px, 0, 0, 0) 
3. And to smoothen it out a little, we can curve the edges using border-radius: 20px;
4. Next, let's make the title more prominent, it's time to go big or go home! (try 70px)
5. Now for the nav bar, first, we'll line up the links in a single row (hint: display)
6. But it's looking a little tight, so we'll add some space around the links using padding (0px 10px)
7. Notice, the ul's aren't perfectly center, so we'll set the padding to be 5px (all around)
8. Everything is looking a bit drab, so let's jazz up the header by giving it a nice background and adjust its sizing 
* background: url("") 
* background-size: cover;
9. Since the background image is a little dark, let's change the text to white to improve the contrast
10. But notice that the links are still blue, let's change those too (hint: a element)
11. Let's make the nav bar match, change the nav bar to rgba(0,0,0,0.5).
12. To make it stand out a little, we can add a solid white boarder of 4px

In HTML - let's add some content
1. Write a paragraph about you 
2. Write a paragraph about your favourite dogs
3. Write something about your favourite food
4. let's clean up the HTML by wrapping these paragraphs in article tags

In CSS - let's clean up the new content
1. Add some padding to the articles (20px) 
2. Let's make the width a little more managable, max-width: 500px
3. Now center the text using the margin 0 auto trick

In CSS - let's make the site responsive
1. Use a media query 
* @media (max-width: 500px) {} 
2. Now resize the title (36px) 
3. Update the nav bar 
* display: block;
* padding: 5 px; 
