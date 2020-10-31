This repository contains files related to a masters project I did while studying at the University of Freiburg.

The aim of the project was to study the predictive performance of different computational models for spatial reasoning. I studied how well different models predict individual responses.

In my project, I compared models created by cognitive scientist and machine learning solutions I coded myself. However, here I have only included files for the models that I created myself, as the cognitive models were provided by other people who had worked at the research group.

Benchmarking is done with the help of the CCOBRA framework.

## To run the benchmark:

* First, make sure you have python and required libraries installed.
    * Required libraries: ccobra, NumPy, Pytorch, auto-sklearn, tqdm, pandas

	   
* To run the benchmarks:
    * On linux or ubuntu for windows you can use the shell script: runBenchmarks.sh
    * Othwerwise, you can run benchmarks individually with the command: ccobra benchmarkname.json
    * NOTE: Running the benchmark in its entirety takes several hours.

* The full results of the benchmark can also conveniently be viewed from the results folder, which means running the benchmark is NOT required.



## Current status
The benchmark is ran on 4 different datasets, which all contain subject data from different spatial relational reasoning tasks.

Here, I have only included the models that I worked on myself.

* Baseline models:
    * Random guess (all benchmarks)
    * Most Frequent Answer (all benchmarks)

* Machine learning models:
    * Multilayer perceptron (MLP) 
    * Recurrent neural network (RNN)
    * Recurrent neural network with LSTM cells (LSTM)
    * AutoML 


## Results

Full results of the benchmark are provided in the results folder. 