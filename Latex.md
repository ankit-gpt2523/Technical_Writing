# LATEX

## 1. Introduction

LaTeX is a document preparation system used to create professional technical, scientific, and academic documents. It uses markup commands to define the structure and formatting of documents.

It is especially useful for writing mathematical equations, research papers, assignments, and technical reports.

## 2. Features of LaTeX

- Produces professionally formatted documents.
- Supports complex mathematical equations.
- Provides automatic numbering of sections, figures, and tables.
- Supports references and citations.
- Maintains consistent document formatting.
- Generates high-quality PDF documents.

## 3. Basic Structure of a LaTeX Document

A LaTeX document consists of two main parts:

1. **Preamble:** Contains document class, packages, and settings.
2. **Document Body:** Contains the actual content.

### Example

```latex
\documentclass{article}

\usepackage{amsmath}

\begin{document}

\title{My First Document}
\author{Ankit Gupta}
\maketitle

\section{Introduction}
This is my first LaTeX document.

\end{document}
```

## 4. Important LaTeX Commands

| Command | Purpose |
|---|---|
| `\documentclass{}` | Defines document type |
| `\usepackage{}` | Includes packages |
| `\begin{document}` | Starts the document |
| `\end{document}` | Ends the document |
| `\section{}` | Creates a section |
| `\subsection{}` | Creates a subsection |
| `\textbf{}` | Makes text bold |
| `\textit{}` | Makes text italic |
| `\includegraphics{}` | Inserts an image |
| `\tableofcontents` | Generates a table of contents |

## 5. Lists and Tables

LaTeX provides environments to organize information.

### Unordered List

```latex
\begin{itemize}
    \item First Point
    \item Second Point
\end{itemize}
```

### Ordered List

```latex
\begin{enumerate}
    \item First Step
    \item Second Step
\end{enumerate}
```

### Creating a Table

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

## 6. Mathematical Expressions

One of the major advantages of LaTeX is its support for mathematical expressions.

Examples:

**Inline equation:**

```latex
$a^2+b^2=c^2$
```

**Displayed equation:**

```latex
\[
E = mc^2
\]
```

**Fraction:**

```latex
\[
\frac{a+b}{c+d}
\]
```

## 7. Important LaTeX Packages

Packages extend the functionality of LaTeX.

| Package | Purpose |
|---|---|
| `amsmath` | Mathematical expressions |
| `graphicx` | Inserting images |
| `geometry` | Adjusting page margins |
| `hyperref` | Creating hyperlinks |
| `xcolor` | Adding colours |
| `booktabs` | Professional tables |

Packages are included using the command:

```latex
\usepackage{amsmath}
```

## 8. Applications of LaTeX

- Academic assignments and reports.
- Research papers.
- Scientific and mathematical documents.
- Technical documentation.
- Resumes and CVs.
- Books and educational material.

## 9. Advantages of LaTeX

- Produces high-quality documents.
- Handles complex mathematical equations.
- Provides consistent formatting.
- Supports automatic numbering and referencing.
- Suitable for large and structured documents.

## 10. Conclusion

LaTeX is a powerful document preparation system widely used in academic and technical fields. Its ability to handle mathematical expressions, tables, references, and structured content makes it an important tool for students, researchers, and professionals.