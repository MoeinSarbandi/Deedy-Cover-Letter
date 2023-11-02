# Justifying Text in Deedy-Cover-Letter

This README explains the changes made to the Deedy-Cover-Letter branch to justify text. It also includes before and after images for reference.

## Changes Made

In the LaTeX code, the following changes were made to justify the text:

```latex
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
% Justifying
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
\usepackage{ragged2e}
\renewcommand{\lettercontent}[1]{\justifying\noindent\fontspec[Path = 
OpenFonts/fonts/raleway/]{Raleway-Medium}\fontsize{11pt}{13pt}
\selectfont {#1 \\}\mbox{}\\ \normalfont}
```

The \justifying command was added to justify the text.

### Before

![Before Image](https://github.com/MoeinSarbandi/Deedy-Cover-Letter/blob/master/before.JPG)

### After

![After Image](https://github.com/MoeinSarbandi/Deedy-Cover-Letter/blob/master/after.JPG)

How to Use
If you want to use this modified code in your Deedy-Cover-Letter, simply replace the relevant section of your LaTeX file with the provided code.

License
This project is open-source and available under the [License Name] license. See the LICENSE file for details.

Author:
Moein Sarbandi

Feel free to contribute to this project.
