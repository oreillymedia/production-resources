---
layout: default
title: O'Reilly Style Guide
---

# O'Reilly Style Guide and Word List

<section data-type="chapter" id="general_specifications">
<h1>General O’Reilly Specifications</h1>


<p><strong>Last updated:</strong> December 12, 2013</p>

<p>This stylesheet is maintained by Publishing Services and is available <a href="http://chimera.labs.oreilly.com/books/1230000000969/index.html">online</a>.</p>






<section data-type="sect1" id="getting_started">
<h1>Getting Started</h1>

<p>Authors, please consult with your editor, editorial assistant, or production editor if you have questions specific to your book. If you’d like to use different conventions, please confer with your editor.</p>

<p>This stylesheet contains information for authors writing in all formats. If you’re an author, please also consult the authoring documentation for the format in which you’re writing (<a href="http://chimera.labs.oreilly.com/books/1230000000065/index.html">Asciidoc</a>, <a href="http://chimera.labs.oreilly.com/books/1234000000058/index.html">DocBook</a>, or <a href="https://prod.oreilly.com/external/tools/templates/word/ORA/docs/">Word</a>).</p>

<p>Our general style reference is The Chicago Manual of
      Style, 15th Edition (though some O’Reilly styles differ).</p>

<p>Our dictionary is Merriam-Webster’s Collegiate
      Dictionary, 11th Edition. Please refer here for any words not on the O’Reilly word list.</p>
</section>













<section data-type="sect1" id="considering_electronic_formats">
<h1>Considering Electronic Formats</h1>

<p>Because we use a single set of source files to produce the print and electronic versions of our books, it’s important to keep all possible formats in mind during the authoring, editorial, and production phases.</p>

<ul>
<li>
<p>Avoid using "above" and "below" when referencing figures, tables, examples, unnumbered code blocks, equations, etc. (e.g., "In the example below…"). Using live cross references (e.g., "see Figure 2-1") is best, but when that’s not possible, use "preceding" or "following," as the physical placement of elements could be different in reflowable formats.</p>
</li>
<li>
<p>URLs should be anchored to text nodes whenever possible, like they would be on a website.</p>
</li>
</ul>
<div data-type="warning" id="id-BeU0teho"><h6>Warning</h6>
<p>When anchoring URLs to text nodes, be as descriptive as possible, as the print version of your book renders hyperlinks like this: "text anchor (<em><a href="http://url.example.com/"><em class="hyperlink">http://url.example.com/</em></a></em>)."</p>

