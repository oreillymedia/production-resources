---
layout: default
title: O'Reilly Style Guide
---

# O'Reilly Style Guide and Word List

* <a href="#getting_started">About O'Reilly Style</a>
* <a href="#considering_electronic_formats">Considering Electronic Formats</a>
* <a href="#orm_grammar_punctuation_etc">O’Reilly Grammar, Punctuation, etc.
  * <a href="#abbreviationsacronyms">Abbreviations/Acronyms</a>
  * <a href="#bibliographical_entries">Bibliographical Entries</a>
    * <a href="#footnotes">Footnotes</a>
  * <a href="#cross_references">Cross References</a>
  * <a href="#headings">Headings</a>
  * <a href="#dates_and_numbers">Dates and Numbers</a>
  * <a href="#figures_tables_and_examples">Figures, Tables, and Examples</a>
  * <a href="#code">Code</a>
    * <a href="#line-length-ZKs1FLck">Line Length</a>
    * <a href="#syntax-highlighting-zVsXIecp">Syntax Highlighting</a>
    * <a href="#formatting-code-in-word-yDsgtXca">Formatting Code in Word</a>
  * <a href="#gen_ai">Generative AI</a>
  * <a href="#links">Links</a>
  * <a href="#lists">Lists</a>
    * <a href="#numbered_list">Numbered list</a>
    * <a href="#variable_list">Variable list</a>
    * <a href="#bulleted_list">Bulleted list</a>
  * <a href="#miscellaneous">Miscellaneous</a> 
  * <a href="#punctuation">Punctuation</a>
  * <a href="#typography_and_font_conventions">Typography and Font Conventions</a>
* <a href="#word-list">O’Reilly Word List</a> 
 

<section data-type="sect1" id="getting_started">
<h1>About O'Reilly Style</h1>

<p>This style guide is for authors, copyeditors, and proofreaders working on books of all formats. As writers and editors, we know that language changes over time, so <strong>please check back regularly for updates to terms and conventions</strong>. Recent additions will be set in bold for a few months.</p>

<p>Authors, please also consult the authoring documentation for the format in which you’re writing (<a href="http://docs.atlas.oreilly.com/writing_in_asciidoc.html">Asciidoc</a>, <a href="http://oreillymedia.github.io/HTMLBook/">HTMLbook</a>, <a href="https://docbook.org">DocBook</a>, or <a href="http://oreillymedia.github.io/production-resources/word/">Word</a>). For sponsored projects, please see our <a href="https://oreil.ly/editorial-independence">statement of editorial independence</a>.</p>

<p>For term conventions, check our guide and word list first, then <em>The Chicago Manual of Style</em>, 17th edition, then <em><a href="https://www.merriam-webster.com">Merriam-Webster’s Collegiate Dictionary</a></em>. Use your book-specific word list (provided by production) to document style choices that differ or are not covered here (e.g., A.M. or a.m., data center or datacenter).</p>

<p>To avoid unintentional bias, when writing about groups of people, check the group’s advocacy organization for guidance on appropriate language. The <a href="https://consciousstyleguide.com">Conscious Style Guide</a> is one good resource, aggregating links to relevant organizations. <strong>The <a href="https://itconnect.uw.edu/work/inclusive-language-guide">University of Washington has another</a> that is tech-specific.</strong> The <a href="https://ncdj.org/style-guide">Disability Language Style Guide</a> is a thorough guide to writing about disabilities with sensitivity. Always follow a person’s preference and note exceptions, if necessary (e.g., quoting research that is decades old).</p>

<p>For questions specific to your book or assignment, please consult with your editor or production editor.</p>
</section>




<section data-type="sect1" id="considering_electronic_formats">
<h1>Considering Electronic Formats</h1>

<p>Because we use a single set of source files to produce the print and electronic versions of our books, it’s important to keep all formats in mind while writing and editing:</p>

<ul>
  <li>
    <p>Avoid using "above" and "below" to reference figures, tables, examples, unnumbered code blocks, equations, etc. (e.g., "In the example below…"). Using live cross references (e.g., "see Figure 2-1") is best, but when that’s not possible, use "preceding" or "following," as the physical placement of elements could be different in reflowable formats.</p>
  </li>
  <li>
    <p>Anchor URLs to text nodes whenever possible, like you would on a website. See <a href="#links">Links</a> for more information.</p>

<div data-type="tip" id="id-BeU0teho">
  <p>Be as descriptive as possible because the print version of your book renders hyperlinks like this: "text anchor (<a href="http://url.example.com/"><em class="hyperlink">http://url.example.com/</em></a>)."</p>

