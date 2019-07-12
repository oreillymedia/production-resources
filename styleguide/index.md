---
layout: default
title: O'Reilly Style Guide
---

# O'Reilly Style Guide and Word List

* <a href="#getting_started">Getting Started</a>
* <a href="#considering_electronic_formats">Considering Electronic Formats</a>
* <a href="#orm_grammar_punctuation_etc">O’Reilly Grammar, Punctuation, etc.
  * <a href="#abbreviationsacronyms">Abbreviations/Acronyms</a>
  * <a href="#bibliographical_entries">Bibliographical Entries</a>
  * <a href="#cross_references">Cross References</a>
  * <a href="#dates_and_numbers">Dates and Numbers</a>
  * <a href="#figures_tables_and_examples">Figures, Tables, and Examples</a>
  * <a href="#code">Code</a>
    * <a href="#line-length-ZKs1FLck">Line Length</a>
    * <a href="#syntax-highlighting-zVsXIecp">Syntax Highlighting</a>
    * <a href="#formatting-code-in-word-yDsgtXca">Formatting Code in Word</a>
  * <a href="#footnotes">Footnotes</a>
  * <a href="#headings">Headings</a>
  * <a href="#links">Links</a>
  * <a href="#lists">Lists</a>
    * <a href="#numbered_list">Numbered list</a>
    * <a href="#variable_list">Variable list</a>
    * <a href="#bulleted_list">Bulleted list</a>
  * <a href="#miscellaneous">Miscellaneous</a> 
  * <a href="#punctuation">Punctuation</a>
  * <a href="#typography_and_font_conventions">Typography and Font Conventions</a>
* <a href="#word-list">O’Reilly Word List</a> 
 

<section data-type="sect2" id="getting_started">
<h2>Getting Started</h2>

<p>Authors, please consult with your editor or production editor if you have questions specific to your book. If you’d like to use different conventions, please confer with your editor.</p>

<p>This style guide contains information for authors writing in all formats. If you’re an author, please also consult the authoring documentation for the format in which you’re writing (<a href="http://docs.atlas.oreilly.com/writing_in_asciidoc.html">Asciidoc</a>, <a href="http://oreillymedia.github.io/HTMLBook/">HTMLbook</a>, <a href="https://docbook.org">DocBook</a>, or <a href="http://oreillymedia.github.io/production-resources/word/">Word</a>).</p>

<p>Our general style reference is <em>The Chicago Manual of Style</em>, 17th Edition (though some O’Reilly styles differ).</p>

<p>Our dictionary is <em><a href="https://www.merriam-webster.com/">Merriam-Webster’s Collegiate Dictionary</a></em>, 11th Edition. Please refer here for any words not on the O’Reilly word list and note that O’Reilly uses the American spellings of words when they differ.</p>
</section>


<section data-type="sect2" id="considering_electronic_formats">
<h2>Considering Electronic Formats</h2>

<p>Because we use a single set of source files to produce the print and electronic versions of our books, it’s important to keep all possible formats in mind during the authoring, editorial, and production phases.</p>

<ul>
  <li>
    <p>Avoid using "above" and "below" when referencing figures, tables, examples, unnumbered code blocks, equations, etc. (e.g., "In the example below…"). Using live cross references (e.g., "see Figure 2-1") is best, but when that’s not possible, use "preceding" or "following," as the physical placement of elements could be different in reflowable formats.</p>
  </li>
  <li>
    <p>URLs should be anchored to text nodes whenever possible, like they would be on a website. See <a href="#links">Links</a> for more information.</p>
  </li>
</ul>

<div data-type="warning" id="id-BeU0teho"><h6>Warning</h6>
  <p>When anchoring URLs to text nodes, be as descriptive as possible, as the print version of your book renders hyperlinks like this: "text anchor (<a href="http://url.example.com/"><em class="hyperlink">http://url.example.com/</em></a>)."</p>

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
<div data-type="warning" id="id-warning-amazon"><h6>Warning</h6>
  <p>Content should not contain any active links to products on any sales channels other than oreilly.com, including Apple, Google, or Amazon. If these remain, it will cause issues (i.e., Apple and Google will refuse to sell content that links to products on Amazon). For vendors, please flag any links to these online vendors and let the production editor know they exist.</p>
  
  <p>However, saying "XX book is available on Amazon"—sans link—is OK.</p>
</div>
</section>


