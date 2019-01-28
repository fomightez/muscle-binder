# muscle-binder

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fomightez/muscle-binder/master?urlpath=lab/tree/index.ipynb)

*tl;dr:*  
Click any `launch binder` badge on this page to run command line-based MUSCLE multiple sequence alignment tool inside your browser.

------

***MUSCLE: Multiple Sequence alignment tool on the command-line.***

This repository is for running Muscle in Jupyter environment provided by [MyBinder.org](https://mybinder.org/).  


At the EMBL-EBI cite is billed as, "Accurate MSA tool, especially good with proteins. Suitable for medium alignments." "MUSCLE stands for MUltiple Sequence Comparison by Log- Expectation. MUSCLE is claimed to achieve both better average accuracy and better speed than ClustalW2 or T-Coffee, depending on the chosen options."

-------

Software
--------

The MUSCLE software will be installed already in each active session launched from this repository. The MUSCLE software is available directly from the author of the software, Robert Edgar,[https://www.drive5.com/muscle/].


**BLAST is a registered trademark of the National Library of Medicine**, see [here](https://blast.ncbi.nlm.nih.gov/Blast.cgi?CMD=Web&PAGE_TYPE=BlastDocs&DOC_TYPE=References).

The BLAST software references are listed [here](https://blast.ncbi.nlm.nih.gov/Blast.cgi?CMD=Web&PAGE_TYPE=BlastDocs&DOC_TYPE=References).

The author of the software, Robert Edgar, requests users please cite:

[MUSCLE: multiple sequence alignment with high accuracy and high throughput. Edgar RC. Nucleic Acids Res. 2004 Mar 19;32(5):1792-7. Print 2004. PMID: 15034147](https://www.ncbi.nlm.nih.gov/pubmed/15034147)


***Clarifying Software Attribution: I, Wayne, am not involved in the MUSCLE software at all. Robert Edgar is the author. See his materials at the links herein. I simply set up this repository to make the software useable on the command line without installation headaches.***



Usage
-----

There is a [MUSCLE aligner web tool](https://www.ebi.ac.uk/Tools/msa/muscle/) served from EMBL-EBI. If it is at all possible, I suggest you use that.

This repository is set up to allow running the command line version of MUSCLE software after pressing the `launch binder` button above or below. The target use case is when you want to process a lot of sequences and you being told by [the available EMBL-EBI MUSCLE web tool](https://www.ebi.ac.uk/Tools/msa/muscle/) that it is limited to "500 sequences or a maximum file size of 1 MB".

In the notebooks that can be launched, I have added some examples illustrating how to use the program. However, as it is command line based if you are familiar with use of such tools, you can launch a `terminal` in the active Jupyter session that will arise after pressing the `launch binder` button above, launch a terminal by pressing the `terminal` icon, upload your sequnece ,and run your alignment using MUSCLE. JupyterLab, which the session defaults to running in, allows drag-and-drop and so you can just drop in your file to the "file" directory panel on the left. (For those of you who prefer the classic notebook style, change the URL in your browser to read `tree` instead of `lab`. In other words, do the reverse of what is describe [here](https://github.com/binder-examples/jupyterlab#start-jupyterlab-after-you-start-your-binder).

MUSCLE is already available as web-served versions of software from EMBL-EBI at the following link:

*Aligning with MUSCELE web-based tools*

* [MUSCLE web tool served from EMBL-EBI](https://www.ebi.ac.uk/Tools/msa/muscle/)
 
License for MUSCLE aligner
----------------------------

The author [states here](http://www.drive5.com/muscle/manual/license.html)  MUSCLE is donated to the public domain.

```
MUSCLE license: public domain
 
MUSCLE is public domain software
The MUSCLE software, including object and source code and documentation, is donated to the public domain. You may therefore freely copy it for any legal purpose you wish. Acknowledgement of authorship and citation in publications is appreciated.
Disclaimer of warranty
THIS SOFTWARE IS PROVIDED "AS IS" WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING WITHOUT LIMITATION IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOS

```

When you run `muscle` on the command line you specifically see:

```
MUSCLE v3.8.1551 by Robert C. Edgar

    http://www.drive5.com/muscle
    This software is donated to the public domain.
    Please cite: Edgar, R.C. Nucleic Acids Res 32(5), 1792-97.
```

Technical Details
-----------------

This repository is set up to make use of the binder service offered by [MyBinder.org](https://mybinder.org/). See their site for more information about Binder.

I borrrowed the 'warning' highlight/introductory text about notebooks at the top of the included notebook from Tim Sherratt's notebook [here](https://github.com/GLAM-Workbench/te-papa-api/blob/master/Exploring-the-Te-Papa-collection-API.ipynb).

Click this button below to begin using MUSCLE:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fomightez/muscle-binder/master?urlpath=lab/tree/index.ipynb)
