# 2023-NYCU-AI-final-team16
The AI final project for Team 16 for 2023 NYCU Intro-to-AI class

Topic: Creature Creator via Reinforcement Learning 

# Overview of our task
  This repo is written for our Final Project of AI class, we implement a creature creator with Unity, we can draw your creature with it and train our creatures on it.
# Get  Started
## Packages and Environments we recommend to use
Python, version==3.7.16

Unity, version==2021.3.20f1

and use
```pip install requirements.txt```

## Unity Part
  (Please download our AI_Final file from Google Drive via to_AI_Final.txt, the file is too big. qq)
  Draw Creatures on your own with our drawing tool!
  ![image](https://github.com/TianYueh/2023-NYCU-AI-final-team16/blob/main/man.png)
  
## Training
  Run DDPGNotebook.ipynb to train your creature!
  Here is a GIF for successful training:
  ![image](https://github.com/TianYueh/2023-NYCU-AI-final-team16/blob/main/demo.gif)
  
  Also it might fail...
  ![image](https://github.com/TianYueh/2023-NYCU-AI-final-team16/blob/main/demo2.gif)
  
  Note that you should put your build file and ddpg_agent.py, and model.py together in the same layer, and you should rename the path in the ipynb file.
  
## Sample Results
  Training with PPO(Proximal Policy Optimization):
  ![image](https://github.com/TianYueh/2023-NYCU-AI-final-team16/blob/main/mil.png)
  Training with DDPG(Deep Deterministic Policy Gradient):
  ![image](https://github.com/TianYueh/2023-NYCU-AI-final-team16/blob/main/ddpg.png)




