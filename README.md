# Regression between BMI and Blood Pressure

![Project Image]()

> 

---

### Table of Contents
You're sections headers will be used to reference location of destination.

- [Description](#description)
- [How To Use](#how-to-use)
- [References](#references)
- [License](#license)
- [Author Info](#author-info)

---

## Description
This is a project we chose to do for a class assignment. We decided we wanted to use a linear regression method on a data set from NCD Risk factor collaboration. With the data set, we wanted to find if there is a correlation between blood pressure and Body Mass Index(BMI) from every country in the world from the year 1890 to the year 2000. Since analyzing each year would take a long time, we decided to use SQL to extract only the year 1996. We tested the R^2 and shown a regression line to give support to our hypothesis of BMI and Blood Pressure. 


#### Technologies

- Juypter Notebook
- Postgres SQL
- Anaconda

[Back To The Top](#read-me-template)

---

## How To Use

#### Installation

conda install statsmodels

#### API Reference

```html
   import numpy as np
   import statsmodels.api as sm
   import statsmodels.formula.api as smf

# Load data
dat = sm.datasets.get_rdataset("Guerry", "HistData").data

# Fit regression model (using the natural log of one of the regressors)
results = smf.ols('Lottery ~ Literacy + np.log(Pop1831)', data=dat).fit()

```
[Back To The Top](#read-me-template)

---

## References
- http://www.ncdrisc.org/data-downloads-blood-pressure.html
- http://www.ncdrisc.org/data-downloads-adiposity-ado.html

[Back To The Top](#read-me-template)


---

## License

MIT License

Copyright (c) [2019] []

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

[Back To The Top](#read-me-template)

---

## Author Info

- Linkedin - [Timothy Olawuni](www.linkedin.com/in/timothyolawuni)
- Linkedin - [Alex De Mouy](www.linkedin.com/in/alexdemouy)

[Back To The Top](#read-me-template)
