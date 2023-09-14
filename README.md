# squirrel
An basic repository with an environment and .gitignore

## Central Park Squirrel Census

![squirrel!](https://imgs.6sqft.com/wp-content/uploads/2018/10/03124715/squirrel-Central-Park.jpg)

https://www.thesquirrelcensus.com

### Explore the data

The survey data was originally collected and stored in to files available at this link:

[https://www.thesquirrelcensus.com/data](https://www.thesquirrelcensus.com/data)

For this exercise, we will use an integrated `.csv` file that combines data and is a little more structured than the raw `.csv`. This file was downloaded from [kaggle.com](http://www.kaggle.com) at this link:

[2018 survey data on Kaggle](https://www.kaggle.com/datasets/dominoweir/nyc-2018-squirrel-census)

The downloaded file is already added to the class repository in the `data/` folder as as `2018_Central_Park_Squirrel_Census_-_Squirrel_Data.csv`. You can copy this folder to your new repository on your local machine

### Setting up for some squirrely analyses:

1. Create a short name for your group and a new repository for this exercise. Clone the repo to your local machines. 

1. Load the combined datafile (either using the url or from your repository's `../data` directory) using `pd.read_csv()`.

1.  Use standard `df.info()`, `df.head()`, `df.describe()` to explore the data. 

1. Read over the user guide here to understand what the various columns contain.

[Survey Data User Guide](https://www.dropbox.com/s/cs293zzz1li79nn/user-guide_data-sets_nyc-open-data-week-multi-park-squirrel-count.pdf?dl=0)

Additional information on the survey and stories are available here:

[https://www.thesquirrelcensus.com/data](https://www.thesquirrelcensus.com/data)

1. Work together to make a new `.ipynb` in your repo that contains an analysis and simple visualization of the data!


####
# LeafMap Example: Visualizing NYC Squirrel Census Data
In this example, we will demonstrate how to use the lwafmap package in python to visualize NYC squirrel census data obtained from the Kaggle dataset 'NYC 2018 Squirrel Census'. Leafmap simnplifies the process of creating interactive maps and working with geospatial data, making it easy to explore and analyze datasets like this one.

## Getting Started
### Dependencies
Before you begin, ensure you have the following prerequisites:

Python installed on your machine.
The LeafMap package installed.
Download the NYC Squirrel Census data from Kaggle and save it to your project directory.

### Installing
How/where to download your program
Any modifications needed to be made to files/folders
### Executing program
How to run the program
Step-by-step bullets
code blocks for commands
## Help
Any advise for common problems or issues.

command to run if program contains helper info
## Authors
Contributors names and contact info

ex. Dominique Pizzie
ex. @DomPizzie

## Version History
0.2
Various bug fixes and optimizations
See commit change or See release history
0.1
Initial Release
## License
This project is licensed under the [NAME HERE] License - see the LICENSE.md file for details

## Acknowledgments
Inspiration, code snippets, etc.

awesome-readme
PurpleBooth
dbader
zenorocha
fvcproductions