<section data-type="chapter" id="orm_grammar_punctuation_etc">
<h1>O’Reilly Grammar, Punctuation, etc.</h1>

<section data-type="sect2" id="abbreviationsacronyms">
<h2>Abbreviations/Acronyms</h2>

<ul>
 <li>
  <p>Generic pronouns should be they/their when needed, not he, she, or he/she.
  </p>
 </li>
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

<section data-type="sect2" id="bibliographical_entries">
<h2>Bibliographical Entries and Citations</h2>

<p>In general, when referring to another book within a book’s text, include the author name(s) for up to two authors. For three or more authors, state the first author name, followed by “et al.” (be sure to include the period).</p>

<p>On first reference to another book, include author and publisher name. For example, "You can find more information in <em>The Elements of Typographic Style</em> by Robert Bringhurst (H&amp;M)," or "For more information, consult Robert Bringhurt’s <em>The Elements of Typographic Style</em> (H&amp;M)." On subsequent references, just use the book title.</p>

<p>When referencing an O’Reilly book within the text, note only "O’Reilly" in parentheses, not "O’Reilly Media, Inc." References to other O’Reilly books should be linked to the book’s <a href="http://shop.oreilly.com/category/browse-subjects.do">catalog page</a>.</p>
<div data-type="note" id="id-BeU1hLI7"><h6>Note</h6>
<p>Make sure that the catalog page is anchored to the book’s title, rather than standing on its own like this: "See <a href="http://shop.oreilly.com/product/0636920024033.do"><em>Programming F# 3.0</em></a>." Not this: "See <em>Programming F# 3.0</em> (<a href="http://shop.oreilly.com/product/0636920024033.do"><em class="hyperlink">http://shop.oreilly.com/product/0636920024033.do</em></a>)."</p>
</div>

<h3>Citations</h3>
<p>When citing other materials in bibliographies, reference lists, or footnotes, use the “Notes and Bibliography” system found in the <em>The Chicago Manual of Style</em>, 17th Edition.</p>
</section>

<section data-type="sect2" id="cross_references">
<h2>Cross References</h2>

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
<p>More details on cross-references in Asciidoc are available in our <a href="http://docs.atlas.oreilly.com/writing_in_asciidoc.html#XREFS">Writing in AsciiDoc</a> guide.</p>
</li>
<li>
<p>These cross-reference styles are also available in DocBook under various &lt;xref&gt;: formats. Please refer to the <a href="http://chimera.labs.oreilly.com/books/1234000000058/ch02.html#creating_xrefs">DocBook Authoring Guidelines</a>.</p>
</li>
</ul>

<p>For information about styling URLs and hyperlinks, see <a data-type="xref" href="#considering_electronic_formats">Considering Electronic Formats</a>.</p>
</section>













<section data-type="sect2" id="dates_and_numbers">
<h2>Dates and Numbers</h2>

<ul>
<li>
<p>Spell out numbers under 10, and even hundreds, thousands, millions, etc., unless the same object appears in a sentence with an object 10 or over (five apples; five apples and one hundred oranges; 5 apples and 110 oranges).</p>
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
 <p>Always use the symbol % with numerals rather than the spelled out word (percent), and make sure it is closed up to number: .05%. Unless the percentage begins a sentence or title/caption, the number should be a numeral with the % symbol.</p>
 </li>
 <li>
  <p>Use spaces around inline operators (1 + 1 = 2. NOT 1+1=2).</p>
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
<p>Use multiplication symbol “x” for dimensions, not by (e.g., "8.5 x 11").</p>
</li>
<li>
<p>Ordinal numbers: Spell out first through ninth, use numerals for 10th and above. No superscript.</p>
</li>
</ul>
</section>













<section data-type="sect2" id="figures_tables_and_examples">
<h2>Figures, Tables, and Examples</h2>

<p>Every figure, table, and example should be preceded by a specific in-text reference (for example: see Figure 99-1; Example 1-99 shows; Table 1-1 lists, etc.). Figures, tables, and examples should not be introduced with colons or phrases like “in the following figure,” or “as shown in this table.” Lack of specific in-text references may cause incorrect placement of figures.</p>

<p>If you are writing or copyediting in Word, figure, table, and example numbers should be numbered as follows: 1-2 (note hyphen [-], not en dash [–] between numbers). The first number is the chapter number. This will be soft-coded in production if not during the writing process.</p>

