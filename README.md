This repository contains the project work carried out by Group 18 in the MLOps course taught at DTU ([course website](https://skaftenicki.github.io/dtu_mlops/)). Group 18 consists of: Sitong Chen, Yaxin Luo, Xiaofu Chen. 

1. **Overall goal:**
The project is a Movie Recommendation System based on the Latent Factor Model (LFM) algorithm. This system is designed to provide movie recommendations to users.
2. **Framework:**
The model SVDModel is a subclass of tf.keras.Model, indicating the use of TensorFlow's Keras API. This is a high-level API for building and training deep learning models in TensorFlow.
3. **Deep learning models used?**
The SVD Model is designed for a movie recommendation system. It predicts movie ratings based on user and item (movie) interactions.

## Project flowchart
[Alt text](reports/figures/Machine learning operations pipeline.png?raw=true  "Flowchart")

## How to install
Installing the project on your machine should be straighforward although Pytorch Geometric can cause some trouble. Clone the repo:
```bash
git clone https://github.com/Yaxin9Luo/MLops_project_Group18.git
```
Install requirements, preferably in seperate virtual environment:
```bash
pip install -r requirements.txt
```

## How to run
Running the training locally can be done with calling the `train_model.py` from the terminal:
```bash
python lfm/scripts/train_models.py
```
And to predict with the model use
```bash
python lfm/scripts/test_models.py
```
