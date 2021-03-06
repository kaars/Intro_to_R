# (A Brief) Introduction to R

This tutorial was originally designed for Northwestern University Master of Science in Clinical Investigation (*<https://nucats.northwestern.edu/education-career-development/investigator-resources/msci>*) students to be given over two 1.5 hour sessions on June 27 & 29, 2017. It is presented in an R Markdown document and covers R basics including arithmetic functions, variable assignment, basic data types, importing and working with files in several formats, and very simple exploratory data analysis techniques. In addition to this tutorial, the students were given full access to Data Camp (*<http://www.datacamp.com>*) content to continue learning R and/or Python in a self-paced, online format.

## Getting Started

You will need R and are encouraged to download R Studio to use these exercises.

### Prerequisites

1. Download and install R
	* Go to *<http://ftp.osuosl.org/pub/cran/>*
	* Pick the appropriate version for your computer
	*	* Macs: The most current version is ‘R-3.3.3.pkg’ (for Mavericks, Yosemite). If you have have ‘El Capitan’ or higher, pick ‘R-3.4.0.pkg’.
	*	* PC: Pick the base version
	* After download, install with default settings

2. Download and install R Studio:
	* Go to https://www.rstudio.com/products/rstudio/#Desktop
	* Click on “DOWNLOAD RSTUDIO DESKTOP”
	* Choose the appropriate version for your computer under "Installers for Supported Platforms"
	* After download, install with default settings

If you have trouble with the installation, there is a [video walkthrough](https://campus.datacamp.com/courses/working-with-the-rstudio-ide-part-1/orientation?ex=3) available through Data Camp.

3. Install the 'haven' and 'readxl' libraries.

4. Install the ['rmarkdown' package](https://cran.r-project.org/web/packages/rmarkdown/rmarkdown.pdf) if it is not already.

5. Install the ['knitr' package](https://cran.r-project.org/web/packages/knitr/knitr.pdf).

6. **For Macs**: For _knitr_ to function properly, you will need the [XQuartz](https://www.xquartz.org/) X Window System for OS X.

7. If you do not have a TeX installation on your machine, you will receive a message like the following when you try to use knitr to create a PDF file:

 >No TeX installation detected (TeX is required to create PDF output). You should install a recommended TeX distribution for your platform:  
  Windows: MiKTeX (Complete) - http://miktex.org/2.9/setup
  (NOTE: Be sure to download the Complete rather than Basic installation)  
  Mac OS X: TexLive 2013 (Full) - http://tug.org/mactex/
  (NOTE: Download with Safari rather than Chrome _strongly_ recommended)  
  Linux: Use system package manager  

Follow the instructions for your machine type.

8. Download the **'Data_Files'** folder and place it in the same folder as 'Intro_to_R.Rmd', or change the code within to the proper path.

## References

See _Intro_to_R.Rmd_ for references

## Authors

**Matt Carson** - [Kaars](https://github.com/kaars)

## Acknowledgments

Thanks to Christina Maimone for help with student access to Data Camp.
