# data-analysis

Import json file containing fitted Arena data.

Read data into a pandas dataframe, and rebuild to get rid of nested dictionaries, as they contain values on which we want to filter.

For each mac address, count time ordered positions in a 2d binned region of space to create a 2d pdf for each mac.
Use both non-overlapping and a sliding moving window, of variable length and step size.

