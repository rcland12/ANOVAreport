%WELCOME TO A STATISTICS REPOSITORY
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%BEFORE YOU READ MORE THIS PROJECT REEQUIRES SAS UNIVERSITY VERSION (ITS FREE)

This project was a homework assignment, but uses a LaTeX package called STATREP.
I really recommend checking this project out on CTAN at https://ctan.org/pkg/statrep?lang=en

My assignment required to do an ANOVA test on some sample data, but also requires Fisher's LSD test and Tukey's LSD test, so using SAS was essential. There are packages similar that ingegrate R as well.
This package is not installed with most TeX program such as MikTeX or TeKmaker. This requires a hard install.
If you are interested in downloading this package, visit the website above, but if you are using the SAS UV, then find the pdf file that explains what to do on this version of SAS.

A few things to note:
-In your TeX file, your \def\SRrootdir{/path...} must be the file path in your virtual machine. I made this mistake.
-Before compiling your SAS file, make sure you run the statrep_tagset.sas file first. This runs formatting for your TeX file.

I also implement the pgfplots package. This package is great! There are so many options available for making beautiful graphs, like the boxplot I made. If your reading this, I am sure you have used pgfplots before.
Hope you enjoy my project. If you have any questions feel free to contact me via my website: rclresume.com
