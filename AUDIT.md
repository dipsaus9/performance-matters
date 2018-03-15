#CSS Performance
I've checked multiple ways to get a better performance on the Bootstrap website. This part will describe the way I optimalized the CSS.

## CSS Minifiy
This may sound like a easy solution and it is. By doing this the wesbite will load a lot faster. First I placed all the css on the end of the page. This will result in a fast loading page. The only problem with this is a page being loaded without css. After 1 or 2 seconds the page will jump to the right css. This is a very annoying feeling. To solve this problem I created a crictical css. The crictical will create all the css shown on the first page / first viewheight. This will prevent the page from jumping. After this I minfied all the remaining css. The font css was disabling the text from showing till the text was loaded.
`font-display: swap`
If you use this code u can tell the browser to use a system font till the custom font is loaded. This way you can always see the text while the page is still loading.

Using these methods I created a faster page. This also results into a faster loading first paint. This give the user a better experience. 
