# Intro

This is a sandbox repo with code to play around [Synthea](https://synthetichealth.github.io/synthea/)  data.

# Fetch data

We can download and extract the available data in `CSV`

```sh

mkdir data
cd data

wget https://synthetichealth.github.io/synthea-sample-data/downloads/synthea_sample_data_csv_apr2020.zip

unzip synthea_sample_data_csv_apr2020.zip

```

The corresponding data dictionary can be found [here](https://github.com/synthetichealth/synthea/wiki/CSV-File-Data-Dictionary).
Synthea data.


# Rendering reports

To render the `Quarto` reports, we can use the RStudio **render** button or call directly quarto from the command line

```sh

quarto render 01_first_exploration.qmd

```

Information about `Quarto` can be fond [here](https://quarto.org/docs/get-started/).
