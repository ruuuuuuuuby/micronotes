# MicroNotes by Ruby

MicroNotes is a lightweight, client-side web application designed for creating printable flashcards and study sheets. It features a continuous-flow pagination engine that automatically distributes text, Markdown, and mathematical equations across a customizable front-and-back grid layout. 

Everything runs locally in your browser within a single file—no build process or backend required.

## Features

* **Continuous Flow Engine**: Automatically calculates text overflow and moves content to the next available grid cell.
* **Print-Optimized**: Generates mirrored pages (Front/Back) perfectly aligned for physical printing on A4, Letter, or A5 paper.
* **Rich Text & Math**: Supports basic Markdown and complex mathematical formulas using KaTeX.
* **Live Preview**: Real-time canvas rendering as you type.
* **Zero Dependencies**: A completely self-contained HTML file utilizing CDNs for external libraries.

## Quick Start

You can use the application directly in your browser:

**[Play with MicroNotes Live](https://[your-username].github.io/[your-repo-name]/)**

To run it locally:
1. Clone this repository or download the `index.html` file.
2. Double-click `index.html` to open it in any modern web browser.

## Formatting Guide

MicroNotes supports text formatting options right in the editor. You can type these manually or use the toolbar.

| Format Type | Syntax | Example |
| :--- | :--- | :--- |
| **Bold Text** | `**text**` | `**Newton's 2nd Law**` |
| **Inline Math** | `$equation$` | `$E = mc^2$` |
| **Block Math** | `$$equation$$` | `$$x = \frac{-b \pm \sqrt{b^2-4ac}}{2a}$$` |
| **Cell Break** | `---` | Forces content to jump to the next cell. |

## Interface Controls

* **Grid Layout**: Customize the number of rows and columns per page.
* **Cell Margin & Font Size**: Adjust spacing and text scale to fit your specific needs.
* **Page Options**: Select your target paper size (A4, Letter, A5) and toggle borders or sequence numbers.
* **Cell Editor**: Click on any filled cell in the preview canvas to edit that specific chunk of text directly.

## Technologies Used

* Vanilla JavaScript, HTML5, and CSS3
* KaTeX (for mathematical rendering)
* html2canvas (for canvas processing)

## License

This project is open-source and available for personal use and modification.
