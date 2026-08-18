Stage 0: Bash & Bioinformatics Fundamentals

This repository contains my submission for Stage 0 of the HackBio Internship, covering Bash command-line fundamentals and installation of essential bioinformatics software in a Conda environment.

The projects were completed using the Linux terminal in Google Cloud Shell, with Miniconda used for environment and package management.

---

Repository Contents

text
.
  ├── Project1/
  │   └── project1.sh
  ├── Project2/
  │   └── project2.sh
  └── README.md

The exact folder and file names may vary depending on the final repository structure.

---

Project 1: Bash Basic

Objective

The objective of Project 1 was to complete a series of tasks using the Linux command line and basic Bash utilities.

The project covered:

-   Printing information to the terminal
-   Creating and navigating directories
-   Downloading files using wget
-   Moving and deleting files
-   Searching files with grep
-   Redirecting command output to files
-   Extracting information from GenBank files
-   Counting lines
-   Working with file and directory listings
-   Using Bash commands and pipelines

Tasks Completed

1. Print name

Printed my name to the terminal using:

bash
echo "YOURNAME"

2. Create a personal directory

Created a directory named after me.

3. Create and navigate into the biocomputing directory

Created the directory and navigated into it using a single command:

bash
mkdir -p biocomputing && cd biocomputing

4. Download biological sequence files

Downloaded the provided FASTA and GenBank files using wget.

The files were obtained from the HackBio Bash NGS Starters repository.

5. Move the FASTA file

Moved the .fna file into my personal directory.

6. Remove the duplicate GenBank file

Removed the duplicate .gbk file created when the same file was downloaded twice.

7–8. Identify the mutant FASTA sequence

Used grep with case-insensitive searching to determine whether the sequence contained:

-   tata — wild type
-   tatatata — mutant

If the mutant sequence was identified, the matching lines were saved to a separate output file.

9. Count GenBank lines

Counted the number of lines in the GenBank file while excluding the header.

10. Extract sequence length

Used the LOCUS tag in the GenBank file to identify the sequence length.

11. Identify the source organism

Used the SOURCE tag to identify the organism from which the sequence originated.

12. Extract gene names

Used:

bash
grep '/gene='

to identify gene annotations in the GenBank file.

13. Clear the terminal and display command history

Used Bash commands to clear the terminal and display the commands used during the session.

14. List files in the directories

Used ls to inspect the contents of the relevant directories.

---

Project 2: Installing Bioinformatics Software

Objective

The objective of Project 2 was to set up a Conda-based bioinformatics environment and install commonly used bioinformatics software from the Bioconda channel.

Environment Setup

Miniconda was installed and used to manage the bioinformatics environment.

A dedicated Conda environment named:

text
funtools

was created for the project.

The environment was activated before installing the required tools.

Software Installed

The following software was installed:

| Software | Purpose |
| --- | --- |
| Figlet | Display text as ASCII art |
| BWA | Sequence alignment |
| BLAST | Sequence similarity searching |
| SAMtools | Manipulation and analysis of SAM/BAM files |
| BEDTools | Genomic interval operations |
| SPAdes | Genome assembly |
| BCFtools | Variant calling and manipulation of variant files |
| fastp | FASTQ quality control and preprocessing |
| MultiQC | Aggregation and reporting of bioinformatics QC results |

Conda Channels

The following Conda channels were configured:

text
defaults
bioconda
conda-forge

Bioinformatics packages were installed through the Bioconda channel.

Environment

text
Conda environment: funtools
Platform: Linux x8664
Terminal: Google Cloud Shell
Distribution: Miniconda

---

Key Bash and Bioinformatics Skills Demonstrated

Through these projects, I practiced the following command-line skills:

text
mkdir       Directory creation
cd          Directory navigation
mv          Moving and renaming files
cp          Copying files
rm          Removing files
ls          Listing files
pwd         Displaying the current directory
wget        Downloading files
cat         Displaying file contents
grep        Searching text
sed         Editing text streams
sort        Sorting data
df          Checking filesystem usage
du          Checking directory usage
history     Viewing command history
clear       Clearing the terminal

I also practiced:

-   Bash command chaining
-   Output redirection
-   File paths and relative paths
-   Working with FASTA files
-   Working with GenBank files
-   Extracting sequence metadata
-   Conda environment management
-   Bioconda package installation
-   Basic bioinformatics software setup

---

Technologies and Tools

-   Bash
-   Linux
-   Google Cloud Shell
-   Miniconda
-   Conda
-   Bioconda
-   wget
-   grep
-   sed
-   awk
-   SAMtools
-   BWA
-   BLAST
-   BEDTools
-   SPAdes
-   BCFtools
-   fastp
-   MultiQC

---

Acknowledgements

This project was completed as part of the HackBio Internship.

The biological sequence datasets used in Project 1 were provided through the HackBio Bash NGS Starters repository.

---

Author

Praise Sope

Stage 0 — Bash & Bioinformatics Fundamentals
