# Search Tips

## Getting Started wit​​​​h Search  

To search for a document, type a few descriptive words in the search box and press the **Enter** key or click the search button. A results page appears with a list of documents and web pages that are related to your search terms, with the most relevant search results appearing at the top of the page.

By default, only pages that include all of your search terms are returned. So to broaden or restrict the search include fewer or more terms. You do not need to include "and" between the terms. For example, to search for engineering product specification documents, type the following: "engineering product specifications."

The search appliance uses sophisticated text-matching techniques to find pages that are both important and relevant to your search. For instance, the search appliance analyzes not only the candidate page, but also the pages that link to it, too.

The search appliance also prefers pages in which your query terms are near each other. Every search result lists one or more snippets, or excerpts from the document, to display the search terms in context. In the snippet, your search terms are displayed in bold text so that you can quickly determine if that result is from a page or document you want to visit.

*Note**:*** *Encrypted, viewable PDF documents are converted to HTML for indexing, but the HTML is not displayed.*

 **Spelli​​​​n​​g  
**For searches in some languages, a single spelling suggestion is returned with the results for queries where the spell checker has detected a possible spelling mistake. The spell checker supports the following languages by default:

  - U.S. English
  - French
  - German
  - Italian
  - Brazilian Portuguese
  - Spanish

The spell checker feature is context sensitive.

Your browser's language setting affects how the search appliance handles spelling corrections.

  - If the browser language is English, Portuguese, French, Italian, German, or Spanish, the search appliance returns spelling corrections.
  - If the browser language is Japanese, traditional Chinese, Korean, or simplified Chinese, the search appliance returns English spelling corrections.
  - If the browser language is any other language, the search appliance does not return spelling corrections.

For information about how to change your browser's language setting, read the help system for the browser.

 **Capitalization  
**The search appliance searches are not case-sensitive. All letters, regardless of how you enter them, are handled as lower-case. For example, searches for "george washington," "George Washington," and "George washington" return the same results.

 **Common Wo​​​rds  
**Because they tend to slow down your search without improving the results, the search appliance ignores some terms, including:

  - Common words and characters, such as "where" and "how," when they are used in conjunction with other search term. 
    
    For example, if you search for "who," the search appliance does not ignore it. The search appliance returns results for "who." However, if you search for "Pat who," the search appliance does ignore "who" and only returns results for "Pat."

  - Certain single digits and single letters

If a common word is essential to getting the results you want, you can include it by putting a plus ("+") sign in front of it. Include a space before the "+" sign, but not after it. For example, to search for documents about Star Wars I, type the following: ="Star Wars +I".

