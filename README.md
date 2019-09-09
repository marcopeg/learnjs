# learning-webdev
Goal oriented Web Development roadmap that focuses on visible results that you can quickly share with your friends.

First step is on CodePen or similar web based IDE, so the student doesn’t need to deal with local setup.

- HTML
    - [Textual hello world](./codepen/html/hello-world.md)
    - Use different tags
    - Id / class attributes
- CSS
    - Use identifiers
    - Basic properties for font and colors
    - Pseudo classes for hover and similar stuff
- Javascript
    - (Make sure they see how to disable “auto run” in CodePen so they run code when they really want to)
    - Use functions - alert
    - Use variables - prompt > variable > alert prompted text
    - Use conditionals - prompt > variable > if (condition) alert “OK” else alert “NO”
    - Create a function: function with alert, then call the function
    - Events handlers
        - Click on button > alert “Hello”
        - Click on button > change class to item
        - input on change > update text in paragraph (or do animation with transitions on translate3D)
        - button on click > read from text > alert text > clear out input content > keep focus on input
    - DOM Handling
        - Click on button > create new “p” with progressive number inside (kept in the global scope), append newly created p to the body
        - Starting with 2/3 buttons on the page, when click, remove the button from the page (use IDs on each button, you may create many functions)
    - Arrays & Loops
        - Create an array of names, for each item, alert the item (forEach)
        - Create an array of names, for each item, create a P with the text and append it to the body (forEach)
        - Same exercise but first transform names into elements (map) then append (forEach)
        - Same as before but append only names that start with letter “a” (filter, map, forEach)
    - Single way rendering
        - Given an array and a pointer to a list UL (like the id), replace the contents in the list with LI mapped out of the array
        - With the previous code, add a text field and a button “add”. On click, read the text from the input, add it to the array and call the rendering function again
        - With the previous code, when click on an item, remove it from the array, call the render again



Second step is to get closer to a working setup with a real computer.
Mac or Windows

- bash (Mac or Win)
    - Move around file system
    - Create directory
    - Create file
    - Read file (cat)
    - Delete files and directories
    - Optional - edit files with vim or similar
- Setup for Coding
    - Editor (VSCode?)
    - NodeJS with NVM >> consider to this entirely via Docker ???
    - NPM / Yarn
- Use global packages
    - Run HTML “hello world” via simple node server
    - Run HTML “hello world” via ParcelJs
- Setup for Collaboration
    - Create GitHub Account
    - Create an empty repo and use it locally (learn what a repo is, commit, push/pull)
    - Exclude files from repository (.gitignore)
    - Write all the exercises done in CodePen as subfolders of the repository

Personal static website - using ParcelJS

- Create a simple CV with HTML and CSS. Add your image into it. Publish it as GitHub page using the “username.github.io” repository. (Organise the codebase, build parcel. Push source to one repo and push the build to the other)
- Split your cv in multiple pages and link them with “A” tag.
- Rework your CV using Twitter Bootstrap CSS framework as much as you can.
- Integrate Google Analytics into your website
- Integrate Disqus into your website
- Embed some of the CodePen you did as demonstration of what you can do




