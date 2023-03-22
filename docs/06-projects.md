# Projects {-}
## TL;DR {-}
For Project 1, pick an environmental dataset on a topic you already know something about, ask a question, and answer it using data. For Project 2, also do some stats!

## Example project
The CO~2~ case study is an example project to give you a sense of what constitutes a great final product. You can access the CO~2~ case study through [this github repo](https://github.com/ENST222/exercises/tree/main/lab-06-co2-case-study) or in the class R Studio Cloud workspace (lab-06-co2-case-study).

## What and why {-}
The goal of the projects is to apply the techniques we have covered in class to a novel dataset in a meaningful way. The mid-semester project should emphasize data wrangling, tidying, and visualization, and the end of semester project should additionally incorporate statistical modeling (bonus "points" if you use spatial data as well). For both projects, you will analyze any environmental dataset you'd like, with the one requirement that it be related to a topic with which you are already familiar. Data analysis is usually most powerful if you have expertise in a relevant topic area and can, therefore, ask questions and draw conclusions that are well-grounded in that disciplinary domain. So this is a good opportunity to apply previous coursework or experiences in a new, perhaps more quantitative context. 

You don't necessarily need to do an exhaustive data analysis (i.e., do not calculate every statistic or visualize every variable), but rather demonstrate that you are proficient at: 

- asking meaningful questions and answering them through data analysis
- using R and GitHub to code collaboratively
- presenting and interpreting your results using literate, reproducible programming (i.e., RMarkdown) 
- for project 2, using statistical analysis to draw more rigorous conclusions

To that end, you should focus on your research questions and work backwards from there. Think about what types of analysis and visualizations will help you answer your question and how your data need to be wrangled or tidied in order to complete those tasks. You'll probably need to do some initial exploratory data analysis to get a sense of what types of questions you might ask. As you enter the analysis stage, you can stick to the packages we learned in class (`tidyverse`) or push yourself explore others if they will improve your analysis. Finally, give careful thought to how you communicate your analysis. Neatness, coherency, and clarity are all important.

If at any point you are having trouble, don't hesitate to ask for help before it's too late. The main reason we have a lab session is so you can work while I'm in the room to provide immediate assistance. Take advantage of it!

## Data {-}
In order for you to have the greatest chance of success with this project it is important that you choose a manageable dataset. This means that the data should be readily accessible and large enough that multiple relationships can be explored. As such, your dataset should have at least 50 observations and between 10 to 20 variables (exceptions can be made but you must speak with me first). The dataset's variables should include both categorical and numerical variables. If you are using a dataset that comes in a format that we haven't encountered in class, make sure that you are able to load it into R as this can be tricky depending on the source. Please don't reuse datasets we have already analyzed in class.

Below is a list of data repositories that might be of interest to browse. These are not all exclusively environmental data repositories, although some of them are. You're not limited to these resources - you are welcome to identify your own datasets as well.

-   [TidyTuesday](https://github.com/rfordatascience/tidytuesday)
-   [Bikeshare data portal](https://www.bikeshare.com/data/)
-   [Kaggle datasets](https://www.kaggle.com/datasets)
-   [Awesome public datasets](https://github.com/awesomedata/awesome-public-datasets)
-   [Harvard Dataverse](https://dataverse.harvard.edu/)
-   [Chesapeake Bay Program Data Hub](https://datahub.chesapeakebay.net/)
-   [USGS National Water Information System](https://waterdata.usgs.gov/nwis)
-   [US EPA Toxic Release Inventory](https://www.epa.gov/toxics-release-inventory-tri-program/tri-data-and-tools)
-   [NSF Long Term Ecological Research Data Portal](https://lternet.edu/using-lter-data/)
-   [US EPA Environmental Dataset Gateway](https://edg.epa.gov/metadata/catalog/main/home.page)
-   [NOAA National Centers for Environmental Information](https://www.ncei.noaa.gov/)

## Collaborative coding {-}
These are group projects for a reason - they will force you to learn how to code collaboratively. Code conflicts are inevitable and indeed very annoying. But learning how to fix them is an important skill. Embrace the messiness and try not to get too frustrated - I am here to help. Googling error messages is usually helpful as well. 

It should go without saying, but everyone needs to make significant code contributions to each project. Because we are using Git and GitHub, I can see each person's commits, including what you did and when you did it. So it is very obvious if one person is doing most of the work, for example, or another person waited till the last minute to make a few sloppy contributions. 

## Deliverables {-}

### Proposal {-}

**Introduction (2 paragraphs)**  
The introduction should introduce your general research question and your data. In the first paragraph, provide background information to introduce the topic. You should do some research and cite relevant sources to provide context that is grounded in the literature. For example, if I wanted to know whether there was evidence of increasing hurricane intensity in the `storms` dataset we have previously worked with, I would briefly review the scientific literature on why and how we know hurricanes are becoming more intense. The topic should be something you've already researched in some way so that you have enough expertise to spend most of your time analyzing your data rather than reading about your topic.

In the second paragraph, state your research question and provide a brief overview of your dataset (where it came from, how it was collected, etc.).

Please cite references parenthetically using author-date format (author's last name, year of publication) using any citation style you'd like. APA is generally straightforward.

**Data (1-2 paragraphs)**  
Provide a more detailed description of your dataset, including names of files (if you have more than one), number of observations, and names of files. Then use the `skim()` function to provide a detailed summary of each dataset. Be sure to place your data in the \`/data\` folder of your project GitHub repository.  

**Data analysis plan (2-4 paragraphs)**  
This section should include a brief description of 
- The outcome (response, Y) and predictor (explanatory, X) variables you will use to answer your question, if applicable
- The comparison groups you will use, if applicable
- Very preliminary exploratory data analysis, including summary statistics and visualizations, along with some explanation on how they help you learn more about your data
- The method(s) that you believe will be useful in answering your question(s).
- What results from these specific methods are needed to support your hypothesized answer?

**References cited**
Include a list of any references you cited. You can use any citation format you'd like as long as the citations are clean and consistent. If you're not sure, APA is a straightforward default.

**README file**  
The README file is like the home page of a GitHub repository. This is an important component of reproducible data analysis - someone should be able to access your GitHub repo, quickly learn what you did and why you did it in the README, and then access your analysis. Your project template includes a README.md template file. You should add your project title and author names to the README template, then populate the "Executive summary" and "Data dictionary" sections.

### Report {-}

The report will more or less follow the same format as the proposal, with some additional content to contextualize your topic and present your results.

**Introduction (at least 3-4 paragraphs)**  
The content should be the same as your proposal introduction, but with an additional 1-2 paragraphs to expand on your background information. Please aim to cite 3-5 information sources. 

**Data (1-2 paragraphs)**  
Same guidelines as the proposal.

**Methods (2-4 paragraphs)**  
This section should include a description of the methods you used and why these methods were the right approach for answering your research question(s). Include any packages you used and provide a [citation for each package](https://www.r-bloggers.com/2018/08/how-to-cite-packages/). Start with a general overview of your approach, and then fill in the details. You don't necessarily need to describe every single function you used and line of code you wrote. Focus instead on the big picture: why and how you wrangled the data, created new variables, calculated data summaries, made comparisons, identified relationships and patterns, etc.  
    
**Results and discussion (at least 3-4 paragraphs but more is ok)**  
This section should present and discuss the results of your data analysis with an emphasis on how each of your results helps you answer your research question(s). Whereas a typical scientific paper generally includes separate results and discussion sections, here we will combine them to make the report more interesting and readable. It needs to include narrative text as well as code output (i.e., figures, tables, etc.). 

You should organize this section around each of your key findings. Be sure to explain what each visualization is illustrating and how the ways in which the data are presented help to address your question. Discuss why we might be seeing particular patterns, relationships, trends, differences, etc. This is where your domain knowledge comes in again - you need to have a good sense of the underlying phenomena that are represented by your data in order to develop well-founded explanations. You may find that it will be helpful to cite additional information sources to help contextualize your results, but it really depends on the dataset, so these additional citations are optional. Please also include a discussion of the limitations of your analysis, what you would do if you had more time, etc. 



**References cited**  
Same guidelines as the proposal.

**README summary**  
Make sure to update your README.md file so that it reflects the content of your final report.

### Repo organization {-}

The following folders and files should be in your project repository:

-   `proposal.Rmd` + `proposal.md`: Your proposal documents
-   `report.Rmd` + `report.md`: Your report documents
-   `README.md`: your README file containing a project summary and metadata
-   `/data`: folder containing your dataset(s) in CSV or RDS format

Your repo should not contain any other files. You may find it useful to create some "scratch" files to do  exploratory analysis or code testing outside of your project file. But these files should be removed from your final repository. Our goal is to create a clean, fully reproducible repository that could be made public. That means that only your final, well-documented work should be included.

## Project evaluation {-}
- Question and data: The research question should be well-designed and the data should be relevant to the research question.
- Methods: Appropriate analytical methods should be used to address the research question.
- Creativity and critical thought: The project should be carefully designed and implemented, and limitations/shortcomings should be thoughtfully discussed.
- Professional polish: The figures and writing should follow best practices (be free of errors, well-organized, polished, etc.).
- Syntax: The report should take advantage of [R Markdown syntax](https://www.rstudio.com/wp-content/uploads/2015/03/rmarkdown-reference.pdf) to format for clarity (e.g., plain text, code chunks, bulleted lists, headings, embedded hyperlinks, inline code, etc.) 
- Time management: The team should equitably distribute time spent on the project.
- Collaboration: The team should work as a cohesive unit to collaboratively complete the project. This involves good communication and defining clear expectations for each other.
- Reproducibility: Entire analysis can be run by an independent user in a new R Studio session and README file contains a project summary and metadata description.

## Tips {-}
- You're working in the same repo as your teammates now, so merge conflicts will happen and that's fine. Commit and push often. And ask questions when stuck.
- Each team member should be contributing, both in terms of quality and quantity. Talk to me if you have any issues with this.
- Set aside time to work together and apart (physically).
- In your knitted/rendered report file, your code should be hidden (use `echo = FALSE` in your code chunks) so that your document is neat and easy to read. However your document should include all of your code so that if I re-knit your R Markdown file I should be able to obtain the results you presented. 
- Make sure to knit your final report, commit it, and then push to GitHub!
