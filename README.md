# ECRI-RCDS-Hackathon 2025
Annual Hackathon workshop organized by RCDS team at ECRI, Imperial

## Theme - Algorithm Optimization and Sustainability

## Pre-Session Work

In order to follow this hackathon, you will need to have a [GitHub](https://github.com/home) account. If you don't have one, you can sign up for free. You will also need to enable [Github Copilot](https://github.com/features/copilot) in your Github account. This is, by default, a paid-for feature, but it is also available for free to students and educators through Github Education. You can register for this [here](https://github.com/edu). It may take a few days for your application to be approved, so it is best to apply at least a week in advance.

There are several Jupyter notebooks (the files with the extension `.ipynb`) present in this  repository. You may review them in advance if you want to, but you aren't required to.

## Plan

time |activity|
|-----|--------|
|1000 |demos and exercises: Sparse network and optimization; features selection|
|1200 |general speaker|
|1300 |lunch break|
|1400 |speaker technical|
|1500 |hack!: feature selection and regression to achieve \ |
|     | - less runtime \ |
|     | - less memory usage \ |
|     | - less carbon emission \ |
|     | - and lower MSE|
|1630 |results and wrap up|

[Detailed Plan](plan.md)

## Sparse network

- data: facebook snap data

- Find the top 20 most connected nodes with two different methods and compare the performance

    - full matrix for the networking

    - sparse matrix for the networking

## Carbon footprint estimation

- Emissions: 

    - $$E_{total} = E_{codecarbon} * 1000 \text{  gCO}_2\text{e}$$

    - $$E_{calibrated} = E_{total} * CPU_{percentage}$$

- code

- Generative AI usage:
    - [Use this site to estimate](https://huggingface.co/spaces/genai-impact/ecologits-calculator)

## Preliminary practice with network analyis - task 1 & 2 

### Task 1

Find number of nodes, edges, density, the longest path and the shortest path of the given Facebook social network data.

- Naïve method is loop-based BFS (breadth first search) method.

- Optimized methods are (vectorized computational method) with `networks` and `scipy.sparse` libraries.

### Task 2

- Based on estimation of emissions for both naïve method and optimized methods, observe the sustainability of the code.

## Task 3 & 4

## Main task 5 - Configure codespace

- Allow all users to have a unify environment to run code on codespaces. A Codespace is a development environment hosted by GitHub directly from a repository. 

- First, `fork` this repository to your own GitHub.

- Requirements for the codespaces:

    - Install required Python libraries: pandas==2.2.2, numpy==1.26.4, scikit-learn==1.5.2, psutil==6.0.0, codecarbon==3.0.2

    - Activate copilot as AI assistant.

    - Need to create a JSON file `.devcontainer.json` or `devcontainer.json` in the sub-dir `.devcontainer`.

        - Key tags include:

            - "image": Choose the base container image to build the environment. In this case, please use "mcr.microsoft.com/devcontainers/python:3.10"

            - "extensions": Allow to activate extensions for the codespaces, for example, copilot.

            - "postCreateCommand": Allow to install required libraries for Python.

- Test your GitHub codespace

To use this, you will need to be signed into a GitHub account. To open the Codespace, click the **green `Code`** button at the top right of the repository. Make sure you're in the `Codespaces` tab and click the `Create New Codespace on Master` button. This will create a Codespace of your own. This will take a minute or so to initialise. You may be asked to reload the page. If so, do reload the page. If the Codespace seems to get stuck loading, reloading the page can often fix the problem.

Once your Codespace has initialised, it will remain associated with your GitHub account for around a month, when it will expire. Your Codespace will be given a name like "fuzzy-barnacle" so you can identify it. To reopen it on a future occasion, click the **green `Code`** button again, then select the Codespace, click `Open`, then `Open in Browser`.

To download the content of the files within the Codespace, open the Files tab on the left, select the files, right click and click `Download` button. Alternatively, if you're familiar with GitHub, you can open the source control tab on the left, you can commit and push changes. This will fork the repository with your changes. Either of these options will allow you to keep a copy of the course notes with your solutions to the exercises, etc.
