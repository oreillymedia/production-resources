---
layout: default
title: styleguide
---
# O'Reilly Media Illustration Guidelines

This document will help you understand the procedure for using screenshots and technical illustrations in your project.

You can contact O'Reilly's Illustrator at <a href="mailto:dcps-illustrations@oreilly.com">dcps-illustrations@oreilly.com</a>.

## Types of Figures

There are two main types of figures: *screenshots* and drawn *illustrations*. 

Either type might also feature *callouts*, which are boxes, arrows, and text that might be added to a figure to aid the reader.

### Screenshots

*	Don't save screenshots as JPEGs. Please use TIF, PNG, or BMP.
*	Please capture the smallest necessary area when a full desktop screenshot is not required. The less in the screenshot, the easier it will be for your audience to read it.
*	Let us know if you require callouts, and supply one file with callouts added and one without. (Callouts are text, circles, lines, and arrows added to screenshots or photos that label or describe elements.)

### Drawn Illustrations

Most illustrations will be modified to fit the style of O'Reilly books. We're happy to work with you to create a refined graphic.

* Use whatever method is most comfortable for you when first creating your illlustrations: they can be sketched, described in text, or generated using a computer drawing program. 
* If you're using a program such as Visio, PowerPoint, Freehand, Illustrator, or another drawing program, please export your files as PDFs to ensure that there are no translation errors between computers.
* To help you generate the images, [we have templates in Adobe Illustrator](http://oreillymedia.github.io/production-resources/illustrations/image-stuff.zip) and as PDFs that should be able to be opened in your vector program of choice. Just let us know you want to try your hand at them! If you do choose to work with the Illustrator templates, please send us the .ai files you create, along with exported PDFs. 
* If you need to add callouts (such as arrows, boxes, or explanatory text) to your images, please include two versions of the image: a "clean" version without callouts, and version that mocks up the callouts you want. Our Illustrator will use standard O'Reilly fonts and specs to add callouts to the clean file, using your example as a guide. Use a file-naming convention that makes it clear which how a "clean" file relates to another image. For example, if your file with callouts is named *0102.png*, you should name the clean file *0102_clean.png*.

## Figure Sizing

When creating your figures or taking screenshots, please remember there are page size limitations. For most of our books, your images need to fit into a 4.8 x 7 inch space.

## Naming Your Files

Most authors prefer to use descriptive filenames. When naming your files, please don't use spaces or other non-standard characters, and please keep the names relatively short. Our Illustrator's scripts will sometimes choke with overly long filenames or files that have spaces in the names.

When your book is officially submitted to production, we'll run tools that convert your descriptive filenames (and in-source references) to our standard format, which numbers figures by chapter and order within chapter, as described in more detail below.

If you're willing to name your figure files by chapter and order within a chapter, that would be helpful to us (but not a requirement). For example, you could name the third image to appear in chapter 2 as *0203.png* (assuming a .png file in this example). 

If you're including a clean version of a file that has callouts, be sure to add *"_clean"* to the filename, so we can keep them related.

## Organizing with a Figure List

Organization is key. A well-organized figure list allows us to move your book through production more quickly and accurately. The figure list should contain the filename, position of the figure in the book, and caption for each figure. This is also where you tell us about callouts you need, whether we need to crop an image, and whether you need us to redraw something.

The Illustrator might not be looking at a PDF of your book or have access to source files, so a figure list is her best way of working accurately with your images.

When creating figure lists, please use the following conventions:

1. **Fig#**: The location of the figure in the printed book.
2. **Filename**: These are the names of the files you send to us. It is very important that this information be as accurate as possible.
3. **Type/Instructions**: Let us know if an illustration needs to be drawn or touched-up by our illustrator. Please provide instructions for cropping, adding callouts, etc.
4. **Figure Caption**: These are very helpful for us when trying to make solve a figure placement problem or when we need to make sure we're working with the correct image in the right place in the book.
 
Here's an example of an ideal figure list (this is also available as a [template for your use](https://docs.google.com/spreadsheets/d/1WWS5PicZC1ub6q9ckZ-i1y4nIga4_96ZSThkWgvQhgc/edit?usp=sharing)):

Fig #   |   Filename   | Type/Instructions   |  Caption
 --- | --- | --- | ---
 01-01 | some-file-name.pdf | Drawing. Please add an arrow pointing from the outside servers to the middle servers and label it "Workflow."   | Example of server setup showing an important idea.
 01-02 | my-favorite-picture.png | Screenshot. Please crop tightly on the top third. | This is what the top of thee page will look like.
 01-03 | hello-world-example.png | Screenshot | The image caption would go here.
 ... | ... | ... | ...
 02-01 | my-cat.png | Screenshot | Caption goes here.
 02-02 | Michael-Stipe.pdf | Drawing. Please keep the hand-drawn look and feel. | Caption goes here.
 
## Illustration Workflow Examples Showing Importance of Figure Lists

Here's an example showing how a figure list helps production handle images that need callouts.

In Atlas, figure files are usually added to the `images/` directory. Here's a screenshot of an `image/` directory as it might appear before production. In this example, the author is using descriptive filenames, and you'll see two version of the *aircraft_carrier.jpg* image. One version contains callouts added by the author, and one is clean (doesn't include callouts, which production will use to add callouts).

![Images directory before production](http://oreillymedia.github.io/production-resources/illustrations/images-dir-preproduction.png)

During production, we standardize both the filenames and the references to files in the source. We do this only for images that are actually referenced in the source files. Here's what an asciidoc reference to a figure would look like before production renamed the files:

![Figure reference before production](http://oreillymedia.github.io/production-resources/illustrations/fileref-before-prod.png)

And here's what it would look like after production. We apply a prefix (usually a few letters from the book's title), followed by the chapter number and order of the figure within the chapter (so the second image in chapter 1 would be "0102"). In this example, I've added "eidi" as the prefix, and this is the first image in chapter 1:

![Figure reference after production](http://oreillymedia.github.io/production-resources/illustrations/fileref-after-prod.png)

Now, if we take a look at the images directory again, we'll see that the file that is reference has been renamed, but the "clean" version (which wasn't explicitly referenced) has not been renamed:

![Images directory after production](http://oreillymedia.github.io/production-resources/illustrations/image-dir-postprod.png)

This is when a figure list is crucial. Without it, the illustrator won't know which file to use to redraw the callouts. She'll see that *eidi_0101.png* requires work, but won't have any idea where to find it.

And here's another scenario where we need a figure list:

Let's say that we've already renamed the files and we're well into QC, at which point the author spots some problems that require new figures. More often than not, the new image files that we get from authors will use the original descriptive names. So then a human has to try and sort it all out, which inevitably leads to either mistakes or much back and forth, or both. Again, a well-ordered figure list can help avoid this problem.







