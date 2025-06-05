# ECRI-RCDS-Hackathon 2025
Annual Hackathon workshop organized by RCDS team at ECRI, Imperial

## Theme - Algorithm Optimization and Sustainability

## Pre-Session Work

In order to follow this hackathon, you will need to have a [GitHub](https://github.com/home) account. If you don't have one, you can sign up for free. You will also need to enable [Github Copilot](https://github.com/features/copilot) in your Github account. This is, by default, a paid-for feature, but it is also available for free to students and educators through Github Education. You can register for this [here](https://github.com/edu). It may take a few days for your application to be approved, so it is best to apply at least a week in advance.

There are several Jupyter notebooks (the files with the extension `.ipynb`) present in this  repository. You may review them in advance if you want to, but you aren't required to.

## Opening a Codespace

This hackathon is designed to run inside of a [Codespace](https://docs.github.com/en/codespaces/overview). A Codespace is a development environment hosted by GitHub directly from a repository. To use this, you will need to be signed into a GitHub account. To open the Codespace, click the $\color{Green}{\textsf{Code}}$ button at the top right of the repository. Make sure you're in the `Codespaces` tab and click the `Create New Codespace on Master` button. This will create a Codespace of your own. This will take a minute or so to initialise. You may be asked to reload the page. If so, do reload the page. If the Codespace seems to get stuck loading, reloading the page can often fix the problem.

Once your Codespace has initialised, it will remain associated with your GitHub account for around a month, when it will expire. Your Codespace will be given a name like "fuzzy-barnacle" so you can identify it. To reopen it on a future occasion, click the ${\color{green}Code}$ button again, then select the Codespace, click `Open`, then `Open in Browser`.

To download the content of the files within the Codespace, open the Files tab on the left, select the files, right click and click `Download` button. Alternatively, if you're familiar with GitHub, you can open the source control tab on the left, you can commit and push changes. This will fork the repository with your changes. Either of these options will allow you to keep a copy of the course notes with your solutions to the exercises, etc.

## Main task 1 & 2 - Feature selection

- Select the most important features associated with sale price from the house price data.

- Naïve method is loop-based method to calculate the correlation of each column with the sale price. The basic naïve method is based on `scipy.stats` which lacks of vectorization, It is generally less memory-efficient and needs more time to run. This method can be improved by `corrceof()` from `numpy`.

- Optimized method is (vectorized computational method?) with `pandas` `corrwith()` function.

## Main task 3 & 4 - Sustainability

- Based on estimation of emissions for naïve method and optimized method, observe the sustainability of the code.
