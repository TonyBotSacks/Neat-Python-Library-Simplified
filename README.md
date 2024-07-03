# Neat-Python-Library-Simplified

A small python library for a more compact application of neat-python.

# Instructions

    pip install neat-python

Add the Neat.py file into the correct directory

Import the simplified library with:

    from Neat import Agents

# Syntax

    agents = Agents([number of generations], [environment], '"[name of cofiguration file]".txt', '[name of the model file].pkl')
    agents.train()

The "[environment]" must be a function that takes in observations and predicts an action. This is looped over every genome in the neat configuration file

    for genome_id, genome in genomes:
        net = neat.nn.FeedForwardNetwork.create(genome, config)

        reset = False
        while not reset:

        ########################
        ########################
        ########################

        reset = True    
