# R Computing in Bengali <img src="https://upload.wikimedia.org/wikipedia/en/4/41/Flag_of_India.svg" width="36" align="center" alt="India">

Welcome to the **R Computing in Bengali** project! This is an open-source initiative aimed at teaching the R programming language to Bengali speakers. By providing essential data science and programming concepts in Bengali, we hope to make learning R more accessible and enjoyable for students and professionals.

## 📖 Contents

The book currently covers the following fundamental topics:
1. **R এর প্রাথমিক ধারণা (Basics of R)** - Installation, console usage, basic math, and variables.
2. **ডেটা স্ট্রাকচার (Data Structures)** - Vectors, Lists, Matrices, and Data Frames.
3. **ডেটা ম্যানিপুলেশন (Data Manipulation)** - Using `dplyr` to filter, select, and mutate data.
4. **ডেটা ভিজ্যুয়ালাইজেশন (Data Visualization)** - Introduction to plotting with `ggplot2`.

## 🚀 How to Build the Book Locally

This book is built using [Quarto](https://quarto.org/). To render the book locally on your own machine, follow these steps:

### Prerequisites
1. **Quarto CLI**: You need to have Quarto installed. Download it from the [Quarto website](https://quarto.org/docs/get-started/).
2. **R and RStudio**: Make sure R is installed on your computer.
3. **Fonts for PDF Rendering**: To generate the PDF version with Bengali text properly formatted, you need to have the **Kalpurush** font installed on your system.

### Rendering Commands

To render the HTML version of the book, run:
```bash
quarto render --to html
```

To render the PDF version of the book, run:
```bash
quarto render --to pdf
```

To preview the book dynamically as you make edits:
```bash
quarto preview
```

## 🤝 Contributing
We welcome contributions! If you would like to add a new chapter, fix typos, or improve existing content, feel free to open a Pull Request.

## 📄 License
This project is open-source and available under the standard MIT License.
