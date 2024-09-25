# James McDonald

## Project Overview
This is a LaTeX book project dedicated to documenting the genealogy and descendants of James McDonald, his wife Mary Welch, and their son Alexander. They were among the British 1820 Settlers to South Africa.

## Purpose
The purpose of this book is to provide a comprehensive and detailed account of the McDonald family's lineage, tracing their roots and documenting the lives and contributions of their descendants.

## Structure
The book is organized into several chapters, each focusing on different generations and branches of the McDonald family tree. It includes historical context, personal anecdotes, and genealogical charts.

## Getting Started
To compile the book, you will need a LaTeX distribution installed on your computer. Recommended distributions include TeX Live for Linux and Mac, and MiKTeX for Windows.


### Installing TeX Live on macOS

To install TeX Live on macOS, follow these steps:

1. **Download MacTeX**:
   Visit the [MacTeX](https://tug.org/mactex/) website and download the latest MacTeX package. MacTeX includes TeX Live along with additional tools and editors tailored for macOS. 

2. **Install MacTeX**:
   Open the downloaded `.pkg` file and follow the on-screen instructions to complete the installation. This process will install TeX Live and other useful applications like TeXShop and BibDesk.

3. **Verify Installation**:
   Open the Terminal application and type `tex --version` to verify that TeX Live has been installed correctly. You should see output indicating the version of TeX Live installed.



### Compilation Instructions
1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Run the following command to compile the book:
   ```bash
   pdflatex main.tex
   bibtex main
   pdflatex main.tex
   pdflatex main.tex
   ```