Alternatively, you can enclose a series of words with quotation marks and do a [phrase search](#phrase_search).

 **Date S​​ort  
**By default, search results are sorted by relevance, with the most relevant result appearing at the top of the page.

If you want to sort the documents by date instead, click the Sort by Date link. The most recent document appears at the top of the page and the date of each file is returned in the results. Results that do not contain dates are displayed at the end and are sorted by relevance.

 **Numbers  
**When you search for numbers, do not use exponential numbers, such as "1e10," or negative integers, such as "-12."

Numbers that are separated by commas are treated as separate figures, not fractional numbers; that is, the comma is treated as a term separator, not a decimal separator. For example, if you type "3,75," the search query is treated as a search for two separate terms, "3" and "75," not the decimal fraction, "three and three quarters."

Commas that separate every three digits are ignored and are not necessary. For example, both "10,000" and "10000" are treated alike.

-----

## Widening Your Search

You can expand your search by using the `OR` operator. To retrieve pages that include either word A or word B, use an upper-case `OR` between terms. For example, to search for an office in either London or Paris, type the following: "office london OR paris". ​

-----

## Refining Your Search

Since the search appliance returns only web pages that contain all of the words in your query, refining or narrowing your search is as simple as adding more words to the search terms you have already entered.  
  
The refined query returns a subset of the pages that were returned by your original broad query. If that does not get the results that you want, you can try to exclude words, search for exact phrases, or restrict the search to a range of numbers. These techniques are described in the following subsections.

**  
**

**Word Exclusion**

If your search term has more than one meaning, you can focus your search by adding a minus sign ("-") in front of words related to the meaning you want to avoid. Make sure you include a space before the minus sign. You can daisy chain a list of words you want to exclude.

For example, to search for the planet Saturn and exclude search results about the car company or Roman god, type the following query: "Saturn -car -god"

The search appliance returns pages about Saturn that do not contain the word "car" or "god."

 **Phrase Searches  
**Phrase searches are useful when you are searching for famous sayings or specific names. You can search for an exact phrase or name in the following ways:

  - By enclosing the phrase in quotation marks. The search appliance only returns documents that include the exact phrase you entered.
  - By using phrase connectors — such as hyphens, slashes, periods, equal signs, and apostrophesv — in between every word of your search query.

Phrase connectors and quotation marks join your search words as a single unit. For example, if you type the following query, the search appliance treats it as a phrase search even though the search words are not enclosed in quotation marks: "father-in-law"

****  **Range Searches  
**You can confine your search query within a certain range. You can set ranges for dates, weights, prices, meta tags, and so on. The following subsections describe ways you can refine your searches with ranges.​

 **Number Ranges  
**To search for documents or items that contain numbers within a range, type your search term and the range of numbers separated by two periods (".."). You can set ranges for weights ("250..500 g carbon fork"), dimensions ("90..100 mm stem"), years ("tour de france 2000..2006"), prices in dollar currencies only ("bike lights $10..$30"), and so on. Be sure to specify a unit of measurement or some other indicator of what the number range represents.

For example, to search for pencils that costs between $1.50 and $2.50, type the following: "pencils $1.50..$2.50".

Each number in the range should not include more than six significant digits. For example, if you were to type the search query, "1..1234567 ton truck," only the first six significant digits in the "1234567" would be included in the range search; that is, it is as though you have just typed, "1..1234560 ton truck."

 **Date Ranges  
**You can search for documents that contain dates that fall within a time frame. To use date range search, type all of the following:

  - The search term
  - The `daterange:` operator
  - The start date
  - The range separator (which is two periods if you are using a YYYY-MM-DD format or a hyphen if you are using a Julian format)
  - The end date

Do not add a space between the search operator and the date range. The dates could be in either of the following formats:

  - The YYYY-MM-DD (ISO 8601) format. Date ranges using this format should be separated by two periods ("..").
  - The Julian format. The Julian date is calculated by the number of days since January 1, 4713 BC. For example, the Julian date for August 1, 2001 is 2452122. Date ranges in this format should be separated by a hyphen ("-").

For example, to search for a document about Harry Potter that was modified within a specific two-year period, type the following: "Harry Potter daterange:2004-01-13..2006-01-13".

The earliest date that you can use in your date range search is January 1, 1900; and the latest date, June 6, 2079.

 **Metadata and Meta Tag Ranges  
**You can search only for documents that include metadata or meta tags that contain numbers within the range you specified. To use metadata range search, type all of the following:

  - The search term
  - The `inmeta:` operator
  - The name of metadata or meta tag
  - The range of numbers separated by two periods ("..")

For accurate date range searches with `inmeta`, the meta tag content must contain only the date and no other data. Suppose your documents have metadata called "modified" that contains the last modified dates of the documents. To search for a document about risks that was created sometime in 2006, you could type the following: "risk inmeta:modified:2006-01-01..2006-12-31".

You can use the `inmeta` operator beyond just searching for documents with metadata that includes a range of dates or numbers. To learn more about `inmeta`, see the Search Protocol Reference on the [Google Search Appliance help center](https://support.google.com/gsa/). ​

 **Advanced Search Operators  
**The search appliance supports several advanced operators, which are query words that restricts your search to a smaller set of documents. When you enter your search query, do not add a space between the search operator and the search terms.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<tbody>
<tr class="odd">
<td><strong>Search Operator</strong></td>
<td><strong>Description</strong></td>
<td><strong>Example</strong></td>
</tr>
<tr class="even">
<td><strong>allinanchor:<span id="allinanchor"></span></strong></td>
<td><p>Restricts the search to pages that contain all the search terms in the anchor text of the page. The following example shows an anchor tag:</p>
<p>&lt;a href="http://foo.com"&gt;Go Foo&lt;/a&gt;</p>
<p>allinanchor: evaluates the text between &gt; and &lt;/a&gt;. allinanchor: evaluates only &lt;a href anchor tags. It does not evaluate &lt;a name anchor tags.</p>
<p>An anchor is a marker inserted at a specific section of a page. It lets the writer of the document create links to these anchors, which quickly take the reader to the specified section. The table of contents at the top of this document, for example, uses hyperlinks to anchors embedded throughout this document.</p>
<p>Do not include any other search operators with the <code>allinanchor:</code> operator.</p></td>
<td><p>Typing <code>allinanchor:cheap books</code> in the search box returns only pages that have anchor text that include the words "cheap" and "books" between &gt; and &lt;/a&gt;.</p></td>
</tr>
<tr class="odd">
<td><strong>allintitle: <span id="allintitle"></span></strong></td>
<td><p>Restricts the search to documents whose HTML title contains all the search terms.</p>
<p>Also see the <a href="#intitle">intitle: search operator</a>.</p></td>
<td><p>Typing <code>allintitle:google search </code>in the search box returns only documents that have both "google" and "search" in the HTML title.</p></td>
</tr>
<tr class="even">
<td><strong>allintext:</strong><span id="allintext"></span></td>
<td><p>Restricts the search to documents whose titles or body text contains the search terms. The search appliance does not search for the query words in the metadata, anchors, or urls.</p>
<p>Also see the <a href="#intext">intext: search operator</a>.</p></td>
<td>Typing allintext:googlesearch in the search box returns only documents that have both "google" and "search" in the title or body text of the document.</td>
</tr>
<tr class="odd">
<td><strong>allinurl:<span id="allinurl"></span></strong></td>
<td><p>Restricts the search to documents whose URL contains the search terms. The search operator does not require the query words to be adjacent to each other in the document, nor does it require the words to appear in a particular order in the document.</p>
<p>The search operator works on words in the URL, not URL components such as punctuation. Slashes ("/"), for example, are ignored.</p>
<p>Also see the <a href="#inurl">inurl: search operator</a>.</p></td>
<td><p>Typing <code>allinurl:google search</code> in the search box returns only documents that have both "google" and "search" in the URL.</p>
<p>Typing <code>allinurl:google/search</code> in the search box returns the same documents as the previous example. The slash in the search term is altogether ignored.</p></td>
</tr>
<tr class="even">
<td><strong>cache:<span id="cache"></span></strong></td>
<td><p>The search engine keeps the text of the many documents it crawls available in "cache." A cached version of a web page can be retrieved if the original page is unavailable, such as when the page's server is down. The cached page appears exactly as it looked when the crawler last crawled it, but it includes a message (at the top of the page) to indicate that it's a cached version of the page.</p>
<p>If you include search words in addition to the web address in your query, those search words will be highlighted within the cached document.</p></td>
<td><p>Typing <code>cache:www.google.com</code> in the search box returns the cached version of Google's homepage.</p>
<p>Typing <code>cache:www.google.com press releases</code> in the search box returns the cached content with the words "press" and "releases" highlighted.</p></td>
</tr>
<tr class="odd">
<td><strong>daterange:<span id="daterange"></span></strong></td>
<td>Restrict search to documents that contain dates that fall within a time frame, or before or after a specified date. You can search any dates from 1900-01-01 to 2079-06-06. The dates can be in any format except Julian format, which is considered a number range search. When specifying dates in ISO 8601 format (YYYY-MM-DD), separate date ranges by two periods (<code>..</code>).</td>
<td><p>Typing<code> election daterange:2004-01-13..2006-01-13</code><code> </code>in the search box returns results for the search term "election" whose dates fall within the specified time range.</p></td>
</tr>
<tr class="even">
<td><strong>filetype:<strong><span id="filetype"></span></strong></strong></td>
<td>Restricts the search to specific file types such as Excel spreadsheets, PDF files, or Word documents. Type the <code>filetype:</code> operator followed by the file extension.</td>
<td>Typing <code>cars filetype:pdf</code> in the search box returns only PDF files about cars.</td>
</tr>
<tr class="odd">
<td><strong>info: <span id="info"></span></strong></td>
<td><p>Returns the following information for that particular URL:</p>
<ul>
<li>The cache of the page</li>
<li>Web sites that are similar to the page</li>
<li>Web pages that have hyperlinks to the page</li>
<li>Web pages that are hyperlinked in that page</li>
<li>Web pages that contain the URL in its body text</li>
</ul></td>
<td><p>Typing <code>info:www.google.com</code> in the search box returns the following information about the Google home page:</p>
<ul>
<li>The cache of www.google.com</li>
<li>Web sites that are similar to www.google.com</li>
<li>Web pages that have hyperlinks to www.google.com</li>
<li>Web pages that are hyperlinked in www.google.com</li>
<li>Web pages that contain the www.google.com in its body text</li>
</ul></td>
</tr>
<tr class="even">
<td><strong>inmeta:<span id="inmeta"></span></strong></td>
<td>You can filter results by meta tags and their values using <code>inmeta</code>. Used with the operators <code>~</code> or <code>=</code>, <code>inmeta</code> restricts results to required or partial meta tag values in the same way as the <code>requiredfields</code> and <code>partialfields</code> search parameters.</td>
<td><p>Typing <code>inmeta:department=Human Resources</code><code> </code>returns documents where the meta tag includes <code>department=Human Resources</code>.</p></td>
</tr>
<tr class="odd">
<td><strong>intext:<span id="intext"></span></strong></td>
<td><p>Restricts the search to documents that contain the search word in the titles or body text of the documents. The search appliance does not search for the query word in the metadata, anchors, or urls.</p>
<p>Putting intext: in front of every word in your query is equivalent to putting <a href="#allintext">allintext:</a> at the front of your query.</p></td>
<td><p>Typing intext:google returns documents that mention the word "google" in their title or body text.</p>
<p>Typing intext:google intext:search in the search box is the same as typing allintext: google search.</p></td>
</tr>
<tr class="even">
<td><strong>intitle:<span id="intitle"></span></strong></td>
<td><p>Restricts the search to documents that contain the search word in the HTML title.</p>
<p>Putting <code>intitle:</code> in front of every word in your query is equivalent to putting <code>                       allintitle:</code> at the front of your query.</p></td>
<td><p>Typing <code>intitle:google search</code> returns documents that mention the word "google" in their HTML title, and mention the word "search" in the title, body text, anchor, or anywhere else in the document.</p>
<p>Typing <code>intitle:google intitle:search</code> in the search box is the same as <code>typing allintitle:google search</code>.</p></td>
</tr>
<tr class="odd">
<td><strong>inurl:<span id="inurl"></span></strong></td>
<td><p>Restricts the search to documents that contain the search word in the URL.This operator works on words, not URL components such as punctuation. Slashes ("/"), for example, are ignored.</p>
<p>Putting the <code>inurl: </code> operator in front of every word in your query is equivalent to putting <code>                       allinurl:</code> at the front of your query.</p></td>
<td><p>Typing <code>inurl:google search</code> in the search box returns documents that mention the word "google" in their URL and mention the word "search" in the URL, body text, title, or anywhere else in the document.</p>
<p>Typing <code>inurl:google/search</code> in the search box returns the same documents as the previous example. The slash in the search term is altogether ignored.</p>
<p>Typing <code>google inurl:google inurl:search</code> in the search box returns documents that contain both "google" and "search" in the URL. It returns the same documents as the search query <code>allinurl:google search</code>.</p></td>
</tr>
<tr class="even">
<td><strong>link:<span id="link"></span></strong></td>
<td><p>Restricts the search to all pages that link to the web site in the query.</p>
<p>No other search term can be appended to this search operator and the specified web site.</p></td>
<td>Typing <code>link:www.berkeley.edu</code> in the search box returns all the pages that link to that page.</td>
</tr>
<tr class="odd">
<td><strong>site: <span id="site"></span></strong></td>
<td><p>Restricts the search to documents in a web site. If you do not specify the web site and just type the generic top-level domain, such as .com, .edu, or .org, the search engine returns all documents in the generic top-level domain.</p>
<p>The <code>site:</code> operator lets you extend the search restriction down to directories.</p></td>
<td><p>Typing <code>help site:www.google.com </code> in the search box returns pages about help or user documentation within www.google.com.</p>
<p>Typing <code>help site:com </code> in the search box finds pages about help or user documentation within all web sites that end in <code>.com</code>.</p>
<p>Typing <code>site:www.google.com/enterprise/</code> restricts the search to everything at the enterprise directory level. If the trailing slash is omitted, as in <code>www.google.com/enterprise</code>, all subdirectories are searched.</p></td>
</tr>
<tr class="even">
<td><strong>wildcard:</strong><span id="wildcard"></span></td>
<td>The wildcard: operator enables you to search by word pattern rather than the exact spelling of a term. The search appliance supports two wildcard operators:
<ul>
<li>*--Matches zero or more characters</li>
<li>?--Matches exactly 1 character</li>
</ul>
<p>A wildcard query term must satisfy at least one of the following conditions:</p>
<ul>
<li>A sequence of at least 2 characters at the start of a word</li>
<li>A sequence of at least 2 characters at the end of a word</li>
<li>A sequence of at least 3 characters anywhere in the word</li>
</ul></td>
<td><p>Typing <code>wildcard:go*</code> matches any words that begin with the letters "go".</p>
<p>Typing <code>wildcard:g?</code> matches any single character that follows the letter "g".</p>
<p>Typing <code>wildcard:*le</code> matches any words that end with the letters "le".</p>
<p>Typing <code>wildcard:*ear*</code> matches any words that contain the letter sequence "ear" anywhere in the word.</p>
<p>​ </p></td>
</tr>
</tbody>
</table>
