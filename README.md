# Ghaida Alruwais's lab 7 starter
**Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.**

*Within a Github action that runs whenever code is pushed 
*Manually run them locally before pushing code
*Run them all after all development is completed

Choice: Within a Github action that runs whenever code is pushed, because it ensures that every time someone makes a change, the code is automatically tested.

**Would you use an end to end test to check if a function is returning the correct output? (yes/no)**
Choice: No, e2e tests user interactions with the entire application flow. They are not meant for checking single function outputs. I would use unit tests

**What is the difference between navigation and snapshot mode?**
Navigation mode analyzes a web page right after it loads.
Snapshot mode captures the page in its current state

**Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.**
1. Add a <meta name="viewport"> tag – This improves both accessibility and best practices scores.
2. Properly size images – Lighthouse reports a potential savings of 518 KiB. the images are larger than needed. Resizing images would significantly improve page load time.
3. Reduce unused JavaScript and CSS – Lighthouse indicates savings of 1MB (950 KiB JS, 261 KiB CSS). Removing unused resources can improve performance.




