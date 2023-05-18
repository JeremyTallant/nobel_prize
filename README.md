# A Visual History of Nobel Prize Winners
Description
The Nobel Prize is perhaps the world's most well known scientific award. Every year it is given to scientists and scholars in chemistry, literature, physics, medicine, economics, and peace. The first Nobel Prize was handed out in 1901, and at that time the prize was Eurocentric and male-focused, but nowadays it's not biased in any way. Surely, right?

Well, let's find out! What characteristics do the prize winners have? Which country gets it most often? And has anybody gotten it twice? It's up to you to figure this out.

The [dataset](https://www.kaggle.com/datasets/nobelfoundation/nobel-laureates) used in this project is from The Nobel Foundation on Kaggle.
## Usage
Clone this repository and open the Jupyter notebook file (`*.ipynb`) in a Jupyter environment with Python kernel support. Make sure to install the required packages such as `pandas`, `numpy`, `seaborn`, and `matplotlib`. You can do this by running the following commands in a code cell within the notebook:
```python
!pip install pandas numpy matplotlib seaborn
```
Once the packages are installed, run the code cells in the notebook to generate the plots and analyses.

If you don't have a Jupyter environment set up, you can install Jupyter Notebook and the Python kernel using the following steps:

1. Install Jupyter Notebook by following the instructions on the [official Jupyter website](https://jupyter.org/install).

2. Ensure you have Python installed. If not, you can download and install Python from the [official Python website](https://www.python.org/downloads/).
## Contents
1. **The most Nobel of Prizes:** Load the required libraries and the Nobel Prize dataset.
2. **So, who gets the Nobel Prize?:** Count up the Nobel Prizes. Also, split by `sex` and `birth_country`
3. **USA dominance:** Create a DataFrame with two columns: decade and proportion of USA-born Nobel Prize winners that decade.
4. **USA dominance, visualized:** Plot the proportion of USA born winners per decade.
5. **What is the gender of a typical Nobel Prize winner?:** Plot the proportion of female laureates by decade split by prize category.
6. **The first woman to win the Nobel Prize:** Extract and display the row showing the first woman to win a Nobel Prize.
7. **Repeat laureates:** Extract and display the rows of repeat Nobel Prize winners.
8. **How old are you when you get the prize?:** Calculate and plot the age of each winner when they won their Nobel Prize.
9. **Age differences between prize categories:** Plot how old winners are within the different price categories.
10. **Oldest and youngest winners:** Pick out the rows of the oldest and the youngest winner of a Nobel Prize.
11. **You get a prize!:** Assign the name of the youngest winner of a Nobel Prize to `youngest_winner`. The first name will suffice.