# MotorsportStats<br/>


## Overview:

The project consists of collecting and presenting statistical information on selected auto racing series. It includes styled tables and graphs that present selected information.

The aim of the project is to develop skills in the use of selected technologies and to deepen knowledge of data analysis and processing.

## Notebooks:

Project currently consists of three notebooks:

>
>  * <b>Indycar Calendar Importer</b> - imports Wikipedia tables from selected Indycar season article and transforms it to desired format,
>  * <b>IRL ICS Stats</b> - imports data from .csv file and depicts several statistics about wins and pole positions on specific tracks,
>  * <b>Indycar 2022</b> - imports data about 2022 Indycar season from .csv file and calculate some statistics. It involves calculating championship standings, position plots, race by race standings plot and boxplot which contains distribution of race positions of top drivers.

## Preview Images:
Following image depicts final dataframe containing Indycar Series standings.

<img src="https://github.com/kztrp/MotorsportStats/blob/main/exported_images/Indycar 2022 Standings.png" width="750" height="407" />

Race to title image depicts how many points top drivers scored in the course of the season and how general classification was changing during these events.

<img src="https://github.com/kztrp/MotorsportStats/blob/main/exported_images/Race%20to%20title.png" width="750" height="750" />

Race positions box plot shows how distributed were race positions scored by top drivers.

<img src="https://github.com/kztrp/MotorsportStats/blob/main/exported_images/Race%20places.png" width="750" height="562" />

## Prerequisites [for developers]

If you want to run these notebooks on your computer, you need to install following packages.
* emoji-country-flag >= 1.3.0
* matplotlib >= 3.5.0
* numpy >= 1.21.0
* pandas >= 1.3.5

You can also install all of required packages using pip and requirements.txt file: 
```
$ pip install -r requirements.txt
```

Then you can open specific notebook with: 
```
$ jupyter notebook filename.ipynb
```


