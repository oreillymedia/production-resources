---
layout: default
title: O'Reilly Word Template
---
# O'Reilly Media Word Template Quickstart Guide

Congratulations on joining the ranks of O'Reilly authors! We know you're anxious to get started writing, so this document has the bare essentials you'll need to begin working right away.

## System Requirements

This template was created using Word 2000 for Windows. Yeah, it’s kind of old. But it still works! There are many different versions of Word out there, so you might encounter some differences in your specific setup compared to what we talk about here. 

NOTE: Our template is not fully compatible with Microsoft Word 2008 for Mac. The styling buttons work pretty well, but most of the macros aren’t supported in this particular version of Word for Mac.

## Installing the Template

The template contains numerous customizations and macros (short programs written in Visual Basic for Applications, or VBA). In order for these customizations to work properly, and to be available whenever you're working on your manuscript, you'll need to store this template in a special templates folder on your computer.

NOTE: Like we mentioned before, there are a lot of versions of Word out there. You might have to adapt the following, depending on where your templates folder is.

### Installing on a Windows Machine

On most Windows systems, the Word templates folder is:

*C:\Documents and Settings\UserName\Application Data\Microsoft\Templates*

If you can't find this folder, another way to determine where Word stores your templates is to open up a new Word document, then choose File→Save As, then select "Document Template" from the pulldown menu at the bottom of the dialog box. This will automatically place you in the templates folder. Just make a note of where on your computer that folder is located. 

Once you've found the templates folder on your computer, move the template file to that folder. To be sure your installation was successful, go to File→New, and make sure that "ORA.dot" is listed as one of the choices.

### Installing on a Mac

Save the template to your desktop, then double-click to open it. When you open it, the title bar should read "ORA.dot", and not Document 1. If it doesn't say "ORA.dot", skip to the next section.

If the opened file says "ORA.dot", choose File→Save, and choose Save As Template. Save the template in your My Templates folder. Close the template, then exit and restart Word. The template will now be available from the Project Gallery. You can send the copy on your desktop to the Trash.

#### If the template opens as a document

If the template opens as a document, and not as a template (if it says "Document1" in the title bar, and not "ORA.dot"), close the document without saving changes. Move the ORA.dot file from your desktop to your My Templates folder. The template will now be available from the Project Gallery.

## The O'Reilly Menus and Toolbars

In addition to the two custom toolbars you should see on your screen (labeled "O'Reilly SmartStyler" and "O'Reilly Toolbar"—if you don't see them, go to View→Toolbars, and be sure they're checked), you'll notice two new menus, labeled "ORAStyles" and "ORATools." Among these toolbars and menus, you should be able to find most of the tools you'll need.

## Setting a Few Important Options

There are a few Word options that you should set to help yourself work better with the template. These aren't essential, but unless you have a compelling reason to want them off, you should probably turn and leave them on.

1.	Tools→Options→View→Field Shading→Always (note this is different from the check box marked "Field Codes")
2.	Tools→Options→View→Paragraph Marks
3.	Tools→Options→View→Bookmarks

## Paragraph and Character Styles

Now that you've arranged your workspace, you're ready to start writing. But first, you need to know that all of your text must have a *Style* applied to it. Every single paragraph needs to have a *Paragraph Style* applied, and if you want certain characters within a paragraph to look different than the rest of that paragraph, such as applying *Italics*, **Bold**, or `Literal`, you'll be using a *Character Style*. 

Styles are just named sets of formatting attributes, used to identify and group structurally identical elements in a document.
Once you've gotten familiar with the keyboard shortcuts and the SmartStyler, you'll find you won't need to spend much time searching for which style to use. But for now, know that you can find all the Paragraph and Character (also known as *Inline*) styles either from the menu labeled "ORAStyles," or on the O'Reilly Toolbar. They are grouped by category. There are a lot of them, for sure, but that's because we need a lot of them. Again, once you've adjusted to the SmartStyler and hopefully picked up a few keyboard shortcuts, you'll find you won't need to spend much time in these menus searching for styles.

There are two buttons on the SmartStyler that you may not recognize. The button marked "C" stands for `Code`, or `Literal`. This is for text that represents computer code or output. The "P" button stands for "Plain", and removes any character, or inline, formatting from the selected text. We encourage you to experiment with the SmartStyler to become familiar with its results.

### Hyperlinks, Filenames, and Technical Terms

Word kindly formats hyperlinks for you as you type. If you want to denote a hyperlink that Word doesn't recognize, you should use the "Hyperlink" style.

