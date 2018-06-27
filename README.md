# Calliope

a data integrity tool

Humans will probably have to check for data integrity by hand, because it's so complicated. But we can provide tools to make it easier to hone in on trouble spots, through statistics, sampling, and visualization.

- statistical analysis for outliers and presentation of outlier values and rows
- check for membership of dimensions columns in a category
- check for unexpected null values
- automatically generate visualizations of data
- randomly sample rows for visual inspection

see also: xsv provides basic stats for csv.

## Components
- CLI tool
- GUI

## Example Usage

Histogram of values, user can see distribution, then click on an outlier bin and see the rows that contributed to that bin.
