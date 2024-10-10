# turbo-lamp
Documenting my progress in obtaining my degree from RealPython University with a minor in Stack Exchange. Scripts are alterations to example problems in tutorials, most of which involve adding tasks in the interest of teaching myself skills not covered in the course. 
Repository title completely unrelated because Github suggested it. Thank you, Github.

## Data Cleaning, First Foray
Example data cleaning problems from beginner course *Data Cleaning with pandas and Numpy* by Ian Currie.

**Skills learned from the course:**
* reading data from .txt and .csv files and make basic alterations
* dropping unnecessary columns/rows from a DataFrame
* changing the index of a DataFrame
* using basic .str() methods to clean columns
* renaming columns
* skipping unnecessary rows in .csv file

**Skills learned by scouring the swamps of Stack Exchange and official pandas documentation, often preempting the tutorial:**
* fetching, decoding and reading data from a url
* splitting and slicing and stripping strings
* cleaning data using list comprehension
* set().issubset()
* more advanced .str() methods
* checking for duplicates, replacing data in individual cells
* concocting conditional statements, ordering if/else blocks 
* ordering if/else blocks
* querying dataset, data aggregation and grouping
* combining Series and merging DataFrames
* changing Series datatypes and working around null values
* applying lambda functions
* simple data visualization with **matplotlib.pyplot** and **plotly.express**
* compare datasets with different shapes
* applying a formatting mask to a DataFrame to highlight values

**Skills I would like to learn next:**
* write more pythonic code. too attached to method chaining
* scraping data from html. never again will i copy and paste hundreds of items into a list
* regular expressions, even though they're terrifying
  
### Olympic Data
Data about the performance of countries/teams in the summer and winter Olympic games as of ~2012. Original column headers are located on the second line and painful to look at. Country column has both the country name and code, the latter of which is sometimes duplicated.
* transferred data frm url directly to dataframe
* renamed column headers
* split team_name column into team_name and team_code, keeping only the first instance of the team name without unnecessary parentheses/brackets
* set team_code as index
* attempted to condense code into as few lines as possible
* discovered an addiction to dot notation when referencing columns

### University Towns Dataset
Messy text document containing a list of towns under their state "header". each town is followed by a list of colleges/universities separated by varying delimiters.
Digits in square brackets are scattered about and a few schools are duplicated or are followed by some random factoid. Scrutinized every line multiple times to clean this thing, and it would honestly have been quicker to simply do it by hand. I shudder to think what it would have been like if it had been several thousand lines long instead of 567.
* transferred and decoded data to list of strings (some characters were being shifty)
* took psychic damage from cleaning said list of strings. employed an egregious number of if/else statements
* transferred to DataFrame and cleaned some more (dropping, reassigning, checking for duplicates)
* practiced aggregating and querying the dataset
* spent a total of 12 hours on Wikipedia copying and pasting additional data into lists... for character building purposes
* messed around with datetime and categorical datatyping just to see what was up
* attempted to condense code into as few lines as possible. traumatizing
* performed comparison of original, unaltered dataframe and updated dataframe
* further classified data for more in-depth analysis

### Exploring the Books Dataset
Absolute cluster and I will *not* be bothering with that.
