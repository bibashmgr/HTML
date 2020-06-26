> # HTML Head Element:

The HTML `<head>` element is a container for all the head elements: `<title>` , `<style>` , `<meta>` , `<link>` , `<script>` , and `<base>` .

1. `<title>` element:

    - defines a title in the browser tab
    - displays a title for the page in search engine results
    - is required in all HTML documents.

2. `<style>` element :
    
    - define style information for a single HTML page.

3. `<link>` element:

    - used to link to external style sheets.

4. `<script>` element:

    - used to define client-side JavaScripts.

5. `<meta>` element:

    - used to specify which character set is used, page description, keywords, author, and other metadata.
    - Some of its attributes are:

        - Define the character set used:
        ```html
        <meta charset="characterSET">
        ```
        - Define a description of your web page:
        ```html
        <meta name="description" content="detailsOfPage">
        ```
        - Define keywords for search engines:
        ```html
        <meta name="keywords" content="result01, result02, ....">
        ```
        - Define the author of a page:
        ```html
        <meta name="author" content="authorName">
        ```
        - Refresh document every 30 seconds:
        ```html
        <meta http-equiv="refresh" content="timeInSeconds">
        ```
        - Setting The Viewport:
        ```html
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        ```