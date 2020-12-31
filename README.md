# 6thmorpethscouts - info for editors


## Content 
Content pages are broken down into different sections to allow editors to change text without inadvertently altering code that would compromise the layout.

The content is written in markdown files (files with the extension .md). To edit, open a markdown file in Github by clicking on the pencil icon. Save your changes and the live site will be updated almost instantly.

beavers.md, cubs.md etc - these contain the main content of your page (the first text that will appear).
\_extras - the files in this folder appear as content in the boxes on each section's page.
\_full-width-contents - these files hold the content for the shaded area above the boxes (currently showing programme info for each section). Front matter of section, name, img. Section is very important as this is what tells the browser to show that information on the relevant page. Name is the subtitle that will appear on that section and img is for for adding an image to that part of the page. \_extras MUST have an image for consistency in the design. \_full-width-contents images are optional.

If no file exists, then no box/shaded area will appear.

## Images
All images should be uploaded to the 'images' folder. 

Other than the 'hero' image (the full width image) on the homepage, all other images are saved at 600x400 pixels (and 72dpi/pixels per inch) and will scale depending on where they appear on the site (e.g. images in the 3 columns on the homepage will appear smaller than an image added within the body of the Beavers page). Save all your images at 600x400 for consistency. 

Images have mostly been added through a page's 'front matter' to ensure they appear consistently in the layout.
When you open a markdown page, the 'front matter' is shown in a table at the top of that page. The front matter allows us to control what appears where, for example it tells the browser "if section = Cubs, show this content on the Cubs page".

To add an image to a page, replace the name of the image in the "img" field. If the img field is not visible, you will need to add it to the 'front matter' as per the example below.
The front matter is written between two lines of dashes (---) at the top of the markdown file, visible when in editing mode.

```
---
name: page name
img: imagename.jpg
---
```

## Site setup
Layout templates - these are files that control the layout of the pages. Editing these can break your site! They are found in the \_layouts folder. There are two layouts, one for the homepage and one for all other pages.

\_includes - these are parts that are reused across the site, such as the header (navigation) and footer that appear on every page. Again, editing these can break your site!




