# Professional LaTeX Resume Template

This repository provides a highly customizable LaTeX resume template based on the `res.cls` document class, along with an example resume (`kirkwood-donavin-resume.tex`) demonstrating its usage.

If you appreciate a clean, well-structured, and easily adaptable resume format, this template might be a great starting point for you\!

## Files in this Repository

  * `res.cls`: The custom LaTeX document class file that defines the styling and commands for the resume.
  * `kirkwood-donavin-resume.tex`: An example resume showcasing how to use the `res.cls` file, complete with various sections like Summary, Highlights, Experience, and Education. This document also includes custom commands for formatting, such as `\tagline`, which places a short descriptive phrase under the name.

## Features of the `res.cls` Style

The `res.cls` style offers several features to help you craft a professional resume:

  * **Customizable Header:** Choose between a `centered` name and address layout (default) or a `line` layout where the name is on the left with a horizontal line separating it from the address on the right.
  * **Flexible Section Titles:** Section titles can `overlap` the body text (default) or be placed in a `resmargin` to the left of the body text.
  * **Font Size Options:** Supports `11pt` and `12pt` font sizes in addition to the default `10pt`.
  * **Dedicated Commands:**
      * `\name{text}`: Defines your name.
      * `\tagline{text}`: Defines a professional tagline that appears under your name and before your addresses.
      * `\address{text}`: Defines your address (can be called twice for two addresses).
      * `\section{text}`: Creates left-aligned section titles, with multi-line support.
      * `\employer{text}`, `\title{text}`, `\dates{text}`, `\location{text}`: Commands to declare job-related information for the `position` environment.
      * `\begin{position}...\end{position}`: Environment for detailing job descriptions.
      * `\begin{ncolumn}{n}...\end{ncolumn}`: Creates a tabular environment with `n` equally spaced columns.
  * **Adjustable Dimensions:** Control `sectionwidth`, `sectionskip`, and `resumewidth` for fine-tuning the layout.
  * **Customizable Fonts:** `sectionfont` and `namefont` can be redefined to change the appearance of titles and your name. A `taglinefont` is also included for controlling the tagline's appearance, set to `\small` by default.

## How to Use

1.  **Clone the Repository:**
    ```bash
    git clone https://github.com/YourUsername/your-repo-name.git
    cd your-repo-name
    ```
2.  **Edit `kirkwood-donavin-resume.tex`:**
      * Open `kirkwood-donavin-resume.tex` in your favorite LaTeX editor.
      * Replace the placeholder information with your own details.
      * Make use of the provided commands like `\name{}`, `\tagline{}`, `\address{}`, `\section{}`, and the `position` environment.
      * Experiment with the document class options (e.g., `centered`, `line`, `resmargin`, `overlapped`, `11pt`, `12pt`) by modifying `\documentclass[]` at the top of the `.tex` file.
3.  **Compile with LaTeX:**
    Use a LaTeX compiler (like `pdflatex`) to compile the `.tex` file:
    ```bash
    pdflatex "kirkwood-donavin-resume.tex"
    ```
    This will generate a PDF of your resume.

## Customization

Feel free to open `res.cls` and make further modifications to suit your specific needs. The comments within the `.cls` file provide some guidance on various definitions and settings.

## Contributing

If you find any improvements or issues, feel free to open an issue or submit a pull request\!