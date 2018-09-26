# Vega_Visualizations

The visualization system contain two views: 
(1) a choropleth map on the top that shows
state boundaries and uses a sequential segmented colormap to encode the total amount of losses,
(2) a bar chart on the bottom that expresses the amount of loss with aligned horizontal position
and separates the damage type with vertical position. The marks are ordered by the loss amount
attribute that encodes the size of the bar. When no interaction is available the entire data set is
used to generate the two views. 

The following two data files are provided: us-10m.json – containing state boundaries, and
losses2015_transformed.csv – containing the 2015 indemnities per state.