<p>If you are writing or copyediting in Asciidoc, please refer to <a href="http://docs.atlas.oreilly.com/writing_in_asciidoc.html#XREFS">Writing in AsciiDoc</a> for examples of Asciidoc cross references.</p>

<p>If you are writing or copyediting in DocBook, please reference each figure, table, and example with an &lt;xref&gt;.</p>

<p>Any word groupings within a figure should have an initial cap on the first word only, with the exception of proper nouns. Generally, we don’t use periods at the end of these word groupings.</p>

<ul>
<li>
<p>Figure 1-1. Figure captions are initial-capped on first word only, with the exception of proper nouns.  No code styling within the figure name or caption. There is no period after figure captions, but if all captions are long and sentence style, periods can be used as long as they are used consistently throughout.</p>
</li>
<li>
<p>Table 1-1. Column heads and table titles are initial-capped on the first word only, with the exception of proper nouns.  No code styling within the table name or caption. There is no period after table titles.</p>
</li>
<li>
<p>Example 1-1. Example titles are initial-capped on the first word only, with the exception of proper nouns.  No code styling within the example name or caption. There is no period after example titles.</p>
</li>
</ul>

<p>When working in Word, make sure all table cells are tagged with a cell paragraph tag, even if they’re blank. Any bold “headings” that appear below the very first row of a table should be tagged CellSubheading rather than CellHeading.</p>

<p>Also in Word, all figures must be within a FigureHolder paragraph followed directly by a FigureTitle paragraph.</p>
</section>













<section data-type="sect2" id="code">
<h2>Code</h2>








<section data-type="sect3" id="line-length-ZKs1FLck">
<h3>Line Length</h3>

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
  <td><p><strong>Trade 6x9</strong></p></td>
  <td><p>76</p></td>
  <td><p>72</p></td>
  <td><p>65</p></td>
  <td><p>80</p></td>
  <td><p>69</p></td>
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













<section data-type="sect3" id="syntax-highlighting-zVsXIecp">
<h3>Syntax Highlighting</h3>

<p>We use a tool called Pygments to colorize code. In most books, code will appear in black and white in the print book and in color in all electronic formats, including the web pdf. If you’re an author, please consult the <a href="http://pygments.org/docs/lexers/">list of available lexers</a> and apply them to your code as you write. To apply syntax highlighting in Asciidoc, consult <a href="http://docs.atlas.oreilly.com/writing_in_asciidoc.html#syntax_highlighting">Writing in AsciiDoc</a>. To apply syntax highlighting in DocBook, consult <a href="http://chimera.labs.oreilly.com/books/1234000000058/ch02.html#syntax_highlighting">the DocBook Authoring Guidelines</a>. To apply syntax highlighting in Word, consult the <a href="http://oreillymedia.github.io/production-resources/word/#syntax-highlighting">O’Reilly Media Word Template Quickstart Guide</a>.</p>
</section>













<section data-type="sect3" id="formatting-code-in-word-yDsgtXca">
<h3>Formatting Code in Word</h3>

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

<p>Footnotes should contain more than just a URL, whether a full citation for the text the URL points to or context for where the link leads.</p>

<p>This:</p>

