# LATEX

## 1. Introduction

LaTeX is a document preparation system widely used for creating professional technical, scientific, and academic documents. It is based on the TeX typesetting system and uses markup commands to define the structure and formatting of a document.

Unlike traditional word processors, LaTeX focuses on the logical structure of content rather than manual formatting.

It is particularly useful for documents containing mathematical equations, scientific expressions, tables, references, and complex formatting.

## 2. Features of LaTeX

- Produces high-quality and professionally formatted documents.
- Provides excellent support for mathematical equations.
- Supports automatic numbering of sections, figures, tables, and equations.
- Allows cross-referencing between different sections.
- Supports bibliography and citation management.
- Provides consistent formatting throughout a document.
- Supports reusable templates and document classes.
- Can generate PDF documents.

## 3. Basic Structure of a LaTeX Document

A basic LaTeX document consists of two major parts:

1. **Preamble:** Contains the document class, packages, and configuration commands.
2. **Document Body:** Contains the actual content of the document.

### Example

```latex
\documentclass[12pt]{article}

\usepackage{amsmath}

\title{Introduction to LaTeX}
\author{Ankit Gupta}
\date{\today}

\begin{document}

\maketitle

\section{Introduction}

LaTeX is a document preparation system.

\section{Conclusion}

LaTeX is useful for creating technical documents.

\end{document}
```

## 4. Document Classes

The `\documentclass{}` command defines the type of document being created.

Some commonly used document classes are:

| Document Class | Purpose |
|---|---|
| `article` | Articles and assignments |
| `report` | Long reports and academic documents |
| `book` | Books and lengthy publications |
| `letter` | Formal letters |
| `beamer` | Presentations |

Example:

```latex
\documentclass{article}
```

## 5. Important LaTeX Commands

| Command | Purpose |
|---|---|
| `\documentclass{}` | Defines the document type |
| `\usepackage{}` | Includes additional packages |
| `\begin{document}` | Starts the document body |
| `\end{document}` | Ends the document |
| `\title{}` | Defines the document title |
| `\author{}` | Specifies the author |
| `\date{}` | Sets the date |
| `\maketitle` | Generates the title |
| `\section{}` | Creates a section |
| `\subsection{}` | Creates a subsection |
| `\textbf{}` | Makes text bold |
| `\textit{}` | Makes text italic |
| `\underline{}` | Underlines text |
| `\newpage` | Starts a new page |
| `\tableofcontents` | Generates a table of contents |

## 6. Text Formatting

LaTeX provides commands to format text.

Examples:

```latex
\textbf{Bold Text}

\textit{Italic Text}

\underline{Underlined Text}
```

These commands help emphasize important information in a document.

## 7. Lists in LaTeX

LaTeX supports two common types of lists.

### 7.1 Unordered List

The `itemize` environment creates bullet-point lists.

```latex
\begin{itemize}
    \item First Point
    \item Second Point
    \item Third Point
\end{itemize}
```

### 7.2 Ordered List

The `enumerate` environment creates numbered lists.

```latex
\begin{enumerate}
    \item First Step
    \item Second Step
    \item Third Step
\end{enumerate}
```

## 8. Mathematical Expressions

One of the most important advantages of LaTeX is its ability to typeset complex mathematical expressions.

### 8.1 Inline Mathematics

Mathematical expressions can be included within a sentence using `$...$`.

```latex
The equation is $a^2+b^2=c^2$.
```

### 8.2 Display Mathematics

Equations can be displayed separately using `\[...\]`.

```latex
\[
E = mc^2
\]
```

### 8.3 Fractions

```latex
\[
\frac{a+b}{c+d}
\]
```

### 8.4 Square Roots

```latex
\[
\sqrt{x^2+y^2}
\]
```

### 8.5 Summation

```latex
\[
\sum_{i=1}^{n} i
\]
```

### 8.6 Matrices

```latex
\[
\begin{bmatrix}
1 & 2 \\
3 & 4
\end{bmatrix}
\]
```

## 9. Tables in LaTeX

The `tabular` environment is used to create tables.

Example:

```latex
\begin{tabular}{|c|c|}
\hline
Name & Marks \\
\hline
Ankit & 90 \\
Rahul & 85 \\
\hline
\end{tabular}
```

Here:

- `c` represents centre alignment.
- `l` represents left alignment.
- `r` represents right alignment.
- `|` creates vertical borders.
- `\hline` creates horizontal borders.
- `&` separates columns.
- `\\` starts a new row.

## 10. Inserting Images

The `graphicx` package is used to insert images into a LaTeX document.

First, include the package:

```latex
\usepackage{graphicx}
```

Then insert an image:

```latex
\includegraphics[width=0.5\textwidth]{image.png}
```

The image file should be available in the project directory or at the specified path.

## 11. Cross-Referencing

LaTeX provides commands to refer to sections, equations, tables, and figures automatically.

Important commands:

- `\label{}` assigns a reference identifier.
- `\ref{}` retrieves the number of the referenced element.
- `\pageref{}` retrieves its page number.

Example:

```latex
\section{Introduction}
\label{sec:intro}

Refer to Section \ref{sec:intro}.
```

This makes it easier to maintain documents when sections are rearranged.

## 12. Packages in LaTeX

Packages extend the functionality of LaTeX.

Some commonly used packages are:

| Package | Purpose |
|---|---|
| `amsmath` | Advanced mathematical typesetting |
| `graphicx` | Inserting images |
| `geometry` | Adjusting page margins |
| `hyperref` | Creating hyperlinks |
| `xcolor` | Adding colours |
| `booktabs` | Creating professional tables |
| `array` | Advanced table formatting |
| `enumitem` | Customizing lists |

A package is included using:

```latex
\usepackage{amsmath}
```

## 13. Bibliography and Citations

LaTeX supports references and citations, which are important in academic and research documents.

A simple bibliography can be created using:

```latex
\begin{thebibliography}{9}

\bibitem{latex}
Leslie Lamport,
LaTeX: A Document Preparation System.

\end{thebibliography}
```

A citation can then be inserted using:

```latex
\cite{latex}
```

For larger projects, bibliography management tools such as BibTeX can also be used.

## 14. Applications of LaTeX

- Academic assignments and reports.
- Research papers and scientific publications.
- Mathematical and engineering documents.
- Technical documentation.
- Resumes and CVs.
- Books and educational material.

## 15. Advantages of LaTeX

- Produces professional-quality documents.
- Handles complex mathematical expressions efficiently.
- Maintains consistent formatting.
- Supports automatic numbering and referencing.
- Suitable for large and structured documents.
- Provides powerful customization through packages.

## 16. Conclusion

LaTeX is a powerful document preparation system widely used in academic and technical fields. Its ability to handle mathematical expressions, references, tables, and structured content makes it an important tool for students, researchers, and professionals.

Learning LaTeX helps in preparing well-organized, consistent, and professional technical documents.