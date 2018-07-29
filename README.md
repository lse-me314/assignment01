# ME314 Introduction to Data Science and Big Data Analytics

### LSE Methods Summer Programme 2018


#### Rstudio environment

To work on assignments, you need to have an RStudio environment. For local installation, you can follow one of numerous instructions online (e.g. https://medium.com/@GalarnykMichael/install-r-and-rstudio-on-windows-5f503f708027). Basically, all you need is to install two things, R and Rstudio.

Instead, you can use our RStudio server which supposedly works in a way very similar to the local version. You can access to the server through this url: https://me314.hpccloud.lse.ac.uk/. After going to the page, enter your LSE username and password.


#### Instructions for Submitting Homeworks

Each homework will be a single file in the [RMarkdown](http://rmarkdown.rstudio.com) format.  The files linked below are *named very carefully*, to make it easy for us to identify your completed lab assignments.

1.  Create a new RStudio project.

    Each assignment of this course is created as a github repository. To work on the assigment, first you need to clone the respository (i.e. copy the entire repository). The easiest way to do so is through creating a new project.
    
    1) Click a project button (near the top-right corner of the screen)
    2) Select "New Project" (this will open a popup window)
    3) Select "Version Control"
    4) Select "Git"
    5) Enter repository URL (for this assignment, it is https://github.com/lse-me314/assignment01)



2.  Rename the starter files.

    For each day, you will start with a starter file, which is in the RMarkdown format.  You should embed your answers, with code, into your version of the instruction files. The starter file can be found in the project folder newly created in Step 1. 
    
    The first thing you need to do is rename the starter file using your full name. For example, the first assignment file is named `ME314_assignment1_LASTNAME_FIRSTNAME.Rmd`, which you will need to rename by replacing the uppercase terms with your own last and first names, e.g.  `ME314_assignment1_Bloggs_Joe.Rmd`.

    To rename files, you can use R's `file.rename()` function, or Rstudio's rename capability (In the "Files" pane, tick the file to rename, then click "Rename").
    
3.  Work on the assignment.

4.  Create an HTML file to submit. From RStudio, you can create an HTML output file with your evaluated code, figure, and text answers by clicking the "Knit HTML" button in the top of the editor pane in RStudio.  The resulting HTML file will be saved in your working directory.

4.  Download a knitted html. Like you did in step 2, use the "Files" pane (Tick the file to download, then click "More", select "Export")

5.  Upload the resulting HTML file -- renamed! -- to the course Moodle page, to the appropriate assignment folder.

We will walk you through this process in the Day 1 lab, so don't worry if it seems complicated the first time.  This sort of careful workflow process and file management is part of learning practical data science too!

We do not mark the homework but we will walk through the solutions at the start of computer labs the following day.

#### After finishing an assignment

Don't forget to log out from the server if you are using RStudio Server. You are sharing computing resource with other students. If we observe find a session inactive for long time, we will terminate the session.