<blockquote>
 <p>1. The Wikipedia entry on JavaScript (https://en.wikipedia.org/wiki/JavaScript) provides more information.</p>
 <p>2. Grove, John. 2015. “Calhoun and Conservative Reform.” American Political Thought 4, no. 2 (March): 203–27. https://doi.org/10.1086/680389.</p>
</blockquote>

<p>Not this:</p>

<blockquote>
<p>1. https://en.wikipedia.org/wiki/JavaScript</p>
 <p>2. https://doi.org/10.1086/680389</p>
 </blockquote>

<p>More details about styling footnotes in AsciiDoc are in <a href="http://docs.atlas.oreilly.com/writing_in_asciidoc.html#adding_footnotes">Writing in AsciiDoc</a>.</p>
</section>













<section data-type="sect1" id="headings">
<h1>Headings</h1>

<ul>
<li>
 <p>Capitalization in headings:</p>
 <ul>
  <li><p>In most of our design templates, A- and B-level headings are initial-capped (or title case): cap the first letter of each word, with the exception of articles, conjunctions, and program names or technical words that are always lowercase and coordinating conjunctions (e.g., and, but, for, etc.).</p></li> 
  <li><p>Prepositions of four letters or fewer are not initial-capped, unless they function as part of a verb (e.g., “Set Up Your Operating System”).</p></li> 
  <li><p>Hyphenated words in subordinating conjunctions (e.g., as, if, that, because, etc.) are always initial-capped (even if they are four letters or less). Hyphenated words in titles or captions should both be capped if the second word is a main word, but only the first should be capped if the second word isn’t too important (it’s a bit of a judgment call). For example: Big-Endian, Built-in. See <em>The Chicago Manual of Style</em>.</p>
</li>
  <li>
<p>C-level headings have initial cap on the first word only (also called sentence-case), with the exception of proper nouns and the first word that follows a colon (unless that word refers to code and should be lowercase).</p>
</li>
  <li>
<p>D-level headings (rare) are run-in with the following paragraph and have an initial cap on the first word only, with the exception of proper nouns and the first word that follows a colon (unless that word refers to code and should be lowercase), with a period at the end of the heading.</p>
</li>
  <li>
<p>Sidebar titles are initial-capped, or title case (like A- and B-level headings, mentioned previously).</p>
</li>
  <li>
<p>Admonition (note/tip/warning) titles are initial-capped, or title case (like A- and B-level headings, mentioned previously). Admonition titles are optional.</p>
</li>
 </ul>
 </li>
<li>
<p>Headings should not contain inline code font or style formatting such as bold, italic, or code font.</p>
</li>
<li>
 <p>Headings should always immediately precede body text. Do not follow a heading with an admonition or another heading without some form of introductory or descriptive text.</p>
 </li>
 
</ul>
</section>



<section data-type="sect1" id="links">
<h1>Links</h1>

<p>In books produced in Atlas, URLs should be anchored to descriptive text where possible. In ebook versions, the markup will render like this:</p>

<p>Navigate to the <a href="https://oreilly.com">O'Reilly homepage</a> for more information.</p>

<p>In the print book, the URL will unfurl in a parenthetical after the linked text:</p>

<p>Navigate to the O'Reilly homepage (<em>https://oreilly.com</em>) for more information.</p>

<p>Because of this difference in appearance of links in ebooks and print books, long and complex URLs are shortened during production. In the past, we used bit.ly to shorten these URLs, but as of May 2019, all shortened links will be hosted and tracked internally, using the oreil.ly short link. </p>

<p>We do not anchor URLs to text in books produced in InDesign.</p>

</section>





<section data-type="sect1" id="lists">
<h1>Lists</h1>

<p>Typically, we use three types of lists: numbered lists, for ordered steps or chronological items; variable lists, for terms and explanations/definitions; and bulleted lists, for series of items. List items are sentence-capped. List items should be treated as separate items and should not be strung together with punctuation or conjunctions. </p> 

<p>Not O'Reilly style:</p>
<ul>
 <li>Here is an item, and</li>
 <li><p>here is another item; and</p></li>
 <li><p>here is the final item.</p></li>
 </ul>
 
 <p>O'Reilly style:</p>
 <ul>
 <li><p>Here is an item</p></li>
 <li><p>Here is another item</p></li>
 <li><p>Here is the final item</p></li>
 </ul>

<p>Following are examples of each type of list.</p>


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
<p>Do not use a hyphen between an adverb and the word it modifies. So, “incredibly wide table” rather than “incredibly-wide table.”</p>
</li>
<li>
<p>Unless part of a proper noun, close up words with the prefixes “micro,” “meta,” “multi,” “pseudo,” “re,” “non,” “sub,” and "co" (e.g., “multiusers,” “pseudoattribute,” “nonprogammer,” “subprocess,” "coauthor"). Any exceptions will be noted in the word list below (e.g., "re-create").</p>
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
 <li>
<p>Do not stack admonitions, sidebars, or headings.</p>
</li>
</ul>
</section>













<section data-type="sect1" id="punctuation">
<h1>Punctuation</h1>

<p>For anything not covered in this list, please consult the Chicago Manual of Style, 17th Edition.</p>

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


<p>The following shows the basic font conventions used in O’Reilly books. Follow these links for detailed instructions for applying these styles in <a href="http://docs.atlas.oreilly.com/writing_in_asciidoc.html#INLINES">Asciidoc</a>, <a href="http://chimera.labs.oreilly.com/books/1234000000058/index.html:">DocBook</a>, and <a href="http://oreillymedia.github.io/production-resources/word/#paragraph-character-styles">Word</a>.</p>
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
<td><p>Emphasized words (shouting!).</p><p>Please use italics rather than bold for emphasis.</p></td>
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

<p>These font conventions may vary slightly for each project; please consult your editor, the production editor, or the freelance coordinator if you have any questions. <em>Please note:</em> Word authors should refer to the <a href="http://docs.atlas.oreilly.com/writing_in_asciidoc.html#INLINES">Word Template Quickstart Guide</a>; DocBook authors should refer to our <a href="https://prod.oreilly.com/external/tools/docbook/docs/authoring/">DocBook Authoring Guidelines</a> (username: guest; leave the password blank).</p>

<p>It’s <em>very</em> important to follow tagging conventions for terms. The method for applying conventions will vary depending on the format: Word/OpenOffice, DocBook XML, or InDesign. Please consult with your editor or  <em>toolsreq@oreilly.com</em> for instructions specific to each environment.</p>

<p>For Word copyediting, please do the following before submitting files for conversion: replace any tabs in code with the appropriate number of spaces (see earlier section, <a data-type="xref" href="#code">Code</a>); convert any remaining Word comments to tagged Comment paragraphs highlighted in blue; search for any manual linebreaks (^l) and delete or replace with paragraph breaks as appropriate; and accept all changes and make sure filenames adhere to house style.</p>
<div data-type="note" id="note-1"><h6>Note</h6>
<p>If you’re an author, and you want to use a font convention that is slightly different for one of the following items, check with your editor first—some things can change; some can’t.</p>

<p>For instance, URLs will not be anything but <em>italic</em>, but you might come up with a different font convention for function names or menu items. If you do use something that differs from the following list, please write it down on your printout of this stylesheet, which should be submitted with your manuscript.</p>

<p>Or, if you have a “new” element, please consult with your editor about which font to use, then write it on your printout and submit it with your manuscript.</p>
</div>
</section>



<h1 id="cover-style">O'Reilly Cover Style</h1>
_Use Chicago Maual of Style, 17th Edition for anything not mentioned here:_

<p>Bulleted lists on the back cover should begin with a capitalized word and end with <em>no</em> punctuation. Even if the list item is a complete sentence, it will not take a period.</p>


<h1 id="word-list">O’Reilly Word List</h1>

_Alphabetical Word List: Default Spellings_

<a href="#wordlist-A">A</a> | <a href="#wordlist-B">B</a> | <a href="#wordlist-C">C</a> | <a href="#wordlist-D">D</a> | <a href="#wordlist-E">E</a> | <a href="#wordlist-F">F</a> | <a href="#wordlist-G">G</a> | <a href="#wordlist-H">H</a> | <a href="#wordlist-I">I</a> | <a href="#wordlist-J">J</a> | <a href="#wordlist-K">K</a> | <a href="#wordlist-L">L</a> | <a href="#wordlist-M">M</a> | <a href="#wordlist-N">N</a> | <a href="#wordlist-O">O</a> | <a href="#wordlist-P">P</a> | <a href="#wordlist-Q">Q</a> | <a href="#wordlist-R">R</a> | <a href="#wordlist-S">S</a> | <a href="#wordlist-T">T</a> | <a href="#wordlist-U">U</a> | <a href="#wordlist-V">V</a> | <a href="#wordlist-W">W</a> | <a href="#wordlist-X">X</a> | <a href="#wordlist-Y">Y</a> | <a href="#wordlist-Z">Z</a> |

<h2 id="wordlist-A">A</h2>

* acknowledgments
* ActionScript
* ActiveX control
* Addison-Wesley
* ad hoc
* ADO.NET
* Agile (cap when referring to Agile software development or when used on its own as a noun)
* Ajax
* a.k.a. or aka (be consistent)
* a.m. or A.M.
* Alt key
* Alt-N
* anonymous FTP
* anti-pattern
* appendixes
* applet (or Java applet)
* AppleScript
* AppleScript Studio (ASS)
* ARPAnet
* ASCII
* ASP.NET
* at sign
* autogenerate
* awk

<h2 id="wordlist-B">B</h2>

* backend
* background processes
* backquote
* backslash
* Backspace key
* backtick
* backup (n)
* back up (v)
* backward
* backward compatible
* bandwidth
* BeOS
* Berkeley Software Distribution (BSD)
* Berkeley Unix (older books may have UNIX)
* BHOs
* Big Design Up Front (BDUF)
* bioinformatics
* bitmap
* bit mask
* Bitnet
* bit plane
* bitwise operators
* BlackBerry
* Boolean (unless referring to a datatype in code, in which case s/b lowercase)
* Bourne-again shell (bash)
* Bourne shell
* braces or curly braces
* brackets or square brackets
* browsable
* _build-&gt;measure-&gt;learn_ cycle
* built-in (a, n)
* button bar
 
<h2 id="wordlist-C">C</h2>

* CacheStorage
* call-to-cation
* Caps Lock key
* caret or circumflex
* CAT-5
* CD-ROM
* C language (n)
* C-language (a)
* checkbox
* checkmark
* check-in (n)
* classpath
* click-through (a)
* client/server
* client side (n)
* client-side (a)
* cloud-native (a) (cloud-native application)
* co-class
* coauthor
* code set
* colorcell
* colormap
* Command key (Macintosh)
* command line (n)
* command-line (a)
* Common Object Request
* Broker Architecture (CORBA)
* compact disc
* compile time (n)
* compile-time (a)
* CompuServe
* Control key (Mac)
* copyleft
* copyright
* coworker
* CPU
* criterion (s), criteria (p)
* cross-reference
* C shell
* &lt;CR&gt;&lt;LF&gt;
* Ctrl key (Windows)
* Ctrl-Alt-Delete
* Ctrl-N
* curly braces or braces
* cybersecurity

<h2 id="wordlist-D">D</h2>
* database
* data block
* datacenter or data center (be consistent)
* Data Encryption Standard (DES)
* datafile
* datatype or data type (be consistent)
* data is
* dataset or data set (be consistent)
* DB-9
* Debian GNU/Linux
* decision making (n)
* decision-making (a)
* DevOps
* dial-up (a)
* dial up (v)
* disk
* disk-imaging software
* Delete key
* design time (n)
* design-time (a)
* DNS
* DocBook
* Document Object Model (DOM)
* Domain Name System
* dot
* dot-com
* double-click
* double-precision (a)
* double quotes
* down arrow
* downlevel (a)
* download
* drag-and-drop (n)
* drag and drop (v)
* drop-down (a)

<h2 id="worldlist-E">E</h2>
* ebook* ebusiness* ecommerce 
* eBay
* Emacs
* email
* empty-element tag
* end-of-file (EOF)
* end-tag
* end user (n.), end-user (adj.)
* Engines of Groth
* Enter key
* equals sign
* ereader
* Escape key (or Esc key)
* et al.
* Ethernet
* exclamation mark
* Exim
        

<h2 id="wordlist-F">F</h2>
* failback
* failover
* fax
* file manager
* filename
* file server
* filesystem
* file type
* FireWire
* foreground
* FORTRAN
* Fortran 90
* forward (adv)
* frame type
* FreeBSD
* Free Documentation License (FDL)
* Free Software Foundation (FSF)
* frontend
* _ftp_ (Unix command)
* FTP (protocol)
* FTP site
* full stack (Full Stack in headings), no hyphen, even if adjective
        
<h2 id="wordlist-G">G</h2>

* gateway
* Gb (gigabit)
* GB (gigabyte)
* GBps (gigabytes per second)
* GHz
* gid
* GIMP
* GNOME
* GNU Emacs
* GNU Public License (GPL)
* GNUstep
* Google PageRank
* grayscale
* greater-than sign or &gt;
* greenlight (v)
* GUI, GUIs
        
<h2 id="wordlist-H">H</h2>

* handcode
* handoff (n)
* hardcoded
* hardcore
* hardcode (v)
* hardcopy
* hard link
* hash sign or sharp sign
* high-level (adj)
* home page
* hostname
* hotspot
* HTML
* HTTP
* hypertext
        
<h2 id="wordlist-I">I</h2>

* IDs
* IDE
* IndexedDB
* inline
* inode
* interclient
* internet, the internet
* internetwork
* intranet
* Intrinsics
* I/O
* IP (Internet Protocol)
* IPsec
* ISO
* ISP
 
<h2 id="wordlist-J">J</h2>

* Jabber
* Jabber client
* Jabber server
* Jabber applet
* JAR archive
* JAR file
* JavaScript
* JPEG

<h2 id="wordlist-K">K</h2>

* K Desktop Environment (KDE)
* Kb (kilobit)
* KB (kilobyte) (denotes file size or disk space)
* Kbps (kilobits per second)
* Kerberos
* keepalive (n or a)
* keyclick
* keycode
* keymaps
* keypad
* keystroke
* keysym
* keywords
* key performance indicators (KPIs)
* kHz (kilohertz)
* Korn shell

<h2 id="wordlist-L">L</h2>

* Lean (capitalize noun or adjective when referring to Lean business methodology)
* local area network or LAN
* left angle bracket or &lt;
* lefthand (a)
* leftmost
* less-than sign or &lt;
* leveled (not levelled)
* life cycle
* line-feed (a)
* line feed (n)
* Linux
* LinuxPPC
* listbox
* logfile
* login, logout, or logon (n or a)
* log in, log out, or log on (v)
* lower- and uppercase
* lowercase
* lower-level (a)
* lower-right (a)
* Linux Professional Institute (LPI)

<h2 id="wordlist-M">M</h2>

* Macintosh
* Mac OS
* Mac OS 9 (_note the use of spaces_)
* macOS (replaces Mac OS X)
* machine learning (noun), machine-learning (adj.)
* mail-handling (adjective)
* manpage
* markup
* Mb (megabit)
* MB (megabyte)
* MBps (megabytes per second)
* McGraw-Hill
* menu bar
* metacharacter
* Meta key
* Meta-N
* MHz (megahertz)
* mice or mouses (be consistent)
* microservices
* Microsoft Windows
* Microsoft Windows Me
* Microsoft Windows NT
* Microsoft Windows XP
* Microsoft Windows 2000
* MIDlet
* MKS Toolkit
* MS-DOS
* multiline (Unless before a proper noun, always close up the following prefixes: “non,” “sub,” “multi,” and “pseudo.”)
* Multi-Touch (when referring to Apple's trademark)
* My Services
* MySpace
        
<h2 id="wordlist-N">N</h2>

* nameserver
* name service
* namespace
* the Net
* .NET
* NetBIOS
* NetBSD
* NetInfo
* newline
* newsgroups
* NeXTSTEP
* NOOP
* nonlocal
* NoSQL
* Novell NetWare
* the _New York Times_

<h2 id="wordlist-O">O</h2>

* Objective-C
* object linking and embedding (OLE)
* object-oriented programming (OOP)
* object request broker (ORB)
* OK
* offline
* offload
* onboard
* ongoing
* online
* open source (n or a)
* open source software (OSS)
* OpenBSD
* OpenMotif
* OpenStep
* OpenWindows
* Option key (Macintosh)
* Oracle7
* Oracle8
* Oracle 8.0
* Oracle 8_i_ (italic “i”)
* Oracle 9_i_ (italic “i”)
* Oracle Parallel Query Option
* O’Reilly Media, Inc.
* OS/2
* OSA
* OSF/Motif
* OS X

<h2 id="wordlist-P">P</h2>

* packet switch networks
* Paint Shop Pro
* pagefile
* page rank (but Google PageRank™)
* parentheses (p)
* parenthesis (s)
* Pascal
* password
* pathname
* pattern-matching (a)
* peer-to-peer (or P2P)
* % (not percent)
* performant (Oracle)
* period
* Perl
* Perl DBI
* plain text (n)
* plain-text (a)
* Plug and Play (PnP)
* plug in (v)
* plug-in (a, n)
* p.m. or P.M.
* Point-to-Point Protocol (PPP)
* pop up (v, n)
* pop-up (a)
* POP-3
* Portable Document Format (PDF)
* Portable Network Graphics (PNG)
* Portable Operating
*   System Interface (POSIX)
* POSIX-compliant
* Post Office Protocol (POP)
* postprocess
* PostScript
* Prentice Hall
* process ID
* progress bar
* pseudoattribute
* pseudo-tty
* public key (n)
* public-key (a)
* pull-down (a)

<h2 id="wordlist-Q">Q</h2>

* qmail
* Qt
* QuarkXPress
* Quartz
* Quartz Extreme
* QuickTime
* quotation marks (spell out first time; it can be “quotes” thereafter)

<h2 id="wordlist-R">R</h2>

* random-access (a)
* RCS
* read-only (a)
* read/write
* real time (n)
* real-time (a)
* re-create
* Red Hat Linux
* Red Hat Package Manager (RPM)
* redirection
* reference page or manpage
* remote-access server
* rename
* Rendezvous (_Mac OS X Zeroconf networking_)
* Return (key)
* RFC 822
* rich text (n)
* rich-text (a)
* right angle bracket or
* greater-than sign (&gt;)
* right-click
* righthand (a)
* rmail
* roll back (v)
* rollback (n)
* rootkit
* Rubout key
* rulebase
* ruleset
* runtime (n, a)

<h2 id="wordlist-S">S</h2>

* Samba
* saveset
* screen dump
* screenful
* screensaver
* screenshot
* scroll bar
* securelevel (in Linux)
* Secure Shell (SSH)
* Secure Sockets Layer (SSL)
* sed scripts
* semicolon
* server-dependent
* server side (n)
* server-side (a)
* service worker
* servlet
* set up (v)
* setup (n)
* SGML
* sharp sign or hash sign
* shell (lowercase even in shell name: Bourne shell)
* shell scripts
* Shift key
* shortcut
* Simple API for XML (SAX)
* single-precision (a)
* single quote
* site map
* slideshow
* Smalltalk
* SMP (a, n)
* SOAP
* Social Security number (SSN)
* source code
* space bar
* spam (not SPAM)
* spellcheck
* spellchecker
* split screen
* square brackets or brackets
* standalone
* standard input (stdin)
* standard output (stdout)
* start tag
* startup file
* stateful
* stateless
* status bar
* stylesheet
* subprocess (Unless before a proper noun, always close up the following prefixes: “non,” “sub,” “multi,” and “pseudo.”)
* SUSE Linux
* swapfile
* swapspace
* sync
* system administrator
* system-wide

<h2 id="wordlist-T">T</h2>

* 10-baseT
* T1
* t-shirt
* Tab key
* TAR file
* TCP/IP
* Telnet (the protocol)
* telnet (v)
* terabyte
* T<subscript>E</subscript>X
* texinfo
* text box
* text-input mode
* thread pooling (n)
* time-sharing processes
* timestamp
* time zone
* title bar
* Token Ring
* toolbar
* toolkit
* tool tip
* top-level (a)
* toward
* trade-off
* troubleshoot

<h2 id="wordlist-U">U</h2>

* UK (for United Kingdom)
* Ultrix
* Universal Serial Bus (USB)
* Unix (UNIX in many books, esp. older ones)
* up arrow
* upper- and lowercase
* uppercase
* upper-left corner
* UPSs
* up-to-date
* URLs
* US (for United States)
* Usenet
* user ID (n)
* user-ID (a)
* username

<h2 id="wordlist-V">V</h2>

* v2 or version 2
* VAX/VMS
* VB.NET
* versus (avoid vs.)
* vice versa
* VoiceXML
* Visual Basic .NET
* Visual Basic 6 or VB 6
* Visual C++ .NET
* Visual Studio .NET
* VS.NET
* Volume One

<h2 id="wordlist-W">W</h2>

* the _Wall Street Journal_
* the web (n)
* web (a)
* web client
* webmaster
* web page
* web server
* web services (unless preceded by a proper noun, as in Microsoft Web Services)
* website
* white pages
* whitepaper (I printed my whitepaper on white paper.)
* whitespace
* wide area network or WAN
* WiFi
* wiki
* wildcard
* Windows 95
* Windows 98
* Windows 2000
* Windows NT
* Windows Vista
* Windows XP
* Wizard (proper noun)
* wizard (a, n)
* workaround
* workbench
* workgroup
* workstation
* World Wide Web (WWW)
* wraparound
* writable
* write-only (a)
* WYSIWYG

<h2 id="wordlist-X">X</h2>

* (x,y) (no space)
* x-axis
* Xbox
* X client
* _x_ coordinate
* X protocol
* X server
* X Toolkit
* XView
* X Window series
* X Window System
* x86
* xFree86
* XHTML
* XLink
* XML
* XML Query Language (XQuery)
* XML-RPC
* XPath
* XPointer
* XSL
* XSLT

<h2 id="wordlist-Y">Y</h2>
* Yahoo!
* y-axis
* _y_ coordinate

<h2 id="wordlist-Z">Z</h2>
* Zeroconf (short for “Zero Configuration”)
* zeros
* zip code
* zip (v)
* ZIP file
