## Jsoup

**jsoup** is a Java library that simplifies working with real-world HTML and XML. It offers an easy-to-use API for URL fetching, data parsing, extraction, and manipulation using DOM API methods, CSS, and xpath selectors.



**jsoup** implements the [WHATWG HTML5](https://html.spec.whatwg.org/multipage/syntax.html) specification, and parses HTML to the same DOM as modern browsers.

- scrape and [parse](https://jsoup.org/cookbook/input/parse-document-from-string) HTML from a URL, file, or string
- [find](https://jsoup.org/cookbook/extracting-data/selector-syntax) and extract data, using DOM traversal or CSS selectors
- [manipulate](https://jsoup.org/cookbook/modifying-data/set-html) the HTML elements, attributes, and text
- [clean](https://jsoup.org/cookbook/cleaning-html/safelist-sanitizer) user-submitted content against a safelist, to prevent XSS attacks
- [output](https://jsoup.org/apidocs/org/jsoup/nodes/Element.html#html()) tidy HTML

jsoup is designed to deal with all varieties of HTML found in the wild; from pristine and validating, to invalid tag-soup; jsoup will create a sensible parse tree.