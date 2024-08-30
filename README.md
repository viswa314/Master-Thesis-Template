# LaTeX Thesis Template

This repository contains a LaTeX template for creating a master thesis or similar academic document. The template is organized into different sections and chapters to help you easily manage and structure your thesis.

## Structure

### Main Files

- **`main.tex`**: The main file that includes all other sections and chapters. Compile this file to generate the final document.
- **`preamble.tex`**: Contains LaTeX packages and configurations. Customize this file to modify the document's appearance and functionality.
- **`thesis.tex`**: Defines the overall structure of the thesis, including the order of sections and chapters.
- **`bibliography.bib`**: A BibTeX file for managing references. Add your references here.

### Chapters

The `chapters` directory contains `.tex` files for each chapter of your thesis:

- **`introduction.tex`**: Introduction chapter.
- **`literature_review.tex`**: Literature review chapter.
- **`methodology.tex`**: Methodology chapter.
- **`results_traditional_cv.tex`**: Results chapter for traditional computer vision.
- **`results_comparison.tex`**: Comparative results chapter.
- **`discussion.tex`**: Discussion of the results.
- **`conclusion.tex`**: Conclusion chapter.
- **`appendices.tex`**: Appendices section.

### Sections

The `sections` directory contains `.tex` files for specific sections:

- **`abstract.tex`**: Abstract of the thesis.
- **`acknowledgments.tex`**: Acknowledgments section.
- **`acronyms.tex`**: List of acronyms used in the thesis.
- **`toc.tex`**: Table of Contents.
- **`lof.tex`**: List of Figures.
- **`lot.tex`**: List of Tables.
- **`ConfidentialityClause.tex`**: Confidentiality clause section.
- **`affidavit.tex`**: Affidavit section.

### Templates

The `templates` directory contains customizable templates for the thesis:

- **`dedication.tex`**: Dedication page.
- **`titlepage.tex`**: Title page layout.

### Figures

The `figures` directory contains images used in the thesis:

- **`Akkodis-Logo-Colour.png`**: Example logo.
- **`thiRGB.jpg`**: Example image.

## Usage

1. **Clone the Repository**: Start by cloning this repository to your local machine.
   ```bash
   git clone https://github.com/viswa314/Master-Thesis-Template
   ```
2. **Edit the Content**: Replace the content in the `.tex` files with your own. You can add new chapters or sections as needed.
3. **Compile the Document**: Use a LaTeX editor or command-line tools like `pdflatex` or `xelatex` to compile `main.tex` and generate the final PDF.
4. **Add References**: Manage your references in the `bibliography.bib` file using BibTeX format.

## Customization

- **Preamble**: Customize the document settings and packages in `preamble.tex`.
- **Title Page**: Modify `titlepage.tex` to change the title page layout.
- **Figures**: Add your images to the `figures` directory and include them in your chapters using the `\includegraphics` command.

## License

This template is open for use. Feel free to modify and distribute it as needed.

## Contact

For any questions or suggestions, please contact me at viswag001@gmail.com
