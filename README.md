# Learning the statistics of pain: computational and neural mechanisms.

## Introduction

This is the code used for behavioural and neuroimaging data analyses in the paper 'Learning the statistics of pain: computational and neural mechanisms' (submitted). 
<!-- An older preprint version of the paper can be found on biorxiv: [Endogenous controllability of closed-loop brain-machine interfaces for pain](https://www.biorxiv.org/content/10.1101/369736v1). -->

## Usage
For behavioural data analysis, the following directories contain code for specific use. 
* data (behavioural data from fMRI sessions)
* model_fit (fit models to behavioural data)
* model_comparison (performs model comparison)
* model_gen (generate parametric modulators for fMRI analyses using fitted model parameters)

For imaging analysis, 
* imaging (1st and 2nd level analysis scripts based on nipype)
* imaging_plot (result visualisation using nilearn)

Please change data paths and parameter settings within the scripts.

## Requirements
To run the code for behavioural analyses, you will need the following:
* MATLAB
* [Minimal Transition Probs Model package](https://github.com/florentmeyniel/MinimalTransitionProbsModel)
* [VBA toolbox](https://mbb-team.github.io/VBA-toolbox/)

For imaging analyses, the required python packages are listed in `requirements.txt`. Nipype scripts are best run inside its docker/singularity container, a useful tutorial can be found [here](https://miykael.github.io/nipype_tutorial/).

