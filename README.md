#tufteskine
Pelican Theme based on [Tufte CSS](https://github.com/edwardtufte/tufte-css).

## Usage
- Each page is an article. The index uses a section tag to logically group up articles. 
- Use section tags in general around each logical grouping of text and headings. 
- Using New Thought:  For this we use a span with the class newthought.


## Evolution
- Changed the font pixel size. Things look shit now. Very different from the page [here](https://edwardtufte.github.io/tufte-css/) 
- Tufte uses four levels of headings for his setup. If I use two levels for my blog title and subtitle, it kind of fucks up the rest of the blog. I attempted removing the header from the blog, it looks weird and empty. Could be that I need to do more work on this or perhaps use a different font style for this. It may very well be that you'd have to suck it up and use the different font style for blog title/subtitle.
- I have decided to go with the weird and empty look. Rationale. Some articles will be generated via rStudio and it is going to be fairly expensive to get that shit incorporated with the title. 
- Currently I have added almost all elements of the tufte css into an article. However, the article font now looks almost identical to [here](https://edwardtufte.github.io/tufte-css/). However the entire page itself looks weird. Perhaps because it is one long section. I need to figure out how to add sections in markdown and for them to go into blog sections. 
- I have modified the block quotes to be identical with Tufte. 
- I have fixed the footer. Cleaned up a lot of the old code.  

## References
[Tufte-CSS](https://edwardtufte.github.io/tufte-css/)
[Tufte-Jekyll](https://github.com/clayh53/tufte-jekyll/)


