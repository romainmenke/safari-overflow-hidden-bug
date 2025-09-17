# Safari 26 `overflow: hidden` bug

1. using iOS Safari 26
2. visit http://www.romainmenke.com/safari-overflow-hidden-bug/
3. scroll the page
4. open the overlay
5. scroll the page again

-----

When the overlay is open I expect the page to not be able to scroll.  
Instead the page scrolls underneath the overlay, despite having `overflow` set to `hidden`

For a screen recording see: https://github.com/romainmenke/safari-overflow-hidden-bug/issues/1
