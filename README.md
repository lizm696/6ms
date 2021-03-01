# 6thmorpethscouts - info for editors

## Content 
The site uses a 'content management system' called Netlify CMS. You can edit the content easily through Netlify (which then pushes the changes to this Github repository) or edit the files directly in Github. Netlify gives you a user-friendly interface for editing and means you don't really need to know a lot of Markdown.

## Images
Images can be uploaded when editing through Netlify. If uploading directly to Github, all images should be uploaded to the 'images' folder. 

Other than the 'hero' image (the full width image) on the homepage, all other images are saved at 600x400 pixels (and 72dpi/pixels per inch) and will scale depending on where they appear on the site (e.g. images in the 3 columns on the homepage will appear smaller than an image added within the body of the Beavers page). Save all your images at 600x400 for consistency. 

## Site setup
### Layout templates
These are files that control the layout of the pages. Editing these can break your site! They are found in the \_layouts folder. There are 3 layouts, one for the homepage, one for section pages (i.e. Cubs, Scouts) and a generic layout (without the features boxes that appear on section pages)

### \_includes
These are parts that are reused across the site, such as the header (navigation) and footer that appear on every page. Again, editing these can break your site!

### homepage-features
These are the items that appear in the three columns/boxes on the homepage, before the footer section. Again, these can be edited and created through Netlify.

## Deleting and creating pages
This must be done from the Github repository, it cannot currently be done through Netlify. 

Before creating a new page, think about how this will affect the structure of your site. Can the content be incorporated into an existing page or does it need a page of its own? 

All pages other than the homepage and section pages use the 'blank' page layout (a full page layout without the feature boxes you see on section pages).

### To create a new page

* Go to the Github root repository (where you will find pages like join.md and location.md)
* Create a new file with the .md extension, e.g. mynewpage.md
* Keep the file name succint, lowercase and without spaces
* Click on the pencil icon to edit your page
* Put the following at the very top of the file (including the ---):

>\---  
title: Your Page Title  
layout: blank  
\---  

* Save the file

#### Add the page to the site navigation

* Go to the data folder
* Open navigation.yml
* Enter two new lines for your new page, copying the format you see for the other pages listed, e.g.

>abcd

### To delete a page

* Ensure you remove any links within the site that point to the page being deleted
* Find the file in the Github repository and click on it
* Click on the trash can icon on the right (next to the pencil icon)
* Click 'Commit changes' and the page will be deleted
