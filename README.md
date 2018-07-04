# Custom Template

## Basic Requirements


- matplotlib
- numpy
- pandas
- pandas_summary
- sklearn
- pyarrow
- scipy
- seaborn
- sqlalchemy
- tqdm
- wurlitzer
- yaml

## Custom tools pandas

- imputer; Assign missing values using K-means. need improvments
- combine_date; combine date in  a single value
- expand_date; expand date into weekday, day, month , year, etc...
- to_cats; Apply category to all string columns
- apply_cats; apply category using a template
- fix_missing; assignation of meadian to missing values, quick
- numericalize; Changes the column col from a categorical type to it's integer codes.
- scale_vars; scale values from -1 to 1
- proc_df; quick and dirty preprocessing for dataframes