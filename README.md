# Programming for Data Analsis Project  
***  

**Student Name:** Gillian Kane-McLoughlin | **Student Number:** G00398258  

This repository will contain my submission for the Programming for Data Analysis Project for Winter 2021.  

Contents:  
- progda_project.ipynb - this is the Jupyter notebook containing the main body of work and all references used in completing this project
- this README.md file  
- a .gitignore (Python) file  

### Software Information
***
The code for this assignment was written in Python (version 3.8.8) and ran in Jupyter Lab.    

Jupyter Version:  
jupyter core : 4.7.1  
jupyter-notebook : 6.3.0  
qtconsole : 5.0.3  
ipython : 7.22.0  
ipykernel : 5.3.4  
jupyter client : 6.1.12  
jupyter lab : 3.0.14  
nbconvert : 6.0.7  
ipywidgets : 7.6.3  
nbformat : 5.1.3  
traitlets : 5.0.5   


### Modules Required  
***
Please note that the following Python modules were used to create this notebook:  

``import numpy as np``  
``import pandas as pd``  
``import statistics``  

### How to Run the Notebooks 
***
A Python environment is required to run the two Jupyter notebooks containing the bulk of the submission for this assessment. To ensure that the notebooks run correctly, I would advise that you first install Anaconda on your machine, clone this repository to your device and then open and run the notebooks in Jupyter Lab as per the steps below:  
- Download Anaconda from https://www.anaconda.com/products/individual  
- Install the package  
- Clone this repository to your machine as per the steps outlined [here](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository)    
- Open the command line interface (CLI) on your machine - on Windows, open the Command Prompt tool by selecting Start, searching "cmd" and selecting it from the list. On a Mac, click the Launchpad icon in the Dock, type "Terminal" in the search field, then click Terminal  
- Navigate to the folder where the repository was cloned (above) on the CLI using the cd (Change Directory) command  
- Once in the correct folder, enter command "jupyter lab" to launch the program (note that although Jupter launches in your browser, it is running on your local machine)  
- Select the notebook from the left hand pane   
- **Important:** Select "Kernel" at the top of the notebook and click "Restart Kernel and Run All Cells"  
- To exit Jupyter once finished, close your browser, return to the CLI and enter command CTRL+C  

### Scope of Project  
***  
For my project, I decided to investigate the phenomenon of voter turnout. The Jupyter notebook will simulate a dataset using Python which would show the results of a survey carried out on 100 voting aged Irish citizens. The dataset will show the age of the person surveyed, their location (urban or rural) and the election type. The final value in the dataset will be the answer they provide to the question "_Did you vote or abstain in this particular election?_".  
Please note that the idea behind the dataset would be that these 100 people would not all be surveyed on the same day, so their responses will be in relation to different election types.  

### Issues Encountered
***
Throughout this project, the biggest issue I faced was obtaining figures to backup my ideas for my different variables. For example, I found one document ("Election Turnout in Ireland: measurement, trends and policy implications") which I relied heavily on for turnout figures in different elections, but it only covered elections prior to 2016. Other than the idea.int site, I was unable to find any other sources that were as indepth for the subsequent elections, and I was aware that I was relying on these two sourses for the majority of the figures I used. I would have preferred to have more sources to compare the figures against just for accuracy, but these proved difficult to source.  

Another issue encountered was the realisation that there are many factors that influence whether a person chooses to vote or not. Other variables I considered researching were education levels, political engagement and weekend voting, but I found myself under pressure to get the research done for the variables I had already selected, and so I had to limit the scope of my project to the impact of election type, age and geographical location on the decision to vote.  

I also have to acknowledge that while I spent a lot of time researching my variables and trying to understand the relationship between them and the decision to vote, I had to simplify some of them for the sake of this project. For example, we all know that you can have both a local and European election on the same day, or that we can be asked to vote on more than one referendum at a time, and while I do think these situations might increase the level of voter turnout, I was unable to figure out how I would work these situations into my simulation. Therefore, I had to take a more simple approach and assume that in any of the cases simulated in my dataset, only one type of election or vote was taking place at a time, which would not be an overly accurate reflection of this phenomenon in real life.  

