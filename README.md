# Green Power repository 

Scheduling with green power 

## Files

- green_energy_simulator.tgz: python and R files of the simulator
- simulatorWithIntValues.tgz: smae simulator but simplified with int values
- 
coming soon: green_energy_results.tgz: R data_frame with the mean makespan and flowtime for the heatmaps

## TaskGeneration
python code to generate tasks:

- tasks.py generates tasks with random power (uniform law) and random
  processing times (exponential law) 
- fietelsohnTasks.py tasks with random power (uniform law) and random
  processing times (hypergama law from Fietelsohn's paper) 

## IntervalsGeneration
python code to generate intervals:

- interval.py generates intervals with a bell shape
- interFromTasks.py takes a set of tasks and generate a set of
  interavls that exactly matches the tasks
  
## Main:
Simulator

## Results
Obtained results 
