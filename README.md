This repo implements a novel approach to shielding for autonomous agents (currently only RL agents are supported). It contains two examples: Game Of Drones and Water Tank. The first has a predator drone pursuing a prey drone. There are various experiments that can be carried out, chosen by setting their corresponding flags in the config_gd.py file (GEOFENCING, DOING_OBSTACLES, DOING_BOUNDED, any subset of these flags can be chosen). The second implements shielding for a water tank controller. To install and run do the following:

"python -m venv venv"  
"source venv/bin/activate"  
"source set setLxSHPYTHONPATH"  
"pip install -r requirements.txt"  
"cd src"  
"python experiment.py"
