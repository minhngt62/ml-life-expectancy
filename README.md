![image](https://user-images.githubusercontent.com/86721208/164498440-5f171021-c58f-470f-863c-dbb5b0325ae4.png)

# Business Analytics on Life Expectancy (WHO)

The Global Health Observatory (GHO) data repository under World Health Organization (WHO) keeps track of the health status as well as many other related factors for all countries The datasets, including [Life Expectancy (WHO)](https://www.kaggle.com/datasets/kumarajarshi/life-expectancy-who?fbclid=IwAR155pP1NyfjMQUfIxPN-s6oD06RWTAX9X0Gv5wkvPdVlUgP__Us2VNxujE), are made available to public for the purpose of health data analysis. The dataset [Life Expectancy (WHO)](https://www.kaggle.com/datasets/kumarajarshi/life-expectancy-who?fbclid=IwAR155pP1NyfjMQUfIxPN-s6oD06RWTAX9X0Gv5wkvPdVlUgP__Us2VNxujE) related to life expectancy, health factors for 193 countries has been collected from the same WHO data repository website and its corresponding economic data was collected from United Nation website.

Since the observations of this dataset are based on different countries, it will be easier for a country to determine the predicting factor which is contributing to lower value of life expectancy. This will help in suggesting a country which area should be given importance in order to efficiently improve the life expectancy of its population.

Then, we are now participating in exploring this dataset using EDA and ML technique in order to deduce the factors that affects the life expectancy the most, then utilizing the information obtained to predict the life expectancy given social and health factors of a area.

- More information about the dataset and the related issues can be found on: [Life Expectancy (WHO)](https://www.kaggle.com/datasets/kumarajarshi/life-expectancy-who?fbclid=IwAR155pP1NyfjMQUfIxPN-s6oD06RWTAX9X0Gv5wkvPdVlUgP__Us2VNxujE).
- Refer to the detailed document of what we have done so far: [`./report/report.pdf`](https://github.com/minhngt62/ml-life-expectancy/blob/main/report/report.pdf)

---
### Setup

- Install Python (over 3.6): https://www.python.org/downloads/
- Install necessary libraries to rerun the notebooks:
  - `pip install pandas`
  - `pip install matplotlib`
  - `pip install seaborn`
  - `pip install notebook`
  - `pip install scikit-learn`
  - `pip install catboost`(For the notebook `Trees_and_ensembles.ipynb` only)
  - `pip install h2o` (For the notebook `Trees_and_ensembles.ipynb` only)
  
  After that, if some base components are not installed yet, `numpy` and `scipy` should then be installed by:
  - `pip install numpy`
  - `pip install scipy`
  
---
### Compile & Run
- Run Jupyter Notebook from the root of the directory of source code - Reference: [Running the Jupyter Notebook](https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/execute.html)
- Open the notebooks you want to rerun and run the desired cells
  - Some cells will require the other cells to be run first so my suggestion is to run cells sequentially. Also, if there is something that does not follow the normal sequential run, it is always noted in the head comments of each cell or through text cell with the prefix "Caution".
- For the notebook `Trees_and_ensembles.ipynb` only, we may suggest everyone run it on google colab (`h2o` installed) since `h2o` can be difficult to be installed and set up manually.

---
### Contributors

- Nguyễn Tống Minh
- Nguyễn Xuân Thái Hòa
- Ngô Thị Thu Huyền
- Nguyễn Nhật Quang
