We need to sort a dataframe by the values in a column, Use the pandas sort_values function During data analysis and exploration, it’s often useful to sort a DataFrame by a particular column or set
of columns. The by argument to sort_values takes a list of columns by which to sort the DataFrame and will sort based on the order of column names in the list.
By default, the ascending argument is set to True - so it will sort the values lowest to highest. If we wanted the oldest passengers instead of the youngest, we could set it so False
