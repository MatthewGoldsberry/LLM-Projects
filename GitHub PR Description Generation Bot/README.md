# GitHub Pull Request Description Generation Bot

### Project Overview

The GitHub Pull Request Description Generation bot aims to automate the process of generating detailed, clear, and concise descriptions for GitHub Pull Requests (PRs). The bot will analyze the diff (with potential to take additional context) of a PR and update its descriptions with a professional summary that explains the purpose, changes, and impact on the PR.

This project also serves as a hands-on learning opportunity, allowing me to take on my first LLM project.

### Project Goal:

1. Build a bot that utilizes LLM capabilities to evaluate the code diff of a PR (and maybe additional context) and generate a detailed description that adheres to best practices for technical documentation.\
2. Further knowledge and skills through experiential learning, helping me understand/ implement the following:
   1. Fine-Tuning pretrained LLMs for specific tasks.
   2. Integrating LLMs with external APIs
   3. Deploying AI-based automation in real-world applications.

### Project Methodology:

##### 1. Explore existing pretrained LLMs and whether fine-tuning is necessary for this task.
##### 2. Modular Implementation via Jupyter Notebooks

Each component of this project will be tackled in a standalone Notebook to ensure clarity and focus, and allow for easier learning.

###### 1. Pretained LLM Exploration:
* Experiment with existiing models on Hugging Face
* Choose one and implement in `base_pretrained_model.ipynb`.
###### 2. Implement Capabilities to Grab Data from GitHub:
* Using the GitHub API implement ways to obtain information on a PR, with a focus on grabbing diff data.
* Implement in `base_github_pr_inter.ipynb`.
###### 3. LLM Fine-Tuning:
* Create dataset(s) to train the LLM on to improve its PR descriptions.
* Fine-Tune the model on those datasets to ensuer accurate AND context aware descriptions.
* Implement in `base_training_model.ipynb`.
###### 4. Evaluate and Validate:
* Test model's outputs on real-world PR diffs to ensure relevance and readbility.
* Iteratively refining the model based on feedback
* Implement in `base_testing_trained_model.ipynb`.
###### 6. Integrate and Automate:
* Combine all of the components of the previous files into a pipeline.
* Integrate that pipeline into GitHub, building a bot that updates PR descriptons automatically upon execution.

### Project Limitations

This project is constrained by my limited hardware resources for LLM development. With limited RAM and the absence of a high-performance GPU, the size of models and datasets I can effectively work with is restricted. While these limitations impose certain constraints, I view them as an opportunity to learn and develop strategies for maximizing the potential of limited resources when working with LLMs.


### Expected Learning Outcomes

Through this project, I aim to:

1. Develop a comprehensive understanding of LLMs, including fine-tuning and task-specific customization.
2. Gain hands-on experience working with the GitHub API for automation purposes.
3. Enhance my ability to structure and execute complex projects by breaking them into manageable tasks.
4. Build a functional tool that addresses a common developer pain point, with potential for real-world application.

### Results:

Still in work