# Basic formatting for NxTx


### Use it in your browser
Minified: `<script src="https://nxtxorg.github.io/basic-formatting/build/basic-formatting.min.js"></script>`

Unminified: `<script src="https://nxtxorg.github.io/basic-formatting/build/basic-formatting.js"></script>`


### API
`\text:it(text:string)` Makes the text *italic*

`\text:bf(text:string)` Makes the text __bold__

`\text:tt(text:string)` Makes the text `monospaced`

`\dquote(text:string)` “Double-quotes” the text

`\break` Inserts a line-break with a default height of 1.5 lines (em)

`\pagebreak` Inserts a page-break, which fills the remaining space of the page

`\title(text:string)` Sets the (browser) title for the document

`\ignore(content:string)` Ignores the content passed as arguments. 
Can be used to temporarily exclude some content from rendering