For richer hyperlinks, in which the text being linked isn't a URL, again use the "Hyperlink" style. Then associate the link with the appropriate URL by highlighting the Hyperlink-styled text, selecting the command Insert→Hyperlink, and entering the URL in the Insert Hyperlink dialog. Here's an example of such a hyperlink to [O'Reilly's website](http://www.oreilly.com). To see the associated URL after it's inserted, mouse over the hyperlink text, and the URL will appear in a yellow tooltip.

For filenames and directory paths, you should use the "Filename" style. For technical terms that you may want to emphasize when first introduced, you should use the "Technical Italic" style, which is also available from the keyboard shortcut "Ctrl+Shift+I." The only difference between "Technical Italic" and the "emphasis" style is that terms styled with "Technical Italic" don't appear in Word's spell check if you use the SmartStyler.

The SmartStyler recognizes context, not content, so cannot apply the "Technical Italic" style; that is left to your discretion. Please ask your editor if you're unsure of when to apply that style.

### Styles that follow other styles

As an added convenience, many of the Paragraph styles in the template have been set up so that pressing `Enter` at the end of the paragraph automatically makes the *next* paragraph the style that is most likely to follow it. Press `Enter` after a heading, and you're in *Body Text* style. Press `Enter` at the end of a *Sidebar Title*, and you're automatically placed in the Sidebar Body text style.

Of course, sometimes you'll want to use a style other than the default "next" style, but most of the time you'll find it a convenient timesaver.

## Lists and Notes

You'll soon find the need to convey information using a list, or perhaps put a Note or a Warning to accompany a topic. Though there are several types of lists (there are more than two dozen paragraph styles for lists alone), the SmartStyler will take care of remembering which style to use, even for lists within notes.

There are four types of lists you can use in your document:

* **Simple List:** This is a list of several short items, usually one or a few words each.
* **Bulleted List:** A list. With Bullets.
* **Numbered List:** Numbers instead of Bullets.
* **Variable List:** Usually made of a pair of items, a *term* and a *definition*.
* 
Except for the Simple List, all of the list types are available via buttons on the SmartStyler. You may nest lists, but only lists that aren't within another formatting element, such as Note or Sidebar. To create a nested list, use the "Increase Indent" button on the SmartStyler.

If you need to "continue" a list item, maybe if a bullet point needs more than one paragraph and you don't want a new bullet yet, you should press `Enter` at the end of the first paragraph in your list item, then press the "List Continue" button on the SmartStyler.

There are two types of Notes: *Notes* and *NoteWarnings*. There is a paragraph style for each. You can use the SmartStyler to create a list within a Note, or to insert a code snippet within a Note. If you're typing a paragraph in a Note or a Warning, then press `Enter`, pressing any of the List buttons on the SmartStyler will apply the correct list style.

## Tables and Figures

Headings and body text are fine for introductory information, but once you get into the meat of your subject, you'll probably be using some tables and figures. These can seem complicated at first, but the template will take care of most of the hard work for you. Here's a quick introduction to putting these important elements into your document.

### Tables

There are two main types of tables: *Captioned* and *Uncaptioned*. If your table requires a description, or if you expect to refer to it later elsewhere in the text, you probably want a Captioned table.

A Caption is different from a Heading row. A caption describes the entire table, while a heading row usually contains information about each column. Your Captioned tables might not have heading rows, and your Uncaptioned tables could still have heading rows. Don't worry, once you've seen a couple, it'll become much clearer.

To insert a table, click "Insert Table" on the O'Reilly toolbar. From there, choose whether or not you want a Caption, then whether or not you want a Heading row. The "Insert Table" dialog will come up on your screen. Fill in the number of rows and columns, and click "OK". If you've chosen a Captioned table, an auto-numbered caption will be inserted above the table, and filled in with dummy placeholder text, which you can then replace.

If you later decide you don't want a caption, simply delete it. If you decide another table needs a caption, just put a blank paragraph above it, put your cursor in it, then on the O'Reilly Toolbar click Insert Caption→Table Caption. In either case, the numbering will be adjusted automatically.

NOTE: Some of these commands are also available in other menus, such as the Table menu and the ORATools menu.

### Figures

Your figures will probably have captions, and most often, you'll be putting the caption in at the same time you put in the figure. 

To put a figure in your text, put your cursor in a blank paragraph, and on the O'Reilly Toolbar, click "Insert Figure with Caption". The "Insert Picture" dialog will come up; find the appropriate image, and click "Insert". Your Figure captions will include the auto-numbered prefix.

### Moving and Deleting Tables and Figures

When you insert a new Figure or Table, the numbering for all the other Figures and Tables updates automatically. But if you delete a Figure or Table, or just move one around, the numbering won't update until the next time you save the document, or the next time you insert a caption or cross reference. You can choose to update the numbering manually, by clicking "Insert Caption" on the O'Reilly Toolbar, and choosing "Update Caption Numbering."

## Code Examples

In addition to Tables and Figures, most O'Reilly books rely heavily on Code Examples to illustrate topics and provide examples and exercises. Sometimes your code will just be in two- or three-line snippets, but much of the time your examples will be larger blocks of code that you'll want to label and provide a caption for.

The captions for code examples go above the code itself, so to create a new code example, you'll probably first want to create the caption. Put your cursor in a blank paragraph, then on the O'Reilly Toolbar, go to Insert Caption→Example Caption.

NOTE: If you have text selected when you insert any type of caption, the selected text becomes the text of the caption, and the dummy text is not inserted.

When you've finished the caption, pressing `Enter` puts you into the proper "Code" style. When formatting Code examples, you should use the SmartStyler. For example, if you want one of the lines in your example to stand out in bold, just highlight the entire line, and press the "Bold" button. Also, the "Increase Indent" and "Decrease Indent" buttons will add or subtract leading spaces to selected Code paragraphs, in a default increment of 4 spaces.

NOTE: Since many of you write your code examples in a text editor or IDE, you'll probably want to cut and paste at least some code in from another application. If you do, you can use the menu option labeled "Paste As Code" under ORATools→Insert. This will ensure the text is stripped of any residual formatting from the other application (such as keyword coloring), and that any tabs are converted to the appropriate number of spaces.

### Code Length and Spacing Guidelines
Maximum line length for code varies slightly between book formats. For standard Animal books, the maximum line length for code is 80 characters, with 84 characters available in captioned examples. In small Animal books (6x9), standard line length for code is 63 characters, with 67 characters available in captioned examples. Pocket references have even smaller code line length—check with your editor for this information. 
Please make sure your code lines do not exceed these restrictions so that code lines don't run into the right margin when files are converted from Microsoft Word and prepared for typesetting. Indent using spaces, not tabs.







