==============================
LEXICON
==============================

## Scenario

A scenario is constituted by the following set :

	- Input
	- Model
	- Output

It defines a well defined trajectory for a nuclear fleet evolution on a given time frame.

## Input

Self consistant set of input parameters and factors that allows the complete description of the simulated scenario.

### Input variable

An input variable is a factor that is observable in a real fleet and has to be defined by the user. Input variable can be ordonnated: 

	- Time range
	- Cycle units (facilities and connections)
	- Facilities parameters (BU, cooling time, tail assets, power, etc.)
	- Facilities evolution
	- Model hypothesis

Or not ordonnated:

	- separation demand or one line
	- fifo lifo

### Input parameter

An input factor is not measurable in the real fleet and has to be estimated.

	- Reactivity threshold for maximal burn up
	- Time steps
	- ...?
	
## Model

Represents the computationnal tool that processes the input and performing output calculation according to defined hypothesis. Here's a non exhaustive list of models : 

	- CYCLUS
	- CLASS
	- COSI

### Model simplifications

	decay or not
	depletion or not

## Output

An output is composed by raw data calculated by the model according to input and hypothesis of the scenario.

## Design of experiment

Design Of Experiment is the range of variation for Input variables and parameters


## Metric
  Understandable values





