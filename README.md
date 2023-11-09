# my-duckietown
The duckietown project file for COMP3414 Experiential Learning on Artificial Intelligence and Robotics, only pytorch ddpg part.

Rebuilt the whole package with the latest suggested template in slack

Make sure that you follow the installation procedures in the gym-duckietown page before using this package

Link: https://github.com/duckietown/gym-duckietown/tree/master

## Usage

```
git clone https://github.com/mmmmmm44/my-duckietown.git
cd my-duckietown
```

Then run the below for training

```
python3 train_reinforcement.py
```

## Others
Feel free to modify the hyper-parameters in the train_reinforcement.py

Also can modify the image preprocessing part in utils/wrappers.py

Update a tiny bit of codes so that it can run in colab

Note that colab will not automatically save things, so remember to download your training and model code for further reference.
