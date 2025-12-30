# Volusion-Blog-Page-Javascript
This is the Javascript function used for reversing the order of the blog html elements
It will find all html elements with the class blog-card, then create a a variable of total based on how many elements were found, and from there it will assign each element a css order property based on the total variable minus its current index (which index starts at 0). As an example, if the total variable is 9 blog cards, the third blog-card element in the index (which since starting at 0 would mean it would have an index of 2) would be assigned an order of 7 because it would be 9 - 2

This way it essentially reverses the display order of the html elements so merchants do not have to worry about adding new blog cards to the top of the html card elements, but can more easily just add it below the last entry, and the last one will show up first as it will be the "latest entry". The pain point this solves is ease of use.
