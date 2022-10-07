# Analytics
Using pandas, matplotlib and  seaborn libraries in data analytics in the different jupyter notebooks in the repository. 
This readme is a table of contents of the notebooks. 

## Data Manipulation with Pandas
### 1. Aggregating data frames
- summary statistics: mean, median, cumulative stats
- the .agg( ) method
- dropping duplicates
- counting categorical variables
- calculating after using .groupby()
- multiple grouped summaries
- pivot tables
- filling in missing values

### 2. Creating and Visualizing dataframes 
- bar plots, line plots, scatter plots, histograms 
- list of dictionaries to a dataframe
- dictionary of lists to a DataFrame
- reading and writing CSVs using pandas

### 3. Data manipulation using pandas
- components of a dataframe
- sorting dataframe columns
- subsetting columns
- subsetting rows
- subsetting rows by categorical variables
- adding new columns to a DataFrame

### 4. Slicing and indexing dataframes
- setting and removing indexes
- subsetting with .loc[ ]
- setting multi level indexes
- sorting by index values
- slicing and subsetting with .loc( ) and iloc( )
- slicing time series
- subsetting by rows / columns
- creating pivot tables
- subsetting pivot tables
- calculating in pivot tables 

## Joining data with pandas
### 1. Data merging basics
- inner joins
- relationships
- one to many merge

### 2. Merging tables with different merge types
- left join
- right join
- outer join
- self join
- merging on indexes (single index, multi-index, left_on, right_on)

### 3. Merging ordered or time series data
- merge_ordered( )
- foward filling technique
- merge_asof( )
- selecting with .query( )
- reshaping data with melt 

## Data Visualization with Matplotlib
### 1. Introduction to Matplotlib
- adding data to the axes object
- customizing plots (adding markers, setting linestyle, choosing color, adding axes labels, adding titles)
- subplots
- creating small multiples with plt.subplots( )
- shared y axis

### 2. Plotting Time series data
- read data with time index
- plotting time series with different variables
- annotating time series data

### 3. Quantitative comparisons and statistical visualizations
- quantitative comparisons with barcharts
- stacked bar charts
- quantitative comparisons with histograms
- statistical plotting - errorbars
- boxplots
- quantitative comparisons with scatter plots

### 4. Sharing Visualizations
- plotting styles
- saving visualizations
- automating figures from data


## Data Visualization with seaborn
### 1. Introduction to seaborn
- introduction
- scatter plots
- count plots
- adding a third variable using hue
- setting hue order
- specifying hue colors

### 2. Visualizing Quantitative variables
- introduction to relational plots (enables you to visualize the relationship between two quantitative variables using either scatter plots or line plots.)and subplots
- scatterplot() vs. relplot()
- subplots in columns / rows / both
- wrapping cols
- ordering cols
- two factor subplots
- customizing Scatter Plots (size, point style, transparency)
- line plots

### 3. Visualizing Categorical and quantitative variables
- countplots and barplots
- boxplots
- pointplots

### 4. Customizing seaborn plots
- changing plot style and color
- changing the figure style
- changing the palette (Diverging, Sequential)
- changing the scale
- adding Titles and Labels
