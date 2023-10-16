# count-words explaination

1. **HTML Structure**:
   - The HTML document includes various elements for creating the user interface, including a `<div>` with the id "root" that contains the entire content.
   - It includes a heading (`<h1>`) for the page title, an input box for entering words, a "Count" button to trigger the word count, and a textarea to display the word count results.
2. **CSS Styling**:
   - CSS styles are applied to format and style the user interface elements. This includes setting background colors, margins, font sizes, and border radius to create a visually appealing design.
3. **JavaScript Code**:
   - The JavaScript code is embedded within the HTML document using a `<script>` tag.
   - 
     - It first retrieves the text entered by the user from the input field with the id "para."

     - The array of key-value pairs is sorted in descending order based on word frequency using the `sort()` method.

     - The sorted array is then sliced to limit the output to all entries.

     - Finally, the sorted word count data is displayed in the textarea with the id "output" using `document.getElementById('output').innerHTML`.
4. **User Interaction**:
   - When a user enters words into the input box and clicks the "Count" button, the `countWords()` function is called, and the word count results are displayed in the textarea.
  
   - https://github.com/BalasuryaMCA2023/count-words/assets/139736173/fe467311-ae76-490c-865a-bb6a9d8faa3c
  - ## Future Improvements
  
     That is currently  for only count words  Future Improvements include using the slice method in javascript improve count texts for using Javascript are other languages in the future 
