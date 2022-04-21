![image](https://user-images.githubusercontent.com/86721208/164498440-5f171021-c58f-470f-863c-dbb5b0325ae4.png)

# Machine Learning on Life Expectancy (WHO)
<p align="center">
 <img src=https://user-images.githubusercontent.com/86721208/164503714-4cffbfb7-b8c2-48b0-b922-4e4fe7fca871.png>
</p>

The Global Health Observatory (GHO) data repository under World Health Organization (WHO) keeps track of the health status as well as many other related factors for all countries The datasets, including [Life Expectancy (WHO)](https://www.kaggle.com/datasets/kumarajarshi/life-expectancy-who?fbclid=IwAR155pP1NyfjMQUfIxPN-s6oD06RWTAX9X0Gv5wkvPdVlUgP__Us2VNxujE), are made available to public for the purpose of health data analysis. The dataset [Life Expectancy (WHO)](https://www.kaggle.com/datasets/kumarajarshi/life-expectancy-who?fbclid=IwAR155pP1NyfjMQUfIxPN-s6oD06RWTAX9X0Gv5wkvPdVlUgP__Us2VNxujE) related to life expectancy, health factors for 193 countries has been collected from the same WHO data repository website and its corresponding economic data was collected from United Nation website.

Since the observations of this dataset are based on different countries, it will be easier for a country to determine the predicting factor which is contributing to lower value of life expectancy. This will help in suggesting a country which area should be given importance in order to efficiently improve the life expectancy of its population.

Then, we are now participating in exploring this dataset using Machine Learning technique in order to deduce the factors that affects the life expectancy the most, then utilizing the information obtained to predict the life expectancy given social and health factors of a area. 

More information about the dataset and the related issues can be found on: [Life Expectancy (WHO)](https://www.kaggle.com/datasets/kumarajarshi/life-expectancy-who?fbclid=IwAR155pP1NyfjMQUfIxPN-s6oD06RWTAX9X0Gv5wkvPdVlUgP__Us2VNxujE).

# Setup
- Install Python (over 3.6): https://www.python.org/downloads/
- Install necessary libraries:
  - `pip install pandas`
  - `pip install matplotlib`
  - `pip install notebook`
  - `pip install sklearn`

- For any member, please create your own directory (your_name, lowercase_underscore) in the repo and put all your work in that directory only (avoid conflict):
<p align="center">
 <img src=https://user-images.githubusercontent.com/86721208/164508594-5e09e5d0-789e-4f20-a323-fb8aedeca7ce.png>
</p>

- For any member, please follow the notebook's setting below:
  ```
  # Python ≥3.5 is required
  import sys
  assert sys.version_info >= (3, 5)

  # Scikit-Learn ≥0.20 is required
  import sklearn
  assert sklearn.__version__ >= "0.20"

  # Common imports
  import numpy as np
  import os

  # to make this notebook's output stable across runs
  np.random.seed(42)

  # To plot pretty figures
  %matplotlib inline
  import matplotlib as mpl
  import matplotlib.pyplot as plt
  mpl.rc('axes', labelsize=14)
  mpl.rc('xtick', labelsize=12)
  mpl.rc('ytick', labelsize=12)

  # Where to save the figures
  PROJECT_ROOT_DIR = "."
  USER_ID = ""  # YOUR NAME, lowercase_underscore
  NOTEBOOK_ID = "ensemble" # CUSTOMIZE YOURSELF, PLEASE STICK WITH lowercase_underscore
  IMAGES_PATH = os.path.join(PROJECT_ROOT_DIR, USER_ID, "images", NOTEBOOK_ID)
  os.makedirs(IMAGES_PATH, exist_ok=True)
  
  # please use this function to save figure (if you need to save image only)
  def save_fig(fig_id, tight_layout=True, fig_extension="png", resolution=300):
      path = os.path.join(IMAGES_PATH, fig_id + "." + fig_extension)
      print("Saving figure", fig_id)
      if tight_layout:
          plt.tight_layout()
      plt.savefig(path, format=fig_extension, dpi=resolution)
  ```

# Contributors
- Nguyễn Tống Minh
- Nguyễn Công Đạt
- Nguyễn Xuân Thái Hòa
- Ngô Thị Thu Huyền
- Nguyễn Nhật Quang
