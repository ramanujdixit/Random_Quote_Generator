# Random_Quote_Generator

The provided code is an HTML document that creates a web page for a "Notion Random Quote" generator. Here's a breakdown of the code and its functionality:

1. HTML Structure:
   - The document starts with the `<!DOCTYPE html>` declaration, followed by the opening `<html>` tag.
   - The `<head>` section contains metadata, including the page title, character encoding, and viewport settings.
   - Within the `<head>`, there is a link to Google Fonts for three font families.
   - The `<style>` section defines the CSS styles used for the webpage.

2. Body Structure:
   - The `<body>` element has the class `light`, which is used for applying the light color scheme initially.
   - The `<div class="settings">` contains options for shuffling quotes, changing font sizes and styles, and toggling between light and dark modes.
   - The main quote display section is enclosed in `<div class="quote mono">`. It contains a `<blockquote>` element for the quote content and a `<cite>` element for the quote's author.

3. JavaScript:
   - The JavaScript code is enclosed within a `<script>` tag.
   - It uses the `DOMContentLoaded` event to execute the code when the HTML document has finished loading.
   - The code includes event listeners and functions to handle various interactions and settings.
   - The `updateQuote()` function fetches a random quote from the "https://api.quotable.io/random" API and updates the quote display accordingly.
   - The `updateQuoteCustom(f)` function allows fetching quotes from a custom API endpoint specified through the `f` parameter.
   - The `updateStyle()` function retrieves saved settings from local storage and applies them to the webpage.
   - The remaining functions handle font changes, mode changes, and font size adjustments based on user interactions.
   - The `loadQuote()` function determines whether to fetch quotes from the default API or a custom API based on the URL parameter "f".
   - The code also includes event listeners for button clicks and media queries to handle color scheme changes.

Overall, this code creates a webpage that displays random quotes and provides options for customizing the quote's appearance, including font style, size, and light/dark mode. Users can click the shuffle button to fetch a new random quote. this code is cloned from https://github.com/saman/notion-quote/tree/master
