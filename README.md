# data-analysis

Jupyter notebook importing json file containing fitted Arena data.

The data is read into a pandas dataframe, and rebuild to get rid of nested dictionaries, as they contain values on which we want to filter.

For each mac address, time ordered positions are counted in a 2d binned region of space to create a 2d pdf for each mac.
We use both non-overlapping and a sliding moving window, of variable length and step size.

