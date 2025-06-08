# Bug List

> Make a list of the things that don't work as expected. Keep a list of things that you have fixed and try to document how you solved them.

1. Tried to use the same codes to connect the first two buttons but they both lead to the same page. 
2. Tried using if-statements but ended up with two functions instead, one for each button.  
3. I have been searching for ways to get buttons on multiple pages. I now think it would be better to update the two buttons from page 1 since every page is going to have two buttons.
4. There are no buttons on page 2.1. I could replace the text on page 1 with the text of the new page?
5. How do I make the same button update the text on the screen several times? Can I hide the headline when leaving the first page?
6. I do need to think about a way to get the text box on a different page. Maybe also get a cover for the book. 
7. Adding a button to a text box is not good enough if the user doesn't get any output that shows that their input has been stored. I think that changing the text of the button from 'Enter' to something else would be a good way to show that the button actually did work.
8. I should also add a name that shows if the user doesn't enter any text. 
9. The two buttons both output both the pages that I am trying to connect. I want them to output different pages. I hade the same function name for both buttons, they now have different function names and work so far. 
10. I tried to output the third page of the book but now I can't reach page 2.2.
11. Tested the first sequence and it shows in the console but now I get "Undefined" as an output on the screen. 
12. Tried to change color on some text but the entire code went white/yellow.
13. Because I am using innerHTML for my 'Welcome' page I had to use <span style></span> to change color on the text because otherwise the code could be read by the webbrowser. 
14. Pages are not showing in the right order.  
15. If the user doesn't type anything in the textbox that empty string also replaces the name I    wanted to replace IF the user typed their name. Meaning there are no longer a name in those  places in the book. I had to add an if-statement to define that the name 'Carlos' should only be replaced if the user typed something before pushing Enter.    
16. After I added Autocomplete and that worked, I also added Localstorage but then Autocomplete stopped working. I had to stop the page from reloading directly because the web-browser didn't have time to save the input.  
17. Still don't get the right lines from the arrays to show. Line 1 is the only one that works correct. 
18. Changed text on the buttons depending on what page you're on but the button text from the last page stayed and updated the text of the buttons for page 1. I had to reset them when starting the book over again. 
19. The text of the buttons didn't change. I had to change from , to || (or).
20. Tried again to output the right pages but now are all pages 3 missing. 
21. Page 3 is now showing but it's the wrong page 3 in every sequence except seq 1 and seq 2. 
22. The text of the buttons on page 3.2, 3.3 och 3.4 didn't update as expected. 
23. Somehow I got the text of the buttons mixed up. The text on the left button should have been on the right button and the other way around. I started to change the text but since I have buttons that has 'A' and 'B' on them it looked confusing when they said 'B' and 'A'. I decided to simply change place on the buttons. So now the button to the left is called 'rightButton' and the other way around, in the code. There's brobably better ways to fix the problem but it works. I came back to this after giving it some thoughts and I decided to change place on the book-pages texts in the variables instead.    
24. Added the page number to the bottom of the page but it doesn't show the way I wanted it to. I had to stop page number 4 to show using an empty string. I also had to add some code in showPage. 
25. The text-box now dissapear when the user typed their name and pushed 'Enter'. It does show though, when you reload or restart the page. Where the text 'Welcome back' is shown. 
26. The text might look strange, single words on some rows, if the user types a long name. So I removed most of the <br> that I had added to the text. This also made the text look better hold together.  
27. Index 1 is not showing in the console. I wrote 'index: 1;' in the code but it should have been 'index = 1;'. 
28. I have added the users steps to the console, but it shows the wrong (other) button. I think it might have something to do with me changing place of the texts.       