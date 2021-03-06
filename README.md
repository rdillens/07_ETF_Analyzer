# ETF_Analyzer
Financial database and web application using SQL, Python, and Voila to analyze the performance of a hypothetical FinTech ETF.

**The application is published [here](http://rdillens.github.io/07_ETF_Analyzer) as a github project page, try it yourself!**

---
## Installation Instructions
- ### Install [Selenium](https://selenium-python.readthedocs.io/) to use [bokeh.io](https://docs.bokeh.org/en/latest/) image export functions
```shell
conda install selenium
```
and
```shell
conda install -c conda-forge firefox geckodriver
```
- ### To publish this notebook as HTML use [Voila](https://voila.readthedocs.io/en/stable/index.html):
```shell 
conda install -c conda-forge voila
```

---
## Usage
To run the notebook from the command line use:
```shell
voila etf_analyzer.ipynb
```
![Run from command line](Images/Voila_01.gif)
![Load from localhost](Images/Voila_02.gif)
![Explore in browser](Images/Voila_03.gif)

---
## Examples
![PYPL Daily Returns](Images/PYPL_Daily_Returns.png)
![PYPL Cumulative Returns](Images/PYPL_Cumulative_Returns.png)
![PYPL Daily Returns](Images/ETF_Portfolio_Cumulative_Returns.png)

---
## Contributors
Starter code was given in the Rice FinTech Bootcamp and all modifications were made by Remy Dillenseger.

---
## License
This project is licensed under the MIT License.
[Click Here](https://github.com/rdillens/05_Financial_Planner/blob/main/LICENSE) for more information.