---
layout: default
title: O'Reilly Word Template
---
# O'Reilly Media Word Template Quickstart Guide

Congratulations on joining the ranks of O'Reilly authors and templaters! We know you're anxious to get started, so this document has the bare essentials you'll need to begin working right away, including the <a href="orm-styles.dotm">O'Reilly Word template</a>, which contains all the custom styles we use when templating book content.

If you are an author, please note that it is common for a copyeditor to template Word files before they are converted into HTML, so if your files are not 100% templated (or not templated at all), don't worry about that!

<h2 id="table-of-contents-word">Table of Contents</h2>

* <a href="#installing">Installing the Template</a>
  * <a href="#install-windows">Installing on a Windows Machine</a>
  * <a href="#install-mac">Installing on a Mac</a>
  * <a href="#enabling-macros">Enabling Macros: Windows and Mac</a>
  * <a href="#template_existing">Starting to Template an Existing Chapter</a>
* <a href="#menus-toolbars">The O'Reilly Menus and Toolbars</a>
* <a href="#setting-options">Setting a Few Important Options</a>
* <a href="#paragraph-character-styles">Paragraph and Character Styles</a>
  * <a href="#styles-follow-styles">Styles that Follow Other Styles</a>
* <a href="#lists-notes">Lists and Notes</a>
* <a href="#tables-figures">Tables and Figures</a>
  * <a href="#tables">Tables</a>
  * <a href="#figures">Figures</a>
* <a href="#code-examples">Code Examples</a>
  * <a href="#code-length">Code Length and Spacing Guidelines</a>
  * <a href="#syntax-highlighting">Code Syntax Highlighting</a>
  * <a href="#code-annotation">Code Annotations</a>
* <a href="#xrefs">Cross References</a>
* <a href="#misc">Miscellany</a>
  * <a href="#keyboard-shortcuts">Keyboard Shortcuts</a>
  * <a href="#tabs-spaces">Tabs and Spaces</a>
  * <a href="#blank-lines">Blank lines</a>
  * <a href="#help">Getting Help</a>


<h2 id="installing">Installing the Template</h2>

Designed to work with all recent versions of Microsoft Word, the O'Reilly Word template for books contains numerous custom styles and macros (short programs written in Visual Basic for Applications, or VBA). In order for these customizations to work properly, and to be available whenever you're working on your manuscript, you'll need to:

* Store the template in a special templates folder on your computer.
* Ensure your Word settings are configured to allow macros to run.

We'll walk through these steps in the following subsections.

<div data-type="note">
  <h6>Note</h6>
  <p>There are a lot of versions of Word out there! You might have to adapt the following, depending on where your templates folder is.</p>
</div>

<h3 id="install-windows">Installing on a Windows Machine</h3>

On most Windows systems, the Word templates folder is:

*C:\Documents and Settings\UserName\Application Data\Microsoft\Templates*

If you can't find this folder, another way to determine where Word stores your templates is to open up a new Word document, then choose **File→Save As**, then select **Document Template** from the pulldown menu at the bottom of the dialog box. This will automatically place you in the templates folder. Just make a note of where on your computer that folder is located. 

Once you've found the templates folder on your computer, move the template file to that folder. To be sure your installation was successful, go to **File→New from Template**, and make sure that "orm-styles.dotm" is listed as one of the choices.

<h3 id="install-mac">Installing on a Mac</h3>

Save the template to your desktop, then double-click to open it. When you open it, the title bar should read "orm-styles.dotm", and not "Document 1". If it doesn't say "orm-styles.dotm", skip to the next section.

If the opened file says "orm-styles.dotm", choose **File→Save**, and choose **Save As Template**. Save the template in your *My Templates* folder. Close the template, then exit and restart Word. The template will now be available from the Project Gallery. You can send the copy on your desktop to the Trash.

#### If the template opens as a document

If the template opens as a document, and not as a template (if it says "Document1" in the title bar, and not "orm-styles.dotm"), close the document without saving changes. Move the _orm-styles.dotm_ file from your desktop to your *My Templates* folder. The template will now be available from the Project Gallery.

