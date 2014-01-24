# Embedding Media
Embedding media, such as videos and images, is easy with HelpPag.es.

## Images
![shoe](/img/crawling-shoe.gif)

The standard syntax with Markdown for images is `![title here](image-url-here)`.  Not too bad, right?  Trouble is, you'd normally still need to worry about hosting your image online and getting it somewhere that your pages have access too.  Bit of a pain.  With HelpPag.es, we wanted to make this easier.  To embed an image, simply drop your image into your repo and link to it relative to the root path.  

For example, we recommend that you make a folder called `img` in your repo and drop images in there.  To include one in your doc, just add:

```
![image title](/img/picture-1.jpg)
```
We'll load your images into a lightning fast CDN and render them from there for you.

## Videos
<http://www.youtube.com/watch?v=lm8oxC24QZc>

Yes, even videos.  Just throw in a youtube link just like any other link using the `[title-here](http://link-goes-here)` syntax, or the shorter `<link-goes-here.com>` syntax and we'll turn it into an embedded video.  Looking for more than just youtube videos?  Let us know on the [feedback page](https://github.com/helppages/feedback/issues).