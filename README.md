# PromKappa 2.0 makes Objective Digital Stains
PromKappa 2.0 is a complete application made in Visual Basic 6.0 (VB6) that generates Objective Digital Stains (aka DNA patterns). The main output of the application consists of a series of images that are saved in the 'chart' (or 'chart_comp') folder and which can be later analysed using different methods. A second output can be the results.htm file which contains a series of measurements for each ODS generated by the application. Note that if you are familiar with python, then VB6 will come natural to you. Also note that once the application is started, the first step will be to load a FASTA file (the 'gene_promoters_complete.fa') using the 'Open promoter file' button. In the PromKappa case the 'gene_promoters_complete.fa' contains a series of gene promoters, as the analysis of gene promoters was the main aim of this application.

![screenshot](https://github.com/Gagniuc/PromKappa-2.0-makes-Objective-Digital-Stains/blob/main/img/Objective%20Digital%20Stains%20-%20aka%20DNA%20patterns%20(1).gif)

The compiled version of PromKappa (PromKappa.exe) will ask for a dependency file called "msvbvm60.dll" and possibly other dependency files. These files are present in the 'bin' folder. The following files are a complete set of dependencies that a regular VB6 app may require:

- msvbvm60.DLL
- VBA6.DLL
- shlwapi.dll
- MSCOMCTL.OCX
- COMDLG32.OCX

However, if you install Visual Basic 6.0 from the Visual Studio 6.0 package, then all dependency files will be present on your system anyway.

# Implementations - other
The Objective Digital Stains are also implemented in two scripting languages, from which an entire customised application can be made.

In Java Script:
https://github.com/Gagniuc/Objective-Digital-Stains

In PHP:
https://github.com/Gagniuc/Objective-Digital-Stains-in-PHP

# Info on ODSs
 Please read more about DNA patterns (aka Objective Digital Stains) here:
 
 Eukaryotic genomes may exhibit up to 10 generic classes of gene promoters: 
 https://bmcgenomics.biomedcentral.com/articles/10.1186/1471-2164-13-512
 
 and 
 
 Gene promoters show chromosome-specificity and reveal chromosome territories in humans:
 https://bmcgenomics.biomedcentral.com/articles/10.1186/1471-2164-14-278
 
 and
 
 Algorithms in Bioinformatics: Theory and Implementation:
 https://www.wiley.com/en-ag/Algorithms+in+Bioinformatics%3A+Theory+and+Implementation-p-9781119697961
 
# Screenshot

![screenshot](https://github.com/Gagniuc/PromKappa-2.0-makes-Objective-Digital-Stains/blob/main/img/PromKappa%202.0%20Objective%20Digital%20Stain%20(1).PNG)

![screenshot](https://github.com/Gagniuc/PromKappa-2.0-makes-Objective-Digital-Stains/blob/main/img/PromKappa%202.0%20Objective%20Digital%20Stain%20(2).PNG)

![screenshot](https://github.com/Gagniuc/PromKappa-2.0-makes-Objective-Digital-Stains/blob/main/img/PromKappa%202.0%20Objective%20Digital%20Stain%20(3).PNG)

![screenshot](https://github.com/Gagniuc/PromKappa-2.0-makes-Objective-Digital-Stains/blob/main/img/PromKappa%202.0%20Objective%20Digital%20Stain%20(4).PNG)
