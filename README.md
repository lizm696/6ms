# 6thmorpethscouts

## Site setup
Layout templates - in which folder\
where main content for each page is\
where additional content is

Creating new content - type of file, front matter required

Images - where to upload, how to insert, which content types use img in front matter, size

### Content 
The content is written in markdown files (files with the extension .md). To edit, open a markdown file in Github by clicking on the pencil icon. Save your changes and the live site will be updated almost instantly.

### Images
Other than the 'hero' image (the full width image) on the homepage, all other images are saved at 600x400 pixels (and 72dpi/pixels per inch) and will scale depending on where they appear on the site (e.g. images in the 3 columns on the homepage will appear smaller than an image added within the body of the Beavers page). You can therefore save all your images at 600x400 for consistency. 

Images are added through a page's 'front matter' to ensure they appear consistently in the layout.
When you open a mardown page, the 'front matter' is shown in a table at the top of that page. The front matter allows us to control what appears where, for example it tells the browser "if section = Cubs, show this content on the Cubs page".

To add an image to a page, replace the name of the image in the "img" field. If the img field is not visible, you will need to add it to the 'front matter' as per the example below.
The front matter is written between two lines of dashes (---) at the top of the markdown file, visible when in editing mode.

```
---
name: page name
img: imagename.jpg
---
```





