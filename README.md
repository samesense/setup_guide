# setup_guide

## Mac setup

* Homebrew

### Install with homebrew
* python3
* dash

### Bash aliases


### Optional

## Cluster setup

### python3
* Use virtualenv to manage your python3 modules.
* Use a bash alias to 
### snakemake

## Project layout
* code/sf.py contains my main snakefile. If running the snakefile on the cluster, I include a run.sh file that invokes the snakefile.
* Each project includes these directories, which are global variables in sf.py. 
    * work
    * code
    * data
    * tmp
    * plot
Only the code directory (sometimes plot) is in my git repository. Sometimes I include a web directory for publishing on Dropbox or other hosts. This web directory is added to my git repository to keep track of html, associated scripts, and css. I also include a static direcotry to hole contents like figures and javascript libraries. The static directory is onot put into the repository. For projects that turn into papers, a paper directory is also included and added to the git repository. Don't forget to make use of the .gitignore file.
* I also two files in every project
    * README.md describes the project and has my TODO list at the top.
    * .gitignore shows git what to exclude from the repository
    
## Project workflow
* Trello
* Git
* Gmail