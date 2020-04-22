Microbiome-based forensics with QIIME 2
---------------------------------------

This project is made up of three parts that you will work on in order. In this assignment, you'll be using `QIIME 2 <https://qiime2.org>`_ version 2020.2 to analyze two data sets. The objective of this assignment is to learn a real-world bioinformatics tool based on its documentation (Part 1), apply it to answer a specific question (Part 2), and report your findings (Part 3).  

In **Part 1**, you'll read and run the QIIME 2 `Moving Pictures of the Human Microbiome tutorial <https://docs.qiime2.org/2020.2/tutorials/moving-pictures/>`_, a tutorial that is designed to be a first entry point into the QIIME 2 microbiome bioinformatics platform. This tutorial uses a few thousand sequences from four different body sites collected over a few days from two human subjects. This will familiarize you with running QIIME 2 and interpreting QIIME 2 output. In **Part 2**, you'll adapt the commands from that tutorial to analyze another data set, where human-associated microbial communities were explored for their forensic potential. Specifically, the researchers were interested in determining whether a "microbial fingerprint" left behind on an object could provide information on who touched the object. In **Part 3**, you'll interpret and write up your results from **Part 2** in a three-page report.

Before starting this assignment, you should read `Fierer et al (2010) <http://www.pnas.org/content/early/2010/03/01/1000162107.full.pdf>`_, where this forensic study was initially published. This will help you understand the study. Then, as you work through the assignment, any time you use a QIIME 2 command you should either look up that command in the `QIIME 2 plugin index <https://docs.qiime2.org/2020.2/plugins/available/>`_, or call it with its ``--help`` parameter to understand what it does and how to use it.  

**IMPORTANT**: This assignment includes some steps that will take some time to run (possibly up to 20 minutes). You should avoid starting this assignment close to the deadline - if the server is backlogged because many people are using it, it may take time for your notebook server to be accessible. You are responsible for starting this in a timely manner!

For **Part 1**, you will run analyses and answer questions in the Jupyter Notebook provided `here  <http://nbviewer.jupyter.org/github/gregcaporaso/bio450-qiime2-assignment/blob/master/qiime2-assignment-part1.ipynb>`_. 

For **Part 2**, you will run analyses and answer questions in the Jupyter Notebook provided `here <http://nbviewer.jupyter.org/github/gregcaporaso/bio450-qiime2-assignment/blob/master/qiime2-assignment-part2.ipynb>`_. 

Download each of the notebooks above (click the download icon on the top-right, and save it to your computer). Log into the class Jupyter Notebook server, and create two new folders: one for assignment part 1, and one for assignment part 2. Upload each of the notebooks to it's corresponding folder. (Creating these folders is important - otherwise it'll be very easy to mix up the files from these two parts, which will lead to all sorts of confusing error messages.) Each notebook contains empty cells for you to work in.

For **Part 1**, you'll turn in the notebook containing the commands that you ran. Append your NAU ID to the beginning of the file name. For example, the file I turn in would be named `jgc53-qiime2-assignment-part1.ipynb`.

For **Part 2**, you'll turn in the notebook containing the commands that you ran, as well as a completed `question sheet <>`_, and all `.qzv` files that you reference in your answers in the question sheet. Append your NAU ID to the beginning of each file name. For example, the files I turn in would be named: `jgc53-qiime2-assignment-part2.ipynb`, `jgc53-qiime2-assignment-part2-questions.pdf`, and multiple files with names like `jgc53-*.qzv` (where the `*` is replaced with a descriptive name for each file, such as `jgc53-taxonomy-barplot.qzv`). 

For **Part 3**, you will write a 2.5 to 3 page paper describing your analysis. **Your paper should not be any shorter than 2.5 pages nor any longer than 3 pages. It must have 1.5 line spacing, 0.5" margins, and be written in 12 point Times New Roman font. Figures and tables are included in the page count, though the total space taken by these should be a maximum of one page.**

Write this as if you’re submitting to a journal, so your paper should contain:

* A title and list of authors (just you, in this case). This should be in no more than 14 point font, and follow the margin/spacing requirements listed above.
* An *Introduction* section describing the goals of the study (you can refer to `Fierer et al (2010) <http://www.pnas.org/content/early/2010/03/01/1000162107.full.pdf>`_);
* A *Methods* section containing a brief description of your bioinformatics methods (e.g., what version of QIIME, what commands were used), and how the data was generated (e.g., sequencing platform);
* And a *Results and Conclusions* section describing the results of your analysis. 

You should address several specific questions in your *Results and Conclusions*:

* Which keyboard belonged to each of the human subjects? Back this up with figures and statistics that support your answer. Describe what each of your figures tells you.
* Which bacterial phyla appear to be most useful for matching each individual to their keyboard? Refer to *Taxonomic barplots* to address this.
* Which features were most different in abundance across the subjects? Refer to the *Taxonomic barplots* to address this. Present a table containing the most differentially abundant features and their taxonomy. 
* Which subject had the most features (i.e., the highest microbial community richness) in their skin microbiome, on average? Was the number of features across subjects significantly different? 
