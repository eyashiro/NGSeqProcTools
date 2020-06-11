# README

Last modified: 11 June, 2020

Author: Erika Yashiro, Ph.D.

Repository name: NGSeqProcTools

Version 1.1.0

########################################
### Contents
   - Description of the repository and tools
   - How to run the help function with usage instructions
   - How to cite the tools 
   - Version history

########################################

### Description of the repository and tools

NGSeqProcTools is a git repository where you can find tools that can be useful for the BIO-servers at AAU.  

The current collection of tools are geared toward processing Illumina sequenced data.  

Current list of tools:  
  * getseqID   - This script retrieves the LIB and Sequence IDs from either the LIB or SEQ ID user query.
  * getseq4SRA - This script retrieves the raw fastq files from a list of names in the samples file. Then it creates part of the SRA submission form in tab-delimited format.  

### How to run the help function with usage instructions

Type either (replace script by the script name): 

script -h

OR

script -help

### How to cite the tools

Use this github site in your papers when you cite the tools here.  
https://github.com/eyashiro/NGSeqProcTools  


########################################

# VERSION HISTORY

NGSeqProcTools v1.1.0
Released for user evaluation:  11 June 2020
- This is the official github version-controlled release.
- getseqID is now transferred to NGSeqProcTools. it was previously a tool in the AmpProc repository.
- getseqID and getseq4SRA both determine location of the scripts automatically.
- These scripts also now use a config file containing the paths to different required resources. The template file for this is NGSeqProcToolsConfig_template.sh
- The help functions of getseqID and getseq4SRA were updated and also now contains examples of commands.


NGSeqProcTools v1.0.0
Released for user evaluation:  3 June 2020
- getseqSRA working version was released

