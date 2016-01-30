Codegolf IDE
===

A Web editor dedicated to HTML/JS code-golfing

http://codegolf.github.io/codegolfIDE

*Featuring:*

- A code editor with CodeMirror, on the left.
- A real time preview, on the right.
- A character count, in the title
- Dev tools, hidden under the checkbox on the bottom:
  - A custom console.
  - A button to save current code in localStorage.
  - A button to load previous code from localStorage.
  - A button to export (download) your code as index.html.
  - A button to share current code with an URL.
  - A button to minify current JS code using Closure Compiler.
  - A button to pack current JS code using RegPack.
  - A button to minify AND regpack current JS code.
  - Basic RegPack configuration (gain/length/copies/mode).
  
*NB:*

- The custom console responds to console.log() and console.clear(). It is cleared before each refresh of the preview.
- "Current JS code" is extracted from the first &lt;script> tag present in the source code.
- Closure Compiler is called with the parameters "simple optimizations" and "ES6 code".
- Closure Compiler's output is cleaned (line breaks and trailing semicolon are removed).
- Minified and/or packed code is logged in the console.

