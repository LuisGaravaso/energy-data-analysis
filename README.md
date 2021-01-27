# energy-data-analysis
This repository is a personal project to analyze countries' energy investments.
Since I am Brazilian, I focus my analysis in Brazil, but you are welcome to clone the repository and change the `Location` of your choice.
This project is only for research/fun purposes, but I intend to expand it and make something useful for the world with it someday.

## Table of contents
* [Installation](#Installation)
* [Technologies]($Technologies)
* [Usage](#Usage)
* [Results](#Results)
* [Collaborating](#Collaborating)
* [Future Work](#Future-Work)

## Technologies

This project uses:

* Python 3.8.7

And the packages:

* Numpy 1.19.2
* Pandas 1.2.1
* MatplotLib 3.3.2
* Seaborn 0.11.1

## Installation

```
$ git clone https://github.com/LuisGaravaso/energy-data-analysis
```

## Files

Once you clone the repo, you'll get the following files:

* Energy.ipynb : Jupyter Notebook with the Data Analysis
* enerdata_energy_statistical_yearbook_2018.xlsx: .XLSX file contaning the data.
* LICENSE : MIT License
* README : This README

If you wish, go to [World Energy Statistics](https://yearbook.enerdata.net/) and get an updated version of the .XLSX file.
This file will be updated in future works.

## Usage

Just open the Jupyter Notebook and use the predefined functions `etl` and `plotting_prep` with a `Location` of your choice.

## Results

This versions' analysis tried to answer the following questions:

1. Are we, Brazilians, investing in Energy generation?
2. Are we getting more efficient in our production?
3. Brazil is well known for its renewable energy sources, but are we still on the podium?
4. Which other countries should we look to?

And the answers were:

1. Yes, but not doing it properly
2. The results were ambiguous therefore require further analysis
3. We lost our position recently to Colombia and New Zealand
4. We should definitely look to Norway, New Zealand and Colombia

Check the [Medium Post](https://medium.com/@luisgaravaso/this-will-make-us-brazilians-rethink-our-energy-investments-525b9c49a087) about it.

## Collaborating

Send me a connection request on Linkedin: https://www.linkedin.com/in/luisgaravaso/
That way you can send me files, urls or advice on the analysis.

## Future Work

1. Gathering more data on Brazil to predict future renewables share
2. Get more info on **Colombia** and **New Zealand** to see how they have been investing lately
