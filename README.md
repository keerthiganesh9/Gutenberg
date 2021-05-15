# Gutenberg

The test case that is automated for "https://gutenberg.org/" website.

The test ase identified that can be automated is,
Step 1 - It will hit the url and validate for the title.
Step 2 - It will select the "Bookshelves" from the dropdown "Search and Browse".
Step 3 - It will search for "Fictional Bookshelf" category and click on it.
Step 4 - Now it will search for "Harry" in the search box and press on "Go".
Step 5 - Now it keep on searching till it finds "Harry" either in TITLE or AUTHOR, if it dosent match it the current page,it will press on the "NEXT" button and move to 
next page, this happens untill it is found and then exits.
Step 6 - if it is found then the current book is opened and check for the url if it is broken or not.
Step 7 - If not broken , displays a message saying "HAPPY READING !!"




List of test cases that can be automated,

* One thing what i have noticed is, after searching for a particular keyword in a particular category,the search results is not limited only to the keyword which is been 
searched, hence need to traverse to find the keyword in order to find the book.

* My test case has the ability to take the parameters and can run for any valid category and any valid TITLE/AUTHOR (only positive Test scenarios).

*The above described is a positive scenario where in we obtain the final validation .Similarly,

1) We can provide the invalid dropdown option to validate the test case.
2) We can provide the invalit TITLE/Author which is not present at all.
3) For every possible scenario we can write both positive and negative test cases in order to validate the UI.
        
