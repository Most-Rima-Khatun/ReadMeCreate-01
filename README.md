# Formatting Text Spans<br>
<br>
Surround text with a single asterisk or underscore for emphasis (italics)<br>
<br>
she thought in *italics*<br>
<br>
she thought in _italics_<br>
<br>
Surround text with double asterisks or underscores to make it bold<br>
<br>
Boldness and emphasis can be nested for bold-italic text<br>
<br>
**Boldness has *genius*, _power_, and *magic*** in it<br>
<br>
Surround text with one of more backticks to make it code<br>
<br>

Should I use `pandas` or `dplyr`?<br>
<br>
Surround text with one of more tildes to strike it through<br>
<br>
Every strike brings me ~closer to~ the next home run<br>
Surround text with a single dollar sign to make it a LaTeX equation<br>
<br>

$e^{\pi i} + 1 = 0$<br>
<br>
# Formatting Text Blocks<br>
Start a line with greater than then space to make it a quote<br>

> Without data you're just<br>

> another person with an opinion<br>
<br>
Surround a block of text with lines starting with three backticks to make it a code block<br>

```

x = (1 + sqrt(5)) / 2

```
Optionally specify the language of the code after the backticks to highlight syntax<br>

``` python

x = (1 + sqrt(5)) / 2

```
# Lists<br>
Start lines with hyphens, plus or asterisks then a space to make an unordered list<br>

(Be consistent about which punctuation is used)<br>

- bread<br>

- milk<br>

- eggs<br>

- teabags<br>
<br>
Start lines with a number followed by a period then a space to make an ordered list.<br>

(Numbering is automatic and follows from the first element.)<br>

3. three<br>

1. four<br>

1. five<br>

1. six<br>
<br>
Inside a list, include square brackets filled with a space or character (conventionally 'x') to create a checklist<br>

- [x] bread<br>

- [ ] milk<br>

- [x] eggs<br>

- [ ] teabags<br>
<br>
Use space indentation to nest lists<br>

* The Lord of the Rings<br>

1. The Fellowship of the Ring<br>

1. The Ring Sets Out<br>

1. The Ring Goes South<br>

1. The Two Towers<br>

1. The Treason of Isengard<br>

1. The Ring Goes East<br>

1. The Return of the King<br>

1. The War of the Ring<br>

1. The End of the Third Age<br>
<br>
# Headings<br>
Start a line with one to six hashes then a space to make it a heading<br>

# Constitution of the United States<br>

## Articles<br>

### Article I: The Legislative Branch<br>

#### Section 1: The Legislature<br>
<br>
For level one headings, you can also follow the line with a line of equals signs<br>

Constitution of the United States<br>

=================================<br>
<br>
For level two headings, you can also follow the line with a line of hyphens<br>

Articles<br>

--------<br>
<br>
# Links, Images and Footnotes<br>
Use square brackets containing link text followed by parentheses containing a URL to include a hyperlink<br>

[Build data and AI skills with DataCamp](https://www.datacamp.com)<br>
<br>
Use square brackets containing link text followed by a reference number, then (usually at the bottom of the doc) square brackets containing the reference number followed by a colon then a space then a URL to include reference-style hyperlinks.<br>

[Listen to DataFramed][1]<br>

[1]: https://www.datacamp.com/podcast<br>
<br>
Use an exclamation mark followed by square brackets containing alt text followed by parentheses containing a URL or path to a file to include an image<br>

![The Markdown logo](Markdown-mark.png)<br>
<br>
Use square brackets containing a caret then a number (both within the content and at the foot of the page) to create a footnote.<br>

Literature is the original Internet – every footnote, every citation, every allusion is essentially a hyperlink to another text, to another mind.[^1]<br>

[^1]: Attributed to Maria Popova<br>
<br>
# Tables<br>
Use pipes to delimit columns in a table. Use hyphens to separate the header from the content. Use a colon to the left or right of those hyphens to indicate column alignment.<br>

| Sepal Length| Sepal Width| Petal Length| Petal Width|      Species |<br>

|-----------------:|----------------:|-----------------:|---------------:|:---------------|<br>

|                 5.1|                3.3|                  1.7|              0.5|        setosa |<br>

|                4.8|                3.0|                  1.4|              0.1|        setosa |<br>

|                 6.1|                2.8|                 4.7|               1.2|   versicolor |<br>

|                 6.1|                3.0|                 4.6|               1.4|  versicolor |<br>
<br>
# Breaks<br>
Have a line with only three or more hyphens, asterisks, or underscores (plus optional spaces) to include a horizontal rule.<br>

---<br>

***<br>

___<br>
<br>
By default, text on consecutive lines flows as a single line.<br>

Writing one line,<br>

then another without a break,<br>

results in text flowing as a single line.<br>
<br>
Two spaces at the end of a line result in a line break.<br>

Appending two spaces to the end of the line¶¶<br>

creates a line break.<br>
<br>
Blank lines create a new paragraph.<br>

Including a blank line in between two lines of text<br>

creates a paragraph break.<br>
<br>