<p>For example, this:</p>
<blockquote>
<p>Download the source code (<a href="http://www.url.thisismadeup.com"><em class="hyperlink">http://www.url.thisismadeup.com</em></a>) and install the package"</p></blockquote>

<p>is more useful than this:</p>
<blockquote>
<p>"Download the source code from this website (<a href="http://www.url.thisismadeup.com"><em class="hyperlink">http://www.url.thisismadeup.com</em></a>) and install the package."</p></blockquote>

<p>Avoid anchoring URLs to generic words or phrases such as "here," "this website," etc.</p>
</div>
  </li>

<li>
<p>Long URLs will be shortened so that they’re easy for print readers to type manually.</p>
 
<div data-type="warning" id="id-warning-amazon">
  <p>Do not link to products on any sales channels other than oreilly.com, including Apple, Google, or Amazon. Apple and Google will refuse to sell content that links to products on Amazon. Vendors, please flag any links to these sales channels and let the production editor know they exist.</p>
  
  <p>Saying "XX book is available on Amazon"—sans link—is OK.</p>
</div>
</li>
</ul>
</section>




<section data-type="sect1" id="orm_grammar_punctuation_etc">
<h1>O’Reilly Grammar, Punctuation, etc.</h1>

<p>For any words or conventions not covered here, refer to <em>The Chicago Manual of Style</em>, 17th edition and <em><a href="https://www.merriam-webster.com/">Merriam-Webster</a></em>.</p>

<p><a href="#getting_started">back to top</a></p>


<section data-type="sect2" id="abbreviationsacronyms">
<h2>Abbreviations/Acronyms</h2>

<ul>
 <li>
  <p>Generic pronouns should be they/their when needed, not he, she, or he/she.
  </p>
 </li>
<li>
 <p>Acronyms should <em>generally</em> be spelled out the first time they appear in a book, as in: "collaborative development environment (CDE)." See the <a href="#word-list">Word List</a> for common exceptions. After the acronym has been defined, you should generally use the acronym only (not the whole term, unless it makes more sense contextually to use the whole term). Usually, acronyms are defined only once per book. But if the author prefers, we can also define certain terms the first time they appear in each chapter.</p>
</li>
 <li>
  <p>Acronyms should be capitalized when expanded only if the term is a proper noun (and spelled that way by the company). For example, key performance indicator (KPI), but Amazon Web Services (AWS).</p>
 </li>
<li>
<p>A.M. and P.M. or a.m. and p.m.—be consistent.</p>
</li>
<li>
<p>K = 1,024; k = 1,000. So a 56 kbps modem is equal to 56,000 bps, while 64 K of memory is equal to 65,536.</p>
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

<p><a href="#getting_started">back to top</a></p>
</section>





<section data-type="sect2" id="bibliographical_entries">
<h2>Bibliographical Entries and Citations</h2>

<p>In general, when referring to another book within a book’s text, include the author name(s) for up to two authors. For three or more authors, state the first author name, followed by “et al.” (be sure to include the period).</p>

<p>On first reference to another book, include author and publisher name. For example, "You can find more information in <em>The Elements of Typographic Style</em> by Robert Bringhurst (H&amp;M)," or "For more information, consult Robert Bringhurst’s <em>The Elements of Typographic Style</em> (H&amp;M)." On subsequent references, just use the book title.</p>

<p>When referencing an O’Reilly book within the text, note only "O’Reilly" in parentheses, not "O’Reilly Media, Inc." References to other O’Reilly books should be linked to the book’s <a href="http://shop.oreilly.com/category/browse-subjects.do">catalog page</a>.</p>

<div data-type="warning">
<p>Make sure that the catalog page is anchored to the book’s title, rather than standing on its own like this: "See <a href="http://shop.oreilly.com/product/0636920024033.do"><em>Programming F# 3.0</em></a>." <em>NOT THIS:</em> "See <em>Programming F# 3.0</em> (<a href="http://shop.oreilly.com/product/0636920024033.do"><em class="hyperlink">http://shop.oreilly.com/product/0636920024033.do</em></a>)."</p>
</div>

<h3>Citations</h3>
<p>When citing other materials in bibliographies, reference lists, or footnotes, use the “Notes and Bibliography” system from the <a href="https://www.chicagomanualofstyle.org/tools_citationguide.html"><em>The Chicago Manual of Style</em></a>, 17th edition. <strong>Chicago also has an Author-Date system that some authors prefer, which is perfectly acceptable. If there is no discernible consistency, suggest Chicago's Notes for footnotes and Bibliography for endnotes or back matter.</strong></p> 

<p><strong>Let your production editor know which of Chicago's systems you applied by adding a note to the Word List Doc.</strong></p>

<section data-type="sect3" id="footnotes">
<h3>Footnotes</h3>

<ul>
 <li>
<p>Footnotes in running text are numbered and start over at 1 in each chapter. Footnote markers in running text should always appear after punctuation.</p>

<div data-type="tip">
<p>This: The following query selects the <code>symbol</code> column and all columns from <code>stocks</code> whose names start with the prefix price.<sup>1</sup></p>

<p><em>Not this:</em> The following query selects the <code>symbol</code> column and all columns from <code>stocks</code> whose names start with the prefix price<sup>1</sup>.</p>
</div>
</li>
<li>
<p>Footnotes should contain more than just a URL, whether a full citation for the text the URL points to or context for where the link leads.</p>

<div data-type="tip">
 <p>This:</p>
 <ol>
  <li>The Wikipedia entry on JavaScript (https://en.wikipedia.org/wiki/JavaScript) provides more information.</li>
  <li>Grove, John. 2015. “Calhoun and Conservative Reform.” <em>American Political Thought</em> 4, no. 2 (March): 203–27. https://doi.org/10.1086/680389.</li>
 </ol>

<p><em>Not this:</em></p>
<ol>
  <li>https://en.wikipedia.org/wiki/JavaScript</li>
 <li>https://doi.org/10.1086/680389</li>
 </ol>
 </div>
 </li>
<li>
<p>Table footnotes are lettered (a, b, c, etc.) and appear directly after the table. They should be kept to a minimum.</p>
</li>
</ul>

<p>More details about styling footnotes in AsciiDoc are in <a href="http://docs.atlas.oreilly.com/writing_in_asciidoc.html#adding_footnotes">Writing in AsciiDoc</a>.</p>
</section>

<p><a href="#getting_started">back to top</a></p>

</section>

<section data-type="sect2" id="cross_references">
<h2>Cross References</h2>

<p>Here are a few examples of cross references:</p>

<ul>
<li>
<p>Chapter: See Chapter 27.</p>
</li>
<li>
<p>Section: See “Treatment” on page xx. (The text “on page xx” will be dynamic in Atlas, updating as page numbers change.)</p>
</li>
<li>
<p>Figure: ...as shown in Figure 1-1.</p>
</li>
<li>
<p>Sidebars: See “A Note for Mac Users” on page xx. (As with section xrefs, the page number will update automatically in Atlas.)</p>
</li>
</ul>
 
<p>More details on cross-references in Asciidoc are available in our <a href="http://docs.atlas.oreilly.com/writing_in_asciidoc.html#XREFS">Writing in AsciiDoc</a> guide.</p>

<p>These cross-reference styles are also available in DocBook under various &lt;xref&gt;: formats. Please refer to the <a href="http://chimera.labs.oreilly.com/books/1234000000058/ch02.html#creating_xrefs">DocBook Authoring Guidelines</a>.</p>

<p>For information about styling URLs and hyperlinks, see <a data-type="xref" href="#considering_electronic_formats">Considering Electronic Formats</a>.</p>

<p><a href="#getting_started">back to top</a></p>
</section>








<section data-type="sect2" id="headings">
<h2>Headings</h2>

 <p>Capitalization in headings:</p>
 
 <ul>
  <li><p>In most of our design templates, A- and B-level headings are initial-capped (or title case): cap the first letter of each word, with the exception of articles, conjunctions, and program names or technical words that are always lowercase.</p></li> 
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
 

<p>Headings should not contain inline code font or style formatting such as bold, italic, or code font.</p>

<p>Headings should always immediately precede body text. Do not follow a heading with an admonition or another heading without some form of introductory or descriptive text.</p>

<p><a href="#getting_started">back to top</a></p>
</section>





<section data-type="sect2" id="dates_and_numbers">
<h2>Dates and Numbers</h2>

<p>What to spell out and when:</p>
<ul>
<li>
 <p>Spell out numbers from zero to nine and certain round multiples of those numbers unless the same object appears in a sentence with an object 10 or over (five apples; five apples and one hundred oranges; 5 apples and 110 oranges). </p>
 </li>
  <li><p>Whole numbers one through nine followed by hundred, thousand, million, billion, and so forth are usually spelled out (except in the sciences or with monetary amounts).</p>
</li>
 <li><p>Centuries follow the same zero through nine rule, so those will usually be numerals (i.e., 20th century, 21st century).</p>
  </li>
<li>
<p>In most numbers of one thousand or more, commas should be used between groups of three digits, counting from the right (32,904 <em>NOT 32904</em>). Exceptions: page numbers, addresses, port numbers, etc.</p>
</li>
<li>
<p>Use numerals for versions (version 5 or v5).</p>
</li>
<li>
<p>Use a numeral if it’s an actual value (e.g., 5% 7″ $6.00).</p>
</li>
<li>
 <p>Always use the symbol % with numerals rather than the spelled out word (percent), and make sure it is closed up to number: 0.05%. Unless the percentage begins a sentence or title/caption, the number should be a numeral with the % symbol.</p>
 </li>
 <li>
<p>Ordinal numbers: Spell out first through ninth, use numerals for 10th and above. No superscript.</p>
</li>
 </ul>
 
 <p>Formatting:</p>
 
 <ul>
 <li>
  <p>Use spaces around inline operators (1 + 1 = 2. <em>NOT 1+1=2</em>).</p>
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
<p>Use multiplication symbol “&times;” for dimensions, not "by" (e.g., "8.5 &times; 11").</p>
</li>
</ul>

<p><a href="#getting_started">back to top</a></p>
</section>








<section data-type="sect2" id="figures_tables_and_examples">
<h2>Figures, Tables, and Examples</h2>

<p>Every formally numbered figure, table, and example should be preceded by a specific in-text reference (for example: see Figure 99-1; Example 1-99 shows; Table 1-1 lists, etc.). Formal figures, tables, and examples should not be introduced with colons or phrases like “in the following figure,” or “as shown in this table.” Though we do support unnumbered informal figures/tables/examples, these should be used only for elements whose contents are not discussed at length or referred back to. Lack of specific in-text references may cause incorrect placement of figures. <strong>See <a href="#cross_references">Cross References</a> above for more detail on including cross references.</strong></p>

<div data-type="tip">
<p>If you are writing or copyediting in Word, figure, table, and example numbers should be numbered as follows: 1-2 (note hyphen [-], not en dash [–] between numbers). The first number is the chapter number. This will be soft-coded in production if not during the writing process.</p>

<p>If you are writing or copyediting in Asciidoc, please refer to <a href="http://docs.atlas.oreilly.com/writing_in_asciidoc.html#XREFS">Writing in AsciiDoc</a> for examples of Asciidoc cross references.</p>

<p>If you are writing or copyediting in DocBook, please reference each figure, table, and example with an &lt;xref&gt;.</p>
</div>

<p>Any word groupings within a figure should have an initial cap on the first word only, with the exception of proper nouns. Generally, we don’t use periods at the end of these word groupings.</p>

<ul>
<li>
<p>Figure 1-1. Figure captions are sentence-cased, with the exception of proper nouns. Code styling is allowed within the figure name or caption. There is no period after figure captions. Exceptions should be discussed with your production editor (e.g., if several long captions require punctuation, we can collaborate on efficient ways to achieve consistency). </p>
</li>
<li>
<p>Table 1-1. Column heads and table titles are sentence-cased, with the exception of proper nouns.  Code styling is allowed within the table name or caption. There is no period after table titles.</p>
</li>
<li>
<p>Example 1-1. Example titles are sentence-cased, with the exception of proper nouns. Code styling is allowed within the example name or caption. There is no period after example titles.</p>
</li>
</ul>

<div data-type="tip">
<p>When working in Word, make sure all table cells are tagged with a cell paragraph tag, even if they’re blank. Any bold “headings” that appear below the very first row of a table should be tagged CellSubheading rather than CellHeading.</p>

<p>Also in Word, all figures must be within a FigureHolder paragraph followed directly by a FigureTitle paragraph.</p>
</div>

<p><a href="#getting_started">back to top</a></p>
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





<div data-type="tip" id="formatting-code-in-word-yDsgtXca">
<h4>Formatting Code in Word</h4>

<p>When copyediting in Word, please do a global search and replace for tabs in code (search for \^t to find them) before submitting files for conversion; tabs <em>will not</em> convert. A general rule of thumb is one tab can be replaced with four spaces (which is the same number that the clean-up macro in the ORA.dot template uses). However, this number can vary, so the most important thing is that copyeditors replace tabs with the numbers of spaces needed to match the indentation and make sure levels of indentation are preserved.</p>
</div>


<p><a href="#getting_started">back to top</a></p>
</section>

<section data-type="sect2" id="#gen_ai">
 <h2>Generative AI</h2>

 <p>Display text generated by artificial intelligence in blockquotes. To separate a prompt from a response, showing who “said” what, use italics:</p> 
 
 <blockquote>
  <p><em>Prompt</em>: Can you write some text?</p>
  <p><em>(insert appropriate technology name here)</em>: Sure can!</p>
 </blockquote>
  
 <p>We want to accurately replicate the back-and-forth between human and AI. Human prompts can be edited very lightly (e.g., punctuation, capitalization), but AI-generated text should be kept verbatim. If AI output is edited for some reason, be sure to still acknowledge the AI's contribution. It must be clear what is AI-generated.</p>

<p><a href="#getting_started">back to top</a></p>
</section>

<section data-type="sect2" id="links">
<h2>Links</h2>

<p>In books produced in Atlas, URLs should be anchored to descriptive text where possible. In ebook versions, the markup will render like this:</p>

<ul>
 <li>
<p>Navigate to the <a href="https://oreilly.com">O'Reilly home page</a> for more information.</p>
 </li>
 </ul>

<p>In the print book, the URL will unfurl in a parenthetical after the linked text:</p>

<ul>
 <li>
<p>Navigate to the O'Reilly home page (<em>https://oreilly.com</em>) for more information.</p>
 </li>
 </ul>
 
<p>Because of this difference in appearance of links in ebooks and print books, long and complex URLs are shortened during production. In the past, we used bit.ly to shorten these URLs, but as of May 2019, all shortened links will be hosted and tracked internally, using the oreil.ly short link. </p>

<div data-type="tip">
<p>We do not anchor URLs to text in books produced in InDesign.</p>
 </div>


<p><a href="#getting_started">back to top</a></p>
</section>





<section data-type="sect2" id="lists">
<h2>Lists</h2>

<p>Typically, we use three types of lists: numbered lists, for ordered steps or chronological items; variable lists, for terms and explanations/definitions; and bulleted lists, for series of items. List items are sentence-capped. List items should be treated as separate items and should not be strung together with punctuation or conjunctions. Unless one item in a list forms a complete sentence, the list's items do not take periods. If one does form a complete sentence, use periods for all items within that list, even fragments.</p> 



<div data-type="tip">
<p><em>NOT O'Reilly style:</em></p>
<ul>
 <li><em>Here is an item, and</em></li>
 <li><em>here is another item; and</em></li>
 <li><em>here is the final item.</em></li>
 </ul>
 
 <p>O'Reilly style:</p>
 <ul>
 <li>Here is an item.</li>
 <li>Here is another item.</li>
 <li>Here is the final item.</li>
 </ul>
 </div>

<p>Following are examples of each type of list.</p>


<section data-type="sect3" id="numbered_list">
<h3>Numbered list</h3>

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




<section data-type="sect3" id="variable_list">
<h3>Variable list</h3>

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





<section data-type="sect3" id="bulleted_list">
<h3>Bulleted list</h3>

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

<p><a href="#getting_started">back to top</a></p>
</section>





<section data-type="sect2" id="punctuation">
<h2>Punctuation</h2>

 <p>For anything not covered in this list, please consult the <em>Chicago Manual of Style</em>, 17th Edition.</p>

<ul>
<li>
<p>Serial comma (this, that, and the other).</p>
</li>
<li>
<p>Commas and periods go inside quotation marks.</p>
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
 <p>Em dashes are always closed (no space around them).</p>
  </li>
 <li>
<p>Ellipses are always closed (no space around them).</p>
  </li>
<li>
<p>For menu items that end with an ellipsis (e.g., "New Folder…"), do not include ellipsis in running text.</p>
</li>
<li>
<p>Lowercase the first letter after a colon: this is how we do it. (Exception: headings.)</p>
</li>
<li>
<p>Parentheses are always roman, even when the contents are italic. For parentheses within parentheses, use square brackets (here’s the first parenthetical [and here’s the second]).</p>
</li>
</ul>
</section>

<p><a href="#getting_started">back to top</a></p>
</section>








<section data-type="sect1" id="miscellaneous">
<h1>Miscellaneous</h1>

<ul>
<li>
<p>Do not use a hyphen between an adverb and the word it modifies. So, “incredibly wide table” rather than “incredibly-wide table.”</p>
</li>
<li>
<p>Close up words with the following prefixes (unless part of a proper noun) “micro,” “meta,” “multi,” “pseudo,” “re,” “non,” “sub,” and "co" (e.g., “multiusers,” “pseudoattribute,” “nonprogrammer,” “subprocess,” "coauthor"). Exceptions are noted in the word list (e.g., "re-create," "re-identification").</p>
</li>
<li>
<p>Avoid using the possessive case for singular nouns ending in “s,” if possible. So, it’s “the Windows Start menu,” not “Windows’s Start menu.”</p>
</li>
<li>
<p>Avoid wholesale changes to the author’s voice—for example, changing the first-person plural (the royal “we”) to the first-person singular or the second person. However, do try to maintain a consistency within sentences or paragraphs, where appropriate.</p>
</li>
 <li>
  <p>We advise using a conversational, user-friendly tone that assumes the reader is intelligent but doesn’t have this particular knowledge yet—like an experienced colleague onboarding a new hire. First-person pronouns, contractions, and active verbs are all encouraged.<strong>(Copyeditors: please check with your production editor if you wish to suggest global changes to tone.)</strong></p>
 </li>
<li>
<p>Companies are always singular. So, for example, “Apple emphasizes the value of aesthetics in its product line. Consequently, it dominates the digital-music market” is correct. “Apple emphasize the value of aesthetics in their product line. They dominate the digital-music market” is <em>not</em>. (Also applies to generic terms “organization,” “team,” “group,” etc.)</p>
</li>
<li>
<p>When referring to software elements or labels, always capitalize words that are capitalized on screen. Put quotes around any multiword element names that are lowercase on screen and would thus be hard to distinguish from the rest of the text (e.g., Click “Don’t select object until rendered” only if necessary.)</p>
</li>
<li>
<p>Use “between” for two items, “among” for three or more. Use “each other” for two, “one another” for three or more.</p>
</li>
 <li>
  <p>Use the American spellings of words when they differ.</p>
  </li>
<li>
<p>Common foreign terms (such as “en masse”) are roman.</p>
</li>
<li>
<p>Introduce unnumbered code blocks with colons.</p>
</li>
 <li>
<p>Do not stack admonitions, sidebars, or headings.</p>
</li>
 <li>
<p>Avoid obscenities and slurs, and obscure if included (grawlix, a two-em dash, etc.)</p>
</li>
</ul>
 
<p><a href="#getting_started">back to top</a></p>
</section>







<section data-type="sect1" id="typography_and_font_conventions">
<h1>Typography and Font Conventions</h1>


<p>The following shows the basic font conventions used in O’Reilly books. Follow these links for detailed instructions for applying these styles in <a href="http://docs.atlas.oreilly.com/writing_in_asciidoc.html#INLINES">Asciidoc</a>, <a href="http://chimera.labs.oreilly.com/books/1234000000058/index.html:">DocBook</a>, and <a href="http://oreillymedia.github.io/production-resources/word/#paragraph-character-styles">Word</a>.</p>


<div data-type="warning">
<p>If you want to use a font convention that is slightly different for one of the following items, check with your editor first—some things can change; some can’t. For example, URLs will not be anything but <em>italic</em>, but you might come up with a different font convention for function names or menu items. If you have a “new” element, please consult with your editor about which font to use.</p>
</div>

<table>

<thead>
<tr>
<th>Type of element</th>
<th>Final result</th>
</tr>
</thead>
<tbody>
<tr>
<td><p>Filenames, file extensions (such as .jpeg), directory paths, and libraries.</p></td>
<td><p><em>Body font italic</em></p></td>
</tr>
<tr>
<td><p>URLs, URIs, email addresses, domain names</p></td>
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
<td><p>Language and script elements: class names, types, namespaces, attributes, methods, variables, keywords, functions, modules, commands, properties, parameters, values, objects, events, XML and HTML tags, and similar elements. Some examples include: <code>System.Web.UI</code>, a <code>while</code> loop, the <code>Socket</code> class, the <code>grep</code> command, and the <code>Obsolete</code> attribute.</p></td>
<td><p><code>Constant width</code></p></td>
</tr>
<tr>
 <td><p>SQL commands (<code>SELECT</code>, <code>INSERT</code>, <code>ALTER</code> <code>TABLE</code>, <code>CREATE</code> <code>INDEX</code>, etc.)</p></td>
 <td><p><code>CONSTANT</code> <code>WIDTH</code> <code>CAPS</code></p></td>
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
<td><p>Placeholders in paths, directories, URLs, or other text that would be italic anyway</p></td>
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

<p><a href="#getting_started">back to top</a></p>
</section>





<section data-type="sect1" id="cover-style">
<h1>O'Reilly Cover Style</h1>
<p>Use <em>Chicago Manual of Style</em>, 17th Edition for anything not mentioned here.</p>

<p>Bulleted lists on the back cover should begin with a capitalized word and end with <em>no</em> punctuation. Even if the list item is a complete sentence, it will not take a period.</p>

<p><a href="#getting_started">back to top</a></p>
</section>




<section data-type="sect1" id="word-list">
<h1>O’Reilly Word List</h1>

<p>Alphabetical Word List: Default spellings</p>

<a href="#wordlist-A">A</a> | <a href="#wordlist-B">B</a> | <a href="#wordlist-C">C</a> | <a href="#wordlist-D">D</a> | <a href="#wordlist-E">E</a> | <a href="#wordlist-F">F</a> | <a href="#wordlist-G">G</a> | <a href="#wordlist-H">H</a> | <a href="#wordlist-I">I</a> | <a href="#wordlist-J">J</a> | <a href="#wordlist-K">K</a> | <a href="#wordlist-L">L</a> | <a href="#wordlist-M">M</a> | <a href="#wordlist-N">N</a> | <a href="#wordlist-O">O</a> | <a href="#wordlist-P">P</a> | <a href="#wordlist-Q">Q</a> | <a href="#wordlist-R">R</a> | <a href="#wordlist-S">S</a> | <a href="#wordlist-T">T</a> | <a href="#wordlist-U">U</a> | <a href="#wordlist-V">V</a> | <a href="#wordlist-W">W</a> | <a href="#wordlist-X">X</a> | <a href="#wordlist-Y">Y</a> | <a href="#wordlist-Z">Z</a> |

<h2 id="wordlist-A">A</h2>

<ul>
 <li>acknowledgments</li>
 <li>ActionScript</li>
 <li>ActiveX control</li>
 <li>Addison-Wesley</li>
 <li>ad hoc</li>
 <li>ADO.NET</li>
 <li>Agile (cap when referring to Agile software development or when used on its own as a noun)</li>
 <li>AI (no need to expand acronym to artificial intelligence)</li>
 <li>Ajax</li>
 <li>a.k.a. or aka (be consistent)</li>
 <li>a.m. or A.M.</li>
 <li>Alt key</li>
 <li>Alt-N</li>
 <li>anonymous FTP</li>
 <li>antipattern</li>
 <li>API (no need to expand acronym to application programming interface)</li>
 <li>appendixes</li>
 <li>applet (or Java applet)</li>
 <li>AppleScript</li>
 <li>AppleScript Studio (ASS)</li>
 <li>ARPAnet</li>
 <li>ASCII</li>
 <li>ASP.NET</li>
 <li>at sign</li>
 <li>autogenerate</li>
 <li>awk</li>
</ul>

<p><a href="#getting_started">back to top</a></p>

<h2 id="wordlist-B">B</h2>

<ul>
<li>backend</li>
 <li>background processes</li>
 <li>backpressure</li>
 <li>backquote</li>
 <li>backslash</li>
 <li>Backspace key</li>
 <li>backtick</li>
 <li>backup (n); back up (v)</li>
 <li>backward</li>
 <li>backward compatible</li>
 <li>bash (avoid starting sentence with this word, but if unavoidable, cap as Bash)</li> 
 <li>BeOS</li>
 <li>Berkeley Software Distribution (BSD)</li>
 <li>Berkeley Unix (older books may have UNIX)</li>
 <li>BHOs</li>
 <li>big data</li>
 <li>Big Design Up Front (BDUF)</li>
 <li>bioinformatics</li>
 <li><strong>Bitcoin (capitalize the concept/network/currency in general; lowercase specific units of currency)</strong></li>
 <li>bitmap</li>
 <li>bit mask</li>
 <li>Bitnet</li>
 <li>bit plane</li>
 <li>bitwise operators</li>
 <li>BlackBerry</li>
 <li>–black-box/white-box testing s/b avoided (alternatives: behavioral/structural testing, closed/open testing, opaque/clear testing)</li>
 <li>–black hat/white hat s/b avoided (alternatives: unethical/ethical, malicious/preventative)</li>
 <li>–blacklist/whitelist s/b avoided (alternatives: block list/allow list, deny/permit, excluded/included)</li>
 <li>Boolean (unless referring to a datatype in code, in which case s/b lowercase)</li>
 <li>Bourne-again shell (bash)</li>
 <li>Bourne shell</li>
 <li>braces or curly braces</li>
 <li>brackets or square brackets</li>
 <li>browsable</li>
 <li>_build-&gt;measure-&gt;learn_ cycle</li>
 <li>built-in (a, n)</li>
 <li>button bar</li>
 </ul>
 
<p><a href="#getting_started">back to top</a></p>

<h2 id="wordlist-C">C</h2>
<ul>
 <li>CacheStorage</li>
 <li>call-to-action</li>
 <li>Caps Lock key</li>
 <li>caret or circumflex</li>
 <li>CAT-5</li>
 <li>CD-ROM</li>
 <li>C language (n)</li>
 <li> C-language (a)</li>
 <li>checkbox</li>
 <li>checkmark</li>
 <li>check-in (n)</li>
 <li>classpath</li>
 <li>CLI (no need to expand acronym to command-line interface)</li>
 <li>click-through (a)</li>
 <li>client/server</li>
 <li>client side (n)</li>
 <li>client-side (a)</li>
 <li><strong>cloud native (n or a)</strong></li>
 <li>co-class</li>
 <li>coauthor</li>
 <li>codebase</li>
 <li>code set</li>
 <li>colorcell</li>
 <li>colormap</li>
 <li>Command key (Mac)</li>
 <li>command line (n)</li>
 <li>command-line (a)</li>
 <li>Common Object Request</li>
 <li>Broker Architecture (CORBA)</li>
 <li>compact disc</li>
 <li>compile time (n)</li>
 <li>compile-time (a)</li>
 <li>CompuServe</li>
 <li>Control key (Mac)</li>
 <li>copyleft</li>
 <li>copyright</li>
 <li>coworker</li>
 <li>CPU (no need to expand to central processing unit)</li>
 <li>–crazy s/b avoided (alternatives: foolish, bizarre, etc.)</li>
 <li>criterion (s), criteria (p)</li>
 <li>cross-reference</li>
 <li>C shell</li>
 <li>&lt;CR&gt;&lt;LF&gt;</li>
 <li>Ctrl key (Windows)</li>
 <li>curly braces or braces</li>
 <li>cybersecurity</li>
 </ul>

<p><a href="#getting_started">back to top</a></p>

<h2 id="wordlist-D">D</h2>
<ul>
 <li>data block</li>
 <li>datacenter or data center (be consistent)</li>
 <li>Data Encryption Standard (DES)</li>
 <li>datafile</li>
 <li>datatype or data type (be consistent)</li>
 <li>data is</li>
 <li>dataset or data set (be consistent)</li>
 <li>DB-9</li>
 <li>Debian GNU/Linux</li>
 <li>decision making (n)</li>
 <li>decision-making (a)</li>
 <li>deep learning (n and a, no hyphen)</li>
 <li>de-identification (hyphenate)</li>
 <li>DevOps</li>
 <li>dial-up (a)</li>
 <li>dial up (v)</li>
 <li>disk</li>
 <li>disk-imaging software</li>
 <li>Delete key</li>
 <li>design time (n)</li>
 <li>design-time (a)</li>
 <li>DNS</li>
 <li>DocBook</li>
 <li>Document Object Model (DOM)</li>
 <li>Domain Name System</li>
 <li>dot</li>
 <li>dot-com</li>
 <li>double-click</li>
 <li>double-precision (a)</li>
 <li>double quotes</li>
 <li>down arrow</li>
 <li>downlevel (a)</li>
 <li>drag-and-drop (n)</li>
 <li>drag and drop (v)</li>
 <li>drop-down (a)</li>
 <li>–dummy s/b avoided (alternatives include: placeholder)</li>
 </ul>

<p><a href="#getting_started">back to top</a></p>

<h2 id="worldlist-E">E</h2>
<ul>
<li>ebook</li>
 <li>ebusiness</li> 
 <li>ecommerce</li> 
 <li>eBay</li>
 <li>Emacs</li>
 <li>email</li>
 <li>empty-element tag</li>
 <li>end-of-file (EOF)</li>
 <li>end-tag</li>
 <li>end user (n); end-user (a)</li>
 <li>Engines of Groth</li>
 <li>Enter key</li>
 <li>equals sign</li>
 <li>ereader</li>
 <li>Escape key (or Esc key)</li>
 <li>et al.</li>
 <li>Ethernet</li>
 <li>exclamation mark</li>
 <li>Exim</li>
        </ul>

<p><a href="#getting_started">back to top</a></p>

<h2 id="wordlist-F">F</h2>
<ul>
 <li>failback</li>
 <li>failover</li>
 <li>fax</li>
 <li>file manager</li>
 <li>filename</li>
 <li><strong>filepath</strong></li>
 <li>file server</li>
 <li>filesystem</li>
 <li>file type</li>
 <li>FireWire</li>
 <li>foreground</li>
 <li>FORTRAN</li>
 <li>Fortran 90</li>
 <li>forward (adv)</li>
 <li>frame type</li>
 <li>FreeBSD</li>
 <li>Free Documentation License (FDL)</li>
 <li>Free Software Foundation (FSF)</li>
 <li>frontend</li>
 <li>_ftp_ (Unix command)</li>
 <li>FTP (protocol)</li>
 <li>FTP site</li>
 <li>full stack (Full Stack in headings), no hyphen, even if adjective</li>
        </ul>
    
<p><a href="#getting_started">back to top</a></p>

<h2 id="wordlist-G">G</h2>
<ul>
 <li>gateway</li>
 <li>Gb (gigabit)</li>
 <li>GB (gigabyte)</li>
 <li>GBps (gigabytes per second)</li>
 <li>GHz</li>
 <li>gid</li>
 <li>GIMP</li>
 <li><strong>Git</strong></li>
 <li><strong>GitHub</strong></li>
 <li>GNOME</li>
 <li>GNU Emacs</li>
 <li>GNU Public License (GPL)</li>
 <li>GNUstep</li>
 <li>Google PageRank</li>
 <li>grayscale</li>
 <li>greater-than sign or &gt;</li>
 <li>greenlight (v)</li>
 <li>GUI, GUIs</li>
 </ul>
       
<p><a href="#getting_started">back to top</a></p>

<h2 id="wordlist-H">H</h2>
<ul>
 <li>handcode</li>
 <li>handoff (n)</li>
 <li>hardcode (v)</li>
 <li>hardcore</li>
 <li>hardcopy</li>
 <li>hard link</li>
 <li>hardware-in-the-loop</li>
 <li>hash sign or sharp sign</li>
 <li>high-level (a)</li>
 <li>home page</li>
 <li>hostname</li>
 <li>hotspot</li>
 <li>HTML</li>
 <li>HTTP</li>
 <li>hypertext</li>
        </ul>
        
<p><a href="#getting_started">back to top</a></p>

<h2 id="wordlist-I">I</h2>
<ul>
 <li>IDs</li>
 <li>IDE</li>
 <li>IndexedDB</li>
 <li>infrastructure as a service (IaaS)</li>
 <li>inline</li>
 <li>inode</li>
 <li>interclient</li>
 <li>internet, the internet</li>
 <li>Internet of Things (IoT)</li>
 <li>internetwork</li>
 <li>intranet</li>
 <li>Intrinsics</li>
 <li>I/O</li>
 <li>IP (Internet Protocol)</li>
 <li>IPsec</li>
 <li>ISO</li>
 <li>ISP</li>
 </ul>
 
<p><a href="#getting_started">back to top</a></p>

<h2 id="wordlist-J">J</h2>

<ul>
 <li>Jabber</li>
 <li>Jabber client</li>
 <li>Jabber server</li>
 <li>Jabber applet</li>
 <li>JAR archive</li>
 <li>JAR file</li>
 <li>JavaScript</li>
 <li>JPEG</li>
 </ul>

<p><a href="#getting_started">back to top</a></p>

<h2 id="wordlist-K">K</h2>
<ul>
 <li>K Desktop Environment (KDE)</li>
 <li>Kb (kilobit)</li>
 <li>KB (kilobyte) (denotes file size or disk space)</li>
 <li>Kbps (kilobits per second)</li>
 <li>Kerberos</li>
 <li>keepalive (n or a)</li>
 <li>keyclick</li>
 <li>keycode</li>
 <li>keymaps</li>
 <li>keypad</li>
 <li>keystroke</li>
 <li>keysym</li>
 <li>keywords</li>
 <li>key performance indicators (KPIs)</li>
 <li>kHz (kilohertz)</li>
 <li>–kill s/b avoided (alternatives: end, exit, cancel)</li>
 <li>Korn shell</li>
 </ul>

<p><a href="#getting_started">back to top</a></p>

<h2 id="wordlist-L">L</h2>
<ul>
 <li>lambda (lc unless referring to a product)</li>
 <li>Lean (capitalize noun or adjective when referring to Lean business methodology)</li>
 <li>local area network or LAN</li>
 <li>left angle bracket or &lt;</li>
 <li>lefthand (a)</li>
 <li>leftmost</li>
 <li>less-than sign or &lt;</li>
 <li>leveled (not levelled)</li>
 <li><strong>life cycle or lifecycle (be consistent)</strong></li>
 <li>line-feed (a)</li>
 <li>line feed (n)</li>
 <li>Linux</li>
 <li>LinuxPPC</li>
 <li>listbox</li>
 <li>logfile</li>
 <li>login, logout, or logon (n or a)</li>
 <li>log in, log out, or log on (v)</li>
 <li>lower-level (a)</li>
 <li>lower-right (a)</li>
 <li>Linux Professional Institute (LPI)</li>
</ul>

<p><a href="#getting_started">back to top</a></p>

<h2 id="wordlist-M">M</h2>
<ul>
 <li><strong>Mac (or MacBook)</strong></li>
 <li>macOS (replaces Mac OS X)</li>
 <li><strong>machine learning (n and a, no hyphen)</strong></li>
 <li>mail-handling (adjective)</li>
 <li>– man hours s/b avoided (alternatives: work hours, employee hours)</li>
 <li>manpage</li>
 <li>markup</li>
 <li>–master/slave (n, a) s/b avoided (alternatives: parent/child, leader/follower, primary/secondary)</li>
 <li>Mb (megabit)</li>
 <li>MB (megabyte)</li>
 <li>MBps (megabytes per second)</li>
 <li>McGraw-Hill</li>
 <li>menu bar</li>
 <li>metacharacter</li>
 <li>Meta key</li>
 <li>Meta-N</li>
 <li>MHz (megahertz)</li>
 <li>mice or mouses (be consistent)</li>
 <li>microservices</li>
 <li>Microsoft Windows</li>
 <li>Microsoft Windows Me</li>
 <li>Microsoft Windows NT</li>
 <li>Microsoft Windows XP</li>
 <li>Microsoft Windows 2000</li>
 <li>–middleman s/b avoided (alternatives: go-between, link, etc.)</li>
 <li>MIDlet</li>
 <li>MKS Toolkit</li>
 <li>model-in-the-loop</li>
 <li>MS-DOS</li>
 <li>multiline </li>
 <li>Multi-Touch (when referring to Apple's trademark)</li>
 <li>My Services</li>
 <li>MySpace</li>
 </ul>
      
<p><a href="#getting_started">back to top</a></p>

<h2 id="wordlist-N">N</h2>
<ul>
 <li>nameserver</li>
 <li>name service</li>
 <li>namespace</li>
 <li>the Net</li>
 <li>.NET</li>
 <li>NetBIOS</li>
 <li>NetBSD</li>
 <li>NetInfo</li>
 <li>newline</li>
 <li>newsgroups</li>
 <li>NeXTSTEP</li>
 <li>NGINX (company), nginx (server)</li>
 <li>NOOP</li>
 <li>nonlocal</li>
 <li>NoSQL</li>
 <li>Novell NetWare</li>
 <li>the <em>New York Times</em></li>
 </ul>

<p><a href="#getting_started">back to top</a></p>

<h2 id="wordlist-O">O</h2>
<ul>
 <li>Objective-C</li>
 <li>object linking and embedding (OLE)</li>
 <li>object-oriented programming (OOP)</li>
 <li>object request broker (ORB)</li>
 <li>OK</li>
 <li>offline</li>
 <li>offload</li>
 <li>online</li>
 <li>on premises (prep. phrase) on-premises (modifier); may be abbreviated to on prem/on-prem</li>
 <li>open source (n or a, rewrite to avoid using in a verb form)</li>
 <li>open source software (OSS)</li>
 <li>OpenBSD</li>
 <li>OpenMotif</li>
 <li>OpenStep</li>
 <li>OpenWindows</li>
 <li>Option key (Mac)</li>
 <li>Oracle7</li>
 <li>Oracle8</li>
 <li>Oracle 8.0</li>
 <li>Oracle 8<em>i</em> (italic “i”)</li>
 <li>Oracle 9<em>i</em> (italic “i”)</li>
 <li>Oracle Parallel Query Option</li>
 <li>O’Reilly Media, Inc.
  <ul>
  <li><strong>O’Reilly’s platform s/b "the O’Reilly platform" or "the O’Reilly learning platform" and then "O’Reilly" on subsequent mentions.</strong></li>
  </ul>
 </li>
 <li>OS/2</li>
 <li>OSA</li>
 <li>OSF/Motif</li>
 <li>OS X</li>
 </ul>

<p><a href="#getting_started">back to top</a></p>

<h2 id="wordlist-P">P</h2>
<ul>
 <li>packet switch networks</li>
 <li>Paint Shop Pro</li>
 <li>pagefile</li>
 <li>page rank (but Google PageRank)</li>
 <li>parentheses (p)</li>
 <li>parenthesis (s)</li>
 <li>Pascal</li>
 <li>pathname</li>
 <li>pattern-matching (a)</li>
 <li>peer-to-peer (or P2P)</li>
 <li>% (not percent)</li>
 <li>performant (Oracle)</li>
 <li>period</li>
 <li>Perl</li>
 <li>Perl DBI</li>
 <li>plain text (n)</li>
 <li>plain-text (a)</li>
 <li>platform as a service (PaaS)</li>
 <li>Plug and Play (PnP)</li>
 <li>plug in (v)</li>
 <li>plug-in (a, n)</li>
 <li>p.m. or P.M.</li>
 <li>Point-to-Point Protocol (PPP)</li>
 <li>pop up (v)</li>
 <li>pop-up (n, a)</li>
 <li>POP-3</li>
 <li>Portable Document Format (PDF)</li>
 <li>Portable Network Graphics (PNG)</li>
 <li>Portable Operating
  <ul>
   <li>System Interface (POSIX)</li>
  </ul>
 </li>
 <li>POSIX-compliant</li>
 <li>Post Office Protocol (POP)</li>
 <li>postprocess</li>
 <li>PostScript</li>
 <li>Prentice Hall</li>
 <li>process ID</li>
 <li>progress bar</li>
 <li>pseudoattribute</li>
 <li>pseudo-tty</li>
 <li>public key (n)</li>
 <li>public-key (a)</li>
 <li>publish/subscribe or pub/sub</li>
 <li>pull-down (a)</li>
 </ul>

<p><a href="#getting_started">back to top</a></p>

<h2 id="wordlist-Q">Q</h2>
<ul>
 <li>qmail</li>
 <li>Qt</li>
 <li>QuarkXPress</li>
 <li>Quartz</li>
 <li>Quartz Extreme</li>
 <li>QuickTime</li>
 <li>quotation marks (spell out first time; it can be “quotes” thereafter)</li>
 </ul>
 
<p><a href="#getting_started">back to top</a></p>

<h2 id="wordlist-R">R</h2>
<ul>
 <li>random-access (a)</li>
 <li>RCS</li>
 <li>read-only (a)</li>
 <li>read/write</li>
 <li>real time (n)</li>
 <li>real-time (a)</li>
 <li>re-create</li>
 <li>Red Hat Linux</li>
 <li>Red Hat Package Manager (RPM)</li>
 <li>redirection</li>
 <li>reference page or manpage</li>
 <li>re-identification (hyphenate)</li>
 <li>remote-access server</li>
 <li>Rendezvous (<em>Mac OS X zeroconf networking</em>)</li>
 <li>Return (key)</li>
 <li>RFC 822</li>
 <li>rich text (n)</li>
 <li>rich-text (a)</li>
 <li>right angle bracket or greater-than sign (&gt;)</li>
 <li>right-click</li>
 <li>righthand (a)</li>
 <li>rmail</li>
 <li><strong>road map or roadmap (be consistent)</strong></li>
 <li>rollback (n); roll back (v)</li>
 <li>rollout (n); roll out (v)</li>
 <li>rootkit</li>
 <li>Rubout key</li>
 <li>rulebase</li>
 <li>ruleset</li>
 <li>runtime (n, a)</li>
 </ul>

<p><a href="#getting_started">back to top</a></p>

<h2 id="wordlist-S">S</h2>
<ul>
 <li>Samba</li>
 <li>saveset</li>
 <li>screen dump</li>
 <li>screenful</li>
 <li>screensaver</li>
 <li>scroll bar</li>
 <li>securelevel (in Linux)</li>
 <li>Secure Shell (SSH)</li>
 <li>Secure Sockets Layer (SSL)</li>
 <li>sed scripts</li>
 <li>server-dependent</li>
 <li>server side (n)</li>
 <li>server-side (a)</li>
 <li>service worker</li>
 <li>servlet</li>
 <li>set up (v)</li>
 <li>setup (n)</li>
 <li>SGML</li>
 <li>sharp sign or hash sign</li>
 <li>shell (lowercase even in shell name: Bourne shell)</li>
 <li>shell scripts</li>
 <li>Shift key</li>
 <li>Simple API for XML (SAX)</li>
 <li>single-precision (a)</li>
 <li>single quote</li>
 <li>site map</li>
 <li>–slave/master (n, a) s/b avoided (alternatives: child/parent, follower/leader, secondary/primary)</li>
 <li>Smalltalk</li>
 <li>SMP (a, n)</li>
 <li>SOAP</li>
 <li>Social Security number (SSN)</li>
 <li>software as a service (SaaS)</li>
 <li>software-in-the-loop</li>
 <li>source code</li>
 <li>space bar</li>
 <li>spam (not SPAM)</li>
 <li>spellcheck</li>
 <li>spellchecker</li>
 <li>split screen</li>
 <li>square brackets or brackets</li>
 <li>standalone</li>
 <li>standard input (stdin)</li>
 <li>standard output (stdout)</li>
 <li>start tag</li>
 <li>startup file</li>
 <li>stateful</li>
 <li>stateless</li>
 <li>status bar</li>
 <li>stylesheet</li>
 <li>subprocess</li>
 <li>SUSE Linux</li>
 <li>swapfile</li>
 <li>swapspace</li>
 <li>sync</li>
 <li>system administrator</li>
 <li>system-wide</li>
 </ul>

<p><a href="#getting_started">back to top</a></p>

<h2 id="wordlist-T">T</h2>
<ul>
 <li>10-baseT</li>
 <li>T1</li>
 <li>t-shirt</li>
 <li>Tab key</li>
 <li>TAR file</li>
 <li>TCP/IP</li>
 <li>Telnet (the protocol)</li>
 <li>telnet (v)</li>
 <li>terabyte</li>
 <li>T<subscript>E</subscript>X</li>
 <li>texinfo</li>
 <li>text box</li>
 <li>text-input mode</li>
 <li>thread pooling (n)</li>
 <li><strong>timeout (in tech/computing contexts)</strong></li>
 <li>time-sharing processes</li>
 <li>timestamp</li>
 <li>time zone</li>
 <li>title bar</li>
 <li>Token Ring</li>
 <li>toolbar</li>
 <li><strong>toolchain</strong></li>
 <li>toolkit</li>
 <li>tool tip</li>
 <li>top-level (a)</li>
 <li>toward</li>
 <li>trade-off</li>
 <li>– tribe s/b avoided (alternatives: company, institution, network, community)</li>
 <li>tweet, retweet, live-tweet v, n (avoid “tweet out”)</li>
 <li>Twitter user (preferred to "tweeter")</li>
 <li>Twitterstorm, tweetstorm</li>
 </ul>

<p><a href="#getting_started">back to top</a></p>

<h2 id="wordlist-U">U</h2>
<ul>
 <li>UI (no need to expand to user interface)</li>
 <li>UK (for United Kingdom)</li>
 <li>Ultrix</li>
 <li>Universal Serial Bus (USB)</li>
 <li>Unix (UNIX in many books, esp. older ones)</li>
 <li>up arrow</li>
 <li>upper- and lowercase</li>
 <li>uppercase</li>
 <li>upper-left corner</li>
 <li>UPSs</li>
 <li>up-to-date</li>
 <li>URLs</li>
 <li>US (for United States)</li>
 <li>Usenet</li>
 <li>user ID (n)</li>
 <li>user-ID (a)</li>
 <li>username</li>
 <li>UX (no need to expand to user experience)</li>
 </ul>

<p><a href="#getting_started">back to top</a></p>

<h2 id="wordlist-V">V</h2>
<ul>
 <li>v2 or version 2</li>
 <li>VAX/VMS</li>
 <li>VB.NET</li>
 <li>versus (avoid vs.)</li>
 <li>vice versa</li>
 <li>VoiceXML</li>
 <li>Visual Basic .NET</li>
 <li>Visual Basic 6 or VB 6</li>
 <li>Visual C++ .NET</li>
 <li>Visual Studio .NET</li>
 <li>VS.NET</li>
 <li>Volume One</li>
 </ul>

<p><a href="#getting_started">back to top</a></p>

<h2 id="wordlist-W">W</h2>
<ul>
 <li>the <em>Wall Street Journal</em></li>
 <li>the web (n)</li>
 <li>web (a)</li>
 <li>web client</li>
 <li>webmaster</li>
 <li>web page</li>
 <li>web server</li>
 <li>web services (unless preceded by a proper noun, as in Microsoft Web Services)</li>
 <li>website</li>
 <li>–white-box testing s/b avoided (alternatives: structural/behavioral testing open/closed testing, clear/opaque testing)</li>
 <li>–white hat/black hat s/b avoided (alternatives: ethical/unethical, preventative/malicious)</li>
 <li>white pages</li>
 <li>–whitelist/blacklist s/b avoided (alternatives: allow list/block list, permit/deny, included/excluded)</li>
 <li>whitepaper (I printed my whitepaper on white paper.)</li>
 <li>whitespace</li>
 <li>wide area network or WAN</li>
 <li>WiFi</li>
 <li>wiki</li>
 <li>wildcard</li>
 <li>Windows 95</li>
 <li>Windows 98</li>
 <li>Windows 2000</li>
 <li>Windows NT</li>
 <li>Windows Vista</li>
 <li>Windows XP</li>
 <li>Wizard (proper noun)</li>
 <li>wizard (a, n)</li>
 <li>workaround</li>
 <li>workbench</li>
 <li>workgroup</li>
 <li>workstation</li>
 <li>World Wide Web (WWW)</li>
 <li>wraparound</li>
 <li>writable</li>
 <li>write-only (a)</li>
 <li>WYSIWYG</li>
 </ul>

<p><a href="#getting_started">back to top</a></p>

<h2 id="wordlist-X">X</h2>
<ul>
 <li>(x,y) (no space)</li>
 <li>x-axis</li>
 <li>Xbox</li>
 <li>X client</li>
 <li><em>x</em> coordinate</li>
 <li>X protocol</li>
 <li>X server</li>
 <li>X Toolkit</li>
 <li>XView</li>
 <li>X Window series</li>
 <li>X Window System</li>
 <li>x86</li>
 <li>xFree86</li>
 <li>XHTML</li>
 <li>XLink</li>
 <li>XML</li>
 <li>XML Query Language (XQuery)</li>
 <li>XML-RPC</li>
 <li>XPath</li>
 <li>XPointer</li>
 <li>XSL</li>
 <li>XSLT</li>
 </ul>

<p><a href="#getting_started">back to top</a></p>

<h2 id="wordlist-Y">Y</h2>
<ul>
 <li>Yahoo!</li>
 <li>y-axis</li>
 <li><em>y</em> coordinate</li>
 </ul>

<p><a href="#getting_started">back to top</a></p>

<h2 id="wordlist-Z">Z</h2>
<ul>
 <li>Zeroconf (short for “Zero Configuration”)</li>
 <li>zeros</li>
 <li>zip code</li>
 <li>zip (v)</li>
 <li>ZIP file</li>
 </ul>

<p><a href="#getting_started">back to top</a></p>