<p>For example, this:</p>
<blockquote>
<p>Download the source code (<a href="http://www.url.thisismadeup.com"><em class="hyperlink">http://www.url.thisismadeup.com</em></a>) and install the package"</p></blockquote>

<p>is more useful than this:</p>
<blockquote>
<p>"Download the source code from this website (<a href="http://www.url.thisismadeup.com"><em class="hyperlink">http://www.url.thisismadeup.com</em></a>) and install the package."</p></blockquote>

<p>Avoid anchoring URLs to generic words or phrases such as "here," "this website," etc.</p>
</div>

<ul>
<li>
<p>Long URLs should be shortened so that they’re easy for print readers to type manually. If a book contains many long URLs, our Tools group may be able to automate link shortening.</p>
</li>
</ul>
</section>







</section>














<section data-type="chapter" id="orm_grammar_punctuation_etc">
<h1>O’Reilly Grammar, Punctuation, etc.</h1>







<section data-type="sect1" id="abbreviationsacronyms">
<h1>Abbreviations/Acronyms</h1>

<ul>
<li>
<p>Acronyms should generally be spelled out the first time they appear in a book, as in: "Computer Development Environment (CDE)." After the acronym has been defined, you should generally use the acronym only (not the whole term, unless it makes more sense contextually to use the whole term). Usually, acronyms are defined only once per book. But if you prefer, you can also define them the first time they appear in each chapter.</p>
</li>
<li>
<p>A.M. and P.M. or a.m. and p.m.—be consistent.</p>
</li>
<li>
<p>K = 1,024; k = 1,000. So a 56 kbps modem is equal to 56,000 bps, while 64K of memory is equal to 65,536.</p>
</li>
<li>
<p>In units of measure, do not use a hyphen. For example, it’s 32 MB hard drive, not 32-MB hard drive. (Though when the unit is spelled out, use a hyphen, e.g., 32-megabyte hard drive.)</p>
</li>
<li>
<p>University degrees (e.g., B.A., B.S., M.A., M.S., Ph.D., etc.) can appear with or without periods—just be consistent.</p>
</li>
<li>
<p>United States and United Kingdom should be spelled out on first mention. After that, just use the acronym with no periods (so, US or UK).</p>
</li>
</ul>
</section>













<section data-type="sect1" id="bibliographical_entries">
<h1>Bibliographical Entries</h1>

<p>In general, when referencing another book within a book’s text paragraphs, include the author name(s) when there is one or two authors. When there are three or more authors, state the first author name, followed by “et al.”</p>

<p>On first reference to another book, include author and publisher name. For example, "You can find more information in <em>The Elements of Typographic Style</em> by Robert Bringhurst (H&amp;M)," or "For more information, consult Robert Bringhurt’s <em>The Elements of Typographic Style</em> (H&amp;M)." On subsequent references, just use the book title.</p>

<p>When referencing an O’Reilly book within the text, note only "O’Reilly" in parentheses, not "O’Reilly Media, Inc." References to other O’Reilly books should be linked to the book’s <a href="http://shop.oreilly.com/category/browse-subjects.do">catalog page</a>.</p>
<div data-type="note" id="id-BeU1hLI7"><h6>Note</h6>
<p>Make sure that the catalog page is anchored to the book’s title, rather than standing on its own.</p>

<p>Like this: "See <a href="http://shop.oreilly.com/product/0636920024033.do"><em>Programming F# 3.0</em></a>"</p>

<p>Not: "See <em>Programming F# 3.0</em> (<a href="http://shop.oreilly.com/product/0636920024033.do"><em class="hyperlink">http://shop.oreilly.com/product/0636920024033.do</em></a>)."</p>
</div>

<p>For full bibliographical entries (which usually appear in bibliographies or reference lists), see <em>The Chicago Manual of Style</em>, 15th Edition.</p>
</section>













<section data-type="sect1" id="cross_references">
<h1>Cross References</h1>

<ul>
<li>
<p>An example of a chapter cross-reference: see Chapter 27.</p>
</li>
<li>
<p>An example of a section cross-reference: see the section “Treatment”. The text “on page x” will be added post-conversion, so the final xref will eventually read “Treatment” on page 37.</p>
</li>
<li>
<p>An example of a section cross-reference in another chapter: see “Acceptable Gifts” on page 58 in Chapter 27.</p>
</li>
<li>
<p>More details on cross-references in Asciidoc are available in our <a href="http://chimera.labs.oreilly.com/books/1230000000065/ch04.html#XREFS:">Getting Started with Atlas Guide</a>.</p>
</li>
<li>
<p>These cross-reference styles are also available in DocBook under various &lt;xref&gt;: formats. Please refer to the <a href="http://chimera.labs.oreilly.com/books/1234000000058/ch02.html#creating_xrefs">DocBook Authoring Guidelines</a>.</p>
</li>
</ul>

<p>For information about styling URLs and hyperlinks, see <a data-type="xref" href="#considering_electronic_formats">Considering Electronic Formats</a>.</p>
</section>













<section data-type="sect1" id="dates_and_numbers">
<h1>Dates and Numbers</h1>

<ul>
<li>
<p>Spell out numbers under 10, unless the same object appears in a sentence with an object 10 or over (five apples; 5 apples and 100 oranges).</p>
</li>
<li>
<p>In most numbers of one thousand or more, commas should be used between groups of three digits, counting from the right (32,904 not 32904). Exceptions: page numbers, addresses, port numbers, etc.</p>
</li>
<li>
<p>Use numerals for versions (version 5 or v5).</p>
</li>
<li>
<p>You may use a numeral if it’s an actual value (e.g., 5% 7″ $6.00).</p>
</li>
<li>
<p>32-bit integer.</p>
</li>
<li>
<p>1980s or ’80s.</p>
</li>
<li>
<p>Phone numbers can appear in the format xxx-xxx-xxxx.</p>
</li>
<li>
<p>Use an en dash (–) with negative numbers or for minus signs, rather than a hyphen.</p>
</li>
<li>
<p>Use x for dimensions, not by (e.g., "8.5 x 11").</p>
</li>
<li>
<p>Ordinal numbers: Spell out first through ninth, use numerals for 10th and above. No superscript.</p>
</li>
</ul>
</section>













<section data-type="sect1" id="figures_tables_and_examples">
<h1>Figures, Tables, and Examples</h1>

<p>Every figure, table, and example should be preceded by a specific in-text reference (for example: see Figure 99-1; Example 1-99 shows; Table 1-1 lists, etc.). Figures, tables, and examples should not be introduced with colons or phrases like “in the following figure,” or “as shown in this table.” Lack of specific in-text references may cause incorrect placement of figures.</p>

<p>If you are writing or copyediting in Word, figure, table, and example numbers should be numbered as follows: 1-2 (note hyphen [-], not en dash [–] between numbers). The first number is the chapter number. This will be soft-coded in production if not during the writing process.</p>

<p>If you are writing or copyediting in Asciidoc, please refer to <a href="http://chimera.labs.oreilly.com/books/1230000000065/ch04.html#XREFS:">Getting Started with Atlas</a> for examples of Asciidoc cross references.</p>

<p>If you are writing or copyediting in DocBook, please reference each figure, table, and example with an &lt;xref&gt;.</p>

<p>Any word groupings within a figure should have an initial cap on the first word only, with the exception of proper nouns. Generally, we don’t use periods at the end of these word groupings.</p>

<ul>
<li>
<p>Figure 1-1. Figure captions are initial-capped on first word only, with the exception of proper nouns. There is no period after figure captions, but if all captions are long and sentence style, periods can be used as long as they are used consistently throughout.</p>
</li>
<li>
<p>Table 1-1. Column heads and table titles are initial-capped on the first word only, with the exception of proper nouns. There is no period after table titles.</p>
</li>
<li>
<p>Example 1-1. Example titles are initial-capped on the first word only, with the exception of proper nouns. There is no period after example titles.</p>
</li>
</ul>

<p>When working in Word, make sure all table cells are tagged with a cell paragraph tag, even if they’re blank. Any bold “headings” that appear below the very first row of a table should be tagged CellSubheading rather than CellHeading.</p>

<p>Also in Word, all figures must be within a FigureHolder paragraph followed directly by a FigureTitle paragraph.</p>
</section>













<section data-type="sect1" id="code">
<h1>Code</h1>








<section data-type="sect2" id="line-length-ZKs1FLck">
<h2>Line Length</h2>

<p>Maximum line length for code varies slightly between book formats. Consult the table below to find the maximum line length for your book’s series within Atlas v2. If writing in Word, please keep code within the margins that appear in the Word template and indicate proper linebreaks and indents for all code. Indent using spaces, not tabs.</p>
<table>

<thead>
<tr>
<th><strong>Series</strong></th>
<th><strong>Body (top-level code)</strong></th>
<th><strong>Examples</strong></th>
<th><strong>Lists</strong></th>
<th><strong>Readeraids</strong></th>
<th><strong>Sidebars</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td><p><strong>Animal</strong></p></td>
<td><p>81</p></td>
<td><p>85</p></td>
<td><p>73</p></td>
<td><p>57</p></td>
<td><p>77</p></td>
</tr>
<tr>
<td><p><strong>Animal 6x9</strong></p></td>
<td><p>64</p></td>
<td><p>68</p></td>
<td><p>56</p></td>
<td><p>40</p></td>
<td><p>60</p></td>
</tr>
<tr>
<td><p><strong>Report 6x9</strong></p></td>
<td><p>64</p></td>
<td><p>68</p></td>
<td><p>56</p></td>
<td><p>40</p></td>
<td><p>60</p></td>
</tr>
<tr>
<td><p><strong>Cookbook</strong></p></td>
<td><p>81</p></td>
<td><p>85</p></td>
<td><p>73</p></td>
<td><p>57</p></td>
<td><p>77</p></td>
</tr>
<tr>
<td><p><strong>Make 1-column</strong></p></td>
<td><p>89</p></td>
<td><p>89</p></td>
<td><p>81</p></td>
<td><p>66</p></td>
<td><p>39</p></td>
</tr>
<tr>
<td><p><strong>Make 2-column</strong></p></td>
<td><p>45</p></td>
<td><p>46</p></td>
<td><p>35</p></td>
<td><p>28</p></td>
<td><p>40</p></td>
</tr>
<tr>
<td><p><strong>Make Getting Started</strong></p></td>
<td><p>63</p></td>
<td><p>67</p></td>
<td><p>60</p></td>
<td><p>51</p></td>
<td><p>60</p></td>
</tr>
<tr>
<td><p><strong>Nutshell</strong></p></td>
<td><p>71</p></td>
<td><p>75</p></td>
<td><p>67</p></td>
<td><p>60</p></td>
<td><p>75</p></td>
</tr>
<tr>
<td><p><strong>Pocket Ref</strong></p></td>
<td><p>51</p></td>
<td><p>55</p></td>
<td><p>50</p></td>
<td><p>42</p></td>
<td><p>51</p></td>
</tr>
<tr>
<td><p><strong>Theory in Practice</strong></p></td>
<td><p>81</p></td>
<td><p>85</p></td>
<td><p>77</p></td>
<td><p>51</p></td>
<td><p>83</p></td>
</tr>
</tbody>
</table>
</section>













<section data-type="sect2" id="syntax-highlighting-zVsXIecp">
<h2>Syntax Highlighting</h2>

<p>We use a tool called Pygments to colorize code. In most books, code will appear in black and white in the print book and in color in all electronic formats, including the web pdf. If you’re an author, please consult the <a href="http://pygments.org/docs/lexers/">list of available lexers</a> and apply them to your code as you write. To apply syntax highlighting in Asciidoc, consult <a href="http://chimera.labs.oreilly.com/books/1230000000065/ch04.html#code_explanation">the Asciidoc Authoring Guidelines</a>. To apply syntax highlighting in DocBook, consult <a href="http://chimera.labs.oreilly.com/books/1234000000058/ch02.html#syntax_highlighting">the DocBook Authoring Guidelines</a>. If you’re writing in Word, for each block of code that you want to have syntax highlighted, indicate the programming language in brackets, styled as a Comment that immediately precedes the block of code. For example, you’d indicate that the following code is in Java like so:</p>

<figure id="id-7XiEIGIpcV">
<img src="images/code_syntax_highlighting_word.png" alt="code syntax highlighting word">
<figcaption><span class="label">Figure 2-1. </span></figcaption>
</figure>
</section>













<section data-type="sect2" id="formatting-code-in-word-yDsgtXca">
<h2>Formatting Code in Word</h2>

<p>When copyediting in Word, please do a global search and replace for tabs in code (search for \^t to find them) before submitting files for conversion; tabs <em>will not</em> convert. A general rule of thumb is one tab can be replaced with four spaces (which is the same number that the clean-up macro in the ORA.dot template uses). However, this number can vary, so the most important thing is that copyeditors replace tabs with the numbers of spaces needed to match the indentation and make sure levels of indentation are preserved.</p>
</section>





</section>













<section data-type="sect1" id="footnotes">
<h1>Footnotes</h1>

<p>Footnotes in running text are numbered and start over at 1 in each chapter. Footnote markers in running text should always appear after punctuation.</p>

<p>This:</p>
<blockquote>
<p>The following query selects the <code>symbol</code> column and all columns from <code>stocks</code> whose names start with the prefix price.<sup>1</sup></p></blockquote>

<p>Not this:</p>
<blockquote>
<p>The following query selects the <code>symbol</code> column and all columns from <code>stocks</code> whose names start with the prefix price<sup>1</sup>.</p></blockquote>

<p>Table footnotes are lettered (a, b, c, etc.) and appear directly after the table. They should be kept to a minimum.</p>

<p>More details about styling footnotes in Asciidoc are in <a href="http://chimera.labs.oreilly.com/books/1230000000065/ch04.html#adding_footnotes:">Getting Started with Atlas</a>.</p>
</section>













<section data-type="sect1" id="headings">
<h1>Headings</h1>

<ul>
<li>
<p>In most of our design templates, A- and B-level headings are cap and lowercase: cap the first letter of each word, with the exception of articles, conjunctions, and program names or technical words that are always lowercase and coordinating conjunctions (e.g., and, but, for, etc.). Prepositions of four letters or less are not initial-capped, unless they function as part of a verb (e.g., “Set Up Your Operating System”). Hyphenated words in subordinating conjunctions (e.g., as, if, that, because, etc.) are always initial-capped (even if they are four letters or less). Hyphenated words in titles or captions should both be capped if the second word is a main word, but only the first should be capped if the second word isn’t too important (it’s a bit of a judgment call). For example: Big-Endian, Built-in. See <em>The Chicago Manual of Style</em>.</p>
</li>
<li>
<p>C-level headings have initial cap on the first word only, with the exception of proper nouns and the first word that follows a colon (unless that word refers to code and should be lowercase).</p>
</li>
<li>
<p>D-level headings (rare) are run-in with the following paragraph and have an initial cap on the first word only, with the exception of proper nouns and the first word that follows a colon (unless that word refers to code and should be lowercase), with a period at the end of the heading.</p>
</li>
<li>
<p>Sidebar titles are cap and lowercase (like A- and B-level headings, mentioned previously).</p>
</li>
<li>
<p>Headings should not contain inline code font.</p>
</li>
</ul>
</section>













<section data-type="sect1" id="lists">
<h1>Lists</h1>

<p>Typically, we use three types of lists: numbered lists, for ordered steps or chronological items; variable lists, for terms and explanations/definitions; and bulleted lists, for series of items. List items are sentence-capped. Following are examples of each type of list.</p>








<section data-type="sect2" id="numbered_list">
<h2>Numbered list</h2>

<p>The following list of step-by-step instructions is an example of a numbered list:</p>
<ol>
<li>
<p>Save Example 2-1 as the file <em>hello.cs</em>.</p>
</li>
<li>
<p>Open a command window.</p>
</li>
<li>
<p>From the command line, enter <code>csc /debug hello.cs</code>.</p>
</li>
<li>
<p>To run the program, enter <code>Hello</code>.</p>
</li>

</ol>
</section>













<section data-type="sect2" id="variable_list">
<h2>Variable list</h2>

<p>The following list of defined terms is an example of a variable list:</p>
<dl>
<dt><em>Setup project</em></dt>
<dd>
<p>This creates a setup file that automatically installs your files and resources.</p>
</dd>
<dt><em>Web setup project</em></dt>
<dd>
<p>This helps deploy a web-based project.</p>
</dd>
</dl>
</section>













<section data-type="sect2" id="bulleted_list">
<h2>Bulleted list</h2>

<p>The following series of items is an example of a bulleted list:</p>

<ul>
<li>
<p>Labels</p>
</li>
<li>
<p>Buttons</p>
</li>
<li>
<p>A text box</p>
</li>
</ul>

<p>“Bulleted” lists nested inside of bulleted lists should have em dashes as bullets.</p>

<p>Frequently, bulleted lists should be converted to variable lists. Any bulleted list whose entries consist of a short term and its definition should be converted. For example, the following bulleted list entries:</p>

<ul>
<li>
<p>Spellchecking: process of correcting spelling</p>
</li>
<li>
<p>Pagebreaking—process of breaking pages</p>
</li>
</ul>

<p>should be variable list entries:</p>
<dl>
<dt><em>Spellchecking</em></dt>
<dd>
<p>Process of correcting spelling</p>
</dd>
<dt><em>Pagebreaking</em></dt>
<dd>
<p>Process of breaking pages</p>
</dd>
</dl>
</section>





</section>













<section data-type="sect1" id="miscellaneous">
<h1>Miscellaneous</h1>

<ul>
<li>
<p>Don’t use “they” for third-person singular; alternate between “he” and “she.”</p>
</li>
<li>
<p>Do not use a hyphen between an adverb and the word it modifies. So, “incredibly wide table” rather than “incredibly-wide table.”</p>
</li>
<li>
<p>Unless part of a proper noun, close up words with the prefixes “multi,” “pseudo,” “non,” “sub,” and "co" (e.g., “multiusers,” “pseudoattribute,” “nonprogammer,” “subprocess,” "coauthor").</p>
</li>
<li>
<p>Avoid using the possessive case for singular nouns ending in “s,” if possible. So, it’s “the Windows Start menu,” not “Windows’s Start menu.”</p>
</li>
<li>
<p>Avoid wholesale changes to the author’s voice—for example, changing the first-person plural (the royal “we”) to the first-person singular or the second person. However, do try to maintain a consistency within sentences or paragraphs, where appropriate.</p>
</li>
<li>
<p>Companies are always singular. So, for example, “Apple emphasizes the value of aesthetics in its product line. Consequently, it dominates the digital-music market” is correct. “Apple emphasize the value of aesthetics in their product line. They dominate the digital-music market” is <em>not</em>. (Also applies to generic terms “organization,” “team,” “group,” etc.)</p>
</li>
<li>
<p>When referring to software elements or labels, always capitalize words that are capitalized on screen. Put quotes around any multiword element names that are lowercase on screen and would thus be hard to distinguish from the rest of the text (e.g., Click “Don’t select object until rendered” only if necessary.)</p>
</li>
<li>
<p>For menu items that end with an ellipsis (e.g., "New Folder…"), do not include ellipsis in running text.</p>
</li>
<li>
<p>Use “between” for two items, “among” for three or more. Use “each other” for two, “one another” for three or more.</p>
</li>
<li>
<p>Common foreign terms (such as “en masse”) are roman.</p>
</li>
<li>
<p>Commas and periods go inside quotation marks.</p>
</li>
<li>
<p>Em-dashes: always closed (no space around them).</p>
</li>
<li>
<p>Ellipses: always closed (no space around them).</p>
</li>
<li>
<p>Hyphens: close up words used as nouns (“coverup”); hyphenate words used as adjectives (“the cover-up measures”); verbs are two words (“cover up the flaw with…”).</p>
</li>
<li>
<p>Introduce unnumbered code blocks with colons.</p>
</li>
</ul>
</section>













<section data-type="sect1" id="punctuation">
<h1>Punctuation</h1>

<p>For anything not covered in this list, please consult the Chicago Manual of Style, 15th Edition.</p>

<ul>
<li>
<p>Serial comma (this, that, and the other).</p>
</li>
<li>
<p>Curly quotes and apostrophes (“ ” not " ") in regular text.</p>
</li>
<li>
<p>Straight quotes (" " not “ ”) in constant-width text and all code. Some Unix commands use backticks (<code>`</code>), which must be preserved.</p>
</li>
<li>
<p>No period after list items unless one item forms a complete sentence (then use periods for all items within that list, even fragments).</p>
</li>
<li>
<p>Lowercase the first letter after a colon: this is how we do it. (Exception: headings.)</p>
</li>
<li>
<p>Parentheses are always roman, even when the contents are italic. For parentheses within parentheses, use square brackets (here’s the first parenthetical [and here’s the second]).</p>
</li>
</ul>
</section>







</section>














<section data-type="chapter" id="typography_and_font_conventions">
<h1>Typography and Font Conventions</h1>


<p>The following shows the basic font conventions used in O’Reilly books. Follow these links for detailed instructions for applying these styles in <a href="http://chimera.labs.oreilly.com/books/1230000000065/index.html:">Asciidoc</a>, <a href="http://chimera.labs.oreilly.com/books/1234000000058/index.html:">DocBook</a>, and <a href="https://prod.oreilly.com/external/tools/templates/word/ORA/docs/:">Word</a>.</p>
<table>

<thead>
<tr>
<th>Type of element</th>
<th>Final result</th>
</tr>
</thead>
<tbody>
<tr>
<td><p>Filenames, file extensions (such as .<em>jpeg</em>), directory paths, commands in Unix, Oracle, SQL, and Linux books</p></td>
<td><p><em>Body font italic</em></p></td>
</tr>
<tr>
<td><p>URLs, URIs, email addresses</p></td>
<td><p><em>Body font italic</em></p></td>
</tr>
<tr>
<td><p>Emphasized words (shouting!)</p></td>
<td><p><em>Body font italic</em></p></td>
</tr>
<tr>
<td><p>First instance of a technical term</p></td>
<td><p><em>Body font italic</em></p></td>
</tr>
<tr>
<td><p>Code blocks</p></td>
<td><p><code>Constant width</code></p></td>
</tr>
<tr>
<td><p>Registry keys</p></td>
<td><p><code>Constant width</code></p></td>
</tr>
<tr>
<td><p>Language and script elements: class names, types, namespaces, attributes, methods, variables, keywords, functions, modules, commands, properties, parameters, values, objects, events, XML and HTML tags, and similar elements. Some examples include: <code>System.Web.UI</code>, a <code>while</code> loop, the <code>Socket</code> class, and the <code>Obsolete</code> attribute. <strong>Exception:</strong> commands in Unix, Oracle, SQL, and Linux book, which are regular italics.</p></td>
<td><p><code>Constant width</code></p></td>
</tr>
<tr>
<td><p>Replaceable items (placeholder items in syntax); “username” in the following example is a placeholder:
 <code>login:</code> <em><code>username</code></em></p></td>
<td><p><em><code>Constant width italic</code></em></p></td>
</tr>
<tr>
<td><p>Commands or text to be typed by the user</p></td>
<td><p><strong><code>Constant width bold</code></strong></p></td>
</tr>
<tr>
<td><p>Line annotations</p></td>
<td><p><em>Body font italic</em> (but smaller)</p></td>
</tr>
<tr>
<td><p>Placeholders in paths, directories, GUI items, URLs, or other text that would be italic anyway</p></td>
<td><p><em><a href="http://www.&lt;yourname&gt;.com"><em class="hyperlink">http://www.&lt;yourname&gt;.com</em></a></em></p></td>
</tr>
<tr>
<td><p>Keyboard accelerators (Ctrl, Shift, etc.), menu titles, menu options, menu buttons</p></td>
<td><p>Body text</p></td>
</tr>
</tbody>
</table>

<p>These font conventions may vary slightly for each project; please consult your editor, the production editor, or the freelance coordinator if you have any questions. <em>Please note:</em> Word authors should refer to the <a href="https://prod.oreilly.com/external/tools/templates/word/ORA/docs/">Word author Quick Start Guide</a> (username: guest; leave the password blank); DocBook authors should refer to our <a href="https://prod.oreilly.com/external/tools/docbook/docs/authoring/">DocBook Authoring Guidelines</a> (username: guest; leave the password blank).</p>

<p>It’s <em>very</em> important to follow tagging conventions for terms. The method for applying conventions will vary depending on the format: Word/OpenOffice, DocBook XML, or InDesign. Please consult with your editor or  <em>toolsreq@oreilly.com</em> for instructions specific to each environment.</p>

<p>For Word copyediting, please do the following before submitting files for conversion: replace any tabs in code with the appropriate number of spaces (see earlier section, <a data-type="xref" href="#code">Code</a>); convert any remaining Word comments to tagged Comment paragraphs highlighted in blue; search for any manual linebreaks (^l) and delete or replace with paragraph breaks as appropriate; and accept all changes and make sure filenames adhere to house style.</p>
<div data-type="note" id="note-1"><h6>Note</h6>
<p>If you’re an author, and you want to use a font convention that is slightly different for one of the following items, check with your editor first—some things can change; some can’t.</p>

<p>For instance, URLs will not be anything but <em>italic</em>, but you might come up with a different font convention for function names or menu items. If you do use something that differs from the following list, please write it down on your printout of this stylesheet, which should be submitted with your manuscript.</p>

<p>Or, if you have a “new” element, please consult with your editor about which font to use, then write it on your printout and submit it with your manuscript.</p>
</div>
</section>














<section data-type="chapter" id="oreilly_word_list">
<h1>O’Reilly Word List</h1>


<p><em>Alphabetical Word List: Default Spellings</em></p>
      <sect2 id="a_entries">
        <title>A</title>

        <simplelist columns="2">
          <member>acknowledgments</member>

          <member>ActionScript</member>

          <member>ActiveX control</member>

          <member>Addison-Wesley</member>

          <member>ad hoc</member>

          <member>ADO.NET</member>

          <member>Agile</member>
          <member>  (cap when referring to Agile software development or when used on its own as a noun)</member>

          <member>a.k.a. or aka (be consistent)</member>

          <member>a.m. or A.M.</member>

          <member>Alt key</member>

          <member>Alt-N</member>

          <member>anonymous FTP</member>

          <member>anti-pattern</member>

          <member>appendixes</member>

          <member>applet (or Java applet)</member>

          <member>AppleScript</member>

          <member>AppleScript Studio (ASS)</member>

          <member>ARPAnet</member>

          <member>ASCII</member>

          <member>ASP.NET</member>

          <member>at sign</member>

          <member>autogenerate</member>

          <member>awk</member>
        </simplelist>
      </sect2>

      <sect2 id="b_entries" role="notoc">
        <title>B</title>

        <simplelist columns="2">
          <member>backend</member>

          <member>background processes</member>

          <member>backquote</member>

          <member>backslash</member>

          <member>Backspace key</member>

          <member>backtick</member>

          <member>backup (n)</member>

          <member>back up (v)</member>

          <member>backward</member>

          <member>backward compatible</member>

          <member>bandwidth</member>

          <member>BeOS</member>

          <member>Berkeley Software Distribution (BSD)</member>

          <member>Berkeley Unix</member>

          <member>  (older books may have UNIX)</member>

          <member>BHOs</member>

          <member>Big Design Up Front (BDUF)</member>

          <member>bioinformatics</member>

          <member>bitmap</member>

          <member>bit mask</member>

          <member>Bitnet</member>

          <member>bit plane</member>

          <member>bitwise operators</member>

          <member>BlackBerry</member>

          <member>Boolean (unless referring</member>

          <member>to a datatype in code,</member>

          <member>in which case s/b lowercase)</member>

          <member>Bourne-again shell (bash)</member>

          <member>Bourne shell</member>

          <member>braces or curly braces</member>

          <member>brackets or square brackets</member>

          <member>browsable</member>

          <member>_build-&gt;measure-&gt;learn_ cycle</member>

          <member>built-in (a, n)</member>

          <member>button bar</member>
        </simplelist>
      </sect2>

      <sect2 id="c_entries" role="notoc">
        <title>C</title>

        <simplelist columns="2">
          <member>call-to-cation</member>

          <member>Caps Lock key</member>

          <member>caret or circumflex</member>

          <member>CAT-5</member>

          <member>CD-ROM</member>

          <member>C language (n)</member>

          <member>C-language (a)</member>

          <member>checkbox</member>

          <member>checkmark</member>

          <member>check-in (n)</member>

          <member>classpath</member>

          <member>click-through (a)</member>

          <member>client/server</member>

          <member>client side (n)</member>

          <member>client-side (a)</member>

          <member>co-class</member>

          <member>coauthor</member>

          <member>code set</member>

          <member>colorcell</member>

          <member>colormap</member>

          <member>Command key (Macintosh)</member>

          <member>command line (n)</member>

          <member>command-line (a)</member>

          <member>Common Object Request</member>

          <member>Broker Architecture (CORBA)</member>

          <member>compact disc</member>

          <member>compile time (n)</member>

          <member>compile-time (a)</member>

          <member>CompuServe</member>

          <member>Control key (Mac)</member>

          <member>copyleft</member>

          <member>copyright</member>

          <member>coworker</member>

          <member>CPU</member>

          <member>criterion (s), criteria (p)</member>

          <member>cross-reference</member>

          <member>C shell</member>

          <member>&lt;CR&gt;&lt;LF&gt;</member>

          <member>Ctrl key (Windows)</member>

          <member>Ctrl-Alt-Delete</member>

          <member>Ctrl-N</member>

          <member>curly braces or braces</member>
        </simplelist>
      </sect2>

      <sect2 id="d_entries" role="notoc">
        <title>D</title>

        <simplelist columns="2">
          <member>database</member>

          <member>data block</member>

          <member>Data Encryption Standard (DES)</member>

          <member>datafile</member>

          <member>datatype or data type (be consistent)</member>

          <member>data is</member>

          <member>dataset or data set (be consisten)</member>

          <member>DB-9</member>

          <member>Debian GNU/Linux</member>

          <member>decision making (n)</member>

          <member>decision-making (a)</member>

          <member>DevOps</member>

          <member>dial-up (a)</member>

          <member>dial up (v)</member>

          <member>disk</member>

          <member>disk-imaging software</member>

          <member>Delete key</member>

          <member>design time (n)</member>

          <member>design-time (a)</member>

          <member>DNS</member>

          <member>DocBook</member>

          <member>Document Object Model (DOM)</member>

          <member>Domain Name System</member>

          <member>dot</member>

          <member>dot-com</member>

          <member>double-click</member>

          <member>double-precision (a)</member>

          <member>double quotes</member>

          <member>down arrow</member>

          <member>downlevel (a)</member>

          <member>download</member>

          <member>drag-and-drop (n)</member>

          <member>drag and drop (v)</member>

          <member>drop-down (a)</member>
        </simplelist>
      </sect2>

      <sect2 id="e_entries" role="notoc">
        <title>E</title>

        <simplelist columns="2">
          <member>ebook</member>

          <member>ebusiness</member>

          <member>ecommerce </member>

          <member>eBay</member>

          <member>Emacs</member>

          <member>email</member>

          <member>empty-element tag</member>

          <member>end-of-file (EOF)</member>

          <member>end-tag</member>

          <member>end user (n.), end-user (adj.)</member>

          <member>Engines of Groth</member>

          <member>Enter key</member>

          <member>equals sign</member>

          <member>ereader</member>

          <member>Escape key (or Esc key)</member>

          <member>et al.</member>

          <member>Ethernet</member>

          <member>exclamation mark</member>

          <member>Exim</member>
        </simplelist>
      </sect2>

      <sect2 id="f_entries" role="notoc">
        <title>F</title>

        <simplelist columns="2">
          <member>failback</member>

          <member>failover</member>

          <member>fax</member>

          <member>file manager</member>

          <member>filename</member>

          <member>file server</member>

          <member>filesystem</member>

          <member>file type</member>

          <member>FireWire</member>

          <member>foreground</member>

          <member>FORTRAN</member>

          <member>Fortran 90</member>

          <member>forward (adv)</member>

          <member>frame type</member>

          <member>FreeBSD</member>

          <member>Free Documentation License (FDL)</member>

          <member>Free Software Foundation (FSF)</member>

          <member>frontend</member>

          <member><emphasis>ftp</emphasis> (Unix command)</member>

          <member>FTP (protocol)</member>

          <member>FTP site</member>

          <member>full stack (Full Stack in headings), no hyphen, even if adjective</member>
        </simplelist>
      </sect2>

      <sect2 id="g_entries" role="notoc">
        <title>G</title>

        <simplelist columns="2">
          <member>gateway</member>

          <member>Gb (gigabit)</member>

          <member>GB (gigabyte)</member>

          <member>GBps (gigabytes per second)</member>

          <member>GHz</member>

          <member>gid</member>

          <member>GIMP</member>

          <member>GNOME</member>

          <member>GNU Emacs</member>

          <member>GNU Public License (GPL)</member>

          <member>GNUstep</member>

          <member>Google PageRank</member>

          <member>grayscale</member>

          <member>greater-than sign or &gt;</member>

          <member>greenlight (v)</member>

          <member>GUI, GUIs</member>
        </simplelist>
      </sect2>

      <sect2 id="h_entries" role="notoc">
        <title>H</title>

        <simplelist columns="2">
          <member>handcode</member>

          <member>handoff (n)</member>

          <member>hardcoded</member>

          <member>hardcore</member>

          <member>hardcode (v)</member>

          <member>hardcopy</member>

          <member>hard link</member>

          <member>hash sign or sharp sign</member>

          <member>high-level (adj)</member>

          <member>home page</member>

          <member>hostname</member>

          <member>hotspot</member>

          <member>HTML</member>

          <member>HTTP</member>

          <member>hypertext</member>
        </simplelist>
      </sect2>

      <sect2 id="i_entries" role="notoc">
        <title>I</title>

        <simplelist columns="2">
          <member>IDs</member>

          <member>IDE</member>

          <member>inline</member>

          <member>inode</member>

          <member>interclient</member>

          <member>Internet</member>

          <member>internetwork</member>

          <member>intranet</member>

          <member>Intrinsics</member>

          <member>I/O</member>

          <member>IP (Internet Protocol)</member>

          <member>IPsec</member>

          <member>ISO</member>

          <member>ISP</member>
        </simplelist>
      </sect2>

      <sect2 id="j_entries" role="notoc">
        <title>J</title>

        <simplelist columns="2">
          <member>Jabber</member>

          <member>Jabber client</member>

          <member>Jabber server</member>

          <member>Jabber applet</member>

          <member>JAR archive</member>

          <member>JAR file</member>

          <member>JavaScript</member>

          <member>JPEG</member>
        </simplelist>
      </sect2>

      <sect2 id="k_entries" role="notoc">
        <title>K</title>

        <simplelist columns="2">
          <member>K Desktop Environment (KDE)</member>

          <member>Kb (kilobit)</member>

          <member>KB (kilobyte)</member>

          <member>  (denotes file size or disk space)</member>

          <member>Kbps (kilobits per second)</member>

          <member>Kerberos</member>

          <member>keepalive (n or a)</member>

          <member>keyclick</member>

          <member>keycode</member>

          <member>keymaps</member>

          <member>keypad</member>

          <member>keystroke</member>

          <member>keysym</member>

          <member>keywords</member>

          <member>key performance indicators (KPIs)</member>

          <member>kHz (kilohertz)</member>

          <member>Korn shell</member>
        </simplelist>
      </sect2>

      <sect2 id="l_entries" role="notoc">
        <title>L</title>

        <simplelist columns="2">
          <member>Lean (capitalize noun or adjective when referring to Lean business methodology)</member>

          <member>local area network or LAN</member>

          <member>left angle bracket or &lt;</member>

          <member>lefthand (a)</member>

          <member>leftmost</member>

          <member>less-than sign or &lt;</member>

          <member>leveled (not levelled)</member>

          <member>line-feed (a)</member>

          <member>line feed (n)</member>

          <member>Linux</member>

          <member>LinuxPPC</member>

          <member>listbox</member>

          <member>logfile</member>

          <member>login, logout, or logon (n or a)</member>

          <member>log in, log out, or log on (v)</member>

          <member>lower- and uppercase</member>

          <member>lowercase</member>

          <member>lower-level (a)</member>

          <member>lower-right (a)</member>

          <member>Linux Professional Institute (LPI)</member>
        </simplelist>
      </sect2>

      <sect2 id="m_entries" role="notoc">
        <title>M</title>

        <simplelist columns="2">
          <member>Macintosh</member>

          <member>Mac OS</member>

          <member>Mac OS 9 (<emphasis>note the use of
          spaces</emphasis>)</member>

          <member>Mac OS X (<emphasis>note the use of
          spaces</emphasis>)</member>

          <member>machine learning (noun), machine-learning (adj.)</member>

          <member>mail-handling (adjective)</member>

          <member>manpage</member>

          <member>markup</member>

          <member>Mb (megabit)</member>

          <member>MB (megabyte)</member>

          <member>MBps (megabytes per second)</member>

          <member>McGraw-Hill</member>

          <member>menu bar</member>

          <member>metacharacter</member>

          <member>Meta key</member>

          <member>Meta-N</member>

          <member>MHz (megahertz)</member>

          <member>mice or mouses (be consistent)</member>

          <member>Microsoft Windows</member>

          <member>Microsoft Windows Me</member>

          <member>Microsoft Windows NT</member>

          <member>Microsoft Windows XP</member>

          <member>Microsoft Windows 2000</member>

          <member>MIDlet</member>

          <member>MKS Toolkit</member>

          <member>MS-DOS</member>

          <member>multiline<footnote id="CHP-1-FNOTE-2">
              <para>Unless before a proper noun, always close up the following
              prefixes: “non,” “sub,” “multi,” and “pseudo.”</para>
            </footnote></member>

          <member>Multi-Touch (when referring to Apple's trademark)</member>

          <member>My Services</member>

          <member>MySpace</member>
        </simplelist>
      </sect2>

      <sect2 id="n_entries" role="notoc">
        <title>N</title>

        <simplelist columns="2">
          <member>nameserver</member>

          <member>name service</member>

          <member>namespace</member>

          <member>the Net</member>

          <member>.NET</member>

          <member>NetBIOS</member>

          <member>NetBSD</member>

          <member>NetInfo</member>

          <member>newline</member>

          <member>newsgroups</member>

          <member>NeXTSTEP</member>

          <member>NOOP</member>

          <member>nonlocal<footnoteref linkend="CHP-1-FNOTE-2"></footnoteref></member>

          <member>Novell NetWare</member>

          <member>the <emphasis>New York Times</emphasis></member>
        </simplelist>
      </sect2>

      <sect2 id="o_entries" role="notoc">
        <title>O</title>

        <simplelist columns="2">
          <member>Objective-C</member>

          <member>object linking and embedding (OLE)</member>

          <member>object-oriented programming (OOP)</member>

          <member>object request broker (ORB)</member>

          <member>OK</member>

          <member>offline</member>

          <member>offload</member>

          <member>onboard</member>

          <member>ongoing</member>

          <member>online</member>

          <member>open source (n or a)</member>

          <member>open source software (OSS)</member>

          <member>OpenBSD</member>

          <member>OpenMotif</member>

          <member>OpenStep</member>

          <member>OpenWindows</member>

          <member>Option key (Macintosh)</member>

          <member>Oracle7</member>

          <member>Oracle8</member>

          <member>Oracle 8.0</member>

          <member>Oracle 8<emphasis>i</emphasis> (italic “i”)</member>

          <member>Oracle 9<emphasis>i</emphasis> (italic “i”)</member>

          <member>Oracle Parallel Query Option</member>

          <member>O’Reilly Media, Inc.</member>

          <member>OS/2</member>

          <member>OSA</member>

          <member>OSF/Motif</member>

          <member>OS X</member>
        </simplelist>
      </sect2>

      <sect2 id="p_entries" role="notoc">
        <title>P</title>

        <simplelist columns="2">
          <member>packet switch networks</member>

          <member>Paint Shop Pro</member>

          <member>pagefile</member>

          <member>page rank (but Google PageRank™)</member>

          <member>parentheses (p)</member>

          <member>parenthesis (s)</member>

          <member>Pascal</member>

          <member>password</member>

          <member>pathname</member>

          <member>pattern-matching (a)</member>

          <member>peer-to-peer (or P2P)</member>

          <member>performant (Oracle)</member>

          <member>period</member>

          <member>Perl</member>

          <member>Perl DBI</member>

          <member>plain text (n)</member>

          <member>plain-text (a)</member>

          <member>Plug and Play (PnP)</member>

          <member>plug in (v)</member>

          <member>plug-in (a, n)</member>

          <member>p.m. or P.M.</member>

          <member>Point-to-Point Protocol (PPP)</member>

          <member>pop up (v, n)</member>

          <member>pop-up (a)</member>

          <member>POP-3</member>

          <member>Portable Document Format (PDF)</member>

          <member>Portable Network Graphics (PNG)</member>

          <member>Portable Operating</member>

          <member>  System Interface (POSIX)</member>

          <member>POSIX-compliant</member>

          <member>Post Office Protocol (POP)</member>

          <member>postprocess</member>

          <member>PostScript</member>

          <member>Prentice Hall</member>

          <member>process ID</member>

          <member>progress bar</member>

          <member>pseudoattribute<footnoteref linkend="CHP-1-FNOTE-2"></footnoteref></member>

          <member>pseudo-tty</member>

          <member>public key (n)</member>

          <member>public-key (a)</member>

          <member>pull-down (a)</member>
        </simplelist>
      </sect2>

      <sect2 id="q_entries" role="notoc">
        <title>Q</title>

        <simplelist columns="2">
          <member>qmail</member>

          <member>Qt</member>

          <member>QuarkXPress</member>

          <member>Quartz</member>

          <member>Quartz Extreme</member>

          <member>QuickTime</member>

          <member>quotation marks</member>

          <member>  (spell out first time it;</member>

          <member>  can be “quotes” thereafter)</member>
        </simplelist>
      </sect2>

      <sect2 id="r_entries" role="notoc">
        <title>R</title>

        <simplelist columns="2">
          <member>random-access (a)</member>

          <member>RCS</member>

          <member>read-only (a)</member>

          <member>read/write</member>

          <member>real time (n)</member>

          <member>real-time (a)</member>

          <member>Red Hat Linux</member>

          <member>Red Hat Package Manager (RPM)</member>

          <member>redirection</member>

          <member>reference page or manpage</member>

          <member>remote-access server</member>

          <member>rename</member>

          <member>Rendezvous</member>

          <member>  (<emphasis>Mac OS X Zeroconf
          networking</emphasis>)</member>

          <member>Return (key)</member>

          <member>RFC 822</member>

          <member>rich text (n)</member>

          <member>rich-text (a)</member>

          <member>right angle bracket or</member>

          <member>greater-than sign (&gt;)</member>

          <member>right-click</member>

          <member>righthand (a)</member>

          <member>rmail</member>

          <member>roll back (v)</member>

          <member>rollback (n)</member>

          <member>rootkit</member>

          <member>Rubout key</member>

          <member>rulebase</member>

          <member>ruleset</member>

          <member>runtime (n, a)</member>
        </simplelist>
      </sect2>

      <sect2 id="s_entries" role="notoc">
        <title>S</title>

        <simplelist columns="2">
          <member>Samba</member>

          <member>saveset</member>

          <member>screen dump</member>

          <member>screenful</member>

          <member>screensaver</member>

          <member>screenshot</member>

          <member>scroll bar</member>

          <member>securelevel (in Linux)</member>

          <member>Secure Shell (SSH)</member>

          <member>Secure Sockets Layer (SSL)</member>

          <member>sed scripts</member>

          <member>semicolon</member>

          <member>server-dependent</member>

          <member>server side (n)</member>

          <member>server-side (a)</member>

          <member>servlet</member>

          <member>set up (v)</member>

          <member>setup (n)</member>

          <member>SGML</member>

          <member>sharp sign or hash sign</member>

          <member>shell (lowercase even in</member>

          <member>  shell name: Bourne shell)</member>

          <member>shell scripts</member>

          <member>Shift key</member>

          <member>shortcut</member>

          <member>Simple API for XML (SAX)</member>

          <member>single-precision (a)</member>

          <member>single quote</member>

          <member>site map</member>

          <member>slideshow</member>

          <member>Smalltalk</member>

          <member>SMP (a, n)</member>

          <member>SOAP</member>

          <member>Social Security number (SSN)</member>

          <member>source code</member>

          <member>space bar</member>

          <member>spam (not SPAM)</member>

          <member>spellcheck</member>

          <member>spellchecker</member>

          <member>split screen</member>

          <member>square brackets or brackets</member>

          <member>standalone</member>

          <member>standard input (stdin)</member>

          <member>standard output (stdout)</member>

          <member>start tag</member>

          <member>startup file</member>

          <member>status bar</member>

          <member>stylesheet</member>

          <member>subprocess<footnote id="CHP-1-FNOTE-5">
              <para>Unless before a proper noun, always close up the following
              prefixes: “non,” “sub,” “multi,” and “pseudo.”</para>
            </footnote></member>

          <member>SUSE Linux</member>

          <member>swapfile</member>

          <member>swapspace</member>

          <member>sync</member>

          <member>system administrator</member>

          <member>system-wide</member>
        </simplelist>
      </sect2>

      <sect2 id="t_entries" role="notoc">
        <title>T</title>

        <simplelist columns="2">
          <member>10-baseT</member>

          <member>T1</member>

          <member>t-shirt</member>

          <member>Tab key</member>

          <member>TAR file</member>

          <member>TCP/IP</member>

          <member>Telnet (the protocol)</member>

          <member>telnet (v)</member>

          <member>terabyte</member>

          <member>T<subscript>E</subscript>X</member>

          <member>texinfo</member>

          <member>text box</member>

          <member>text-input mode</member>

          <member>thread pooling (n)</member>

          <member>time-sharing processes</member>

          <member>timestamp</member>

          <member>time zone</member>

          <member>title bar</member>

          <member>Token Ring</member>

          <member>toolbar</member>

          <member>toolkit</member>

          <member>tool tip</member>

          <member>top-level (a)</member>

          <member>toward</member>

          <member>trade-off</member>

          <member>troubleshoot</member>
        </simplelist>
      </sect2>

      <sect2 id="u_entries" role="notoc">
        <title>U</title>

        <simplelist columns="2">
          <member>UK (for United Kingdom)</member>

          <member>Ultrix</member>

          <member>Universal Serial Bus (USB)</member>

          <member>Unix (UNIX in many</member>

          <member>  books, esp. older ones)</member>

          <member>up arrow</member>

          <member>upper- and lowercase</member>

          <member>uppercase</member>

          <member>upper-left corner</member>

          <member>UPSs</member>

          <member>up-to-date</member>

          <member>URLs</member>

          <member>US (for United States)</member>

          <member>Usenet</member>

          <member>user ID (n)</member>

          <member>user-ID (a)</member>

          <member>username</member>
        </simplelist>
      </sect2>

      <sect2 id="v_entries" role="notoc">
        <title>V</title>

        <simplelist columns="2">
          <member>v2 or version 2</member>

          <member>VAX/VMS</member>

          <member>VB.NET</member>

          <member>versus (avoid vs.)</member>

          <member>vice versa</member>

          <member>VoiceXML</member>

          <member>Visual Basic .NET</member>

          <member>Visual Basic 6 or VB 6</member>

          <member>Visual C++ .NET</member>

          <member>Visual Studio .NET</member>

          <member>VS.NET</member>

          <member>Volume One</member>
        </simplelist>
      </sect2>

      <sect2 id="w_entries" role="notoc">
        <title>W</title>

        <simplelist columns="2">
          <member>the <emphasis>Wall Street Journal</emphasis></member>

          <member>the Web (n)</member>

          <member>web (a)</member>

          <member>web client</member>

          <member>webmaster</member>

          <member>web page</member>

          <member>web server</member>

          <member>web services (unless</member>

          <member>  preceded by a proper noun,</member>

          <member>  as in Microsoft Web Services)</member>

          <member>website</member>

          <member>white pages</member>

          <member>whitespace</member>

          <member>wide area network or WAN</member>

          <member>WiFi</member>

          <member>wiki</member>

          <member>wildcard</member>

          <member>Windows 95</member>

          <member>Windows 98</member>

          <member>Windows 2000</member>

          <member>Windows NT</member>

          <member>Windows Vista</member>

          <member>Windows XP</member>

          <member>Wizard (proper noun)</member>

          <member>wizard (a, n)</member>

          <member>workaround</member>

          <member>workbench</member>

          <member>workgroup</member>

          <member>workstation</member>

          <member>World Wide Web (WWW)</member>

          <member>wraparound</member>

          <member>writable</member>

          <member>write-only (a)</member>

          <member>WYSIWYG</member>
        </simplelist>
      </sect2>

      <sect2 id="x_y_z_entries" role="notoc">
        <title>X Y Z</title>

        <simplelist columns="2">
          <member>(x,y) (no space)</member>

          <member>x-axis</member>

          <member>Xbox</member>

          <member>X client</member>

          <member><emphasis>x</emphasis> coordinate</member>

          <member>X protocol</member>

          <member>X server</member>

          <member>X Toolkit</member>

          <member>XView</member>

          <member>X Window series</member>

          <member>X Window System</member>

          <member>x86</member>

          <member>xFree86</member>

          <member>XHTML</member>

          <member>XLink</member>

          <member>XML</member>

          <member>XML Query Language (XQuery)</member>

          <member>XML-RPC</member>

          <member>XPath</member>

          <member>XPointer</member>

          <member>XSL</member>

          <member>XSLT</member>

          <member>Yahoo!</member>

          <member>y-axis</member>

          <member><emphasis>y</emphasis> coordinate</member>

          <member>Zeroconf</member>

          <member>  (short for “Zero Configuration”)</member>

          <member>zeros</member>

          <member>zip code</member>

          <member>zip (v)</member>

          <member>ZIP file</member>
        </simplelist>
      </sect2>
</section>









  </body>
</html>
