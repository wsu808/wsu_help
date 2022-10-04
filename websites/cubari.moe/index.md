## What is [cubari.moe](https://cubari.moe/)?
> "This website is an image proxy. It takes images from other websites and displays them in a better manga-oriented reader, Cubari."  
~cubari.moe website

`ℹ️` You can also use it with [Tachiyomi](https://tachiyomi.org/) Cubari extension for easier reading on android devices.

## How to create own comic?
a)  Use [stirante.com/facaccimo](https://stirante.com/facaccimo/). It provides GUI for creating github gists that Cubari uses. (Mind that URLs are separated by new lines). 

b) If you prefer to create file with links by yourself follow instructions in [this reddit post](https://www.reddit.com/r/manga/comments/mcicbp/sl_how_to_host_a_series_on_imgur_with_guyamoe/).

## How to obtain URLs of images from website?
Some sites post comic and have a certain naming convention. You can:
1. Use **link grabber** function in [Jdownloader](https://jdownloader.org/) to obtain them.  
    > It's located in bottom left corner of program's window
2. **Sort by name** and choose links to images that are part of the actual comic. 
    > You can also sort **by size** first (useful when site provide both low and high quality of images or display thumbnails with the same name) and delete unwanted links.
3. [One-time configuration] In right-click menu choose `Manage Settings` add `Copy` field and choose to copy **URL only**.
4. Select aplicable links and right-click them. 
5. Select copy and then paste them in your file.

---

## How to create chapter from Imgur album
Here we will be using cubari's proxy option

1. Let's assume we have an imgur link like:  
	`https://imgur.com/a/x67SjZ5`
2. Change the link to:  
	`/proxy/api/imgur/chapter/x67SjZ5/`  
		`ℹ️` Mind that the characters sequence at the end is you unique album identifier  
		`⚠️` Don't forget the slash `/` at the very end of the line
3. Check the `✅ Proxy` checkbox and paste the link like the one above into the input field below `✅ Proxy` label.

---

## How to add text between pages
If you need to add some short text before or after page use [placeholder.com](https://placeholder.com/) to easily insert image containing caption.
