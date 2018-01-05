

The Tripal Transcriptome table creates a block with a sortable table of transcriptomes.

This module is not designed for use outside of the Hardwood Genomics Project.  You are welcome to use it, but administrative pages for customizing content are not available.  It's a very simple module though: to change the descriptio ntext that appears on the block, find and edit this code:

```angular2html
$content = "<p>
                    RNA-Seq datasets for multiple species are available.
                    MiSeq and HiSeq reads from multiple libraries were  cleaned with 
                    <a href=\"http://www.usadellab.org/cms/?page=trimmomatic\">Trimmomatic</a>
                    and assembled by <a href=\"http://trinityrnaseq.sourceforge.net/\">Trinity</a>.
                    <a href=\"http://weizhong-lab.ucsd.edu/cd-hit/\">CD-hit</a> was used to collapse highly similar
                    reads into a single sequence. Older transcriptomes were built with
                    <a href=\" http://www.dnastar.com/t-seqmanpro.aspx\">SeqMan Pro</a>.
                 </p>";
```