# Reading 2

## JavaScript and jQuery book by Jon Duckett pages 293-301, 306-331 and 354-357

- jQuery: a JavaScript file that you include in your web pages which let yoou find elements using CSS-style selectors and the do something with the elements using jQuery methods.
- `jQuery()` = `$()` : a function let us find one or more elements in the page by creating an object called jQuery which holds refernces to those elements.
- We add jQuery to our code like this: `<script src="j s/ jquery-1 .11. 0 .js "></script> `.
- ***minification*** done in a  jQuery file with the file extension .min . js. which means **unnecessary spaces and carriage returns have been stripped from the file**.
- jQuery doesn't do anything you cannot achieve with pure JavaScript. It is just a JavaScript file but estimates show it has been used on over a
quarter of the sites on the web, because it makes coding **simpler**; it has  SIMPLE SELECTORS, COMMON TASKS IN LESS CODE and CROSS-BROWSER COMPATIBILITY.
- When we use jQuery we usually select elements using CSS-style selectors and other selectors.
------------------------------------------------------------------------------------------
- Matched set or jQuery selection: when we select one or more elements a **jQuery object** is returned.

- When we create a selection with jQuery, it stores a refernce to the corresponding nodes in the DOM tree. It does not create copies of them.

- A jQuery object stores reference to elements. Caching a jQuery object stores a refernce to it in a variable.

- The ability to update all of the elements in the jQuery selection is known as **implicit iteration**. 

- When we want to get information from a series of elements, we can use the `.each ()` method.

- If we want to use more than one jQuery method on the same selection of elements, we can list several methods at a time using **dot notation** to separate each one which is called **chaining**.

- `.ready()` method is used to check that the page is ready for our code to work with.

- The `.html()` and `.text()` methods both retrieve and update the content
of elements. 

- `.html` retrieves information an `.text()` retrieves text.

- `.replaceWith()` replaces every element in a matched set with new content. It also returns the replaced elements.

- `.remove()` removes all of the elements in the matched set.

- Inserting new elements involves two steps:
  1. Create the new elements in a jQuery object.
  2. Use a method to insert the content into the page uch as `.before()`, `.after()`, `.prepend()` and `.append()`.

- We can create attributes, or access and update their contents, using the following four methods:
  1. `.attr()`
  2. `.removeAttr()`
  3. `.addClass()`
  4. `.removeClass()`

- The `.css()` method let us retrieve and set the values of CSS properties. 

- Every event handling function receives an event object. It has methods and properties related to the event that occurred. 


## Article: 6 Reasons for Pair Programming

1. Greater efficiency: 
   * It is easier to catch mistakes in the making.
   * It takes slightly longer, but produces higher-quality code that doesn’t require later effort in troubleshooting and debugging.
   * When coming up with ideas and discussing solutions out loud, two programmers may come to a solution faster than one programmer on their own. 
   * Pairing enhances technical skills, team communication, and even enjoyability of coding in the workplace.

2. Engaged collaboration: 
    * When two programmers focus on the same code, the experience is more engaging and both programmers are more focused than if they were working alone.
    * It is harder to procrastinate or get off track when someone else is relying on you to complete the work.
    * When developers pair program, they rely more on each other and can often find a solution together without needing to ask for additional help. Ultimately, this boosts overall confidence.
    
3. Learning from fellow students:
    * Working with a teammate can expose developers to techniques they otherwise would not have thought of.
    * If one programmer is more experienced in a certain skill, they can teach a student who is less familiar with that area. The less experienced developer benefits from the experienced developer’s knowledge and guidance, and the latter benefits from explaining the topic in their own words, further solidifying their own understanding.

4. Social skills: 
    * Pair programming help programmers develop their interpersonal skills. When just grabbing the keyboard and taking over isn’t an option, getting good at finding the right words is a skill unto itself.
    * This has long-term career impacts. As much as employers want strong programmers, they know it’s essential to hire people who can work well with others.

5. Job interview readiness:
    * For most roles, the ability to work with and learn from others and stellar communication skills are as (or more!) important to a company than specific technical skills. Pair programming strengthens all of those skills.

6. Work environment readiness.



## Bookmark/Skim

### JavaScript and jQuery book by Jon Duckett pages 332-335
### JavaScript and jQuery book by Jon Duckett pages 302-305