# ***Topics in Algebraic Attacks on Cryptosystems*** – MSc Thesis

This repository contains the source code for my Master’s thesis titled "Topics in Algebraic Attacks on Cryptosystems". 
The thesis was submitted in partial fulfillment of the requirements for the Master of Science degree in Mathematics at the University of Tehran, Iran, in 2016.

## Usage Note
The thesis is written in Persian/Farsi (فارسی) and is designed to be compiled using XeLaTeX. 
You need to install the required fonts located in the [Fonts](Fonts) folder before compiling the thesis.
To do so, you need to run the following commands:
```bash
sudo cp Fonts/*.ttf /usr/share/fonts/
sudo fc-cache -f -v
```

To compile the thesis, you will need XeTeX and the `xepersian` package.
Use the following commands to compile the thesis:

```bash
xelatex main.tex
bibtex main.aux
xelatex main.tex
xelatex main.tex
```

The compiled thesis is also available in the `pdf` format here: [main.pdf](main.pdf).
Also, Persian students may find the template useful for writing their own thesis. 

Persian-speaking students may find the provided LaTeX template useful for their own thesis projects.

## Contact
For any questions or issues regarding this repository, please feel free to contact me at [hsn.hadipour@gmail.com](hsn.hadipour@gmail.com) or open an issue in this repository.


