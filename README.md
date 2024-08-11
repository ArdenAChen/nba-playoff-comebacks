# NBA Comeback Percentage Project

## Description
This data science project analyzes how several factors affect the chance of a team making a comeback in a playoff series after trailing 0-2 in a series.

## Table of Contents
* [Introduction](#nba-comeback-percentage-project)
* [Setup Instructions](#setup-instructions)
* [Project Structure](#project-structure)
* [Models and Analysis](#models-and-analysis)
* [Results](#results)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)

## Setup Instructions
There are a couple of ways to view or run the notebook by using one of the following options:

### **View the Notebook in MyBinder**:
Click the link below to launch the notebook in an interactive MyBinder environment. This method is best for viewing and interacting with the Notebook, but does not allow editing of the project.
* [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ArdenAChen/nba-playoff-comebacks/HEAD?filepath=notebooks/NBA%20Comeback%20Percentage%20Project.ipynb)

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
  * This formula is further explained in the Notebook, adds multipliers based on the factors, and takes into account things like sample size and $R^2$ scores.

## Results
Using the DataFrame, I found that there were five total factors which had some connection to the odds of a comeback. More details on which factors, as well as what each factor means alongside analysis are provided in the Notebook.

## Contributing
Any constructive criticism is greatly appreciated. Feel free to let me know about issues or submit pull requests for this project.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
For any questions or feedback, please contact me at `aac@ucsb.edu`.
