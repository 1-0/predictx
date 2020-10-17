# predictx
Prediction test project
## Getting Start
### Installation
- Install or/and check installed git and python3:
  - `git --version`
  - `python3 --version`
- `python3 -m pip install -U pip`
- `python3 -m pip install -U virtualenv`
- `python3 -m pip venv predictx`
- `cd predictx`
- `source ./bin/activate` in *nix OS or `.\Scripts\activate.bat` in Windows OS
- `git clone https://github.com/1-0/predictx`
- `mv predictx src`
- `cd src`
- `python3 -m pip install -r Requirements.txt`
### Usage
- `python3 -m jupyter notebook ./data_analysis.ipynb` for  data analysis
----------
## Test task
In internship time you will solve a couple of different tasks in the field of computer vision.
This task will give you a basic understanding of techniques and frameworks which we use on a daily basis to solve similar problems.
### Dataset:
https://www.kaggle.com/c/data-science-bowl-2018/data
## Goal:
Build a ​ semantic​ segmentation model with UNet architecture using Keras. Please note, that the test task is not instance segmentation!
### Results:
As results you must provide a link to your GitHub repo that will include:
1. `README.md` with a description of techniques that you have used to solve the task and instructions for running training and prediction.
2. `Requirements.txt`
3. `Train.py` - the script that will run training.
4. `Predict_masks.py` - a script that will run inference on test data.
5. Jupyter notebook with exploratory data analysis.
6. Any other scripts with datasets, models, etc...
### Main requirements
1. Completely working code.
2. It must be easy to set up the environment and run it.
3. Dice Score score at each image https://en.wikipedia.org/wiki/S%C3%B8rensen%E2%80%93Dice_coefficient - 0.4
### Useful links
1. Kaggle competition kernels will help you to understand data and find some insights.
2. https://adeshpande3.github.io/adeshpande3.github.io/A-Beginner%27s-Guide-To-Understanding-Convolutional-Neural-Networks/
3. UNET paper ​ https://arxiv.org/abs/1505.04597
4. Semantic vs instance segmentation https://www.quora.com/What-are-the-differences-between-semantic-segmentation-instance-detection-and-object-proposal
