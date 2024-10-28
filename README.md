# GeneticAlgorithmSchedulingProgram
This project uses a genetic algorithm to generate a schedule from a list of constraints and a dataset

This project takes in a list of constraints and a dataset containing information about rooms, facilitators, times, and overarching activities and then uses a genetic algorithm to generate random schedules and then selectively narrow down 
schedules to converge towards a solution that satisfies constraints. Additionally, mutation is used to add new information into the algorithm that was not included in its original initialization so that better solution spaces can be explored.
Selection was made using Softmax to create a probability distribution.
