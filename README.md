# data-analysis

Import json file containing fitted positioning data.

Read data into a pandas dataframe, and rebuild to get rid of nested dictionaries, for filtering.

For each mac address, divide time sorted positions in bins to create a 2d density histogram for each mac.

Use a sliding moving window, of variable length and step size, and divided in variable number of weighted subwindows.

