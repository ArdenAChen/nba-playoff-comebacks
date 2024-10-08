# NBA Comeback Percentage Project

## Description
This data science project analyzes how several factors affect the chance of a team making a comeback in a playoff series after trailing 0-2 in a series. This project is partially inspired by the statistic that 7.41% of teams make a comeback when down 0-2. I was interested in seeing how some easily accessible statistics like playoff seeding would change the odds of a comeback.

## Table of Contents
* [Introduction](#nba-comeback-percentage-project)
* [Setup Instructions](#setup-instructions)
* [Project Structure](#project-structure)
* [Models and Analysis](#models-and-analysis)
* [Results](#results)
* [Contributing](#contributing)
* [License](#license)
* [Future Work](#future-work)
* [Acknowledgments](#acknowledgments)
* [Contact Information](#contact-information)

## Setup Instructions
There are a couple of ways to view or run the notebook by using one of the following options:

### **View the Notebook in MyBinder**:
Click the link below to launch the notebook in an interactive MyBinder environment. This method is best for viewing and interacting with the Notebook, but does not allow editing of the project.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ArdenAChen/nba-playoff-comebacks/blob/main/notebooks/NBA%20Comeback%20Percentage%20Project.ipynb)

### **Running the Notebook Locally**:
This method allows for editing of the Notebook.
1. **Clone the repository**
   * Clone the repository to your local machine using the following commands in a Bash shell terminal:
     1. `git clone https://github.com/ArdenAChen/nba-playoff-comebacks.git`
     2. `cd nba-playoff-comebacks`
2. **Install Jupyter Notebooks and necessary libraries**
   * To install Jupyter Notebooks and the libraries, input into the terminal: `pip install -r requirements.txt`.
     * The packages included in `requirements.txt` are `Jupyter Notebooks`, as well as the libraries `pandas`, `NumPy`, `Matplotlib`, `seaborn`, and `scikit-learn`
3. **Open and Run the Notebook**
   * Start Jupyter Notebook by running the following command in the terminal: `jupyter notebook`
   * Navigate to the file `NBA Comeback Percentage Project.ipynb` in the browser and open it
   * At the top, under `Run`, click on `Run All Cells` to run every cell. You can also run each cell individually by pressing `Shift` + `Enter`, or `Ctrl` + `Enter` (`Cmd` + `Enter` for Mac).

## Project Structure
* `data/`: Contains the dataset used in the analysis
* `notebooks/`: Jupyter Notebooks with code and analysis
* `LICENSE`: Licensing of this project
* `README.md`: Project documentation
* `requirements.txt`: List of Python packages and libraries required to run the project

## Models and Analysis
The Notebook tests several different attributes of the data to see if there is any correlation between the attribute and the odds of making a comeback when an NBA team is trailing 0-2 in a series.
* Factors that had a moderate or significant correlation or connection to making a comeback are included as factors in a formula that calculates the chance a comeback will happen based on those factors.
  * This formula adds multipliers based on the factors and takes into account things like sample size and $R^2$ scores. More on this formula can be found in the Notebook.

## Results
Using the DataFrame, I found that there were five total factors which had some connection to the odds of a comeback. More details on which factors, as well as what each factor means alongside analysis are provided in the Notebook.

## Contributing
Any constructive criticism is greatly appreciated. Feel free to let me know about issues or submit pull requests for this project.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Future Work
* Implement machine learning models to improve accuracy
* Finding more correlations with other statistics
  * Utilizing other DataFrames that record statistics such as individual player statistics, offensive rating, defensive rating, etc.
  * Regular season win-loss record or regular season win-loss record differential could be a good indicator as well.
* Accounting for era for each factor
* Establishing more concrete ranges for eras
  * I only really split the data set into the 1900s versus the 2000s, so there is definitely potential for improvement in this regard.

## Acknowledgments
* Thanks to [Land Of Basketball](https://www.landofbasketball.com/), [Basketball Reference](https://www.basketball-reference.com/), [Wikipedia](https://www.wikipedia.org/), and [The Official NBA Website](https://www.nba.com/) for providing the data.

## Contact Information
For any questions or feedback, please contact me at `aac@ucsb.edu`.
