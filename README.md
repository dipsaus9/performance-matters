# IMG Performance
I've checked multiple ways to get a better performance on the Bootstrap website. This part will describe the way I optimalized the Images.

## IMG Minifiy
I tested this part on the getting started page. This page loads multiple images. These images are really slowing the page down. By using a simple compression method. I used Tinypng for the compression method.
This results into a 60% compression. That is a lot.

I also wanted to change the sourceset but this didn't result into a difference for this page.

Before:
![Image loading time](https://raw.githubusercontent.com/dipsaus9/performance-matters/IMG-A/img.png)

After:
![Image loading time after](https://raw.githubusercontent.com/dipsaus9/performance-matters/IMG-A/miniefed_img.png)

After this I formated all the images to the WebP images. This resulted in a 40kb win.

After with WebP:
![Image loading time webP after](https://raw.githubusercontent.com/dipsaus9/performance-matters/IMG-A/miniefed_img_webp.png)
