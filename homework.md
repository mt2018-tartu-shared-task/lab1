# Homework
Please, answer shortly to following questions with 1-2 sentences per question.
## 1. Digits to letters
Imagine that you modified the data generation script to contain letters instead of digits as a target. Follow the simple mapping:

```1 - a; 2 - b; 3 - c; ... 10 - j ```

The training pair then might look like this:

```1 3 2 10  ->  a c b j```

How do you think, will it be harder for the MT system to learn this mapping comparing to the digits copying task? Explain your answer.

Alternatively, you can test it in practice (generate the data and train it for some time) and provide final perplexity and accuracy scores. Try to guess why the results are as they are.

### Answer:
You answer goes here

## 2. Change a couple
We will continue to discuss hyperparameters of the MT systems in future labs, but for now you already know how to start training and do basic configuration.

1. Choose 2 arbitrary hyperparameters of the sockeye.train command and explain how they are supposed to affect the training process.
2. Choose 2 arbitrary hyperparameters of the sockeye.translate command and explain how they are supposed to affect the translation process.

Alternatively, you can test it in practice. Try to guess why the results are as they are.

### Answer:
You answer goes here


## 3. HPC, SLURM
To run large scale models we will use University of Tartu's HPC center servers. In order to get the access to it do the following:
1. Write an email to the support@hpc.ut.ee with your university username to setup the account on HPC clusters. Indicate that you need it for this course taught by Mark Fishel.
2. Walt through the slides 1-17 of the following [intro to UT HPC presentation](https://docs.google.com/presentation/d/1XhA4YnnZ-Gzuyo-_PghMcu_X-fXe_EUhiW2bHoABwgI/edit#slide=id.g3309b08eae_0_37)
3. Submit a simple SLURM job via ```sbatch``` script that uses <1Gb of memory, loads the python module of your choice, and executes ```which python``` command. Include the content of your ```sbatch``` script and the output file below.
### Answer:
```bash
sbatch scrip goes here
```

```bash
output of the sbatch scrip goes here
```

## 4. Get ready
Split into teams of 2-3 people and write me an email that contains:

```bash
a) Team name
b) List of the team members with their email addresses and github usernames (!)
```