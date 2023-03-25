# umn-edx-module-1-challenge-code-refactor

## Summary
This is my code for the first homework/challenge from the Minnesota Coding Bootcamp.  The general idea was refactor the HTML page to use semantic tags, but I also took the opportunity to slim down the CSS a bit since there were classes with the same styling that were used once.

## Notes
Since the affected classes no longer have any specific styling, I debated leaving them there in case there are changes down the line that might use them, but ultimately decided to remove them for code cleanliness.

I also wanted to condense all the definitions of text color to white as the default and have black for the footer, but left it as is since two separate elements with text in the footer meant minimal reduction in the CSS length.

I left the sidebar headings as *h3* since they seemed less important that the main article headings.  If I were to make them *h2*, the styling would be updated to set the *aside h2* to have *font-size: 1.17em* so the visual size would remain unchanged.

I debated replacing the *.hero* class with a *picture* element, but the image being used as a background of the one element did not seem to fit the use of a *picture* element containing more than one image size and/or captioning, so I left it as is.

## Live View
The page can be viewed here: https://thinkbui.github.io/umn-edx-module-1-challenge-code-refactor/