<h3 id="enabling-macros">Enabling Macros: Windows and Mac</h3>

By virtue of having saved the template in the Word templates folder (a trusted location), the template's macros will likely work on your machine by default. If they do not, you can follow these steps to enable macros:

1. In Microsoft Word, navigate to File > Options.
2. Select Trust Center, then choose Trust Center Settings.
3. In the Trust Center, select Macro Settings.
4. Select "Enable all macros" and click OK. 
   
Alternatively, you can select "Disable all macros with notification." In this case, you will be notified whenever you open a document containing macros, and can then enable them on a case-by-case basis.

These steps may vary slightly depending on your version of Microsoft Word.

<h3 id="template_existing">Starting to Template an Existing Chapter</h3>

If you are templating an existing chapter that does not have any paragraph styles applied, you can attach the template to the document by going to Tools > Templates and Add-ins, clicking Attach... and selecting the orm-styles.dotm template from the explorer/finder window. Make sure "Automatically update document styles" is checked, then click OK. You can now apply template styles using the Style pane or the macro buttons. Note that these steps may vary slightly, depending on your version of Microsoft Word.

Alternatively, you can create a new document for the chapter content (File→New from Template). In the pop-up that appears, select My Templates (or Templates) and then orm-styles.dotm (if this option does not appear, go back to the installation steps). You can then copy-paste the original chapter content into the new document and apply template styles using the Style pane. There is a cheat sheet of common template styles at https://oreil.ly/word-template-styles.

<h2 id="menus-toolbars">The O'Reilly Menus and Toolbars</h2>

In addition to the custom styles described in subsequent sections, the template comes with an ORM Tools tab on the Word ribbon. This tab provides access to all of our custom styles, as well as some utilities designed to make the job of templating documents a little easier.  

<h2 id="setting-options">Setting a Few Important Options</h2>

There are a few Word options that you should set to help yourself work better with the template. These aren't essential, but unless you have a compelling reason to want them off, you should probably turn and leave them on.

1.	Tools→Options→View→Field Shading→Always (note this is different from the check box marked "Field Codes")
2.	Tools→Options→View→Paragraph Marks
3.	Tools→Options→View→Bookmarks

Please also make sure "All Markup" is selected in the Review tab. If that drop-down is set to "No Markup," Track Changes will be present, but hidden.

<h2 id="paragraph-character-styles">Paragraph and Character Styles</h2>

Now that you've arranged your workspace, you're ready to start templating, or applying O'Reilly's custom styles throughout the document.   

Styles are just named sets of formatting attributes, used to identify and group structurally identical elements in a document. Many paragraphs and snippets of text in your document will need to have styles applied to them. Standard paragraphs do not need to have a _Paragraph Style_ applied, but all other "block" elements (to borrow a term from HTML parlance), such as list items, preformatted text (i.e., code listings), and block quotes or epigraphs will need to be styled with the appropriate Paragraph Style. In addition, if you want certain characters within a paragraph (or other block element) to look different than the rest of that paragraph, such as applying *Italics*, **Bold**, or `Literal`, you'll be using a *Character Style*. 

There is a cheat sheet of common template styles at https://oreil.ly/word-template-styles.

<h3 id="styles-follow-styles">Styles that Follow Other Styles</h3>

As an added convenience, many of the Paragraph Styles in the template have been set up so that pressing `Enter` at the end of the paragraph automatically makes the *next* paragraph the style that is most likely to follow it. Press `Enter` after a heading, and you're in *normal* style (the default style used for standard paragraph text). Press `Enter` at the end of a *Sidebar Title*, and you're automatically placed in the *Sidebar Body* text style.

Of course, sometimes you'll want to use a style other than the default "next" style, but most of the time you'll find it a convenient timesaver.

<h2 id="lists-notes">Lists and Notes</h2>

You'll soon find the need to convey information using a list, or perhaps include a Note, a Tip, or a Warning to accompany a topic. There are four types of lists you can use in your document:

* **Simple List:** This is a list of several short items, usually one or a few words each.
* **Bulleted List:** A list. With Bullets.
* **Numbered List:** Numbers instead of Bullets.
* **Variable List:** Usually made of a pair of items, a *term* and a *definition*.
 
