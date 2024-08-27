Have you ever bought a pet simulator game, just to realize it was boring? What if your virtual pet could be considered alive? Introducing: NEURALNET-GAME (rebrand coming soon!)

Challenging the definition of "sentient" and "alive," NEURALNET-GAME uses reinforcement learning to provide a virtual pet with a virtual brain, allowing your pet to "live," which provides an incentive to keep taking care of it. 

# HOW TO RUN:
- Clone the repo to a local drive, and then install the requirements in requirements.txt to a conda environment.
- To run the game in game mode, run "python neuralnetgame" in the project directory.
- To run the game in training mode, run the program like above but with the "--train" flag.

# CLI PARAMETERS
- --train : Runs the program in training mode
- --train-duration [int] : How many episodes to train for
- --resume [str] : The name of a model file inside the models folder to resume training frome
- --report-interval [int] : How often (in steps) to report the current step and episode of the model
- --save-interval [int] : How often (in episodes) to save the model's current state
- 
- --model-name [str] : The name of a model (in the models folder) to use when in play mode. Defaults to "pretrained-model"
# TODO
- [x] Finish Gymnasium environment
- [x] Implement general TensorFlow functionality
- [x] Switch to Pytorch because general tensorflow functionality means no functionality at all because tensorflow lacks an observer library for windows
- [ ] Finetune training settings
- [ ] Comfort features
  - [x] Full click support for easier training
  - [ ] IN PROGRESS - Replayability to watch model progress
  - [x] Game element (player interaction with the model - placing food and water around the map)

