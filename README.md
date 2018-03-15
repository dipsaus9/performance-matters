# JS Performance	
I've checked multiple ways to get a better performance on the Bootstrap website. This part will describe the way I optimalized the JS.	
	
## JS Minifiy	
Again for this project Minifiying the files will give you a huge difference. The most import isue here is the amount of function being loaded into the browser. It is a good thing browsers support a cache function. This website really needs this.	
If you minify all the JS files this will be the result:	
	
Before:	
![Without minify](https://raw.githubusercontent.com/dipsaus9/performance-matters/JS-A/js_without_minify.png)	
	
After:	
![With minify](https://raw.githubusercontent.com/dipsaus9/performance-matters/JS-A/js_with_minify.png)	
	
You can see the diffrence in the loading time of the JS files.	
	
When we look into the JS files you can see clearly the page needs a JS file for IE support. But we are testing on Chrome so we don't need this script here.	
	
`<!--[if IE]><script src="/assets/js/ie10-viewport-bug-workaround.js"></script><![endif]-->`	
	
This results into a page that only loads this script on IE.	
	
Result:	
![With minify and without IE script](https://raw.githubusercontent.com/dipsaus9/performance-matters/JS-A/js_disableie.png)