Except for the "Simple List", all of the list types are available via buttons on the SmartStyler. You may nest lists, but only lists that aren't within another formatting element, such as Note or Sidebar. To create a nested list, use the "Increase Indent" button on the SmartStyler.

If you need to "continue" a list item, maybe if a bullet point needs more than one paragraph and you don't want a new bullet yet, you should press `Enter` at the end of the first paragraph in your list item, then press the "List Continuation" button on the SmartStyler.

There are three types of Notes: *Notes*, *NoteTips*, and *NoteWarnings*. There is a paragraph style for each. You can use the SmartStyler to create a list within a Note, or to insert a code snippet within a Note. If you're typing a paragraph in a Note or a Warning, then press `Enter`, pressing any of the List buttons on the SmartStyler will apply the correct list style.

<h2 id="tables-figures">Tables and Figures</h2>

Headings and body text are fine for introductory information, but once you get into the meat of your subject, you'll probably be using some tables and figures. Here's a quick introduction to putting these important elements into your document.

<h3 id="tables">Tables</h3>

There are two main types of tables: *captioned* and *uncaptioned*. If your table requires a description, or if you expect to refer to it later elsewhere in the text, you probably want a captioned table.

A caption is different from a heading row. A caption describes the entire table, while a heading row usually contains information about each column. Your captioned tables might not have heading rows, and your uncaptioned tables could still have heading rows. Don't worry, once you've seen a couple, it'll become much clearer.

You can use Word's built-in table tools (Insert > Table) to insert a table in your document. If the table should have a caption, simply add the caption line above the table. It should be preceded by a numbered label indicating its place in the document's sequence of tables: e.g., "Table 7-1. This is my table caption." Table captions are styled using the TableTitle style, and table column headings are styled using the CellHeading style.

To include a reference to the table in the text, simply refer to the table by number: "As shown in Table 7-1, ..."

<h3 id="figures">Figures</h3>

Your figures will probably have captions, and most often, you'll be putting the caption in at the same time you put in the figure. 

You can use Word's built-in image tools (Insert > Pictures) to add a figure to the document. If the figure should have a caption, simply add the caption line below the figure. It should be preceded by a numbered label indicating its place in the document's sequence of figures: e.g., "Figure 1-2. This is my figure caption." Figure captions are styled using the FigureTitle style, and the images themselves are styled using the FigureHolder style.

To include a reference to the figure in the text, simply refer to the figure by number: "As shown in Figure 1-2, ..."

<h2 id="code-examples">Code Examples</h2>

In addition to Tables and Figures, most O'Reilly books rely heavily on Code Examples to illustrate topics and provide examples and exercises. Sometimes your code will just be in two- or three-line snippets, but much of the time your examples will be larger blocks of code that you'll want to label and provide a caption for.

The captions for code examples go above the code itself. As with tables and figures, code example captions should be preceded by a numbered label indicating there place in the document's sequence of examples: e.g., "Example 4-5. This is my example caption." Example captions are styled using the ExampleTitle style.

To include a reference to the example in the text, simply refer to the example by number: "As shown in Example 4-5, ..."

<div data-type="note">
  <h6>Note</h6>
  <p>If you write your code examples in a text editor or IDE, you'll probably want to cut and paste at least some code in from another application. When doing so, please make sure to convert any tab characters to the appropriate number of standard spaces, as the presence of tab characters can interfere with the alignment of your code in the document's final format (typically HTML).</p>
</div>

<h3 id="code-length">Code Length and Spacing Guidelines</h3>

Maximum line length for code varies slightly between book formats. For standard Animal books, the maximum line length for code is 81 characters, with 85 characters available in captioned examples. In small Animal books (6x9), standard line length for code is 64 characters, with 68 characters available in captioned examples. Pocket references have even smaller code line length—check with your editor for this information. 

Please make sure your code lines do not exceed these restrictions so that code lines don't run into the right margin when files are converted from Microsoft Word and prepared for typesetting. Indent using spaces, not tabs.

<h3 id="syntax-highlighting">Code Syntax Highlighting</h3>

