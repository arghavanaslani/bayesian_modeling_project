### ANACONDA ###

Install miniconda, see : https://docs.anaconda.com/miniconda/

From a terminal, move to an appropriate folder of your choice.

Run the following command:
    conda env create -f environment.yaml
    conda activate bmcb
    python run_simple.pyc
    
A window called Agent Simulation Interface should open.
Try if everything works well:
- Click on Start Learning (2000 Trials) => This should save a file called training_history.csv
- Click on Load Stimuli Pairs CSV and select the experiment_stim_pairs_csv file then click on Run Experiment => This should save a file called experiment_results.csv