Overall, I actually enjoyed working on this project as it was in relation to something I had an interest in (I have a BA in History & Politics), but if I had more time I know I would try to work out some of the issues alluded to above. Despite all of this, the resulting dataset simulated in my notebook showed results mostly in line with my research (voter turnout simulated in the dataset was within ~5% of the levels observed over the course of my research each time I ran the notebook).   

### References
***
[1] https://adriankavanaghelections.org/  
[2] https://www.britishelectionstudy.com/bes-findings/age-and-voting-behaviour-at-the-2019-general-election/#.Yc8q3mjP02w  
[3] https://www.census.gov/library/stories/2021/04/record-high-turnout-in-2020-general-election.html  
[4] https://www.cso.ie/en/csolatestnews/pressreleases/2006pressreleases/reportonvitalstatistics2004/  
[5] https://www.cso.ie/en/csolatestnews/pressreleases/2008pressreleases/reportonvitalstatistics2005/  
[6] https://www.cso.ie/en/csolatestnews/pressreleases/2009pressreleases/reportonvitalstatistics2006/  
[7] https://www.cso.ie/en/qnhs/qnhsmethodology/voterregistrationandparticipationmodule/  
[8] https://data.oireachtas.ie/ie/oireachtas/libraryResearch/2016/2016-01-28_l-rs-note-election-turnout-in-ireland-measurement-trends-and-policy-implications_en.pdf  
[9] https://www.europarl.europa.eu/election-results-2019/en/turnout/  
[10] https://www.europeanmovement.ie/irish-general-election-february-2020/  
[11] https://www.fairvote.org/what_affects_voter_turnout_rates  
[12] https://www.geeksforgeeks.org/create-a-pandas-dataframe-from-lists/  
[13] https://www.idea.int/data-tools/country-view/143/40  
[14] https://www.independent.ie/irish-news/abortion-referendum/abortion-referendum-turn-out-is-third-highest-ever-for-a-referendum-in-ireland-36949137.html  
[15] https://www.indexmundi.com/ireland/demographics_profile.html  
[16] https://www.ipa.ie/_fileUpload/Documents/LA_Times_Summer_2019.pdf  
[17] https://www.irishtimes.com/news/politics/urban-rural-divide-among-voters-made-clear-by-turnout-figures-1.1553322  
[18] https://www.maynoothuniversity.ie/research/spotlight-research/getting-out-vote-what-influences-voter-turnout  
[19] https://newbedev.com/count-occurrences-of-certain-words-in-pandas-dataframe  
[20] https://numpy.org/doc/stable/reference/random/generated/numpy.random.binomial.html  
[21] https://ourworldindata.org/age-structure  
[22] https://pandas.pydata.org/pandas-docs/stable/user_guide/merging.html  
[23] https://python-course.eu/numerical-programming/weighted-probabilities.php  
[24] https://pythonexamples.org/pandas-set-column-as-index/#2  
[25] https://www.refcom.ie/previous-referendums/  
[26] https://www.researchgate.net/publication/228215776_What_Affects_Voter_Turnout  
[27] https://www.researchgate.net/publication/253829692_The_geography_of_Irish_voter_turnout_A_case_study_of_the_2002_general_election  
[28] https://www.rte.ie/brainstorm/2018/1019/1005247-voter-turnout-elections-ireland/  
[29] https://www.rte.ie/news/2019/0526/1051741-divorce-referendum/  
[30] https://www.rte.ie/news/elections-2019/results/#/local  
[31] https://stackoverflow.com/questions/34023918/make-new-column-in-panda-dataframe-by-adding-values-from-other-columns/42634214  
[32] https://www.statista.com/statistics/710767/irish-population-by-age/  
[33] https://www.tcd.ie/Political_Science/people/michael_gallagher/Election2016.php  
[34] https://towardsdatascience.com/bernoulli-and-binomial-random-variables-d0698288dd36  
[35] https://tradingeconomics.com/ireland/rural-population-percent-of-total-population-wb-data.html  
[36] https://www.thejournal.ie/low-turnout-presidential-election-4309871-Oct2018/  
[37] https://towardsdatascience.com/building-a-logistic-regression-in-python-step-by-step-becd4d56c9c8  