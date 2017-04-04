# Final Exam - Spring 2017 

- Total Points : `100`
- Deadline : `April 22nd, 11:59 PM`
- Submission type : `Markdown document + Ipynb Notebook`

---
###**You can choose any one of the pattern described below. **

---


### Pattern 1 : (100 Points)

> Using a **readily downloadable dataset**, perform **5** analysis on the dataset and create a Readme.md file explaining your analysis. 


| Code        | Points           | 
| -------------- |:-------------| 
| Individual Analysis        | **15** Points | 
| Readme.md      | **25** Points      |   
| Total      | **100** Points      |   


---
### Pattern 2 : (100 Points)


> Use an **API to collect data and store it**. Perform **4** analysis on the dataset and create a Readme.md file explaining your analysis.



| Code        | Points           | 
| ------------- |:-------------:| 
|Collect Data       | **15** Points | 
| Storing Data      | **15** Points      |   
| Individual Analysis  | **15** Points      |
| Readme.md      | **25** Points      |   
| Total      | **100** Points      | 


---

# General Instructions :

- You need to submit a `runnable ipython notebook`. TA should be able to clone your repository and run the code in their machine. (They will install any libraries you have as well as set-up any environment variable and file argument that you have need.) But there should be no code change required to run the notebook.

- You are allowed to use any python libraries . You can use a library for crawling (if you think you need it but it should not be an automated click to run types.) You can use **only python libraries or shell packages only for the whole exam submission**. If you need to use anything else, please contact `brahmbhattspandan@gmail.com`

- If you are using any additional library, please mention it in your readme file. You should have a section at the end of readme files : `Addtional Instructions to Run the code` - Specify the additional libraries and how to install them.

- Do not share/upload any keys on Github. You should store them as environment variable. If the TA needs those key, they will send you a email regarding them
```sh
$ export data_download_key = abcd1234
```
```python
import os
data_download_key = os.get_env('data_download_key')
```
- You can only use `matplotlib,seaborn,bokeh` to create plots. Highly recommended to have plot as a part of your analysis. You can have multiple plots per analysis

- Submitting the dataset (should be in `data` folder only):
	- If it is possible, create a top level folder called as `data/raw_data` and upload your data over there.
	- If the data is too big to upload and you have a link from where you downloaded the data , you can just put a **txt file** containing that link and additional instructions that the TA can use to download the data at `data/raw_data/link_to_data.txt`. **The TA should be able to download the data else you will lose point if the instructions are missing**
	- If none if the above ways work for you, you can sample the data and upload the sampled data in `data/raw_data`. 

- Following folder/file structure is **required** : 

| Path        | Purpose           | 
| ------------- |-------------| 
|`final/`       | folder to store all your final submission files | 
| `final/data/*`      | Store all raw data      |   
| `final/analysis/ana_[1-5].ipynb`  | Notebook to store the code for analysis      |
| `final/analysis/ana_[1-5]/*`  | Extra files required/generated for each analysis (Eg. output.csv,plot.png)      |
| `final/readme.md`  | Markdown Final report     |
| `final/extra`  | Extra files if needed     |


-  The TA will only look for a folder `final` in your repository and all the required files should be available inside it. You may lose points if the files are kept in some other location or have a different naming convention.

- Your analysis should use **downloaded data only** (and not try to re-download this data again during analysis time).

-  Using **NLTK** in your analysis will carry higher points. Just using it for the sake of it does not constitute as NLTK usage.

-  Since this is final, **no extension of deadline is available**. You lose 5 point for every 4 hours delay. Eg : `You submit it at 12:01 AM or 3:01 AM , you will lose 5 points. You submit it at 4:01 AM you lose 10 points`

-  Please use **Markdown syntax in your ipynb notebook** so the TA understands what you are trying to do. 

-  You will need to create a final report stating what analysis you have done and its output. It needs to be created as a markdown document as named `readme.md`. This is important and failing to do so will result in large loss of marks. **`No Prezi,ppt,pdf allowed`**. Imagine if I was to go through only this document (and no other file), I should be able to understand what data you had, how you obtained it, how is it stored, what analysis have you done, what information did you get etc etc. You wont get any points for making cells in Jupyter as markdown document and saving it as Readme.ipynb file. 

- Your Readme.md should **contain the plots** that you have created for the analysis. TA wont be looking inside the repository to search for png files.

- TA are not going to help with any git related questions. Its your responsibility to do daily commits for any work. There is no deadline extension for `laptop crashing, git not working, data upload issues`.  Since the TA have their own final exams, they wont be responding to any questions during the last **3 days of submission**. Your best source of advise and help is `Stackoverflow`. 
- Follow instructions over here and some common sense when you ask a question on SO to get an answer quickly. [How to ask a question on StackOverflow ](https://stackoverflow.com/help/how-to-ask )