O'Reilly's ebook toolchain supports syntax highlighting via Pygments. For each block of code that you want to have syntax highlighted, indicate the programming language in brackets, styled as a "Comment" that immediately precedes the block of code. For example, you'd indicate that the following code is in Java like so:

[java]

~~~
int radius = 40;
float x = 110;
float speed = 0.5;
int direction = 1;
~~~

As a result, that block of code will ultimately render in the ebook as shown in the image below.

![syntax highlighting example](http://oreillymedia.github.io/production-resources/word/syntax-highlighting-example.png)

Pygments supports a wide variety of languages; please see the [full list here](http://pygments.org/docs/lexers/). Ebook reading systems that do not have color screens will still display the highlighting, but in more subtle shades of gray.

If you would like to do something in a language that's not supported, please write to us at [toolsreq@oreilly.com](mailto:toolsreq@oreilly.com) and we'll try to work with you on incorporating it.

<h3 id="code-annotation">Code Annotations</h3>

Authors who are interested in annotating code blocks or examples can use callouts to do so. See [Bob Stayton's definition of callouts](http://www.sagehill.net/docbookxsl/AnnotateListing.html#Callouts) along with an example. Callouts are a useful and powerful way of annotating your code because they have the advantage of acting as clickable cross-references in online and mobile formats of your book. In the PDF of your book, the callouts will be clickable in the same way that is demonstrated in Stayton's example. Note that you can click back and forth between the callout and its description in the callout list, which is handy when the code and the callout list straddle pages. 

The following example shows you how to create callouts in your book. Include a note to production at the first occurrence to ensure that the callouts are processed correctly.

Production: Using !!CO1!!, !!CO2!!, etc. to indicate callouts throughout. Match the callouts with the list that follows.

~~~
Code example 12345 example code  !!CO1!!
   more code
      yet more code 12345 !!CO2!!
~~~

1.	Description of first callout.
2.	Description of second callout.

Note that the code block is followed immediately by a list styled with the CalloutList style. Each callout marker is indicated using the convention !!CO<em>N</em>!!: !!CO1!!, !!CO2!!, etc.

<div data-type="note">
  <h6>Note</h6>
  <p>We strongly encourage authors to utilize callouts rather than numbered lines of code, because callouts tend to support a better user experience and are easier to maintain across future printings and editions.</p>
</div>

<h2 id="xrefs">Cross References</h2>

Now that you have a document with a few sections of text, and probably some figures, tables, and examples, you'll likely find the need to refer to these elsewhere in the text.

As mentioned previously, figures, tables, and examples can be cross-referenced by using their numbered label in the text: e.g., "In Figure 7-1, we show that..."

Other chapters can be cross-referenced simply by referring to the chapter by number in the text: "You saw in Chapter 2 how..." If you wish to refer to another section in the document, simply do so by using the section's title in quotation marks: 'In the section "Code Annotations," we described...' Section cross-references should be styled with the SectionXRef style. Chapter, figure, table, and example cross-references do not require any special style. 

<h2 id="misc">Miscellany</h2>

Here we present a few final items that warrant mention.

<h3 id="keyboard-shortcuts">Keyboard Shortcuts</h3>

Most of the SmartStyler commands, as well as a few of the other template utilities, have keyboard shortcuts associated with them. To see if a command has a keyboard shortcut, hover over the command's button on the ribbon in Word to view its tool tip, which will mention any shortcuts. (Note that tool tips are not visible within the drop-down menus, only on the main ribbon.)

<h3 id="tabs-spaces">Tabs and Spaces</h3>

Please don't use tabs to indent text or code. If you absolutely *must* use tabs in your code examples, please change them to spaces before submitting your manuscript for production.

<h3 id="blank-lines">Blank lines</h3>

Except in Code Examples, there should ideally be no blank or empty paragraphs in your document.

<h3 id="help">Getting Help</h3>

If you're having any trouble with the template, or just have a question, and you're unable to find the answer in the documentation, please send an email to [toolsreq@oreilly.com](mailto:toolsreq@oreilly.com). Congratulations again, and good luck!















