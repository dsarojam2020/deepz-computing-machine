# Exploratory Data Analysis on NetFlix, Amazon Prime, Disney+ and Hulu real time data. 

## Step 1: Finding a Project Topic/Idea/Domain

Use the Movies and TV shows available on Netflix, Amazon Prime, Disney+ and Hulu to draw insights on the popularity of the shows/movies, availabilty, IMDb ratings etc.             
<..........Eloborate on problem statement.........>                    

          
## Step 2: Finding a Dataset for your Project

**Selected Dataset**    
- Webscrap the Dataset
 - Webscrap the NetFlix, Amazon Prime, Disney+ and Hulu data using BeautifulSoup  
      
          - Notebook: https://github.com/ruch798/Movies-and-TV-shows
          - Notebook: https://jovian.ai/viewer?url=https%3A%2F%2Fgithub.com%2Fruch798%2FMovies-and-TV-shows%2Fblob%2Fmaster%2FData_scraping.ipynb
          - Watch: https://www.youtube.com/watch?v=87Gx3U0BDlo
          - Watch: https://www.youtube.com/watch?v=ng2o98k983k    

**Problem Statement**     
The objective of this project is to deliver insights to understand customer demands better and thus help developers to popularize the product. This project involves loading the data into data frame, cleaning the data, extracting statistics from the dataset, exploratory analysis and visualizations, and asking & answering questions.  
  
The aim of this project is to find out which are the most relevant features that students consider to choose the preferred American university. Some of the essential questions for developing this project are related to the number of applications, admissions, and enrollments, cost of tuition and fees, cost of living on campus, types of degrees offered, and features of the states where universities are located (population and GDP).

## Step 3: Preparing an Outline & Deadlines - Planning

**Outline for a Data Analysis Project**  

1. Perform data preparation & cleaning
    - Load the dataset into a data frame using Pandas
    - Explore the number of rows & columns, ranges of values etc.
    - Handle missing, incorrect and invalid data
    - Perform any additional steps (parsing dates, additional columns, merging datasets etc.)
    - Dataset Preparation 
    - What are the questions I can ask? 
     - df.describe()
     - Variable-Specific EDA
     - Pandas profiling 
          
           -!pip install https://github.com/pandas-profiling/pandas-profiling/archive/master.zip                                                 
           - from pandas_profiling import ProfileReport       
           - profile = ProfileReport(movies_df, title='Pandas Profiling Report', html={‘style: {full_width= True}})               
           - profile.to_notebook_iframe()                   
           - profile.to_file("edaononlinestreaming_report.html")       
     - Correlation 
- Dataset Cleaning 
     - Answer the questions   
          
           - .dropna() — drop NaN values (if needed) 
           - .fillna() — impute NaN values (if needed) 
           - .drop_duplicates()— drop duplicate values (if needed) 
           - .astype()— change a column data type (if needed) 
    
2. Perform exploratory analysis & visualization
    - Compute the mean, sum, range and other interesting statistics for numeric columns
    - Explore distributions of numeric columns using histograms etc.
    - Explore relationship between columns using scatter plots, bar charts etc.
    - Make a note of interesting insights from the exploratory analysis
    
3. Ask & answer questions about the data
    - Ask at least 4 interesting questions about your dataset
    - Answer the questions either by computing the results using analysis or graphs
    - Create new columns, merge multiple dataset and perform grouping/aggregation
    
4. Summarize your inferences & write a conclusion
    - Write a summary of what you've learned from the analysis
    - Include interesting insights and graphs from previous sections
    - Share ideas for future work on the same topic using other relevant datasets
    - Share links to resources you found useful during your analysis


**Project Outline & Timeline**  

  | Task                                                | End Date     | Status                                                                 
  |-----------------------------------------------------|--------------|---------------------------------------------------------------------  
  | Create the base structure with available dataset    | 1/28         | In- Progress
  | Webscrap the Dataset - Watch Videos                 | 1/29         | In- Progress                                                       
  | Practise - Beautiful Soup                           | 1/29         | In- Progress                                                         
  | Dataset Preparation                                 | TBD          |                                                    
  | Dataset Cleaning                                    | TBD          |                                                       
  | EDA and Data Visualization                          | TBD          |                                                       
  | Conclusion                                          | TBD          |                                                        
  |                                                     | TBD          |                                                        
  |                                                     | TBD          |                                                     

- [ ] Webscrap the Dataset
    - [ ] Watch videos on Web scrapping and practise a sample web scrapping - 1/26 
    - [ ] Webscrap the NetFlix, Amazon Prime, Disney+ and Hulu data using BeautifulSoup  
      
          - [ ] Notebook: https://github.com/ruch798/Movies-and-TV-shows
          - [ ] Notebook: https://jovian.ai/viewer?url=https%3A%2F%2Fgithub.com%2Fruch798%2FMovies-and-TV-shows%2Fblob%2Fmaster%2FData_scraping.ipynb
          - [X] Watch: https://www.youtube.com/watch?v=87Gx3U0BDlo 
           - [ ] Practise sample - 1/27
          - [ ] Watch: https://www.youtube.com/watch?v=ng2o98k983k
- [ ] Dataset Preparation 
    - [ ] What are the questions I can ask? 
     - [X] Describe - `df.describe()`
     - [ ] Variable-Specific EDA
     - [X] Pandas profiling 
     
        `profile = ProfileReport(df, title='Pandas Profiling Report', explorative=True)`            
        `profile.to_widgets()`                    
        `profile.to_notebook_iframe()`            
        `profile.to_file("your_report.html")`               
     - [ ] Correlation 
- [ ] Dataset Cleaning 
         
        .dropna() — drop NaN values (if needed) 
        .fillna() — impute NaN values (if needed)                   
        .drop_duplicates() — drop duplicate values (if needed)                
        .astype() — change a column data type (if needed)                     
- [ ] EDA and Data Visualization 
    - [ ] Webscrap the Dataset
- [ ] What is the Conclusion/Inferences? 


## Step 4: Executing & Iterating on your project

**Project Deliverables**   

- Jupyter notebook (web scrapping - 2nd step)
- EDA
- Medium/LinkedIn Blog post
- Portfolio (Streched)
- Resume (Streched)
 
## Step 5: Reference and Future Research
