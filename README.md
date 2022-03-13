# Trading Algorithm Bot

This project creates a machine learning bot that aims to test different trading strategies and compare them by reviewing graphical and numeric data.

## Technologies

This project utilizes python 3.7 along with the following packages:

[Pandas](https://pandas.pydata.org/) 

[scikit-learn](https://pypi.org/project/scikit-learn/)

[jupyterlab](https://jupyter.org/)

This project has been constructed in a [Jupyter Lab](https://jupyter.org/) notebook entitled `machine_learning_trading_bot.ipynb`.

## Installation Guide

1. Make sure you are using python version 3.7 or greater by typing the following:

`python -V`

2. Confirm that the packages are installed by using the following code lines:

`pip install pandas`

`pip install scikit-learn`

`pip install jupyterlab`

## Usage

In order to view the project, navigate to the `machine_learning_trading_bot.ipynb` notebook in the repository directory. If you cannot find the file, simply click [here](https://github.com/MaxAcheson/module_14_challenge/blob/main/Starter_Code/machine_learning_trading_bot.ipynb) instead. If you would like to interact with the live version of the analysis, you may navigate to your cloned version of the repository in your terminal and run `jupyter lab`.

## Analysis

![Image 1](https://github.com/MaxAcheson/module_14_challenge/blob/main/Images/image_7.png)

This first figure shows that, over an initial 3 month training period, the predicted trading strategy performed slightly better than the actual returns. 

![Image 2](https://github.com/MaxAcheson/module_14_challenge/blob/main/Images/image_6.png)

This second figure displays a comparison of strategy vs. actual returns over a 2 month moving window. The prediction is quite close to the actual returns in the end, however the strategy returns exhibit a more volatile trajectory. 

![Image 3](https://github.com/MaxAcheson/module_14_challenge/blob/main/Images/image_8.png)

This third figure displays the data along a 6 month training window. The data suggests that the returns remained similar until the few years of data, where the actual returns were noticeably higher than the strategy yields in 2019, but then this trend reversed for the entirety of 2020.

Conclusion: The 3 month training window appears to offer the least volatile returns.

The following 3 figures display strategy vs. actual trading returns using 3 unique sets of short and long SMA values. 

![Image 4](https://github.com/MaxAcheson/module_14_challenge/blob/main/Images/image_4.png)

![Image 5](https://github.com/MaxAcheson/module_14_challenge/blob/main/Images/image_3.png)

![Image 6](https://github.com/MaxAcheson/module_14_challenge/blob/main/Images/image_9.png)

The data from the 3 figures above suggests that a short window of 7 days with a 150 day long window presents the most consistent, least volatile returns. As a result, I recommend using a short/long window of 7/150.

![Image 7](https://github.com/MaxAcheson/module_14_challenge/blob/main/Images/image_2.png)

This final figure shows that the LRM strategy has a strong dip in returns during 2020. My recommendation is to stick with the SVM strategy in order to expect the most conistent returns for the future. 

## Contributors

Max Acheson

maxacheson@gmail.com

[LinkedIn](https://www.linkedin.com/in/max-acheson-75093a19a/)

## Licenses

MIT License

Copyright (c) [2021] [Max Acheson]

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

