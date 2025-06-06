To use the them, you just need to put `\usetheme{CITIUS}` at the preamble of the document.
Options:
* `theline`: puts a thin gray line below the frame title. It can be configured to define the width percentage of the line, e.g. `theline=0.9`.
* `thebox`: shows a light gray box behind the logo section at the title page.

Tips & Tricks:
* `\def\toctitle{Outline}` defines a variable with the title of the table of contents slides.
* Set the option `aspectratio=169` in the `documentclass` to force the presentation to be on 16:9.
* Put `\setcounter{framenumber}{0}` to start counting the pages wherever you want.
* Option `plain` in a frame forces to hide all the layout elements.
* Option `noframenumbering` ignores the frame as part of the counting pages.