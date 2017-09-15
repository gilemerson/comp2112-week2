# PURPOSE: 
## To understand the power of querySelector etc... in action by modifying existing HTML elements on a webpage.
# DELIVERABLE: 
## One .js file, posted on GitHub, that includes all your code such that if I copy/paste it in the console while viewing a Chapters book on the webpage, it changes to whatever you decided.

1. goto www.chapters.ca
1. Click on any book to see its details

Using the console, do the following challenges using document.querySelector, document.querySelectorAll, and other js methods :

View all lessons below in playlist: https://scrimba.com/playlist/pRnVS9

3. View lesson https://scrimba.com/casts/co055-3403a8c0f053 

	1. Change the book title (listed on right hand side) to a food you love (example: 'French fries')
	1. View the lesson above, and only if you're really stuck, then [view the answer on Youtube](https://youtu.be/sBbu1PqXsu8)

4. View lesson https://scrimba.com/casts/co364-7337cec28d65 

	1. Change the book cover to a food picture (copy url of picture listed in http://images.google.com)
	1. View the lesson above, and only if you're really stuck, then [view the answer](https://youtu.be/z3-Brkn48eg)

5. View lesson  https://scrimba.com/casts/coaad-81d70665628f
	1. Change the nav menus to different words taken from an array that you create (example: let navTitles = ['a', 'b', 'c'])
	1. View the lesson above, and only if you're really stuck, then [view the answer](https://youtu.be/XrJpRiJJjA4)

6. View lesson  https://scrimba.com/casts/cLpzJtV
	1. Change logo by replacing the img element, with our own created <img> element.
	1. View the lesson above, and only if you're really stuck, then [view the answer](https://youtu.be/nwvMb3_UbQU)

7. View lesson  https://scrimba.com/casts/caqzMs3
	1. Using a template literal with an object to change innerHTML
```
function render(obj) {
   let snippet = `
   <ul>
    <li>${obj.name}</li>
    <li>${obj.calories}</li>
    <li>${obj.taste}</li>
   </ul>
   `;

	node.innerHTML = snippet;
}
render(object)
```

8. View lesson: https://scrimba.com/casts/cocbb-9743174ae496
	1. Use a template literal within a template literal to create multiple ul-blocks above, using an array of objects, then calling the render(obj) function by manually typing in the console:
```
	render(object[0]);
	render(object[1]);
	render(object[2]);
```

9. Make the book's author link go to www.georgiancollege.ca.  So if you hover over it you'll see the link at the bottom left corner (but don't click the link otherwise you'll lose your console session)


10. Make the button to "Add to Cart" so that it erases the body.
If you say document.documentElement.innerHTML = '' then you basically erase the entire body of the page

