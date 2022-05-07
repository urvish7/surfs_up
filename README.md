# surfs_up
## Overview of the Analysis

The purpose of the project is to review patterns in Hawaii for opening a surf and ice-cream shop.The Analysis we does in this module was appreciated by W. Avy however it seems he wants more information about the temperature trends before opening the surf shop. Specifically, he wants temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.

The files that are handy for this project are:
 -  [SurfsUp_Challenge.ipynb](https://github.com/urvish7/surfs_up/blob/main/SurfsUp_Challenge.ipynb)
 -  [The SQLite Database](https://github.com/urvish7/surfs_up/blob/main/hawaii.sqlite)

## Deliverable 1: Determine the Summary Statistics for June

In this Analysis part we will use the Panda,SQL Alchemy, Python functions and methods to filter the date column in the hawaii.sqlite to retrive all the temperature for the month of the june. 

This Analysis have following steps:
 - Retrieve the June temperatures from the date column of the Measurement table 
 - Convert the June temperatures to a list
 - Generate the summary statistics for the June temperatures DataFrame.
 
![](https://github.com/urvish7/surfs_up/blob/main/Resources/June_Temp.png)


## Determine the Summary Statistics for December

In this Analysis part we will use the Panda,SQL Alchemy, Python functions and methods to filter the date column in the hawaii.sqlite to retrive all the temperature for the month of the December

This Analysis have following steps:
 - Retrieve the December temperatures from the date column of the Measurement table 
 - Convert the December temperatures to a list
 - Generate the summary statistics for the June temperatures DataFrame.


![](https://github.com/urvish7/surfs_up/blob/main/Resources/December_Temp.png)

## Results

 - The Average temperature of the December is more compare to the June temperature.
 - The Maximum temperature that occured in June was 85 degrees while December is at 83 degrees. 


## Summary

In the nutshell, the june temperature is more concentrated between 70 to 80 degrees while, December temperature is more concentraed between 65 and 75 degrees. From the Analysis we can say that the June month is warmer compare to the December month. 

![June_graphs](https://github.com/urvish7/surfs_up/blob/main/Resources/June_graph.png)

![December_graph](https://github.com/urvish7/surfs_up/blob/main/Resources/December_graph.png)

