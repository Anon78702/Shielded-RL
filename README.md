This repo implements a novel approach to shielding for autonomous agents (currently only RL agents are supported). It contains two examples: Game Of Drones and Water Tank. The first has a predator drone pursuing a prey drone. There are various experiments that can be carried out, chosen by setting their corresponding flags in the config_gd.py file (GEOFENCING, DOING_OBSTACLES, DOING_BOUNDED, any subset of these flags can be chosen). The second implements shielding for a water tank controller. To train the agent for either example with shielding on, set the use_shield flag to True in the corresponding config file (config_gd or confg_wt), to run without shielding, set the flag False. To install and run do the following:

"python -m venv venv"  
"source venv/bin/activate"  
"source set setLxSHPYTHONPATH"  
"pip install -r requirements.txt"  
"cd src"  
"python experiment.py" (Trains the model. To run a trained model, add "--mode run <experiment id>")
